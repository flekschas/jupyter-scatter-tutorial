# Jupyter Scatter Tutorial

![jupyter-scatter demo](https://user-images.githubusercontent.com/932103/223292112-c9ca18b9-bc6b-4c3b-94ac-984960e8f717.gif)


:wave: Welcome! Here you will find the notebooks for the **jupyter-scatter** tutorial, presented at [SciPy 2023](https://cfp.scipy.org/2023/talk/AXSVZ3/). These notebooks offer an in-depth guide to interactive scatter plot visualizations using [`jupyter-scatter`](https://github.com/flekschas/jupyter-scatter). Specifically, the tutorial covers

1. [How to get started with Jupyter Scatter and visualize medium to large-scale datasets as interactive scatter plots.](1-Getting-Started.ipynb)
2. [How to compose and link/synchronize multiple scatter plots](2-Composing-Linking-Scatter-Plots.ipynb)
3. How to integrate Jupyter Scatter with other widgets to build bespoke interfaces for:
   1. [Exploring LLM-based sentence embeddings](3-LLM-Sentence-Embedding.ipynb)
   2. [Comparing multiple embedding method of the Fashion MNIST dataset](3-Fashion-MNIST.ipynb)
   3. [Browsing genomic data with HiGlass and loci embeddings](3-Genomics.ipynb)
   4. [Comparing a pair of single-cell embeddings by their label abundance differences](3-Comparative-Single-Cell-Embeddings.ipynb)

> **Note**
>
> The accompanying [slides from my SciPy '23 talk are available at Speaker Deck](https://speakerdeck.com/flekschas/interactive-exploration-of-large-scale-datasets-with-jupyter-scatter).

## Run the Tutorial

#### Online

If you have a Google/Gmail account, you can Run this tutorial from your browser using Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flekschas/jupyter-scatter-tutorial/blob/main/notebooks/Index.ipynb).

#### Locally

To run the notebook locally we recommend setting up a custom environment using [hatch](https://github.com/pypa/hatch) as follows:

```sh
hatch shell
```

Finally, you can now run the notebooks with:

```sh
jupyterlab
```

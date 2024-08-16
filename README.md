# Jupyter Scatter Tutorial

<p float="center">
   <a href="https://www.youtube.com/watch?v=RyC5ixtQG-Q">
        <img
         width="auto"
         height="320px"
         src="https://github.com/flekschas/jupyter-scatter-tutorial/blob/2a125926ed49fad4f14888b43f95979b0d92ce96/teaser.gif"
         alt="SciPy 2023 Talk"
        >
   </a>
</p>

:wave: Welcome! Here you will find the notebooks for the **Jupyter Scatter** tutorial, first presented at [SciPy 2023](https://cfp.scipy.org/2023/talk/AXSVZ3/). These notebooks offer an in-depth guide to interactive scatter plot visualizations using [`jupyter-scatter`](https://github.com/flekschas/jupyter-scatter). Specifically, the tutorial covers

1. [How to get started with Jupyter Scatter and visualize medium to large-scale datasets as interactive scatter plots.](notebooks/1-Getting-Started.ipynb)
2. [How to compose and link/synchronize multiple scatter plots](notebooks/2-Composing-Linking-Scatter-Plots.ipynb)
3. How to integrate Jupyter Scatter with other widgets to build bespoke interfaces for:
   1. [Exploring LLM-based sentence embeddings](notebooks/3-LLM-Sentence-Embedding.ipynb)
   2. [Comparing multiple embedding method of the Fashion MNIST dataset](notebooks/3-Fashion-MNIST.ipynb)
   3. [Browsing genomic data with HiGlass and loci embeddings](notebooks/3-Genomics.ipynb)
   4. [Comparing a pair of single-cell embeddings by their label abundance differences](notebooks/3-Comparative-Single-Cell-Embeddings.ipynb)
4. How to use the tooltip feature, introduced in `v0.15.0` (Added after the SciPy 2023):
   1. [Tooltip with text previews for the LLM-based sentence embeddings](notebooks/4-Tooltip-LLM-Sentence-Embedding.ipynb)
   2. [Tooltip with image previews for the Fashion MNIST embedding](notebooks/4-Tooltip-Fashion-MNIST.ipynb)
   3. [Tooltip for a single-cell embededding](notebooks/4-Tooltip-Single-Cell-Embeddings.ipynb)
   4. [Tooltip with audio previews for Google's Magenta Nsynth dataset](notebooks/4-Tooltip-Google-Nsynth.ipynb)
5. How to add features to Jupyter Scatter composition with other Jupyter Widgets (Added after the SciPy 2023):
   1. [Search](notebooks/5-Search.ipynb)

> **Note**
>
> You can find my [SciPy '23 talk on YouTube](https://www.youtube.com/watch?v=RyC5ixtQG-Q) and the accompanying [slides at Speaker Deck](https://speakerdeck.com/flekschas/interactive-exploration-of-large-scale-datasets-with-jupyter-scatter).

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

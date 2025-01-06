# Dazbo's Python Jupyter Demos

This is simply a collection of jupyter notebooks, which I will use to demonstrate concepts and ideas. They are intended to be used alongside articles which I tend to publish in one of these locations:

- [Dazbo on Medium](https://medium.com/@derailed.dash)
- [Dazbo's Advent of Code Walkthroughs and Python Learning Resource](https://aoc.just2good.co.uk/)

## Installing Conda for Package Management

Let's start by installing Conda:

```bash
# Create the env
export JUPYTER_CONDA_ENV="jupyter-conda-env"
conda create --name $JUPYTER_CONDA_ENV
conda activate $JUPYTER_CONDA_ENV

# Install packages
conda install -y -c conda-forge python jupyter jupyterlab

# Save the configuration
conda env export > $JUPYTER_CONDA_ENV.yml
```

Or we could create our environment from an existing configuration file:

```bash
conda env create -f $JUPYTER_CONDA_ENV.yml
```

## Guidance for Running Jupyter Notebooks

If you don't know much about Jupyter notebooks, then I suggest you start with my article [here](https://medium.com/python-in-plain-english/five-ways-to-run-jupyter-labs-and-notebooks-23209f71e5c0), which covers:

- The value and point of Jupyter notebooks
- Good use cases for Jupyter notebooks
- Several ways to run the notebooks
- How to run your own - or someone else's notebooks (like the ones in this repo) - quickly and easily, _for free_ in [Google Colab](https://colab.research.google.com/).

## Demo List

**This is work-in-progress.  Content coming soon!**

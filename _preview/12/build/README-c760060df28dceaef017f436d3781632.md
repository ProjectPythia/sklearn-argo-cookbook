<img src="thumbnail.png" alt="thumbnail" width="300"/>

# Scikit-learn on Argo Observations

[![nightly-build](https://github.com/song-sangmin/sklearn-argo/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/song-sangmin/sklearn-argo/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/song-sangmin/sklearn-argo/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/808693731.svg)](https://zenodo.org/badge/latestdoi/808693731)

This Project Pythia Cookbook covers two objectives:

1. Accessing publicly available, quality-controlled [Biogeochemical-Argo](https://biogeochemical-argo.org/) ocean observations
2. Demonstrating uses of [scikit-learn](https://scikit-learn.org/), a powerful Python package for machine learning.


## Motivation

This cookbook provides an overview of how to use python to access Argo oceanographic data and how to use sklearn to perform machine learning analyses. Argo is a global observatory of _in situ_ robots that autonomously sample the ocean interior. It is an international collaborative effort, and provides a treasure trove of high quality, open-source data. However, there are many different ways to access Argo data, which can get confusing for users. This cookbook highlights some basic workflows to access and work with Argo data. 

## Authors

[Song Sangmin](@song-sangmin), [Michael Chen](@mchen96).

### Contributors

<a href="https://github.com/song-sangmin/sklearn-argo/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=song-sangmin/sklearn-argo" />
</a>

## Structure

This cookbook is broken up into two main sections. 

1. Argo Foundations
2. Scikit-learn Workflows

### Section 1: Argo Foundations

This section contains two notebooks. argo-introductions.ipynb provides an overview of the Argo program, what kind of data are available, and how the data are structured. The argo-access.ipynb provides an overview of several methods to retrieve Argo data.

### Section 2: Scikit-learn Workflows

This section provides an overview of workflows using the sklearn package to conduct machine learning analyses on Argo data. The notebooks provide workflows on running regression and clustering (under construction) analyses.

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/cookbook-example` repository:

   ```bash
    git clone https://github.com/ProjectPythia/cookbook-example.git
   ```

1. Move into the `cookbook-example` directory
   ```bash
   cd cookbook-example
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate cookbook-example
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```

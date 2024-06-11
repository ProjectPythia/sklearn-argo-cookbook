<img src="thumbnail.png" alt="thumbnail" width="300"/>

# Scikit-learn with Argo Observations Cookbook

[![nightly-build](https://github.com/song-sangmin/sklearn-argo/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/song-sangmin/sklearn-argo/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/song-sangmin/sklearn-argo/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/808693731.svg)](https://zenodo.org/badge/latestdoi/808693731)

This Project Pythia Cookbook covers two objectives:

1. Accessing publicly available, quality-controlled [Biogeochemical-Argo](https://biogeochemical-argo.org/) ocean observations
2. Demonstrating uses of [scikit-learn](https://scikit-learn.org/), a powerful Python package for machine learning.


## Motivation

(Add a few sentences stating why this cookbook will be useful. What skills will you, "the chef", gain once you have reached the end of the cookbook?)

## Authors

[Song Sangmin (@song-sangmin), [Second Author](@second-author), etc. _Acknowledge primary content authors here_

### Contributors

<a href="https://github.com/song-sangmin/sklearn-argo/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=song-sangmin/sklearn-argo" />
</a>

## Structure

(State one or more sections that will comprise the notebook. E.g., _This cookbook is broken up into two main sections - "Foundations" and "Example Workflows."_ Then, describe each section below.)

This cookbook is broken up into __ sections: 

1. Accessing BGC-Argo data with Argopy
2. Applying scikit-learn to prepare data for machine learning
3. Using sckikit-learn to develop regression models (e.g. RFR, XGBoost)

### Section 1: Accessing BGC-Argo ( Replace with the title of this section, e.g. "Foundations" )

(Add content for this section, e.g., "The foundational content includes ... ")

### Section 2: Scikit-learn ( Replace with the title of this section, e.g. "Example workflows" )

(Add content for this section, e.g., "Example workflows include ... ")

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

# xmACIS2Py Cookbook

<img src="thumbnails/thumbnail.png" alt="thumbnail" width="300"/>

[![nightly-build](https://github.com/edrewitz/xmacis2py-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/xmacis2py-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/xmacis2py-cookbook/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18332254.svg)](https://doi.org/10.5281/zenodo.18332253)


## Motivation

This cookbook teaches users how to download and analyze xmACIS2 data in Python.

xmACIS2 is a popular tool among meteorologists for analyzing weather station data and comparing this data to climate normals and/or records. 

Users will develop a basic understanding of working with ACIS2 data in the form of a Pandas.DataFrame in Python.

Users will also be able to learn how to use xmACIS2Py to create various types of graphical summaries of the data. 

## Authors

[Eric J. Drewitz](https://github.com/edrewitz)

### Contributors

<a href="https://github.com/ProjectPythia/xmacis2py-cookbook/graphs/contributors">
  <img src="https://avatars.githubusercontent.com/u/101157849?v=4" width="100" height="100"/>
</a>

## Structure

This cookbook is a combination of two example notebooks ***xmacis2py_analysis.ipynb*** and ***xmacis2py_graphics.ipynb***.

### Foundations

The foundational content includes the:

- Data Access & Analysis with xmACIS2Py
- Graphical Summary Creation with xmACIS2Py

### Example Workflows

1) Data Access & Analysis example workflows in *xmacis2py_analysis.ipynb* demonstrate how to download ACIS2 data and perform various analyses on the data.
2) Graphical Summary Creation example workflows in *xmacis2py_graphics.ipynb* demonstrate how to create a medley of graphical summaries of the data. 

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
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter).

Note, not all Cookbook chapters are executable. If you do not see
the rocket ship icon, such as on this page, you are not viewing an
executable book chapter.


### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/xmacis2py-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/xmacis2py-cookbook.git
   ```

1. Move into the `cookbook-example` directory
   ```bash
   cd xmacis2py-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate xmacis2py-cookbook-dev
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```

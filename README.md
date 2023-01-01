# 3D models from geological maps

Welcome. In this repository you will find a group of geologic maps that we have converted into 3D geological models using the geo-modelling tool GemPy (https://www.gempy.org). 

# Clone the repository

The best way to work with the resource is to clone this repository. This saves all material to your local machine. It behaves almost like a copy.
1. Open a terminal.
2. Navigate to the folder where you would like to store the local copy of the repository. (`cd <foldername>`)
3. Press the green button 'Code' on the right hand side and copy the path in the Clone section.
4. Execute the terminal command `git clone <fill in path here>`.
5. Now you can start working with the resource files. They are saved in the folder you chose in step 2.

# Install required libraries

In order to create the models from the geological maps, you will need to install the following libraries/programs in a new anaconda environment. This can be done in the Anaconda prompt or a terminal following the steps below:

## For Windows

### Create and activate a new environment

conda create -n geomaps python==3.9

conda activate geomaps

### Install Jupyter Notebook

conda install -c conda-forge jupyter

### Install PyGeos, GeoPandas and Rasterio

conda install -c conda-forge pygeos 

conda install -c conda-forge geopandas 

conda install -c conda-forge rasterio

### Install PyVista 

conda install -c conda-forge pyvista

conda install -c conda-forge pyvistaqt

### Install Theano

conda update --all

conda install libpython

conda install m2w64-toolchain

conda install git

conda install -c conda-forge pygpu

pip install theano

### Install GemPy and GemGIS

pip install gempy

pip install gemgis

conda install mkl-service

## For macOS

### Create and activate a new environment

conda create -n geomaps python==3.8

conda activate geomaps

### Install Jupyter Notebook

conda install -c conda-forge jupyter

### Install PyGeos, GeoPandas and Rasterio

conda install -c conda-forge pygeos

conda install -c conda-forge geopandas

conda install -c conda-forge rasterio

### Install PyVista

conda install -c conda-forge pyvista

conda install -c conda-forge pyvistaqt

### Install GemPy and GemGIS

pip install gempy

pip install gemgis

conda install mkl-service

## Check the installation

Launch Jupyter Notebook from the new geomaps environment. Create a new notebook and enter the following commands in a code cell:

import rasterio

import geopandas as gp

import gempy as gp

import gemgis as gg

Run the cell. If the installation is fine, there shouldn't be any errors.

# Contact

If any questions, please contact me at [nestor.cardozo@uis.no](mailto:nestor.cardozo@uis.no)
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

In order to create the models from the geological maps, you will need to install the following libraries/programs in a new anaconda environment. This can be done in a terminal following the steps below:

### Create and activate a new environment

conda create -n geomaps python==3.10

conda activate geomaps

### Install gempy

### Windows

conda install aesara

pip install gempy

### macOS

pip install gempy

### Install gemgis

pip install gemgis

### Install gdal

conda install gdal

### Install Jupyter Notebook

conda install jupyter

# Check the installation

### Launch Jupyter Notebook 

jupyter notebook

### Create a new notebook and in a code cell write these lines:

import rasterio

import geopandas as gpd

import gempy as gp

import gemgis as gg

### Run the cell 

There shouldn't be any errors.

# Contact

If any questions, please contact me at [nestor.cardozo@uis.no](mailto:nestor.cardozo@uis.no)
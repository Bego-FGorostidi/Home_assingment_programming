# Home Assignment Programming

## Description
This project contains a Jupyter notebook that performs various tasks related to the analysis of FMRI data for musicians, including data import, visualization, and histogram plotting.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Contributing](#contributing)
4. [Authors and Acknowledgments](#authors-and-acknowledgments)

## Installation
- Data is imported from Nylearn, including anatomical (structural FMRI) and functional (uniformity test) data for musicians.
- Necessary libraries (os, glob, nilearn, nibabel, and matplotlib) are necessary.
    - You can install these libraries using conda: ```bash conda install os glob nilearn nibabel matplotlib

## Usage
- The code locates FMRI data files on the user's computer based on file extensions and names.

  ## Visualizing the Data:
    - Functional data is plotted on top of anatomical scans using nilearn.plotting.plot_stat_map.
    - The visualization includes brain areas activated in musicians, displayed with specific coordinates and color mapping.

  ## Plotting a Histogram:
    - The functional MRI data file is loaded using the nibabel library.
    - Voxel activation values are extracted, and only positive values (representing brain activation regions) are selected.
    - A histogram of the positive values is plotted using matplotlib, showing the distribution of voxel intensities.

## Contributing
Please feel free to submit issues and pull requests. All contributions are welcome.

## Authors and Aknowledgments
Author: Bego-FGorostidi
Special thanks to Mattias Mau, Anna Harmelen and Karla Tann

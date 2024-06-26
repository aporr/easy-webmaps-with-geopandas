# Quick and Easy Standalone Webmaps Using GeoPandas

As presented at the June 2024 NNIP Idea Showcase.

See additional details in `easy-webmaps-with-geopandas.ipynb`.

## Abstract

Lots of great third-party platforms are available which allow users to create interactive webmaps to present spatial data including ArcGIS Online, Google Maps, and Mapbox.  These services are appropriate for many use cases, however some situations may warrant a standalone webmap that is not reliant on a third party platform.  Such situations might include budget constraints, special access control requirements, special user interface requirements, the desire to package the content or implement version control, or the need to access the webmap in an environment without internet access.  In such cases, it is possible to develop a standalone webmap from scratch using frameworks such as Leaflet or OpenLayers, however this can be time consuming, and it requires knowledge of Javascript programming and web server administration. Luckily, the excellent [GeoPandas](https://geopandas.org/) package for [Python](https://www.python.org/) provides a means of producing basic webmaps that is more accessible to Python programmers and avoids much of the complexity and tedium of building the webmap from scratch. This presentation demonstrates how to automatically produce an interactive standalone webmap using vehicle access data from U.S. Census API and bike infrastructure data from an ArcGIS REST API using GeoPandas. The workflow is implemented using [Jupyter](https://jupyter.org/) to allow for convenient prototyping of the webmap prior to production.  The presentation also covers how to make the webmap accessible to the public using [GitHub Pages](https://pages.github.com/). 

Attendee familiarity with Python, Jupyter, and GitHub is helpful but not required.

## Repository contents

  - **easy-webmaps-with-geopandas.ipynb** - [Jupyter notebook](https://jupyter.org/) that contains the narrative content for the presentation and documented Python code
  - **easy-webmaps-with-geopandas.html** - HTML export of the Jupyter notebook that is viewable in a web browser
  - **requirements.txt** - Requirements file used with [pip](https://pip.pypa.io/en/stable/cli/pip_install/#pip-install) to install required libraries
  - **webmap.html** - Exported standalone webmap to be published via GitHub Pages
  - **images** - Screenshots and other images used in the notebook
  
## Getting Started

  1. Install a recent version of Python 3.x
  1. In a terminal, navigate to the directory that contains this README.md file.  File paths referenced below are relative to this directory.
  1. Install required packages as follows: `pip install -r requirements.txt`
  1. Launch Jupyter Lab as follows: `jupyter lab`
  1. Open the Jupyter notebook, `./easy-webmaps-with-geopandas.ipynb`
  1. Execute the cells in the notebook.  Although it is possible to run the entire notebook all at once, consider stepping through the notebook one cell at a time so that you can understand what each one is doing.
  1. Open the file `webmap.html` in a modern web browser to see the standalone webmap.  It was tested in Google Chrome.

## License

[Creative Commons Attribution-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-sa/4.0/)

Copyright 2024 Mid-Ohio Regional Planning Commission

You are free to:
  - Share — copy and redistribute the material in any medium or format
  - Adapt — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:
  - Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
  - ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
  - No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
  

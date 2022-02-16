# SciPy 2022 Talk Submission - Geospatial analysis and visualization with PyGMT

## Prompt

### Short Summary Prompt

The brief description which will appear in the online program and give attendees a basic sense of your talk. This should be around 100 words or less.

### Abstract Prompt

Your placement in the program will be based on reviews of your abstract. This should be a roughly 500 word outline of your presentation. This outline should concisely describe software of interest to the SciPy community, tools or techniques for more effective computing, or how scientific Python was applied to solve a research problem. A traditional background/motivation, methods, results, and conclusion structure is encouraged but not required. Links to project websites, source code repositories, figures, full papers, and evidence of public speaking ability are encouraged.

## Submission

### Title

Geospatial analysis and visualization with PyGMT

### Authors

*Meghan Jones
Wei Ji Leong
Leonardo Uieda

### Short Summary

Spatial data are ubiquitous across the Earth, Ocean, Geo & Atmospheric Sciences. PyGMT is an open-source Python package that specializes in processing and plotting spatial data. We will provide a demonstration of the latest developments in PyGMT, including new features for sampling, projecting, filtering, and analyzing data along with enhancements for visualizing tabular and raster datasets. We will also discuss our progress towards a more Pythonic API through simpler arguments and more informative exceptions. Lastly, we will present ways to get involved with the PyGMT community, including contributing feedback, writing documentation and/or code, and participating in PyGMT events.

### Abstract

PyGMT is an open-source Python library for processing geospatial and geophysical data and making publication quality maps and figures. PyGMT complements other tools in the scientific Python ecosystem by providing functionality for processing and plotting both vector and raster data stored as NumPy arrays, Pandas DataFrames, Xarray Datasets and DataArrays, and/or GeoPandas GeoDataFrames, in addition to standard file formats like ASCII files, NetCDF files, and GeoTiffs. PyGMT provides these capabilities as a Pythonic interface to the Generic Mapping Tools (GMT), which is a widely-used, feature-rich command-line toolbox with over 30 years of continuous development.

The initial prototype for PyGMT was presented at SciPy 2017. The creation of an object-oriented API and its support for interactive display in Jupyter notebooks were presented at SciPy 2018. Since 2018, PyGMT has seen its first official release (May 03, 2020), four additional minor releases following semantic versioning (v0.6.0 is anticipated in March 2022), and a transition to community driven development with five new maintainers and over 40 new contributors. The five minor releases have included 22 new functions for processing tabular and raster data, 17 new functions for data visualization, improved support for geospatial metadata through a custom xarray.DataArray extension, the addition of a comprehensive set of gallery examples and tutorials, as well as numerous enhancements and maintenance improvements. We will provide a demonstration of the latest features and enhancements, solicit feedback on recent design decisions, provide an overview of PyGMT's community structure and development workflows, and encourage participation in PyGMT development.

In the first section of the talk, we will provide a live demonstration of new features for data processing and visualization using an interactive Jupyter notebook hosted on Binder. We will provide a quick overview of new functions for processing tabular and raster data, including features for gridding data (e.g., blockmean, nearneighbor, surface), functions for forward and inverse projections (e.g., project, grdproject), and functions for selecting, clipping, and transforming data (e.g., select, grdclip, grdcut, grdsample). We will also highlight data visualization examples relevant to different disciplines, such as projected satellite imagery, a Hovmöller diagram, and a cross section showing earthquake focal mechanisms.

We will highlight opportunities to help guide PyGMT development, in particular the adoption of more Pythonic syntax for GMT arguments. While the developers and community have long-discussed the issue of terse, cryptic GMT arguments, recent PyOpenSci reviews highlighted the need to focus developer efforts on these user experience components. We currently have two open pull requests that propose convenience classes as a simplification for GMT arguments. One proposal introduces classes for specifying map projections and another introduces a convenience class for specifying pen styling attributes. We will present examples using the v0.5.0 syntax as well as our progress towards Pythonic syntax and describe opportunities for feedback and contributions through GitHub issues and PyGMT sprints.

Lastly, we will introduce the audience to our community forum as a place for Q&A, give a brief overview of some 'good first issues', and encourage people to participate in a PyGMT sprint and our quarterly community meetings.

PyGMT repository: https://github.com/GenericMappingTools/pygmt
PyGMT documentation: https://www.pygmt.org/
PyGMT Q&A: https://forum.generic-mapping-tools.org/c/questions/pygmt-q-a/11
YouTube Channel: https://www.youtube.com/c/TheGenericMappingTools
PyGMT Community Meeting Playlist: https://www.youtube.com/playlist?list=PL3GHXjKa-p6VsIqW_ffp7ZK0lXYDfXYMA
2021 AGU Presentation with Binder link and Jupyter notebooks: https://github.com/meghanrjones/agu2021
Quick Intro to Plotting with PyGMT (created for AGU Fall Meeting 2021): https://www.youtube.com/watch?v=Kb6TYvZcI_c

### Keywords (at least three)

Geospatial
Visualization
Raster
Vector
Earth
Ocean
Geophysics

### Type of Submission (talk or poster)

Talk

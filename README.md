# SciPy 2022 Talk Submission - Geospatial analysis and visualization with PyGMT

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/maxrjones/scipy2022/HEAD?labpath=pygmt_demo.ipynb)

|    |Info|
|---:|:---|
| Conference | [SciPy 2022](https://www.scipy2022.scipy.org/) |
| Track | Earth, Ocean, Geo, & Atmospheric |
| Authors | [Max Jones](https://github.com/maxrjones), [Wei Ji Leong](https://github.com/weiji14), [Leonardo Uieda](http://www.leouieda.com/) |
| Date | July 13, 2022 |
| Time | 10:55 - 11:25 UTC-05:00 |
| Where | Room 204 |

## Short Summary

Spatial data are ubiquitous across the Earth, Ocean, Geo & Atmospheric Sciences. PyGMT is an open-source Python package
that specializes in processing and plotting spatial data. We will provide a demonstration of the latest developments in
PyGMT, including new features for sampling, projecting, filtering, and analyzing data along with enhancements for
visualizing tabular and raster datasets. We will also discuss our progress towards a more Pythonic API through simpler
arguments and more informative exceptions. Lastly, we will present ways to get involved with the PyGMT community,
including contributing feedback, writing documentation and/or code, and participating in PyGMT events.

## Abstract

PyGMT is an open-source Python library for processing geospatial and geophysical data and making publication quality
maps and figures. PyGMT complements other tools in the scientific Python ecosystem by providing functionality for
processing and plotting both vector and raster data stored as NumPy arrays, Pandas DataFrames, Xarray Datasets and
DataArrays, and/or GeoPandas GeoDataFrames, in addition to standard file formats like ASCII files, NetCDF files, and
GeoTiffs. PyGMT provides these capabilities as a Pythonic interface to the Generic Mapping Tools (GMT), which is a
widely-used, feature-rich command-line toolbox with over 30 years of continuous development.

The initial prototype for PyGMT was presented at SciPy 2017. The creation of an object-oriented API and its support for
interactive display in Jupyter notebooks were presented at SciPy 2018. Since 2018, PyGMT has seen its first official
release (May 03, 2020), four additional minor releases following semantic versioning (v0.6.0 is anticipated in March
2022), and a transition to community driven development with five new maintainers and over 40 new contributors. The
five minor releases have included 22 new functions for processing tabular and raster data, 17 new functions for data
visualization, improved support for geospatial metadata through a custom xarray.DataArray extension, the addition of a
comprehensive set of gallery examples and tutorials, as well as numerous enhancements and maintenance improvements. We
will provide a demonstration of the latest features and enhancements, solicit feedback on recent design decisions,
provide an overview of PyGMT's community structure and development workflows, and encourage participation in PyGMT
development.

In the first section of the talk, we will provide a live demonstration of new features for data processing and
visualization using an interactive Jupyter notebook hosted on Binder. We will provide a quick overview of new functions
for processing tabular and raster data, including features for gridding data (e.g., blockmean, nearneighbor, surface),
functions for forward and inverse projections (e.g., project, grdproject), and functions for selecting, clipping, and
transforming data (e.g., select, grdclip, grdcut, grdsample). We will also highlight data visualization examples
relevant to different disciplines, such as projected satellite imagery, a Hovmöller diagram, and a cross section
showing earthquake focal mechanisms.

We will highlight opportunities to help guide PyGMT development, in particular the adoption of more Pythonic syntax for
GMT arguments. While the developers and community have long-discussed the issue of terse, cryptic GMT arguments, recent
PyOpenSci reviews highlighted the need to focus developer efforts on these user experience components. We currently
have two open pull requests that propose convenience classes as a simplification for GMT arguments. One proposal
introduces classes for specifying map projections and another introduces a convenience class for specifying pen styling
attributes. We will present examples using the v0.5.0 syntax as well as our progress towards Pythonic syntax and
describe opportunities for feedback and contributions through GitHub issues and PyGMT sprints.

Lastly, we will introduce the audience to our community forum as a place for Q&A, give a brief overview of some
'good first issues', and encourage people to participate in a PyGMT sprint and our quarterly community meetings.

- [PyGMT repository](https://github.com/GenericMappingTools/pygmt)
- [PyGMT documentation](https://www.pygmt.org/)
- [PyGMT Q&A](https://forum.generic-mapping-tools.org/c/questions/pygmt-q-a/11)
- [YouTube Channel](https://www.youtube.com/c/TheGenericMappingTools)
- [PyGMT Community Meeting Playlist](https://www.youtube.com/playlist?list=PL3GHXjKa-p6VsIqW_ffp7ZK0lXYDfXYMA)
- [2021 AGU Presentation with Binder link and Jupyter notebooks](https://github.com/maxrjones/agu2021)
- [Quick Intro to Plotting with PyGMT (created for AGU Fall Meeting 2021)](https://www.youtube.com/watch?v=Kb6TYvZcI_c)

## Keywords (at least three)

- Geospatial
- Visualization
- Raster
- Vector
- Earth
- Ocean
- Geophysics

## Type of Submission (talk or poster)

Talk

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
This content is licensed under a
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

All source code is distributed under the [BSD 3-clause License](https://opensource.org/licenses/BSD-3-Clause).

## Acknowledgements

The development of PyGMT has been supported by NSF grants
[OCE-1558403](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1558403) and
[EAR-1948603](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1948602).
M.R. Jones has been supported by [EAR-1948602](https://nsf.gov/awardsearch/showAward?AWD_ID=19486020).
PyGMT has benefited from the contributions of [numerous developers](https://github.com/GenericMappingTools/pygmt/blob/main/AUTHORS.md)
and [community members](https://forum.generic-mapping-tools.org/).

The data visualization examples are based on the [GMT for Geodesy seismology section](https://github.com/GenericMappingTools/gmt-for-geodesy/tree/main/5_seismology)
and the [PyGMT roads gallery example](https://www.pygmt.org/latest/gallery/lines/roads.html#sphx-glr-gallery-lines-roads-py). The data
processing examples are based on the [EGU 2022 PyGMT short course LiDAR tutorial](https://www.generic-mapping-tools.org/egu22pygmt/lidar_to_surface.html)
and the [PyGMT grid equalization tutorial](https://www.pygmt.org/latest/tutorials/advanced/grid_equalization.html#sphx-glr-tutorials-advanced-grid-equalization-py).

Data sources are listed in the [PyGMT demo](#pygmt_demo.ipynb).

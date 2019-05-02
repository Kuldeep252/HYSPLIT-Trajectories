# Visualizing Hysplit Trajectories
The Hybrid Single Particle Lagrangian Integrated Trajectory Model also known as HYSPLIT is a complete system for computing simple air parcel trajectories, as well as complex transport, dispersion, chemical transformation, and deposition simulations.The GUI of this NOAA model is tcl based with limited options and it often is rigid.To remove this limitation python can be employed to create beautiful Visualizations.This Project Aims to introduce the vizualization of Backtrajectories by using python.
## Prerequisite
Before running the code it is necessary to parse the HYSPLIT output file to extract useful information.The given code uses csv file extracted from raw data and then used with pandas.
## Dependencies
1 [Pandas](https://pandas.pydata.org/pandas-docs/stable/)
2 [Matplotlib](https://matplotlib.org/contents.html)
## Use Cases
1 The plotted trajectories can easily be converted to shp files using [PyShp](https://pypi.org/project/pyshp/) library which can then be used with GIS systems.
2 The trajectories can also be plotted in 3D area by use of Axes3D.plot function

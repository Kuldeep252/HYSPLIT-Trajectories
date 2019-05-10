# Visualizing Hysplit Trajectories
The Hybrid Single Particle Lagrangian Integrated Trajectory Model also is known as HYSPLIT is a complete system for computing simple air parcel trajectories, as well as complex transport, dispersion, chemical transformation, and deposition simulations. The GUI of this NOAA model is "Tcl" based with limited options and it often is rigid in its functionality. To remove this limitation python can be employed to create beautiful Visualizations. This Project aims to introduce a simple visualization of Backtrajectories by using python. Click [here](https://github.com/Kuldeep252/HYSPLIT-Trajectories/blob/master/backtraj_plotting.ipynb) to access the code.
## Prerequisite
Before running the code it is necessary to parse the HYSPLIT output file to extract the useful information. The given code uses csv type file extracted from raw data and then used with pandas.
## Dependencies
1 [Pandas](https://pandas.pydata.org/pandas-docs/stable/)
2 [Matplotlib](https://matplotlib.org/contents.html)
## Use Cases
1 The plotted trajectories can easily be converted to shp files using [PyShp](https://pypi.org/project/pyshp/) library which can then be used with GIS systems.
2 The trajectories can also be plotted in 3D area by use of Axes3D.plot function

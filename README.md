# Yeast-Chromosome-Dynamic-Simulaion

The simulation provides numerical model which simulates the dynamics of chromosomes in the nucleus of budding yeast. 

The simulation pipeline uses DataTank, a numerical working environment as user interphase.  DataTank is developed by David Adelsteinsson and researchers can go to the following website for license and download https://www.visualdatatools.com/DataTank/. DataTank provides powerful visualization and analysis tools that are compatible with various types of data. DataTank employs embedded data-oriented functions and is itself a visual programming environment. Programs created by standard utilities or the built-in C++ framework can be launched in DataTank for numerical purposes. The simulation results are parse by DataTank in real time for downstream data visualization and analyses. 

1.	Yeast_Chromosome_Dynamics_Simulator.tank—The main file for the simulation pipeline contains 1). The interface to enter input parameters and settings. 2). The port connecting to simulation program. 3). Visualization module. 4). Modules for stochastic analyses.

2.	Microscope_Simulator.tank—Microscope simulator pipeline functions to convert numerical results to experimental microscope images. This enables direct statistical comparison of geometries between simulated chromosomes and experimental observations.

3.  Community_Detection_Analysis.tank—The community detection pipeline applies a multilayer modularity optimization process to detect community behavior during chromosomal interactions in simulation results.

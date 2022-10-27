Kay_lab_python_code
A repository of basic python code as a resource for the Kay lab group. Last updated: October 2022

List of files and their functionality
vertical_cross_section_example.ipynb
Example of plotting a CESM variable in lat/height space. Interpolates from CESM sigma-hybrid coordinates to pressure coordinates. Requires PyNGL installation. Please see CAM_vertical_interpolation_python_readme.pdf (below) for instructions.

This notebook also contains examples of extracting CESM variables from NetCDF files, using dictionaries, 1-line for-loops, and plotting.
vertical_cross_section_example_dask.ipynb
Same as above but using DASK (i.e., multiple cheyenne nodes) to speed up the computation.
CAM_vertical_interpolation_python_readme.pdf
Instructions for installing PyNGL & utilizing the vertical cross-section python codes above. Also describes the process of pushing/pulling from Github to make changes to a repo.
output_netcdf_file.ipynb
A very simple example of loading in some CESM data and saving one timestep.
plot_cosp_scam_cam6.ipynb - Plots outputs (including COSP2) from the MPACE SCAM case - to be used for Arctic research and for COSP2 development
python_gotchas.ipynb - shows some gotchas for python programming
CERES-EBAF_plot_global_map_energy_balance.ipynb - Example of making a global map plot of data in netcdf format using cartopy (here data from CERES-EBAF)
regridding CESM sea ice to a lat-lon grid (contributed by Patricia)


To be added eventually...
XXX

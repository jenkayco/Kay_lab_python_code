# Kay_lab_python_code
A repository of basic python code as a resource for the Kay lab group.
Last updated: July 15, 2021

### List of files and their functionality
1. vertical_cross_section_example.ipynb   
*Example of plotting a CESM variable in lat/height space. Interpolates from CESM sigma-hybrid coordinates to pressure coordinates. Requires PyNGL installation. Please see CAM_vertical_interpolation_python_readme.pdf (below) for instructions.*   
*This notebook also contains examples of extracting CESM variables from NetCDF files, using dictionaries, 1-line for-loops, and plotting.*
2. vertical_cross_section_example_dask.ipynb   
*Same as above but using DASK (i.e., multiple cheyenne nodes) to speed up the computation.*
3. CAM_vertical_interpolation_python_readme.pdf   
*Instructions for installing PyNGL & utilizing the vertical cross-section python codes above. Also describes the process of pushing/pulling from Github to make changes to a repo.*
4. output_netcdf_file.ipynb  
*A very simple example of loading in some CESM data and saving one timestep.*
5. plot_cosp_scam_cam6.ipynb  
*Plots outputs (including COSP2) from the MPACE SCAM case - to be used for Arctic research and for COSP2 development*
6. python_gotchas.ipynb  
*shows some gotchas for python programming*

### To be added eventually... 
1. simple_CESM_spatial_plot_xarray.ipynb   
*Example of extracting and making a simple spatial plot with CESM data*
2. beautifying_spatial_plot_cartopy.ipynb   
*Making a plot publishing quality in cartopy.*

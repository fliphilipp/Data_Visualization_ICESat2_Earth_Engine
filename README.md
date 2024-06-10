# Data Visualization Tutorial, ICESat-2 Hackweek 2023

![teaser image](https://raw.githubusercontent.com/fliphilipp/images/main/nearshore-bathymetry.jpg)

By Philipp Arndt \
Scripps Institution of Oceanography, University of California San Diego \
Github: [@fliphilipp](https://github.com/fliphilipp) \
Contact: parndt@ucsd.edu

## Outline

- Discover some interesting ICESat-2 data by browsing [OpenAltimetry](https://openaltimetry.org/data/icesat2/)
- Get the data into a Jupyter Notebook
- Plot the data and overlay the ground track on a map
- Use Google Earth Engine to find the closest-in-time Sentinel-2 image that is cloud-free along ICESat-2's gound track
- Make a plot from ICESat-2 data and contemporaneous imagery in Jupyter/matplotlib
- Bonus material: Extract Sentinel-2 data onto the ICESat-2 ground track 

**Note from June 2024:** *OpenAltimetry has become very slow since it transitioned to being hosted at NSIDC. Also, some of the data products have become unavailable through the API (this prints as "request failed" for now). When this code runs, it is now unfortunately painfully slow. I am told that the OpenAltimetry/NSIDC teams are working on fixing this.*

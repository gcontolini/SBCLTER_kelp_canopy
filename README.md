# SBCLTER_kelp_canopy
Manipulating Santa Barbara Coastal Long Term Ecological Research kelp canopy area time series from Landsat. Data source: https://portal.edirepository.org/nis/mapbrowse?scope=knb-lter-sbc&identifier=74&revision=14

The raw NetCDF file from that source is too large (> 130 MB) to host in this GitHub repository. Therefore, the raw NetCDF data was downloaded and processed into a csv file on a local machine. The code to process the raw NetCDF file is commented early in the RMarkdown file, "kelp_canopy.Rmd". That csv was then uploaded to this repository (e.g., "kelp_canopy_output_ 2021-11-24.csv"). The date on the csv file reflects when the raw NetCDF data was processed and will change as new NetCDF data are available and processed. All products are derived from that csv file.

View HTML output here: https://rpubs.com/gcontolini/remote_sensing_report

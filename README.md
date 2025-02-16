These files allow raw data to be downloaded and plotted. 
https://xmacis.rcc-acis.org/ is temperature, precipitation, and snow data collected at stations nationwide and compiled by NOAA Regional Climate Data Centers.
The snippet here shows how to download data directly from xmacis.rcc-acis.org. The station used is the Matanuska Experiment Farm and Extension Center (station ID 505733)
Using this method is infinitely superior to downloading it from the other method - which is to download from the xmacis site as a pdf, convert the pdf to a csv or Excel, then spend hours getting one value in each column. The Excel download isn't clean.
This snippet can easily be adapted to update to a current date, change the station, or select only certain years.
Only Max and Min Temperatures were downloaded. The snippet can be adapted to download precip and/or snowfall and/or snowdepth.

Files are: code for downloading, code for downloading and creating plots, code for downloading and creating plots and automatically storing some in Tmax and Tmin folders in the base directory for easy viewing and use.

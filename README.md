# SOTC
Antarctic surface mass balance analysis for the annual state of the climate (SOTC) report. 

## To reproduce this analysis every year, follow the steps outlined below:
1. [Update](https://github.com/EricKeenan/download_MERRA2) your MERRA-2 atmospheric reanalysis record to include 1980 to the present. 
2. Calculate MERRA-2 monthly means from hourly data by using [Make_monthly_means.ipynb](https://github.com/EricKeenan/SOTC/blob/master/Make_monthly_means.ipynb).
3. Conduct analysis and save figures using [SOTC_AIS_SMB_MERRA_2.ipynb](https://github.com/EricKeenan/SOTC/blob/master/SOTC_AIS_SMB_MERRA_2.ipynb).

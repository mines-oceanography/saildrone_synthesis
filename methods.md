# Methods

- Data analysis was done in python notebooks using Xarray, Matplotlib, hvPlot, and numpy libraries.
- discuss SMODE, Saildrones, and the models used (what a numerical model is, what each model does)

Data analysis began with identifying potential fronts of interest. This was done with an interactive plot using the hvPlot library. We used sea surface temperature as our indicator, looking for gradients of at least 1˚C. Then, to verify the front, we looked at the $H_s$ signature to make sure the wave data was coherent and did not have sporadic variations. Once these checks were fulfilled, the start and end date, time, Saildrone ID, along-track distance, and any notes on the front were saved in a table. 
A secondary analysis was performed on all identified fronts of interest using a subplot function that plots the Saildrone SST and surface current speed against model data from the Navy Coastal Operational Model (NCOM), $H_s$ and $T_p$ plotted against model data from WAVEWATCH III, and the wind speed plotted against the fifth generation ECMWF atmospheric reanalysis (ERA-5).

## Results
- Saildrones can provide a comprehensive insight into submesoscale interactions with some limitations that can be accounted for with additional data from models
- We have a library of temperature fronts identified using the methods above, the analysis of these fronts provide an insight into the strengths and weaknesses of Saildrones
We have presented a case study of different wind, wave, and current interactions along submesoscale fronts recorded by Saildrones. Our analysis has provided an insight into the strengths and weaknesses of Saildrones. 
Saildrones provide a comprehensive insight into submesoscale interactions with minor limitations due to a lack of large-scale spatial coverage. This limitation can be accounted for with supplemental model data.


(content:methods:labels)=
# Methods

Data analysis began with identifying potential fronts of interest. This was done with an interactive plot using the hvPlot library. We used sea surface temperature as our indicator, looking for gradients of at least 1˚C. Then, to verify the front, we looked at the $H_s$ signature to make sure the wave data was coherent and did not have sporadic variations. Once these checks were fulfilled, the start and end date, time, Saildrone ID, along-track distance, and any notes on the front were saved in a table. 
A secondary analysis was performed on all identified fronts of interest using a subplot function that plots the Saildrone SST and surface current speed against model data from the Navy Coastal Operational Model (NCOM), $H_s$ and $T_p$ plotted against model data from WAVEWATCH III, and the wind speed plotted against the fifth generation ECMWF atmospheric reanalysis (ERA-5).

### An Example of Interactive Plot
```{iframe} https://github.com/mines-oceanography/saildrone_synthesis/blob/main/figures/sd_1062_interactive_plot.html
:width: 100%
:height: 500px

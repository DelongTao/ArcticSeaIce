# ArcticSeaIce
Repository contains scripts for plotting routines of Arctic sea ice and atmospheric parameters ```[Python]```.

######Under construction...

## Contact
Zachary Labe - [Research Website](http://sites.uci.edu/zlabe/) - [@ZLabe](https://twitter.com/ZLabe)

## Description

'plot_MinYears_JAXA.py' --
Bar graph of minimum Arctic sea ice extents over the 2002-present period. Comparison looks at the current sea ice extent versus the minimum years. Data is available by the Japan Aerospace Exploration Agency (JAXA) and through the [Arctic Data archive System (NiPR)](Japan Aerospace Exploration Agency).

`plot_SeaIceExtent_JAXA.py` --
Daily Arctic sea extent over the 2002-2016 (to-date) is available by the Japan Aerospace Exploration Agency (JAXA) and through the [Arctic Data archive System (NiPR)](Japan Aerospace Exploration Agency).

`plot_SeaIceConc_SSMIS.py` --
Daily Arctic sea concentration data is available through the [Ocean and Sea Ice SAF](http://osisaf.met.no/p/ice/) F-18 satellite. Data is provisional from the DMSP F-18 satellite as a result of F-17 satellite errors [(for more information)](https://nsidc.org/arcticseaicenews/2016/05/daily-sea-ice-extent-updates-resume-with-provisional-data/).

`plot_SIV_PIOMAS.py` --
Daily Arctic sea ice volume (SIV) is available through [PIOMAS (Zhang and Rothrock, 2003)](http://psc.apl.uw.edu/research/projects/arctic-sea-ice-volume-anomaly/) at the beginning of each month. Sea ice volume is available from 1979 to present and averaged over the entire Arctic. Gridded products are also [available](http://psc.apl.washington.edu/zhang/IDAO/). 

`plot_ZonalTAS_NCEP.py` --
Mean zonal surface temperatures over the Arctic Circle (north of 66°) through NCEP reanalysis. Data available using the [ESRL toolbox](http://www.esrl.noaa.gov/psd/cgi-bin/data/timeseries/timeseries1.pl). Grid cells are weighted and data available for yearly (January - to-date, monthly) time frames.

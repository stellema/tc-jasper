## tc-jasper

Analysis of the rainfall associated with Tropical Cyclone Jasper.


#### Commands
```
/g/data/xv83/dbi599/miniconda3/envs/unseen-processing/bin/fileio /g/data/xv83/agcd-csiro/precip/daily/precip-total_AGCD-CSIRO_r005_*_daily.nc /g/data/xv83/dbi599/tc-jasper/rx5day_AGCD-CSIRO_r005_1900-2023_A-JUN_daintree-river.nc --variables pr --spatial_agg weighted_mean --rolling_sum_window 5 --shapefile /g/data/xv83/dbi599/tc-jasper/shapefiles/daintree_river.shp --time_freq A-JUN --time_agg max --input_freq D --units_timing middle --reset_times --complete_time_agg_periods --verbose --time_agg_dates --units pr='mm day-1' --metadata_file /home/599/dbi599/unseen/config/dataset_agcd_daily.yml
```

# Cleaned Database

This folder contains all the cleaned and processed data, the data source files can be found in folder `db1_source/`. All the file namess in this folder obey the rule of `MARKET_AREA_CATEGORY.csv`. Readers can find their interested files quickly by activating the Github's file finder (Press `T`).

Current data are updated to `April 29, 2020`. After final release, the supporting team will implement daily updates to catch the latest situations.


## Electricity Data Field Description
All files are organized in a wide csv table.
- Field `date`: list all the date from 2017 to present. Format: `mm/dd/YYYY`
- Field `fuel`: only in generation mix dataset, represent the different fuel souce used by generators. Possible values: coal, gas, oil, nuclear, hydro, wind, solar, other, export. We harmonize all the different definitions in different electricity markets.
- Field `kind`: only in weather dataset, represent the type of measurement that is recorded in each corresponding row. Possible values:
dwpc, relh, sped, tmpc
- Field `HH:MM`: represent the hourly time slot. For example, items in the column 08:00 represent the recorded data of period 8AM to 9AM.

## COVID-19 Data Field Description
- Field `date`: list all the date from 1/23/2020 to present. Format: `mm/dd/YYYY`
- Field `accum_confirm`: Accumulated confirmed case number recorded at each date
- Field `new_confirm`: Newly confirmed case number of each date
- Field `infect_rate`: Infection ratio calculated at each date
- Field `accum_death`: Accumulated confirmed deth number recorded at each date
- Field `new_death`: Newly confirmed death number of each date
- Field `fatal_rate`: Fatal rate calculated at each date

## Visit Pattern to Point of Interests (POIs)
- Field `date`: list all the date from 12/30/2019 to present. Format: `mm/dd/YYYY`
- Field `Restaurant_Recreation`: Daily total number of visits to Restaurant and Recreation places
- Field `Grocery_Pharmacy`: Daily total number of visits to Grocery and Pharmacy places
- Field `Retail`: Daily total number of visits to Retail places

## Social Distancing
- Field `date`: list all the date from 01/01/2020 to present. Format: `mm/dd/YYYY`
- Field `completely_home_device_count_percentage`: percentage of devices that stay at home 24 hours out of all devices
- Field `median_home_dwell_time_percentage`: median proportion of home dwell time in one day
- Field `part_time_work_behavior_devices_percentage`: percentage of devices that go to workplaces for 3 to 6 hours out of all devices
- Field `full_time_work_behavior_devices_percentage`: percentage of devices that go to workplaces for more than 6 hours out of all devices
- Field `completely_home_device_count`: count of devices that stay at home 24 hours
- Field `device_count`: total count of devices
- Field `part_time_work_behavior_devices`: count of devices that go to workplaces for 3 to 6 hours
- Field `full_time_work_behavior_devices`: count of devices that go to workplaces for more than 6 hours


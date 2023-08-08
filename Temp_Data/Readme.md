Generate_different_temp_variables_hourly_data.html:
This code file that generating hourly data of each station from 1937-2022 for different variables:
Variables from humidity file will include
temperatures(time), float64 dewpoints(time), float64 slp(time), float64 vapor_pressure(time), float64 saturation_vapor_pressure(time), float64 wet_bulb_temperature(time), float64 specific_humidity(time), float64 relative_humidity(time)
Variables from heat_stress file will include
temperatures(time), float64 dewpoints(time), float64 windspeeds(time), float64 temperature_humidity_index(time), float64 wet_bulb_globe_temperature(time), float64 humidex(time), float64 apparent_temperature(time), float64 heat_index(time)

2. get_us_stations_data.html
This code file contains how to generate data that only inside the US. Using reverse_geocoder to get also county/city info based on lat/lon from file.

3. US_Heat_stress_file and US_humidity_file contains the path which easier for me to iterative all the files.
   
4. All the NC files path is under: /global/cfs/projectdirs/m1532/Projects_MVP/MET_OFFICE_CLIMATE_DATA/
For humidity is under: /global/cfs/projectdirs/m1532/Projects_MVP/MET_OFFICE_CLIMATE_DATA/HUMIDITY_data
For heat stress is under: /global/cfs/projectdirs/m1532/Projects_MVP/MET_OFFICE_CLIMATE_DATA/HEAT_STRESS_nc_data

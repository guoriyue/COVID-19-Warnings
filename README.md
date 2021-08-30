# Introduction to the Data of COVID-19 Hazard Aera Warning System

The Phase1, Phase2, Phase3 are in trainvalidtest.phase(1/2/3).json

data structure:
```
FeatureDict = {"Geographical": ["lng", "lat", "nearest_x3", "kavg_x4", "inrange_x7", "region_nearest_x5", "region_mean_x6"],
           "Temporal": ["nearest_date_x15", "nearest_date_kmin_x16", "nearest_date_kmean_x17", "nearest_date_region_x18"],
           "Demographic": ["mall", "market", "hospital", "apartment", "metro", "population", "population_density"],
           "Temperature": ["max_temperature", "min_temperature", "avg_temperature", "max_humidity", "min_humidity", "avg_humidity", 
                          "wind", "min_AQI", "max_AQI", "avg_AQI"],
           "LiveUpdate": ["local_confirm", "local_suspecte", "local_recover", "local_dead", "local_confirm_add",
                         "local_suspecte_add", "local_recover_add", "local_dead_add", "country_confirm",
                         "country_suspecte", "country_recover", "country_dead", "country_confirm_add",
                         "country_suspecte_add", "country_recover_add", "country_dead_add", "local_exist", "country_exist", "infection_rate"],
           "Epidemiologica": ["local_diffusion", "local_dispersion", "local_growthrate", "local_doublingtime",
                                "country_diffusion", "country_dispersion", "country_growthrate", "country_doublingtime",
                                "local_r0", "country_r0", "local_beta", "local_gamma", "country_beta", "country_gamma"],
           "Sociology": ["GDP", "GDP_per_capita", "medical_institution", "medical_staff", "mobility_by_land", "mobility_by_air", "aging_rate"]}
```

Acknowledgment:

http://lbsyun.baidu.com/

https://m.mp.oeeee.com/h5/pages/v20/nCovcase/

https://github.com/BlankerL/DXY-COVID-19-Data

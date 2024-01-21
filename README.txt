*Scripts for MVT bias correction of NESM3 simulations during historical period and under four future senarios
------------------------------------------------------------------------------------------------------------------
*How to conduct bias correction:
    (1) Before starting bias correction, all datasets should be regrided, as the script in regrid.zip

    (2) The scripts in hist_correct.zip are for the bias correction of NESM3 simulations during historical period.
        Follow the scripts in folders: monavg -> cal_NLT -> detrend -> cal_stddev_Ratio -> Correct

    (3) The scripts in future_correct.zip are for the bias correction of NESM3 simulations under four future senarios 
        Follow the scripts in folders: monavg -> cal_NLT -> detrend -> Correct  
------------------------------------------------------------------------------------------------------------------
*Source of raw data:
    NESM3 historical simulations: https://aims2.llnl.gov
    NESM3 future simulation     : https://doi.org/10.57760/sciencedb.09659
    ERA5 reanalysis             : https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5

*Variables: upper air variables : specific humidity air temperature, zonal wind, meridional wind, geopotential height
            surface variables   : sea level pressurre, sea surface temperature. surface pressure

*Time period: NESM3 during historical period & ERA5 : 1979–2014
              NESM3 under transient 2 °C scenario   : 2031–2061
              NESM3 under stabilized 1.5°C scenario, 1.5°C overshoot scenario & stabilized 2 °C scenario: 2070–2100
              
*Time scale: 6-hour interval, including UTC 0300, UTC 0900, UTC 1500, UTC 2100
------------------------------------------------------------------------------------------------------------------
* Data source:
    Bias-corrected NESM3 global dataset for dynamical downscaling under 1.5 °C and 2 °C global warming[DS/OL]. 
      V2. Science Data Bank, 2023[2023-07-21]. https://doi.org/10.57760/sciencedb.07777. DOI:10.57760/sciencedb.07777. 
* Code creators: 
    Meng-Zhuo Zhang, Ying Han, Zhongfeng Xu & Weidong Guo
* Institutions:
    School of Atmospheric Sciences, Nanjing University
    CAS Key Laboratory of Regional Climate and Environment for Temperate East Asia, Institute of Atmospheric Physics, Chinese Academy of Sciences

* Any questions can contact zhangmengzhuo1996@163.com
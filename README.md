# tropical-cyclone-hudhud
Cyclonic Storm Hudhud  A depression formed over the Bay of Bengal, intensifying into Cyclonic Storm 'Hudhud' as it neared India, named by Oman. CS Hudhud made landfall over Visakhapatnam, Andhra Pradesh at noon of October 12, 2014, near 17.7°N 83.3°E.

# WRF-ARW Simulation:
The WRF-ARW (v4.5) model was used to simulate this event over an 8-day and 18-hour period (00 UTC 07 Oct 2014 to 18 UTC 14 Oct 2014). The model domain featured a 35-km resolution parent domain with a nested domain at ~11.7-km resolution, using a parent-to-nest grid ratio of 1:3. The simulation utilized the 'NCEP GDAS fnl 0.25°x0.25° dataset with physics schemes configured as follows:
 Microphysics sch. : Thompson (mp_physics = 3)
 Convection sch.  : Kain-Fritsch (cu_physics = 1)
 Land Surface Model: Thermal Diffusion (sf_surface_physics = 1)
 Radiation     : RRTM (ra_lw_physics = 1, ra_sw_physics = 1)
 PBL sch.     : YSU (bl_pbl_physics = 1)

# Projected path of cyclone:
Cyclone Hudhud initiated its formation over the Andaman and Nicobar Islands in the Bay of Bengal. Subsequently, the system intensified and tracked on a northwesterly trajectory, making its approach towards the eastern coastline of India. The city of Visakhapatnam was identified as the primary area for its anticipated landfall.
The IMD issued warnings for heavy to very heavy rainfall in coastal Andhra Pradesh and Odisha. They also cautioned about subsequent heavy rain in Uttar Pradesh, Bihar, Chhattisgarh, and Jharkhand after landfall.

# Plots:
Following plots have been developed from the generated model output with 6-hourly temporal resolution:
 WPS Domain Configuration
 Outgoing Longwave Radiation
 Cloud cover
 Mean Sea Level Pressure Perturbation
 Accumulated Precipitation
 IMD Observed Track


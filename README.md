**Analyses of TDR Soil Moisture Sensor Waveform** <br />
A validation patented intellectual property <br />
### Prepared by B. Keith Bellingham, <br />
Soil Scientist, <br />
October 7, 2022<br/>
https://www.linkedin.com/in/bkbellingham/
**Introduction**

Time domain reflectometry (TDR) is commonly used for the determination of the volumetric soil water content. 
Monitoring soil moisture is increasingly becoming more important for irrigation, flood and drought risk, water resources, and climate change assessments.
TDR is based on the principle that the velocity of an electrical pulse will slow down in the soil as the soil gets wetter. The travel time of the electrical pulse, T, is directly corelated to the parameter called the apparent dielectric permittivity, $K_a$ (sometimes called the relative dielectric permittivity). Knowing the time of travel of the pulse, the $K_a$ of the soil can be determined by: <br />!

$$K_a = (cT/L)^2$$

Where c is the speed of light, and L is the path length of the waveguide. The waveguide is metal part of the sensor that is in the soil through which the electrical pulse travels before reflecting back to the sensor head. 

The Topp Equation, is commonly used as the soil moisture calibration for TDRs by using the $K_a$ value to estimate soil water content; 

$$\theta = a + bK_a + cK_a^2 + dK_a^3$$

Where a, b, c, and d, are empirical coefficients. 

The measurement the travel time of the electrical pulse is the raw measurement used to determine the dielectric permittivity and thus the soil moisture.  The raw signal produced by a TDR instrument is a plot of the voltage of the pulse as a function of time called a waveform. The time the signal enters the soil (start time) and the time the signal reflects and returns to the detector (finish time) is characterized by valleys and inflections in the waveform. Mathematical and algorithmic treatment of the waveform to determine the start time and the finish time will automate the soil moisture determination and can be utilized in the TDR’s commercial software. 



**About the Dataset**

The impute file is a csv that contains the waveforms of distilled water and saturated sand. The waveguide length is 0.08 meters. The are 1200 times where the voltage signal is recorded representing a range of 12,000 picoseconds. Water is used as a reference fluid because the dielectric constant of water is 78.5 at room temperature. 

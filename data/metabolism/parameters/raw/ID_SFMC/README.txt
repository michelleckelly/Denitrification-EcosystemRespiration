Data Set Descriptors 

---

Title: YSI Data from South Fork, ID
	Originator(s): Kevin Nevorski, Amy Marcarelli, Michigan Tech
	Latitude: 42.7074
	Longitude: -112.4228
	Beginning of observation: 2017-07-25 12:15:49
	End of observation: 2017-08-02 16:05:48

Obtained through CAREER Project Shared [Google] Drive, uploaded to Drive by Kevin on 2017-08-24
File path: CAREER Project Shared Drive > Data - Site information, raw or compiled data, calculated or modeled data products > Raw Data > YSIFile_SouthFork.txt

File name: YSIFile_SouthFork.csv

Metadata:

Column name	Units		Description

Date		NA		"DD/MM/YY" date of sensor measurement
Time		NA		"HH:MM:SS" time of sensor measurement
temp_C		C		Stream water temperature
SpCond_uSm
Cond_uScm
Sal_ppt
pH
pH_mV
Turbid_NTU
ODOsat_perc	%		Percent saturation of dissolved oxygen concentration of water
ODO_mgL		mg/L		Dissolved oxygen concentration of water
Battery_V	V		Sensor battery voltage

---
Title: PAR data collected in Marsh Creek, ID during 2017 growing season
	Originator(s): 	Sarah A.S. Honious, Rebecca L Hale, James J. Guilinger, Benjamin T Crosby,
			Colden V Baxter, Idaho State University
	Beginning of observation (site 2): "5/20/17 0:00"
	End of observation (site 2): "10/13/17 23:45"

Obtained through edirepository.org. Citation: Honious, S.A., R.L. Hale, J.J. Guilinger, B.T. Crosby, and C.V. Baxter. 2021. Stream Metabolism in Marsh Creek, Idaho, USA 2016-2017 ver 1. Environmental Data Initiative. https://doi.org/10.6073/pasta/c5dcdde09dbbee91764e3e6f5ee81696 (Accessed 2023-02-23).

File name: SouthForkMilkCreek_FieldDischarge.xlsx

Metadata:

Site 2
	Description: 	farthest downstream site, 9.2 km upstream of confluence of Marsh Creek 
			and the Portneuf River
	Latitude:	42.7360164936
	Longitude:	-112.236397783
	Note:		15 km from South Fork Mink Creek
Site 6
	Description: 	29.9 km upstream of confluence of Marsh Creek and the Portneuf River. 
			USGS gaging station.
	Latitude:	42.6297582858
	Longitude:	-112.225404265
	Note:		18 km from South Fork Mink Creek
Site 8
	Description: 	42.3km upstream of confluence of Marsh Creek and the Portneuf River
	Latitude:	42.5838776206
	Longitude:	-112.194979732
	Note:		23 km from South Fork Mink Creek
Site 9
	Description: 	45 km upstream of confluence of Marsh Creek and the Portneuf River
	Latitude:	42.5663643448
	Longitude:	-112.186642485
Site 10
	Description: 	48.8km upstream of confluence of Marsh Creek and the Portneuf River
	Latitude:	42.5415770916
	Longitude:	-112.178783768
Site 15
	Description: 	farthest upstream site, 68.3 km upstream of confluence of Marsh 
			Creek and the Portneuf River
	Latitude:	42.4283553211
	Longitude:	-112.190606286	

Column name	Units		Description

site		NA		Site number
date_time	NA		"YYYY-MM-DD HH:MM:SS" date time of sensor measurement in local time
turbididty_ntu	NTU		Water turbidity
light		mol m-2 s-1	PAR at stream surface, based on LUX measurements (see paper)
tempC		C		Water temperature
DO.meas		mg/L		Measured dissolved oxygen concentration
atmo.pressure	mBar		Barometric pressure
salinity		ppt		Salinity of water


---

Title: Measurements of stream depth and discharge from South Fork, ID
	Originator(s): Kevin Nevorski, Amy Marcarelli, Michigan Tech

File name: SouthForkMilkCreek_FieldDischarge.xlsx

Metadata:

Column name	Units		Description

Site		NA		Site name
Date		NA		"YYYY-MM-DD" date that depth and/or discharge was measured
Transect number	NA		Section of stream reach where cross-section was measured (see data 
				sheets for map)
Measurement point		Numeric, identifies the sampling point along the transect
Distance from bank	m	Distance measurement point is from left wetted edge of river
Width at point		m	Cross-section width at each measurement point, calculated as 
				(Distance[i+1] - Distance[i-1])/2
Depth at point		m	Water depth at sampling point
Area		m2		Area of cross-section, calculated as point width * point depth
Velocity		m/s		Water velocity at point, as measured by Marsh-McBirney flow meter
Q at point	m3/s		Discharge at point, as calculated by Area * Velocity
Total transect Q	m3/s		Sum of discharge values across transect





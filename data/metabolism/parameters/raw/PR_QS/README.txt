Data Set Descriptors

---

Title: Data from Quebrada Sonadora, Puerto Rico
	Originator(s): Miguel C. Leon, Luquillo LTER Information Manager
	Latitude: 
	Longitude:

Obtained through email correspondence, data was downloaded through http://odm2admin.cuahsi.org:8503/ Downloaded each variable as a separate csv file to not overload the memory of the database portal. Merged variables into one data frame and converted units in R, script saved in ModelMetabolism.Rmd

MetabolismParameters_Raw_Sonadora_2019-01-01_2019-12-31.csv

DateTime_local	From database, date and time of sample in Puerto Rico time
DateTime_UTC 	Local date and time converted to UTC time
Discharge_m3s	From Discharge.csv, originally recorded in units of cubic ft per second
Level_m		From StageHeight.csv, originally recorded in units of cm
WaterTemp_C	From WaterTemp.csv, gap in record from 24 Aug - 19 Sept, Hurricane Dorian hit island on 29-29 Aug
DO_mgL		From DOAdjConc.csv
Light_Lux	From Light.csv
AirPress_kPa	From AirPress.csv
# Automated Ship Activity Detection using AIS

This notebook utilizes the ArcGIS Geoanalytics server to process global AIS data and detect events of interest. Specifically the notebook detects:
- Ship Dwell Events --> when a ship idles in a fixed location for a fixed period of time
- Track Gap Events --> when no positional report is received for a ship for a fixed period of time
- Port Events --> when a ship enters/exits a port

The notebook with default parameters is designed to be run every 4 hours against the 6 most recent hours of AIS data.

![alt text](https://github.com/phornstein/ArcGIS-Notebooks-Samples/blob/main/(Analysis)%20Ship%20Activity%20Detection/Dashboard1.JPG?raw=true)

![alt text](https://github.com/phornstein/ArcGIS-Notebooks-Samples/blob/main/(Analysis)%20Ship%20Activity%20Detection/Dashboard2.JPG?raw=true)

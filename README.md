# Mobility-Data

Mobility Index:
The Mobility Index referenced in this data set has a 100 value based on median distance traveled in each county the week of February 17, 2020. 
  
The Mobility Index was developed by Descartes Labs. Descartes Labs collects anonymous data from a sample of mobile devices reporting their location throughout the day, then calculates the maximum distance moved from the first reported location. The information is de-identified, aggregated, and summarized to protect the privacy of users and communities. More information can be found at descarteslabs.com/mobility and some publicly available data of this nature can be found on their github page github.com/descarteslabs/ 

Connectivity Data:
Fields:
  Hub: The central county whose device IDs are being compared to each surrounding
  “spoke” county.
  
  Spoke: The surrounding county to which devices in the “hub” county can travel.

  Value: For intercounty comparisons, Value represents the proportion of devices in the hub county that appear in the spoke     county per day. For rows with "did not enter other counties" in the “Spoke” field, Value represents the proportion of         devices in the “hub” county that did not appear in any of the “spoke” counties.

  Device sample: The number of device IDs in the "hub" county that were used to generate these statistics, after filtering.

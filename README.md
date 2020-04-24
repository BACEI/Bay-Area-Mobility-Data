# Mobility-Data
The Mobility Index and Connectivity data were developed by Descartes Labs for the Bay Area Council. Descartes Labs collects anonymous data from a sample of mobile devices reporting their location throughout the day, then calculates the maximum distance moved from the first reported location. The information is de-identified, aggregated, and summarized to protect the privacy of users and communities. More information can be found on their <a href="https://www.descarteslabs.com/mobility/">website</a>, and vizualizations of the data can be found on the Bay Area Council Economic Institute <a href="http://www.bayareaeconomy.org/how-the-bay-area-has-reacted-to-stay-at-home-orders/">website</a>. 

<strong>Mobility Index</strong>

The Mobility Index shows the change in movement since the Bay Area has been sheltering in place. It references a 100 value based on median distance traveled in each county the week of February 17, 2020. For example, a mobility index of 50 means the median distance traveled is half of what it was during the week of February 17, 2020.

If you use this data, please attribute it to the Bay Area Council Economic Institute and Descartes Labs. 


<strong>County Connectivity Data</strong>

The connectivity data demonstrates the level of intercounty movement between Bay Area counties. Devices with first and last location reports spanning less than eight hours of the day, or that have fewer than 10 total reports throughout the day are discarded. The overlap value represents the share of device IDs that appear in multiple counties, showing the percentage of devices that appear in the 'county of residence' where the location is first reported and the 'destination' county that the device has traveled to per day. If the device only appears in one county it is labeled as 'did not enter other counties'. The daily overlap index value references the overlap value each day to an overlap value derived from an average by day of week over the baseline period February 10, 2020 through March 1, 2020. 

<strong>County Connectivity Data Fields</strong>

Hub: The central county whose device IDs are being compared to each surrounding “spoke” county.

Spoke: The surrounding county to which devices in the “hub” county can travel.

Date: Local date of samples (currently UTC -7).

Device sample: The number of device IDs in the "hub" county that were used to generate
these statistics, after filtering.

Value: For intercounty comparisons, Value represents the proportion of devices in the hub county that appear in the spoke county per day. For rows with "did not enter other counties" in the “Spoke” field, Overlap actually represents the proportion of devices in the “hub” county that did not appear in any of the “spoke” counties.

Overlap index: Daily Overlap as a percentage of Overlap averaged by day of week over the
baseline period (2020-02-10 through 2020-03-01).

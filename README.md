# Mobility-Data
The Mobility Index and Connectivity data were developed by Descartes Labs. Descartes Labs collects anonymous data from a sample of mobile devices reporting their location throughout the day, then calculates the maximum distance moved from the first reported location. The information is de-identified, aggregated, and summarized to protect the privacy of users and communities. More information can be found on their <a href="https://www.descarteslabs.com/mobility/">website</a>.

<strong>Mobility Index:</strong>
The Mobility Index shows the change in movement since the Bay Area has been sheltering in place. It references a 100 value based on median distance traveled in each county the week of February 17, 2020. For example, a mobility index of 50 means the median distance traveled is half of what it was during the week of February 17, 2020.

<strong>Connectivity Data:</strong>
The connectivity data demonstrates the level of intercounty movement between Bay Area counties. Devices that have location reports spanning most of the day are included in the data. Devices with first and last location reports spanning less than eight hours of the day, or that have fewer than 50 total reports throughout the day are discarded. Then the overlap of unique device IDs that approach in multiple counties is reported and the overlap is quantified.

<strong> Connectivity Fields: </strong>

Hub: The central county whose device IDs are being compared to each surrounding “spoke” county.
  
Spoke: The surrounding county to which devices in the “hub” county can travel.

Value: For intercounty comparisons, Value represents the proportion of devices in the hub county that appear in the spoke county per day. For rows with "did not enter other counties" in the “Spoke” field, Value represents the proportion of     devices in the “hub” county that did not appear in any of the “spoke” counties.

Device sample: The number of device IDs in the "hub" county that were used to generate these statistics, after filtering.

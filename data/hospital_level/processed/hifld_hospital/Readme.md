- Data source: https://hifld-geoplatform.opendata.arcgis.com/datasets/6ac5e325468c4cb9b905f1728d6fbf0f_0
- Last downloaded: 04-01-2020
- Description: This data has ICU, location, and number of employees info about each hospital.
- Known data quality issues: 
    - Not all hospitals in the US are included.
    - Does not have CMS Certification Number, which would be used a primary key for each hospital.
- Selected Columns:
    - Hospital Name, str, all lower case
    - Long, 
    - Lat,
    - Address, str, all lower case
    - City, str, all lower case
    - Zipcode
    - State
    - Telephone, Missing value is NOT AVAILABLE
    - countyFIPS
    - Total Beds
    - Website
    - Trauma Center Level, 1-5
    - Hospital Type, str, lower case
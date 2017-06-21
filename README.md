# Zipcodes by County

## Files

### `county_state_zip.csv`
List of counties with a single zip per row.

Example Data (truncated for preview):

| County  | State | Zip |
| - | - | - |
| Autauga County | AL | 36051 |
| Autauga County | AL | 36006 |
| Autauga County | AL | 36066 |
| Baldwin County | AL | 36576 |
| Baldwin County | AL | 36547 |
| Baldwin County | AL | 36551 |
| Barbour County | AL | 36048 |
| Barbour County | AL | 36311 |
| Barbour County | AL | 36072 |
| Barbour County | AL | 36017 |
| Bibb County    | AL | 35034 |
| Bibb County    | AL | 35456 |
| Bibb County    | AL | 36750 |

### `county_state_zips.csv`
List of counties with a all zipcodes in the zips column.

Example Data:

| County | State | Zip |
| - | - | - |
| Autauga County | AL | 36003, 36006, 36008, 36022, 36051, 36066, 36067, 36068, 36091, 36701, 36703, 36749, 36758 |
| Barbour County | AL | 26201, 26238, 26250, 26267, 26275, 26283, 26330, 26349, 26354, 26405, 26408, 26416, 36016, 36017, 36027, 36048, 36053, 36072, 36311, 36317, 36374 |
| Bibb County    | AL | 31020, 31052, 31066, 31201, 31203, 31204, 31205, 31206, 31207, 31208, 31209, 31210, 31211, 31213, 31216, 31217, 31220, 31221, 31295, 35034, 35035, 35042, 35074, 35111, 35115, 35184, 35188, 35456, 36750, 36792, 36793 |


## Sources:
*Sourced on 21-06-2016*

### County Zipcodes (USPS ZIPCODE Crosswalk Data):
* Data: https://www.huduser.gov/portal/datasets/usps/COUNTY_ZIP_032017.xlsx
* Source Page: https://www.huduser.gov/portal/datasets/usps_crosswalk.html#data
* Local Copy: `./raw_data/COUNTY_ZIP_032017.xlsx`


### County FIPS Data:
* Data: https://www2.census.gov/geo/docs/reference/codes/files/national_county.txt
* Source Page: https://www.census.gov/geo/reference/codes/cou.html
* Local Copy: `./raw_data/national_county.txt`

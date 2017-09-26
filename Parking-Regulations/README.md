[NYC Parking Regulation Search Tool](http://a841-dotvweb01.nyc.gov/ParkingRegs/ViewController/LocationValidation.aspx) | *** |
[DOT DL Page](http://www.nyc.gov/html/dot/html/about/datafeeds.shtml#parking)
# The CSV files ‘ locations’ and ‘signs’
### ‘locations’ file record has the following fields:
- Borough code (B - Bronx, K – Brooklyn, M – Manhattan, Q – Queens, Staten Island)
- ‘Status’ - order number
- From street
- Main street
- To street
- Side of street (N - north, S - south, E - east, W - west)

|Borough|Order #|From street|Main street|To street|St. Side|
|---|---|---|---|----|----|
|B|P-00097691|KATONAH AVENUE|EAST  235 STREET|EAST  236 STREET|E|
|B|P-00097700|WHITE PLAINS ROAD|EAST  213 STREET|EAST GUNHILL ROAD|W|


### ‘Signs’ file record has the following fields:
- Borough code (B - Bronx, K – Brooklyn, M – Manhattan, Q – Queens, Staten Island)
- ‘Status’ - order number
- Sign sequence
- Distance from curb line
- Arrow points
- Sign description
- Sign code

| Borough |Order #| Sign seq. | Dist. from curb line | Arrow points | Sign description | Sign code |
|---------|--------------|---------------|-------------------------|--------------|------------------|-----------|
|B|P-330868  |2|16   |NULL|Building Line|BL|
|B|P-330862  |11|799  |NULL|Building Line|BL|	

### Files should be matched by concatenating of the borough code field and the Status order number field


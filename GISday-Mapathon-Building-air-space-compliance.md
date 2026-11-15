# Mapping Building Conpliance with Air-space in Ibara ward 1, Abeokuta south LGA, Ogun state


## THE PROBLEM

> Houses needs more than walls to provide a comfortable living environment, it needs enough open space around it for air, natural light and proper separation from neighbouring buildings. However, as neighbourhood develop, buildings occupy every avaliable spaces, living little room between one house to another. This raise an important question is the building in our neighbourhood meeting the required air-space standards?
---
## DATA USED
| Date | Source | Purpose | Type |
| --- | --- | --- | --- |
| OSM Building Footprint | OpenStreetmap | assess air-space compliance | spatial (polygon)
| Administrative Boundary Level 2,3 | GRID3 | accurately define and clip the analysis to the study area | spatial (polygon) |
| OSM Road | OpenStreetmap | show location and alignment to the study area | spatial (point) |

## METHODS
### *The study area*
> The study was carried out in Ibara ward 1, located within Abeokuta south L.G.A in Ogun state. The ward is selected because of its recent  urban development, concentration of residential housing schemes, and growing built-up areas, making it suitable for this study.
*Figure below show the map of the study area*
![Ibara ward 1](compliance/study-area.png)

### ANALYSIS
* All spatial data  were projected to UTM zone 31N
* To minmise error arising from digitization and topology and also to remove kiosk, shops, among others polygon less than **30 sqm** were excluded fom the analysis
* A **1.5 m** was created around each building footprint and intersecting buffered polygons were identified
* selected features attribute were updated and joined with the original building footprint
---
### FINDINGS

| SN | Description | count | % |
| --- | --- | --- | --- |
| 1 | Ignored | 100 |  |
| 2 | Adequate | 3539 | 32.2 |
| 3 | Not Adequate | 1684 | 67.8 |
|   | Total | 5223 | 100 |


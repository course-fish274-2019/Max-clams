Detailed metadata are provided in this repository for reproducing all analyses in Spatial and temporal coherence in intertidal clams (Barber et al., in review)

FILES INCLUDE:
Barberetal_Rcode_DFA.txt
SuppTable1_ClamData_DFA.csv
SuppTable2_Salinity_DFA.csv
SuppTable3_AirTemp_DFA.csv
SuppTable4_CrabCatch_DFA.csv
SuppTable5_SST_DFA.csv

FILE DESCRIPTIONS:
Barberetal_Rcode_DFA.txt = detailed R code from analysis

SuppTable1_ClamData_DFA.csv = Mean clam biomass/m2 by species, site, and Puget Sound sub-basin. Also includes standard deviation and sample size. Codes explained below.

SuppTable2_Salinity_DFA.csv = Raw sea surface salinity data obtained from Department of Fisheries and Oceans Canada. Annual mean from Race Rocks, Strait of Juan de Fuca. http://www.pac.dfo-mpo.gc.ca/science/oceans/data-donnees/lightstations-phares/data/RaceRocksDailySalTemp.txt

SuppTable3_AirTemp_DFA.csv = Raw annual mean air temperature from Puget Sound lowlands. Accessed from https://www.ncdc.noaa.gov/cag/time-series

SuppTable4_CrabCatch_DFA.csv = mean October state catch (kg) per landing. Commerical state harvest data from Northwest Indian Fisheries Commission and Washington Department of Fish and Wildlife (B. Conrad, unpublished data)

SuppTable5_SST_DFA.csv = Raw sea surface temperature data obtained from Department of Fisheries and Oceans Canada. Seasonal means from Race Rocks, Strait of Juan de Fuca: Winter (win) = January-March, Spring (spr) = April-June, Summer (sum) = July- August. http://www.pac.dfo-mpo.gc.ca/science/oceans/data-donnees/lightstations-phares/data/RaceRocksDailySalTemp.txt

CLAMDATA.CSV METADATA:
Year = year of datapoint

Species:
sa	Saxidomus gigantea
leu	Leukoma staminea
cli	Clinocardium nuttallii

Beach:
ca	Camano Island State Park
wc	West Penn Cove
ss	Sequim Bay State Park (South)
sn	Sequim Bay State Park (North)
ii	South Indian Island County Park
pt	Port Townsend Ship Canal
wp	Wolfe Property State Park
st	Shine Tidelands State Park
ps	Potlatch State Park
pd	Potlatch Dept. Natural Resources

Sub-basin:
1	Strait of Juan de Fuca
4	Whidbey
5	Admirality Inlet
8	Hood Canal

Example: "leu.pd.8" = L. staminea in Potlatch Department of Natural Resources in Hood Canal sub-basin

Columns with "sd" at the end of the ID follow the same code as above but the "sd" represents the standard deviation. Example: "cli.ps.8.sd"

Columns with "n" at the end of the ID follow the same code as above but the "n" represents the sample size. Example: "leu.ss.1.n"









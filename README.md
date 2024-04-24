# Arctic River Data Repository

The Arctic River Data Repository! This repository is dedicated to organizing various datasets related to Arctic rivers, including river runoff, temperature, precipitation, and land type data. Additionally, some of the precipitation data has been modeled using Google Earth Engine.

## Table of Contents

- [Introduction](#introduction)
- [Datasets](#datasets)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Arctic rivers play a crucial role in the regional and global climate system, influencing ocean circulation patterns, freshwater availability, and ecosystem dynamics. Understanding the dynamics of these rivers is essential for various scientific and environmental studies.

This repository aims to centralize diverse datasets related to Arctic rivers, to provide a basis in conducting a pan-Arctic ERRA analysis.

## Datasets

### River Data

| River Name         | Lat/Lon          | River Runoff Data                               | Precipitation Data                             | Temperature Data                                |
|--------------------|------------------|-------------------------------------------------|------------------------------------------------|-------------------------------------------------|
| [Upper Kuparuk, Toolik, Alaska](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Upper_Kuparuk) | $68^{\circ} 28'$ N, $148^{\circ}36'$ W | [Runoff 2003-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Upper_Kuparuk/ERRA_Ready_Data/UK_synthesized_data.txt) | [Precipitation 2003-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Upper_Kuparuk/ERRA_Ready_Data/UK_synthesized_data.txt) | [Temperature 2003- 2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Upper_Kuparuk/ERRA_Ready_Data/UK_synthesized_data.txt)    |
| [Goose, Cape Bounty, Canada](Cape_Bounty) | $74^{\circ} 54'$ N, $109^{\circ}35'$ W  | [Runoff 2007-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Cape_Bounty/ERRA_Ready_Data/CB_thawingdepth_hourly.txt) | [Precipiation 2007-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Cape_Bounty/ERRA_Ready_Data/CB_thawingdepth_hourly.txt) | [Temperature 2007-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Cape_Bounty/ERRA_Ready_Data/CB_thawingdepth_hourly.txt)    |
| [Ptarmigan, Cape Bounty, Canada](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Cape_Bounty) | $74^{\circ} 54'$ N, $109^{\circ} 35'$ W | [Runoff 2007-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Cape_Bounty/ERRA_Ready_Data/CB_thawingdepth_dist_hourly.txt) | [Precipiation 2007-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Cape_Bounty/ERRA_Ready_Data/CB_thawingdepth_dist_hourly.txt) | [Temperature 2007-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Cape_Bounty/ERRA_Ready_Data/CB_thawingdepth_dist_hourly.txt)    |
| [Røde Elv, Greenland](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Rodeelv) | $69^{\circ} 15'$ N, $53^{\circ} 31'$ W| [Runoff 2015-2021](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Rodeelv) | [http:/g‐e‐m.dk](http:/g‐e‐m.dk) | [http:/g‐e‐m.dk](http:/g‐e‐m.dk)    |
| [Putuligayuk, Toolik, Alaska](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Putuligayuk) | $68^{\circ} 37'$ N, $149^{\circ}19'$ W  | [River Runoff 1999-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Putuligayuk/ERRA_Ready_Data/PR_synthesized_data.txt) | [Precipitation 1999-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Putuligayuk/ERRA_Ready_Data/PR_synthesized_data.txt) | [Temperature 1999-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Putuligayuk/ERRA_Ready_Data/PR_synthesized_data.txt)    |
| [Jarvis Creek, Alaska](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Jarvis_Creek) | $64^{\circ} 02'$ N, $145^{\circ}73'$ W  (needs confirmation)| [River Runoff 2013-2016](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Jarvis_Creek/ERRA_Ready_Data/PR_synthesized_data.txt) | [Precipitation 2013-2016](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Jarvis_Creek/ERRA_Ready_Data/PR_synthesized_data.txt) | [Temperature 2013-2016](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Jarvis_Creek/ERRA_Ready_Data/PR_synthesized_data.txt)    |
| [Imnavait Creek, Toolik, Alaska](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Imnavait_Creek) | $68^{\circ} 62'$ N, $149^{\circ}34'$ W | [River Runoff 1985-2017](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Imnavait_Creek/Discharge/ImnavaitCr_Historical_Discharge_1985_2017_2018Aug6.csv) | [Precipitation likely with MET data](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Imnavait_Creek/Meteorologic_Data) | [Temperature 1986-2018](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Imnavait_Creek/Meteorologic_Data/MET)    |
| [Goldstream, Fairbanks, Alaska](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Goldstream) | $64^{\circ} 91'$ N, $147^{\circ}95'$ W | [Multiple River Runoff 2016-2018](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Goldstream/ERRA_Ready_Data/GS_synthesized_data.txt) | [Precipitation  2016-2018](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Goldstream/ERRA_Ready_Data/GS_synthesized_data.txt) | [Temperature  2016-2018](https://github.com/cculha4/Permafrost_ERRA_Arctic/blob/main/Goldstream/ERRA_Ready_Data/GS_synthesized_data.txt)    |

### Land Type Data


## Contributing

Contributions to this repository are by Niek Jesse Speetjens and Cansu Culha.

## License

This repository is licensed under the [MIT License](LICENSE).

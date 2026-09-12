# Project Brief

## Part 1: Research Question

Which wards in Ikeja Local Government Area (LGA) are more than 3km from a police station?

## Part 2: Why It Matters

This question helps residents who live in Ikeja LGA know the closest police station in their neighborhood, and it highlights gaps in physical access in case of security emergencies. Residents, companies, and government agencies can use these findings to prioritize the siting of new facilities.

## Part 3: Data Needed

1. Nigeria State Boundary Data
2. Nigeria LGA Level Data
3. Nigeria Ward Level Data
4. Police Stations in Ikeja LGA, Lagos State, Nigeria
5. Road Data from the QuickOSM plugin in QGIS

## Part 4: Data Sources

| Dataset | Source of Data |
|---|---|
| Nigeria State Boundary Data | [GRID3 NGA - Operational State Boundaries (April 2024) - 862kb](https://data.grid3.org/datasets/c41532b720504f4799fe20438b7e3b7f_0/explore?location=9.077959%2C8.685290%2C6) |
| Nigeria LGA Level Data | [GRID3 NGA - Operational LGA Boundaries (December 2020) - 3.58mb](https://data.grid3.org/datasets/2bb616a49ee84f409427cc2143787113_0/explore?location=9.077959%2C8.685290%2C6) |
| Nigeria Ward Level Data | [GRID3 NGA - Operational Wards v1.0 (September 2025) - 1.1mb](https://data.grid3.org/datasets/0824aded5f5a4d39b10871c667aa8ccf_0/explore?location=6.605815%2C3.392352%2C12) |
| Police Stations in Ikeja LGA, Lagos State, Nigeria | [GRID3 NGA - Police Stations (September 2025) - 604kb](https://data.grid3.org/datasets/93239bea1fa84d79bb7be03b5fb82832_0/explore?location=6.616078%2C3.380246%2C11) |
| Road Data from the QuickOSM plugin in QGIS | Extracted using the QuickOSM plugin in QGIS software |

## Part 5: What Will Be Built

An interactive web map of Ikeja GRA that shows every ward colored by its distance to the nearest police station, with wards beyond 3km clearly flagged in red. The map can be updated each month as new facility or road data is added. Security operatives can use the map to plan for upcoming police infrastructure.

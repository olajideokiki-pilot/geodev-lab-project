# Month 1 Summary - Police Station Access in Ikeja LGA

## Question

Which settlements in Ikeja LGA, Lagos State fall within 500m from a police station?

## Operation Run

Buffered GRID Police Station by 500m, then joined attributes by nearest (settlements - police stations), using clipped and reprojected layers (EPSG:2631, UTM Zone 31N).

## Expected

I expected to identify settlements within 500m of police stations and compare them to different wards in Ikeja LGA.

## Obtained

I obtained 733 of 1,715 settlements within 500m reach of the police station.

## What Surprised Me

The settlements located in commercial, industrial, and government-established places are farther from the nearest police station compared to settlements located in residential areas within Ikeja.

## Data Still Needed

Further updates will incorporate population and road-network distance.

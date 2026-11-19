# Visualizing fire scars through false color
EDS220 HW4

## Author

Emalia Partlow

![Palisades Fire - LA County, 2025](https://www.rollingstone.com/wp-content/uploads/2025/01/GettyImages-2192344712.jpg?w=1280)

## Repository purpose

Contains the script **hwk4-task2-false-color-partlow.ipynb** for creating a map visualizing the fire boundaries and fires scars for the Eaton and Palisades Fires, which occured in LA county during January, 2025.

## Repository Structure

```{}
.
├── README.md
├── data
│   ├── Eaton_Perimeter_20250121
│   ├── landsat8-2025-02-23-palisades-eaton.nc
│   └── Palisades_Perimieter_20250121
└── hwk4-task2-false-color-partlow.ipynb
```

## Data access

**.gitignore** removes **data/** from this repository.

To download the data, click on the links in the reference section.

Data files used in **hwk4-task2-false-color-partlow.ipynb** analysis include:

1) `landsat8-2025-02-23-palisades-eaton.nc`
    - Includes values of surface reflectance bands (red, green, blue, near-infrared and shortwave infrared). These data were collected by the Landsat 8 satellite.
2) `Eaton_Perimeter_20250121.shp` and `Palisades_Perimieter_20250121.shp`
    - Includes polygons of the fire burn perimeters. These data were collected by CAL FIRE.

## References

Planetary Computer. (1982 – Present). Landsat Collection 2 (Level-2). Microsoft. [10.5066/P9OGBGM6]()

CAL FIRE (2025). Palisades and Eaton Dissolved Fire Perimeters. ArcGIS Hub. [https://hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about]()
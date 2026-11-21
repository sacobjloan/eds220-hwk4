# Visualizing the Eaton and Palisades Fires 2025

## About

The the greater Los Angeles landscape was changed greatly in 2025 by both the Eaton and Palisades fires. Satellite imagery is widely accessible and you can observe the burn scars through them, but sometimes differences across a landscape are easier visualized with false color imagery rather than true color. In this repo I've created a false color image with fire bounds to show the extent of the two 2025 fires.

## Repository Structure 

```
EDS220-HW4
│   README.md
│   hwk4-task2-false-color-sloan.ipynb
│   .gitignore   

```

## Data

Raster data used to create true and false color images comes from the Landsat 8 satellite, and is housed on the Microsoft Planetary Computer data catalog. The data includes 6 layers: red band, green band, blue band, near infrared band, short-wave infrared band, and a layer describing the spatial reference of the data.

Fire perimeter data was taken from the County of Los Angeles arcgis page. The data files contain the names of the fires and the spatial geometries of each.

[Data files can be found in this google drive folder.](https://drive.google.com/drive/folders/1sPc0Yqu-zTpeNQ39vlUQOaANU7kSLutz?usp=drive_link)


## References

C. Galaz García, EDS 220 - Working with Environmental Datasets, Course Notes. 2024. [Online]. Available: https://meds-eds-220.github.io/MEDS-eds-220-course/book/preface.html

Los Angeles Couny. (2025). Palisades and Eaton dissolved fire perimeters (2025). Arcgis.Com.[Dataset] https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about.
[Accessed: Nov 20, 2026]

Microsoft planetary computer. (2024). Microsoft.Com.[Dataset] https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2. [Accessed: Nov 20, 2026]


# NICAR 2025: Using Python to analyze map data

### 🔗 [bit.ly/nicar25-python-gis](https://bit.ly/nicar25-python-gis)

This repository contains materials for an introductory workshop at the NICAR 2025 conference on using Python to analyze GIS data.

The session is scheduled for Thursday, March 6, from 11:30 a.m. – 12:30 p.m. in room `Lafayette Bay` on the eighth floor.

🗺️ Don't miss "Advanced Python mapping techniques" with Ari Sen at 2:15 p.m. in the same room. For a deeper dive, check out ["Fun with shapes: Scripted mapping in R or Python"](https://www.ire.org/product/nicar25-fun-with-shapes-scripted-mapping-in-r-or-python/) ($40) on Saturday morning.

### First step
Open the `Terminal` application. Copy and paste this text and hit enter:

```
cd Desktop/hands_on_classes/20250306-thursday-using-python-to-analyze-map-data && env/bin/activate && jupyter lab
```

### Course outline
- Hello, geopandas!
- Points-in-polygon analysis
- Calculating overlay areas
- (Bonus!) Downloading GIS data from a public ArcGIS server

🛜 On the off chance the shapefiles aren't available, they're mirrored here:
- [U.S. counties](https://schedules.ire.org/nicar-2025/files/cb_2023_us_county_20m.zip)
- [Forest Service office locations](https://schedules.ire.org/nicar-2025/files/Forest_Service_Office_Locations.zip)
- [Minnesota old-growth forests](https://schedules.ire.org/nicar-2025/files/shp_biota_dnr_forest_inv_old_growth.zip)

### Resources
- [Geopandas documentation](https://geopandas.org/en/stable/)
- Online book: ["Introduction to Python for Geographic Data Analysis"](https://pythongis.org/)
- [Free courses and textbooks from the University of Colorado Earth Lab](https://www.earthdatascience.org/courses/)

#### Using Google CoLab or Binder
You can run these notebooks by plugging this GitHub repository's URL into [Google CoLab](https://colab.research.google.com/) or [Binder](https://notebooks.gesis.org/binder/), both easy-to-use, cloud-based Python notebook environments.

#### On your own laptop
- Install Python, if you haven't already ([here's our guide](https://docs.google.com/document/d/1cYmpfZEZ8r-09Q6Go917cKVcQk_d0P61gm0q8DAdIdg/edit))
- Clone or download this repo
- `cd` into the directory and install the requirements, preferably into a virtual environment using your tooling of choice: `pip install -r requirements.txt`
- `jupyter lab` to launch the notebook server

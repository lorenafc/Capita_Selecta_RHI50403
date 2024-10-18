# Capita_Selecta_RHI50403

Scripts made during the Capita Selecta History course of Wageningen University & Research for the Useful Knowledge Project, under the supervision of Sandra de Pleijt.

The scripts do the encoding, geocoding of locations of records, and visualization of authors localization from the years 800 to 1800 of small cities (<10.000 habitants) in the world, and big cities from the North Sea region (The Netherlands, Belgium and UK). The records were obtained from the Virtual International Authority File (VIAF) database (by Eric Chaney).

Structure:

├── LICENSE<br>
├── README.md  
├── preprocessing   <- Scripts to do the data cleaning, encoding, and geocoding<br>
├── preprocessing   <- Scripts to do the data cleaning, encoding, and geocoding using openai API. Its now on the repository Useful_Knowledge, so this script will not be uodated here <br>
├── visualization   <- Scripts to create visualizations of the authors in the locations along the years (Inicially were the scripts "Maps_authors.pynb" and "Maps_authors_NL_BE_UK.ipynb", but I want to gradually put everything only on visualization.ipynb. I am still working on it.<br>
├── tests           <- Scripts to show the statistics of places not geocoded. Currently in the scripts "1401_cities_names_fixed.ipynb" and "authors_cities_not_geocoded.ipynb", but I want to keep everything on "tests". Still working on it.  


## Environment Setup

This project was built using **Python 3.8.19**. Make sure you are using this version or a compatible one to avoid potential issues with library compatibility.

### Libraries:

- **pandas**: Version `1.4.4`
- **geopandas**: Version `0.13.2`
- **requests**: Version `2.32.2`
- **html** (module, no separate version)
- **geopy**: Version `2.4.1`
- **tqdm**: Version `4.66.4`
- **googlemaps**: Version `4.10.0`
- **matplotlib**: Version `3.4.3`
- **contextily**: Version `1.6.0`
- **pyproj**: Version `3.5.0`
- **shapely**: Version `2.0.1`
- **matplotlib-scalebar**: Version `0.8.1`

### Media Processing Libraries:
- **imageio**: Version `2.33.1` (for GIF creation)
- **moviepy**: Version `1.0.3` (for video creation)

### License
This project is licensed under the MIT License.





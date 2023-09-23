## Table of Contents
1. [General Info](#general-info)
2. [Installation](#installation)

## General Info
***
### About This Script

This Python script performs multiple tasks related to geographic coordinates. 

#### Features:

1. **Read Excel File**:  
   The script reads an Excel file that contains a set of coordinates in a specific format (e.g., `42N0605.5` for latitude and `002E1737.48` for longitude).

2. **Coordinate Transformation**:  
   Transforms these coordinates into decimal format using helper functions.

3. **Reverse Geolocation**:  
   Utilizes the Google Maps API for reverse geolocation to obtain the name of the municipality where these coordinates point to.

4. **Update Excel File**:  
   Appends the obtained municipality information to the original Excel file.

5. **Generate Map**:  
   Creates an HTML map using the Folium library. Each marker on the map represents one of the processed coordinates.
***
### Installation
A little intro about the installation. 
```
$ git clone https://github.com/crashbit666/coords.git
$ cd coords
$ pip install -r requirements.txt
```

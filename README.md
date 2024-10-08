################### Disclaimer ################

## This software is provided "as-is," without any express or implied warranty. In no event shall the author(s) be held liable for any damages arising from the use of this software.

## **Non-Commercial Use Only**: This code is licensed for personal and educational use only. You may not use, distribute, or modify this software for any commercial purposes, whether for-profit or non-profit, without explicit permission from the author(s).

## **No Liability**: The author(s) make no representations or warranties regarding the accuracy or functionality of this software. The use of this code is at your own risk, and the author(s) disclaim any responsibility for any direct, indirect, incidental, or consequential damages arising from its use.

## By using this software, you agree to the terms of this disclaimer.

##############################################

This R sample code takes at risk asset locations from https://city-tampa.opendata.arcgis.com/search?tags=Location and maps them against Reask (1km) forecast estimates for category 1 equivlant winds at each site.

Input

Databse.csv = a databse inlcudling police station, hospitals and fire station locations in Tampa Florida. Source: https://city-tampa.opendata.arcgis.com/search?tags=Location
LiveCyc_al142024_2024100706_ft_gust_exProba_Cat1.tiff = Reask cat 1 equaivalent wind speeds probabilities (1km resolution)

Output 

ReasPlot.html = an interative map where locaiton level cat 1 wind speeds probabilites can be assess at each location in the asset database


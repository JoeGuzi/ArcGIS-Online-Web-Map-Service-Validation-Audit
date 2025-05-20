Description: This script will check the urls of map services within webmaps to determine if they are valid. 
If they are not valid, it will write the results to a csv file so they can be taken care of. 
 
Created on: 9/3/2018
 
Purpose: This script will go through an entire ArcGIS Online Organization or a Portal Organization and look through all of the Web Maps. Then, this script will check the all of the urls of all of the map services within each Web Map to determine if they are valid. If they are not valid, it will write the results to a csv file so they can be taken care of. The csv file can then be used to aid the administrator in the cleanup of the map services with invalid urls.  This is a Jupyter Notebook written using the ArcGIS Python API. 
 
Authored by: Joe Guzi
 
Previous Production Date: 8/7/2024      

Production Date: 3/11/2025

Note:

 - 8/7/2024 - Updated with my template

 - 3/11/2025 - Script was updated due to the update to the ArcGIS Python API version 2.4, using the web map's JSON to find the layer URL since Map module is not working

 - 4/15/2025 - removed unnecessary module from import block.

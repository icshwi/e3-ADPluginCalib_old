
e3-ADPluginCalib  
======
ESS Site-specific EPICS module : ADPluginCalib

Algorithm:
1. The plugin takes the image from PG1/PG2
2. Use Canny algorithm to find all contours
3. Find the biggest countour with 4 corners
4. Transform image using four corners points and calculated coresponding rectangular points
5. Calibrate image pix -> mm

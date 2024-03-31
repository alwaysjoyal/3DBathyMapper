# 3DBathyMapper
Data Loading and Configuration:
Ensure correct loading of data files. The input file should have no header, with the first column representing Easting, the second column representing Northing, and the third column representing Depth. Upon loading, apply the Full Reservoir Level (FRL) and the Current Reservoir Level (CRL) for accurate plotting. 

Display Options:
There is an option to display the Geographic coordinates of the maximum and minimum depth points, along with UTM coordinates. 

Coordinate Conversion:
Coordinate conversion is performed using the Universal Transverse Mercator (UTM) projection with the ellipsoid set as WGS 84. 

Important Notes:

Application Loading Time :  Loading the application may take up to 2 minutes, depending on system performance and file size.

Fallback Values          :  If FRL and CRL values are not provided, it is important to manually fill them with zero (0).

System Requirements      : The application requires Windows 10 or above to run smoothly.

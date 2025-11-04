# DioGIS

This is an example of how to set up a basic local developing and testing environment for building a high-level webGIS API. 
Note that the spatial files are not stored/shared. 

To make it work, you need your own spatial files!

## Basics
  - Download and install *Node.js* from https://nodejs.org/en/download!
  - Open any terminal, move to your working directory where all html and js files are stored, for example: *cd D:\DEV*.
  - Run your node (fileserver) file: *node dummy_fileserver.js*.
  - If you see the following line appear in the terminal: *Server running with CORS at http://localhost:8080*, you have successfully created a local webserver!
  - Go to any browser and run any html file: *http://localhost:8080/dummy_MAIN.html*.

###  Important 
  - The webGIS API appears only if the geojson files exist and their urls (for example: "http://localhost:8080/geojson/AOI.geojson") are set correctly (change the urls)!
  - It can easily be connected to a geoserver using the server's webservices (rendering large spatial files of almost any format).

### Screenshots
<img align="bottom" src="https://raw.githubusercontent.com/DijoG/storage/main/README/DioGIS_01.png">
<img align="bottom" src="https://raw.githubusercontent.com/DijoG/storage/main/README/DioGIS_02.png">
<img align="bottom" src="https://raw.githubusercontent.com/DijoG/storage/main/README/DioGIS_03.png">
<img align="bottom" src="https://raw.githubusercontent.com/DijoG/storage/main/README/DioGIS_04.png">
<img align="bottom" src="https://raw.githubusercontent.com/DijoG/storage/main/README/DioGIS_05.png">
<img align="bottom" src="https://raw.githubusercontent.com/DijoG/storage/main/README/DioGIS_06.png">
<img align="bottom" src="https://raw.githubusercontent.com/DijoG/storage/main/README/DioGIS_07.png">
<img align="bottom" src="https://raw.githubusercontent.com/DijoG/storage/main/README/DioGIS_08.png">
<img align="bottom" src="https://raw.githubusercontent.com/DijoG/storage/main/README/DioGIS_09.png">



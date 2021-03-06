# Samples

MIVisionX samples using OpenVX and OpenVX extension libraries

## GDF - Graph Description Format

MIVisionX samples using runvx with GDF

### skintonedetect.gdf

<p align="center"><img width="90%" src="images/skinToneDetect_image.PNG" /></p>

usage:

````
runvx skintonedetect.gdf
````
### canny.gdf

<p align="center"><img width="90%" src="images/canny_image.PNG" /></p>

usage:

````
runvx canny.gdf
````
### skintonedetect-LIVE.gdf
Using live camera

usage:

````
runvx -frames:live skintonedetect-LIVE.gdf
````
### canny-LIVE.gdf
Using live camera

usage:

````
runvx -frames:live canny-LIVE.gdf
````
### OpenCV_orb-LIVE.gdf
Using live camera

usage:

````
runvx -frames:live OpenCV_orb-LIVE.gdf
````

## C / C++ Samples

MIVisionX samples IN C / C++

### Canny

usage:

````
cmake .
make
./cannyDetect --image <imageName> 
./cannyDetect --live
````
### Orb Detect
usage:

````
cmake .
make
./orbDetect
````

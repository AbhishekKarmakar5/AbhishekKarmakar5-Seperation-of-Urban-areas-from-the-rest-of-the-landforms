# Seperation-of-Urban-areas-from-the-rest-of-the-landforms
The Urban Areas has been extrated out from the landset image. The main idea of this reprojectory is to extract out the area which contain the densly populated place.

# Watershed segmentation

The watershed is a classical algorithm used for segmentation, that is, for separating different objects in an image.

Starting from user-defined markers, the watershed algorithm treats pixels values as a local topography (elevation). The algorithm floods basins from the markers until basins attributed to different markers meet on watershed lines. In many cases, markers are chosen as local minima of the image, from which basins are flooded.

# The code works on the similar types of images also the 4 types of images generated werer:-
* watershed1 - where the pixel values are ==1, the urban area has been greened.
* watershed2 - where the pixel values are !=1, the other landforms other than urban has been greened.
* watershed3 - where the pixel values are ==-1, the border has been marked which seperated the two of them (urban and the other landforms)
* watershed4 - where the pixel values are !=-1, the border line has been visualised at great ease.

![just4](https://user-images.githubusercontent.com/39180928/89710469-e9479a00-d9a0-11ea-9863-41816e49ee92.jpg)

![kop1](https://user-images.githubusercontent.com/39180928/89778161-aa455000-db2a-11ea-95b6-842138741911.jpg)

![lol4](https://user-images.githubusercontent.com/39180928/89873829-a53eda00-dbd8-11ea-91e9-2848763a3357.jpg)

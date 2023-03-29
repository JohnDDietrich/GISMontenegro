<h1>Habitat Model Montenegro</h1>


<h2>Description</h2>
This project consists of using a DEM and water bodies vector files to model habitat for a theoretical organism occuring in Montenegro.
<br />


<h2>Techniques Used</h2>

- <b>Raster classification</b> 
- <b>Buffer</b>
- <b>Intersect</b>
- <b>Hillshade</b>

<h2>Software Used </h2>

- <b>QGIS</b>

<h2>Classify raster to separate everthing above 1500m:</h2>

<p align="center">

<img src="https://github.com/JohnDDietrich/GISMontenegro/blob/main/MNE_rasterclassification.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a 1km buffer around water features  <br/>
<img src="https://github.com/JohnDDietrich/GISMontenegro/blob/main/MNE_buffering.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Find intersection between water buffer and 1500+ elevation polygons <br/>
<img src="https://github.com/JohnDDietrich/GISMontenegro/blob/main/MNE_intersect.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add in hillshade for visual effect  <br/>
<img src="https://github.com/JohnDDietrich/GISMontenegro/blob/main/MNE_map.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

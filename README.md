<h1>Habitat Model Montenegro</h1>


<h2>Description</h2>
This project consists of using a DEM and water bodies vector files to model habitat for a hypothetical organism occuring in Montenegro.  This hypothetical organism has habitat requirements that limit its' range to areas above 1500m within 1km of water.
<br />


<h2>Techniques Used</h2>

- <b>Raster classification</b> 
- <b>Buffer</b>
- <b>Intersect</b>
- <b>Hillshade</b>

<h2>Software Used </h2>

- <b>QGIS</b>

<h2>Step by step processing</h2>

<p align="center">
Classify raster to separate everthing above 1500m (shown in green):

<img src="https://github.com/JohnDDietrich/GISMontenegro/blob/main/Classify.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add in water features  <br/>
<img src="https://github.com/JohnDDietrich/GISMontenegro/blob/main/buffer1.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a 1km buffer around water features  <br/>
<img src="https://github.com/JohnDDietrich/GISMontenegro/blob/main/Buffer2.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Find intersection between water buffer and 1500+ elevation polygons <br/>
<img src="https://github.com/JohnDDietrich/GISMontenegro/blob/main/intersect.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Potential habitat is delineated in red. Hillshade added for visual effect  <br/>
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

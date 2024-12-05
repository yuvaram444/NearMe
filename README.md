# Ex04 Places Around Me
## Date: 05.12.2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
<html>
    <head>
        <title>TRICHY</title>
    </head>
    <body>
        <div style="text-align: center;">
        <h1 > Explore My Neighbourhood</h1>
        <h2> Please click any of the pictures in the middle to know more about it</h2>
        
            <div style="text-align: center;">
            <img src="c:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2024-12-04 113151.png" alt=""  usemap="#Landmark" style="width: fit-content;">
            </div>
         <map name="Landmark">
            <area shape="circle" coords="1319,291,12" title="Kallanai Dam" href="C:\Users\admin\NearMe\imgmap\imgapp\static\kall.html">
            <area shape="circle" coords="564,775,16" title="Tiruchirappalli InterNational Airport" href="C:\Users\admin\NearMe\imgmap\imgapp\static\airp.html">
            <area shape="circle" coords="485,591,17" title="Trichy" href="C:\Users\admin\NearMe\imgmap\imgapp\static\tri.html">
            <area shape="circle" coords="1239,806,14" title="NIT" href="C:\Users\admin\NearMe\imgmap\imgapp\static\nit.html">
            <area shape="circle" coords="316,181,16" title="Theppakulam" href="C:\Users\admin\NearMe\imgmap\imgapp\static\thep.html">
            <area shape="circle" coords="" title="Srirangam" href="">
         </map>
        </div>
    </body>
</html>
```
## OUTPUT
 ![alt text](<Screenshot 2024-12-05 224528.png>)
 # Trichy
 ![alt text](<Screenshot 2024-12-05 224620.png>)
 ![alt text](<Screenshot 2024-12-05 224630.png>)
 # Theppakulam
 ![alt text](<Screenshot 2024-12-05 224603.png>)
 # NIT
 ![alt text](<Screenshot 2024-12-05 224758.png>)
 ![alt text](<Screenshot 2024-12-05 224810.png>)
 ![alt text](<Screenshot 2024-12-05 224819.png>)
 # Kallanai
 ![alt text](<Screenshot 2024-12-05 225354.png>)
 # Airport
 ![alt text](<Screenshot 2024-12-05 224700.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.

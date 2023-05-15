# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Create a new django project and app
### Step 2:
Add a new imagemap html file in templates and neede images in static folder and define it in settings.
### Step 3:
Type ur image map code in the html with coordinates and target file to redirect on click
### Step 4:
Define your components pages and create content in such a way that it gives information about place which is being clicked
### Step 5:
Include pictures and contents for your subpages and map them using urls and views
## Code:
```

<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>myplaces</title>
</head>
<body>
   
<img id="Image-Maps-Com-image-maps-2023-04-19-142410" src="images/sivakasi.jpg" border="0" width="1819" height="938" orgWidth="1819" orgHeight="938" usemap="#image-maps-2023-04-19-142410" alt="" />
<map name="image-maps-2023-04-19-142410" id="ImageMapsCom-image-maps-2023-04-19-142410">
<area  alt="" title="Bilal-Mahal" href="milal.html" shape="rect" coords="452,285,574,349" style="outline:none;" target="_self"    data-maphilight='Milal-mahal' />
<area  alt="" title="Bell-Hotel" href="bellhotel.html" shape="rect" coords="606,219,720,281" style="outline:none;" target="_self"    data-maphilight='Bell-Hotel' />
<area  alt="" title="SIvakasi-lions" href="sivakasi.html" shape="rect" coords="1168,353,1357,453" style="outline:none;" target="_self"    data-maphilight='Sivakasi-lions-school
' />
<area  alt="" title="Theatre" href="theatre.html" shape="rect" coords="1340,208,1558,308" style="outline:none;" target="_self"    data-maphilight='Theatre' />
<area  alt="" title="Samsung" href="samsung.html" shape="rect" coords="791,581,1029,681" style="outline:none;" target="_self"    data-maphilight='Samsung-Mobiles
' />
<area shape="rect" coords="1817,936,1819,938" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
</map>


</body>
</html> 



```

## Output:
![map](imagemap.png)

## Result:
Thus a website is developed to display details about my school near my house.

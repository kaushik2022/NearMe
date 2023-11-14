# Ex04 Places Around Me

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

## map.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Map
        </title>
    </head>
    <body >
        <h1 align="center" >
            <font color="red" >
                    KODAIKANAL
            </font>


            
        </h1>
        <h3 align="center">
        <font color="blue" face ="cursive">
            K.KAUSHIK(212222040074)
        </font>
            
        </h3>
        <center>
        <img id="Image-Maps-Com-image-maps-2023-04-18-204107" src="/static/images/myhome.png" border="0" width="1828" height="788" orgWidth="1828" orgHeight="788" usemap="#image-maps-2023-04-18-204107" alt="" />
        <map name="image-maps-2023-04-18-204107" id="ImageMapsCom-image-maps-2023-04-18-204107">
            <area  alt="" title="Poombarai" href="poombarai.html" shape="rect" coords="1198,726,1248,776" style="outline:none;" target="_self"     />
            <area  alt="" title="Lake" href="lake.html" shape="rect" coords="1526,261,1576,311" style="outline:none;" target="_self"     />
            <area  alt="" title="Resort" href="resort.html" shape="rect" coords="963,671,1013,721" style="outline:none;" target="_self"     />
            <area  alt="" title="Land" href="land.html" shape="rect" coords="404,129,454,179" style="outline:none;" target="_self"     />
            <area  alt="" title="Valley" href="valley.html" shape="rect" coords="465,421,515,471" style="outline:none;" target="_self"     />
            <area shape="rect" coords="1826,786,1828,788" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
        </map>


        </center>
        <p align="center">
            <font color="maroon"  face="Comic Sans MS" >
                This Image Map shows various locations around my home.<br>
                Click the location and get information about it.
            </font>
            
            
            
            
</p>


</body>

</html>
```
## lake.html

```
<!DOCTYPE html>
<html>
<head>
    <title>
        BERIJAM LAKE
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        BERIJAM LAKE
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>Best place to visit.<br></LI>     
            <LI>Best boating and can have a nice experience.<br></LI>
            <LI>Nice place to visit for family and friends.<br></LI>
        </OL>


    </font>
    <font color ="red" face = "cursive" size="16" > 
    "LOSE YOUR HEART TO KODAIKANAL HILLS"
    </font>




</p>


</body>


</html>
```
## land.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        GREEN LANDS
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        GREEN LANDS
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>With greenish feel and nice appearance.<br></LI>     
            <LI>Peaceful place ever.<br></LI>
            <LI>Best place to visit.<br></LI>
        </OL>


    </font>
    <font color ="red" face = "cursive" size="16" > 
    "IF THE ICE MELTS IN GREENLAND IT CAN SHUTDOWN THE GULF CURRENT"
    </font>




</p>


</body>


</html>
```

## poombarai.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        POOMBARAI
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        POOMBARAI
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>Poombarai is a small village.<br></LI>     
            <LI>Near poombarai there are many lakes, falls,etc.<br></LI>
            <LI>Poombarai has a good agriculture.<br></LI>
            <LI>It is the tourist place in kodaikanal.<br></LI>
        </OL>


    </font>
    <font color ="red" face = "cursive" size="16" > 
        "HAPPINESS IS NOT A  STATE TO ARRIVE AT,BUT A MANNER OF TRAVELLING."
    </font>




</p>


</body>


</html>
```
## resort.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        KODAI MIST RESORT
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        KODAI MIST RESORT
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is the resort with well organised rooms.<br></LI>     
            <LI>In this resort there is camfire.<br></LI>
            <LI>They provide foods.<br></LI>
            <LI>Best resort to stay in kodaikanal.<br></LI>
        </OL>


    </font>
    <font color ="red" face = "cursive" size="16" > 
    "THE PRINCESS OF HILL STATION"
    </font>
    
    
    
 </p>
    
 </body>
    
 </html>
 ```
## valley.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        SILENT VALLEY VIEW
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        SILENT VALLEY VIEW
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>Best place to visit.<br></LI>     
            <LI>Silent place for the people who searching for peace.<br></LI>
            <LI>Many peoples celebrate their birthdays there.<br></LI>
            <LI>The greenish feel with peace.<br></LI>
        </OL>


    </font>
    <font color ="red" face = "cursive" size="16" > 
    "THE WORLD IS A BOOK AND THOSE WHO NOT TRAVEL READ ONLY ONE PAGE"
    </font>




</p>


</body>

</html>
```
## OUTPUT

## map.html

![map html](https://github.com/amrutha23ashok/NearMe/assets/120772913/7190e3ac-9c30-47ca-8efc-365d8dfe54a7)

## lake.html

![lake html](https://github.com/amrutha23ashok/NearMe/assets/120772913/a864e4f8-ad2e-45be-80fc-5ad484e5042b)

## land.html

![land html](https://github.com/amrutha23ashok/NearMe/assets/120772913/6c19833b-3322-4898-94ef-711c917acdd8)

## poombarai.html

![poombarai html](https://github.com/amrutha23ashok/NearMe/assets/120772913/932b9647-9d52-4dfa-af7e-9c25e1d4baa4)

## resort.html

![resort html](https://github.com/amrutha23ashok/NearMe/assets/120772913/cba9f6c7-132c-429c-b9b5-30d83d865018)

## valley.html

![valley html](https://github.com/amrutha23ashok/NearMe/assets/120772913/c69de350-e200-4f96-86fe-251f03576e50)

## RESULT

The program for implementing image maps using HTML is executed successfully.

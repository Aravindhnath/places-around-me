# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Create a new Django project.
### Step 2:
Add a view and template to your Django project
### Step 3:
Take screenshots of places around your house using Google Maps.
### Step 4:
Identify a minimum of five different locations and mark them using image maps.
### Step 5:
Develop a webpage(minimum of 50 words) for each location and link it to the image region

## Code:
index.html
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
                    Image Map Of My Home Town
            </font>
        </h1>
        <h3 align="center">
        <font color="blue" face ="cursive">
            ARAVINDHNATH TR (212222100005)
        </font>
        </h3>
        <center>
        <img id="Image-Maps-Com-image-maps-2023-04-20-031915" src="mymap.jpg" border="0" width="1457" height="807" orgWidth="1457" orgHeight="807" usemap="#image-maps-2023-04-20-031915" alt="" />
<map name="image-maps-2023-04-20-031915" id="ImageMapsCom-image-maps-2023-04-20-031915">
<area  alt="" title="Swamythopu Pathi-temple" href="temple.html" shape="rect" coords="481,647,531,697" style="outline:none;" target="_self"     />
<area  alt="" title="Raja Nursery Garden" href="nursery.html" shape="rect" coords="788,454.99999237060547,838,504.99999237060547" style="outline:none;" target="_self"     />
<area  alt="" title="My Home" href="home.html" shape="rect" coords="897,161,947,211" style="outline:none;" target="_self"     />
<area  alt="" title="My School" href="school.html" shape="rect" coords="468,521,518,571" style="outline:none;" target="_self"     />
<area  alt="" title="Tiffin Centre" href="shop.html" shape="rect" coords="1226,365,1276,415" style="outline:none;" target="_self"     />
<area shape="rect" coords="1455,805,1457,807" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
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
home.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        HOME
    </title>
</head>
<body bgcolor='violet'>
<h1 align="center">
    <font color="blue" face="cursive" size='16'>
        MY HOME
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is my home where I live happy with my family.<br></LI>     
            <LI>My mother and Father take cares of me and I have fun with my siblings and my pets.<br></LI>
            <LI>My pets are the loved ones because they keep me always engaging.<br></LI>
            <LI>When I feel stress, I used to visit my farms around my house and the nature and its beauty makes me to feel better.<br></LI>
        </OL>


    </font>
    <font color ="red" face = "cursive" size="16" > 
    "HOME IS WHERE OUR STORY BEGINS"
    </font>
</p>
</body>
</html>
```
nursery.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        NURSERY
    </title>
</head>
<body bgcolor='lightgreen'>
<h1 align="center">
    <font color="blue" face="cursive" size='16'>
        NURSERY
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is a place where we can see lots of plants and trees.<br></LI>     
            <LI>It is almost a mini forest.<br></LI>
            <LI>Many little and cute birds,animals and insects are found here.<br></LI>
            <LI>I used to spend time here as it's a great feeling to enjoy the nature alongby watering the plants.<br></LI>
        </OL>


</p>
</body>
</html>
```
school.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        SCHOOL
    </title>
</head>
<body bgcolor="orange">
<h1 align="center">
    <font color="blue" face="cursive" size='16'>
        MY SCHOOL
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is a place where I completed my high school grade.<br></LI>     
            <LI>I got many new friends and even friendly staffs.<br></LI>
            <LI>I got too learn many new things and got many experiences about life and so on.<br></LI>
            <LI>My passion about chess started from here.<br></LI>
        </OL>

</p>
</body>
</html>
```
shop.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        SHOP
    </title>
</head>
<body bgcolor="pink">
<h1 align="center">
    <font color="blue" face="cursive" size='16'>
        SHOP
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is the place where I eat breakfast often.<br></LI>     
            <LI>Every evening I get here to enjoy the lovely tea given by the shopkeeper.<br></LI>
            <LI>I have great conversation with the shopkeeper about the life and he motivates me a lot to focus on my passion.<br></LI>
            <LI>I play with their daughter as she is very very cute.<br></LI>
        </OL>
</p>
</body>
</html>
```
temple.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        TEMPLE
    </title>
</head>
<body bgcolor="yellow">
<h1 align="center">
    <font color="blue" face="cursive" size='16'>
        TEMPLE
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>I come here to worship the God.<br></LI>     
            <LI>It's a very famous place, even the streets of the temple would be busy on every Sundays.<br></LI>
            <LI>Since my childhood, I play a lot here with my village friends.<br></LI>
            <LI>It feels good whenever I go and worship in the temple.<br></LI>
        </OL>
</p>
</body>
</html>
```

## Output:
MAP:
![map](Output/map.png)
HOME:
![home](Output/home.png)
SCHOOL:
![school](Output/school.png)
NURSERY:
![nursery](Output/nursery.png)
SHOP:
![shop](Output/shop.png)
TEMPLE:
![temple](Output/temple.png)

## Result:
Thus the locations are located and their informations are linked using HTML code.
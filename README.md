# Ex04 Places Around Me
# Date:31/10/2023
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
# map.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Tirunelveli  - Halwa City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Selva Kumar A (212222110042)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="a.html" title="Arulmigu Nellaiappar Temple">
<area shape="rectangle" coords="230,30,260,60" href="b.html" title="Einstein College of Engineering">
<area shape="circle" coords="400,350,50" href="c.html" title="Thamirabarani River">
<area shape="circle" coords="400,200,75" href="d.html" title="Govt.ADW higher secondary school">
<area shape="rectangle" coords="490,150,870,320" href="e.html" title="Sankar Cements Cricket Ground">
</map>
</center>
</body>
</html>
~~~

# a.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<title> Temple</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Tirunelveli  - Halwa City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Arulmigu Nellaiappar Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of  are Arulmigu Nellaiappar Temple.
<ul>
<li>The Nellaiappar Temple is a Hindu temple dedicated to the deity Shiva, located in Tirunelveli, a city in the South Indian state of Tamil Nadu. .</li>
<li> Shiva is worshipped as Nellaiappar represented by the lingam and his consort Parvati is depicted as Kanthimathi Amman.</li>
<li>The temple complex is spread over an area of 14 acres and consists of several shrines and mandapams (halls)</li>
<li>The temple has three six rituals at various times from 6:00 a.m. to 9:00 p.m., and six yearly festivals on its calendar. </li>
</ul>
</font>
</p>
</body>
</html>
~~~
~~~
b.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Einstein College of Engineering</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Tirunelveli  - Halwa City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Einstein College of Engineering</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
Einstein college of engineering offered courses
<ul>
<b>
    <li>BE Civil Engineering</li>
    <li>BE Computer engineering</li>
   <li> BE  Electronics and Communications Engineering</li>
</b>
</font>
</p>
</body>
</html>
~~~
# c.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<title>Thamirabarani River</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Tirunelveli  - Halwa City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thamirabarani River</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The uses of Thamirabarani River in Tirunelveli District are 
<ol type="1">
<li>Lake is used for rain water harvesting.</li>
<li>It is used for drinking.</li>
<li>Pisculture.</li>
<li>For bathing, washing clothes etc.</li>
</ol>
</font>
</p>
</body>
</html>
~~~
# d.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<title>Govt. High. Sec. School</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Tirunelveli  - Halwa City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Govt.ADW higher secondary school</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of Tirunelveli Government Higher Secondary School are 
<ul>
<li>To impart proper and qualified training to teachers and give them an attractive salary and incentives so that they are not tempted to quit and look elsewhere for jobs.</li>
<li>To provide financial aids and grants wisely and judiciously.</li>
<li>To Frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>
</ul>
</font>
</p>
</body>
</html>
~~~
# e.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<title>Cricket Ground</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Tirunelveli  - Halwa City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sankar Cements Cricket Ground</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
    Cricket ground 
<ul> Indian Cement Company Ground, also known as ICL Sankar Nagar Cricket Ground is a cricket ground located in Tirunelveli in Tamil Nadu, India.[2][3] The ground is in Bala Vidyalaya School run by India Cements.[4] It is adjacent to the NH 44 in the village of Thaliyuthu.[4][5]

    From 2016, the ground has been used for hosting Tamil Nadu Premier League (TNPL) matches.[6][7][8] As of 2020, it has hosted eight first-class and two List A cricket matches.[9]
</font></ul>
   
</p>
</body>
</html>
~~~
## OUTPUT
# Map.html:
![image](https://github.com/Selvakumar525/NearMe/assets/120643262/a7cc86a2-fa8f-453d-817a-c6bf770337e6)
# a.html:
![image](https://github.com/Selvakumar525/NearMe/assets/120643262/6067257b-fe54-4c87-b2d8-6def3241218c)

# b.html:
![b html](https://github.com/Selvakumar525/NearMe/assets/120643262/0f7e8bb9-3381-4794-9921-c4a14afef5fa)


# c.html:
![c html](https://github.com/Selvakumar525/NearMe/assets/120643262/3351fd37-d254-478a-884b-c31c56f3d510)

# d.html:
![d html](https://github.com/Selvakumar525/NearMe/assets/120643262/0d7e6678-bd5f-4d1a-ab46-09bd9857f846)

# e.html:
![e html](https://github.com/Selvakumar525/NearMe/assets/120643262/0cc282f3-a752-4050-9fa7-cd3a2dc77a3b)


## RESULT
The program for implementing image maps using HTML is executed successfully.

# Ex04 Places Around Me
## Date: 7/10/25

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
map.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <img src="Screenshot 2025-10-08 204326.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="home town" title="home town" href="ko.html" coords="637,328,835,502" shape="rect">
    <area target="" alt="electrical famous" title="electrical famous" href="po.html" coords="1222,471,1070,325" shape="rect">
    <area target="" alt="famous of temple" title="famous of temple" href="gut.html" coords="90,404,235,522" shape="rect">
    <area target="" alt="super market" title="super market" href="na.html" coords="1231,156,1390,325" shape="rect">
    <area target="" alt="textiles" title="textiles" href="ka.html" coords="462,738,678,838" shape="rect">
</map>
</body>
</html>

ko.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>NATTRAMPALLI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>kothur - Home Town</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Kothur is a village in the Natrampalli Taluk of Tamil Nadu, located within what was formerly the Vellore district and is now part of the Tirupathur district. Natrampalli is a town and administrative hub for the surrounding villages, with agricultural activities as a key economic driver. 
</font>
</p>
</body>
</html>

na.html

<html>
<head>
<title>supermarket</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="red"><b>NATTRAMPALLI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>sorakayalnatham - super market</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
- Sorakayalnatham is a village in Natrampalli Block, part of Tirupattur Taluka.
- It falls under the Sorakayalnatham Gram Panchayat and is governed locally by this body.
- The pincode for the village is 635854.
- The nearest town for major economic activities is Natrampalli, located about 3–5 km away.


</font>
</p>
</body>
</html>

ka.html

<html>
<head>
<title>textiles</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>NATTRAMPALLI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>bargur - textiles</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Bargur textiles refer to the fabric markets and vendors in Bargur, a town in Krishnagiri district, Tamil Nadu, known for its diverse textile offerings including cotton and silk, and a wide range of ready-made garments. The Bargur Textile Market is a hub for retailers and offers various types of fabric and clothes for all ages at reasonable prices. 
</font>
</p>
</body>
</html>

po.html

<html>
<head>
<title>electrical famous</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="red"><b>NATTRAMPALLI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>pathur-electrical famous</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
 - Patchur is a small village in Natrampalli Block, previously part of Vellore District, now under Tirupattur District.
- It falls under the Patchur Panchayat and is located about 10 km from Natrampalli town.
- The PIN code is 635854, and the postal head office is also in Patchur.


</font>
</p>
</body>
</html>

gut.html

<html>
<head>
<title>temple</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="red"><b>NATTRAMPALLI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>gutleeti - temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">

- Gutletti is one of the villages under the Natrampalli revenue block in Tirupattur district.
- It is governed by a local Gram Panchayat and falls under the jurisdiction of Tirupattur Taluka.
- The village is part of the Jolarpettai Assembly Constituency and Tiruvannamalai Lok Sabha Constituency
</font>
</p>
</body>
</html>
```





## OUTPUT
![alt text](<Screenshot 2025-10-08 215057.png>)
![alt text](<Screenshot 2025-10-08 215112.png>)
![alt text](<Screenshot 2025-10-08 215125.png>)
![alt text](<Screenshot 2025-10-08 215138.png>)
![alt text](<Screenshot 2025-10-08 215151.png>)
![alt text](<Screenshot 2025-10-08 220823.png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.

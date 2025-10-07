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
map.html
<html>
<head>
    <title>sample page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1 align="center">
        <font color="blue"><b>TENKASI</b></font>
    </h1>
    <h2 align="center">
        <font color="blue"><b>KARTHIGA SRI</b></font>
    </h2>
    <center>
        <img src="Screenshot 2025-10-08 012027.png" usemap="#image-map" height="800" width="1500">

<map name="image-map">
    <area target="" alt="Krishna tourist home" title="Krishna tourist home" href="touristhome.html" coords="948,128,1152,164" shape="rect">
    <area target="" alt="Zamin resort" title="Zamin resort" href="resort.html" coords="234,466,314,492,314,520,244,535,166,514,164,483" shape="poly">
    <area target="" alt="Yasuragi boutique resort" title="Yasuragi boutique resort" href="boutique.html" coords="92,240,88" shape="circle">
    <area target="" alt="Drizzle residence" title="Drizzle residence" href="residence.html" coords="588,695,684,739" shape="rect">
    <area target="" alt="Mount zion holiday" title="Mount zion holiday" href="hotel.html" coords="745,456,71" shape="circle">
</map>
        </map>
    </center>
</body>
</html>

boutique.html
<html>
    <head>
        <title>boutique</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
         <font color="blue"><b>TENKASI</b></font>  
        </h1>
        <h3 align="center">
            <font color="black"<b>Yasuragi boutique resort</b>
        </h3>
        <hr>
        <p font color="black">The Yasuragi Boutique Resort in Shencottah, Tamil Nadu, offers a tranquil escape with air-conditioned rooms, a swimming pool, a garden, and on-site dining. Located near attractions like Palaruvi Waterfall and Courtallam Falls, it provides various accommodation options, including family rooms and luxury suites, with amenities like free Wi-Fi, a restaurant serving local cuisine, and paid services such as airport shuttles and cycling rentals. </p>
        
    </body>
</html>

hotel.html
<html>
    <head>
        <title>Resort</title>
    </head>
    <body bgcolor="grey">
        <h1 align="center">
         <font color="blue"><b>TENKASI</b></font>  
        </h1>
        <h3 align="center">
            <font color="black"<b>Mount zion holiday</b>
        </h3>
        <hr>
        <p font color="black">"Shenkottai Mount Zion Holiday" refers to a hotel in Tirunelveli, Tamil Nadu, that offers accommodation with a focus on nature and peace, featuring rooms with balconies and air conditioning, and is suitable for peace-lovers. While "Mount Zion Adventure Holidays" is a separate vacation rental in the Palakkad district of Kerala, the user's query likely points to the Tirunelveli property. </p>
        
    </body>
</html>

residence.html
<html>
    <head>
        <title>Residence</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
         <font color="blue"><b>TENKASI</b></font>  
        </h1>
        <h3 align="center">
            <font color="black"<b>Drizzle residence</b>
        </h3>
        <hr>
        <p font color="black">Drizzle Residence is a luxury hotel in Courtallam, Tamil Nadu, known for its picturesque location near waterfalls and dams, modern facilities including unique OTT projector rooms, and a range of services like room service, a doctor on call, and personalized concierge service. Founded in 2024, it offers a blend of comfort and nature with a mission to provide personalized, unforgettable experiences, focusing on exceptional service and setting new standards in excellence.  </p>
        
    </body>
</html>

resort.html
<html>
    <head>
        <title>Zamin resort</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
         <font color="blue"><b>TENKASI</b></font>  
        </h1>
        <h3 align="center">
            <font color="black"<b>Zamin resort-Resort</b>
        </h3>
        <hr>
        <p font color="black">Krishna Tourist Home is a hotel located in Tenkasi, Tamil Nadu, offering amenities like free parking, WiFi, and an on-site restaurant. The hotel provides a comfortable, home-like atmosphere, with 24-hour room service, luggage storage, and safety deposit boxes available for guests</p>
        
    </body>
</html>

touristhome.html
<html>
    <head>
        <title>Krishna tourist home-Resort</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
         <font color="blue"><b>TENKASI</b></font>  
        </h1>
        <h3 align="center">
            <font color="black"<b>Krishna tourist home-Resort</b>
            </h3>
        <hr>
        <p font color="black">Krishna Tourist Home is a hotel located in Tenkasi, Tamil Nadu, offering amenities like free parking, WiFi, and an on-site restaurant. The hotel provides a comfortable, home-like atmosphere, with 24-hour room service, luggage storage, and safety deposit boxes available for guests</p>
        
    </body>
</html>





## OUTPUT

![alt text](<preethi/preethi/static/Screenshot 2025-10-08 012027.png>)
![alt text](<preethi/preethi/static/Screenshot 2025-10-08 014544.png>)
![alt text](<preethi/preethi/static/Screenshot 2025-10-08 014606.png>)
![alt text](<preethi/preethi/static/Screenshot 2025-10-08 014618.png>)
![alt text](<preethi/preethi/static/Screenshot 2025-10-08 014631.png>)
![alt text](<preethi/preethi/static/Screenshot 2025-10-08 014646.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.

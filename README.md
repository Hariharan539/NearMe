# Ex04 Places Around Me
## Date: 27/04/2025
## Reg No:212224220032

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
  <title>MY CITY</title>
</head>
<body bgcolor="beige">
  <h1 align="center"><b>TIRUPATTUR</b></h1>
  <h3 align="center"><b>HARIHARAN V(212224220032)</b></h3>
  <center>
  <img src="Map.png" alt="Map of my Area" usemap="#mymap" width="1450" height="610">
  <map name="mymap">
    <area shape="rect" coords="700,250,850,400" href="hills.html" alt="YELAGIRI HILLS">
    <area shape="rect" coords="581,390,596,519" href="temple.html" alt="PUTHU KOVIL">
    <area shape="rect" coords="118,144,970,154" href="hotel.html" alt="HOTEL HILLS">
    <area shape="rect" coords="1452,888,1542,869" href="school.html" alt="SRI VIJAY VIDHYALAYA">
    <area shape="rect" coords="1363,750,1558,813" href="theatre.html" alt="RAMAJAYAM THEATRE">

</center>
 
  </map>
</body>~
</html>

hills.html
<html>
  <head>
    <title>My Home Town</title>
  </head>
  <body bgcolor="DARK GREEN">
    <h1 align="center">
      <font color="beige"><b><u>TIRUPATTUR</u></b></font>
    </h1>

    <h3 align="center">
      <font color="BLACK"><b>YELAGIRI HILLS</b></font>
    </h3>

    <hr size="3" color="gold">

    <p align="justify">
      <font color="bLACK" face="Georgia" size="5">
        Yelagiri Hills, nestled in the Eastern Ghats of Tamil Nadu, is a serene hill station at an elevation of 1,410 meters above sea level.
         Located between Vaniyambadi and Jolarpettai, it offers a peaceful retreat with pleasant weather year-round, making it an ideal 
         destination for nature lovers and adventure enthusiasts.
      </font>
    </p>
  </body>
</html>

temple.html
<html>
  <head>
    <title>My Home Town</title>
  </head>
  <body bgcolor="dark green">
    <h1 align="center">
      <font color="beige"><b><u>TIRUPATTUR</u></b></font>
    </h1>

    <h3 align="center">
      <font color="black"><b>PUTHU KOVIL</b></font>
    </h3>

    <hr size="3" color="gold">

    <p align="justify">
      <font color="black" face="Georgia" size="5">
        Puthu Kovil in Tirupattur—specifically near Natrampalli—is a well-known Amman (Goddess) temple in Tamil Nadu.
        The name "Puthu Kovil" literally means "New Temple" in Tamil, but in this context, it refers to a specific local 
        temple rather than just a new structure.
      </font>
    </p>
  </body>
</html>

hotel.html
<html>
  <head>
    <title>My Home Town</title>
  </head>
  <body bgcolor="DARK GREEN">
    <h1 align="center">
      <font color="beige"><b><u>TIRUPATTUR</u></b></font>
    </h1>

    <h3 align="center">
      <font color="BLACK"><b>HOTEL HILLS</b></font>
    </h3>

    <hr size="3" color="gold">

    <p align="justify">
      <font color="bLACK" face="Georgia" size="5">
        Hotel Hills in Tirupattur, Tamil Nadu, is a contemporary business hotel situated on Krishnagiri Road, approximately 2 km from 
        the Tirupattur Railway Station and 1.6 km from the Bus Stand. This 5-story property offers a blend of comfort and convenience,
         making it a preferred choice for both business and leisure travelers.​
      </font>
    </p>
  </body>
</html>

school.html
<html>
  <head>
    <title>My Home Town</title>
  </head>
  <body bgcolor="DARK GREEN">
    <h1 align="center">
      <font color="beige"><b><u>TIRUPATTUR</u></b></font>
    </h1>

    <h3 align="center">
      <font color="BLACK"><b>SRI VIJAY VIDHYALAYA SCHOOL</b></font>
    </h3>

    <hr size="3" color="gold">

    <p align="justify">
      <font color="bLACK" face="Georgia" size="5">
        Sri Vijay Vidyalaya School in Tirupattur, Tamil Nadu, is part of the renowned Vijay Vidyalaya Group of Institutions, 
        which has been providing quality education for over three decades. The institution operates two branches in Tirupattur:
      </font>
    </p>
  </body>
</html>

theatre.html
<html>
  <head>
    <title>My Home Town</title>
  </head>
  <body bgcolor="DARK GREEN">
    <h1 align="center">
      <font color="beige"><b><u>TIRUPATTUR</u></b></font>
    </h1>

    <h3 align="center">
      <font color="BLACK"><b>RAMAJAYAM THEATRE</b></font>
    </h3>

    <hr size="3" color="gold">

    <p align="justify">
      <font color="bLACK" face="Georgia" size="5">
        Sri Ramajeyam Theatre A/C 4K is a modern cinema hall located in Achamangalam, near Tirupattur, Tamil Nadu.
         It is renowned for its state-of-the-art facilities, including 4K resolution and Dolby Atmos sound system, providing an
          immersive movie-watching experience.
      </font>
    </p>
  </body>
</html>
```

## OUTPUT!
![alt text](<Screenshot 2025-04-26 205451.png>)
![alt text](<Screenshot 2025-04-26 205410.png>)
![alt text](<Screenshot 2025-04-26 205434.png>)
![alt text](<Screenshot 2025-04-26 205502.png>)
![alt text](<Screenshot 2025-04-26 205633.png>)
![alt text](<Screenshot 2025-04-26 205717.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.

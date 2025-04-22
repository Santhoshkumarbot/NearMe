# Ex04 Places Around Me
## Date:22/04/2025
## Reg No : 212224040295

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

Map.html
<html>
<head>
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Salem</b></font>
</h1>
<h3 align="center">
<font color= "blue"><b>Santhosh Kumar P(24900711)</b></font>
</h3>
<center>
<img src="map.png" usemap="#myCity" height="610" width="1450">
</center>
<map name="myCity">
<area shape="rect" coords="536,35,712,82" href="salem airport.html" title="SALEM AIRPORT">
<area shape="rect" coords="198,469,421,530" href="natarajan.html" title="NATARAJAN CRICKET ACADEMY">
<area shape="rect" coords="1165,76,1281,127" href="yercaud.html" title="YERCAUD">
<area shape="circle" coords="822,980,1049,1023" href="paravasa ulagam.html" title="PARAVASA ULAGAM">
<area shape="circle" coords="1150,949,1311,1012" href="bothamalai.html" title="BOTHAMALAI">
</map>

</body>
</htm1>

Salem airport.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY AREA</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>SALEM</b></font>
    </h1>
    <h3 align="center">
        <b>SALEM AIRPORT</b>
    </h3>
    <hr size="3" color="red">
    <br>
    <p align="justify" style="word-spacing: 5px;padding: 5px;line-height: 30px;">
        <font face="Georgia" size="3">
            Salem Airport (IATA: SXV, ICAO: VOSM) is a domestic airport located in Kamalapuram, approximately 15 km northwest of Salem city in Tamil Nadu, India. It serves the Salem metropolitan area and surrounding districts, including Dharmapuri, Krishnagiri, and Namakkal.
            The airport features a single 1,806-meter asphalt runway (04/22) and a terminal building with a capacity to handle 100 passengers. It is equipped with navigational aids such as VHF radio, Precision Approach Path Indicators (PAPI), and a Non-Directional Beacon (NDB).
        </font>
    </p>
</body>
</html>

Natrajan.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY AREA</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>SALEM</b></font>
    </h1>
    <h3 align="center">
        <b>NATARAJAN CRICKET ACADEMY</b>
    </h3>
    <hr size="3" color="red">
    <br>
    <p align="justify" style="word-spacing: 5px;padding: 5px;line-height: 30px;">
        <font face="Georgia" size="3">
            Natarajan Cricket Academy, established by Indian cricketer Thangarasu Natarajan, is located in Chinnappampatti village near Sankagiri, Salem district. The academy aims to identify and nurture young cricketing talent from rural areas, providing them with professional coaching and facilities. The academy's ground features four pitches—two turf, one concrete, and one matting—along with a gym, canteen, and a mini gallery with seating for 100 spectators. Notable personalities, including cricketers Dinesh Karthik, Varun Chakravarthy, and Washington Sundar, have supported the academy's initiatives. The academy operates as a commercial venture, covering expenses for ground maintenance and staff salaries, while offering free training to existing students and nominal fees for new enrollees.
        </font>
    </p>
</body>
</html>


yercaud.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY AREA</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>SALEM</b></font>
    </h1>
    <h3 align="center">
        <b>YERCAUD</b>
    </h3>
    <hr size="3" color="red">
    <br>
    <p align="justify" style="word-spacing: 5px;padding: 5px;line-height: 30px;">
        <font face="Georgia" size="3">
            Yercaud, nestled in the Shevaroy Hills of Tamil Nadu, is a serene hill station known for its lush coffee plantations, citrus orchards, and the picturesque Yercaud Lake. Often referred to as the "Poor Man’s Ooty," it offers a tranquil retreat with attractions like the Shevaroy Temple, Pagoda Point, and Kiliyur Falls. 
Tamil Nadu Tourism.The region enjoys a pleasant climate year-round, with temperatures rarely exceeding 29°C, making it an ideal destination from October to June. 
Indian Holiday.
        </font>
    </p>
</body>
</html>

Paravasa Ulagam.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY AREA</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>SALEM</b></font>
    </h1>
    <h3 align="center">
        <b>PARAVASA ULAGAM</b>
    </h3>
    <hr size="3" color="red">
    <br>
    <p align="justify" style="word-spacing: 5px;padding: 5px;line-height: 30px;">
        <font face="Georgia" size="3">
            Paravasa Ulagam is a popular water and amusement park located in Mallur, approximately 16 km from Salem, Tamil Nadu. Nestled amidst lush greenery and hilly terrain, it offers over 70 rides, including water slides, wave pools, rain dance, lazy river, and dry rides like bungee jumping, mini train, and flying saucer .
            The park operates daily from 10 AM to 6 PM, with entry fees of ₹750 for adults and ₹600 for children (90–130 cm in height). Additional amenities include a food court, changing rooms, lockers, and ample parking space .Paravasa Ulagam is an ideal destination for families and groups seeking a fun-filled day amidst nature.
        </font>
    </p>
</body>
</html>

Bothamalai.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY AREA</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>SALEM</b></font>
    </h1>
    <h3 align="center">
        <b>BOTHAMALAI</b>
    </h3>
    <hr size="3" color="red">
    <br>
    <p align="justify" style="word-spacing: 5px;padding: 5px;line-height: 30px;">
        <font face="Georgia" size="3">
            Bodhamalai, also known as Bodamalai, is a picturesque hill located in the Eastern Ghats of Tamil Nadu, straddling the Salem and Namakkal districts. The hill rises to an elevation of approximately 1,100 meters and extends over 180 square kilometers, with its highest point reaching 1,200 meters above sea level.It serves as a biodiversity hotspot, featuring dense forests and a variety of flora and fauna. The hill is accessible via off-trail trekking from Salem, offering a challenging yet rewarding experience for hikers .
            Notable villages on the hill include Keelur, Melur, and Gedamalai, each contributing to the region's cultural and ecological richness.​
        </font>
    </p>
</body>
</html>


## OUTPUT

[text](<app4/static/salem airport.html>)
[text](app4/static/natarajan.html)
[text](app4/static/yercaud.html)
[text](<app4/static/paravasa ulagam.html>)
[text](app4/static/bothamalai.html)









## RESULT
The program for implementing image maps using HTML is executed successfully.

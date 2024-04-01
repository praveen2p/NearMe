# Ex04 Places Around Me
## Date:20.03.2024 

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
<html>
    <title>Mycity</title>
    <body bgcolor="white">
        <h1 align="center"><font color="black">SIRKALI</font></h1>
        <h3 align="center">
            <font color="blue">PRAVEEN K(212223040152)</font></h3>
        <center>
            <img src="map.png"  usemap="#MyCity" height="550" width="1300">
            <map name="MyCity">
                    <area shape="rect" coords="350,220,400,270" href="Temple.html" title="sattainathar Temple">     
                    <area shape="rect" coords="750,270,850,350" href="school.html" title="SMH marticulation hr sec school">
                    <area shape="rect" coords="400,600,500,650" href="college.html" title="vivekanada college">
                    <area shape="rect" coords="1100,250,900,300" href="hotel.html" title="the grand white palace">
                    <area shape="rect" coords="800,300,750,350" href="tem.html" title="thrivikrama perumal temple">
            </map>
        </center>
       

    </body>
</html>

temple.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">sirkali</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">sattainathar Temple</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Sirkazhi Sattainathar Temple, also known as the Sirkali Temple or Sattainathar Temple, is a renowned Hindu temple located in the town of Sirkazhi in the Indian state of Tamil Nadu. This temple is dedicated to Lord Shiva and is considered one of the prominent pilgrimage sites in the region. The temple holds immense religious significance and attracts devotees from far and wide, especially during festivals and auspicious occasions.

One of the distinctive features of the Sirkazhi Sattainathar Temple is its association with the legendary Saivite saint, Tirugnanasambandar, who is one of the prominent Nayanars, the revered devotees of Lord Shiva. According to legend, Tirugnanasambandar is said to have miraculously revived a dead child at this very site, which further enhances the sanctity and reverence of the temple.
        </font>
        </p>
    </body>
</html>

school.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">sirkali</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">SMH matriculation hr sec school</font>
    </h3>
    <body bgcolor="pink" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            he Sirkali SMM Matriculation Higher Secondary School, often referred to simply as Sirkali SMH School, is a prominent educational institution located in Sirkali, a town in the Nagapattinam district of Tamil Nadu, India. Established with a commitment to providing quality education, the school has earned a reputation for excellence in academics, extracurricular activities, and overall student development.

Founded with the vision of nurturing young minds and preparing them for the challenges of the modern world, Sirkali SMH School offers education from kindergarten through higher secondary levels. The school follows the Matriculation syllabus prescribed by the Tamil Nadu government, ensuring a comprehensive and holistic learning experience for its students.
        </font>
        </p>
    </body>
</html>

college.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">sirkali</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">vivekanada college</font>
    </h3>
    <body bgcolor="yellow" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Sirkali Vivekananda College, situated in Sirkali, a town in the Nagapattinam district of Tamil Nadu, India, is a renowned institution of higher education. Established with the noble vision of providing quality education to the youth of the region, the college is named after Swami Vivekananda, the revered Indian philosopher and spiritual leader known for his contributions to education and social reform.

Founded with the aim of promoting academic excellence, character development, and holistic growth, Sirkali Vivekananda College offers undergraduate and postgraduate programs in various disciplines, including arts, science, commerce, and management. The college is affiliated with Bharathidasan University, Tiruchirappalli, ensuring that its academic programs adhere to the highest standards of quality and relevance.
        </font>
        </p>
    </body>
</html>

hotel.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">sirkali</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">the grand white palace</font>
    </h3>
    <body bgcolor="red" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Nestled amidst the serene surroundings of Sirkali, Tamil Nadu, stands a magnificent architectural marvel known as "The Grand White Palace." This opulent palace, adorned in pristine white, captures the essence of regal splendor and timeless elegance.

The Grand White Palace exudes grandeur from every corner, with its majestic domes, intricate carvings, and sprawling courtyards. As you step through its grand entrance, you're greeted by a sense of awe and wonder, as if transported to a bygone era of kings and queens.
        </font>
        </p>
    </body>
</html>

tem.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">sirkali</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">thrivikrama perumal temple</font>
    </h3>
    <body bgcolor="blue" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Sirkazhi Thiruvikrama Perumal Temple, located in Sirkali, Tamil Nadu, India, is a revered Hindu temple dedicated to Lord Thiruvikrama Perumal, an incarnation of Lord Vishnu. This ancient temple holds significant religious and historical importance and attracts devotees from far and wide who come to seek the blessings of the divine deity.

The Thiruvikrama Perumal Temple is renowned for its architectural grandeur and spiritual ambiance. The temple complex is characterized by its towering gopuram (gateway tower), intricately carved pillars, and sacred sanctums dedicated to various deities. The main deity, Lord Thiruvikrama Perumal, is depicted in a majestic form with one foot raised high, symbolizing his cosmic stride.
        </font>
        </p>
    </body>
</html>


```


## OUTPUT
![map praveen](https://github.com/praveen2p/NearMe/assets/151658061/a7357c45-8d0f-4cf7-8ef6-7d8ab50011bf)
![temple](https://github.com/praveen2p/NearMe/assets/151658061/512d8b32-1602-411c-a26c-34c90b85bf55)
![school](https://github.com/praveen2p/NearMe/assets/151658061/b1e97e86-3107-4462-94a4-674cb60cbfe2)
![college](https://github.com/praveen2p/NearMe/assets/151658061/1328fb55-91da-4023-99ae-a774132f974c)
![hotel](https://github.com/praveen2p/NearMe/assets/151658061/4d81d4fd-619f-46c9-882e-ac05ebd1b7df)
![tem](https://github.com/praveen2p/NearMe/assets/151658061/a3e841d1-ee5d-47b2-86df-73b9a3b5b80f)


## RESULT
The program for implementing image maps using HTML is executed successfully.

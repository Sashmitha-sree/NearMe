# Ex04 Places Around Me
## Date: 

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
'''
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="blue"><b>Vadapalani</b></font>
        </h1>
        <h3 align="center">
            <font color="pink"><b>Sashmitha sree K V (24900551)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
                <area shape="rect" coords="60,350,260,500" href="temple.html" title="Vadapalani murugan temple"> 
                <area shape="rect" coords="1100,400,1260,550" href="park.html" title="Anna walkers park"> 
                <area shape="rect" coords="600,380,850,550" href="power.html" title="Kodambakkam power house"> 
                <area shape="rect" coords="640,70,760,160" href="temple2.html" title="Bharathwajeshwarar temple"> 
                <area shape="rect" coords="1240,110,1500,230" href="college.html" title="Meenakshi engineering college"> 

            </map>
        </center>
    </body>
</html>

temple.html

<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="#BDEDFF"
    <h1 align="center">
        <font color="BLUE"><b>Vadapalani</b></font>
    </h1>
    <h3 align="center">
        <font color="C38EC7"><b>Vadapalani Murugan temple</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="georgia" size="5">
            Vadapalani Murugan Temple is one of the most prominent temples dedicated to Lord Murugan in Chennai, Tamil Nadu.
            Located in the Vadapalani area, the temple has become a major spiritual and cultural hub in the city. 
            It is particularly famous for its beautiful architecture, religious significance, and the large number of devotees who visit regularly.
        </font>
    </p>
</html>

college.html

<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
        <font color="#C38EC7"><b>Vadapalani</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Meenakshi college</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="georgia" size="5">
            Meenakshi College of Engineering affiliated to Anna University & AICTE was established in the year 2001-2002 by the Meenakshi Ammal Trust, Chennai, which is a public charitable educational trust formed for reaching quality education to more and more deserving and aspiring students. The trust members are drawn from various walks of life and are eminent personalities with proven success in education, research and teaching apart from social service.

            The college offers the right opportunity to step into the world of technology in a confident and successful manner. Handpicked courses are offered in tune with industry requirements and trends in technology development. The vision is to emerge as a center of excellence in technical education and provide an outstanding launch-pad for future technocrats.
            
            The college campus is located in the heart of Chennai city and easily accessible from different parts of the suburbs also. A sprawling and spacious layout with a serene and green environment welcomes the students as they step into the college campus. The campus is a well-planned one and has well designed airy and bright classrooms, modern conference and seminar halls, well equipped laboratories, workshops, computer labs, playgrounds, canteen and a health centre.
        </font>
    </p>
    </body>
</html>

park.html

<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="#FDEEF4">
    <h1 align="center">
        <font color="#C38EC7"><b>Vadapalani</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Anna Walking Park</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="georgia" size="5">
            Anna Walkers Park offers a wealth of natural beauty and recreational opportunities.
            Its landscapes can bring a sense of calm and wonder, making outdoor activities both engaging and enjoyable. 
            The park serves as a bridge between the bustling city and tranquil nature, offering a retreat for relaxation and rejuvenation.

            Furthermore, Anna Walkers Park plays a crucial role in preserving the natural environment and promoting sustainable practices.
            By visiting, you support these efforts and help ensure that the park remains a sanctuary for future generations.
            Visiting parks can also improve physical and mental health, as outdoor activities and serene environments keep the body active and the mind refreshed.
            Additionally, it offers a peaceful escape from the hustle and bustle of everyday life, providing a calming and stress-relieving experience.
        </font>
    </p>
    </body>
</html>

power.html

<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="E3E4FA">
    <h1 align="center">
        <font color="#C38EC7"><b>Vadapalani</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Kodambakkam power house</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="georgia" size="5">
            Kodambakkam Power House in Kodambakkam,
            chennai is known to satisfactorily cater to the
            demarids of its customer base. It stands located
            at No 15,, Sivan Koil St, Ganga Hagar, Kodambakkam- 600024. 
            It has earned 90 reviews and aspires to develop a loyal customer base. 
            The business strives to make for a positive experience through its offerings.
        
            Customer centricity is at the core of Kodambakkam Power 
            House in Kodambakkam, Chennai and it is this belief that has led the business 
            to build long- term relationships. Ensuring a positive customer experience,
            making available goods and/or services that are of top-notch quality is given
            prime importance.
           
           
        </font>
    </p>
</html>

temple2.html

<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="D2B9D3">
    <h1 align="center">
        <font color="green"><b>Vadapalani</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Bharathwajeshwarar temple</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="georgia" size="5">
            Thiru Valiswaram or Bharadwajeswarar Temple, Kodambakkam.
            This temple is situated in a by lane off Best Hospital. 
            It is so called because the sage Bharadwaj and Vali worshipped the Sivalinga in this temple.
            There are stucco statues of both facing the main shrine  Moolavar is called Bharadwajeswarar
            and Ambal in a standing posture facing south is called Swarnambigai.  There are separate shrines 
            for Vinayaka, Subramanya, Bairavar, Ramanadheswar and Navagraha.  It is said that the temple is
            more than 700 years old and some chola era inscriptions are there on the west and north walls.
            However one cannot find anything may be due to the fact that the temple was renovated in 2015
            and many additions have been made.There is a chola era Adhi Ganapathy in standing posture which
            is kept just outside the main shrine.  The sthala viruksha is Nagalinga Tree.
           
           
        </font>
    </p>
    </body>
</html>

'''


## OUTPUT

![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (14).png>)
![alt text](<Screenshot (15).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (18).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.

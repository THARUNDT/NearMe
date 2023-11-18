# Ex04 Places Around Me
## Date: 18.11.2023

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
~~~
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Redhills
</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>THARUN D (23013993)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
                <area shape="rect" coords="1200,400,1400,500" href="home.html" title="Redhills">
                <area shape="rect" coords="600,50,700,130" href="temple.html" title="Angala Eshwari Temple">
                <area shape="rect" coords="600,300,1000,550" href="lake.html" title="Puzhal Lake">
                <area shape="rect" coords="1000,30,1200,100" href="office.html" title="Sub Register Office">
                <area shape="rect" coords="140,500,240,580" href="ground.html" title="STAG Cricket Ground">
                <area shape="rect" coords="400,70,580,170" href="church.html" title="Christ The king Church">

            </map>
        </center>
    </body>
</html>

home.html

<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="red"><b>Redhills</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b> My Home Town</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                The first railway proposals for India were made in Madras in 1832. The country's first transport train, Red Hill Railway (built by Arthur Cotton to transport granite for road-building), ran from Red Hills to the Chintadripet bridge in Madras in 1836-1837.[1] A town named Sholavaram has a unused airstrip build by British for World War II. It was originally operated by the Royal Air Force as an airbase during World War II. After the war, it was abandoned until the airstrip was turned into a venue for drag racing. Most notably, the Malayalam actor Jayan was killed in a helicopter accident here during the shooting of his film Kolilakkam on 16 November 1980.

            </font>
        </p>
        </body>
        </html>

ground.html

<html>
    <head>
        <title>GROUND</title>
    </head>
    <body bgcolor="grey">
        <h1 align="center">
            <font color="red"><b>Redhills</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b> STAG CRICKET GROUND</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                A cricket field or cricket oval is a large grass field on which the game of cricket is played. Although generally oval in shape, there is a wide variety within this: some are almost perfect circles, some elongated ovals and some entirely irregular shapes with little or no symmetry – but they will have entirely curved boundaries, almost without exception. There are no fixed dimensions for the field but its diameter usually varies between 450 and 500 feet (140 and 150 m) for men's cricket, and between 360 feet (110 m) and 420 feet (130 m) for women's cricket. Cricket is unusual among major sports (along with golf, Australian rules football and baseball) in that there is no official rule for a fixed-shape ground for professional games. On most grounds, a rope demarcates the perimeter of the field and is known as the boundary.
                
            </font>
        </p>
        </body>
        </html>

church.html

<html>
    <head>
        <title>CHURCH</title>
    </head>
    <body bgcolor="sandel">
        <h1 align="center">
            <font color="red"><b>Redhills</b></font>
        </h1>
        <h3 align="center">
            <font color="white"><b> CHURCH</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                The church serves Christ The King Catholic Parish, which covers Nakasero, Kololo, and Old Kampala.[3] Many worshippers, however, come from other parts of the city and surrounding neighborhoods to pray at this location.[3] As of September 2016, the seating capacity inside the church was about 600.[4] Because of the size of the congregation, there is insufficient space inside the church to accommodate all the worshippers. During mass and other large events, tents are erected outside the church where worshippers follow the proceedings on loudspeakers.[3]
                
            </font>
        </p>
        </body>
        </html>

lake.html

<html>
    <head>
        <title>LAKE</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="red"><b>Redhills</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b> PUZHAL LAKE</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                The Pulhal reservoir was built in 1876 during the British rule in Pulhal, Chennai, The reservoir was originally a small tank with a capacity of 500 million cubic feet (mcft) and two masonry weirs, built using locally available laterite stones, then functioned as surplus weirs to release excess water from the water body. Today, these masonry weirs are water-retaining structures as they have been replaced by two shutters. In 1997, the storage capacity of the water reservoir was increased to 3,300 mcft and the depth to 21.20 ft to cater to the drinking water needs of Chennai and also to store Krishna river water received from Andhra Pradesh through Poondi Reservoir and the Sholavaram Tank. Until 2012, the Water Resources Department (WRD) has only taken up maintenance work worth of ₹ 500,000 every year.[1]
                
            </font>
        </p>
        </body>
        </html>

temple.html

<html>
    <head>
        <title>TEMPLE</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="red"><b>Redhills</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b> ANGALA ESHWARI TEMPLE</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                The main deity at the temple is known as Poongavanathu Amman.[2] The goddess appears in the form of a natural anthill resembling a woman suffering from labour pain, lying with her mouth open.[1] Owing to the presence of Shiva inside the sanctum sanctorum, the idol of Nandi is present in front of the sanctum instead of a lion found normally in a Devi temple, which is considered a rarity.[3] There are shrines to Ganesh, Nataraja, and the philosopher-saint Valluvar near the sanctum sanctorum. Nataraja is known by the name Thandavarayan.[2][4] The sacred tree of the temple is a neem tree located in the outer corridor. Other shrines at the outer corridor include a sacred anthill and shrines of goddess Karumari, Ganesh, and Nagadevas (serpent deities) under the sacred tree.[2] Devotees believe that worshiping the goddess fulfills their wish for a child.[5][6][7]
                
            </font>
        </p>
        </body>
        </html>

office.html

<html>
    <head>
        <title>OFFICE</title>
    </head>
    <body bgcolor="brown">
        <h1 align="center">
            <font color="red"><b>Redhills</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b> SUB REGISTER OFFICE</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" sixe="5">
                A registration office commonly refers to a government agency at which compulsory information must be lodged.

The most common type of a registration offices are companies registration offices, business name registers, and trade register offices. In most countries, trade and company registers are freely accessible (list of company registers). Additional commerce registers include patent registers and trademark registers (e.g. U.S. Patent and Trademark Office).

</font>
</p>
</body>
</html>
~~~

## OUTPUT

![Screenshot 2023-11-18 124640](https://github.com/THARUNDT/NearMe/assets/144871537/ecb504af-228a-4f11-98b1-c583fb70c6fc)
![home](https://github.com/THARUNDT/NearMe/assets/144871537/79e99b3e-903d-4588-8f64-6f733e582359)
![ground](https://github.com/THARUNDT/NearMe/assets/144871537/bd542388-d036-4800-a66d-30d7703c964c)
![church](https://github.com/THARUNDT/NearMe/assets/144871537/e36b8b4d-43b2-4735-8e27-6215701f682e)
![lake](https://github.com/THARUNDT/NearMe/assets/144871537/8598a6f7-209d-479d-a0a6-1f7837a1f408)
![temple](https://github.com/THARUNDT/NearMe/assets/144871537/b58b0e29-0e9f-4782-a05d-cb2ef742ef4c)
![office](https://github.com/THARUNDT/NearMe/assets/144871537/5451985d-3123-4b30-bf18-130b20f92c3a)





## RESULT
The program for implementing image maps using HTML is executed successfully.

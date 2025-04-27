# Ex04 Places Around Me
## Date: 27-04-2025

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
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>KAVIYA V M(24900714)</b></font>
</h3>
<center>
<img src="MAP.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="100,100,700,420" href="home.html" title="My Home Town">
<area shape="rect" coords="950,120,1250,140" href="temple.html" title="Kandhakottam temple ">
<area shape="rect" coords="200,100,700,650" href="stadium.html" title="Jawaralal nehru stadium ">
<area shape="rect" coords="750,520,800,550" href="park.html" title="Chennai park">
<area shape="rect" coords="100,100,900,900" href="college.html" title="Madras medical college"
</map>
</center>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>My Home Town</b></font>
 </h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Chennai formerly known as Madras,is the capital and largest city of Tamil Nadu, the southernmost
    state of India. It is located on the Coromandel Coast of the Bay of Bengal.Historically, the region
    was part of the Chola, Pandya, Pallava and Vijayanagara kingdoms during various eras. The coastal land
    which then contained the fishing village Madrasapattinam, was purchased by the British East India Company
    from the Nayak ruler Chennapa Nayaka in the 17th century.The city was officially renamed as Chennai in 1996.
</font>
</p>
</body>
</html>

college.html

<html>
<head>
<title>Medical college</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="black"><b>Chennai</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>Madras Medical college 
    </b></font>
</h3>
<hr size="3" color="red">
<font face="Georgia" size="5">
    The Government General Hospital was established on 16 November 1647 to treat soldiers of the British East
    India Company.Madras Medical College was established on 2 February 1835.Mary Scharlieb graduated from Madras
    Medical College in 1878.In 1996, when the metropolis of Madras was renamed as Chennai, the name of the college
    also changed to Chennai Medical College. It was later re-renamed back to the Madras Medical College since the 
    college was known worldwide by the older name.In Jan 2011, the hospital was renamed as Rajiv Gandhi Government General Hospital.
</font>
</p>
</body>
</html>

park.html

<html>
<head>
<title>Fort St.George</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="black"><b>Chennai</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>Secretariat Park
    </b></font>
</h3>
<hr size="3" color="red">
<font face="Georgia" size="5">
    The park stretches from the Reserve Bank of India subway to the War Memorial and measures 18.5 acres.
    The park has a grand circular fountain at the centre and pedestrian walkways. Other features in the 
    park include tree court with 18 granite benches laid around the trees, one-acre sunken court that is 
    below the road level for children, two public rest houses, and grand granite plazas for practising yoga. 
    There are three ramps connected to the pathways, enabling people with disability to make use of all parts
    of the park. The walls have murals done by arts students.The central fountain has an abstract design 
    made of an alloy of copper and tin.
</p>
</body>
</html>

stadium.html

<html>
<head>
<title>Jawaralal Nehru stadium</title>
</head>
<body bgcolor="lightgreen">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>Nehru Stadium
    </b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Jawaharlal Nehru Stadium is a multi-purpose stadium in Chennai, India. The stadium is located 
    at Sydenhams Road in Park Town besides the Chennai Central suburban railway station. It has a 
    capacity of 40,000.The stadium was refurbished in 1993 and was named after India's first Prime
    Minister Jawaharlal Nehru. Indian Super League team Chennaiyin FC and Indian Women's League team
    Sethu FC also use the stadium as their home ground. The indoor complex has a seating capacity of
    8,000 and is used to host several indoor sports. There are two concrete basketball courts, two
    beach volleyball courts, three clay volleyball courts, one throw ball court, a roller rink, a handball 
    court, a fencing hall, a boxing ring, and a kabaddi field.
</font>
</p>
</body>
</html>

temple.html

<html>
<head>
<title>Kandhakottam Temple</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>Murugar temple
    </b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Kandhakottam Temple is located at Rasappa Chetty St, Central, Chennai. This temple is situated in a busy location.
    This temple was first built in 1670's. This temple was maintained by the Hindu caste Chettiar 
    which is now undertaken by Government. Here Lord Muruga is the main God with Goddess Vali and Goddess Deivaiyanai.
    Here many cultural events takes place every year.The Kandha kottam temple has its famous yearly festivals of ādi's
    Kirutthigai with silver car, Aippasi's Kandha Shashti & Deivānai Thiru kalyānam, Karthigai's Deepam, Thai's Brahmotsavam,
    Thai Poosam, Panguni's Utthiram and the monthly festivals of Kirutthigai and Kandha Shashti.  
</font>
</p>
</body>
</html>

```

## OUTPUT

![alt text](<home town.png>)
![alt text](<home html.png>)
![alt text](<college html.png>)
![alt text](<park html.png>)
![alt text](<stadium html.png>)
![alt text](<temple html.png>)!


## RESULT
The program for implementing image maps using HTML is executed successfully.

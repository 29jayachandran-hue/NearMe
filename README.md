# Ex03 Places Around Me
## Date: 29/11/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
        <title>map.html</title>
        <body align="center">
            <h1 align="center" style="color:blue">RANIPET</h1>
            <h3 style="color:red">Jayachandran Anbarasan (25015034)</h3>
            <img src="Screenshot 2025-11-28 112650.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="thazhampoo falls" title="thazhampoo falls" href="falls.html" coords="963,4,1166,48" shape="rect">
    <area target="" alt="sri kulirchilingeswarar" title="sri kulirchilingeswarar" href="temple.html" coords="301,678,111" shape="circle">
    <area target="" alt="karigiri" title="karigiri" href="place.html" coords="195,166,193,193,120,193,104,150,187,135,197,168" shape="poly">
    <area target="" alt="smarttech shuttle" title="smarttech shuttle" href="tech.html" coords="505,255,690,312" shape="rect">
    <area target="" alt="kanchanagiri shivan  malai" title="kanchanagiri shivan  malai" href="templeii.html" coords="775,109,94" shape="circle">
</map>
        </body>
        
    </head>
</html>
```
```
falls.html

<html>
    <head>
        <title>thazhampoo falls</title>
    </head>
    <body bgcolor="lightblue">
        <h1 align="center">Ranipet</h1>
        <h3 align="center">thazhampoo falls</h3>
        <hr>
        <p>Thalampoo Falls, also known as Kayilai Falls, is a waterfall located near the village of Velam in the Ranipet district of Tamil Nadu. It is a scenic spot for a day trip with friends and family, popular for its natural beauty, and its proximity to towns like Ammdoor and Walajapet makes it an accessible destination.  </p>
    </body>

</html>

```
```
temple.html

<html>
    <head>
        <title>sri kulirchilingeswarar</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center" style="color:blue">Ranipet</h1>
        <h3 align="center" style="color:red">Sri Kulirchilingeswarar</h3>
        <hr>
        <p>The Sri Kulirchilingeswarar Temple is an open-air temple located in a dense forest in the Ranipet District of Tamil Nadu. Its main deity is the Sri Kulirchilingeswarar, an east-facing Shiva Lingam that is about 9 ¾ feet tall and also known as Kulam Kaakum Kula Deiva Lingam. The temple is notable for its unique and numerous lingams, including those representing the Navagrahas (nine planets), zodiac signs, and nakshatras (stars), as well as lingams dedicated to Siddhars and the four directions.</p>
    </body>

</html>
```
```
place.html

<html>
    <head>
        <title>karigiri</title>
    </head>
    <body bgcolor="brown">
        <h1 align="center" style="color:blue">Ranipet</h1>
        <h3 align="center" style="color:red">karigiri</h3>
        <hr>
        <p>Karigiri can refer to either a village in the Vellore District of Tamil Nadu, known for its pottery, or a major hospital complex within that village, formerly the Schieffelin Leprosy Research and Training Centre. The village is historically linked to the creation of unique pottery and the hospital is a significant medical and research center for leprosy and other health issues. </p>
    </body>

</html>
```
```
tech.html

<html>
    <head>
        <title>smarttech shuttle</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center" style="color:blue">Ranipet</h1>
        <h3 align="center" style="color:red">Smarttech shuttle</h3>
        <hr>
        <p>There is no company named "Smarttech Shuttle" in the Ranipet area; however, there are local businesses with similar-sounding names. Smart Waves Technologies is located in Arcot (near Ranipet) and deals with satellite channels. There is also a company called Green IOT Solutions for Intelligent Farming which uses "smart" technology, and several other tech and transport companies are listed in Ranipet. </p>
    </body>

</html>
```
```
templeii.html

<html>
    <head>
        <title>kanchanagiri shivan  malai</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center" style="color:blue">Ranipet</h1>
        <h3 align="center" style="color:red">kanchanagiri shivan  malai</h3>
        <hr>
        <p>Kanchanagiri Shivan Malai is a holy hill near Ranipet in Tamil Nadu, notable for its scenic beauty and temples, including a Shiva temple and a Murugan temple. It is a popular destination known for its "bell rock" formation and is also called the Thiru Kanchanagiri Devasthanam Temple. Legend states the mountain was once a volcano that formed natural Shiva lingams, and the site features a main Shiva Lingam idol and numerous smaller ones. </p>
    </body>

</html>
```





## OUTPUT
image map
![alt text](<Screenshot 2025-11-29 113216.png>)

thazhampoo falls
![alt text](<Screenshot 2025-11-29 113348.png>)

sri kulirchilingeswarar temple
![alt text](<Screenshot 2025-11-29 113438-1.png>)

karigiri place
![alt text](<Screenshot 2025-11-29 113455.png>)

smarttech shuttle
![alt text](<Screenshot 2025-11-29 113510.png>)

kanchanagiri shivan  malai
![alt text](<Screenshot 2025-11-29 113559.png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.

# Ex03 Places Around Me
## Date: 17.02.2026

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
<html>
    <head>
        <title>Ayyappan Temple</title>
    </head>
    <body>
        <h1 align="center">Velachery-chennai</h1>
        <h3 align="center">Sahana S 25015837</h3>
        <h4>Sri Ayyappan Temple Velachery is a popular temple in Velachery dedicated to Lord Ayyappa and known for its calm and spiritual atmosphere.
Many devotees visit the temple for daily prayers and special poojas</h4>
    </body>
</html>

html>
    <head>
        <title>IIT Madras </title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">Velachery-chennai</h1>
        <h3 align="center">Sahana S 25015837</h3>
        <h4>IIT Madras is a top engineering institute in Chennai, known for its high-quality education and research.
It has a large green campus and offers many courses in engineering, science, and technology.</h4>
    </body>
</html>

<html>
    <head>
        <title>My City </title>
    </head>
    <body>
        <h1 align="centre">Velachery-chennai</h1>
        <h3 align="centre">Sahana S 25015837</h3>
        <img src="mapweb.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="phoenix Marketcity mall" title="phoenix Marketcity mall" href="phoenix.html" coords="1364,16,1120,82" shape="rect">
    <area target="" alt="PVR grand mall" title="PVR grand mall" href="PVR.html" coords="62,245,56,297,238,314,268,281,238,251" shape="poly">
    <area target="" alt="IIT Madras " title="IIT Madras " href="IIT.html" coords="1441,50,40" shape="circle">
    <area target="" alt="vanuvampet Murugan temple" title="vanuvampet Murugan temple" href="vanuvampet.html" coords="981,188,788,257" shape="rect">
    <area target="" alt="Ayyappan Temple" title="Ayyappan Temple" href="Ayyappan.html" coords="618,504,87" shape="circle">
</map>

        
    </body>
</html>

<html>
    <head>
        <title>phoenix Marketcity mall </title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">Velachery-chennai</h1>
        <h3 align="center">Sahana S 25015837</h3>
        <h4>Phoenix Marketcity Chennai is one of the largest shopping malls in Chennai, located in Velachery, offering a wide range of shopping, dining, and entertainment options.
It is a popular hangout spot with hundreds of stores, restaurants, and a multiplex cinema, making it a one-stop destination for families and friends.</h4>
    </body>
</html>

<html>
    <head>
        <title>PVR grand mall </title>
    </head>
    <body bgcolor="red">
        <h1 align="center">Velachery-chennai</h1>
        <h3 align="center">Sahana S 25015837</h3>
        <h4>PVR Grand Mall in Velachery, Chennai is a well-known shopping and entertainment destination with a PVR multiplex and various retail stores.
It also has a food court, gaming areas, and dining options, making it a popular place for movies and leisure.</h4>
        
    </body>
</html>

<html>
    <head>
        <title>vanuvampet Murugan temple </title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">Velachery-chennai</h1>
        <h3 align="center">Sahana S 25015837</h3>
        <h4>Vanuvampet Murugan Temple is a well-known Hindu temple in Chennai dedicated to Lord Murugan.
It is a peaceful place of worship where many devotees visit for prayers and festivals.</h4>
    </body>
</html>
```

## OUTPUT
![alt text](image.png)
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (23).png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.

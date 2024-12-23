# Ex.06 Book Front Cover Page Design
## Date:15-12-2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style type="text/css">
            .bookcover {
                width: 400px;
                height: 640px;
                color:whitesmoke (221, 39, 39);
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                background-image: url(bg.jpg);
                background-size: cover;
            }
            .insight {
                color:whitesmoke;
            }
            .hr1 {
                width: 130px;
                color:whitesmoke;
            }
            .h1 {
                font-size: larger;
                font-family: Arial, Helvetica, sans-serif;
                text-align: left;
                position: relative;
                top: 20px;
                color:whitesmoke;
            }
            .para {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                top: 40px; 
                color:whitesmoke; 
            }
            .edition {
                font-size: large;
                font-family: Arial, Helvetica, sans-serif;
                color:whitesmoke;
                top: 180px;
                position: relative;
            }
            .pic {
                position: relative;
                top: 230px;
                left: 220px;
                width: 100px;
                height: 100px;
                background-size: cover;
                color:whitesmoke;
            }
            .hr2 {
                position: relative;
                width: 400px;
                top: 280px;
                color:whitesmoke;
            }
            .name {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                display: inline;
                position: relative;
                color:whitesmoke ;
                top: 280px;
            }
            .pub {
                font-size: large;
                position: relative;
                top: 240px;
                left: 330px;
                color:whitesmoke ;
            }
        </style>
        <title> Book Front Cover Page  </title>
    </head>
    <body>
        <div class="bookcover">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hr1">
                <hr>
            </div>
            <div class="h1">
                <h1> Full Stack Foundations<br> </h1>

            </div>
            <div class="para">
                <p> A Complete Guide For
                    <br> Developers </p>
            </div>
            <div class="pic">
                <img src="me.png" height="150" >
            </div>
            <div class="hr2">
                <hr>
            </div>
            <div class="name">
                <p><b>Eswar</b></p>
            </div>
            <div class="pub">
                <b> SEC </b>
            </div>
            <div class="edition">
                <b> Definite Edition </b>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:

![alt text](<Screenshot (52).png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

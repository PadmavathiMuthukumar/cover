# Ex.06 Book Front Cover Page Design
## Date: 22-10-2024

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
        <title>book cover</title>
        <style>
            .book-cover{
                position: relative;
                margin: auto;
                height: 700px;
                width: 500px;
            }
            .title{
                position: absolute;
                top: 2%;
                left: 5%;
                color: white;
                font-size: 25;
                font-weight: bolder;
                font-family: 'Times New Roman', Times, serif;
            }
            
            .caption{
                position: absolute ;
                font-style: italic;
                font-size: large;
                top: 35%;
                color: floralwhite;
                left: 50%;
            }
            .pic{
                width: 200px;
                height: 200px;
                position: absolute;
                background-color: transparent;
                top: 31%;
                left:5%;
            }
            hr{
                width: 90%;
                border: none;
                background-color: white;
                height: 1px;
                position: absolute;
                left:5%;
                box-shadow: 0 0 10px white, 0 0 20px white; 
                transition: box-shadow 0.3s ease;
            }
            hr:first-of-type{
                top: 25%;
            }
            hr:last-of-type{
                top:60%
            }
            .author{
                height:90px;
                width:80px;
                top: 67%;
                right:5%;
                position: absolute;
                border: 2px;
                border-radius: 5px;
                
            }
            .name{
                font-style: oblique;
                position: absolute;
                top:79%;
                right:5%;
                font-size: smaller;
                color: aliceblue;

            }
            .third{
                top:61%;
                left:5%;
                font-size: large;
                font-weight: bold;
                color: white;
                position: absolute;

            }
            .sec{
                font-size: medium;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                position:absolute;
                top:61%;
                right: 7%;
                color: aliceblue;
            }
            
        </style>
    </head>
    <body>
        <div class="book-cover">
            <center>
                <img src="https://img.freepik.com/free-photo/abstract-luxury-gradient-blue-background-smooth-dark-blue-with-black-vignette-studio-banner_1258-54583.jpg" width="100%" height="100%">

            </center>
            <div class="title">
                <h1>Creative Ideas In Web Application</h1>
            </div>
            <hr>
            <div class="caption">
                <p>The web does not just connect machines, it connects people</p>
            </div>
            <div class="pic">
                <img src="https://www.pngplay.com/wp-content/uploads/13/Web-Designing-Transparent-Images.png" width="100%" height="100%">
            </div>
            <hr>
            <div class="author">
                <img src="c:\Users\padma\Downloads\IMG-20230906-WA0050.jpg" width="100%" height="100%">
            </div>
            <div class="name">
                <p>Padmavathi M</p>
            </div>
            <div class="third">
                <p>Third Edition</p>
            </div>
            <div class="sec">
                <p>AUTHOR</p>
            </div>

        </div>
    </body>
</html>
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/798626bb-cacf-4578-9251-ce04a7503d9a)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

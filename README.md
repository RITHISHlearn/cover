# Ex.06 Book Front Cover Page Design
## Date:

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

<!DOCTYPE html>
<html>

<head>
    <title>Book Cover Design</title>
    <style> 
        .wrapper {
            background-color: white;
            height:100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url(back.jpg) ;
            background-size: cover;
        }
            
        
        .insight{
            color: orange;
        
        }
        
        
        .hrstyle{
            width: 100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: blue;
            top: 270px;
            font-family: Georgia;
            font-size: medium;
            padding-bottom: 20px;
        }
        .booktitle{
            color: red;
            font-family: 'Courier New', Courier, monospace, bold;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width: 400px;
            position: relative;
            top: 280px;
            
        }
        .pub{
            color: greenyellow;
            font-size: medium;
            position: relative;
            top: 235px;
            left: 330px;
        }
        .ed{
            color: greenyellow;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 190px;
        
        }
        .subtitle{
            color:gold(24, 38, 78);
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px;
        }
        .subtitle2{
            color: white;
            font-family: Arial, Helvetica, sans-serif;
            font-size: small;
            position: relative;
            top: 250px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>
<body style="background-color: brown;">
    <div class="wrapper">
        <div class="bookpage">
            <div class="insight">
                <b>SOFTWARE DEVELOPMENT</b>
            </div>
            <div class="hrstyle">
                <hr style="color: brown">
            </div>
            <div class="booktitle">
                <h1><b>SOFTWARE DEVELOPMENT</b></h1></div>
            <div class="subtitle">
                 <b>Streamlining Software Development</b> 
            <div class="subtitle2">
                <b>>> Managing Code Changes Effectively</b><br>
                <b>>> Bridging Development and Operations</b><br>
                <b>>> Ensuring Software Quality</b><br>
            </div>     
            </div>
            <div class="mypic">
                <img src="C:\Users\admin\Downloads\college photo.jpg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color: brown">
            </div>
            <div class="author">
               <p><b>RITHISH P(212223230173)</b></p>
            </div>
            <div class="pub">
                SEC 27'
            </div>
        </div>
    </div>
</body>
</html>

## OUTPUT:

![Screenshot 2024-04-26 230302](https://github.com/RITHISHlearn/cover/assets/145446645/092103cd-14b4-4307-8b96-617376497208)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

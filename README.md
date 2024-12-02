# Ex.06 Book Front Cover Page Design
## Date:2.12.2024

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
    <title>Book cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url("web cover.jpg");
            background-size: cover;
        }
            
        
        .insight{
            color:blue;
        
        }
        
        
        .hrstyle{
            width:150px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:red;
            top:190px;

            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:yellow;
            font-family: Roquen;
            font-size:xx-larger;
            text-align: center;
            position: relative;
            top: 10px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:green;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:brown;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:sky blue;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 150px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                Expert Insight
                
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1 style="font-family: cursive; color:orange;">Time Mission</h1></div>
            <div class="subtitle" style="text-align: center;color: orange;">
                 upon that machine
            </div>
            <div class="subtitle" style="color:green;text-align: center;">
                 
            </div>

            <div class="mypic">
                <img src="harshu.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr>
            </div>
            <div class="author">
               <p><b>Harshitha</b></p>
            </div>
            <div class="pub">
              Ammu
            </div>
            <div class="ed">
                <b>FIRST EDITION</b>
            </div>
        </div>
        </body>
        

</html>

## OUTPUT:
![alt text](<Screenshot (49).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

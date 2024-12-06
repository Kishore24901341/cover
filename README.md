# Ex.06 Book Front Cover Page Design
## Date:1/12/2024

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
cover.html

<html>
<head>
<style>
    .bookpage{
        width: 400px;
        height: 600px;
        color:rgb(255, 30, 0);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(OIP.jpeg);
        background-size: cover;
    }
        
    
    .insight{
        color: rgb(245, 119, 56);
    
    }
    
    
    .hrstyle{
        width:170px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: rgb(255, 0, 255);
        top:270px;
        
        font-family:cursive;
        font-size: medium;
    }
    .booktitle{
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        font-style:oblique;
        top: 30px;
        color: cornsilk;
    
    }
    .id {
        width:400px;
        position: relative;
        top:280px;
        color: rgb(244, 37, 199);
        
    }
    .pub{
        color: rgb(255, 47, 54);
        font-size: medium;
        position: relative;
        top:235px;
        left:350px;
    }
    .ed{
        color: rgb(229, 252, 98);
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:185px;
    
    }
    .subtitle{
        color:rgb(1, 10, 7);
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:40px;
        font-style:normal;
    }
    .mypic{
        position: relative;
        top: 230px;
        left: 260px;
        width: 100px;
        height: 90px;
        background-size: cover;
    }
    </style>
    <title>My Cover</title>
    </head>
    <body>
    <div class="bookpage">
        <div class="insight">
            SAVIEANS WORK
        </div>
        <div class="hrstyle">
            <hr style="color: rgb(236, 21, 175);">
        </div>
        <div class="booktitle">
            <h1>UI/UX Designing Course</h1></div>
        <div class="subtitle">
            Learn UI/UX Designing from the expert
        </div>
        <div class="mypic">
            <img src="my pic.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: goldenrod;">
        </div>
        <div class="author" >
           <p><b>Kishore V(24901341)</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>3rd Edition</b>
        </div>
    </div>
    </body>
</html>
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/d9383a72-cc8d-4f3b-9ce5-bccf6ce36aad)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

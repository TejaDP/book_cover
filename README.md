# Ex.06 Book Front Cover Page Design
# Date:24.09.2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<html>
    <head>
        <title>
            BOOK COVER
        </title>
        <h1 > BOOK COVER DESIGN </h1>
        <style>
            h1{ text-align: center; -webkit-text-fill-color: purple;}
     .bookcover{ width: 600px;height:630px;border: 3px;background-image:url(bg.jpg);background-position:center;
                       background-size: cover; position: relative;left:27%; ;border: 6px  }


    .title{font-size: xx-large;font: bold;text-align:center ;height:30px; position: absolute;top: 60px;right:130px;
    
    }
   .topic{
        font-size: xx-large;  font-family:'poppins',sans-serif; position: absolute;font-weight:677px;
        height: 60%; width: 100%;top:28%; left: 20%; font-size: xx-large;-webkit-text-fill-color:#ffa500
    }

   
    .authorname{ font-size: large; font-style: oblique;text-align:center;height:50px ;bottom:20px;position: absolute;right: 70px;
       -webkit-text-fill-color:black
    }
           
     .authorimage{
        background-image: url(download.jpg);position: absolute;height:30%;width:30%; right:30px;bottom: 80px; border:3PX solid #ffe066;
    }
      </style>
    </head>
    <body>
         <div class="bookcover">
        <div class="title" style="color:goldenrod">
            CONCEPTS OF PHYSICS 
        </div>
        <div class="topic">
              <pre>FROM MOTION TO MATTER ,</pre>
              <pre>PHYSICS EXPLAINS IT ALL</pre> 
        </div>
         <div class="authorname">
           <h3> HC VERMA </h3>
        </div>
        <div class="authorimage">
    </div>
    </div>
    </body>
</html>
```
# OUTPUT:
![alt text](<Screenshot (49).png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

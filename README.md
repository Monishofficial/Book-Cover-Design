# Ex-5: Book Cover Design
## DATE: 08-11-2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
index.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(13, 244, 151);
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(image1.jpg);
            background-size: cover;
        }
        .insight{
            color: rgba(255, 213, 0, 0.952);
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display: inline;
            position: relative;
            color: rgb(200, 255, 0);
            top:330px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: 19px;
            text-align: center;
            position: relative;
            top: 30px;
        }
        .id {
            width:400px;
            position: relative;
            top:310px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top:300px;
            left:330px;
        }
        .ed{
            color: rgb(13, 244, 151);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:219px;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">EXPERT INSIGHT</div>
            <div class="hrstyle"><hr style="color: rgb(0, 255, 68);"></div>
            <div class="booktitle"><h1>AI: Transforming Data  Into  Decisions.</h1></div>
            <div class="subtitle">AI: Your Partner in Progress</div>
            <div class="id"><hr style="color: rgb(9, 235, 160);"></div>
            <div class="author"><p><b>BY MONISH N</b></p></div>
            <div class="pub">OPEN >>></div>
            <div class="ed"><b>Special Edition</b></div>
        </div>
    </bodY>
</html>
```
## OUTPUT:
![alt text](<Screenshot (198).png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

# Ex.05 Book Front Cover Page Design
## Date:18.12.25

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
<html lang="en">
<head>
    meta charset="UTF-8"
    title>Book Cover</title>
    style
        body {
            background-color: #111;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, Helvetica, sans-serif;
            }

        .book-cover {
            width: 350px;
            height: 500px;
            background: linear-gradient(180deg, #0b2a3d, #03131e);
            color: white;
            padding: 20px;
            box-shadow: 0 0 20px rgba(0,0,0,0.8);
            position: relative;
        }

        .badge {
            background-color: red;
            color: white;
            padding: 5px 10px;
            font-size: 12px;
            position: absolute;
            top: 15px;
            left: 15px;
        }

        .globe {
            width: 120px;
            height: 120px;
            background: radial-gradient(circle, #4fc3f7, #01579b);
            border-radius: 50%;
            margin: 40px auto 20px;
            box-shadow: 0 0 20px #4fc3f7;
        }

        .devices {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-bottom: 30px;
        }

        .device {
            width: 30px;
            height: 20px;
            background-color: #1e88e5;
            border-radius: 3px;
        }

        h1 {
            text-align: center;
            font-size: 22px;
            margin: 10px 0;
        }

        h2 {
            text-align: center;
            font-size: 16px;
            font-weight: normal;
            color: #90caf9;
        }

        .authors {
            position: absolute;
            bottom: 60px;
            width: 100%;
            text-align: center;
            font-size: 14px;
        }

        .publisher {
            position: absolute;
            bottom: 20px;
            width: 100%;
            text-align: center;
            font-size: 13px;
            color: #bbb;
        }
    </style>
</head>
<body>
<div class="book-cover">
    <div class="badge">NEW</div>

    <div class="globe"></div>

    <div class="devices">
        <div class="device"></div>
        <div class="device"></div>
        <div class="device"></div>
        <div class="device"></div>
    </div>

    <h1>Fundamentals of<br>Web Development</h1>
    <h2>Randy Connolly | Ricardo Hoar</h2>

    <div class="authors">
        Web Design & Development
    </div>

    <div class="publisher">
        Pearson
    </div>
</div>

</body>
</html>


## OUTPUT:
![alt text](<Screenshot 2025-12-20 194017.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

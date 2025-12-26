# Ex.05 Book Front Cover Page Design
 Date:17.12.2025

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
<!DOCTYPE html>
<html>
<head>
    <title>Book Cover</title>
    <style>
        body {
            background-color: #f2f2f2;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }

        .book-cover {
            width: 300px;
            height: 450px;
            background: linear-gradient(135deg, #4a90e2, #1c3d73);
            color: white;
            padding: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
            text-align: center;
            border-radius: 8px;
        }

        .title {
            font-size: 28px;
            font-weight: bold;
            margin-top: 80px;
        }

        .subtitle {
            font-size: 16px;
            margin-top: 10px;
            opacity: 0.9;
        }

        .author {
            position: absolute;
            bottom: 40px;
            left: 0;
            right: 0;
            font-size: 18px;
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="title">FUNDAMENTAL OF WEB APPLICATION</div>
        <div class="author">By JAYENTHAN.R</div>
    </div>

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-12-26 092613.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

# Ex.06 Book Front Cover Page Design
## Date: 10.11.2025

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
### Book.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <style>
    /* ✅ Center the cover in the middle of the screen */
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #c88cbc; /* light background */
      font-family: "Times New Roman", serif;
    }

    /* ✅ Book cover design */
    .cover {
      width: 600px;
      height: 850px;
      border: 6px solid red;
      padding: 20px;
      position: relative;
      background-image: url('back.jpg'); /* 🔹 change background */
      background-size: cover;
      background-position: center;
      color: white;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
    }

    .header {
      font-size: 18px;
    }

    .title {
      margin-top: 60px;
      text-align: center;
      font-size: 26px;
      font-weight: bold;
      line-height: 1.3;
    }

    .subtitle {
      margin-top: 15px;
      text-align: center;
      font-size: 18px;
    }

    .special {
      position: absolute;
      bottom: 100px;
      left: 20px;
      font-size: 18px;
      font-weight: bold;
    }

    .footer {
      position: absolute;
      bottom: 40px;
      left: 20px;
      width: 100%;
      font-size: 18px;
    }

    .footer span {
      float: right;
      margin-right: 60px;
    }

    .author-photo {
      position: absolute;
      bottom: 50px;
      right: 50px;
      width: 120px;
      height: 120px;
      border: 2px solid white;
    }

    .author-photo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="header">
      <p><b>SEC Insights</b></p>
      <hr>
    </div>

    <div class="title">
      <h1>FUNDAMENTALS OF<br>WEB APPLICATION<br>DEVELOPMENT</h1>
    </div>

    <div class="subtitle">
      <p>Deep Dive in HTML, CSS & JS Basics<br>Top seller of 2025</p>
    </div>

    <div class="special">
      <p>BEST EDITION OF 2025</p>
    </div>

    <div class="footer">
      <p><b> Ashwin Kumar K S</b></p>
    </div>

    <div class="author-photo">
      <img src="photo.png" alt="Author Photo"> <!-- 🔹 Change image name -->
    </div>
  </div>
</body>
</html>

```


## OUTPUT:
<img width="503" height="710" alt="image" src="https://github.com/user-attachments/assets/ff92ba0e-ab31-40f8-9c32-2d85ceaf2078" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

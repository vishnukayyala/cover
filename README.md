# Ex.06 Book Front Cover Page Design
## Date: 17.10.24

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
NAME : VISHNU KM
REG NO : 212223240185
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: black;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .book-cover {
      width: 500px;
      height: 700px;
      background-color: #00ffbf;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      position: relative;
      overflow: hidden;
    }

    .insight {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 15px;
      font-weight: bold;
      color: black;
      font-family: 'Arial Black', sans-serif;
    }

    .line1,
    .line2,
    .line3 {
      position: absolute;
      width: 80%;
      left: 10%;
    }

    .line1 {
      top: 40px;
    }

    .title1 {
      position: absolute;
      top: 180px;
      left: 50%;
      transform: translateX(-50%);
      font-size: 32px;
      font-weight: bold;
      color: black;
      font-family: 'Arial Black', sans-serif;
    }

    .subtitle1 {
      position: absolute;
      top: 470px;
      left: 20px;
      font-size: 18px;
      font-weight: bold;
      color: black;
      font-family: 'Arial Black', sans-serif;
    }

    .subtitle2,
    .subtitle3 {
      position: absolute;
      left: 20px;
      font-size: 18px;
      font-weight: bold;
      color: black;
      font-family: 'Arial Black', sans-serif;
    }

    .subtitle2 {
      top: 520px;
    }

    .subtitle3 {
      top: 560px;
    }

    .line2 {
      top: 480px;
    }

    .line3 {
      bottom: 38px;
    }

    .author {
      position: absolute;
      bottom: 5px;
      right: 20px;
      font-size: 18px;
      color: black;
      font-family: 'Arial Black', sans-serif;
    }

    .end {
      position: absolute;
      bottom: 5px;
      left: 50px;
      font-size: 18px;
      color: blackwhite;
      font-family: 'Arial Black', sans-serif;
    }

    .mypic {
      position: relative;
      top: 550px;
      left: 370px;
      width: 120px;
      height: 120px;
      overflow: hidden;
      border-radius: 50%;
    }

    .mypic img {
      width: 100%;
      height: auto;
      object-fit: cover;
    }

    .image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top: 0;
      left: 0;
    }
  </style>
</head>

<body>
  <div class="book-cover">
    <img src="c:\Users\jafil\Downloads\green.png" alt="Book Cover Image" class="image">
    <div class="insight">Biodiversity and Conservation</div>
    <div class="line1"><hr style="color: black (133, 192, 237, 0.877)"></div>
    <div class="title1">Threats to Biodiversity</div>
    <div class="subtitle1">Endangered Species</div>
    <div class="line2"></div> 
    <div class="subtitle2">The Role of Legislation</div>
    <div class="subtitle3">Urban Biodiversity</div>
    <div class="line3"><hr style="color:black (143, 213, 236)"></div>
    <div class="mypic"><img src="c:\Users\jafil\Pictures\vich.png" alt="Author's Picture"></div>
    <div class="end">2024</div>
    <div class="author">VISHNU KM</div>
  </div>
</body>

</html>
```


## OUTPUT:

![WhatsApp Image 2024-10-17 at 23 39 00_cac99bc8](https://github.com/user-attachments/assets/2792e6e7-906f-43fb-a3cc-43e0ebb36845)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

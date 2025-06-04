# Ex.06 Book Front Cover Page Design
## Date:04.06.2025

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
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Book Cover</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Roboto&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background-image: url('Batman.png');
      background-size: cover;
      background-position: center;
      font-family: 'Roboto', sans-serif;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #675b5b;
    }

    .book-container {
      perspective: 1200px;
    }

    .book-cover {
      width: 380px;
      height: 560px;
      background: url('deer.png') center/cover no-repeat; /* Set your book cover image */
      color: white;
      border-radius: 15px;
      box-shadow: 0 30px 60px rgba(0, 0, 0, 0.4);
      padding: 50px 30px;
      transform: rotateY(-10deg);
      transform-style: preserve-3d;
      transition: all 0.6s ease;
      position: relative;
      overflow: hidden;
    }

    .book-cover:hover {
      transform: rotateY(0deg) scale(1.05);
    }

    .book-title {
      font-family: 'Playfair Display', serif;
      font-size: 40px;
      font-weight: 700;
      text-align: center;
      margin-top: 30px;
      line-height: 1.2;
      color: #ffffff;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
    }

    .book-subtitle {
      font-size: 20px;
      text-align: center;
      margin-top: 15px;
      color: #fb0d0d;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
    }

    .author-section {
      text-align: center;
      margin-top: 50px;
    }

    .author-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #fff;
      margin-bottom: 15px;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.3);
      position: relative;
      z-index: 10;
    }

    .book-author {
      font-size: 22px;
      font-style: italic;
      color: #ffffff;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.4);
    }

    .book-footer {
      position: absolute;
      bottom: 30px;
      width: 100%;
      text-align: center;
      font-size: 16px;
      letter-spacing: 2px;
      color: #ffffff;
      text-transform: uppercase;
      font-weight: bold;
    }

  </style>
</head>
<body>
  <div class="book-container">
    <div class="book-cover">
      <div class="book-title">Whispers of the Forgotten</div>
      <div class="book-subtitle">Secrets Hidden in the Wind</div>

      <div class="author-section">
        <img src="Jack.png" class="author-img" />
        <div class="book-author">By ZORO_DONO</div>
      </div>

      <div class="book-footer">Book One • Mystery Series</div>
    </div>
  </div>
</body>
</html>
```

## OUTPUT:

![440506542-8a1383d2-65e5-4c11-809b-e3089248ef04](https://github.com/user-attachments/assets/e1f90b0e-61c0-41e9-9957-8bfa98a1c30c)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

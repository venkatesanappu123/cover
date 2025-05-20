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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>The Monarch of Expansion</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .book-cover {
      width: 350px;
      height: 500px;
      background: linear-gradient(to bottom, #1c2c55 60%, #b41f2f 40%);
      position: relative;
      color: white;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      overflow: hidden;
      border-radius: 8px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      padding: 20px;
      box-sizing: border-box;
    }

    .title {
      text-align: center;
      font-size: 24px;
      font-weight: bold;
      margin-top: 10px;
    }

    .title .highlight {
      color: #ff2e2e;
    }

    .subtitle {
      text-align: center;
      font-size: 10px;
      margin-top: 10px;
      padding: 0 10px;
      text-transform: uppercase;
    }

    .bottom-section {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .author-image {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
      border: 3px solid white;
    }

    .author {
      font-size: 14px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">
        THE MONARCH <br><span class="highlight">OF EXPANSION</span>
      </div>
      <div class="subtitle"><br><br>
        UNLEASH YOUR INNER MONARCH: DOMINATE YOUR INDUSTRY WITH UNPRECEDENTED GROWTH STRATEGIES
      </div>
    </div>

    <div class="bottom-section">
      <img src="001-removebg-preview.png" src="fcd96371-f0ee-4c99-b6f4-c5764077e636.png" alt="Author Image" width="80px" height="100px"><br>
      <div class="author">VENKATESAN R</div>
    </div>
  </div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-05-20 201917.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

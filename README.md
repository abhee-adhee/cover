# Ex.05 Book Front Cover Page Design
## REG NO: 212224040008

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
```html
# Ex.05 Book Front Cover Page Design
## Date: 18-10-2024

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Book Cover</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="book-cover">
    <div class="top-text">EXPERT INSIGHT</div>
    <h1>Responsive Web<br>Design with<br>HTML5 and CSS</h1>
    <p class="subtitle">Develop future-proof responsive websites<br>using the latest HTML5 and CSS techniques</p>
    <div class="edition">Third Edition</div>
    <div class="author">Abinav Aaditya</div>
    <div class="publisher">Packt</div>
    <div class="wave"></div>
  </div>
</body>
</html>
```
##css
```
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

body {
  margin: 0;
  background: #1e1e1e;
  font-family: 'Roboto', sans-serif;
}

.book-cover {
  width: 720px;
  height: 960px;
  background: linear-gradient(145deg, #292929 60%, #1a1a1a 100%);
  color: #ffffff;
  padding: 50px 40px;
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  border-radius: 12px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
}

.top-text {
  color: #cccccc;
  font-size: 14px;
  text-transform: uppercase;
  letter-spacing: 1px;
  margin-bottom: 30px;
}

h1 {
  font-size: 44px;
  font-weight: 700;
  line-height: 1.3;
  margin: 0 0 30px;
  color: #ffffff;
}

.subtitle {
  font-size: 16px;
  color: #bbbbbb;
  line-height: 1.6;
}

.edition {
  color: #ffa500;
  font-weight: bold;
  font-size: 20px;
  margin-top: 50px;
}

.author {
  font-size: 24px;
  font-weight: bold;
  margin-top: 10px;
  color: #00ffcc;
}

.publisher {
  position: absolute;
  bottom: 20px;
  left: 40px;
  font-size: 24px;
  font-weight: bold;
  color: #ffffff;
  border-top: 2px solid white;
  padding-top: 10px;
}

.wave {
  position: absolute;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 200px;
  background: radial-gradient(circle at center, #00ffe7 0%, transparent 70%);
  opacity: 0.4;
  transform: rotate(-2deg);
  pointer-events: none;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/2b352f70-433c-41f1-8933-72fbe14e2505)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.



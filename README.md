# Ex.06 Book Front Cover Page Design
## Date: 09-05-2025
# NAME : MOHAMED HAFEEZ S
# REG NO : 212224040193
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
HTML 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Book Cover</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="book-cover">
    <div class="overlay"></div>
    <div class="content">
      <h1 class="title">The Silent Dawn</h1>
      <p class="subtitle">A Journey Through Light and Shadow</p>
      <p class="author">by Jane Doe</p>
    </div>
  </div>
</body>
</html>

  CSS

body {
  margin: 0;
  font-family: 'Georgia', serif;
}

.book-cover {
  width: 400px;
  height: 600px;
  margin: 50px auto;
  position: relative;
  background-image: url('https://images.unsplash.com/photo-1509021436665-8f07dbf5bf1d'); /* Replace with your image */
  background-size: cover;
  background-position: center;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
  border-radius: 8px;
  overflow: hidden;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.4);
}

.content {
  position: relative;
  color: #fff;
  padding: 40px 30px;
  text-align: center;
  z-index: 1;
}

.title {
  font-size: 32px;
  margin-bottom: 20px;
  font-weight: bold;
}

.subtitle {
  font-size: 18px;
  margin-bottom: 40px;
  font-style: italic;
}

.author {
  font-size: 16px;
  position: absolute;
  bottom: 30px;
  width: 100%;
  left: 0;
}


## OUTPUT:
![Screenshot 2025-05-09 133751](https://github.com/user-attachments/assets/f54760c1-69b3-40b2-a0ec-83d4505abee0)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

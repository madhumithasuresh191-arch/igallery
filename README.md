# Ex.08 Design of Interactive Image Gallery
## Date:20-12-2025
## Ref no:25014660

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
~~~
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Image Gallery</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #111;
            font-family: Arial, sans-serif;
        }

        .gallery {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
        }

        .gallery img {
            width: 400px;
            height: 300px;
            object-fit: cover;
            border: 2px solid #ff3d0036;
            border-radius: 10px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
        }

        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 0 15px #ff3d00;
        }
    </style>
</head>

<body>

    <div class="gallery">
        <img src="cow.jpeg" alt="Image 1">
        <img src="cat.jpeg"alt="Image 2">
        <img src="dog.jpeg"alt="Image 3">
        <img src="goat.jpeg" alt="Image 4">
        <img src="pig.jpeg" alt="Image 5">
        <img src="rabbit.jpeg"alt="Image 6">
    </div>

</body>
</html>

style.css

/* Reset default browser styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Page background */
body {
    background-color: #0f172a;   /* dark background */
    font-family: Arial, sans-serif;
}

/* Gallery container */
.gallery {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 20px;
    padding: 30px;
}

/* Images */
.gallery img {
    width: 400px;
    height: 300px;
    object-fit: cover;
    border: 2px solid #ff3d00;
    border-radius: 10px;
    transition: transform 0
}
~~~

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-12-26 194400" src="https://github.com/user-attachments/assets/ba22f7ff-3348-48a8-8c13-c82edc9dbb2c" />

<img width="1920" height="1079" alt="Screenshot 2025-12-26 194341" src="https://github.com/user-attachments/assets/4032cc00-048b-4639-abf9-e811d7103a74" />

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.

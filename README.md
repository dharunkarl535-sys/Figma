# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
<!DOCTYPE html>
<html>
<head>
    <title>Book Cover</title>
<style>
body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    font-family: 'Georgia', serif;
}

.cover {
    position: relative;
    width: 100%;
    height: 100vh;
    background-color: #000;
    overflow: hidden;
}

.bg-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    opacity: 0.7;
    position: absolute;
    top: 0;
    left: 0;
    z-index: 0;
}

.content {
    position: relative;
    z-index: 1;
    color: white;
    text-align: center;
    padding-top: 15%;
}

.title {
    font-size: 3.5em;
    margin-bottom: 10px;
    color: #fff;
    text-shadow: 2px 2px 8px #000;
}

.subtitle {
    font-size: 1.8em;
    margin-bottom: 30px;
    color: #ccc;
}

.author {
    font-size: 1.2em;
    font-style: italic;
    color: #aaa;
}

</style>
</head>
<body>
    <div class="cover">
        <img src="{% static 'cover/images/bg.jpg' %}" class="bg-img" alt="Background">
        <div class="content">
            <h1 class="title">The Art of Django</h1>
            <h3 class="subtitle">Mastering Web Development</h3>
            <div class="author">by Jane Doe</div>
        </div>
    </div>
</body>
</html>

## OUTPUT:
<img width="1758" height="921" alt="Screenshot 2025-10-08 210711" src="https://github.com/user-attachments/assets/6ef463dd-793f-4fee-9076-31e8aa36c6c5" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

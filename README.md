# Ex.07 Restaurant Website
## Date:19/12/25

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
~~~
admin.html

<!DOCTYPE html>
<html>
<head>
    <title>Crimson Fork - Administration</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header>
    <h1>Crimson Fork</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Our Management Team</h2>

    <div class="team-grid">
        <div class="card"><img src="chef.png"><p> Jack  Head Chef</p></div>
        <div class="card"><img src="manager.png"><p>Rose Restaurant Manager</p></div>
    </div>
</section>

</body>
</html>

contact.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>A square - Contact Us</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header>
    <h1>A square– Non-Veg Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <div class="contact-container">
        <h2>Contact Us</h2>
        <p><b>Address:</b> 96 new street,anna nagar, chennai</p>
        <p><b>Phone:</b> +91 9080954345</p>
        <p><b>Email:</b> A square@gmail.com</p>
        <p><b>Timing:</b> 11:00 AM – 11:30 PM</p>
    </div>
</section>

</body>
</html>

index.css

body {
    font-family: 'Segoe UI', sans-serif;
    margin: 0;

    /* Background image */
    background-image: url("bground.png"); /* put your image name here */
    background-size: cover;        /* makes image cover full screen */
    background-position: center;   /* centers the image */
    background-repeat: no-repeat;  /* prevents repeating */
    background-attachment: fixed;  /* nice scrolling effect */

    color: #3b0a0a;
}

/* Header */
header {
    background: linear-gradient(90deg, #5a0f0f, #8b0000, #c21807);
    color: white;
    padding: 24px;
    text-align: center;
}

/* Navigation */
nav {
    background-color: #2b0606;
    text-align: center;
}

nav a {
    color: #ffd700;
    text-decoration: none;
    margin: 0 16px;
    padding: 10px;
    display: inline-block;
    font-weight: bold;
}

nav a:hover {
    background-color: #ffd700;
    color: #2b0606;
    border-radius: 6px;
}

/* Section */
section {
    padding: 40px;
    text-align: center;
}

/* Banner */
.banner {
    width: 80%;
    max-width: 420px;
    border-radius: 12px;
}

/* Headings */
h2 {
    color: #2b0606;
    letter-spacing: 1px;
}

/* Grid */
.menu-grid, .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
    max-width: 1000px;
    margin: auto;
}

/* Cards */
.card {
    background-color: #fff;
    padding: 18px;
    border-radius: 14px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.15);
    border: 3px solid #8b0000;
}

.card img {
    width: 95px;
    height: 110px;
    border-radius: 12px;
}

/* Contact */
.contact-container {
    background-color: #fff;
    padding: 25px;
    border-radius: 14px;
    max-width: 750px;
    margin: auto;
    box-shadow: 0 6px 15px rgba(0,0,0,0.15);
}

menu.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>A square - Menu</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header>
    <h1>A square – Non-Veg Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Our Non-Veg Special Menu</h2>

    <div class="menu-grid">
        <div class="card"><img src="fried chicken.png"><p>fried Chicken – ₹120</p></div>
        <div class="card"><img src="mutton gravy.png"><p>Mutton gravy – ₹380</p></div>
        <div class="card"><img src="fish fry.png"><p>Fish Fry – ₹50</p></div>
        <div class="card"><img src="chicken briyani.png"><p>Chicken Biryani – ₹550</p></div>
        <div class="card"><img src="tandoori chicken.png"><p>Tandoori Chicken – ₹40</p></div>
        <div class="card"><img src="prawn gravy.png"><p>Prawn Masala – ₹660</p></div>
    </div>
</section>

</body>
</html>

~~~



## OUTPUT:
![alt text](<Screenshot 2025-12-19 114635.png>)
![alt text](<Screenshot 2025-12-19 114647.png>)
![alt text](<Screenshot 2025-12-19 114658.png>)
<img width="1902" height="919" alt="Screenshot 2025-12-19 115940" src="https://github.com/user-attachments/assets/2cb743be-0a3a-4cf9-99ba-11bde0f04930" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

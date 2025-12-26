# Ex.06 Restaurant Website
## Date:26.12.25

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
```
restaurant.html:
<html>
    <head>
        <title>
            Siddhu's Veg
        </title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <nav class="navbar">
        <a href="restaurant.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact Us</a>
  </nav>
</html>

menu.html:
<html>
    <head>
        <title>
            Sid's Menu
        </title>
        <link href="stylesM.css" rel="stylesheet">
    </head>
    <nav class="navbar">
        <a href="restaurant.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact Us</a>
  </nav>
  <body>
    <h3>
        :>Sambar
        Our Sambar is a traditional South Indian lentil stew made with slow-cooked toor dal, fresh seasonal vegetables, and a perfect blend of aromatic spices. Simmered to perfection and finished with a flavorful tempering, it delivers a comforting balance of spice, tang, and warmth.
        Served hot and fresh, our sambar pairs beautifully with idli, dosa, vada, rice, and other South Indian favorites - a true taste of home in every spoon.
    </h3>
  </body>
</html>

about.html:
<html>
    <head>
        <title>
            About Us
        </title>
        <link href="stylesA.css" rel="stylesheet">
    </head>
    <nav class="navbar">
        <a href="restaurant.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact Us</a>
  </nav>
  <body>
    <h3>
        *Welcome to our vegetarian restaurant, where fresh ingredients meet traditional flavors.<br> *We believe that great food starts with quality, so every dish we serve is prepared using handpicked vegetables, authentic spices, and hygienic cooking practices.
        <br>*Our goal is to offer healthy, tasty, and affordable vegetarian meals that feel just like home.<br>From comforting classics to flavorful specialties, we focus on food that nourishes the body and delights the soul.
        <br>*At our restaurant, customer satisfaction comes first.<br>*We are proud to serve food made with care, love, and respect for nature. Whether you’re dining with family or grabbing a quick meal, we promise a warm atmosphere and delicious vegetarian food every time.
    </h3>
  </body>
</html>
contact.html:
<html>
    <head>
        <title>
            Contact US
        </title>
        <link href="stylesC.css" rel="stylesheet">
    </head>
    <nav class="navbar">
        <a href="restaurant.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact Us</a>
  </nav>
  <body>
    <h3>
        :) We'd love to hear from you!<br>
        Feel free to reach out for orders, feedback, or any inquiries.
        <br>
        <br>
        &Address:<br>
        Near Main Road, City Center,<br>
        [Nerkundram], [Chennai]<br>
        <br>
        #Phone:<br>
        +91 8807175509<br>
        <br>
        @Email:<br>
        siddhuvegrestaurant@email.com<br>
        <br>

        Opening Hours:<br>
        Monday - Sunday<br>
        8:00 AM - 10:00 PM<br>
    </h3>
  </body>
</html>
styles.css:
body {
  margin: 0;
  height: 100vh;
  background: url("home.png") center / cover no-repeat;
  font-family: Arial, sans-serif;
}

.navbar {
  position: fixed;
  top: 20px;
  right: 20px;
  background: rgba(237, 160, 60, 0.818);
  padding: 10px 20px;
  border-radius: 25px;
  backdrop-filter: blur(6px);
}

.navbar a {
  color: white;
  text-decoration: none;
  margin: 0 10px;
  font-size: 16px;
}

.navbar a:hover {
  text-decoration: underline;
}
stylesC.css:
body {
  margin: 0;
  height: 100vh;
  background: url("contact.png") center / cover no-repeat;
  font-family: Arial, sans-serif;
}

.navbar {
  position: fixed;
  top: 20px;
  right: 20px;
  background: rgba(237, 160, 60, 0.818);
  padding: 10px 20px;
  border-radius: 25px;
  backdrop-filter: blur(6px);
}

.navbar a {
  color: white;
  text-decoration: none;
  margin: 0 10px;
  font-size: 16px;
}

.navbar a:hover {
  text-decoration: underline;
}

body h3{
    margin-left: 850;
    color:goldenrod;
    padding-top: 270;
    margin-right: 180;
    text-align: left;
}
stylesA.css:
body {
  margin: 0;
  height: 100vh;
  background: url("About.png") center / cover no-repeat;
  font-family: Arial, sans-serif;
}

.navbar {
  position: fixed;
  top: 20px;
  right: 20px;
  background: rgba(237, 160, 60, 0.818);
  padding: 10px 20px;
  border-radius: 25px;
  backdrop-filter: blur(6px);
}

.navbar a {
  color: white;
  text-decoration: none;
  margin: 0 10px;
  font-size: 16px;
}

.navbar a:hover {
  text-decoration: underline;
}
body h3{
    margin-left: 150;
    color:rgba(237, 160, 60, 0.818);
    margin-right: 700;
    padding-top: 275;
}
stylesM.html:
body {
  margin: 0;
  height: 100vh;
  background: url("menu.png") center / cover no-repeat;
  font-family: Arial, sans-serif;
}

.navbar {
  position: fixed;
  top: 20px;
  right: 20px;
  background: rgba(237, 160, 60, 0.818);
  padding: 10px 20px;
  border-radius: 25px;
  backdrop-filter: blur(6px);
}

.navbar a {
  color: white;
  text-decoration: none;
  margin: 0 10px;
  font-size: 16px;
}

.navbar a:hover {
  text-decoration: underline;
}
body h3{
    margin-left: 800;
    color:rgba(237, 160, 60, 0.818);
    margin-top: 150;
    margin-right: 180;

}

```

## OUTPUT:

![alt text](<Screenshot 2025-12-26 104627-1.png>)
![alt text](<Screenshot 2025-12-26 104954.png>)
![alt text](<Screenshot 2025-12-26 105010.png>)
![alt text](<Screenshot 2025-12-26 105047.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

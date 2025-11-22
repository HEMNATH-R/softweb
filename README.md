# Ex.07 Restuarant Website
## Date:

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
# HOME 
```
<html>
<head>=
    <title>MSD Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
        }
        header {
            background-color: wheat;
            text-align: center;
            padding: 20px;
        }
        header img {
            width: 50px;
        }
        nav {
            background-color: grey;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        .banner {
    text-align: right;
    background-image: url("newbannar.jpg");
    background-size: cover;
    background-position: center;
    color: white;
    padding: 50px;
}

        .banner h2 {
            margin: 0;
        }
        .banner p {
            margin-top: 10px;
        }
        .sections {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            gap: 10px;
        }
        .section {
            background-color: wheat;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            width: 30%;
        }
        .section img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            background-color: white;
            padding: 10px;
            margin-top: 20px;
        }
        footer a {
            text-decoration: none;
            color: blanchedalmond;
        }
    </style>
</head>
<body>

<header>
    <img src="my logo.png" alt="HOTSPOT Logo"> 
    <h1>MSD Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="adminstration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>30% Off This Weekend</h2>
    <p>Don't miss out on our special offer! Visit us this weekend and enjoy delicious meals at discounted prices.</p>
</div>

<div class="sections">
    <div class="section">
        <img src="idly.jpg" alt="Menu"> 
        <h3>Our New Menu</h3>
        <p>Explore a variety of mouthwatering dishes crafted to satisfy every taste. From savory appetizers to hearty main courses, there's something for everyone.</p>
        <a href="menu.html">See our new menu</a>
    </div>
    <div class="section">
        <img src="pongal.jpg" alt="Book a Table"> 
        <h3>Reserve Your Spot</h3>
        <p>Enjoy an unforgettable dining experience at DK Restaurant. Book your table today and treat yourself to a fantastic meal in a cozy ambiance.</p>
        <a href="booktable.html">Book your table now</a>
    </div>
    <div class="section">
        <img src="waiter.avif" alt="Opening Hours"> 
        <h3>Opening Hours</h3>
        <p>
            Mon - Fri: 5am - 10am<br>
            Sat: 10am - 12pm<br>
            Sun: 12am - 9pm
        </p>
    </div>
</div>



</body>
</html>
```
# MENU
```
<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightgray;
        }
        nav {
            background-color: darkslategray;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: lightsteelblue;
            padding: 20px;
        }
        .menu-section {
            padding: 30px;
            max-width: 1000px;
            margin: auto;
        }
        .menu-title {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 20px;
        }
        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .menu-item {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            padding: 15px;
            width: 250px;
        }
        .menu-item img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            color: darkslateblue;
            margin: 10px 0;
        }
        .menu-item p {
            color: gray;
            font-size: 14px;
        }
        .menu-item span {
            display: block;
            font-size: 18px;
            font-weight: bold;
            color: darkslategray;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>Our Menu</h1>
</header>

<div class="menu-section">
    <h2 class="menu-title">Explore Our Delicious Dishes</h2>
    <div class="menu-items">
        <div class="menu-item">
            <img src="idly.jpg" alt="Dish 1">
            <h3>Special idly with vada</h3>
            <p>idli: The fluffy perfection. Idli love is real. Idli dreams do come true. Idli: The ultimate comfort food.</p>
            <span>$8</span>
        </div>
        <div class="menu-item">
            <img src="pongal.jpg" alt="Dish 2">
            <h3>Special Ghee Pongal</h3>
            <p>This Pongal, savor the flavors of tradition with our special menu</p>
            <span>$15</span>
        </div>
        <div class="menu-item">
            <img src="poori.webp" alt="Dish 3">
            <h3>Poori With Gravy</h3>
            <p>Our puri is the perfect canvas for your culinary adventure</p>
            <span>$12</span>
        </div>
        <div class="menu-item">
            <img src="chapathi.jpg" alt="Dish 4">
            <h3>Chapathi</h3>
            <p>Indian food is like a symphony of spices, where every note plays its part</p>
            <span>$7</span>
        </div>
    </div>
</div>

</body>
</html>
```

# ADMIN
```
<html>
<head>
    <title>Administration - MSD Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightgray;
        }
        nav {
            background-color: darkslategray;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: lightsteelblue;
            padding: 20px;
        }
        .admin-section {
            padding: 30px;
            max-width: 800px;
            margin: auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .admin-section h2 {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 20px;
        }
        .admin-team {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .team-member {
            background-color: lightblue;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            width: 200px;
        }
        .team-member img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .admin-login {
            margin-top: 30px;
            text-align: center;
        }
        .admin-login input {
            padding: 10px;
            margin: 10px 5px;
            border: 1px solid gray;
            border-radius: 5px;
            font-size: 14px;
        }
        .admin-login button {
            padding: 10px 20px;
            background-color: darkslateblue;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .admin-login button:hover {
            background-color: slateblue;
        }
    </style>
</head>
<body>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>MSD Restaurant</h1>
</header>

<div class="admin-section">
    <h2>Meet the Team</h2>
    <div class="admin-team">
        <div class="team-member">
            <h3>HEMNATH</h3>
            <p>Manager</p>
        </div>
        <div class="team-member">
            <h3>VIJAY</h3>
            <p>Assistant Manager</p>
        </div>
        <div class="team-member">
            <h3>SURYA</h3>
            <p>HR Head</p>
        </div>
    </div>

    <div class="admin-login">
        <h2>Admin Login</h2>
        <form>
            <input type="text" placeholder="Username" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>
</div>

</body>
</html>

```

# BOOKTABLE
```
<html>
<head>
    <title>Book a Table - MSD Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightgray;
        }
        nav {
            background-color: darkslategray;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: lightsteelblue;
            padding: 20px;
        }
        .booking-section {
            padding: 30px;
            max-width: 600px;
            margin: auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .booking-section h2 {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 20px;
        }
        .booking-form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .booking-form input, .booking-form select, .booking-form button {
            padding: 10px;
            font-size: 16px;
            border: 1px solid gray;
            border-radius: 5px;
        }
        .booking-form button {
            background-color: darkslateblue;
            color: white;
            cursor: pointer;
        }
        .booking-form button:hover {
            background-color: slateblue;
        }
    </style>
</head>
<body>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="adminstration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>Book a Table</h1>
</header>

<div class="booking-section">
    <h2>Reserve Your Table Now</h2>
    <form class="booking-form">
        <input type="text" name="name" placeholder="Your Full Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="tel" name="phone" placeholder="Your Phone Number" required>
        <select name="guests" required>
            <option value="" disabled selected>Number of Guests</option>
            <option value="1">1 Guest</option>
            <option value="2">2 Guests</option>
            <option value="3">3 Guests</option>
            <option value="4">4 Guests</option>
            <option value="5">5 Guests</option>
            <option value="6+">6+ Guests</option>
        </select>
        <input type="date" name="date" required>
        <input type="time" name="time" required>
        <button type="submit">Book Now</button>
    </form>
</div>

</body>
</html>
```

# CONTACT 
```

<html>
<head>
    <title>Contact Us - MSD Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
        }
        nav {
            background-color: grey;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: white;
            padding: 20px;
        }
        .contact-section {
            padding: 30px;
            max-width: 600px;
            margin: auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact-section h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .contact-section form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .contact-section input, .contact-section textarea, .contact-section button {
            padding: 10px;
            font-size: 16px;
            border: 1px solid whitesmoke;
            border-radius: 5px;
        }
        .contact-section textarea {
            resize: none;
            height: 100px;
        }
        .contact-section button {
            background-color: #4a4a4a;
            color: white;
            cursor: pointer;
        }
    </style>
</head>
<body>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>Contact Us</h1>
</header>

<div class="contact-section">
    <h2>We'd Love to Hear from You!</h2>
    <form>
        <input type="text" name="name" placeholder="Your Full Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="tel" name="phone" placeholder="Your Phone Number (optional)">
        <textarea name="message" placeholder="Your Message..." required></textarea>
        <button type="submit">Send Message</button>
    </form>
</div>

</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2025-11-22 173825.png>)

![alt text](<Screenshot (164).png>)
![alt text](<Screenshot (165).png>)
![alt text](<Screenshot (166).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

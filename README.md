# Ex.07 Restaurant Website
## Date:18/12/2024

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
restaurant.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Restaurant</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <header>
        <center>
             <h1>THE WOW'S  KITCHEN</h1>
        </center>
            <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            </nav>
        
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to The wow's kitchen, where we serve the finest dishes made from the freshest ingredients. Our chefs are dedicated to providing you with an unforgettable dining experience.</p>
    </section>

    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-container">
            <div class="menu-right">
                <ul>
                    <li>
                        <img src="C:\Users\admin\restweb\chic biriyani.avif" width="300">
                        <b>chicken biriyani - 240 Rs</b>
                    </li>
                    <li>
                        <img src="C:\Users\admin\restweb\chic leg fried.avif" width="300">
                        <b>chicken leg fried - 70 Rs</b>
                    </li>
                    <li>
                        <img src="C:\Users\admin\restweb\grill.avif" width="300">
                        <b>Full grill chicken - 399 Rs</b>
                        </li> 
                    </li>
                </ul>
            </div>
            <div class="menu-left">
                <ul>
                    <li>
                        <img src="C:\Users\admin\restweb\bucket.jpg"  width="400" height="240">
                        <b>Bucket fried chicken- 999 Rs</b>
                    </li>
                    <li>
                        <img src="C:\Users\admin\restweb\chic65.jpg"  width="400">
                       <b> CHICKEN 65 - 99 Rs</b>
                    </li>
                    <li>
                        <img src="C:\Users\admin\restweb\fries.jpg"  width="400">
                         <b>French Fries - 90 Rs</b>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: thewowskitchen@gmail.com</p>
        <p>Phone: (044) 044-0444</p>
        <p>Address: 985,anna nagar, chennai </p>
    </section>

    <footer>
        <p>&copy; thewow'skitchen. All rights reserved.</p>
    </footer>
</body>
</html>
```

```
rest.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    font-size: large;
    background-image: url('pur.jpg');
    background-size: cover; 
    background-position: center; 
    background-repeat: no-repeat; 
    padding: 20px;
    color: white;
}

header {
    background: #f347ff; 
    color: rgb(246, 240, 245);
    padding: 10px 0;
    text-align: center;
    font-style: oblique;
    border-radius: 20px;
}



nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: rgb(15, 14, 14);
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 20px;
    margin: 10px;
}

h2 {
    color: #f552e2; 
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #88bc19;
    color: rgb(240, 240, 230);
    position: relative;
    bottom: 0;
    width: 100%;
}
.menu-container {
    display: flex;
    justify-content: space-between;
}

.menu-left, .menu-right {
    width: 48%; 
}

.menu-left ul, .menu-right ul {
    list-style: none;
    padding: 0;
    font-size: large;
}

.menu-left li, .menu-right li {
    display: flex;
    align-items: center;
    margin-bottom: 20px;
}

.menu-left li img, .menu-right li img {
    margin-right: 10px;
    border-radius: 45px;
}
```


## OUTPUT:
![alt text](<Screenshot (209).png>)
![alt text](<Screenshot (210).png>)
![alt text](<Screenshot (211).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

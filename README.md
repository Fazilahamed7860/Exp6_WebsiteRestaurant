# Ex.06 Restaurant Website
## Date:19.12.2025

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
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Delicious Bites Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navbar -->
    <header>
        <h1 class="logo">Delicious Bites</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#menu">Menu</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-text">
            <h2>Fresh Food, Great Taste</h2>
            <p>Experience the best flavors in town</p>
            <button>Order Now</button>
        </div>
    </section>

    <!-- Menu Section -->
    <section class="menu" id="menu">
        <h2>Our Menu</h2>

        <div class="menu-items">
            <div class="card">
                <img src="biriyaani.jpeg" alt="Food Image">
                <h3>Biryani</h3>
                <p>Spicy and aromatic</p>
            </div>

            <div class="card">
                <img src="burger.jpeg" alt="Food Image">
                <h3>Burger</h3>
                <p>Juicy and tasty</p>
            </div>

            <div class="card">
                <img src="pasta.jpg" alt="Food Image">
                <h3>Pasta</h3>
                <p>Rich Italian flavors</p>
            </div>
            <div class="card">
                <img src="shawarmaa.jpeg" alt="Food Image">
                <h3>Shawarma</h3>
                <p>Spicy and flavorful</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        
        
        <div class="about-text">
            <h2>About Us</h2>
            <p>
                We serve high-quality food made with love and fresh ingredients.
                Our restaurant offers a warm and friendly atmosphere.
            </p>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact">
        <p>📍 Chennai, India</p>
        <p>📞 +91 98765 43210</p>
        <p>© 2025 Delicious Bites</p>
    </footer>

</body>
</html>

CSS
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f8f8f8;
}

/* Header */
header {
    background: #222;
    color: #fff;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav a {
    color: #fff;
    margin-left: 20px;
    text-decoration: none;
    font-weight: bold;
}

header nav a:hover {
    color: orange;
}

/* Hero Section */
.hero {
    height: 90vh;
    background: url("https://via.placeholder.com/1200x600") center/cover no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
}

.hero-text {
    background: rgba(0,0,0,0.6);
    padding: 30px;
    color: #fff;
    text-align: center;
    border-radius: 10px;
}

.hero button {
    margin-top: 15px;
    padding: 10px 25px;
    border: none;
    background: orange;
    color: #fff;
    font-size: 16px;
    cursor: pointer;
}

.hero button:hover {
    background: darkorange;
}

/* Menu */
.menu {
    padding: 60px 40px;
    text-align: center;
}

.menu-items {
    display: flex;
    justify-content: center;
    gap: 25px;
    margin-top: 30px;
    flex-wrap: wrap;
}

.card {
    background: #fff;
    width: 260px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    padding-bottom: 15px;
}

.card img {
    width: 100%;
    border-radius: 10px 10px 0 0;
}

.card h3 {
    margin: 10px 0;
}

/* About */
.about {
    padding: 60px 40px;
    display: flex;
    align-items: center;
    gap: 40px;
    flex-wrap: wrap;
}

.about img {
    width: 100%;
    max-width: 400px;
    border-radius: 10px;
}

.about-text {
    max-width: 500px;
}

/* Footer */
footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 20px;
}

```

## OUTPUT:
![alt text](<Screenshot (20).png>) ![alt text](<Screenshot (21).png>) ![alt text](<Screenshot (22).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

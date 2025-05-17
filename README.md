# Ex.07 Restaurant Website
## Date:17.05.25

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Delicious Bites - Restaurant</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Quicksand', sans-serif;
    }

    body {
      background: #f8f8f8;
      color: #333;
    }

    header {
      background-image: url('C:\Users\admin\Videos\New folder\restweb\rest\restapp\static\images.png\bgrest.png');
      background-size: cover;
      background-position: center;
      color: rgb(160, 228, 32);
      text-align: center;
      padding: 80px 20px;
    }

    nav {
      background: #333;
      color: rgb(226, 112, 112);
      display: flex;
      justify-content: space-around;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .search-bar {
      text-align: center;
      margin: 20px;
    }

    .search-bar input {
      padding: 10px;
      width: 300px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    .section {
      padding: 40px 20px;
    }

    .menu-items {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .dish {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 250px;
      text-align: center;
      padding: 20px;
    }

    .dish img {
      width: 100%;
      border-radius: 10px;
      height: 150px;
      object-fit: cover;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Delicious Bites</h1>
    <p>Your go-to place for amazing food!</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
    <a href="#location">Location</a>
  </nav>

  <div class="search-bar">
    <input type="text" placeholder="Search for dishes...">
  </div>

  <section class="section" id="home">
    <h2>About Us</h2>
    <p>Delicious Bites offers a variety of mouth-watering dishes made with the freshest ingredients. Join us for a memorable dining experience.Get offers on our exclusive cuisine and get the best offers on our premium beverages</p>
  </section>

  <section class="section" id="menu">
    <h2>Our Menu</h2>
    <div class="menu-items">
      <div class="dish">
        <img src="C:\Users\admin\Videos\New folder\restweb\rest\restapp\static\images.png\grilled chicken.png" alt="Grilled Chicken">
        <h3>Spicy Grilled Chicken</h3>
        <p>Succulent grilled chicken with a fiery spice blend.To entertain you tastebuds.</p>
      </div>
      <div class="dish">
        <img src="C:\Users\admin\Videos\New folder\restweb\rest\restapp\static\images.png\pizza.png" alt="Veggie Pizza">
        <h3>Veggie Delight Pizza</h3>
        <p>Loaded with fresh veggies and cheese on a crispy crust.And extra cheesy pull.</p>
      </div>
      <div class="dish">
        <img src="C:\Users\admin\Videos\New folder\restweb\rest\restapp\static\images.png\pannertikka.png" alt="Paneer Tikka">
        <h3>Paneer Tikka</h3>
        <p>Marinated paneer cubes grilled to perfection.Spiced with authentic indian spices</p>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@deliciousbites.com</p>
    <p>Phone: +91-9876543210</p>
  </section>

  <section class="section" id="location">
    <h2>Our Location</h2>
    <p>123 Food Street, Flavor Town, India</p>
  </section>

  <footer>
    &copy; Developed by Harsheni.S
  </footer>
</body>
</html>

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/c6ce64e2-1d2d-43e3-9042-c43139dfcc85)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

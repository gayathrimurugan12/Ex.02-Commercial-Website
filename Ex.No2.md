# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Flexbox Commercial Site</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header class="header">
    <div class="logo">MyShop</div>
    <nav class="nav">
      <a href="#">Home</a>
      <a href="#">Products</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Welcome to MyShop</h1>
      <p>Best products at the best prices.</p>
      <a href="#" class="btn">Shop Now</a>
    </div>
  </section>

  <section class="products">
    <h2>Our Products</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="download (1).jpeg" alt="Product 1">
        <h3>camera</h3>
        <p>$29.99</p>
      </div>
      <div class="product-card">
        <img src="bag.jpeg" alt="Product 2">
        <h3>bag</h3>
        <p>$39.99</p>
      </div>
      <div class="product-card">
        <img src="watch.jpeg" alt="Product 3">
        <h3>i watch</h3>
        <p>$49.99</p>
      </div>
    </div>
  </section>

  <footer class="footer">
    <p>&copy; 2025 MyShop. All rights reserved.</p>
  </footer>

</body>
</html>

```
style.css
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
}


.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color:lightgrey;
  color: white;
}

.nav a {
  margin-left: 20px;
  color: lightcoral;
  text-decoration: none;
}

.logo {
  font-size: 1.5em;
  font-weight: bold;
}


.hero {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 300px;
  background: url('https://via.placeholder.com/1200x300') no-repeat center center/cover;
  color: white;
  text-align: center;
}

.hero-content {
  background-color:lightsteelblue;
  padding: 20px;
}

.btn {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #ff6600;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
}


.products {
  padding: 40px 20px;
  background-color:lightpink;
  text-align: center;
}

.product-grid {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 20px;
}

.product-card {
  background: white;
  padding: 20px;
  width: 250px;
  border: 1px solid lightskyblue;
  border-radius: 8px;
}


.footer {
  background-color: lightseagreen;
  color: lightcoral;
  text-align: center;
  padding: 15px;
}

```

## OUTPUT
<img width="1909" height="759" alt="image" src="https://github.com/user-attachments/assets/4b5f720f-3241-45d6-b402-55478948bb95" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.

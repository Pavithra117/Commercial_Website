# Ex02 Commercial Website
## Date: 17/05/2026

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
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FlexShop</title>
<link rel="stylesheet" href="style1.css">
</head>
<body>

<header>
    <h2>Flex<span>Shop</span></h2>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
        <a href="#account">Account</a>
    </nav>
</header>

<!-- Home -->
<section id="home" class="hero">
    <div class="text">
        <h1>Welcome to FlexShop</h1>
        <p>Your one-stop online shopping store</p>
        <button>Shop Now</button>
    </div>
    <img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?w=500">
</section>

<!-- Products -->
<section id="products" class="products">
    <h1>Our Products</h1>
    <div class="cards">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1546868871-7041f2a55e12?w=300">
            <h3>Smart Watch</h3>
            <p>$20</p>
            <button>Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1583394838336-acd977736f90?w=300">
            <h3>Earbuds</h3>
            <p>$30</p>
            <button>Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=300">
            <h3>Backpack</h3>
            <p>$40</p>
            <button>Add to Cart</button>
        </div>

    </div>
</section>

<!-- About -->
<section id="about" class="section">
    <h1>About Us</h1>
    <p>Welcome to FlexShop, your trusted online shopping destination. 
        We are committed to providing high-quality products at affordable prices 
        with excellent customer service. Our mission is to make online shopping 
        simple, secure, and enjoyable for everyone. </p>
</section>

<!-- Contact -->
<section id="contact" class="section">
    <h1>Contact Us</h1>
    <p>Email: support@flexshop.com</p>
    <p>Phone: +91 9876543210</p>
</section>

<section id="account" class="section">
    <h2>My Account</h2>
    <form>
        <input type="text" placeholder="Username">
        <input type="password" placeholder="Password">
        <button type="submit">Login</button>
    </form>
</section>

<footer>
    <p>© 2026 FlexShop | Follow us on Facebook • Instagram • Twitter</p>
</footer>

</body>
</html>
```
## style.html
```
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
}

body{
background:#f5f5f5;
}

header{
background:black;
color:white;
display:flex;
justify-content:space-between;
padding:20px 50px;
position:sticky;
top:0;
}

span{
color:orange;
}

nav a{
color:white;
text-decoration:none;
margin:15px;
}

nav a:hover{
color:orange;
}

/* Home */
.hero{
display:flex;
justify-content:space-between;
align-items:center;
padding:60px;
background:white;
}

.hero img{
width:400px;
border-radius:10px;
}

.text h1{
font-size:50px;
}

.text p{
margin:20px 0;
font-size:20px;
}

button{
padding:12px 20px;
background:orange;
color:white;
border:none;
border-radius:5px;
cursor:pointer;
margin:5px;
}

/* Products */
.products{
padding:50px;
text-align:center;
}

.cards{
display:flex;
justify-content:space-around;
margin-top:30px;
flex-wrap:wrap;
}

.card{
width:250px;
padding:20px;
background:white;
box-shadow:0 5px 10px rgba(0,0,0,0.2);
border-radius:10px;
margin:15px;
}

.card img{
width:100%;
border-radius:10px;
}

.card p{
color:orange;
margin:10px 0;
}

/* Sections */
.section{
padding:60px;
text-align:center;
background:white;
margin:20px;
border-radius:10px;
}

footer{
background:black;
color:white;
text-align:center;
padding:20px;
margin-top:20px;
}

.account{
text-align:center;
padding:60px;
background:#eef2f7;
}

.account h2{
margin-bottom:20px;
font-size:35px;
}

.account form{
display:flex;
flex-direction:column;
width:300px;
margin:auto;
gap:15px;
}

.account input{
padding:15px;
border:1px solid #ccc;
border-radius:10px;
}

.account button{
padding:15px;
background:#007bff;
color:white;
border:none;
border-radius:25px;
cursor:pointer;
}

.account button:hover{
background:#0056b3;
}
```

## OUTPUT
<img width="1889" height="775" alt="image" src="https://github.com/user-attachments/assets/47aef0d6-9038-433f-afb7-7f2831b63f44" />

<img width="1903" height="866" alt="image" src="https://github.com/user-attachments/assets/76780368-c656-485d-bc84-cf7517e1323d" />

<img width="1877" height="247" alt="image" src="https://github.com/user-attachments/assets/522b32a8-0355-4733-901c-b9ffb5c635a2" />

<img width="1786" height="247" alt="image" src="https://github.com/user-attachments/assets/299b44f2-7b7e-4f0e-92a7-0659e7332fe9" />

<img width="1718" height="240" alt="image" src="https://github.com/user-attachments/assets/5aaba243-a9d8-4d81-aab5-340cb7284841" />




## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.

# Ex.07 Restaurant Website
## Date:04/05/2025

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
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>VirtuTech Solutions</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <div class="logo">Virtu<span>Tech</span> Solutions</div>
    <nav>
      <a href="#">HOME</a>
      <a href="#">PEOPLE</a>
      <a href="#">PRODUCTS</a>
      <a href="#">CONTACT</a>
    </nav>
    <div class="search-bar">
      <input type="text" placeholder="Enter To Search" />
      <button>Search</button>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="hero-text">
        <h1>A Software Agency shaping <span class="highlight">ideas into</span> Products</h1>
        <p>"People who are really serious about software should make their own hardware" - Alan Kay.</p>
        <button class="join-btn">JOIN US</button>
      </div>
      <div class="login-box">
        <h2>Login Here</h2>
        <input type="text" placeholder="Username or Email" />
        <input type="password" placeholder="Password" />
        <button class="login-btn">Login</button>
        <p>Don't have an account? <a href="#">Sign up here</a></p>
        <p>Log in with</p>
        <div class="social-icons">
          <span>🌐</span>
          <span>📸</span>
          <span>🐦</span>
          <span>🟢</span>
        </div>
      </div>
    </section>
  </main>

  <footer>
    Designed and Developed by Dr.R.SELVAKUMAR © 2023
  </footer>
</body>
</html>

---
---
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Georgia', serif;
  background: linear-gradient(to bottom, #f09b88 50%, #b9a3b5 50%);
  color: white;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background: transparent;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  color: blue;
}

.logo span {
  color: purple;
}

nav a {
  margin: 0 15px;
  text-decoration: none;
  color: white;
  font-weight: bold;
}

.search-bar {
  display: flex;
}

.search-bar input {
  padding: 5px;
  border: none;
}

.search-bar button {
  padding: 5px 10px;
  background: orange;
  border: none;
  color: white;
  cursor: pointer;
}

.hero {
  display: flex;
  justify-content: space-between;
  padding: 50px;
}

.hero-text {
  max-width: 60%;
}

.hero-text h1 {
  font-size: 36px;
  margin-bottom: 20px;
}

.hero-text .highlight {
  color: orange;
}

.hero-text p {
  margin-bottom: 20px;
  font-weight: bold;
}

.join-btn {
  padding: 10px 20px;
  background: orange;
  border: none;
  cursor: pointer;
  color: white;
  font-weight: bold;
}

.login-box {
  background: #2c2c2c;
  padding: 30px;
  border-radius: 10px;
  width: 300px;
  color: white;
}

.login-box h2 {
  background: white;
  color: orange;
  text-align: center;
  padding: 10px;
  margin-bottom: 20px;
  border-radius: 5px;
}

.login-box input {
  display: block;
  width: 100%;
  padding: 10px;
  margin-bottom: 15px;
  border: none;
  border-bottom: 1px solid orange;
  background: transparent;
  color: white;
}

.login-box .login-btn {
  width: 100%;
  padding: 10px;
  background: orange;
  border: none;
  color: white;
  font-weight: bold;
  cursor: pointer;
  margin-bottom: 10px;
}

.login-box a {
  color: orange;
  text-decoration: none;
}

.social-icons span {
  margin-right: 10px;
  font-size: 20px;
}

footer {
  text-align: center;
  background: red;
  padding: 10px;
  color: yellow;
  font-weight: bold;
}

---


## OUTPUT:
![alt text](<Screenshot 2025-05-04 171224.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

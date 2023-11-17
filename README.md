# Ex.07 Software Product Company Website
## Date: 5/11/23

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Software Product Development Company</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    header {
      background-color: #3498db;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    nav {
      display: flex;
      justify-content: space-around;
      background-color: #2980b9;
      padding: 10px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
    }

    section {
      padding: 20px;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }

    .product {
      width: 30%;
      margin: 10px;
      padding: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
      text-align: center;
    }

    .people {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }

    .person {
      width: 30%;
      margin: 10px;
      text-align: center;
    }

    .person img {
      width: 100%;
      max-width: 150px; 
      height: auto;
      border-radius: 50%; 
      object-fit: cover; 
    }
    footer {
      background-color: #34495e;
      color: #fff;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Software Product Development Company</h1>
  </header>

  <nav>
    <a href="#products">Products</a>
    <a href="#people">People</a>
    <a href="#contact">Contact Us</a>
  </nav>

  <section id="products">
    <h2>Our Products</h2>
    <div class="products">
      <div class="product">Antivirus Software</div>
      <div class="product">Blogging Platform</div>
      <div class="product">Cloud services</div>
      <div class="product">Computer Aided Design</div>
      <div class="product">Marketing Automation</div>
      <div class="product">Machine learning</div>
      <div class="product">Productivity Tool</div>
      <div class="product">Reporting Tool</div>
      <div class="product">Virtual Assistant</div>
      <div class="product">Software Development Tool</div>
      <div class="product">Security Software</div>
      <div class="product">Presentation Software</div>
    </div>
  </section>

  <section id="people">
    <h2>Our Team</h2>
    <div class="people">
      <div class="person">
        <img src="/static/image.png" alt="Person 1">
        <p>Shruthi</p>
        <p>CEO</p>
      </div>
      <div class="person">
        <img src="/static/image-3.png" alt="Person 2">
        <p>Hari haran</p>
        <p>CTO</p>
      </div>
      <div class="person">
        <img src="/static/image-2.png" alt="Person 3">
        <p>nandhini</p>
        <p>Lead Developer</p>
      </div>
      <div class="person">
        <img src="/static/image-1.png" alt="Person 4">
        <p>Varsha</p>
        <p>UX Designer</p>
      </div>
      <div class="person">
        <img src="/static/image-4.png" alt="Person 5">
        <p>Surya</p>
        <p>QA Engineer</p>
      </div>
      <div class="person">
        <img src="/static/image-5.png" alt="Person 6">
        <p>Priyanka</p>
        <p>Marketing Manager</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Address: Saveeth Engineering College,thandalam,chennai-77</p>
    <p>Phone: 9876543210</p>
    <p>Email: startco123@gmail.com</p>
  </section>

  <footer>
    <p>startupco</p>
  </footer>
</body>
</html>
```

## OUTPUT:
![image](https://github.com/Dhiyanesh24/softweb/assets/118362288/babdf307-672a-47af-99db-20cad2063f51)
![image](https://github.com/Dhiyanesh24/softweb/assets/118362288/25a9c884-d520-4975-b186-9313585daf3d)
![image](https://github.com/Dhiyanesh24/softweb/assets/118362288/7b5f011d-5266-4762-bdb8-5c27b7c24d62)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

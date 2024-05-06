# Ex.07 Software Product Company Website
## Date:
06-05-2024
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

~~~
home.html
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>RAYNE ENTERPRISES</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(9, 2, 2, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(priya\ softapp.webp);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .logo {
        color: rgb(127, 136, 5);
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: rgb(175, 7, 63);
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgb(233, 174, 103);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: rgb(23, 11, 110);
      }
      ::placeholder {
        color: rgb(72, 6, 6);
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background: rgb(233, 64, 202);
        cursor: pointer;
      }
      #search.hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(71, 132, 136);
        color: #081b29;
        box-shadow: 0 0 20px rgb(71, 101, 103);
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: rgb(180, 2, 180);
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(178, 66, 178);
        color: #081b29;
        box-shadow: 0 0 20px rgb(133, 58, 83);
      }
      .content {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        text-align: center;
      }
      .text h2 {
        color: rgb(155, 155, 110);
        font-weight: 800;
        font-size: 50px;
        letter-spacing: 3px;
      }
      .text p {
        color: rgb(184, 184, 133);
        text-transform: capitalize;
        font-size: 15px;
        margin-bottom: 30px;
        word-spacing: 2px;
        letter-spacing: 1px;
      }
      .login {
        margin: 0px 10px;
        border: 2px solid black;
        padding: 13px 35px;
        letter-spacing: 1px;
        color: black;
        border-radius: 30px;
        background-color: rgb(18, 199, 87);
        text-decoration: none;
      }
      .login:hover {
        border: 2px solid rgb(70, 219, 20);
        color: black;
        background-color: black;
        transition: 0.5s;
        cursor: pointer;
      }
      .signup {
        margin: 0px 10px;
        border: 2px solid black;
        padding: 13px 35px;
        letter-spacing: 1px;
        color: black;
        border-radius: 30px;
        background-color: rgb(66, 214, 61);
        text-decoration: none;
      }
      .signup:hover {
        border: 2px solid rgb(102, 137, 13);
        color: rgb(174, 217, 34);
        background-color: rgb(121, 127, 93);
        transition: 0.5s;
        cursor: pointer;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(217, 255, 0);
        color: #081b29;
        box-shadow: 0 0 20px rgb(221, 255, 0);
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">MY SOLUTIONS</h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="product.html"> Product </a></li>
          <li><a href="people.html"> people </a></li>
          <li><a href="contact.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button id="search" type="submit">Search</button>
        </form>
      </div>
      <div class="content">
        <div class="text">
          <h2>
            "SOLVING THE BEST YOU CAN." 
          </h2>
          <br />

          <br />
          <div>
            <a href="#" class="login"> Log In </a>
            <a href="#" class="signup"> Sign Up </a>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <center>DESIGNED AND DEVELOPED BY Lakshmi Mounika (212223100026)</center>
    </footer>
  </body>
</html>

~~~
~~~
product.html
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Product Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(152, 11, 11, 0.75),
            rgba(117, 12, 12, 0.75)
          ),
          url(priya\ softapp.webp);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-product {
        border: 1px;
        padding: 10px;
        color: rgb(160, 162, 98);
        background-color: rgb(8, 11, 95);
        border-radius: 30px;
      }
      .logo {
        color: rgb(11, 192, 177);
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: rgb(20, 136, 125);
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgb(137, 54, 54);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: black;
      }
      ::placeholder {
        color: black;
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: black;
        border-radius: 10px;
        background: rgb(163, 72, 11);
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: black;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(84, 3, 30);
        color: #081b29;
        box-shadow: 0 0 20px rgb(112, 3, 41);
      }
      .container {
        background: transparent;
        padding: 10px 5%;
        padding-bottom: 100px;
      }
      .container .box-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
        gap: 100px;
      }
      .container .box-container .box {
        color: rgb(122, 113, 31);
        box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid rgb(53, 181, 36);
        padding: 30px 20px;
      }
      .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
      }
      .container .box-container .box h3 {
        color: rgb(9, 51, 149);
        font-size: large;
        padding: 20px 0;
      }
      .container .box-container .box p {
        color: rgb(70, 3, 70);
        font-size: small;
        line-height: 1.5;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(2, 36, 139);
        color: #081b29;
        box-shadow: 0 0 20px rgb(14, 9, 152);
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">MY SOLUTIONS</h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="product.html" class="bg-product"> Product </a></li>
          <li><a href="people.html"> people </a></li>
          <li><a href="contact.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="container">
        <div class="box-container">
          <div class="box">
            <h3>C</h3>
            <p>
              Efficiency Redefined: Harnessing the Power of C for Next-Level Development
            </p>
          </div>
          <div class="box">
            <h3>C++</h3>
            <p>
              Crafting Performance: Where Precision Meets C++ Programming.
            </p>
          </div>
          <div class="box">
            <h3>JAVA</h3>
            <p>
                java is a popular programming language that is widely used for developing a variety of applications
            </p>
          </div>
          <div class="box">
            <h3>SHELL</h3>
            <p>
              Shell is a server side scripting language that is embedded in HTML.
            </p>
          </div>
          <div class="box">
            <h3>PYTHON</h3>
            <p>
              Unlocking Innovation: Python Paving the Way to Progress.
            </p>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <center>Designed and DEVELOPED BY Lakshmi Mounika (212223100026)</center>
    </footer>
  </body>
</html>

~~~
~~~
people.html
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>people page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(backgroundweb\ 7.jpg );
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-people {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: rgb(131, 4, 25);
        border-radius: 30px;
      }
      .logo {
        color: rgb(88, 4, 32);
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: rgb(199, 5, 199);
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(83, 67, 67, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: rgb(62, 11, 11);
      }
      ::placeholder {
        color: rgb(69, 13, 13);
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: rgb(80, 206, 130);
        border-radius: 10px;
        background:rgb(25, 15, 162);
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: rgb(153, 212, 190);
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(63, 14, 159);
        color: #081b29;
        box-shadow: 0 0 20px rgb(221, 125, 231);
      }
      .image {
        position: relative;
        border: 0;
        top: 150px;

        background: transparent;
      }
      .image table {
        border: 0;
        color: rgb(107, 174, 126);
        position: relative;
        left: 200px;
        border: 10PX;
        padding-left: 10px;
      
      }
      .image table img {
        height: 140px;
        width: 140px;
        border: 2px solid white;
        padding: 5px;
        border-radius: 50%;
      }
      .image table td {
        color:rgb(231, 127, 30);
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(233, 48, 6);
        color: black;
        box-shadow: 0 0 20px rgb(200, 6, 13);
      }
      .space{
        padding-left: 30px;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">MY SOLUTIONS</h1>
          <li><a href="home.html"> home </a></li>
          <li><a href="product.html"> Product </a></li>
          <li><a href="people.html" class="bg-people"> People </a></li>
          <li><a href="contact.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="image">
        <table cellspacing="80" >
          <tr align="center">
            <td><img src="Screenshot 2024-05-06 230012 - Copy.png" /></td>
            <td><img src="WhatsApp Image 2024-05-06 at 22.55.30_b572afd6.jpg" /></td>
            <td><img src="WhatsApp Image 2024-05-06 at 22.56.01_1cd266c9.jpg" /></td>
            <td><img src="WhatsApp Image 2024-05-06 at 22.57.49_3ba9fffb - Copy.jpg"/></td>
           
          </tr>
          <tr align="center" class="space">
            <th>Tarunika</th>
            <th>Mounika</th>
            <th>Bunny</th>
            <th>Thenu</th>
            
            
          </tr>
          <tr align="center">
            <td>CEO</td>
            <td>CEO,Co-Founder</td>
            <td>CT0</td>
            <td>DIRECTOR</td>
          
            
          </tr>
        </table>
      </div>
    </div>
    <footer>
      <center>DESIGNED AND DEVELOPED BY Lakshmi Mounika (212223100026)</center>
    </footer>
  </body>
</html>
~~~
~~~
contact.html
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(priya\ softapp.webp);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-contact {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: peachpuff;
        border-radius: 30px;
      }
      .logo {
        color: pink;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: palevioletred;
      }
      .navbar form {
        width: 300px;
        height: 40px;
        display: flex;
        background: black;
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      .navbar form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      .navbar form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: bl;
        border-radius: 10px;
        background: aquamarine;
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: bl;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(234, 255, 0);
        color: #081b29;
        box-shadow: white;
      }
      .box {
        display: flex;
        column-gap: 40px;
        background: transparent;
        position: relative;
        top: 50px;
        width: 220px;
      }
      .box-1 {
        height: 400px;
        width: 400px;
        border: 3px solid white;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 250px;
      }
      .box-2 {
        height: 400px;
        width: 400px;
        border: 3px solid white;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 300px;
      }
      .box-1 form {
        display: flex;
        color: antiquewhite;
        background: transparent;
        padding: 10px;
        font-size: 15px;
        position: relative;
        top: 15px;
      }
      .box-1 form input {
        background: transparent;
        display: flex;
        border: 1px solid antiquewhite;
        border-radius: 10px;
        padding: 15px 30px;
        font-size: 15px;
        color: whitesmoke;
        position: relative;
        top: 30px;
      }
      .box-1 form textarea {
        background: transparent;
        color: white;
        padding: 15px 10px;
        position: relative;
        top: 30px;
        left: 20px;
        border: 1px solid white;
        border-radius: 10px;
        width: 300px;
      }
      .box-1 form button {
        border: 0;
        outline: none;
        padding: 10px 20px;
        color: black;
        border-radius: 30px;
        background: white;
        cursor: pointer;
        position: relative;
        top: 50px;
      }
      .box-2 h2 {
        color: white;
        position: relative;
        top: 25px;
        left: 50px;
        font-size: 30px;
      }
      .box-2 p {
        color: white;
        position: relative;
        top: 50px;
        padding: 10px 80px;
      }
      .box-2 span {
        color: rgb(212, 255, 0);
        font-size: 20px;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: paleturquoise;
        color: #081b29;
        box-shadow: 0 0 20px rgb(242, 255, 0);
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">MY SOLUTIONS</h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="product.html"> Product </a></li>
          <li><a href="people.html"> people </a></li>
          <li><a href="contact.html" class="bg-contact"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="box">
        <div class="box-1">
          <form>
            <center>
              <h1>Contact Us</h1>
              <input type="text" placeholder="Your Name" />
              <br />
              <input type="email" placeholder="Your Email" />
              <br />
              
              <br />
              <button type="submit">Submit</button>
            </center>
          </form>
        </div>
        <div class="box-2">
          <h2>Contact Information</h2>
          <p>
            <span>Address</span> :Gandhi nagar road no:12 ,chennai
          </p>
          <p><span>Email</span> : lalli@gmail.com</p>
          <p><span>Phone</span> : 9876545321</p>
        </div>
      </div>
    </div>
    <footer>
      <center>DESIGNED AND DEVELOPED BY Lakshmi Mounika (212223100026)</center>
    </footer>
  </body>
</html>
~~~
## OUTPUT:
![alt text](<Screenshot 2024-05-06 234814-2.png>) 
![alt text](<Screenshot 2024-05-06 234822-2.png>) 
![alt text](<Screenshot 2024-05-06 234831.png>) 
![alt text](<Screenshot 2024-05-06 234838.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

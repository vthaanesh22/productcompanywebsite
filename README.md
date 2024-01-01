# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
``````
home.html
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title> Software Development Company </title>
<style type="text/css">
* {
margin: 0;
padding: 0;
font-family: Arial, Helvetica, sans-serif;
}
.banner {
width: 100%;
height: 100vh;
backgroundimage:lineargradient(rgba(253,114,0,0.848),rgba(0,0,0,0.75)),url(background.
;
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
color: #5500ff;
font-size: 40px;
font-weight: 700;
letter-spacing: 3px;
}
span {
color: rgb(54, 249, 11);
}
form {
width: 300px;
height: 40px;
display: flex;
background: rgba(255, 255, 255, 0.2);
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
color: white;
}
::placeholder {
color: white;
}
form button {
border: 0;
outline: none;
padding: 5px 20px;
color: white;
border-radius: 10px;
background: #1004f5;
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
color: white;
text-transform: uppercase;
}
.navbar li:hover {
border: 1px;
padding: 10px;
color: white;
background-color: #0814fc;
transition: 0.5s;
cursor: pointer;
border-radius: 30px;
}
.content {
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%,-50%);
text-align: center;
}
.text h2 {
color: white;
font-weight: 800;
font-size: 50px;
letter-spacing: 3px;
}
.text p {
color: white;
text-transform: capitalize;
font-size: 15px;
margin-bottom: 30px;
word-spacing: 2px;
letter-spacing: 1px;
}
.login {
margin: 0px 10px;
border: 2px solid #0828f8;
padding: 13px 35px;
letter-spacing: 1px;
color: white;
border-radius: 30px;
background-color: #0e12f5;
text-decoration: none;
}
.login:hover {
border: 2px solid #0e12f5;
color: #6fa1f8;
background-color: white;
transition: 0.5s;
cursor: pointer;
}
.signup {
margin: 0px 10px;
border: 2px solid #0e12f5;
padding: 13px 35px;
letter-spacing: 1px;
color: white;
border-radius: 30px;
background-color: #0e12f5;
text-decoration: none;
}
.signup:hover {
border: 2px solid #0e12f5;
color: #6fa1f8;
background-color: white;
transition: 0.5s;
cursor: pointer;
}
footer {
background-color: #0e25f5;
margin-top: auto;
}
</style>
</head>
<body>
<div class="banner">
<br>
<div class="navbar">
<h1 class="logo">C<span>ode</span>A<span>cadmey</span></h1>
<ul>
<li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
<li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
<li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
<li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
</ul>
<form action="" method="get">
<input type="text" placeholder="Enter to Search">
<button type="submit"> Search </button>
</form>
</div>
<div class="content">
<div class="text">
<h2> Web Development </h2>
<br>
<p> If you're just getting started learning to code, Codecademy is a great way to
get a sense for what coding is and how it works! </p>
<br>
<div>
<a href="#" class="login"> Log In </a>
<a href="#" class="signup"> Sign Up </a>
</div>
</div>
</div>
</div>
<footer>
<center> Designed and Developed by thaanesh </center>
</footer>
</body>
</html>
products.html
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title> Product Page </title>
<style type="text/css">
* {
margin: 0;
padding: 0;
font-family: Arial, Helvetica, sans-serif;
}
.banner {
width: 100%;
height: 100vh;
background-image: linear-gradient(rgba(254, 138, 14,
0.859),rgba(0,0,0,0.75)),url(background.jpg);
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
color: white;
background-color: #0004fd;
border-radius: 30px;
}
.logo {
color: #0213fa;
font-size: 40px;
font-weight: 700;
letter-spacing: 3px;
}
span {
color: rgb(29, 250, 8);
}
form {
width: 300px;
height: 40px;
display: flex;
background: rgba(255, 255, 255, 0.2);
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
color: white;
}
::placeholder {
color: white;
}
form button {
border: 0;
outline: none;
padding: 5px 20px;
color: white;
border-radius: 10px;
background: #3606e4;
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
color: white;
text-transform: uppercase;
}
.navbar li:hover {
border: 1px;
padding: 10px;
color: white;
background-color: #2f0bfa;
transition: 0.5s;
cursor: pointer;
border-radius: 30px;
}
.container {
background: transparent;
padding: 10px 5%;
padding-bottom: 100px;
}
.container .box-container {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
gap: 20px;
}
.container .box-container .box {
color: white;
box-shadow: 0 5px 10px rgba(0,0,0,.2);
border-radius: 20px;
background: transparent;
border: 1px solid white;
padding: 30px 20px;
}
.container .box-container .box img {
height: 70px;
border-radius: 20px;
}
.container .box-container .box h3 {
color: #300eef;
font-size: large;
padding: 10px 0;
}
.container .box-container .box p {
color: white;
font-size: small;
line-height: 1.5;
}
footer {
background-color: #2e0cf3;
margin-top: auto;
}
</style>
</head>
<body>
<div class="banner">
<br>
<div class="navbar">
<h1 class="logo">C<span>ode</span>A<span>cademy</span></h1>
<ul>
<li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
<li><a href="http://127.0.0.1:8000/static/product.html" class="bg-product">
Products </a></li>
<li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
<li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
</ul>
<form action="" method="get">
<input type="text" placeholder="Enter to Search">
<button type="submit"> Search </button>
</form>
</div>
<div class="container">
<div class="box-container">
<div class="box">
<img src="google.png" alt="">
<h3> Google </h3>
<p> Top tech company, famous for search and online services. </p>
</div>
<div class="box">
<img src="apple.png" alt="">
<h3> Apple </h3>
<p> Tech powerhouse, famed for iphones,macs, and innovation. </p>
</div>
<div class="box">
<img src="u.png" alt="">
<h3> Uber </h3>
<p> Ride and food app, global transportation game-changer. </p>
</div>
<div class="box">
<img src="meta.png" alt="">
<h3> Meta </h3>
<p> Social media powerhouse, home to facebook, instagram, and more. </p>
</div>
<div class="box">
<img src="idm.png" alt="">
<h3> IDM </h3>
<p> Internet Download manager, widely used for efficient file downloads. </p>
</div>
<div class="box">
<img src="windows.png" alt="">
<h3> Microsoft </h3>
<p> Tech giant, known for windows office, and cloud services. </p>
</div>
<div class="box">
<img src="Screenshot from 2023-12-28 23-22-30.png" alt="">
<h3> Reddit </h3>
<p> Diverse social platform for content sharing and discussion. </p>
</div>
<div class="box">
<img src="spotify.png" alt="">
<h3> Spotify </h3>
<p> Top music streaming service with songs,podcasts, and playlists. </p>
</div>
<div class="box">
<img src="youtube.png" alt="">
<h3> Youtube </h3>
<p> Global video-sharing giant for diverse content and engagement. </p>
</div>
<div class="box">
<img src="atoz.png" alt="">
<h3> Amazon </h3>
<p> E-commerce giant with prime,streaming, and cloud services. </p>
</div>
<div class="box">
<img src="insta.png" alt="">
<h3> Instagram </h3>
<p> Visual-centric social platform for photo and video sharing. </p>
</div>
<div class="box">
<img src="meta1.png" alt="">
<h3> Meta </h3>
<p> Social media powerhouse, home to facebook, instagram, and more. </p>
</div>
</div>
</div>
</div>
<footer>
<center> Designed and Developed by Bhuvana</center>
</footer>
</body>
</html>
contant.html
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title> Contact Us Page </title>
<style type="text/css">
* {
margin: 0;
padding: 0;
font-family: Arial, Helvetica, sans-serif;
}
.banner {
width: 100%;
height: 100vh;
background-image: linear-gradient(rgba(255, 135, 6,
0.886),rgba(0,0,0,0.75)),url(background.jpg);
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
background-color: #0824fd;
border-radius: 30px;
}
.logo {
color: #091dfa;
font-size: 40px;
font-weight: 700;
letter-spacing: 3px;
}
span {
color: rgb(81, 246, 10);
}
.navbar form {
width: 300px;
height: 40px;
display: flex;
background: rgba(255, 255, 255, 0.2);
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
color: white;
border-radius: 10px;
background: #0521f8;
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
color: white;
text-transform: uppercase;
}
.navbar li:hover {
border: 1px;
padding: 10px;
color: white;
background-color: #0630fe;
transition: 0.5s;
cursor: pointer;
border-radius: 30px;
}
.box {
display: flex;
column-gap: 40px;
background: transparent;
position: relative;
top: 50px;
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
border: 3px solid #0909fb;
border-radius: 20px;
background: transparent;
position: relative;
left: 300px;
}
.box-1 form {
display: flex;
color: white;
background: transparent;
padding: 10px;
font-size: 15px;
position: relative;
top: 15px;
}
.box-1 form input {
background: transparent;
display: flex;
border: 1px solid white;
border-radius: 10px;
padding: 15px 30px;
font-size: 15px;
color: white;
position: relative;
top: 30px;
}
.box-1 form textarea {
background: transparent;
color: white;
padding: 15px 10px;
position: relative;
top: 30px;
left: 30px;
border: 1px solid white;
border-radius: 10px;
}
.box-1 form button {
border: 0;
outline: none;
padding: 10px 20px;
color: white;
border-radius: 30px;
background: #0804ed;
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
color: #0d09f8;
font-size: 20px;
}
footer {
background-color: #250af6;
margin-top: auto;
}
</style>
</head>
<body>
<div class="banner">
<br>
<div class="navbar">
<h1 class="logo">C<span>ode</span>A<span>cademy</span></h1>
<ul>
<li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
<li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
<li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
<li><a href="http://127.0.0.1:8000/static/contact.html" class="bg-contact">
Contact </a></li>
</ul>
<form action="" method="get">
<input type="text" placeholder="Enter to Search">
<button type="submit"> Search </button>
</form>
</div>
<div class="box">
<div class="box-1">
<form>
<center>
<h1> Contact Us </h1>
<input type="text" placeholder="Your Name">
<br>
<input type="email" placeholder="Your Email">
<br>
<textarea rows="4" cols="40" placeholder="Your Message"> </textarea>
<br>
<button type="submit"> Submit </button>
</center>
</form>
</div>
<div class="box-2">
<h2> Contact Information </h2>
<p> <span>Address</span> : 41/14 pudhu palayam st,pillaiyar palayam,kanchipuram</p>
<p> <span>Email</span> : manogarbhuvana@gmail.com </p>
<p> <span>Phone</span> : 6380003117 </p>
</div>
</div>
</div>
<footer>
<center> Designed and Developed by Bhuvana </center>
</footer>
</body>
</html>
people.html
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title> people page </title>
<style type="text/css">
* {
margin: 0;
padding: 0;
font-family: Arial, Helvetica, sans-serif;
}
.banner {
width: 100%;
height: 100vh;
background-image: linear-gradient(rgba(255, 132, 16,
0.837),rgba(0,0,0,0.75)),url(background.jpg);
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
background-color: #1c05f3;
border-radius: 30px;
}
.logo {
color: #0b13f6;
font-size: 40px;
font-weight: 700;
letter-spacing: 3px;
}
span {
color: rgb(71, 250, 5);
}
form {
width: 300px;
height: 40px;
display: flex;
background: rgba(255, 255, 255, 0.2);
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
color: white;
}
::placeholder {
color: white;
}
form button {
border: 0;
outline: none;
padding: 5px 20px;
color: white;
border-radius: 10px;
background: #060af9;
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
color: white;
text-transform: uppercase;
}
.navbar li:hover {
border: 1px;
padding: 10px;
color: white;
background-color: #050dfe;
transition: 0.5s;
cursor: pointer;
border-radius: 30px;
}
.image {
position: relative;
border: 0;
top: 70px;
background: transparent;
}
.image table {
border: 0;
color: white;
position: relative;
left: 150px;
}
.image table img {
height: 140px;
width: 140px;
border: 2px solid white;
padding: 5px;
border-radius: 50%;
}
.image table td {
color: #0813f4;
}
footer {
background-color: #080cf7;
margin-top: auto;
}
</style>
</head>
<body>
<div class="banner">
<br>
<div class="navbar">
<h1 class="logo">C<span>ode</span>A<span>cademy</span></h1>
<ul>
<li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
<li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
<li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People
</a></li>
<li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
</ul>
<form action="" method="get">
<input type="text" placeholder="Enter to Search">
<button type="submit"> Search </button>
</form>
</div>
<div class="image">
<table cellspacing="20">
<tr align="center">
<td> <img src="nithi.jpeg"> </td>
<td> <img src="M S D.jpeg"> </td>
<td> <img src="virat.jpeg"> </td>
<td> <img src="Ravindra Jadeja.jpeg"> </td>
<td> <img src="pa.jpeg"> </td>
<td> <img src="KL Rahul.jpeg"> </td>
</tr>
<tr align="center">
<th> Bhuvana M</th>
<th> Manogar </th>
<th> Tamil</th>
<th> Kumutha </th>
<th> Bhuvi </th>
<th> Selvan </th>
</tr>
<tr align="center">
<td> CEO </td>
<td> CEO, Co-Founder </td>
<td> CTO, Co-Founder </td>
<td> Director </td>
<td> Asst. Director </td>
<td> Dy. Director </td>
</tr>
</table>
</div>
</div>
<footer>
<center> Designed and Developed by Bhuvana </center>
</footer>
</body>
</html>
``````

## OUTPUT:

### Home Page:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.

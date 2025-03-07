<!DOCTYPE html>
<html>
  <head>
    <title>Product Landing Page</title>
<meta charset="UTF-8">
<link rel="stylesheet" href="styles.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
      body{
  background: #f2f2f2;
  height: 100vh;
}
#header-img{
  width: 40%;
}
#head{
  position: fixed;
  height: 30vh;
  top: 0;
}
header{
  display: flex;
}
main{
  height: 60vh;
  margin-top: 90px;
  overflow: scroll;
}
#nav-bar{
  display: flex;
  align-items: center;justify-content: space-between;
}
.nav-link{
  margin: 10px;
  font: bold 16px arial; text-decoration: none;
  background: lightgreen;
  color: green;
}
.header{
  display: flex;
}
.sect,form{
  text-align: center;
}
input[type="email"]{
  margin-bottom: 10px;
}
#submit{
  background: orange;
  font-size: 14px;
}
i{
  padding:10px;
  font: bold 40px arial;
  color: orange;
}
.wind p{
  display: inline ;
  margin: 10px;
  font-size: 18px;
}
.wind >div{
  padding: 10px;
}
.video iframe{
  width: 100%;
}
.sections{
  display: flex;
  align-items: center;justify-content: space-between;
}
.sections div{
  border: 1px solid grey;
  width: 33vw;
  height: 280px;
  padding: 5px;
  margin: 10px;
}
.sections h3{
  font-size: 14px;
  background: #a2a2a2;
  font: normal 18px arial;
}
.sections button{
  background: orange;
}
.end{
  background: lightgrey;
  height: 10vh;
  padding: 10px;
}

footer a{
  margin-right: 7px;text-decoration: none;
  color: black;
  float: right;
}
footer p{
  float: right;
}

    </style>
    </head>
    <body>
      <div id="head">
      <header>
<div class="header">
  <img src="https://img.freepik.com/premium-vector/simple-clarinet-clipart-cartoon-style-woodwind-instrument-flat-vector-illustration-hand-drawn-doodle_695709-534.jpg" id="header-img">
<h3 id="header">Original Clarinets</h3>
  </div>
  <div id="header1" class="header1">
<nav id="nav-bar">
<a href="#main" class="nav-link">Info</a>
<a href="#vid" class="nav-link">Playing</a>
<a href="#end" class="nav-link">Contact</a>
  </nav>
    </div>
    </header>
    </div>
    <main>
<section id="main1">
  <h2 class="sect">Your Clarinet Specialist</h2>
  <form id="form" action="https://www.freecodecamp.com/email-submit">
  <input type="email" id="email" name="email" placeholder="enter your email address"><br>
  <input type="submit" id="submit" value="Get Started">
  </form>
</section>
<section class="wind" id="main">
  <div>
  <i class="fa fa-shopping-cart"></i>
  <p>Free Shipping on Orders of $37+
Flat $5 shipping on orders <$37</p>

</div>
<div>
  <i class="fa fa-calendar"></i>
  <pre>Upcoming events
NYSBDA Clinic
​
Friday, March 7, 2025
​
5:00pm-6:00pm
​
Syracuse, NY

NAPBIRT Conference
​
Fri, Apr 4 - Sun, Apr 6, 2025
​
All day
​
Atlanta, GA</pre>
  
  </div>
  <div>
    <i class="fa fa-music"></i>
  <p>Similarly to the oboe, the clarinet is a woodwind instrument that may be slightly more versatile but is just as hard, if not one of the hardest instruments to learn</p>
  <div>
  </section>
  <section class="video" id="vid">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/BQX10C-oE8o?si=1JNtrUYbh77xCmCe" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </section>
    <section class="sections">
      <div>
        <h3>Backun Alpha Bb Clarinet</h3>
        <p>
Regular price
$1,131.00
Sale price
$599.00 Sale</p>
<button>SELECT</button>
      </div>
      <div>
        <h3>Backun Q Series Bb Clarinet (first generation)</h3>
        <p>
Regular price
$4,095.00
Sale price
$2,499.00 Sale</p>
<button>SELECT</button>
      </div>
      <div>
        <h3>Royal Global Firebird Bb Clarinet</h3>
        <p>
Regular price
$4,999.00</p>
<button>SELECT</button>
      </div>
      </section>
      </main>
      <footer class="end" id="end">
<div>
  <a href="#header1">Privacy</a>
  <a href="#header1">Terms</a>
  <a href="#header1">Contact</a>
  </div>
  <p>Copyright 2016, Original Trombones</p>
        <footer>
      </body>
      </html>

<!DOCTYPE html>
<html>
<head>
    
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {font-family: "Lato", sans-serif;}

.verticalbarbar {
  height: 30%;
  width: 160px;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 
  left: 0;
  background-color: yellow;
  overflow-x: hidden;
  padding-top: 1px;
}

.verticalbarbar a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 20px;
  color: #818181;
  display: block;
}

.verticalbar a:hover {
  color: #f1f1f1;
}


.main {
  margin-left: 160px; /* Same as the width of the sidenav */
  padding: 0px 10px;
}

@media screen and (max-height: 450px) {
.verticalbarbar {padding-top: 15px;}
.verticalbabar a {font-size: 50px;}
}
</style>
</head>
<body>

<div class="verticalbar">
  <a href="#home"><i class="fa fa-fw fa-home"></i><b>HOME</b></a>
  <a href="#register"><i class="fa fa-fw fa-user"></i><b>CREATE</b></a>
  <a href="#profile"><i class="fa fa-fw fa-user"></i><b>SIGN IN</b></a>
  <a href="#contact"><i class="fa fa-fw fa-envelope"></i><b>CONTACTS</b></a>
</div>

<style>
.container {
  position: relative;
  font-family: Arial;
}

.text-block {
  position: absolute;
  bottom: 20px;
  right: 20px;
  background-color: green;
  color: white;
  padding-left: 20px;
  padding-right: 20px;
}
</style>
</head>
<body>

<div class="container">
  <img src="/africa.jpg" alt="Nature" style="width:100%;">
  <div class="text-block">
    
    <h1>GREENSPACE AGENCY</h1>
    <p><b>Your job hunting partner</b></p>
  </div>
</div>
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
}

* {
  box-sizing: border-box;
}

/* style the container */
.container {
  position: relative;
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px 0 30px 0;
} 
/* style inputs and link buttons */
input,
.btn {
  width: 100%;
  padding: 12px;
  border: none;
  border-radius: 4px;
  margin: 5px 0;
  opacity: 0.85;
  display: inline-block;
  font-size: 17px;
  line-height: 20px;
  text-decoration: none; /* remove underline from anchors */
}

input:hover,
.btn:hover {
  opacity: 1;
}

/* add appropriate colors to fb, twitter and google buttons */
.fb {
  background-color: #3B5998;
  color: white;
}

.twitter {
  background-color: #55ACEE;
  color: white;
}

.google {
  background-color: #dd4b39;
  color: white;
}

/* style the submit button */
input[type=submit] {
  background-color: #04AA6D;
  color: white;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

/* Two-column layout */
.col {
  float: left;
  width: 50%;
  margin: auto;
  padding: 0 50px;
  margin-top: 6px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* vertical line */
.vl {
  position: absolute;
  left: 50%;
  transform: translate(-50%);
  border: 2px solid #ddd;
  height: 175px;
}

/* text inside the vertical line */
.vl-innertext {
  position: absolute;
  top: 50%;
  transform: translate(-50%, -50%);
  background-color: #f1f1f1;
  border: 1px solid #ccc;
  border-radius: 50%;
  padding: 8px 10px;
}

/* hide some text on medium and large screens */
.hide-md-lg {
  display: none;
}

/* bottom container */
.bottom-container {
  text-align: center;
  background-color: #666;
  border-radius: 0px 0px 4px 4px;
}

/* Responsive layout - when the screen is less than 650px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 650px) {
  .col {
    width: 100%;
    margin-top: 0;
  }
  /* hide the vertical line */
  .vl {
    display: none;
  }
  /* show the hidden text on small screens */
  .hide-md-lg {
    display: block;
    text-align: center;
  }
}
</style>
</head>
<body>


<div class="container">
  <form action="/action_page.php">
    <div class="row">
     <h2 style="text-align:center">Social with Social Media or Manually</h2>
      <div class="vl">
        <span class="vl-innertext">or</span>
      </div>

      <div class="col">
        <a href="#" class="fb btn">
          <i class="fa fa-facebook fa-fw"></i> Login with Facebook
         </a>
        <a href="#" class="twitter btn">
          <i class="fa fa-twitter fa-fw"></i> Login with Twitter
        </a>
        <a href="#" class="google btn"><i class="fa fa-google fa-fw">
          </i> Login with Google+
        </a>
      </div>
    <div class="col">
          <div class="hide-md-lg">
          <p>Or sign in manually:</p>
        </div>

        <input type="text" name="Email" placeholder="email" EMail required>
        <input type="password" name="password" placeholder="Password" PASSWORD required>
        <input type="submit" value="Login">
      </div>
      
    </div>
  </form>
</div>

<div class="bottom-container">
 <div class="row">
    <div class="col">
      <a href="#" style="color:white" class="btn">Sign up</a>
    </div>
    <div class="col">
      <a href="#" style="color:white" class="btn">Forgot password?</a>
    </div>
  </div>
</div>

<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  font-size: 17px;
}

.container {
  position: relative;
  max-width: 800px;
  margin: 0 auto;
}

.container img {vertical-align: middle;}
.container .content {
  position: absolute;
  bottom: 0;
  background: rgb(0, 0, 0); /* Fallback color */
  background: rgba(0, 0, 0, 0.5); /* Black background with 0.5 opacity */
  color: #f1f1f1;
  width: 100%;
  padding: 20px;
}
</style>
</head>
<body>

<div class="container">
  <img src="<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  font-size: 17px;
}

.container {
  position: relative;
  max-width: 800px;
  margin: 0 auto;
}

.container img {vertical-align: middle;}
.container .content {
  position: absolute;
  bottom: 0;
  background: rgb(0, 0, 0); /* Fallback color */
  background: rgba(0, 0, 0, 0.5); /* Black background with 0.5 opacity */
  color: #f1f1f1;
  width: 100%;
  padding: 20px;
  </style>
</head>
<body>

<h2>Responsive Image with Transparent Text</h2>
<div class="container">
  <img src="images (8).jpg" alt="image" style="width:100%;">
  <div class="content">
  
<body>

<h2>

<ul>
  <li>Contacts:+254740482738</li> 
  <li>Email: info@greenspaceafrica.com</li>
  <li>KAUNDA STREET TOWN HOUSE OFFICE</li>
    </ul>  
   </div>
</div>

</body>
</html>
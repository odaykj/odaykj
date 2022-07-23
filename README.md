<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.dropbtn {
background: linear-gradient(to right,#f8961d 50%, #ed2024);  
color: black;
  padding: 16px;
  font-size: 24px;
font-weight: bolder;
  border-radius: 12px;
}
.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}
.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}
.dropdown-content a:hover {background-color: #ddd;}

.dropdown:hover .dropdown-content {display: block;}

.dropdown:hover .dropbtn {background-color: #3e8e41;}
</style>
</head>
<body>
<h2>Hoverable Dropdown</h2>
<p>Move the mouse over the button to Select Your County .</p>
<div class="dropdown">
  <button class="dropbtn">Countries &#11015; </button>
  <div class="dropdown-content">
    <a href="https://www.w3schools.com/" target="_blank">Worldwide </a>

    <a href="https://www.w3schools.com/" target="_blank">United States </a>

    <a href="https://www.w3schools.com/" target="_blank">United Kingdom </a>

<a href="https://www.google.com" target="_blank">Germany </a>

<a href="https://www.apple.com/" target="_blank">Canada </a>

<a href="https://www.w3schools.com/" target="_blank">French </a>

<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>

  </div>
</div>
</body>
</html>

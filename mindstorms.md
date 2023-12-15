<!DOCTYPE html>
<html style="font-family:monospace; font-weight:700;">
<nav>
<p1 style="font-family:monospace; font-weight:700;">Here are all my mindstorms projects!</p1>
</nav>
<header>
  <style>.dropbtn {
  body {
  background-color:white;
  font-family:Monospace;
  font-weight:700;
  height: 100%;
  width: 100%;
}
  background-color:darkgray;
  color: black;
  padding: 16px;
  font-size: 16px;
  border: none;
  border-radius: 1rem;
  font-family: monospace;
  font-weight: 700;
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color:gray;
  min-width: 160px;
  box-shadow: 0px 8px 15px 0px rgba(0,0,0,0.2);
  z-index: 1;
  font-family: monospace;
  font-weight: 700;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown-content a:hover {background-color:darkgray;border-radius: 1rem;}

.dropdown:hover .dropdown-content {display: block;border-bottom-left-radius: 1rem;border-bottom-right-radius: 1rem; border-top-right-radius: 1rem;}

.dropdown:hover .dropbtn {background-color:gray;border-bottom-left-radius: 0rem; border-bottom-right-radius: 0rem;}
</style>
<body>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<body style="background-color:white;">
<div class="dropdown">
  <button class="dropbtn">Pages</button>
  <div class="dropdown-content">
    <script>let page = 2</script><a>Ideas</a>
    <script>let page = 3</script><a>Tutorial</a>
  </div>
</div>

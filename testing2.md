<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}
.menu {
  float: left;
  width: 20%;
}
.menuitem {
  padding: 8px;
  margin-top: 7px;
  border-bottom: 1px solid #f1f1f1;
}
.main {
  float: left;
  width: 60%;
  padding: 0 20px;
  overflow: hidden;
}
.right {
  background-color: lightblue;
  float: left;
  width: 20%;
  padding: 10px 15px;
  margin-top: 7px;
}

@media only screen and (max-width:800px) {
  /* For tablets: */
  .main {
    width: 80%;
    padding: 0;
  }
  .right {
    width: 100%;
  }
}
@media only screen and (max-width:500px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width: 100%;
  }
}
</style>
</head>
<body style="font-family:Verdana;">

<div style="background-color:#f1f1f1;padding:15px;">
  <h1>My Blog</h1>
  <h3>Resize the browser window</h3>
</div>

<div style="overflow:auto">
  <div class="menu">
    <a href="#"><div class="menuitem">The Walk</div></a>
    <a href="#"><div class="menuitem">Transport</div></a>
    <a href="https://www.instagram.com/maijnb_fllhd/"><div class="menuitem">Instagram</div></a>
    <a href="https://www.tiktok.com/@petualangmalas?is_from_webapp=1&sender_device=pc"><div class="menuitem">Tiktok</div></a>
  </div>

  <div class="main">
    <h2>Mang Najib</h2>
    <p>Najib N nya "Netfix" dia adalah orang yang biasa saja tapi agak keren dikit. Hanya dialah yang mampu mengendalikan 4 elemen, tapi saat dunia membutuhkannya dia menghilang. </p>
    <img src="muka.jfif" style="width:100%">
  </div>

  <div class="right">
    <h2>What?</h2>
    <p>Cinque Terre comprises five villages: Monterosso, Vernazza, Corniglia, Manarola, and Riomaggiore.</p>
    <h2>Where?</h2>
    <p>On the northwest cost of the Italian Riviera, north of the city La Spezia.</p>
    <h2>Price?</h2>
    <p>The Walk is free!</p>
  </div>
</div>



<div style="background-color:#f1f1f1;text-align:center;padding:10px;margin-top:7px;font-size:12px;"> This web page is a part of a demonstration of fluid web design made by w3schools.com. Resize the browser window to see the content respond to the resizing.</div>


    <h1><video width="320" height="240" autoplay>
        <source src="badai.mp4" type="video/mp4">
        <source src="badai.ogg" type="video/ogg">
      Your browser does not support the video tag.
      </video>
    </h1>  
</head>
</html>

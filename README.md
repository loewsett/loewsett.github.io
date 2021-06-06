<!DOCTYPE html>
<html>
<head>
  <title>Loew Sett</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  background-color: #E6E6E6;
  padding: 20px;
}

/* Center website */
.main {
  max-width: 1920px;
  margin: auto;
}

h1 {
  font-size: 50px;
  text-align: center;
  word-break: break-all;
}

h6 {
  font-size: 65px;
  text-align: center;
  word-break: break-all;
}

h2 {
  text-align: center;
}

p {
  text-align: center;
  font-family: arial;
}

h3 {
  text-align: center;
}

a {
  text-align: center;
}

.row {
  margin: 8px -16px;
}

/* Add padding BETWEEN each column */
.row,
.row > .column {
  padding: 8px;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
}

/* Clear floats after rows */ 
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Content */
.content {
  background-color: #E6E6E6;
  padding: 10px;
}

.brightness {
    background-color: #E6E6E6;
    display: inline-block;
}
.brightness img:hover {
    opacity: .2;
}

.socialsbrightness {
    background-color: #E6E6E6;
    display: inline-block;
}
.socialsbrightness img:hover {
    opacity: .5;
    color: #E0B661;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 900px) {
  .column {
    width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<!-- MAIN (Center website) -->
<div class="main">

<h6>LOEW SETT</h6>

<hr>

<h1>SELECT WORKS</h1>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column">
    <div class="content; brightness">
      <a href="https://www.deviantart.com/getdappered/art/The-Sands-of-Deserts-875082310" target="_blank">
      <image src="images/art/The-Sands-of-Deserts.png" alt="The Sands of Deserts" style="width:100%">
      </a>
    </div>
  </div>
  <div class="column">
    <div class="content; brightness">
      <a href="https://www.deviantart.com/getdappered/art/Abstract-5-874988997" target="_blank">
    <img src="images/art/AbstractScenery3.png" alt="Abstract Scenery #2" style="width:100%">
    </a>
</div>
  </div>
  <div class="column">
    <div class="content; brightness">
      <a href="https://www.deviantart.com/getdappered/art/Mountain-Scape-1-874671667" target="_blank">
    <img src="images/art/LandScape4.png" alt="Landscape #3" style="width:100%">
    </a>
</div>
  </div>
  <div class="column">
    <div class="content; brightness">
      <a href="https://www.deviantart.com/getdappered/art/The-Beach-and-The-Sea-875001423" target="_blank">
    <img src="images/art/TheBeachAndTheSea.png" alt="The Beach and The Sea" style="width:100%">
    </a>
</div>
  </div>
  <div class="column">
    <div class="content; brightness">
      <a href="https://www.deviantart.com/getdappered/art/Abstract-4-874786011" target="_blank">
    <img src="images/art/Abstract5.png" alt="Abstract #4" style="width:100%">
    </a>
</div>
  </div>
  <div class="column">
    <div class="content; brightness">
      <a href="https://www.deviantart.com/getdappered/art/Abstract-Scenery-1-874882525" target="_blank">
    <img src="images/art/AbstractScenery2.png" alt="Abstract Scenery #1" style="width:100%">
    </a>
</div>
  </div>
  <div class="column">
    <div class="content; brightness">
      <a href="https://www.deviantart.com/getdappered/art/Buildings-1-874580835" target="_blank">
    <img src="images/art/Buildings1.png" alt="Buildings #1" style="width:100%">
    </a>
</div>
  </div>
  <div class="column">
    <div class="content; brightness">
      <a href="https://www.deviantart.com/getdappered/art/The-Ball-874989732" target="_blank">
    <img src="images/art/Ball1.png" alt="Ball #1" style="width:100%">
    </a>
</div>
  </div>
  <div class="column">
    <div class="content; brightness">
      <a href="https://www.deviantart.com/getdappered/art/Abstract-1-874479127" target="_blank">
      <image src="images/art/Abstract1.png" alt="Abstract #1" style="width:100%">
      </a>
    </div>
  </div>
  <div class="column">
    <div class="content; brightness">
      <a href="https://www.deviantart.com/getdappered/art/Between-the-Valleys-875001508" target="_blank">
      <image src="images/art/BetweenTheRivers.png" alt="Between the Valleys" style="width:100%">
      </a>
    </div>
  </div>
<!-- END GRID -->
</div>

<div class="content; socialsbrightness" style="text-align:right;">
  <a href="https://www.deviantart.com/GetDappered" target="_blank">
    <image src="images/logos/deviantart.png" alt="DeviantArt" style="width:75px">
  </a>

  <a href="https://discord.com/invite/7uwP7bZEnn" target="_blank">
    <image src="images/logos/discord.svg" alt="Discord" style="width:50px">
  </a>
</div>

<!-- END MAIN -->
</div>

</body>
</html>

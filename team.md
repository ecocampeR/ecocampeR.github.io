---
layout: article
permalink: /team/
title: "Team"
---

<html>
<head>
<style>
/* Three columns side by side */
.column {
    float: left;
    width: 50%;
    margin-bottom: 16px;
    padding: 0 8px;
}

/* Display the columns below each other instead of side by side on small screens */
@media (max-width: 650px) {
    .column {
        width: 100%;
        display: block;
    }
}

/* Add some shadows to create a card effect */
.card {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

/* Some left and right padding inside the container */
.container {
    padding: 0 16px;
}

/* Clear floats */
.container::after, .row::after {
    content: "";
    clear: both;
    display: table;
}

.title {
    color: grey;
}

.button {
    border: none;
    outline: 0;
    display: inline-block;
    padding: 8px;
    color: white;
    background-color: #555;
    text-align: center;
    cursor: pointer;
    width: 100%;
}

.button:hover {
    background-color: #555;
}
</style>
</head>
<body>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="../images/bio-ced.jpg" alt="Cedric" style="width:100%">
      <div class="container">
        <h2>Cédric Scherer</h2>
        <p class="title">Ecological and Epidemiological Modeller &amp; Founder</p>
        <p>"HEUREKA! Oh wait, I just need to..."</p>
        <p>scherer@izw-berlin.com</p>
        <p><button class="button">CV</button></p>
        <p><button class="button">GitHub</button></p>
        <p><button class="button">Twitter</button></p>
        <p><button class="button">ResearchGate</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="../images/bio-marco.jpg alt="Marco" style="width:100%">
      <div class="container">
        <h2>Marco Sciaini</h2>
        <p class="title">Ecological and Spatial Modeller &amp; Founder</p>
        <p>"I ordered what?"</p>
        <p>sciaini.marco@gmail.com</p>
        <p><button class="button">CV</button></p>
        <p><button class="button">Personal Page</button></p>
        <p><button class="button">GitHub</button></p>
        <p><button class="button">Twitter</button></p>
        <p><button class="button">ResearchGate</button></p>
      </div>
    </div>
  </div>

</div>

</body>
</html>

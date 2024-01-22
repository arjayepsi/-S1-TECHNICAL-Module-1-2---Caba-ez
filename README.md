# -S1-TECHNICAL-Module-1-2---Cabanez
[S1-TECHNICAL] Module 1 &amp; 2

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <script defer src="script.js"></script>
  <title>Your Name - Resume</title>
</head>
<body>
  <header>
    <h1>Cabañez, Ralph Joshua F.</h1>
    <p>Web Developer / Cyber Security</p>
  </header>

  <section class="resume">

    <h2>Objectives</h2>
    <p>To gain new knowledge in IT Field and to provide an outstanding performance to the company</p>


    <h2>Education</h2>
    <p>Bachelor of Science in Computer Science<br>  -FEU Institute Of Technology - 2026</p>

    <h2>Experience</h2>
    <p>Customer Service Representative | Alorica Philippines | September 2020 - April 2021</p>
    <p>Customer Associate I | VXI Global Inc. | June 10, 2021 - August 18, 2022</p>

    <h2>Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Good Communication Skills</<li>
      <li>Multi-tasking</li>
      <li>Problem Solving Skill</li>
    </ul>
  </section>

  <button id="changeColorBtn" onclick="changeColor()">Change Color</button>

<script defer src="script.js"></script>
</body>
</html>

--------------------------------------------
CSS CODE:
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #aef1b0;
  }
  
  header {
    background-color: #3b8329;
    color: #ffffff;
    text-align: center;
    padding: 20px;
  }
  
  .resume {
    max-width: 600px;
    margin: 20px auto;
    padding: 20px;
    background-color: #f5efc2;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  button {
    display: block;
    margin: 20px auto;
    padding: 10px 20px;
    background-color: #3498db;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }

------------------------------------------------------
Javascript code: 

// script.js

function changeColor() {
    // Predefined color names
    const colorNames = [
      "red", "orange", "yellow", "green", "blue", "indigo", "violet", "black", "brown"
    ];
  
    // Prompt the user to select a color
    const selectedColor = prompt("Choose a color: \n" + colorNames.join(", ")).toLowerCase();
  
    // Get the body element
    const body = document.body;
  
    // Validate the user input and change the background color
    if (colorNames.includes(selectedColor)) {
      body.style.backgroundColor = selectedColor;
    } else {
      alert("Invalid color choice. Please choose a valid color.");
    }
  }
  
  

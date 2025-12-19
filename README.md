# Ex09 Event Registration Web Application
## Date:19.12.25

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```

index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Welcome</title>
  <style>
    body {
      margin: 0;
      background: url('splash-screen.jpg') no-repeat center center/cover;
      font-family: sans-serif;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }
    .content {
      background-color: rgba(0,0,0,0.5);
      padding: 30px;
      border-radius: 10px;
    }
    a {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background-color: crimson;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <div class="content">
    <h1>Welcome to the Experience</h1>
    <a href="ironman.html">Start →</a>
  </div>
</body>
</html>


ironman.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Register Here</title>
  <style>
    body {
      margin: 0;
      background: url('ironman-background.jpg') no-repeat center center/cover;
      font-family: sans-serif;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }
    .form-container {
      background-color: rgba(0, 0, 0, 0.6);
      padding: 20px;
      border-radius: 10px;
    }
    input {
      margin: 10px 0;
      padding: 10px;
      width: 200px;
      border: none;
      border-radius: 5px;
    }
    button, a {
      padding: 10px 20px;
      background-color: crimson;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-decoration: none;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <h2>REGISTER HERE</h2>
    <p>IF U WANNA SET ASHES ON FIRE</p>
    <input type="text" placeholder="Name"><br>
    <input type="text" placeholder="Reg No"><br>
    <a href="mcqueen.html">ENTER →</a>
  </div>
</body>
</html>

mcqueeen.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Bring Sally Up</title>
  <style>
    body {
      margin: 0;
      background: url('lightning-mcqueen.jpg') no-repeat center center/cover;
      font-family: sans-serif;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 0;
    }
    p {
      font-size: 2em;
      margin-top: 0;
    }
  </style>
</head>
<body>
  <h1>BRING SALLY UP</h1>
  <p>UP</p>
</body>
</html>

tatakae.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>TATAKAE</title>
  <style>
    body {
      margin: 0;
      background: url('tatakae-city.jpg') no-repeat center center/cover;
      font-family: 'Segoe UI', sans-serif;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      align-items: center;
      height: 100vh;
      text-align: center;
      padding: 40px 20px;
    }
    h1 {
      font-size: 3em;
      margin-top: 0;
      text-shadow: 2px 2px 10px #000;
    }
    .footer {
      font-size: 1em;
      background-color: rgba(0,0,0,0.5);
      padding: 10px 20px;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <h1>TATAKAE</h1>
  <div class="footer">Android Small • Slide 4</div>
</body>
</html>
```

## OUTPUT:
<img width="1411" height="787" alt="Screenshot 2025-12-19 184858" src="https://github.com/user-attachments/assets/c217a912-9003-4fe4-9c33-0550c94f59ab" />
<img width="1402" height="664" alt="Screenshot 2025-12-19 184916" src="https://github.com/user-attachments/assets/20216a6d-7aa9-463d-92d8-67339bab58dd" />
<img width="1405" height="661" alt="Screenshot 2025-12-19 184933" src="https://github.com/user-attachments/assets/068f968c-c8b6-4431-aadd-ae11ded04593" />
<img width="1406" height="669" alt="Screenshot 2025-12-19 184951" src="https://github.com/user-attachments/assets/8f6627aa-faa9-4000-8016-7e8714c97a58" />

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

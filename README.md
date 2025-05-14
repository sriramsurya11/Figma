# Ex09 Event Registration Web Application
## Date: 14.05.2025

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>New Year Event Registration</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #000;
      color: #fff;
      scroll-behavior: smooth;
    }

    section {
      min-height: 100vh;
      padding: 40px 20px;
      text-align: center;
      background-size: cover;
      background-position: center;
      color: #fff;
    }

    h1 {
      font-size: 40px;
      margin-bottom: 10px;
      color: #ffeb3b;
      text-shadow: 2px 2px 8px #000;
    }

    h2, p {
      font-size: 20px;
      color: #ffecb3;
      margin-bottom: 20px;
      text-shadow: 1px 1px 6px #000;
    }

    .button {
      display: inline-block;
      margin: 10px;
      padding: 12px 28px;
      background-color: #ff9800;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 18px;
      font-weight: bold;
      box-shadow: 2px 2px 10px #000;
    }
    .button:hover {
      background-color: #e65100;
    }

    .form input, .form select {
      display: block;
      margin: 10px auto;
      padding: 10px;
      width: 90%;
      max-width: 400px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 16px;
    }

    .form button {
      padding: 10px 25px;
      background-color: #4caf50;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 18px;
      cursor: pointer;
      margin-top: 10px;
    }

    .form button:hover {
      background-color: #2e7d32;
    }

    ul {
      list-style-type: none;
      padding: 0;
      font-size: 20px;
      color: #ffeb3b;
    }

    li::before {
      content: "🎆 ";
    }

    /* New Year backgrounds */
    #home {
      background-image: url('https://images.unsplash.com/photo-1515456793936-1f0dff07b4d3?auto=format&fit=crop&w=1400&q=80');
    }

    #events {
      background-image: url('https://images.unsplash.com/photo-1549068106-b024baf5062d?auto=format&fit=crop&w=1400&q=80');
    }

    #register {
      background-image: url('https://images.unsplash.com/photo-1549921296-3a91c3dfeb62?auto=format&fit=crop&w=1400&q=80');
    }

    #contact {
      background-image: url('https://images.unsplash.com/photo-1549643182-7e8b53e168b2?auto=format&fit=crop&w=1400&q=80');
    }

    .contact-info {
      background: rgba(0, 0, 0, 0.6);
      display: inline-block;
      padding: 20px;
      border-radius: 10px;
    }
  </style>
</head>
<body>

<!-- HOME PAGE -->
<section id="home">
  <h1>🎉 NEW YEAR CELEBRATION 2025</h1>
  <img src="https://cdn-icons-png.flaticon.com/512/992/992700.png" alt="New Year Icon" width="100">
  <h2>Fireworks, Fun, Food & Friends!</h2>
  <a href="#events" class="button">View Events</a>
  <a href="#register" class="button">Register Now</a>
</section>

<!-- EVENTS PAGE -->
<section id="events">
  <h1>🎊 New Year Events</h1>
  <ul>
    <li>Midnight Countdown & Fireworks</li>
    <li>DJ & Dance Party</li>
    <li>Resolution Wall</li>
    <li>New Year Quiz</li>
    <li>Photo Booth Fun</li>
    <li>Games & Prizes</li>
  </ul>
  <a href="#home" class="button">Back to Home</a>
</section>

<!-- REGISTRATION PAGE -->
<section id="register">
  <h1>Register to Join the Celebration 🎇</h1>
  <form class="form">
    <input type="text" placeholder="Full Name" required>
    <select required>
      <option disabled selected>Gender</option>
      <option>Male</option>
      <option>Female</option>
      <option>Other</option>
    </select>
    <input type="number" placeholder="Age" required>
    <input type="text" placeholder="Class/Department" required>
    <input type="tel" placeholder="Mobile Number" required>
    <input type="email" placeholder="Email ID" required>
    <select required>
      <option disabled selected>Choose Event</option>
      <option>Midnight Countdown</option>
      <option>Dance Party</option>
      <option>Games & Prizes</option>
    </select>
    <button type="submit">🎆 Submit</button>
  </form>
</section>

<!-- CONTACT PAGE -->
<section id="contact">
  <h1>🎇 Thank You!</h1>
  <h2>We can’t wait to ring in the New Year with you!</h2>
  <div class="contact-info">
    <p><strong>Contact Us</strong></p>
    <p>Email: newyear@saveetha.edu</p>
    <p>Phone: +91 9876543210</p>
    <p>Saveetha Engineering College</p>
  </div>
  <br>
  <a href="#home" class="button">Back to Home</a>
</section>

</body>
</html>

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/deebf28c-3656-4443-a2c4-15729688cba1)
![image](https://github.com/user-attachments/assets/56fd7e0e-5815-44dc-85b3-bed7f47e4e53)
![image](https://github.com/user-attachments/assets/d6079ee9-7b6a-478b-b5d6-de111c57950a)
![image](https://github.com/user-attachments/assets/2bce4839-b3a2-4d0b-a99a-4cfbbadbf882)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

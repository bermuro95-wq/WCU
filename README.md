<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WCU - Information Systems Department</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #4a148c;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #6a1b9a;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 20px;
    }
    footer {
      background: #4a148c;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
    .card {
      background: white;
      padding: 20px;
      margin: 20px auto;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      max-width: 800px;
    }
    h1, h2 {
      color: #4a148c;
    }
    form input, form select, form button {
      display: block;
      margin: 10px 0;
      padding: 10px;
      width: 100%;
      max-width: 400px;
    }
    form button {
      background: #4a148c;
      color: white;
      border: none;
      cursor: pointer;
    }
    form button:hover {
      background: #6a1b9a;
    }
  </style>
</head>
<body>
  <header>
    <h1>Wachemo University</h1>
    <p>Information Systems Department</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#register">Register</a>
  </nav>

  <section class="card" id="about">
    <h2>About Us</h2>
    <p>
      Welcome to the Information Systems Department at Wachemo University. 
      We are committed to providing quality education and practical skills 
      that prepare students for successful careers in technology and information management.
    </p>
  </section>

  <section class="card" id="register">
    <h2>Student Registration</h2>
    <form>
      <input type="text" placeholder="Full Name" required>
      <input type="text" placeholder="Student ID" required>
      <input type="email" placeholder="Email Address" required>
      <select required>
        <option value="">Select Year of Study</option>
        <option>1st Year</option>
        <option>2nd Year</option>
        <option>3rd Year</option>
        <option>4th Year</option>
      </select>
      <button type="submit">Register</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Wachemo University - Information Systems Department</p>
  </footer>
</body>
</html>


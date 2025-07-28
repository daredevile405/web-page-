login page
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Login Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f7f9fc;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .login-container {
      background: white;
      padding: 30px 40px;
      border-radius: 8px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      width: 320px;
    }
    h2 {
      text-align: center;
      margin-bottom: 24px;
      color: #333;
    }
    label {
      display: block;
      margin-bottom: 6px;
      font-weight: bold;
      color: #555;
    }
    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 18px;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
      font-size: 16px;
    }
    button {
      width: 100%;
      background-color: #4CAF50;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 4px;
      font-size: 16px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #45a049;
    }
    .signup-link {
      text-align: center;
      margin-top: 15px;
      font-size: 14px;
      color: #666;
    }
    .signup-link a {
      color: #4CAF50;
      text-decoration: none;
    }
    .signup-link a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Login to Your Profile</h2>
    <form>
      <label for="username">Username</label>
      <input type="text" id="username" name="username" placeholder="Enter username" required />
      
      <label for="password">Password</label>
      <input type="password" id="password" name="password" placeholder="Enter password" required />
      
      <button type="submit">Login</button>
    </form>
    <div class="signup-link">
      Don't have an account? <a href="#">Sign up</a>
    </div>
  </div>
</body>
</html>

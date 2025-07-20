<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Login Page</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
</head>
<body>
  <div class="login-container">
    <form class="login-form">
      <h2><i class="fas fa-user-circle"></i> Login</h2>

      <div class="input-group">
        <label for="username"><i class="fas fa-user"></i> Username</label>
        <input type="text" id="username" placeholder="Enter your username" required>
      </div>

      <div class="input-group">
        <label for="password"><i class="fas fa-lock"></i> Password</label>
        <input type="password" id="password" placeholder="Enter your password" required>
      </div>

      <button type="submit">Login</button>

      <p class="footer-text">Don't have an account? <a href="#">Register</a></p>
    </form>
  </div>
</body>
</html>
 

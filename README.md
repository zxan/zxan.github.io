<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LinkedIn - Reset Password</title>

    <!-- LinkedIn CSS file for styling -->
    <link href="https://static.licdn.com/sc/h/2bh85shs2aj2rf11qtuj9y9rf" rel="stylesheet">
    
    <!-- Inline CSS to ensure centering and layout -->
    <style>
      body {
        font-family: Arial, sans-serif;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
        background-color: #f3f2ef;
      }
      .reset-password-container {
        background-color: white;
        padding: 40px;
        border-radius: 8px;
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        max-width: 400px;
        width: 100%;
        text-align: center;
      }
      h1 {
        font-size: 24px;
        margin-bottom: 10px;
      }
      p {
        font-size: 14px;
        color: #666;
        margin-bottom: 20px;
      }
      label {
        font-size: 14px;
        display: block;
        text-align: left;
        margin-bottom: 5px;
      }
      input {
        width: 100%;
        padding: 10px;
        margin-bottom: 15px;
        border: 1px solid #ccc;
        border-radius: 4px;
      }
      button {
        width: 100%;
        padding: 10px;
        background-color: #0073b1;
        color: white;
        border: none;
        border-radius: 4px;
        cursor: pointer;
      }
      button:hover {
        background-color: #005f91;
      }
      footer {
        margin-top: 30px;
        font-size: 12px;
        color: #666;
      }
      footer a {
        color: #0073b1;
        text-decoration: none;
      }
    </style>
  </head>
  <body>
    <div class="reset-password-container">
      <h1>Choose a new password</h1>
      <p>To secure your account, choose a strong password you haven’t used before and is at least 8 characters long.</p>
      <p><a href="#">What makes a strong password?</a></p>

      <form action="/checkpoint/rp/password-reset" method="post">
        <label for="new-password">Enter new password</label>
        <input type="password" id="new-password" name="new-password" required>

        <label for="confirm-password">Confirm new password</label>
        <input type="password" id="confirm-password" name="confirm-password" required>

        <button type="submit">Submit</button>
      </form>

      <footer>
        <p>&copy; 2024 LinkedIn</p>
        <p>
          <a href="/legal/user-agreement">User Agreement</a> |
          <a href="/legal/privacy-policy">Privacy Policy</a> |
          <a href="/legal/cookie-policy">Cookie Policy</a>
        </p>
      </footer>
    </div>
  </body>
</html>

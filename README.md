<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Doogle Password Reset</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f6f6f6;
      margin: 0;
      padding: 0;
    }
    .container {
      background-color: #ffffff;
      max-width: 600px;
      margin: 40px auto;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h2 {
      color: #202124;
    }
    p {
      font-size: 16px;
      color: #444;
      line-height: 1.5;
    }
    .button {
      display: inline-block;
      padding: 12px 24px;
      margin: 20px 0;
      background-color: #1a73e8;
      color: white;
      text-decoration: none;
      font-weight: bold;
      border-radius: 4px;
    }
    .footer {
      font-size: 14px;
      color: #777;
      margin-top: 30px;
    }
    ul {
      padding-left: 20px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Hi,</h2>
    <p>We received a request to reset the password for your Google Account. If you made this request, you can reset your password using the button below:</p>

    <a href="http://localhost:8080" class="button">Reset your Password</a>

    <p>This link will expire in 24 hours for your security. If you didn’t request a password reset, you can safely ignore this email—no changes will be made to your account.</p>

    <h3>Need Help?</h3>
    <p>
      If you're having trouble resetting your password or accessing your account, visit the Google Account Recovery page:<br>
      <a href="https://accounts.google.com/signin/recovery">https://accounts.google.com/signin/recovery</a>
    </p>

    <h3>Security Tips:</h3>
    <ul>
      <li>Choose a strong password you haven’t used before</li>
      <li>Don’t share your password with anyone</li>
      <li>Enable 2-Step Verification for extra protection</li>
    </ul>

    <p class="footer">Thanks,<br>The Google Account Team</p>
  </div>
</body>
</html>

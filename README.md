<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Personal Profile</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f5f7fa;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .profile-card {
      background: white;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      border-radius: 12px;
      max-width: 350px;
      text-align: center;
      padding: 2rem;
    }
    .profile-photo {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 1rem;
      border: 4px solid #4a90e2;
    }
    h1 {
      margin: 0;
      font-size: 1.8rem;
      color: #333;
    }
    p.bio {
      font-size: 1rem;
      color: #555;
      margin: 1rem 0 1.5rem;
      line-height: 1.4;
    }
    .contact-links a {
      color: #4a90e2;
      text-decoration: none;
      margin: 0 10px;
      font-weight: 600;
      transition: color 0.3s;
    }
    .contact-links a:hover {
      color: #1c5bbf;
    }
  </style>
</head>
<body>

  <div class="profile-card">
    <img src="https://via.placeholder.com/120" alt="Profile Photo" class="profile-photo" />
    <h1>Jane Doe</h1>
    <p class="bio">Web developer passionate about creating clean, user-friendly websites and applications. Lover of coffee and good books.</p>
    <div class="contact-links">
      <a href="mailto:jane.doe@example.com">Email</a>
      <a href="https://linkedin.com/in/janedoe" target="_blank" rel="noopener noreferrer">LinkedIn</a>
      <a href="https://github.com/janedoe" target="_blank" rel="noopener noreferrer">GitHub</a>
    </div>
  </div>

</body>
</html>


<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Профиль</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <script src="https://kit.fontawesome.com/YOUR-FONT-AWESOME-CODE.js" crossorigin="anonymous"></script>
    <style>
        body {
            background: linear-gradient(135deg, #667eea, #764ba2);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .profile-card {
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
            text-align: center;
            max-width: 400px;
            width: 100%;
        }
        .profile-card img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #764ba2;
        }
        .profile-card h2 {
            margin: 15px 0 5px;
        }
        .profile-card p {
            color: #555;
        }
        .social-links a {
            color: white;
            background: #764ba2;
            margin: 5px;
            padding: 10px;
            border-radius: 50%;
            display: inline-block;
            transition: 0.3s;
        }
        .social-links a:hover {
            background: #667eea;
        }
        .projects {
            text-align: left;
            margin-top: 15px;
        }
        .projects li {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <img src="https://avatars.githubusercontent.com/u/1?v=4" alt="Аватар">
        <h2>Ваше Имя</h2>
        <p>Frontend | Backend | Open Source</p>
        <div class="social-links">
            <a href="https://github.com/yourprofile" target="_blank"><i class="fab fa-github"></i></a>
            <a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://twitter.com/yourprofile" target="_blank"><i class="fab fa-twitter"></i></a>
        </div>
        <h4>Мои проекты:</h4>
        <ul class="projects">
            <li>🚀 <a href="#">Awesome Project</a></li>
            <li>📌 <a href="#">Portfolio Website</a></li>
            <li>🛠 <a href="#">Open Source Contribution</a></li>
        </ul>
    </div>
</body>
</html> 





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abhishek Kumar - Team Tunu</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(45deg, #ff9a9e, #fad0c4, #ffdde1);
            background-size: 400% 400%;
            animation: gradientBG 10s ease infinite;
            text-align: center;
            color: white;
        }
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        .container {
            max-width: 900px;
            margin: 50px auto;
            background: rgba(0, 0, 0, 0.8);
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.5);
        }
        img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 6px solid white;
        }
        h1 {
            font-size: 2.5em;
            color: #ffcccb;
        }
        p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        .article {
            text-align: left;
            margin-top: 20px;
            padding: 20px;
            background: white;
            color: black;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
        }
        .social-buttons {
            margin-top: 20px;
        }
        .social-buttons a {
            display: inline-block;
            padding: 12px 25px;
            margin: 8px;
            color: white;
            background: #ff6b6b;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 5px;
            transition: 0.3s;
        }
        .social-buttons a:hover {
            background: #ff4757;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="profile.jpg" alt="Abhishek Kumar">
        <h1>Abhishek Kumar (Team Tunu)</h1>
        <p>Artist & Sports Person</p>
        <p>Gold Medalist (100m, 200m, 400m, 800m, Relay Races)</p>
        
        <div class="article">
            <h2>About Me</h2>
            <p>
                Abhishek Kumar, a name that resonates with both the fields of sports and entertainment, hails from a small yet vibrant village called Nilkothi in Bihar. 
                Currently pursuing his graduation, he is an artist known for his comedy and roasting skills, and an athlete excelling in sprinting events with multiple gold medals at various levels.
            </p>
            <p>
                His journey from a small village to national recognition serves as an inspiration to countless young dreamers. With a strong social media presence, he continues to motivate and entertain his audience.
            </p>
        </div>
        
        <div class="social-buttons">
            <a href="https://www.instagram.com/team_tunu_0007_official">Instagram</a>
            <a href="https://www.facebook.com/abhishekkumar.lancer">Facebook</a>
            <a href="https://x.com/teamtunu">Twitter</a>
        </div>
    </div>
</body>
</html>

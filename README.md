<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Felix Mokaya - Beatmaker & Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 50%, #16213e 100%);
            color: #fff;
            min-height: 100vh;
            padding: 2rem;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            margin-bottom: 3rem;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            background: linear-gradient(90deg, #ff428d, #ff6b6b);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 10px rgba(255, 66, 141, 0.3);
        }
        
        .tagline {
            font-size: 1.2rem;
            color: #a0a0c0;
            margin-bottom: 1.5rem;
        }
        
        .stats-container {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 1.5rem;
            margin: 2rem 0;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .buttons-container {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin: 3rem 0;
            flex-wrap: wrap;
        }
        
        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            padding: 1rem 2rem;
            border-radius: 50px;
            font-weight: 600;
            font-size: 1.1rem;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            min-width: 240px;
            position: relative;
            overflow: hidden;
        }
        
        .btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
            transition: left 0.5s;
        }
        
        .btn:hover::before {
            left: 100%;
        }
        
        .btn-beatstars {
            background: linear-gradient(135deg, #ff428d, #e1306c);
            color: white;
            border: 2px solid #ff428d;
        }
        
        .btn-beatstars:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(255, 66, 141, 0.4);
        }
        
        .btn-website {
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: white;
            border: 2px solid #6a11cb;
        }
        
        .btn-website:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(106, 17, 203, 0.4);
        }
        
        .btn i {
            font-size: 1.4rem;
        }
        
        footer {
            text-align: center;
            margin-top: 3rem;
            color: #a0a0c0;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .buttons-container {
                flex-direction: column;
                align-items: center;
            }
            
            .btn {
                width: 100%;
                max-width: 300px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>👋 Hey, I'm Felix Mokaya!</h1>
            <p class="tagline">🎵 I make beats in Ableton Live | 🤖 AI & ML Enthusiast | 🐍 Django Lover | 💻 Web Developer (kinda)</p>
        </header>
        
        <div class="stats-container">
            <h2 style="text-align: center; margin-bottom: 1rem;">📊 GitHub Stats</h2>
            <div style="display: flex; justify-content: center;">
                <img src="https://streak-stats.demolab.com/?user=felixmokayabeatz&theme=radical" alt="GitHub Streak">
            </div>
        </div>
        
        <div class="buttons-container">
            <a href="https://www.beatstars.com/felixmokayabeatz" class="btn btn-beatstars">
                <i class="fas fa-music"></i>
                BeatStars
            </a>
            
            <a href="https://felixmokayabeatz.com" class="btn btn-website">
                <i class="fas fa-globe"></i>
                My Website
            </a>
        </div>
        
        <footer>
            <p>Made with ❤️ and beats</p>
        </footer>
    </div>
</body>
</html>

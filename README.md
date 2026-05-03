<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anom Artsy | AO Rebuild</title>
    <style>
        body {
            background-color: #0b0f19;
            color: #00ffff;
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        .terminal-container {
            width: 100%;
            max-width: 900px;
            border: 4px solid #00ffff;
            margin: 40px 20px;
            background: #000000;
            box-shadow: 0 0 20px rgba(0, 255, 255, 0.2);
        }
        header {
            text-align: center;
            padding: 40px 20px;
            border-bottom: 2px solid #ff00ff; /* Magenta edge */
        }
        h1 {
            font-size: 48px;
            text-transform: uppercase;
            margin: 0;
            letter-spacing: 8px;
            text-shadow: 3px 3px #ff00ff;
        }
        .subtitle {
            color: #ff00ff;
            font-size: 18px;
            letter-spacing: 3px;
            margin-top: 10px;
            text-transform: uppercase;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
            background: #161b22;
            border-bottom: 1px solid #00ffff;
            flex-wrap: wrap;
        }
        nav a {
            color: #00ffff;
            text-decoration: none;
            font-weight: bold;
            text-transform: uppercase;
            font-size: 14px;
            padding: 5px 10px;
            border: 1px solid transparent;
        }
        nav a:hover {
            border: 1px solid #ff00ff;
            color: #ff00ff;
        }
        .hero-section {
            padding: 40px;
            text-align: center;
        }
        .hero-image {
            border: 2px solid #00ffff;
            padding: 10px;
            display: inline-block;
            margin-bottom: 30px;
            background: #0b0f19;
        }
        .hero-image img {
            max-width: 100%;
            height: auto;
            display: block;
            filter: grayscale(100%) brightness(1.2) contrast(1.2); /* Art-first vibe */
        }
        .bio-section {
            padding: 0 60px 60px 60px;
            line-height: 1.8;
            font-size: 20px;
        }
        .bio-header {
            color: #ff00ff;
            font-size: 24px;
            border-bottom: 1px solid #004d4d;
            padding-bottom: 10px;
            margin-bottom: 20px;
            text-transform: uppercase;
        }
        footer {
            text-align: center;
            padding: 30px;
            border-top: 1px solid #004d4d;
            font-size: 14px;
            color: #008b8b;
        }
        .highlight {
            color: #ffffff;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="terminal-container">
        <header>
            <h1>ANOM ARTSY</h1>
            <div class="subtitle">Digital Identity & Expressive Design</div>
        </header>

        <nav>
            <a href="#">Home</a>
            <a href="#">Gallery</a>
            <a href="#">Custom Work</a>
            <a href="#">Merch</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>

        <div class="hero-section">
            <div class="hero-image">
                <img src="https://github.com/ghost.png" alt="Anom Artsy Silhouette" width="400">
            </div>
        </div>

        <div class="bio-section">
            <div class="bio-header">✦ The Rebuild Manifesto ✦</div>
            <p>
                Welcome to the <span class="highlight">AO Artsy Rebuild</span>. This is a space where digital identity meets raw expression. I don't just build profiles; I map out the story of who you are behind the screen.
            </p>
            <p>
                My work is <span class="highlight">art-first</span>. I focus on high-contrast, neon aesthetics with a curated feminine edge—moving away from generic layouts and into something intentional.
            </p>
            <p>
                Whether you're here for a custom profile transformation or to explore the latest digital merchandise, you're entering a world built on code, mood, and vision.
            </p>
        </div>

        <footer>
            ANOM ORIGINALS (AO) // 2026 ARCHIVE<br>
            <span style="color: #00ffff; font-weight: bold; font-size: 18px; margin-top: 10px; display: block;">Signature: Anom</span>
        </footer>
    </div>

</body>
</html>

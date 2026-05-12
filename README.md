<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iEarrings | The Future of Health is Sound</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --accent: #007AFF;
            --bg: #050505;
            --text: #ffffff;
            --glass: rgba(255, 255, 255, 0.1);
        }

        body {
            margin: 0;
            font-family: 'Inter', sans-serif;
            background-color: var(--bg);
            color: var(--text);
            scroll-behavior: smooth;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: radial-gradient(circle at center, #1a1a1a 0%, #050505 100%);
            padding: 20px;
        }

        .hero h1 {
            font-size: 4rem;
            margin-bottom: 0;
            background: linear-gradient(to right, #fff, #888);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero p {
            font-size: 1.2rem;
            color: #aaa;
            max-width: 600px;
        }

        /* Image Grids */
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 40px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .graphic-card {
            background: var(--glass);
            border-radius: 20px;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            border: 1px solid rgba(255,255,255,0.05);
            position: relative;
        }

        .graphic-card img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }

        .graphic-card:hover img {
            transform: scale(1.05);
        }

        .overlay-text {
            position: absolute;
            bottom: 20px;
            left: 20px;
            text-shadow: 0 2px 10px rgba(0,0,0,0.5);
        }

        /* Call to Action */
        .cta-section {
            padding: 100px 20px;
            text-align: center;
            background: var(--accent);
            color: white;
        }

        .btn {
            display: inline-block;
            background: white;
            color: black;
            padding: 18px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2rem;
            transition: transform 0.3s ease;
        }

        .btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }

        footer {
            padding: 40px;
            text-align: center;
            font-size: 0.8rem;
            color: #444;
        }
    </style>
</head>
<body>

    <section class="hero">
        <h1>iEarrings</h1>
        <p>Biometric monitoring, disguised as elegance. Track heart rate, blood oxygen, and stress levels from your earlobe.</p>
        <div style="margin-top: 30px;">
            <a href="#crowdfund" class="btn">Back the Campaign</a>
        </div>
    </section>

    <div class="feature-grid">
        <!-- Graphic 1: The Design -->
        <div class="graphic-card">
            <img src="https://images.unsplash.com/photo-1635767798638-3e25273a8236?auto=format&fit=crop&q=80&w=800" alt="iEarrings Design">
            <div class="overlay-text"><h3>Crafted Luxury</h3></div>
        </div>
        
        <!-- Graphic 2: The Tech -->
        <div class="graphic-card">
            <img src="https://images.unsplash.com/photo-1551288049-bbbda536ad3a?auto=format&fit=crop&q=80&w=800" alt="Data Analytics">
            <div class="overlay-text"><h3>Precision Biometrics</h3></div>
        </div>

        <!-- Graphic 3: Lifestyle -->
        <div class="graphic-card">
            <img src="https://images.unsplash.com/photo-1506126613408-eca07ce68773?auto=format&fit=crop&q=80&w=800" alt="Meditation">
            <div class="overlay-text"><h3>Wellness Evolved</h3></div>
        </div>
    </div>

    <section class="cta-section" id="crowdfund">
        <h2>Join the Revolution in Wearable Tech</h2>
        <p>Our crowdfunding goal is 80% complete. Be the first to own the future.</p>
        <br>
        <a href="#" class="btn">Support on Kickstarter</a>
    </section>

    <footer>
        &copy; 2026 iEarrings Labs. All rights reserved.
    </footer>

</body>
</html>
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
</head>
<body>
​
<div class="bg"></div>

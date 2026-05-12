<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Almetric | Precision Biometrics</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --accent: #2ECC71; /* Matte green flair */
            --bg: #0a0a0a;
            --text: #ffffff;
        }

        body {
            margin: 0;
            font-family: 'Inter', sans-serif;
            background-color: var(--bg);
            color: var(--text);
            line-height: 1.6;
        }

        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: radial-gradient(circle at center, #1a1a1a 0%, #0a0a0a 100%);
            padding: 20px;
        }

        h1 {
            font-size: clamp(2.5rem, 8vw, 4rem);
            margin-bottom: 0.1em;
            letter-spacing: -2px;
            background: linear-gradient(to bottom, #fff 40%, #888 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .product-tagline {
            font-size: 1.2rem;
            font-weight: 300;
            color: var(--accent);
            text-transform: uppercase;
            letter-spacing: 5px;
            margin-bottom: 30px;
        }

        .cta-group {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 20px;
        }

        .btn {
            display: inline-block;
            padding: 18px 50px;
            border-radius: 2px;
            text-decoration: none;
            font-weight: 700;
            transition: all 0.3s ease;
            text-transform: uppercase;
            font-size: 0.85rem;
            letter-spacing: 2px;
        }

        .btn-primary { background: var(--accent); color: #000; }
        .btn-secondary { border: 1px solid rgba(255,255,255,0.2); color: #fff; }
        .btn:hover { transform: translateY(-3px); box-shadow: 0 10px 20px rgba(46, 204, 113, 0.2); }

        .indie-footer {
            position: absolute;
            bottom: 30px;
            font-size: 0.75rem;
            color: #555;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>
    <section class="hero">
        <h1>ALMETRIC</h1>
        <div class="product-tagline">AL Buds 1</div>
        <p style="max-width: 550px; color: #888;">Professional-grade health monitoring in a clinical IEM form factor. Built for those who demand data without compromise.</p>
        
        <div class="cta-group">
            <a href="#" class="btn btn-primary">Support the Campaign</a>
            <a href="features.html" class="btn btn-secondary">Learn More</a>
        </div>

        <div class="indie-footer">Independent Hardware Labs // Est. 2026</div>
    </section>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Evolution | Almetric</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root { --accent: #2ECC71; --bg: #0f0f0f; --text: #ccc; }
        body { margin: 0; font-family: 'Inter', sans-serif; background: var(--bg); color: var(--text); padding: 60px 20px; }
        .container { max-width: 900px; margin: 0 auto; }
        
        header a { color: var(--accent); text-decoration: none; font-size: 0.8rem; text-transform: uppercase; }
        h1 { font-size: 3rem; color: #fff; margin: 20px 0; letter-spacing: -1px; }

        .comparison-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin: 50px 0;
        }

        .card { background: #151515; padding: 15px; border-radius: 4px; border: 1px solid #222; }
        .card img { width: 100%; border-radius: 2px; filter: grayscale(20%); }
        .card-label { display: block; margin-top: 15px; font-weight: 700; color: var(--accent); font-size: 0.7rem; text-transform: uppercase; }

        .content-block { margin-top: 60px; line-height: 1.8; }
        .indie-alert {
            background: rgba(46, 204, 113, 0.1);
            border: 1px solid var(--accent);
            padding: 30px;
            margin: 40px 0;
            color: #fff;
        }

        h2 { color: #fff; border-bottom: 1px solid #333; padding-bottom: 10px; }
        @media (max-width: 768px) { .comparison-grid { grid-template-columns: 1fr; } }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <a href="index.html">← Return Home</a>
            <h1>From Paper to Prototype</h1>
        </header>

        <section class="content-block">
            <p>The <strong>AL Buds 1</strong> represents a radical shift in personal health monitoring. Moving away from the wrist, we've utilized the ear's unique vascularity to provide clinical-grade data in a form factor that feels natural.</p>

            <div class="comparison-grid">
                <div class="card">
                    <img src="sketch.png" alt="Original Almetric Sketch">
                    <span class="card-label">First Sketch</span>
                    <p style="font-size: 0.85rem;">The "Mark 1" concept: focus on tragus-based sensing and modular design.</p>
                </div>
                <div class="card">
                    <img src="prototype.png" alt="Almetric AL Buds 1 Prototype">
                    <span class="card-label">Current Prototype</span>
                    <p style="font-size: 0.85rem;">Refined ergonomics with matte black cabling and a rear battery pack.</p>
                </div>
            </div>

            <h2>Design Refinement</h2>
            <p>Our latest iteration features a <strong>thick matte black over-ear wire</strong> designed to provide maximum stability during movement, leading to a discreet <strong>battery and processing pack</strong> positioned comfortably behind the ear. The shell is finished in a specialized <strong>matte green</strong> polymer that is both bio-compatible and durable.</p>

            <div class="indie-alert">
                <strong>Why we need your support:</strong><br>
                Almetric is a small, independent hardware startup. Unlike big tech conglomerates, we don't have infinite capital. Every dollar from this campaign goes directly into finalizing our sensor calibration and securing the first production run. We are building this for you, funded by you.
            </div>
        </section>

        <footer style="margin-top: 100px; font-size: 0.7rem; color: #444; text-align: center;">
            &copy; 2026 Almetric Labs. Precision in every pulse.
        </footer>
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodeControlAC - Minecraft Anti-Cheat</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #7289DA;
            --secondary-color: #43B581;
            --background-color: #1a1a2e;
            --card-color: #16213e;
            --text-color: #e94560;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--background-color);
            color: #FFFFFF;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            padding: 40px 0;
            text-align: center;
            clip-path: polygon(0 0, 100% 0, 100% 85%, 0% 100%);
        }
        h1 {
            font-size: 3.5em;
            margin: 0;
            text-shadow: 2px 2px rgba(0,0,0,0.1);
            letter-spacing: 2px;
        }
        .feature-section, .pricing-section {
            background-color: var(--card-color);
            border-radius: 20px;
            padding: 30px;
            margin-top: 40px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        .feature-grid, .pricing-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }
        .feature-card, .pricing-card {
            background-color: rgba(255,255,255,0.05);
            border-radius: 15px;
            padding: 25px;
            transition: all 0.3s ease;
            border: 1px solid rgba(255,255,255,0.1);
        }
        .feature-card:hover, .pricing-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }
        .feature-card h3, .pricing-card h3 {
            color: var(--text-color);
            font-size: 1.5em;
            margin-top: 0;
        }
        .cta-button {
            display: inline-block;
            background: linear-gradient(45deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 12px 24px;
            border-radius: 50px;
            text-decoration: none;
            margin-top: 20px;
            transition: all 0.3s ease;
            text-align: center;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }
        .pricing-card .cta-button {
            width: 100%;
            box-sizing: border-box;
        }
        .pricing-card ul {
            padding-left: 20px;
            list-style-type: none;
        }
        .pricing-card ul li:before {
            content: "✓";
            color: var(--secondary-color);
            font-weight: bold;
            display: inline-block;
            width: 1em;
            margin-left: -1em;
        }
        @media (max-width: 768px) {
            .container {
                padding: 15px;
            }
            h1 {
                font-size: 2.5em;
            }
            .feature-grid, .pricing-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>CodeControlAC</h1>
        <p>Advanced Minecraft Anti-Cheat for versions 1.8 to 1.20.6</p>
    </header>
    
    <div class="container">
        <section class="feature-section">
            <h2>Features</h2>
            <div class="feature-grid">
                <div class="feature-card">
                    <h3>Movement</h3>
                    <p>Advanced movement engine similar to Grim, detecting almost any movement-related cheats.</p>
                </div>
                <div class="feature-card">
                    <h3>Combat</h3>
                    <p>Includes checks for Reach, Hitbox, Killaura, Aim, Autoclicker, CrystalAura, and more.</p>
                </div>
                <div class="feature-card">
                    <h3>Player</h3>
                    <p>Detects Baritone, various Badpackets, and Autofish cheats.</p>
                </div>
            </div>
        </section>
        
        <section class="pricing-section">
            <h2>Pricing Options</h2>
            <div class="pricing-grid">
                <div class="pricing-card">
                    <h3>Test Version</h3>
                    <p>Try out CodeControlAC on our test server</p>
                    <ul>
                        <li>Access to test IP</li>
                        <li>Join our Discord community</li>
                    </ul>
                    <a href="#" class="cta-button">Join Discord</a>
                </div>
                <div class="pricing-card">
                    <h3>Premium Version</h3>
                    <p>Full access to CodeControlAC</p>
                    <ul>
                        <li>Five dedicated servers</li>
                        <li>Thorough checks</li>
                        <li>Full configurability</li>
                        <li>Priority support</li>
                    </ul>
                    <p><strong>Price: $30</strong></p>
                    <a href="#" class="cta-button">Purchase Premium</a>
                </div>
            </div>
        </section>
    </div>
</body>
</html>
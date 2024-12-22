<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BioBioincs</title>
    <style>
        /* Global Styles */
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            color: #333;
            line-height: 1.6;
            scroll-behavior: smooth;
        }
        a {
            text-decoration: none;
            color: inherit;
        }
        h1, h2, h3 {
            margin: 0;
        }
        /* Navigation */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 40px;
            background-color: #333;
            position: fixed;
            width: 100%;
            z-index: 1000;
            color: white;
        }
        nav a {
            margin: 0 15px;
            color: white;
            font-size: 14px;
            text-transform: uppercase;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        /* Hero Section */
        .hero {
            height: 100vh;
            background: url('hero-background.jpg') no-repeat center center/cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
        }
        .hero h1 {
            font-size: 4rem;
            font-weight: bold;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 0 auto 30px;
        }
        .hero button {
            padding: 12px 25px;
            font-size: 1rem;
            color: #333;
            background-color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            text-transform: uppercase;
        }
        .hero button:hover {
            background-color: #f4f4f4;
        }
        /* Features Section */
        .features {
            padding: 100px 20px;
            text-align: center;
            background-color: #f9f9f9;
        }
        .features h2 {
            margin-bottom: 40px;
            font-size: 2.5rem;
        }
        .features .feature-grid {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .features .feature-item {
            flex: 1;
            max-width: 300px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .features .feature-item img {
            width: 100%;
            border-radius: 5px;
        }
        .features .feature-item h3 {
            margin-top: 20px;
            font-size: 1.5rem;
        }
        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        footer p {
            margin: 0;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav>
        <h1>BioBioincs</h1>
        <div>
            <a href="#home">Home</a>
            <a href="#features">Features</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>
    <!-- Hero Section -->
    <section id="home" class="hero">
        <h1>Welcome to BioBioincs</h1>
        <p>Pioneering the future of biotechnology with innovation and excellence.</p>
        <button>Learn More</button>
    </section>
    <!-- Features Section -->
    <section id="features" class="features">
        <h2>Our Features</h2>
        <div class="feature-grid">
            <div class="feature-item">
                <img src="feature1.jpg" alt="Feature 1">
                <h3>Advanced Tech</h3>
                <p>Cutting-edge biotechnology solutions for a brighter future.</p>
            </div>
            <div class="feature-item">
                <img src="feature2.jpg" alt="Feature 2">
                <h3>Innovative Research</h3>
                <p>Our dedicated team is revolutionizing the biotech industry.</p>
            </div>
            <div class="feature-item">
                <img src="feature3.jpg" alt="Feature 3">
                <h3>Sustainable Solutions</h3>
                <p>Committed to sustainable and ethical biotechnology.</p>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer>
        <p>&copy; 2024 BioBioincs. All Rights Reserved.</p>
    </footer>
</body>
</html>

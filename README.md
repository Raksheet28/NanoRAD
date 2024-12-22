<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NanoRAD</title>
    <style>
        /* Global Styles */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: #333;
            line-height: 1.6;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 40px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            z-index: 1000;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            height: 100vh;
            position: relative;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .hero video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
        .hero h1 {
            font-size: 3rem;
            font-weight: bold;
        }
        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 20px auto;
        }
        .after-hero {
            background: url('Nanoparticle%20Picture.jpg') no-repeat center center/cover;
            color: #fff;
            padding: 100px 20px;
            text-align: center;
        }
        .data-section {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 50px;
        }
        .data-box {
            flex: 1;
            max-width: 300px;
            background-color: #512d6d;
            color: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }
        .key-features {
            padding: 50px 20px;
            background-color: #f9f9f9;
            text-align: center;
        }
        .key-features h2 {
            font-size: 2.5rem;
        }
        .key-features .feature-grid {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }
        .key-features .feature-box {
            flex: 1;
            max-width: 300px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .additional-features {
            padding: 50px 20px;
            text-align: center;
        }
        .team-page {
            padding: 50px 20px;
            background-color: #f4f4f4;
        }
        .team-member {
            margin-bottom: 20px;
            text-align: center;
        }
        .team-member img {
            border-radius: 50%;
            width: 100px;
            height: 100px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav>
        <h1>NanoRAD</h1>
        <div>
            <a href="#home">Home</a>
            <a href="#team">Team</a>
        </div>
    </nav>
    <!-- Home Page -->
    <section id="home" class="hero">
        <video autoplay muted loop>
            <source src="Nanoparticle%20Video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <h1>Transforming Cancer Outcomes</h1>
        <p>Precision-driven nanoparticle-based radiotherapy for targeted treatment.</p>
    </section>
    <section class="after-hero">
        <h2>Advanced Solutions for Cancer Therapy</h2>
        <p>Delivering exceptional outcomes with targeted radiotherapy solutions.</p>
    </section>
    <section class="data-section">
        <div class="data-box">
            <h3>5-Year Survival Rate</h3>
            <p>Patients with advanced cancer have a relative survival rate of 35%.</p>
        </div>
        <div class="data-box">
            <h3>Reduced Side Effects</h3>
            <p>Localized therapy minimizes damage to healthy tissues.</p>
        </div>
    </section>
    <section class="key-features">
        <h2>Key Features</h2>
        <div class="feature-grid">
            <div class="feature-box">
                <h3>Nanoparticle Design</h3>
                <p>Engineered with a biocompatible core and antibody coating.</p>
            </div>
            <div class="feature-box">
                <h3>Targeted Delivery</h3>
                <p>Precise binding to cancer cells using advanced antibodies.</p>
            </div>
            <div class="feature-box">
                <h3>Customizable Solutions</h3>
                <p>Adaptable to multiple cancer types with versatile designs.</p>
            </div>
        </div>
    </section>
    <section class="additional-features">
        <h2>Additional Features and Benefits</h2>
        <p>Explore the advantages of our groundbreaking therapy.</p>
    </section>
    <!-- Team Page -->
    <section id="team" class="team-page">
        <h2>Meet Our Team</h2>
        <div class="team-member">
            <img src="team1.jpg" alt="Team Member 1">
            <h3>Dr. Jane Doe</h3>
            <p>Lead Research Scientist</p>
        </div>
        <div class="team-member">
            <img src="team2.jpg" alt="Team Member 2">
            <h3>Dr. John Smith</h3>
            <p>Chief Medical Officer</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 NanoRAD. All Rights Reserved.</p>
    </footer>
</body>
</html>

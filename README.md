<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NanoRAD - Targeted Cancer Therapy</title>
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
        .section {
            padding: 50px 20px;
            text-align: center;
        }
        .section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        .section p {
            max-width: 800px;
            margin: 0 auto 20px;
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
            text-align: left;
        }
        .benefits-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
        }
        .benefit-item {
            flex: 1;
            max-width: 300px;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .contact-section {
            padding: 50px 20px;
            text-align: center;
            background-color: #f4f4f4;
        }     
        .team-section {
            padding: 50px 20px;
            background-color: #eef2f3;
            text-align: center;
        }
        .team-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .team-member {
            flex: 1;
            max-width: 250px;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .team-member img {
            width: 100%;
            border-radius: 50%;
            margin-bottom: 15px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .nanoparticle-image {
            display: block;
            max-width: 100%;
            margin: 20px auto;
            border-radius: 10px;
        }
        .video-section {
            text-align: center;
            margin: 40px 0;
        }
        .video-section video {
            width: 80%;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav>
        <h1>NanoRAD</h1>
        <div>
            <a href="#overview">Overview</a>
            <a href="#features">Features</a>
            <a href="#how-it-works">How It Works</a>
            <a href="#applications">Applications</a>
            <a href="#benefits">Benefits</a>
            <a href="#team">Team</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>
    <!-- Hero Section -->
    <section id="home" class="hero">
        <video autoplay muted loop>
            <source src="Nanoparticle%20Video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <h1>Revolutionizing Cancer Therapy</h1>
        <p>Precision-driven nanoparticle-based radiotherapy for effective, targeted cancer treatment.</p>
    </section>
    <!-- Overview Section -->
    <section id="overview" class="section">
        <h2>Product Concept</h2>
        <img src="Nanoparticle%20Image.jpg" alt="Nanoparticle Design" class="nanoparticle-image">
        <p>NanoRAD™ – Targeted Nanoparticle-Based Radiotherapy for Breast Cancer.</p>
        <p>NanoRAD is a cutting-edge nanoparticle-based delivery system for radioisotope Iodine-131 (I-131), designed to revolutionize cancer treatment. The system utilizes nanoparticles coated with cancer-specific antibodies to deliver the radioisotope directly to cancer cells, minimizing damage to surrounding healthy tissue.</p>
    </section>
    <!-- Features Section -->
    <section id="features" class="section key-features">
        <h2>Key Features</h2>
        <div class="feature-grid">
            <div class="feature-box">
                <h3>Nanoparticle Design</h3>
                <p><strong>Core Structure:</strong> Each nanoparticle is designed with a biocompatible core that houses Iodine-131, protecting it during circulation and releasing it upon reaching tumor cells.</p>
                <p><strong>Antibody Coating:</strong> Cancer-specific antibodies ensure the nanoparticles accumulate at the tumor site.</p>
            </div>
            <div class="feature-box">
                <h3>Targeted Delivery Mechanism</h3>
                <p><strong>Antibody-Mediated Targeting:</strong> Nanoparticles bind to overexpressed receptors on cancer cells.</p>
                <p><strong>Precision Release:</strong> Beta particles destroy cancer cells within a confined radius.</p>
            </div>
            <div class="feature-box">
                <h3>Controlled Radiation Emission</h3>
                <p><strong>Beta Particle Emission:</strong> I-131 damages DNA of cancer cells, leading to cell death.</p>
                <p><strong>Real-Time Monitoring:</strong> Imaging techniques confirm accurate targeting.</p>
            </div>
            <div class="feature-box">
                <h3>Minimized Side Effects</h3>
                <p><strong>Localized Treatment:</strong> Reduces exposure to healthy tissues.</p>
                <p><strong>Reduced Dosage:</strong> Lowers overall radioisotope dose.</p>
            </div>
        </div>
    </section>
    <!-- How It Works Section -->
    <section id="how-it-works" class="section">
        <h2>How NanoRAD Works</h2>
        <div class="video-section">
            <video autoplay muted loop>
                <source src="Nanoparticle%20Video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
        <p><strong>1. Administration:</strong> The patient receives an intravenous injection of NanoRAD nanoparticles.</p>
        <p><strong>2. Targeting and Accumulation:</strong> Antibodies on nanoparticles bind to cancer-specific markers.</p>
        <p><strong>3. Release and Treatment:</strong> Iodine-131 emits beta radiation to destroy cancer cells.</p>
        <p><strong>4. Monitoring:</strong> Imaging techniques ensure accurate targeting.</p>
        <p><strong>5. Clearance:</strong> Unbound nanoparticles are cleared by the body.</p>
    </section>
    <!-- Applications Section -->
    <section id="applications" class="section">
        <h2>Potential Applications</h2>
        <p><strong>Treatment of Advanced Cancers:</strong> Suited for metastatic cancers where surgery is not feasible.</p>
        <p><strong>Post-Surgical Cancer Treatment:</strong> Targets remaining cancer cells to reduce recurrence risk.</p>
        <p><strong>Combination Therapy:</strong> Can be used with chemotherapy or immunotherapy for a multi-pronged approach.</p>
    </section>
    <!-- Benefits Section -->
    <section id="benefits" class="section">
        <h2>Additional Features and Benefits</h2>
        <div class="benefits-list">
            <div class="benefit-item">
                <h3>Enhanced Tumor Penetration</h3>
                <p>Specific nanoparticle size ensures deeper tumor microenvironment access.</p>
            </div>
            <div class="benefit-item">
                <h3>Biocompatibility</h3>
                <p>Made from biodegradable materials, ensuring safety and reduced toxicity.</p>
            </div>
            <div class="benefit-item">
                <h3>Reduced Radiation Exposure</h3>
                <p>Minimizes whole-body radiation, protecting sensitive patients.</p>
            </div>
        </div>
    </section>
    <!-- Team Section -->
    <section id="team" class="team-section">
        <h2>Meet Our Team</h2>
        <div class="team-grid">
            <div class="team-member">
                <img src="team1.jpg" alt="Team Member 1">
                <h3>Dr. Alex Johnson</h3>
                <p>Lead Scientist - Oncology</p>
            </div>
            <div class="team-member">
                <img src="team2.jpg" alt="Team Member 2">
                <h3>Dr. Emily Carter</h3>
                <p>Biochemist - Nanotechnology</p>
            </div>
            <div class="team-member">
                <img src="team3.jpg" alt="Team Member 3">
                <h3>Dr. Rajesh Mehta</h3>
                <p>Research Specialist - Radiotherapy</p>
            </div>
            <div class="team-member">
                <img src="team4.jpg" alt="Team Member 4">
                <h3>Sofia Martinez</h3>
                <p>Project Manager</p>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <p>For inquiries or collaborations, please reach out to us at:</p>
        <p><strong>Email:</strong> contact@nanorad.com</p>
        <p><strong>Phone:</strong> +1 234-567-890</p>
    </section>
    <footer>
        <p>&copy; 2024 NanoRAD. All Rights Reserved.</p>
    </footer>
</body>
</html>

# NanoRAD
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NanoRAD</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            box-sizing: border-box;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: #333;
            color: white;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }
        .hero {
            position: relative;
            height: 100vh;
            color: white;
            text-align: center;
        }
        .hero video {
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
            top: 0;
            left: 0;
            z-index: -1;
        }
        .hero .content {
            position: relative;
            top: 50%;
            transform: translateY(-50%);
        }
        .overlay-section {
            position: relative;
            text-align: center;
            color: white;
            padding: 50px 20px;
        }
        .overlay-section img {
            width: 100%;
            object-fit: cover;
        }
        .overlay-section .boxes {
            display: flex;
            justify-content: space-around;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 80%;
        }
        .overlay-section .box {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 20px;
            width: 45%;
            border-radius: 10px;
            text-align: center;
        }
        .key-features, .additional-features {
            padding: 50px 20px;
        }
        .key-features .feature-item,
        .additional-features .feature-item {
            margin: 20px 0;
        }
        .additional-features .images-row {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .additional-features .images-row .image-box {
            flex: 1;
            text-align: center;
            margin: 10px;
        }
        .video-section {
            padding: 50px 20px;
            text-align: center;
        }
        .team-page {
            padding: 50px 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <nav>
        <h1>NanoRAD</h1>
        <div>
            <a href="#home">Home</a>
            <a href="#team">Team</a>
        </div>
    </nav>
    <!-- Home Page -->
    <section id="home">
        <!-- Hero Section -->
        <div class="hero">
            <video autoplay muted loop>
                <source src="Nanoparticle Video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <div class="content">
                <h1>NanoRAD: Revolutionizing Cancer Therapy</h1>
                <p>Precision-driven nanoparticle-based radiotherapy.</p>
            </div>
        </div>
        <!-- Overlay Section -->
        <div class="overlay-section">
            <img src="Nanoparticle Picture.jpg" alt="Nanoparticle Model">
            <div class="boxes">
                <div class="box">
                    <h2>Targeted Therapy</h2>
                    <p>Delivering treatment directly to cancer cells.</p>
                </div>
                <div class="box">
                    <h2>Minimized Side Effects</h2>
                    <p>Protecting healthy tissue with precision.</p>
                </div>
            </div>
        </div>
        <!-- Key Features -->
        <div class="key-features">
            <h2>Key Features</h2>
            <div class="feature-item">
                <h3>Innovative Design</h3>
                <p>Nanoparticles engineered for maximum biocompatibility.</p>
            </div>
            <div class="feature-item">
                <h3>Real-Time Monitoring</h3>
                <p>Track treatment progress with precision imaging.</p>
            </div>
        </div>
        <!-- Additional Features -->
        <div class="additional-features">
            <h2>Additional Features</h2>
            <p>Enhancing cancer treatment with cutting-edge technology.</p>
            <div class="images-row">
                <div class="image-box">
                    <img src="Nanoparticle Picture.jpg" alt="Enhanced Visualization">
                    <h3>Enhanced Visualization</h3>
                    <p>Clear imaging for accurate treatment delivery.</p>
                </div>
            </div>
        </div>
        <!-- Video Section -->
        <div class="video-section">
            <h2>Watch NanoRAD in Action</h2>
            <video autoplay muted loop>
                <source src="Nanoparticle Video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
    </section>
    <!-- Team Page -->
    <section id="team">
        <div class="team-page">
            <h2>Meet Our Team</h2>
            <p>Innovators driving the NanoRAD revolution.</p>
        </div>
    </section>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Afomia Medium Clinic - Quality Healthcare in Hawassa</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary-color: #2B5876;
            --secondary-color: #4ECDC4;
            --accent-color: #FF6B6B;
            --emergency-red: #FF4757;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        .emergency-bar {
            background-color: var(--emergency-red);
            color: white;
            text-align: center;
            padding: 10px;
            font-weight: bold;
        }

        .header {
            background-color: var(--primary-color);
            color: white;
            padding: 1rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: white;
        }

        .contact-bar {
            background-color: var(--secondary-color);
            padding: 15px;
            text-align: center;
            color: white;
        }

        .hero {
            height: 70vh;
            background: linear-gradient(rgba(43, 88, 118, 0.8), rgba(43, 88, 118, 0.8)),
                        url('https://images.unsplash.com/photo-1584432810601-6c7f27d2362b') center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }

        .hero-content h1 {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .highlight {
            color: var(--accent-color);
            font-weight: bold;
        }

        .cta-button {
            padding: 1rem 2rem;
            background-color: var(--accent-color);
            color: white;
            text-decoration: none;
            border-radius: 30px;
            transition: transform 0.3s;
            display: inline-block;
            margin-top: 1rem;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }

        .cta-button:hover {
            transform: translateY(-2px);
        }

        .services {
            padding: 4rem 2rem;
            background-color: #f9f9f9;
        }

        .section-title {
            text-align: center;
            margin-bottom: 3rem;
            color: var(--primary-color);
            font-size: 2.2rem;
        }

        .services-grid {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-icon {
            font-size: 2.5rem;
            color: var(--secondary-color);
            margin-bottom: 1rem;
        }

        .address-section {
            padding: 4rem 2rem;
            background-color: var(--primary-color);
            color: white;
            text-align: center;
        }

        .map-container {
            margin: 2rem auto;
            max-width: 800px;
            height: 300px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        footer {
            background-color: #2B2B2B;
            color: white;
            padding: 3rem 2rem;
            text-align: center;
        }

        .contact-info {
            margin: 1rem 0;
            font-size: 1.1rem;
        }

        .contact-info i {
            margin-right: 10px;
            color: var(--secondary-color);
        }

        @media (max-width: 768px) {
            .hero-content h1 {
                font-size: 2rem;
            }
            
            .logo {
                font-size: 1.2rem;
            }
        }
    </style>
</head>
<body>
    <div class="emergency-bar">
        🚨 24-Hour Emergency Services Available | Open 24/7 🚨
    </div>

    <header class="header">
        <nav class="nav-container">
            <div class="logo">Afomia Medium Clinic</div>
            <div class="contact-bar">
                <i class="fas fa-phone"></i> +251 924 661 342 | +251 948 928 354
            </div>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Compassion with Humanity <span class="highlight">&</span> Quality</h1>
            <p style="font-size: 1.2rem; max-width: 800px; margin: 0 auto;">
                Providing exceptional 24-hour medical care with specialist doctors and advanced laboratory services
            </p>
            <a href="#contact" class="cta-button">Emergency Contact Now</a>
        </div>
    </section>

    <section class="services">
        <h2 class="section-title">Our Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <i class="fas fa-ambulance service-icon"></i>
                <h3>24/7 Emergency Care</h3>
                <p>Immediate medical attention with emergency specialists</p>
            </div>
            <div class="service-card">
                <i class="fas fa-flask service-icon"></i>
                <h3>Advanced Laboratory</h3>
                <p>24-hour diagnostic services with rapid results</p>
            </div>
            <div class="service-card">
                <i class="fas fa-user-md service-icon"></i>
                <h3>Specialist Care</h3>
                <p>Expert medical care across all specialties</p>
            </div>
        </div>
    </section>

    <section class="address-section">
        <h2>Our Location</h2>
        <div class="contact-info">
            <p><i class="fas fa-map-marker-alt"></i> Near Hawassa Alamura Senior Secondary School</p>
            <p>5 meters from traffic light on new road to chicken farm</p>
        </div>
        <div class="map-container">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3940.984509999512!2d38.45983931478114!3d8.998573093550987!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zOMKwNTknNTQuOCJOIDM4wrAyNyczMS4xIkU!5e1!3m2!1sen!2set!4v1624456789012!5m2!1sen!2set" 
                    width="100%" 
                    height="300" 
                    style="border:0;" 
                    allowfullscreen="" 
                    loading="lazy">
            </iframe>
        </div>
    </section>

    <footer>
        <h3>Afomia Medium Clinic</h3>
        <div class="contact-info">
            <p><i class="fas fa-phone"></i> Emergency Numbers: +251 924 661 342 | +251 948 928 354</p>
            <p><i class="fas fa-clock"></i> Open 24 Hours - 7 Days a Week</p>
        </div>
        <p style="margin-top: 2rem;">"Compassion with Humanity and Quality" - Your Trusted Healthcare Partner</p>
    </footer>
</body>
</html>

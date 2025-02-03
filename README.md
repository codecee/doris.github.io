<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doris Berardinucci - Psychotherapist</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header and Navigation */
        .navbar {
            background-color: #2c3e50;
            color: white;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .navbar .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }

        .navbar .nav-links {
            display: flex;
            gap: 1.5rem;
        }

        .navbar .nav-links a {
            color: white;
            transition: color 0.3s ease;
        }

        .navbar .nav-links a:hover {
            color: #3498db;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(44, 62, 80, 0.8), rgba(44, 62, 80, 0.8)), url('therapy-background.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 6rem 2rem;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin: 0;
            animation: fadeIn 2s ease-in-out;
        }

        .hero h2 {
            font-size: 1.8rem;
            margin: 1rem 0;
            animation: fadeIn 3s ease-in-out;
        }

        .hero .cta-button {
            display: inline-block;
            margin-top: 2rem;
            padding: 1rem 2rem;
            background-color: #3498db;
            color: white;
            border-radius: 5px;
            font-size: 1.2rem;
            transition: background-color 0.3s ease;
            animation: fadeIn 4s ease-in-out;
        }

        .hero .cta-button:hover {
            background-color: #2980b9;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* Main Content */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .section {
            margin-bottom: 4rem;
        }

        .section h2 {
            color: #2c3e50;
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
            text-align: center;
        }

        /* About Me Section */
        .about-me {
            display: flex;
            align-items: center;
            gap: 3rem;
        }

        .about-me img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #3498db;
        }

        .about-me p {
            font-size: 1.1rem;
            line-height: 1.8;
        }

        /* Services Section */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background-color: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .service-card:hover {
            transform: translateY(-10px);
        }

        .service-card h3 {
            color: #2c3e50;
            margin-bottom: 1rem;
        }

        /* Testimonials Section */
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .testimonial {
            background-color: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .testimonial p {
            font-style: italic;
            color: #555;
        }

        .testimonial-author {
            font-weight: bold;
            color: #2c3e50;
            margin-top: 1rem;
        }

        /* Contact Section */
        .contact-form {
            display: grid;
            gap: 1rem;
            max-width: 600px;
            margin: 0 auto;
        }

        .contact-form input, .contact-form textarea {
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }

        .contact-form button {
            padding: 1rem;
            background-color: #3498db;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1.2rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .contact-form button:hover {
            background-color: #2980b9;
        }

        /* Footer */
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 4rem;
        }

        footer a {
            color: #3498db;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="logo">Doris Berardinucci</div>
        <div class="nav-links">
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Welcome to My Practice</h1>
        <h2>Licensed Psychotherapist with Over 10 Years of Experience</h2>
        <a href="#contact" class="cta-button">Schedule a Session</a>
    </section>

    <!-- Main Content -->
    <div class="container">
        <!-- About Me Section -->
        <section id="about" class="section">
            <h2>About Me</h2>
            <div class="about-me">
                <img src="doris-berardinucci.jpg" alt="Doris Berardinucci">
                <div>
                    <p>Hi, I’m Doris Berardinucci, a licensed psychotherapist based in Montesilvano, Abruzzo, Italy. With over a decade of experience, I specialize in helping individuals navigate life’s challenges and achieve mental wellness. My approach is compassionate, personalized, and focused on your unique needs.</p>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" clas…

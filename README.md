<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SwiftLogistics | Courier & Transport Services</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
        }

        /* Header Styles */
        header {
            background: #003366;
            color: white;
            padding: 1rem;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
        }

        /* Hero Section */
        .hero {
            background: url('https://example.com/truck-bg.jpg') center/cover;
            height: 500px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
        }

        .hero-content h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        /* Services Section */
        .services {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .service-card {
            padding: 2rem;
            border: 1px solid #ddd;
            border-radius: 8px;
            text-align: center;
        }

        /* Tracking Section */
        .tracking {
            background: #f5f5f5;
            padding: 4rem 2rem;
            text-align: center;
        }

        .tracking-form {
            max-width: 600px;
            margin: 2rem auto;
        }

        input[type="text"] {
            padding: 0.8rem;
            width: 70%;
            margin-right: 1rem;
        }

        button {
            padding: 0.8rem 2rem;
            background: #003366;
            color: white;
            border: none;
            cursor: pointer;
        }

        /* Footer Styles */
        footer {
            background: #003366;
            color: white;
            padding: 2rem;
            text-align: center;
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .hero-content h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">SwiftLogistics</div>
            <div class="nav-links">
                <a href="#home">Home</a>
                <a href="#services">Services</a>
                <a href="#tracking">Tracking</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Fast & Reliable Courier Services</h1>
            <p>Nationwide delivery solutions for businesses and individuals</p>
            <button>Get a Quote</button>
        </div>
    </section>

    <section class="services" id="services">
        <h2>Our Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Express Delivery</h3>
                <p>Same-day and next-day delivery solutions</p>
            </div>
            <div class="service-card">
                <h3>Freight Transport</h3>
                <p>Heavy cargo transportation nationwide</p>
            </div>
            <div class="service-card">
                <h3>International Shipping</h3>
                <p>Global logistics and customs clearance</p>
            </div>
        </div>
    </section>

    <section class="tracking" id="tracking">
        <h2>Track Your Shipment</h2>
        <div class="tracking-form">
            <input type="text" placeholder="Enter tracking number">
            <button>Track</button>
        </div>
    </section>

    <footer>
        <p>Contact us: info@swiftlogistics.com | (555) 123-4567</p>
        <p>123 Transportation Street, Logistics City, LC 4567</p>
        <p>&copy; 2023 SwiftLogistics. All rights reserved.</p>
    </footer>
</body>
</html>

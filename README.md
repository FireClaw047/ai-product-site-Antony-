<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eleven Store | Theme Based Football Merch</title>
    
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        
        /* Navigation */
        nav {
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        /* Hero Section */
        .hero {
            background-color: #1a4a3a; /* Deep Green football pitch color */
            color: white;
            padding: 100px 20px;
            text-align: center;
        }
        .hero h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }
        .btn {
            background-color: #fff;
            color: #1a4a3a;
            padding: 10px 20px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
        }

        /* Container for sections */
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
            text-align: center;
        }

        /* Features Section */
        .features {
            background-color: #f4f4f4;
        }
        .feature-box {
            margin-bottom: 30px;
            padding: 20px;
            background: white;
            border: 1px solid #ddd;
        }

        /* Testimonials */
        .testimonial {
            font-style: italic;
            margin-bottom: 20px;
            color: #555;
        }

        /* Contact/Footer */
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 40px 20px;
        }
        input[type="email"] {
            padding: 10px;
            width: 200px;
        }
        button {
            padding: 10px 20px;
            background-color: #1a4a3a;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <nav>
        <span>ELEVEN STORE</span>
        <br><br>
        <a href="#home">Home</a>
        <a href="#features">Collections</a>
        <a href="#testimonials">Reviews</a>
        <a href="#contact">Contact</a>
    </nav>

    <header id="home" class="hero">
        <h1>Wear the Game. Live the Theme.</h1>
        <p>Exclusive theme-based football merchandise for the modern fan.</p>
        <a href="#features" class="btn">Shop the Drop</a>
    </header>

    <section id="features" class="features">
        <div class="container">
            <h2>Our Collections</h2>
            <p>We combine football heritage with modern art styles.</p>
            
            <div class="feature-box">
                <h3>The Retro Vault</h3>
                <p>Classic cuts and vintage patterns inspired by the 90s golden era.</p>
            </div>

            <div class="feature-box">
                <h3>Neon Pitch</h3>
                <p>Cyberpunk and synth-wave inspired kits for the digital age.</p>
            </div>

            <div class="feature-box">
                <h3>Minimalist United</h3>
                <p>Clean lines and monochrome badges for everyday street wear.</p>
            </div>
        </div>
    </section>

    <section class="container">
        <h2>Why Eleven Store?</h2>
        <p><strong>Designed for Fans:</strong> We believe a jersey is a canvas. We create gear that fits your lifestyle, not just match day.</p>
    </section>

    <section id="testimonials" style="background-color: #e8e8e8;">
        <div class="container">
            <h2>Fan Reviews</h2>
            
            <div class="testimonial">
                "Finally, football gear I can wear to a club, not just the stadium. The Neon Pitch hoodie is incredible." 
                <br><strong>— Alex R.</strong>
            </div>
            
            <div class="testimonial">
                "The quality of the Retro Vault jersey took me straight back to 1998. 10/10." 
                <br><strong>— Sarah J.</strong>
            </div>
        </div>
    </section>

    <footer id="contact">
        <h2>Join the Club</h2>
        <p>Sign up for early access to new theme drops.</p>
        <form>
            <input type="email" placeholder="Enter your email" required>
            <button type="submit">Subscribe</button>
        </form>
        <p style="font-size: 0.8em; margin-top: 30px;">&copy; 2026 Eleven Store. All rights reserved.</p>
    </footer>

</body>
</html>

[Untitled-1.html](https://github.com/user-attachments/files/28905126/Untitled-1.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GG Detailing</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0f0f0f;
            color: white;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(90deg, #b30000, #1a1a1a);
            padding: 60px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            color: #d0d0d0;
            margin-bottom: 20px;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 25px;
            background: #111;
            padding: 15px;
            position: sticky;
            top: 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #ff4d4d;
        }

        section {
            max-width: 900px;
            margin: auto;
            padding: 50px 20px;
        }

        h2 {
            margin-bottom: 20px;
            color: #ff4d4d;
        }

        .card {
            background: #1a1a1a;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
            border: 1px solid #222;
        }

        .button {
            display: inline-block;
            padding: 12px 20px;
            background: #b30000;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            transition: 0.3s;
        }

        .button:hover {
            background: #d40000;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #111;
            color: #777;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }

            nav {
                flex-wrap: wrap;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>GG Detailing</h1>
    <p>Premium Mobile Detailing — Clean. Shine. Protect.</p>
    <a class="button" href="#contact">Book Now</a>
</header>

<nav>
    <a href="#services">Services</a>
    <a href="#pricing">Pricing</a>
    <a href="#contact">Contact</a>
</nav>

<section id="services">
    <h2>Services</h2>

    <div class="card">
        <h3>Exterior Detail</h3>
        <p>Foam wash, wheel cleaning, tire shine, hand dry, and exterior finish.</p>
    </div>

    <div class="card">
        <h3>Interior Detail</h3>
        <p>Deep vacuum, dash and console cleaning, plastic restoration, and fresh finish.</p>
    </div>

    <div class="card">
        <h3>Full Detail</h3>
        <p>Complete interior and exterior detail for a showroom-quality clean.</p>
    </div>
</section>

<section id="pricing">
    <h2>Pricing</h2>

    <div class="card">
        <p><strong>Basic Wash:</strong> $40–$60</p>
        <p><strong>Interior Detail:</strong> $80–$120</p>
        <p><strong>Full Detail:</strong> $120–$180</p>

        <p style="margin-top:15px;color:#aaa;">
            *Prices may vary depending on vehicle size and condition.
        </p>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>

    <div class="card">
        <p>📍 Mobile Service — We come to you</p>
        <p>📞 Phone: 442-306-7167</p>
        <p>📸 Instagram: @ggsmobiledetailing</p>

        <a class="button"
           href="https://instagram.com/ggsmobiledetailing"
           target="_blank">
           Message on Instagram
        </a>
    </div>
</section>

<footer>
    <p>&copy; 2026 GG Detailing. All Rights Reserved.</p>
</footer>

</body>
</html>

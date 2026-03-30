# portfolio
A clean and responsive portfolio website for showcasing web development services
<!DOCTYPE html>
<html>
<head>
    <title>Gunal Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: #0f172a;
            color: white;
            text-align: center;
        }

        header {
            padding: 40px 20px;
            background: linear-gradient(135deg, #1e293b, #020617);
        }

        h1 {
            font-size: 40px;
        }

        h2 {
            color: #38bdf8;
            margin-bottom: 10px;
        }

        section {
            padding: 30px 20px;
        }

        .card {
            background: #1e293b;
            margin: 15px auto;
            padding: 20px;
            border-radius: 15px;
            max-width: 400px;
        }

        .btn {
            display: inline-block;
            margin-top: 15px;
            padding: 12px 25px;
            background: #22c55e;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #16a34a;
        }

        footer {
            padding: 15px;
            background: #020617;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    <h1>GUNAL</h1>
    <p>Frontend Developer</p>
</header>

<section>
    <div class="card">
        <h2>About Me</h2>
        <p>I will create a simple and responsive HTML website for you.</p>
    </div>

    <div class="card">
        <h2>Skills</h2>
        <p>HTML,CSS</p>
    </div>

    <div class="card">
        <h2>Services</h2>
        <p>Website Creation</p>
    </div>

    <div class="card">
        <h2>Contact</h2>
        <p>📞 9361056081</p>
        <p>📧 gunaleswaran123@gmail.com</p>

        <a href="https://wa.me/919361056081?text=Hi%20I%20want%20a%20website" class="btn">
            Chat on WhatsApp 🚀
        </a>
    </div>
</section>

<footer>
    <p>© 2026 Gunal | All Rights Reserved</p>
</footer>

</body>
</html>

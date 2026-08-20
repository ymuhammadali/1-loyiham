<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mening 1-loyiham</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f2f2f2;
            color: #222;
        }

        header {
            background: #111;
            color: white;
            padding: 20px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            color: #00aaff;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 25px;
        }

        nav a:hover {
            color: #00aaff;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: white;
        }

        .hero h2 {
            font-size: 45px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 20px;
            color: #666;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            background: #00aaff;
            color: white;
            padding: 14px 30px;
            border-radius: 8px;
            text-decoration: none;
        }

        .btn:hover {
            background: #0088cc;
        }

        .about {
            padding: 60px 20px;
            text-align: center;
        }

        .about h2 {
            margin-bottom: 20px;
        }

        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>MyProject</h1>

        <nav>
            <a href="#">Bosh sahifa</a>
            <a href="#">Men haqimda</a>
            <a href="#">Aloqa</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Salom! 👋</h2>

        <p>
            Bu mening HTML va CSS yordamida yaratgan birinchi loyiham.
        </p>

        <a href="#" class="btn">Boshlash</a>
    </section>

    <section class="about">
        <h2>Loyiha haqida</h2>

        <p>
            Men web dasturlashni o‘rganmoqdaman.
            Ushbu loyiha orqali HTML va CSS bo‘yicha
            bilimlarimni mustahkamlayapman.
        </p>
    </section>

    <footer>
        <p>© 2026 MyProject. Barcha huquqlar himoyalangan.</p>
    </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Můj Blog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #555;
        }
        .content {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        section {
            display: none;
        }
        #home {
            display: block;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Vítejte na mém blogu</h1>
    </header>
    <nav>
        <a href="#home" onclick="showSection('home')">O mně</a>
        <a href="#blog" onclick="showSection('blog')">Blog</a>
        <a href="#contact" onclick="showSection('contact')">Kontakt</a>
    </nav>
    <div class="content">
        <section id="home">
            <h2>O mně</h2>
            <p>Ahoj! Jmenuji se [Vaše jméno] a vítám vás na mém blogu. Zde píšu o svých zkušenostech, zájmech a všech věcech, které mě zajímají. Doufám, že se vám budou mé příspěvky líbit!</p>
        </section>
        <section id="blog">
            <h2>Blog</h2>
            <p>Zde se objeví vaše blogové příspěvky.</p>
        </section>
        <section id="contact">
            <h2>Kontakt</h2>
            <p>Máte nějaké otázky nebo připomínky? Kontaktujte mě na [vaše e-mailová adresa] nebo mě sledujte na sociálních sítích.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 [Vaše jméno]. Všechna práva vyhrazena.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.style.display = 'none';
            });
            document.getElementById(sectionId).style.display = 'block';
        }
    </script>
</body>
</html>


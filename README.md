<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Soma world or we live in immense prosperity</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #fff;
            padding: 20px 0;
            border-bottom: 1px solid #ddd;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav {
            display: flex;
            gap: 20px;
            margin-left: 20px;
        }
        nav a {
            color: #333;
            text-decoration: none;
            padding: 10px;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #007BFF;
        }
        .blog-title {
            flex-grow: 1;
            text-align: center;
        }
        .social-icons {
            margin-right: 20px;
        }
        .social-icons a {
            color: #333;
            text-decoration: none;
            margin: 0 10px;
            font-size: 1.5em;
            transition: color 0.3s ease;
        }
        .social-icons a:hover {
            color: #007BFF;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .blog-post {
            margin-bottom: 20px;
        }
        .blog-post h2 {
            margin-top: 0;
        }
        .profile-container {
            display: flex;
            align-items: flex-start;
            margin-bottom: 20px;
        }
        .profile-container img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-right: 20px;
        }
        .profile-container .bio {
            max-width: 600px;
        }
        footer {
            background-color: #333;
            color: #fff;
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
        <nav>
            <a href="#home" onclick="showSection('home')">Home</a>
            <a href="#blog" onclick="showSection('blog')">Blog</a>
            <a href="#articles" onclick="showSection('articles')">Articles</a>
        </nav>
        <div class="...we live in enormous prosperity">
            <h1>...we live in enormous prosperity</h1>
        </div>
        <div class="social-icons">
            <a href="https://www.linkedin.com/in/vas-profil" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://www.facebook.com/vas-profil" target="_blank"><i class="fab fa-facebook"></i></a>
	    <a href="https://x.com/TomasKnizek" target="_blank"><i class="fab fa-twitter"></i></a>
        </div>
    </header>
    <div class="content">
        <section id="home">
            <div class="profile-container">
                <img src="C:\Users\Tomáš Knížek\OneDrive\Dokumenty\Personální\Foto\profil_foto.jpg" alt="Profile Photo">
                <div class="bio">
                    <h2>O mně</h2>
                    <p>Ahoj! Jmenuji se [Vaše jméno] a vítám vás na mém blogu. Zde píšu o svých zkušenostech, zájmech a všech věcech, které mě zajímají. Doufám, že se vám budou mé příspěvky líbit!</p>
                </div>
            </div>
            <h2>Welcome to My Blog</h2>
            <p>This is the home page of my blog. Here you will find the latest updates and information about my writing journey.</p>
        </section>
        <section id="blog" class="blog-posts">
            <h2>Blog</h2>
            <div class="blog-post">
                <h3>Blog Post Title 1</h3>
                <p>This is a brief introduction to the first blog post. Click here to read more.</p>
            </div>
            <div class="blog-post">
                <h3>Blog Post Title 2</h3>
                <p>This is a brief introduction to the second blog post. Click here to read more.</p>
            </div>
            <!-- Add more blog posts here -->
        </section>
        <section id="articles">
            <h2>Articles</h2>
            <div class="blog-post">
                <h3>Article Title 1</h3>
                <p>This is a brief introduction to the first article. Click here to read more.</p>
            </div>
            <div class="blog-post">
                <h3>Article Title 2</h3>
                <p>This is a brief introduction to the second article. Click here to read more.</p>
            </div>
            <!-- Add more articles here -->
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Tom Knizek. All rights reserved.</p>
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


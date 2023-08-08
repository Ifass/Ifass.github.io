<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blogging Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav li {
            margin: 0 10px;
        }
        nav a {
            text-decoration: none;
            color: white;
        }
        main {
            padding: 1em;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        #blog {
            background-color: #f9f9f9;
            padding: 1em;
            margin: 1em 0;
            border-radius: 5px;
        }
        article {
            margin: 1em 0;
            padding: 1em;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Blogging Website</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#blog">Blog</a></li>
            <li><a href="#upload">Upload</a></li>
            <!-- Replace #upload with the appropriate section ID for uploading -->
        </ul>
    </nav>
    
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Write a brief introduction about yourself here.</p>
        </section>
        
        <section id="portfolio">
            <h2>Portfolio</h2>
            <p>Showcase your projects, skills, or achievements.</p>
        </section>
        
        <section id="blog">
            <h2>Blog</h2>
            
            <article>
                <h3>Blog Post Title</h3>
                <p>Blog post content goes here.</p>
                <img src="blog-image.jpg" alt="Blog Post Image">
            </article>
            
            <!-- Add more articles for additional blog posts -->
        </section>
        
        <section id="upload">
            <h2>Upload Your File</h2>
            <!-- Add your file upload form or integration here -->
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 My Blogging Website | Created by Your Name</p>
    </footer>
</body>
</html>

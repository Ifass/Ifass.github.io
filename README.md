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
            background-color: #f5f5f5;
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
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            font-size: 16px;
        }
        .btn:hover {
            background-color: #45a049;
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
            <li><a href="#newpage">New Page</a></li>
        </ul>
    </nav>
    
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hello there! I'm a passionate student currently pursuing my studies in college, where I'm constantly fueled by my curiosity and enthusiasm for learning. My name is [Your Name], and I'm not your typical college student. I'm not only dedicated to my academic journey but also thrive as a ChatGPT expert and online marketing enthusiast.</p>
            
            <p>With a keen interest in technology and a deep understanding of the capabilities of AI, I've honed my skills as a ChatGPT expert, engaging in thought-provoking conversations and assisting others in finding creative solutions to their questions.</p>
            
            <p>But that's not all—I've also delved into the world of online marketing, where I've harnessed my strategic thinking and innovative mindset to help businesses thrive in the digital landscape. My ability to weave creativity into every aspect of my work sets me apart, allowing me to come up with fresh and exciting ideas that make an impact.</p>
            
            <p>Join me on my journey as I balance the rigors of academia, my passion for AI and technology, and my boundless imagination that fuels my creative ideas. Together, we'll explore new horizons and make the most of every opportunity that comes our way.</p>
        </section>
        
        <section id="portfolio">
            <h2>Portfolio</h2>
            <p>Showcase your projects, skills, or achievements.</p>
        </section>
        
        <section id="blog">
            <h2>Blog</h2>
            
            <article>
                <h3>Blog Post Title 1</h3>
                <p>This is the content of the first blog post.</p>
            </article>
            
            <article>
                <h3>Blog Post Title 2</h3>
                <p>This is the content of the second blog post.</p>
            </article>
            
            <!-- Add more articles for additional blog posts -->
        </section>
        
        <section id="upload">
            <h2>Upload Your File</h2>
            <form action="https://formkeep.com/p/16b60ff06822fde8809a2679a7b32a2e" method="POST" enctype="multipart/form-data">
                <input type="file" name="file">
                <button type="submit" class="btn">Upload File</button>
            </form>
        </section>
        
        <section id="newpage">
            <h2>New Page</h2>
            <p>This is a new page that opens when you click the "New Page" button in the navigation.</p>
        </

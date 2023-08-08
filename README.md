<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blogging Website</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: black;
            color: blue;
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
            border-top: 4px solid #4CAF50;
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
            transition: background-color 0.3s, transform 0.2s;
        }
        .btn:hover {
            background-color: #45a049;
            transform: scale(1.05);
        }
        h2 {
            color: purple;
        }
        #write-blog {
            background-color: black;
            color: white;
            padding: 1em;
            border-radius: 5px;
            margin: 1em 0;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"],
        textarea {
            width: 100%;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .stylish-font {
            font-family: 'Pacifico', cursive;
            font-size: 24px;
        }
    </style>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap">
</head>
<body>
    <header>
        <h1 class="stylish-font">Welcome to My Blogging Website</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about" class="btn">About</a></li>
            <li><a href="#portfolio" class="btn">Portfolio</a></li>
            <li><a href="#blog" class="btn">Blog</a></li>
            <li><a href="#upload" class="btn">Upload</a></li>
            <li><a href="#newpage" class="btn">New Page</a></li>
        </ul>
    </nav>
    
    <main>
        <section id="about">
            <!-- ... (about section content) ... -->
        </section>
        
        <section id="portfolio">
            <!-- ... (portfolio section content) ... -->
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
            
            <!-- Blog Submission Form -->
            <div id="write-blog">
                <h3>Write a Blog</h3>
                <form action="YOUR_FORMSPREE_ENDPOINT" method="POST">
                    <label for="title">Title:</label>
                    <input type="text" id="title" name="title" required><br>
                    <label for="content">Content:</label>
                    <textarea id="content" name="content" rows="4" required></textarea><br>
                    <button type="submit" class="btn">Submit</button>
                </form>
            </div>
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
        </section>
    </main>
    
    <footer>
        <!-- ... (footer content) ... -->
    </footer>
</body>
</html>

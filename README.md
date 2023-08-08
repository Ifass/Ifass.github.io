<!DOCTYPE html>
<html lang="en">
<head>
    <!-- ... (head section) ... -->
</head>
<body>
    <header>
        <!-- ... (header content) ... -->
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#blog">Blog</a></li>
            <li><a href="#upload">Upload</a></li>
            <li><a href="#newpage">New Page</a></li> <!-- Add this line -->
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
            <!-- ... (blog section content) ... -->
        </section>
        
        <section id="upload">
            <h2>Upload Your File</h2>
            <form action="https://formkeep.com/p/16b60ff06822fde8809a2679a7b32a2e" method="POST" enctype="multipart/form-data">
                <input type="file" name="file">
                <button type="submit">Upload File</button>
            </form>
        </section>
        
        <section id="newpage"> <!-- Add this section -->
            <h2>New Page</h2>
            <p>This is a new page that opens when you click the "New Page" button in the navigation.</p>
        </section>
    </main>
    
    <footer>
        <!-- ... (footer content) ... -->
    </footer>
</body>
</html>

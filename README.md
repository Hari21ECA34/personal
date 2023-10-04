# personal

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Travel Blog</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Travel Blog</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="blog-post.html">Blog Post</a></li>
                <!-- Add more navigation links as needed -->
            </ul>
        </nav>
    </header>

    <main>
        <section class="blog-post">
            <h2>Latest Blog Post</h2>
            <article>
                <img src="blog-image.jpg" alt="Blog Image">
                <h3>Exploring a New Destination</h3>
                <p>Join me on an adventure to a new and exciting destination...</p>
                <a href="blog-post.html">Read More</a>
            </article>
        </section>

        <!-- Add more blog post sections here -->

    </main>

    <footer>
        <p>&copy; 2023 My Travel Blog</p>
    </footer>
</body>
</html>
/* Reset some default styles for consistency */
body, h1, h2, p {
    margin: 0;
    padding: 0;
}

/* Apply some basic styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

main {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.blog-post {
    margin-bottom: 30px;
}

.blog-post img {
    max-width: 100%;
    height: auto;
}

footer {
    text-align: center;
    padding: 10px 0;
    background-color: #333;
    color: #fff;
}

/* Add more custom styles as needed */

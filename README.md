<!honest html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A simple blog for sharing posts and articles">
    <title>My Blog</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="logo">
            <h1>My Blog</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content Section -->
    <main>
        <section class="posts">
            <article class="post">
                <h2 class="post-title">Welcome to My Blog!</h2>
                <p class="post-date">December 29, 2024</p>
                <p class="post-content">
                    This is the first post on my blog. Stay tuned for more content coming soon!
                </p>
            </article>

            <article class="post">
                <h2 class="post-title">My Blogging Journey</h2>
                <p class="post-date">December 28, 2024</p>
                <p class="post-content">
                    Blogging is a great way to share your thoughts, ideas, and experiences with the world.
                </p>
            </article>
        </section>

        <section id="about" class="about">
            <h2>About Me</h2>
            <p>
                I am a passionate blogger who loves to write about technology, lifestyle, and travel. Follow my journey!
            </p>
        </section>

        <section id="contact" class="contact">
            <h2>Contact Me</h2>
            <form>
                <label for="name">Your Name:</label>
                <input type="text" id="name" name="name" required><br>

                <label for="email">Your Email:</label>
                <input type="email" id="email" name="email" required><br>

                <label for="message">Your Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br>

                <input type="submit" value="Send Message">
            </form>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 My Blog | All rights reserved</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

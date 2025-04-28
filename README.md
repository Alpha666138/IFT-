# IFT-
Personal website to showcase my skills in website design 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alpha Tech</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1>Alpha Tech</h1>
    </header>
    <nav>
        <button onclick="navigateTo('home')">Home</button>
        <button onclick="navigateTo('about')">About</button>
        <button onclick="navigateTo('portfolio')">Portfolio</button>
        <button onclick="navigateTo('contact')">Contact</button>
        <button onclick="navigateTo('qa')">Q&A</button>
    </nav>
    <main>
        <section id="home" class="page active">
            <h2>Welcome to Alpha Tech</h2>
            <p>This is the home page. Add your welcome content here.</p>
        </section>
        <section id="about" class="page">
            <h2>About Us</h2>
            <p>Write about Alpha Tech here.</p>
        </section>
        <section id="portfolio" class="page">
            <h2>Our Portfolio</h2>
            <p>Showcase your work here. Add images or videos as needed.</p>
        </section>
        <section id="contact" class="page">
            <h2>Contact Us</h2>
            <form id="contactForm">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Submit</button>
            </form>
        </section>
        <section id="qa" class="page">
            <h2>Questions and Answers</h2>
            <p>Answer frequently asked questions here.</p>
        </section>
    </main>
</body>
</html>

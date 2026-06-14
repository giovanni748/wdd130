
├── index.html
├── styles/
│   └── rafting.css
├── images/
│   ├── hero.jpg
│   ├── rafting1.jpg
│   ├── rafting2.jpg
│   └── logo.png


---

✅ index.html (Landing Page)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="White Water Rafting Adventures">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rafting Adventures | Home</title>
    styles/rafting.css
</head>
<body>

    <!-- HEADER -->
    <header>o
        images/logo.png
        <nav>
            <ul>
                <li>#Home</a></li>
                <li>#Trips</a></li>
                <li>#Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- HERO SECTION -->
    <section class="hero">
        images/hero.jpg
        <h1>Experience the Rush of White Water Rafting</h1>
    </section>

    <!-- MAIN CONTENT -->
    <main>
        <section class="intro">
            <h2>Welcome to Rafting Adventures</h2>
            <p>
                Discover the thrill of white water rafting with our expert guides.
                Whether you're a beginner or experienced rafter, we offer unforgettable experiences.
            </p>
        </section>

        <section class="gallery">
            <h2>Our Adventures</h2>
            <div class="grid">
                <figure>
                    images/rafting1.jpg
                    <figcaption>Extreme Rapids</figcaption>
                </figure>
                <figure>
                    images/rafting2.jpg
                    <figcaption>Family-Friendly Rafting</figcaption>
                </figure>
            </div>
        </section>
    </main>

    <!-- FOOTER -->
    <footer>
        <p>© 2026 Rafting Adventures | Stephen Agyeman</p>
    </footer>

</body>
</html>


---

✅ styles/rafting.css
/* GENERAL */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* HEADER */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #004c6d;
    padding: 10px 20px;
}

.logo {
    height: 60px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 15px;
}

nav a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

/* HERO */
.hero {
    position: relative;
    text-align: center;
    color: white;
}

.hero img {
    width: 100%;
    height: 400px;
    object-fit: cover;
}

.hero h1 {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: rgba(0, 0, 0, 0.5);
    padding: 15px;
}

/* MAIN */
main {
    padding: 20px;
}

.intro {
    text-align: center;
}

/* GALLERY */
.gallery .grid {
    display: flex;
    gap: 20px;
    justify-content: center;
}

.gallery img {
    width: 300px;
    border-radius: 10px;
}

/* FOOTER */
footer {
    background-color: #004c6d;
    color: white;
    text-align: center;
    padding: 10px;
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AJ & Patrick's Travel Blog &#9992;</title>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <style>
        /* Basic Styling */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            scroll-behavior: smooth;
        }

        header, nav, main, section, footer {
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
        }

        /* Header Styling */
        header {
            background: #4CAF50;
            color: white;
            text-align: center;
        }

        /* Navigation Bar */
        nav {
            background: #555;
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            flex-grow: 1;
            text-align: center;
            padding: 10px 0;
        }

        nav a:hover {
            background: #4CAF50;
            border-radius: 5px;
        }

        /* Main Content Styling */
        main {
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        /* Gray Section Blocks */
        .gray-section {
            background: #ddd;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }

        iframe {
            width: 100%;
            height: 300px;
            border: none;
        }

        /* About Us Styling */
        #about-us {
            background: #ddd;
            color: #333;
            text-align: center;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
        }

        #about-us h2 {
            color: #4CAF50;
            font-size: 2em;
            margin-bottom: 10px;
        }

        #about-us p {
            font-style: italic;
            font-size: 1.2em;
        }

        /* Contact & Styled Sections */
        #contact, #destinations, #related-content {
            background: #ddd;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            margin: 20px 0;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
        }

        /* Footer */
        footer {
            background: #333;
            color: #fff;
            text-align: center;
        }

        /* Image Styling */
        a img {
            width: 200px;
            height: auto;
            margin: 10px;
            border-radius: 10px;
            transition: transform 0.3s ease-in-out;
        }

        a img:hover {
            transform: scale(1.1);
        }
    </style>
</head>

<body id="top">
    <!-- Header -->
    <header>
        <h1>Welcome to AJ & Patrick's Travel Blog &#128640;</h1>
        <p>Your journey starts here! &#128507;</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#top">&#127968; Home</a>
        <a href="#about-us">&#128101; About Us</a>
        <a href="#contact">&#128231; Contact</a>
    </nav>

    <!-- Main Content -->
    <main>
        <!-- Why We Travel Section -->
        <section class="gray-section">
            <h2>&#128506; Why We Travel</h2>
            <p>We travel to explore new places, meet different people, and create unforgettable memories. The world is too big to stay in one place — let’s discover it together!</p>
        </section>

        <!-- Travel Inspiration Video -->
        <section class="gray-section">
            <h2>&#127909; Travel Inspiration Video</h2>
            <p>Get inspired for your next adventure:</p>
            <iframe src="https://www.youtube.com/embed/qLh99Cxb1e0" allowfullscreen></iframe>
        </section>

        <!-- School Location -->
        <section class="gray-section">
            <h2>&#128205; Our School Location</h2>
            <p>Here’s where we start our journey — Cebu Eastern College!</p>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d825.2537750382916!2d123.89602888434389!3d10.294529563842085!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x33a99bfcc60d650d:0x5ee73506c68dd233!2sCebu Eastern College!5e0!3m2!1sen!2sph!4v1648573911133!5m2!1sen!2sph" allowfullscreen></iframe>
        </section>
        <!-- About Us Section -->
        <section id="about-us">
            <h2>&#128101; About Us</h2>
            <p>We are AJ Cabuenas and John Patrick Villanueva, BSIT 1st-year students from Cebu Eastern College. We’re not just passionate about coding — we also love exploring new places, discovering new cultures, and making unforgettable memories along the way. Whether we’re building websites or traveling to new destinations, we’re always learning, growing, and chasing adventure together.

</p>
        </section>

        <!-- Clickable Travel Map (Styled) -->
        <section id="destinations">
            <h2>🌎 Clickable Travel Destinations</h2>
            <p>Explore our dream destinations:</p>

            <a href="https://www.google.com/maps/place/Boracay" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/8/8d/Boracay_White_Beach_Panorama.jpg" alt="Boracay Beach">
            </a>

            <a href="https://www.google.com/maps/place/Palawan" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/3d/Palawan_El_Nido_Beach.jpg" alt="Palawan Beach">
            </a>
        </section>
        
        <!-- Emoji List Section with Gray Color Block -->
        <section id="emoji-list" style="background: #ddd; padding: 15px; border-radius: 8px; text-align: center; margin: 20px 0; box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);">
    <h2>&#128515; Our Favorite Emojis</h2>
    <ul style="list-style: none; padding: 0;">
        <li>&#10024; - Sparkle</li>
        <li>&#9992; - Airplane</li>
        <li>&#127757; - Earth Globe</li>
        <li>&#127909; - Video Camera</li>
        <li>&#128205; - Location Pin</li>
    </ul>
</section>


        <!-- Related Content Section (Styled) -->
        <section id="related-content">
            <h2>📚 Related Content</h2>
            <p>Check out more travel content:</p>
            <ul>
                <li><a href="https://greatcontent.com/travel-content-ideas/" target="_blank">Travel Content Ideas for Beginners</a></li>
                <li><a href="https://crowdriff.com/resources/travel-content/" target="_blank">How to Create Engaging Travel Stories</a></li>
            </ul>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>&#128231; Contact Us</h2>
            <p>Email: <a href="mailto:cabuenasaj564@gmail.com">cabuenasaj564@gmail.com</a> | <a href="mailto:patrickvillanueva1422@gmail.com">patrickvillanueva1422@gmail.com</a></p>
        </section>
    </main>
    
    <!-- Back to Top Button -->
    <section style="text-align: center; margin-top: 20px;">
        <a href="#top" style="text-decoration: none; color: #4CAF50; font-weight: bold;">&#8679; Back to Top</a>
    </section>
    

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 AJ & Patrick’s Travel Blog. All Rights Reserved. &#127758;</p>
    </footer>
</body>
</html>

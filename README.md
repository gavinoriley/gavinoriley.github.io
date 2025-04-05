
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hamachi the Psychotic Killer</title>
    <link rel="icon" type="image/png" href="/assets/favicon-96x96.png">
    <style>
        /* Base Styles (unchanged) */
        body {
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        h2 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #ff0000;
        }

        p {
            font-size: 16px;
            line-height: 1.5;
        }

        .image-container {
            text-align: center;
            margin: 20px 0;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        .video-container {
            position: relative;
            padding-top: 56.25%;
            margin: 20px 0;
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        /* Button Container Styles */
        .button-container {
            display: flex;
            justify-content: center;
            gap: 20px; /* Space between buttons */
            margin: 20px 0;
        }

        .button-container a {
            display: inline-block;
        }

        /* Shift "Buy Now" button slightly to the left */
        .button-container .buy-now-link {
            margin-right: -10px; /* Moves "Buy Now" slightly left relative to the gap */
        }

        .button-container img {
            width: 200px;
            height: auto;
            transition: transform 0.3s ease;
        }

        .button-container img:hover {
            transform: scale(1.1);
            box-shadow: 0 0 10px #ff0000; /* Red glow on hover */
        }

        /* Footer and Media Queries (unchanged) */
        footer {
            border-top: 1px solid #333;
            text-align: center;
            padding: 20px 0;
            font-size: 12px;
        }

        @media (min-width: 768px) {
            #trailer, #gameplay {
                display: flex;
                align-items: center;
                gap: 20px;
            }

            #trailer .video-container, #gameplay .image-container {
                flex: 1;
            }

            #trailer p, #gameplay p {
                flex: 1;
            }
        }
    </style>
</head>
<body>
    <!-- Hero Section with Updated Buttons -->
    <header id="hero">
        <div class="image-container">
            <img src="/assets/WebHeader.jpg" alt="Hamachi Hero Graphic">
        </div>
        <div class="button-container">
            <a href="https://store.steampowered.com/app/3355690/Hamachi_the_Psychotic_Killer/" 
               target="_blank" 
               rel="noopener noreferrer" 
               class="buy-now-link">
                <img src="https://gavinoriley.github.io/assets/2buynow.png" alt="Buy Now Button">
            </a>
            <a href="https://store.steampowered.com/news/app/3355690" 
               target="_blank" 
               rel="noopener noreferrer">
                <img src="https://gavinoriley.github.io/assets/devlogbutton.png" alt="Devlog Button">
            </a>
        </div>
    </header>

    <!-- Main Content (unchanged) -->
    <main>
        <section id="about">
            <h2>What is this?</h2>
            <p>Hamachi the Psychotic Killer is a platformer game where you play as Hamachi, a once-ordinary person now possessed by a demon with the influenced goal to kill innocent civilians, flee from the police, and collect their souls to empower her demonic fury. Eventually to become strong enough to take over the entire world. Sounds very dramatic huh.</p>
        </section>
        <section id="trailer">
            <div class="video-container">
                <iframe src="https://www.youtube.com/embed/ltfQsrxRSUw?si=JsxZSltJGaohMLIy" title="Hamachi the Psychotic Killer Trailer" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
            <p>Here's a video of the game in action. This game is still in the early access phase, but you can try out the demo or buy the early access version to support me and see what's currently available for play.</p>
        </section>
        <section id="gameplay">
            <div class="image-container">
                <img src="https://gavinoriley.github.io/assets/mapselect.png" alt="Map Select Graphic">
            </div>
            <p>There are currently 3 worlds you can play! Oh, and did I mention the title screen uses your computer's internal clock to transition from day and night cycles? Because why not? (I'll update this website in time)</p>
        </section>
        <section id="end">
            <div class="image-container">
                <img src="https://gavinoriley.github.io/assets/brand-1.jpg" alt="End Graphic" class="transparent-gif">
            </div>
        </section>
    </main>

    <!-- Footer (unchanged) -->
    <footer>
        <p>Hamachi the Psychotic Killer © Gavin ORiley 2025</p>
    </footer>
</body>
</html>

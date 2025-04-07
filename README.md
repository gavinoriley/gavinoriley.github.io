<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hamachi the Psychotic Killer</title>
    <link rel="icon" type="image/png" href="/assets/favicon-96x96.png">
    <style>
        body {
            background-image:
                linear-gradient(to bottom, rgba(0,0,0,0.6) 0%, rgba(0,0,0,1) 100%),
                url('https://gavinoriley.github.io/assets/unibackground.png');
            background-size: cover;
            background-position: center;
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            cursor: url('/assets/sprCursor_3.png'), auto;
        }

        a {
            cursor: url('/assets/sprCursor_5.png'), auto;
            text-shadow: 1px 1px 2px black;
        }

        h2 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #ff0000;
            text-shadow: 1px 1px 2px black;
        }

        p {
            font-size: 16px;
            line-height: 1.5;
            text-shadow: 1px 1px 2px black;
        }

        .image-container {
            text-align: center;
            margin: 20px 0;
            background: none; /* No background on container */
        }

        img {
            max-width: 100%;
            height: auto;
            background: transparent; /* Ensure no default background */
            display: block; /* Remove inline spacing issues */
            margin: 0 auto; /* Center block-level images horizontally */
        }

        /* Specifically target the titlescreen image for transparency */
        #hero .image-container img {
            background: transparent !important; /* Force transparency */
        }

        /* Ensure brand-1.jpg stays centered */
        #end .image-container img {
            margin: 0 auto; /* Reinforce centering for brand-1.jpg */
        }

        /* Rest of your styles remain unchanged */
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

        .button-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }

        .button-container a {
            display: inline-block;
        }

        .button-container .buy-now-link {
            margin-right: -10px;
        }

        .button-container img {
            width: 200px;
            height: auto;
            transition: transform 0.3s ease;
        }

        .button-container img:hover {
            transform: scale(1.1);
            box-shadow: 0 0 10px #ff0000;
        }

        .demo-link {
            text-align: center;
            margin-top: 10px;
        }

        .demo-link a {
            color: white;
            font-size: 14px;
            text-decoration: none;
        }

        .demo-link a:hover {
            text-decoration: underline;
        }

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
    <header id="hero">
        <div class="image-container">
            <img src="/assets/TITLESCREEN.png" alt="Hamachi Hero Graphic">
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
        <div class="demo-link">
            <a href="https://itch.io/embed-upload/13285482?color=333333" 
               target="_blank" 
               rel="noopener noreferrer">
                or click here to play a scuffed (but free) demo online!
            </a>
        </div>
    </header>

    <main>
        <section id="about">
            <h2>What is this?</h2>
            <p>Hamachi the Psychotic Killer is a platformer game where you control Hamachi, a once-ordinary individual now possessed by a demon. Driven by the demon's influence, Hamachi must slaughter innocent civilians, evade the police, and fuel the demon's demonic fury through bloodshed. As the demon's power increases, it aims to fully dominate Hamachi's mind and use him to conquer the world. Pretty intense, huh?</p>
        </section>
        <section id="trailer">
            <div class="video-container">
                <iframe src="https://www.youtube.com/embed/ltfQsrxRSUw?si=JsxZSltJGaohMLIy" 
                        title="Hamachi the Psychotic Killer Trailer" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                        allowfullscreen>
                </iframe>
            </div>
            <p>Here's a video of the game in action. This game is still in the early access phase, but you can try out the demo or buy the early access version to support me while I continue to develop it.</p>
        </section>
        <section id="gameplay">
            <div class="image-container">
                <img src="https://gavinoriley.github.io/assets/mapselect.png" alt="Map Select Graphic">
            </div>
            <p>There are currently 3 worlds you can play! Oh, and did I mention the title screen uses your computer's internal clock to transition from day and night cycles? Because why not? (I'll update this website in time)</p>
        </section>
        <section id="end">
            <div class="image-container">
                <img src="https://gavinoriley.github.io/assets/brand-1.png" alt="End Graphic" class="transparent-gif">
            </div>
        </section>
    </main>

    <footer>
        <p>Hamachi the Psychotic Killer © Gavin ORiley 2025</p>
    </footer>
</body>
</html>

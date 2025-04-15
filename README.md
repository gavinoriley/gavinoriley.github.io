<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Official website for Hamachi the Psychotic Killer, a platformer game where you play as a demon-possessed killer.">
    <meta name="keywords" content="Hamachi the Psychotic Killer, indie game, 2D platformer, action game, horror game, early access, Steam, demo, pixel art, game development">
    <meta name="author" content="Gavin ORiley">
    <meta property="og:title" content="Hamachi the Psychotic Killer">
    <meta property="og:description" content="Official website for Hamachi the Psychotic Killer, a platformer game where you play as a demon-possessed killer.">
    <meta property="og:image" content="https://gavinoriley.github.io/assets/TITLESCREEN.png">
    <meta property="og:url" content="https://hamachithepsychotickiller.com">
    <meta property="og:type" content="website">
    <title>Hamachi the Psychotic Killer</title>
    <link rel="icon" type="image/png" href="/assets/favicon-96x96.png">
    <style>
        html {
            scroll-behavior: smooth;
        }

        body {
            background-image:
                linear-gradient(to bottom, rgba(0,0,0,0.6) 0%, rgba(0,0,0,1) 100%),
                url('https://gavinoriley.github.io/assets/blankhamachi_hero.png');
            background-size: cover;
            background-position: center;
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            padding-top: 50px;
            cursor: url('/assets/sprCursor_3.png'), auto;
            background-attachment: fixed;
            min-height: 100vh;
        }

        a {
            cursor: url('/assets/sprCursor_3.png'), auto;
            text-shadow: 1px 1px 2px black;
        }

        h2 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #ff0000;
            text-shadow: 1px 1px 2px black;
        }

        #about h2 {
            color: yellow;
        }

        p {
            font-size: 16px;
            line-height: 1.5;
            text-shadow: 1px 1px 2px black;
        }

        .image-container {
            text-align: center;
            margin: 20px 0;
            background: none;
        }

        #hero .image-container {
            margin-bottom: 40px;
        }

        img {
            max-width: 100%;
            height: auto;
            background: transparent;
            display: block;
            margin: 0 auto;
        }

        /* Force transparency for specific images */
        #hero .image-container img,
        .button-container img,
        #end .image-container img,
        .back-to-top img {
            background: transparent !important;
        }

        .video-container {
            text-align: center;
            margin: 20px 0;
        }

        .video-container iframe {
            width: 560px;
            height: 315px;
        }

        #trailer p {
            text-align: center;
            margin: 10px auto;
            max-width: 560px;
        }

        .button-container {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin: 40px 0;
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
            box-shadow: 0 0 10px #A100A1;
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

        .demo-link .itch-link {
            display: block; /* Ensures the new link appears below */
            margin-top: 5px; /* Small spacing between links */
        }

        .location-text {
            font-family: Arial, sans-serif;
            font-size: 14px;
            color: #808080;
            text-shadow: 1px 1px 2px black;
            margin: 10px 0 0 0;
            text-align: center;
        }

        .back-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 100;
            transform: translateY(100%);
            transition: transform 0.3s ease;
        }

        .back-to-top img {
            height: auto;
        }

        footer {
            border-top: 1px solid #333;
            text-align: center;
            padding: 20px 0;
            font-size: 12px;
        }

        footer a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        footer a:hover {
            text-decoration: underline;
        }

        @media (min-width: 768px) {
            #trailer {
                text-align: center;
            }

            #gameplay {
                display: flex;
                align-items: center;
                gap: 20px;
            }

            #gameplay .image-container {
                flex: 1;
            }

            #gameplay p {
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
                <img src="https://gavinoriley.github.io/assets/4buynow.png" alt="Buy Now Button">
            </a>
            <a href="https://store.steampowered.com/news/app/3355690" 
               target="_blank" 
               rel="noopener noreferrer">
                <img src="https://gavinoriley.github.io/assets/devlogbutton.png" alt="Devlog Button">
            </a>
        </div>
        <div class="demo-link">
            <a href="https://itch.io/embed-upload/13392253?color=333333" 
               target="_blank" 
               rel="noopener noreferrer">
                Play the HTML5 Edition online!
            </a>
            <a href="https://gavinoriley.itch.io/hamachithepsychotickiller" 
               target="_blank" 
               rel="noopener noreferrer" 
               class="itch-link">
                view the itch.io page
            </a>
        </div>
    </header>

    <main>
        <section id="about">
            <h2>What is this?</h2>
            <p>Hamachi the Psychotic Killer is a platformer game where you control Hamachi, a once-ordinary individual now possessed by a demon. Driven by the demon's influence, Hamachi must slaughter innocent civilians, evade the police, and fuel the demon's demonic fury through bloodshed. As the demon's power increases, it aims to fully dominate Hamachi's mind and use him to conquer the world. Pretty intense, huh?</p>
        </section>
        <section id="trailer">
            <div class="video-container" style="display: flex; align-items: center; justify-content: center; gap: 20px;">
                <img src="https://gavinoriley.github.io/assets/demon2.png" alt="Demon Left" style="max-height: 315px; width: auto; background: transparent !important;">
                <iframe src="https://www.youtube.com/embed/ltfQsrxRSUw?si=JsxZSltJGaohMLIy" 
                        title="Hamachi the Psychotic Killer Trailer" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                        allowfullscreen>
                </iframe>
                <img src="https://gavinoriley.github.io/assets/demon.png" alt="Demon Right" style="max-height: 315px; width: auto; background: transparent !important;">
            </div>
            <p>Here's a video of the game in action. This game is still in the early access phase, but you can try out the demo or buy the early access version to support me while I continue to develop it.</p>
        </section>
        <section id="gameplay">
            <div class="image-container">
                <img src="https://gavinoriley.github.io/assets/mapselect.png" alt="Map Select Graphic">
            </div>
            <p>There are 3 worlds available in early access! Oh, and did I mention the title screen uses your computer's internal clock to transition from day and night cycles? Because why not?</p>
        </section>
        <section id="end">
            <div class="image-container">
                <img src="https://gavinoriley.github.io/assets/brand-1.png" alt="End Graphic" class="transparent-gif">
                <p class="location-text">based in los angeles</p>
            </div>
        </section>
    </main>

    <footer>
        <p>Hamachi the Psychotic Killer © Gavin ORiley 2025</p>
        <p>
            <a href="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/3355690/manuals/cbeecc8fd965c68b6d64b82a593dafd5da4b0412/2hamachi-the-psychotic-killer-manual.pdf?t=1743916267" 
               target="_blank" 
               rel="noopener noreferrer">Game Manual</a>
            <a href="https://x.com/imgavinoriley" 
               target="_blank" 
               rel="noopener noreferrer">𝕏</a>
            <a href="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/3355690/manuals/4d24f19e6c5b25a41f86c5655abce55091d9eebc/hamachicube.pdf?t=1743916267" 
               target="_blank" 
               rel="noopener noreferrer">Hamachi Cube</a>
            <a href="https://imgur.com/a/T2g8AAt" 
               target="_blank" 
               rel="noopener noreferrer">Key Art</a>
            <a href="mailto:img.oriley@gmail.com?subject=Contact%20from%20Hamachi%20Website" 
               rel="noopener noreferrer" 
               title="Send an email to the developer">Contact</a>
        </p>
    </footer>
    <a href="#" class="back-to-top">
        <img src="/assets/sprnose.png" alt="Back to top">
    </a>

    <script>
        const backToTop = document.querySelector('.back-to-top');
        const triggerDistance = 200;

        function updateHandPosition() {
            const scrollPosition = window.scrollY;
            const viewportHeight = window.innerHeight;
            const documentHeight = document.documentElement.scrollHeight;
            const distanceToBottom = documentHeight - (scrollPosition + viewportHeight);

            let progress = 0;
            if (distanceToBottom < triggerDistance) {
                progress = Math.min(1, Math.max(0, (triggerDistance - distanceToBottom) / triggerDistance));
            }

            const translateY = (1 - progress) * 100;
            backToTop.style.transform = `translateY(${translateY}%)`;
        }

        window.addEventListener('scroll', updateHandPosition);
        updateHandPosition();
    </script>
</body>
</html>

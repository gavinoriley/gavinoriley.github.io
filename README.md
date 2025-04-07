<style>
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
        cursor: url('/assets/sprCursor_3.png'), auto;
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
        margin-bottom: 40px; /* Adjusted for more space */
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
    #end .image-container img {
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
        gap: 40px; /* Adjusted for more space between buttons */
        margin: 40px 0; /* Adjusted for more vertical space */
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

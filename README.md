<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Website</title>
    <style>
        /* CSS for the header */
        .header {
            background-color: #333; /* Dark background */
            padding: 1rem;
            position: fixed; /* Keeps header at top */
            top: 0;
            width: 100%;
            z-index: 1000; /* Ensures it stays on top */
        }

        .header a {
            color: white; /* Text color */
            text-decoration: none; /* Removes underline */
            margin: 0 15px; /* Spacing between buttons */
            font-family: Arial, sans-serif;
        }

        .header a:hover {
            color: #ddd; /* Hover effect */
        }

        /* Push content below header */
        body {
            margin: 0;
            padding-top: 60px; /* Adjust based on header height */
        }
    </style>
</head>
<body>
    <!-- Header with navigation -->
    <div class="header">
        <a href="#home">Home</a>
        <a href="#about">About</a>
    </div>

    <!-- Rest of your content -->
    <h1>Welcome to My Website</h1>
    <p>This is the main content.</p>
</body>
</html>

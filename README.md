<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Introductory Website</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 40px;
            line-height: 1.6;
            color: #333;
            overflow: hidden; /* Hide the overflowing content */
        }

        #video-background {
            position: fixed;
            right: 0;
            bottom: 0;
            min-width: 100%;
            min-height: 100%;
            width: auto;
            height: auto;
            z-index: -1; /* Place the video behind other elements */
        }

        header {
            background-color: transparent; /* Make the header transparent */
            color: #fff;
            padding: 1em;
            text-align: center;
            z-index: 1; /* Place the header above the video */
        }

        h1 {
            font-family: 'American Typewriter', serif; /* Change font for h1 */
        }

        section {
            margin: 2em 0;
            position: relative;
            z-index: 1;
            text-align: center;
            color: #fff;
        }

        .resume-button-container {
            text-align: center;
            margin-top: 30px;
            margin-bottom: 30px;
            position: relative;
            z-index: 1;
        }

        .resume-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #;
    color: #fff;
    text-decoration: none;
    border: 2px solid #fff; /* Add white border */
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s ease;
}

.resume-button:hover {
    background-color: #006400;
}


       nav {
    position: fixed;
    bottom: 20px;
    left: 0;
    right: 0;
    text-align: center;
    z-index: 1;
}

nav {
    position: fixed;
    bottom: 20px;
    left: 0;
    right: 0;
    text-align: center;
    z-index: 1;
}

nav a {
    display: inline-block;
    margin: 0 10px;
    text-decoration: none;
    color: #fff;
    background-color: ;
    padding: 10px 15px;
    border-radius: 15px;
    font-weight: bold;
    transition: background-color 0.3s ease;
}

nav a:hover {
    background-color: #0056b3;
}

footer {
    background-color: transparent;
    color: #fff;
    text-align: center;
    padding: 1em;
    position: fixed;
    bottom: 0;
    right: 0; /* Align to the right */
    margin-bottom: 20px; /* Adjusted margin to create space between nav and footer */
    z-index: 1;
}



        nav img {
            max-height: 30px;
            vertical-align: middle;
        }
/* ... (existing styles) */

section {
    margin: 2em 0;
    position: relative;
    z-index: 1;
    text-align: center;
    color: #fff;
    opacity: 0; /* Set initial opacity to 0 */
    animation: fadeIn 1s ease-in-out 1.0s forwards; /* Animation properties */
}

/* ... (existing styles) */

@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}


    </style>
</head>

<body>
    <video id="video-background" autoplay muted loop>
        <source src="https://github.com/suhaspanuganti/suhaspanuganti.github.io/raw/main/page_background.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <header>
        <h1>My Introduction Website</h1>
    </header>

    <section>
        <img src="your-image.jpg" alt="Description of your image" class="introduction-image">
        <h2>Welcome to My Professional Website</h2>
        <p>This website is designed to showcase my professional portfolio and achievements. Feel free to explore!</p>
    </section>

    <div class="resume-button-container">
        <a href="https://github.com/suhaspanuganti/suhaspanuganti.github.io/blob/main/Suhas_Resume.pdf" target="_blank"
            class="resume-button">Download Resume</a>
    </div>

    <nav>
        <a href="https://www.linkedin.com/in/suhaskumar2308/" target="_blank"><img
                src="https://www.freepnglogos.com/uploads/linkedin-logo-hd-png-3.png" alt="LinkedIn Logo"></a>
        <a href="https://discord.gg/my3UXRwESB" target="_blank"><img
                src="https://logos-world.net/wp-content/uploads/2020/12/Discord-Logo.png" alt="Discord Logo"></a>
        <a href="mailto:chintusuhas2308@gmail.com" style="max-height: 40px;"><img
                src="https://www.logolynx.com/images/logolynx/64/64319177556c729f1806922bcd3adef5.png"
                alt="Gmail Logo"></a>
    </nav>

    <footer>
        &copy; 2024 Suhas Panuganti. All rights reserved
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            var video = document.getElementById('video-background');
            video.play();
        });
    </script>
</body>

</html>

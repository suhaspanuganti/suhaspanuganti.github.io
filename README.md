<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suhas Panuganti</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 40px;
            line-height: 1.6;
            color: #333;
            overflow: auto;
        }

        #video-background {
            position: fixed;
            right: 0;
            bottom: 0;
            min-width: 100%;
            min-height: 100%;
            width: auto;
            height: auto;
            z-index: -1;
        }

        header {
            background-color: transparent;
            color: #fff;
            padding: 1em;
            text-align: center;
            z-index: 1;
        }

        h1 {
            font-family: 'American Typewriter', serif;
            font-size: 3em;
            color: #fff;
            opacity: 0;
            position: relative;
            z-index: 1;
            display: inline-block;
            animation: fadeIn 1.0s ease-in-out 0.7s forwards;
        }

        h1::before {
            content: attr(data-text);
            position: absolute;
            top: 0;
            left: 0;
            z-index: -1;
            color: #000;
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            display: inline-block;
            border: 2px solid #fff; /* White outline */
            box-sizing: border-box;
            width: 0px;
            height: 0px;
            opacity: 0;
            animation: fadeIn 1s ease-in-out 1s forwards; /* Fade-in animation with 1s duration at 1s */
        }

        section {
            margin: 2em 0;
            position: relative;
            z-index: 1;
            text-align: center;
            color: #fff;
            opacity: 0;
            animation: fadeIn 1s ease-in-out 1.5s forwards;
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
            border: 2px solid #fff;
            border-radius: 5px;
            font-weight: bold;
            opacity: 0;
            animation: fadeIn 1s ease-in-out 2.7s forwards;
            transition: background-color 0.3s ease;
        }

        .resume-button:hover {
            background-color: #006400;
        }

        nav {
            position: fixed;
            bottom: -50px;
            left: 0;
            right: 0;
            text-align: center;
            z-index: 1;
            transition: bottom 0.5s ease;
        }

        nav.show {
            bottom: 20px;
        }

        nav a {
            display: inline-block;
            margin: 0 10px;
            text-decoration: none;
            color: #fff;
            padding: 5px 5px;
            border-radius: 10px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        nav a:hover {
            background-color: #0056b3;
        }

        .contact-header {
            color: #fff; /* White color */
            font-size: 1.0em;
            opacity: 0;
            animation: fadeIn 1s ease-in-out 3.0s forwards; /* Fade-in animation with 1s duration at 3.0s */
            margin-bottom: 20px; /* Added margin to move "Contact me" down */
        }

        footer {
            background-color: transparent;
            color: #fff;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            right: 0;
            margin-bottom: 20px;
            z-index: 1;
            opacity: 0;
            animation: fadeIn 1s ease-in-out 4.0s forwards;
        }

        nav img {
            max-height: 30px;
            vertical-align: middle;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        .leftt-text {
            text-align: left;
        }

        /* Blank space after the Download Resume button */
        .space-after-resume {
            height: 25vh; /* Adjust the height as needed */
        }

        /* Styling for the introduction image */s
        .introduction-image {
    max-width: 28%;
    height: auto;
    border-radius: 10px; /* Optional: Add border-radius for a rounded look */}

}
.midtext-text{
font-size: 1.5em;
text-align:center  ;
        }
.italic-text {
    font-style: italic;
}
 .nav-container {
        position: fixed;
        bottom: -50px;
        left: 0;
        right: 0;
        text-align: center;
        z-index: 1;
        transition: bottom 0.5s ease;
    }

    .nav-container.show {
        bottom: 20px;
    }
    </style>
</head>

<body>
    <video id="video-background" autoplay muted loop>
        <!-- Empty source tag for the first video -->
        <source src="" type="video/mp4"
            data-video-source="https://github.com/suhaspanuganti/suhaspanuganti.github.io/raw/main/page_background.mp4">
        <!-- Empty source tag for the second video -->
        <source src="" type="video/mp4"
            data-video-source="https://github.com/suhaspanuganti/suhaspanuganti.github.io/raw/main/page_background2.mp4">
    </video>

    <header>
        <h1 data-text="Suhas Panuganti">Suhas Panuganti</h1>
    </header>

    <section>
        <img src="https://raw.githack.com/suhaspanuganti/suhaspanuganti.github.io/main/graduation_day_main_png.jpg"
     alt="Description of your image" class="introduction-image">

        <h2>Welcome to Suhas Panuganti's World of Technology and Beyond!
        </h2>
        <p class="leftt-text">
<p class = "italic-text">Greetings and a hearty welcome to my digital haven! I am Suhas Panuganti, currently navigating the realm of academia while pursuing my master's degree at Old Dominion University. Originally from the vibrant city of Hyderabad, India, my academic expedition took a significant turn when I completed my Bachelor's in Computer Science and Engineering in July 2023.</p><br>

<p class="midtext-text">Tech Enthusiast and Explorer</p>

<p class = "italic-text">My passion for technology is boundless, spanning from the captivating landscapes of Virtual Reality and the allure of Holograms to the intricacies of Data Science, Cybersecurity, Machine Learning, Deep Learning, and Artificial Intelligence. Within the ever-evolving field of computer science, I've explored the depths of Computer Networks, Operating Systems, and Compiler Designs. Operating systems like Windows, Linux Sushi, Linux Ubuntu, Kali Linux, and Mac have been part of my hands-on journey.</p><br>

<p class="midtext-text">Sporting Spirit </p>

<p class = "italic-text">Beyond the lines of code, my history in sports is rich. Serving as the captain of the college soccer team for two years during my undergraduate journey, I imbibed the values of leadership, teamwork, and resilience. Cricket, a passion that transcends mere gameplay, fuels my competitive spirit.</p><br>

<p class="midtext-text">Broad Intellectual Curiosity</p>

<p class = "italic-text">My intellectual pursuits extend beyond the binary code. Engaging in discussions on philosophy, history, and sports provides constant joy. The exploration of intricate worlds, including chemistry, physics, economics, and political science, adds depth to my curiosity.</p><br>

<p class="midtext-text">Nature Enthusiast</p>

<p class = "italic-text">Amidst the pixels and algorithms, I find solace in nature. An avid traveler, hiker, and camper, I seek adventure in the great outdoors. Exploring diverse landscapes, witnessing the wonders of nature, and camping under the star-lit sky are experiences that fuel my soul.</p><br>

<p class="midtext-text">Leisure and Relaxation</p>

<p class = "italic-text">When it's time to unwind, you'll often find me immersed in the world of online games or exploring the exciting universe of esports. The digital playground provides a different kind of thrill and strategy that complements my tech-centric interests.</p><br>

<p class="midtext-text">Connect with Me</p>

<p class = "italic-text">Feel free to connect with me on social media to continue these conversations. For a detailed overview of my academic journey, projects, internships, and work experience, download my resume. Let's embark on this exciting journey together, where technology meets sports, philosophy intertwines with code, and curiosity knows no boundaries!

Thank you for visiting, and I look forward to connecting with you in this digital space!</p></p>
    </section>

    <div class="resume-button-container">
        <a href="https://github.com/suhaspanuganti/suhaspanuganti.github.io/blob/main/Suhas_Resume.pdf"
            target="_blank" class="resume-button">Download Resume</a>
    </div>

    <!-- Blank space after the Download Resume button -->
    <div class="space-after-resume"></div>

   <div class="nav-container">
    <nav>
        <p class="contact-header">Contact me @</p>
        <a href="https://www.linkedin.com/in/suhaskumar2308/" target="_blank"><img
                src="https://www.freepnglogos.com/uploads/linkedin-logo-hd-png-3.png" alt="LinkedIn Logo"></a>
        <a href="https://discord.gg/my3UXRwESB" target="_blank"><img
                src="https://logos-world.net/wp-content/uploads/2020/12/Discord-Logo.png" alt="Discord Logo"></a>
        <a href="mailto:chintusuhas2308@gmail.com" style="max-height: 40px;"><img
                src="https://www.logolynx.com/images/logolynx/64/64319177556c729f1806922bcd3adef5.png"
                alt="Gmail Logo"></a>
    </nav>
</div>

    <footer>
        &copy; 2024 Suhas Panuganti. All rights reserved
    </footer>

     <script>
        document.addEventListener('DOMContentLoaded', function () {
            var video = document.getElementById('video-background');
            var sources = video.getElementsByTagName('source');
            // Randomly choose one of the video sources
            var randomIndex = Math.floor(Math.random() * sources.length);
            video.src = sources[randomIndex].getAttribute('data-video-source');
            video.play();
        });

        window.onscroll = function () {
            var body = document.body,
                html = document.documentElement;

            var height = Math.max(body.scrollHeight, body.offsetHeight,
                html.clientHeight, html.scrollHeight, html.offsetHeight);

            if (window.innerHeight + window.scrollY >= height-50) {
                // Scrolled to the end of the page
                document.querySelector('nav').classList.add('show');
            } else {
                document.querySelector('nav').classList.remove('show');
            }
        };
    </script>

</html>

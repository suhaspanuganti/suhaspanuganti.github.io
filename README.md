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
            background: url('https://th.bing.com/th/id/R.ea80e8bcf70c0a180cdc6905afb3f1c1?rik=AOnT7YkygFDSYg&riu=http%3a%2f%2fbackgroundcheckall.com%2fwp-content%2fuploads%2f2017%2f12%2fwebsite-background-design.jpg&ehk=wPsIeo20SzI7GQwdyLJG6CMUKL9Awn4f6CnGiNdUxJg%3d&risl=&pid=ImgRaw&r=0') center center fixed; /* Set background image */
            background-size: cover; /* Cover the entire viewport */
        }

        header {
            background-color: #007BFF;
            color: #fff;
            padding: 1em;
            text-align: center;
        }

        h1 {
            font-family: 'American Typewriter', serif; /* Change font for h1 */
        }

        h2 {
            color: #000000; /* Set color for h2 */
        }

        h3,
        h4,
        h5,
        h6 {
            color: #fff; /* White text color for headings */
            transition: color 0.3s ease; /* Hover effect transition */
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #f4f4f4;
            padding: 1em;
        }

        nav a {
            margin: 0 1em;
            text-decoration: none;
            color: #000; /* Black text color for links */
            background-color: #fff; /* White background color for links */
            padding: 5px 5px;
            border: none; /* Black border for button-like appearance */
            border-radius: 15px;
            font-weight: bold;
            display: inline-block; /* Make them inline-block elements */
            transition: color 0.3s ease, background-color 0.3s ease, border-color 0.3s ease; /* Hover effect transition */
        }

        nav a:hover {
            color: #fff; /* Hover text color for links */
            background-color: #007BFF; /* Hover background color for links */
            border-color: #007BFF; /* Hover border color for links */
        }

        section {
            margin: 2em 0;
        }

        .resume-button-container {
            text-align: center; /* Center the button */
            margin-top: 30px; /* Add space above the button */
            margin-bottom: 30px; /* Add space below the button */
        }

        .resume-button {
            display: inline-block; /* Inline block instead of block */
            padding: 10px 20px;
            background-color: #008000; /* Green button color */
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold; /* Bold font */
            transition: background-color 0.3s ease; /* Button hover effect transition */
        }

        .resume-button:hover {
            background-color: #006400; /* Darker green on hover */
        }

        footer {
            background-color: #007BFF;
            color: #fff;
            text-align: center;
            padding: 1em;
        }

        nav img {
            max-height: 30px; /* Adjust the max height as needed */
            vertical-align: middle; /* Align the image vertically within the line */
        }
    </style>
</head>

<body>

    <header>
        <h1>My Introduction Website</h1>
    </header>

    <section>
        <img src="your-image.jpg" alt="Description of your image" class="introduction-image">
        <h2>Welcome to My Professional Website</h2>
        <p>This website is designed to showcase my professional portfolio and achievements. Feel free to explore!</p>
    </section>

    <div class="resume-button-container">
        <a href="https://github.com/suhaspanuganti/suhaspanuganti.github.io/blob/main/Suhas_Resume.pdf" target="_blank" class="resume-button">Download Resume</a>
    </div>

    <nav>
        <a href="https://www.linkedin.com/in/suhaskumar2308/" target="_blank"><img src="https://www.freepnglogos.com/uploads/linkedin-logo-transparent-png-25.png" alt="LinkedIn Logo"></a>
        <a href="https://discord.gg/my3UXRwESB" target="_blank"><img src="https://logos-world.net/wp-content/uploads/2020/12/Discord-Logo.png" alt="Discord Logo"></a>
        <a href="mailto:chintusuhas2308@gmail.com" style="max-height: 40px;"><img src="https://th.bing.com/th/id/OIP.A1l20wxJwyPkNcoFkBWb_wHaHa?w=198&h=198&c=7&r=0&o=5&pid=1.7" alt="Gmail Logo"></a>
    </nav>

    <footer>
        &copy; 2024 Suhas Panuganti. All rights reserved
    </footer>

</body>

</html>

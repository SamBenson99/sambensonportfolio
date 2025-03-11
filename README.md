    <Old Layout>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Portfolio - Sam Benson</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>


 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=2.0">
    <title>Home</title>
</head>
<body>

    <h1>Welcome to My Website</h1>  


  <!-- About Me Section -->
  <section id="about">
    <div class="section-bg" style="background-image: url('images/about-bg.jpg');">
      <h2>About Me</h2>
      <p>Hello, I'm Sam. I'm a video editor, videographer, and 3D artist. Take a look at my work!</p>
    </div>
  </section>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <h1 style="text-align: center;">My Portfolio</h1>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Button with Rollover Effect</title>
    <link rel="stylesheet" href="styles.css"> <!-- If you are using an external CSS file -->
    <style>
        /* General body styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center; /* Center the content horizontally */
            align-items: center; /* Center the content vertically */
            height: 100vh; /* Full viewport height */
        }

        /* Container for the rows of buttons */
        .button-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center; /* Center buttons horizontally */
            gap: 10px;
            width: 90%; /* Center the buttons with margins on the left and right */
            max-width: 1200px; /* Optional max width to prevent buttons from stretching too wide */
        }

        /* Styles for each button */
        .button {
            position: relative;
            width: 48%; /* Two buttons per row */
            height: 33.33vh; /* Set button height to 1/3 of the viewport height */
            padding: 15px 20px;
            text-align: center;
            font-size: 18px;
            text-decoration: none;
            display: block;
            border: 2px solid transparent;
            border-radius: 8px;
            background-size: cover;
            background-position: center;
            color: white;
            overflow: hidden;
            transition: background-image 0.3s ease-in-out;
        }

        /* Hover effect for changing the background image */
        .button:hover {
            background-image: url('https://raw.githubusercontent.com/sambenson99/sambensonportfolio/main/images/tedst.png');
        }

        /* Text on top of the image */
        .button-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 24px;
            font-weight: bold;
            color: white;
            z-index: 1;
        }

    </style>
</head>
<body>

  
    <!-- Grid container for buttons -->
    <div class="button-grid">
        <!-- Button 1 -->
        <a href="my-showreel.html" class="button" id="button1">
            <span class="button-text">Showreel</span>
        </a>

        <!-- Button 2 -->
        <a href="personal-3d-artwork.html" class="button" id="button2">
            <span class="button-text">Personal 3D Projects</span>
        </a>

        <!-- Button 3 -->
        <a href="freelance-projects.html" class="button" id="button3">
            <span class="button-text">Freelance projects</span>
        </a>

        <!-- Button 4 -->
        <a href="personal-projects.html" class="button" id="button4">
            <span class="button-text">Personal Video Projects</span>
        </a>
    </div>

</body>
</html>


  <!-- Contact Me Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>You can reach out to me through the following platforms:</p>
    <ul class="social-links">
      <li><a href="https://www.instagram.com/sambensonvideo" target="_blank">Instagram</a></li>
      <li><a href="https://www.tiktok.com/@blendson" target="_blank">TikTok</a></li>
      <li><a href="mailto:samuelbenson@hotmail.com">Email Me</a></li>
    </ul>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Sam Benson. All rights reserved.</p>
  </footer>

</body>
</html>


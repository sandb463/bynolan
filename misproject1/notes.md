Project Setup
Step 1: Create Your Project Folder Structure
my-website/
├── index.html          (Home Page)
├── hobbies.html        (Hobbies Page)
├── discover.html       (UMD & Duluth Page)
├── resume.html         (Resume Page)
├── career.html         (Career Interests Page)
├── game.html           (Interactive Game Page)
├── css/
│   └── style.css       (Your main stylesheet)
├── js/
│   └── script.js       (Your JavaScript file)
│   └── game.js         (Game JavaScript - from team)
├── images/
│   └── (all your photos and images)
├── videos/
│   └── welcome.mp4     (Your welcome video)
│   └── umd-video.mp4   (Team UMD video)
└── files/
    └── resume.pdf      (Downloadable PDF resume)
Step 2: Set Up Basic HTML Template
Every page should start with this structure:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Page Title</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Navigation Menu (same on all pages) -->
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="hobbies.html">Hobbies</a></li>
            <li><a href="discover.html">Discover UMD</a></li>
            <li><a href="resume.html">Resume</a></li>
            <li><a href="career.html">Career</a></li>
            <li><a href="game.html">Game</a></li>
        </ul>
    </nav>

    <!-- Your page content goes here -->
    <main>
        <!-- Page-specific content -->
    </main>

    <!-- Footer (same on all pages) -->
    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>

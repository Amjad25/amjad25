<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amjad Ali Khan - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 40px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header h2 {
            margin: 10px 0;
            font-size: 1.5rem;
            color: #555;
        }
        .contact {
            text-align: center;
            margin: 20px 0;
        }
        .contact a {
            color: #0891b2;
            text-decoration: none;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            background-color: #fff;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .card:hover {
            transform: scale(1.02);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        .card img {
            width: 100%;
            height: auto;
        }
        .card-content {
            padding: 16px;
        }
        .card-content h3 {
            margin: 0;
            color: #333;
        }
        .card-content p {
            margin: 8px 0 0;
            color: #555;
        }
        .skills, .badges {
            margin: 40px 0;
        }
        .skills img, .badges img {
            margin: 5px;
        }
        .badges img {
            max-width: 100%;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Amjad Ali Khan</h1>
            <h2>Mobile Application Developer</h2>
            <p>Passionate Mobile App Developer, Developing Optimized Robust Apps with Flutter.</p>
        </header>

        <div class="contact">
            <p>
                <strong>•</strong> 🌍  I'm based in Pakistan <br>
                <strong>•</strong> ✉️ You can contact me at <a href="mailto:amjad.alikhan2025@gmail.com">amjad.alikhan2025@gmail.com</a> <br>
                <strong>•</strong> ✉️ Visit my <a href="https://transparent-kryptops-f94.notion.site/Amjad-s-Portfolio-4d430d90691344cfada932aff5912e7b">Portfolio</a> <br>
                <strong>•</strong> 🧠 I'm learning Next.JS
            </p>
            <a href="https://www.x.com/amjad25" target="_blank" rel="noreferrer">
                <img src="https://img.shields.io/twitter/follow/amjad25?logo=twitter&style=for-the-badge&color=0891b2&labelColor=1c1917" />
            </a>
        </div>

        <section>
            <h2>Featured Work</h2>
            <div class="grid">
                <a href="https://transparent-kryptops-f94.notion.site/AnaMee-Cross-Platform-Mobile-App-Complete-Solution-For-Health-Care-9d132e7129e24255a210879dcdafbcdb?pvs=25" class="card">
                    <img src="https://transparent-kryptops-f94.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F66b9e74c-cd78-4f34-8d36-c308af73a487%2Fd2f36e7b-8e3a-4e5a-938c-9e0cd8d9477f%2FScreenshot_2024-11-17_130323.png?table=block&id=141d9cd0-9fc4-80c2-b634-c94bc459546b&spaceId=66b9e74c-cd78-4f34-8d36-c308af73a487&width=1380&userId=&cache=v2" alt="AnaMee">
                    <div class="card-content">
                        <h3>AnaMee Cross-Platform Mobile App</h3>
                        <p>Complete Solution For Health Care</p>
                    </div>
                </a>
                <a href="#" class="card">
                    <img src="image2.png" alt="PETTO">
                    <div class="card-content">
                        <h3>PETTO Cross-Platform Mobile App</h3>
                        <p>An All-In-One App For Pet Lovers</p>
                    </div>
                </a>
                <a href="#" class="card">
                    <img src="image3.png" alt="Book Tracker">
                    <div class="card-content">
                        <h3>Book Tracker Reading Log</h3>
                        <p>Offline-First Cross-Platform App</p>
                    </div>
                </a>
            </div>
        </section>

        <section class="skills">
            <h2>Skills</h2>
            <div>
                <img src="dart.svg" alt="Dart" width="50" height="50">
                <img src="python.svg" alt="Python" width="50" height="50">
                <img src="flutter.svg" alt="Flutter" width="50" height="50">
            </div>
        </section>

        <section class="badges">
            <h2>Badges</h2>
            <div>
                <img src="github-stats.png" alt="GitHub Stats">
                <img src="github-streak.png" alt="GitHub Streak">
                <img src="github-graph.png" alt="GitHub Commits Graph">
            </div>
        </section>
    </div>
</body>
</html>

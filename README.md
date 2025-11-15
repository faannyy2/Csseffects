<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS Effects Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>CSS Effects Page</h1>
        <p>This page shows a few simple CSS effects on an image, a button, and a link.</p>
    </header>

    <main>
        <!-- Image with a hover zoom effect -->
        <section class="card">
            <h2>Image Effect</h2>
            <p>Hover over the image to see the zoom effect.</p>
            <!-- Make sure you have a picture named sample-image.jpg in the same folder -->
            <img src="sample-image.jpg" alt="Fashion outfit on a table" class="image-effect">
        </section>

        <!-- Button with a wiggle animation on hover -->
        <section class="card">
            <h2>Button Effect</h2>
            <p>Hover over the button to see the wiggle animation.</p>
            <button class="btn-effect">Hover Me</button>
        </section>

        <!-- Link to Zara with orange hover color -->
        <section class="card">
            <h2>Link Hover Effect</h2>
            <p>
                This is the Zara website link I used in this week’s discussion.
                Hover over it to see the hover color change:
            </p>
            <a class="zara-link" href="https://www.zara.com" target="_blank" rel="noopener">
                Visit Zara Website
            </a>
        </section>
    </main>

    <footer>
        <p>Created for CIS HTML/CSS assignment: CSS effects practice.</p>
    </footer>
</body>
</html>
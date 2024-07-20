# CRKVideoEditor
#index.html
#styles.css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CRK Video Editor</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>CRK Video Editor</h1>
        <nav>
            <ul>
                <li><a href="#trim">Trim</a></li>
                <li><a href="#merge">Merge</a></li>
                <li><a href="#filters">Filters</a></li>
                <li><a href="#transitions">Transitions</a></li>
                <li><a href="#audio">Audio</a></li>
                <li><a href="#export">Export</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="trim">
            <h2>Trim</h2>
            <p>Cut and trim your videos with ease.</p>
        </section>
        <section id="merge">
            <h2>Merge</h2>
            <p>Combine multiple video clips into one.</p>
        </section>
        <section id="filters">
            <h2>Filters</h2>
            <p>Add filters to enhance your video.</p>
        </section>
        <section id="transitions">
            <h2>Transitions</h2>
            <p>Apply transitions between clips.</p>
        </section>
        <section id="audio">
            <h2>Audio</h2>
            <p>Edit and enhance audio tracks.</p>
        </section>
        <section id="export">
            <h2>Export</h2>
            <p>Export your final video in various formats.</p>
        </section>
    </main>
    <footer>
        <p>Check out our GitHub repository: <a href="https://github.com/yourusername/CRKVideoEditor" target="_blank">CRKVideoEditor</a></p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 2rem;
    max-width: 800px;
    margin: 0 auto;
}

section {
    background-color: white;
    margin-bottom: 1.5rem;
    padding: 1rem;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

section h2 {
    margin-top: 0;
}

footer {
    text-align: center;
    padding: 1rem 0;
    background-color: #333;
    color: white;
    position: fixed;
    width: 100%;
    bottom: 0;
}

footer a {
    color: #61dafb;
    text-decoration: none;
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARfixHelper</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>CARfixHelper 🚗🛠️</h1>
        <p>Your DIY car repair assistant</p>
    </header>

    <main>
        <section>
            <h2>Enter Your Car Problem</h2>
            <input type="text" id="symptomInput" placeholder="e.g. engine won't start">
            <button onclick="lookupIssue()">Get Help</button>
            <div id="results"></div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Atahan Ors – Built for Lewis University Project</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

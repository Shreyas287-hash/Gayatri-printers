
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #0073e6;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        nav {
            background-color: #005bb5;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        main {
            padding: 20px;
        }
        footer {
            background-color: #0073e6;
            color: white;
            padding: 10px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
            background-color: #0073e6;
            color: white;
            border: none;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background-color: #005bb5;
        }
    </style>
</head>
<body>
    <header>Welcome to My Website</header>
    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
    <main>
        <h1>Hello, World!</h1>
        <p>This is a simple website using HTML, CSS, and JavaScript.</p>
        <button onclick="showMessage()">Click Me</button>
        <p id="message"></p>
    </main>
    <footer>&copy; 2025 My Website</footer>
    <script>
        function showMessage() {
            document.getElementById('message').innerText = "You clicked the button!";
        }
    </script>
</body>
</html>

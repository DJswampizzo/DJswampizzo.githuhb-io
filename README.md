# DJswampizzo.githuhb-io
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的 GitHub Pages 網站</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="assets/logo.png" alt="網站 Logo" class="logo">
        <h1>歡迎來到我的網站！</h1>
    </header>

    <main>
        <section>
            <h2>關於我</h2>
            <p>這是一個使用 GitHub Pages 架設的簡單網站。</p>
        </section>

        <section>
            <h2>我的專案</h2>
            <ul>
                <li><a href="#">專案 1</a></li>
                <li><a href="#">專案 2</a></li>
                <li><a href="#">專案 3</a></li>
            </ul>
        </section>

        <button id="clickMe">點我！</button>
    </main>

    <footer>
        <p>&copy; 2023 我的網站</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #007bff;
    color: white;
    padding: 20px;
    text-align: center;
}

header .logo {
    width: 100px;
    height: auto;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

h2 {
    color: #007bff;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    background-color: white;
    margin: 5px 0;
    padding: 10px;
    border-radius: 5px;
}

button {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

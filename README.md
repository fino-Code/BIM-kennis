<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documentation Site</title>
    <style>
        body {
            display: flex;
            min-height: 100vh;
            flex-direction: column;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        #sidebar {
            flex: 0 0 200px;
            background: #f4f4f4;
            padding: 20px;
            height: 100vh;
            overflow: auto;
        }
        #main-content {
            flex: 1;
            padding: 20px;
        }
        a {
            display: block;
            padding: 10px 0;
            color: #000;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .container {
            display: flex;
            flex: 1;
        }
    </style>
</head>
<body>
    <header>
        <h1>Project Documentation</h1>
    </header>
    <div class="container">
        <nav id="sidebar">
            <a href="#introduction">Introduction</a>
            <a href="#installation">Installation</a>
            <a href="#configuration">Configuration</a>
            <a href="#usage">Usage</a>
            <a href="#contributing">Contributing</a>
        </nav>
        <div id="main-content">
            <section id="introduction">
                <h2>Introduction</h2>
                <p>This section introduces the project and gives an overview of its features.</p>
            </section>
            <section id="installation">
                <h2>Installation</h2>
                <p>Details on how to install the project.</p>
            </section>
            <section id="configuration">
                <h2>Configuration</h2>
                <p>How to configure the project settings.</p>
            </section>
            <section id="usage">
                <h2>Usage</h2>
                <p>Instructions on how to use the project after installation.</p>
            </section>
            <section id="contributing">
                <h2>Contributing</h2>
                <p>Guidelines for contributing to the project.</p>
            </section>
        </div>
    </div>
    <footer>
        <p style="text-align:center; margin-top:20px;">&copy; 2024 Documentation Template</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Deeper Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
        }
        nav {
            background-color: #555;
            padding: 0.5em;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 0.5em;
            margin: 0 1em;
        }
        main {
            margin: 20px;
            padding: 20px;
            background-color: #fff;
        }
        footer {
            text-align: center;
            padding: 1em;
            background-color: #555;
            color: #fff;
        }
        form {
            text-align: left;
            max-width: 400px;
            margin: 0 auto;
        }
        input, textarea {
            width: 100%;
            padding: 0.5em;
            margin-bottom: 1em;
            box-sizing: border-box;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Deeper Website</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
    <main>
        <section>
            <h2>Welcome to Your Deeper Website</h2>
            <p>This is a more detailed webpage. Customize the content based on your needs.</p>
            <img src="https://placekitten.com/800/400" alt="Cute Kittens">
        </section>
        <section>
            <h2>About Us</h2>
            <p>We are a team dedicated to creating awesome websites and providing valuable content.</p>
        </section>
        <section>
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Deeper Website. All rights reserved.</p>
    </footer>
</body>
</html>

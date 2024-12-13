<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Movie Site</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
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
                }

        main {
            padding: 20px;
        }

        h2 {
            text-align: center;
            color: #333;
        }

        .movie-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .movie-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            width: 200px;
            text-align: center;
            overflow: hidden;
        }

            .movie-card img {
                width: 100%;
                height: auto;
            }

            .movie-card h3 {
                margin: 10px 0 5px;
            }

            .movie-card p {
                font-size: 14px;
                color: #555;
                padding: 0 10px 10px;
            }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Welcome to My Movie Site</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#movies">Movies</a></li>
                <li><a href="#about">About</a></li>
            </ul>
        </nav>
    </header>

    <!-- Movie Section -->
    <main id="movies">
        <h2>Featured Movies</h2>
        <div class="movie-container">
            <!-- Movie Card 1 -->
            <div class="movie-card">
                <img src="https://www.bing.com/images/search?q=into%20the%20badlands%20images&FORM=IQFRBA&id=4D058DFA7E384B01B720AB5E3BF28257B1621761" alt="Into the Badlands">
                <h3>Into the Badlands</h3>
                <p>An action-packed series with incredible martial arts choreography.</p>
            </div>

            <!-- Movie Card 2 -->
            <div class="movie-card">
                <img src="images/movie2.jpg" alt="Movie 2">
                <h3>Movie Title 2</h3>
                <p>A short description of Movie 2.</p>
            </div>

            <!-- Movie Card 3 -->
            <div class="movie-card">
                <img src="images/movie3.jpg" alt="Movie 3">
                <h3>Movie Title 3</h3>
                <p>A short description of Movie 3.</p>
            </div>
        </div>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 My Movie Site</p>
    </footer>
</body>
</html>

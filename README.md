<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Find Your Dream Car</title>
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
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            padding: 20px;
            text-align: center;
        }
        .container h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        .container p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }
        .reviews {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .review-item {
            background-color: #fff;
            padding: 20px;
            margin: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 30%;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Find Your Dream Car</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">New Cars</a>
        <a href="#">Used Cars</a>
        <a href="#">Compare Cars</a>
        <a href="#">Car Reviews</a>
        <a href="#">Sell Your Car</a>
    </nav>
    <div class="container">
        <h1>FIND YOUR DREAM CAR</h1>
        <p>Explore our wide range of new and used cars. Compare models and read reviews to find the perfect car for you.</p>
        <div class="reviews">
            <div class="review-item">
                <h2>NEWCARS</h2>
                <p>Discover the latest models and features.</p>
            </div>
            <div class="review-item">
                <h2>CAR REVIEWS</h2>
                <p>Read expert reviews and user opinions.</p>
            </div>
            <div class="review-item">
                <h2>COMPARE NOW</h2>
                <p>Compare different car models side by side.</p>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2023 Find Your Dream Car. All rights reserved.</p>
    </footer>
</body>
</html>

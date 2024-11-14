!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f5f5f5;
        }
        .container {
            width: 400px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .search-bar {
            display: flex;
            margin-bottom: 20px;
        }
        .search-bar input {
            width: 80%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px 0 0 5px;
        }
        .search-bar button {
            width: 20%;
            background-color: #a96dfc;
            color: #fff;
            border: none;
            border-radius: 0 5px 5px 0;
            cursor: pointer;
        }
        .city {
            font-size: 32px;
            font-weight: bold;
            margin: 10px 0;
        }
        .date {
            color: #888;
            font-size: 16px;
            margin-bottom: 20px;
        }
        .weather {
            font-size: 64px;
            font-weight: bold;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .weather img {
            width: 50px;
            height: 50px;
            margin-right: 10px;
        }
        .details {
            color: #888;
            font-size: 16px;
            margin-top: 10px;
        }
        .highlight {
            color:#888;
        }
        .footer {
            margin-top: 30px;
            font-size: 12px;
            color: #888;
        }
        .footer a {
            color: #a96dfc;
            text-decoration: none;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="search-bar">
        <input type="text" placeholder="Enter a city..">
        <button>Search</button>
    </div>
    <div class="city">Paris</div>
    <div class="date">Tuesday 07:45, moderate rain</div>
    <div class="weather">
        <img src="https://img.icons8.com/emoji/48/000000/sun-emoji.png" alt="Sun icon">
        <span>24°C</span>
    </div>
    <div class="details">
        Humidity: <span class="highlight">87%</span>, Wind: <span class="highlight">7.2km/h</span>
    </div>
    <div class="footer">
        This project was coded by <a href="#">Munoko Isaiah</a> and is <a href="#">on GitHub</a> and <a href="#">hosted on Netlify</a>
    </div>
</div>

</body>
</html>
# WEATHER-PATTERN

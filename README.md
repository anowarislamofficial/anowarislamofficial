<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Betting Site</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .betting-options {
            display: flex;
            justify-content: space-around;
            margin-top: 30px;
        }
        .betting-option {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 30%;
        }
        .betting-option h3 {
            margin: 10px 0;
        }
        .betting-option button {
            padding: 10px;
            background-color: #28a745;
            border: none;
            color: white;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
        .betting-option button:hover {
            background-color: #218838;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Betting Hub</h1>
    <p>Your trusted platform for sports betting</p>
</header>

<div class="container">
    <h2>Choose Your Bet</h2>
    
    <div class="betting-options">
        <div class="betting-option">
            <h3>Football</h3>
            <p>Bet on the latest football matches</p>
            <button>Place Bet</button>
        </div>
        <div class="betting-option">
            <h3>Basketball</h3>
            <p>Bet on the latest basketball games</p>
            <button>Place Bet</button>
        </div>
        <div class="betting-option">
            <h3>Tennis</h3>
            <p>Bet on tennis tournaments</p>
            <button>Place Bet</button>
        </div>
    </div>
</div>

<footer>
    <p>&copy; 2024 Betting Hub. All Rights Reserved.</p>
</footer>

</body>
</html>

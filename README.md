<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Smart Pesa</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="navbar">
    <button onclick="showSection('home')">Home</button>
    <button onclick="showSection('splitMoney')">Split Money</button>
    <button onclick="showSection('dashboard')">Dashboard</button>
  </div>

  <div id="home" class="section">
    <h1>Welcome to Smart Pesa</h1>
    <p>Your Financial Buddy</p>
  </div>

  <div id="splitMoney" class="section">
    <h2>Split Your Money</h2>
    <input type="number" id="income" placeholder="Enter Your Income">
    <input type="number" id="expenses" placeholder="Enter Your Expenses">
    <button onclick="calculateSplit()">Calculate</button>
    <div id="splitResult"></div>
  </div>

  <div id="dashboard" class="section">
    <h2>Your Financial Dashboard</h2>
    <canvas id="chart"></canvas>
    <div id="goalResult"></div>
  </div>

  <script src="script.js"></script>

</body>
</html>

# My-website
git clone https://github.com/username/repository-name.git
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Budgeting & Savings Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Budgeting and Savings Tracker</h1>
    </header>

    <section class="calculator">
        <h2>Enter Your Details</h2>

        <div class="input-group">
            <label for="income">Monthly Income ($):</label>
            <input type="number" id="income" placeholder="Enter your income">
        </div>

        <div class="input-group">
            <label for="expenses">Monthly Expenses ($):</label>
            <input type="number" id="expenses" placeholder="Enter your expenses">
        </div>

        <button onclick="calculateSavings()">Calculate Savings</button>

        <div id="result" class="result">
            <p id="savings-output"></p>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>

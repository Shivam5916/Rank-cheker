<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SSC Answer Key Score Calculator</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>SSC Answer Key Score Calculator</h1>
        <form id="scoreForm">
            <label for="correct">Correct Answers:</label>
            <input type="number" id="correct" name="correct" required>
            <label for="incorrect">Incorrect Answers:</label>
            <input type="number" id="incorrect" name="incorrect" required>
            <button type="submit">Calculate Score</button>
        </form>
        <div id="result"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>

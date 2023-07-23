# Data-visualization-html-code-index.html
<!DOCTYPE html>
<html>
<head>
    <title>Data Visualization</title>
    <!-- Include Chart.js library -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <h1>Data Visualization</h1>
    <form id="dataForm">
        <label for="dataInput">Enter data (comma-separated):</label>
        <input type="text" id="dataInput" name="dataInput" required>
        <button type="submit">Visualize</button>
    </form>
    <div class="chart-container">
        <canvas id="barChart"></canvas>
    </div>

    <script src="script.js"></script>
</body>
</html>

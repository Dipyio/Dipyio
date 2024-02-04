<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Health Analysis</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        label {
            font-weight: bold;
        }
        input[type="text"],
        input[type="number"],
        select {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Health Analysis</h1>
        <form id="healthForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>

            <label for="age">Age:</label>
            <input type="number" id="age" name="age" required><br>

            <label for="sleepHours">Sleeping Hours:</label>
            <input type="number" id="sleepHours" name="sleepHours" required><br>

            <label for="healthIssues">Health Issues:</label>
            <select id="healthIssues" name="healthIssues">
                <option value="">Select</option>
                <option value="Diabetes">Diabetes</option>
                <option value="Hypertension">Hypertension</option>
                <option value="Asthma">Asthma</option>
                <!-- Add more health issues as needed -->
            </select><br>

            <label for="state">State:</label>
            <select id="state" name="state">
                <option value="">Select</option>
                <!-- Populate with list of states -->
            </select><br>

            <input type="submit" value="Submit">
        </form>
    </div>

    <script>
        // JavaScript code for fetching weather data and displaying sleeping tips
        // This requires integration with a weather API and sleeping tips database
        // Due to complexity, it's not possible to provide a complete solution here
    </script>
</body>
</html>


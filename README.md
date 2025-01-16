<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DRP Evaluation Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            padding: 20px;
        }
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
            padding: 20px;
        }
        .card h3 {
            margin-top: 0;
            color: #333;
        }
        .card table {
            width: 100%;
            border-collapse: collapse;
        }
        .card table th, .card table td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        .card table th {
            background-color: #f8f9fa;
        }
        .summary {
            text-align: center;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Drug-Related Problem (DRP) Evaluation Dashboard</h1>
        <h2>Pharmacy Care Network Thailand (PCNT)</h2>
    </header>

    <div class="container">
        <!-- Summary Section -->
        <div class="summary">
            <h2>Summary of DRP Evaluations</h2>
            <p>Total Evaluations: <strong>125</strong></p>
            <p>Resolved Issues: <strong>98</strong></p>
            <p>Unresolved Issues: <strong>27</strong></p>
        </div>

        <!-- Evaluation Categories -->
        <div class="card">
            <h3>Categories of DRPs</h3>
            <table>
                <thead>
                    <tr>
                        <th>Category</th>
                        <th>Description</th>
                        <th>Total Cases</th>
                        <th>Resolved Cases</th>
                        <th>Unresolved Cases</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Medication Errors</td>
                        <td>Incorrect drug or dosage prescribed/administered</td>
                        <td>45</td>
                        <td>38</td>
                        <td>7</td>
                    </tr>
                    <tr>
                        <td>Adverse Drug Reactions</td>
                        <td>Undesirable effects caused by medication</td>
                        <td>30</td>
                        <td>25</td>
                        <td>5</td>
                    </tr>
                    <tr>
                        <td>Non-Adherence</td>
                        <td>Failure to follow the prescribed therapy</td>
                        <td>50</td>
                        <td>35</td>
                        <td>15</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <!-- Detailed Evaluation Section -->
        <div class="card">
            <h3>Recent DRP Evaluations</h3>
            <table>
                <thead>
                    <tr>
                        <th>Patient ID</th>
                        <th>Category</th>
                        <th>Issue</th>
                        <th>Status</th>
                        <th>Notes</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>PT001</td>
                        <td>Medication Errors</td>
                        <td>Wrong dosage prescribed</td>
                        <td>Resolved</td>
                        <td>Adjusted dosage successfully</td>
                    </tr>
                    <tr>
                        <td>PT002</td>
                        <td>Non-Adherence</td>
                        <td>Missed multiple doses</td>
                        <td>Unresolved</td>
                        <td>Follow-up required</td>
                    </tr>
                    <tr>
                        <td>PT003</td>
                        <td>Adverse Drug Reactions</td>
                        <td>Severe rash</td>
                        <td>Resolved</td>
                        <td>Switched medication</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</body>
</html>

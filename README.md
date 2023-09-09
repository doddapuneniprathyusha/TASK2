# TASK2
creating a table in html in mock
<!DOCTYPE html>
<html>
<head>
    <title>Vegetable Prices</title>
    <style>
        table {
            border-collapse: collapse;
            width: 60%;
            margin: 20px auto;
        }

        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }

        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Vegetable Prices</h1>
    <table>
        <tr>
            <th rowspan="2">Vegetable</th>
            <th colspan="2">COST (in rs)</th>
        </tr>
        <tr>
            <th>MRP</th>
            <th>RP</th>
        </tr>
        <tr>
            <td>Carrot</td>
            <td>50</td>
            <td>60</td>
        </tr>
        <tr>
            <td>Tomato</td>
            <td>40</td>
            <td>45</td>
        </tr>
        <tr>
            <td>Spinach</td>
            <td>35</td>
            <td>40</td>
        </tr>
        <!-- Add more rows for other vegetables as needed -->
    </table>
</body>
</html>



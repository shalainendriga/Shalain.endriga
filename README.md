# Shalain.endriga
sampleoutput

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Javascript 3</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
        }
  
    table {
      border-collapse: collapse; 
      width: 100%; 
    }
    th, td {
      border: 1px solid black; 
      padding: 5px; 
    }

    #apiDataTable th:first-child,
    #apiDataTable td:first-child {
    border-left: none;
    }

    #apiDataTable th:last-child,
    #apiDataTable td:last-child {
    border-right: none;
    }
    </style>
</head>
<body>
    <script type="module" src="main.js"></script>
    <script src="modules.js"></script>
    <h1>Javascript Web Output #3</h1>

    <button id="btnLoad" style="margin-top: 10px;">Load data from the API</button>
    <button id="btnClear" style="margin-top: 10px;">Clear Table</button>
    
    <p>API: <a href="https://jsonplaceholder.typicode.com/todos/">https://jsonplaceholder.typicode.com/todos/</a></p>
    <table id="apiDataTable" >
        <thead >
            <tr >
                <th>User ID</th>
                <th>Task ID</th>
                <th>Title</th>
                <th>Status</th>
            </tr>
        </thead>
        <tbody id="apiDataContainer"></tbody>
    </table>
</body>
</html>

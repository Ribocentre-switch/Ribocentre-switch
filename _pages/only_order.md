---
title: "Structure - Structure"
layout: structure
excerpt: "Structure - Structure"
sitemap: false
permalink: /order_test/
---
<html>
<head>
    <meta http-equiv="Content-type" content="text/html; charset=utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no">
    <title>Ribozyme applications</title>
    <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.12.1/css/jquery.dataTables.min.css">
    <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/buttons/2.2.3/css/buttons.dataTables.min.css">

    <script type="text/javascript" src="https://code.jquery.com/jquery-3.5.1.js"></script>
    <script type="text/javascript" src="https://cdn.datatables.net/1.12.1/js/jquery.dataTables.min.js"></script>

    <script type="text/javascript">
        $(document).ready(function() {
            $.noConflict();
            $('#Dnatable').DataTable({
                dom: 'Bfrtip',
                searching: false,
                buttons: [
                    'copy', 'csv', 'excel', 'pdf', 'print'
                ]
            });

            $('#tableSheet2').DataTable({
                dom: 'Bfrtip',
                searching: false,
                buttons: [
                    'copy', 'csv', 'excel', 'pdf', 'print'
                ]
            });
        });
   </script>
</head>
<body>
<div id="sheet1" class="sheet">
    <h2>Sheet 1</h2>
    <table id="Dnatable">
        <thead>
        <tr>
            <th>Column 1</th>
            <th>Column 2</th>
            <!-- Add more columns if needed -->
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>1</td>
            <td>6</td>
            <!-- Add more rows if needed -->
        </tr>
        <tr>
            <td>7</td>
            <td>3</td>
            <!-- Add more rows if needed -->
        </tr>
        <!-- Add more rows here -->
        </tbody>
    </table>
</div>

<div id="sheet2" class="sheet">
    <h2>Sheet 2</h2>
    <table id="tableSheet2">
        <thead>
        <tr>
            <th>Column 1</th>
            <th>Column 2</th>
            <!-- Add more columns if needed -->
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>4</td>
            <td>6</td>
            <!-- Add more rows if needed -->
        </tr>
         <tr>
            <td>7</td>
            <td>5</td>
            <!-- Add more rows if needed -->
        </tr>
        <!-- Add more rows here -->
        </tbody>
    </table>
</div>
</body>
</html>
---
title: "Structure - Structure"
layout: structure
excerpt: "Structure - Structure"
sitemap: false
permalink: /chatgpt/
---

<html lang="en">
<head>
  <meta http-equiv="Content-type" content="text/html; charset=utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no">
  <title>Ribozyme applications</title>
  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.12.1/css/jquery.dataTables.min.css">
  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/buttons/2.2.3/css/buttons.dataTables.min.css">

  <script type="text/javascript" src="https://code.jquery.com/jquery-3.5.1.js"></script>
  <script type="text/javascript" src="https://cdn.datatables.net/1.12.1/js/jquery.dataTables.min.js"></script>

  <style>
     .header_box {
    border: none;
    background: #efefef;
    font-size:24px
  }
  h2{
    font-size:20px
  }
/* 按钮容器样式 */
    .button-container {
      display: flex;
      justify-content: left;
      align-items: center;
      height: 50px;
    }
    /* 按钮样式 */
    .button {
      display: block;
      padding: 10px;
      margin-right: 10px;
      text-align: center;
      background-color: #efefef;
      color: #005826;
      text-decoration: none;
      font-weight: bold;
      font-size: 20px;
      border: 1px solid #005826;
      border-radius: 5px;
    }
    /* 鼠标悬停样式 */
    .button:hover {
      background-color: #999;
      cursor: pointer;
    }
    /* 样式表格 */
    table {
        border: 2px solid #f8f8ff;
        border: 2px solid #767676;
		    border: 2px solid #767676;
		    border-radius: 5px;
		    background-color: #fff;
        border-radius: 0;
        }
		  th {
        background-color: #719B71;
        background-color: #719B71;
        background-color: #005826;
        color: rgba(255,255,255,0.9);
		    cursor: pointer;
        }
		  td {
		    background-color: #ffffff;
		    background-color: #f9f9f9;
		    background-color: #f9f9f9;
		    }		
		  th, td {
		  
		  padding: 10px 10px;
		}
    /* 隐藏所有 sheet */
    .sheet {
      display: none;
    }
    /* Style the search box */
  #searchBox {
    padding: 10px;
    font-size: 16px;
    border: 2px solid #ccc;
    border-radius: 4px;
    width: 300px;
  }
  /* Style the search box when it has focus */
  #searchBox:focus {
    outline: none;
    border-color: #005826;
  }
  /* Style the placeholder text */
  #searchBox::placeholder {
    font-size: 16px;
  }
  /* 搜索框和下载框水平布局 */
    .form-container {
      display: flex;
      align-items: center;
    }
    .form-container input {
      margin-right: 10px;
    }
    /* 下载框位置设置 */
    .form-container select {
      margin-left: auto;
      padding: 10px;
      font-size: 16px;
      border: 2px solid #ccc;
      border-radius: 4px;
      width: 300px;
    }
  </style>
</head>

<body onload="showSheet('sheet5')">
<h1 class="post-title" itemprop="name headline">Structures</h1>

This page shows all PDB of the collected riboswitches. We also list phase determination of each PDB.
<br><br><br>
<div class="form-container">
  <!-- 搜索框 -->
  <input type="text" id="searchBox" placeholder="Search by keyword..." oninput="searchSheets()"><br><br>
  <select id="downloadOptions">
    <option value="" disabled selected>Select an option</option>
    <option value="/download/riboswitches_page/Cofactors.xlsx">Cofactors</option>
    <option value="/download/riboswitches_page/RNA derivatives.xlsx">RNA derivatives</option>
    <option value="/download/riboswitches_page/RNA derivatives.xlsx">RNA derivatives</option>
    <option value="/download/riboswitches_page/RNA precursors.xlsx">RNA precursors</option>
    <option value="/download/riboswitches_page/Signaling molecules.xlsx">Signaling molecules</option>
    <option value="/download/riboswitches_page/Elemental ions.xlsx">Elemental ions</option>
    <option value="/download/riboswitches_page/Amino acids.xlsx">Amino acids</option>
    <option value="/download/riboswitches_page/Sugars.xlsx">Sugars</option>
    <option value="/download/riboswitches_page/T-box.xlsx">T-box</option>
    <option value="/download/riboswitches_page/Others.xlsx">Others</option>
    <option value="/download/riboswitches_page/all.xlsx">all</option>
  </select>
  <!-- Download button -->
  <button class="button" onclick="downloadExcel()">Download</button>
</div>
<br>
  <!-- 按钮 -->
  <div class="button-container">
      <button class="button" onclick="showSheet('sheet1')">Cofactors</button>
      <button class="button" onclick="showSheet('sheet2')">RNA derivatives</button>
      <button class="button" onclick="showSheet('sheet3')">RNA precursors</button>
      <button class="button" onclick="showSheet('sheet4')">Signaling molecules</button>
      <button class="button" onclick="showSheet('sheet5')">Elemental ions</button>
      <button class="button" onclick="showSheet('sheet6')">Amino acids</button>
      <button class="button" onclick="showSheet('sheet7')">Sugars</button>
      <button class="button" onclick="showSheet('sheet8')">T-box</button>
      <button class="button" onclick="showSheet('sheet9')">Others</button>
  </div>

<div id="sheet1" class="sheet" >
    <h2>Cofactors</h2>

    <table id="cfttable" >
      <thead>
      <tr>
        <th onclick="sortTable(0)">Name</th>
        <th onclick="sortTable(1)">PDB</th>
        <th onclick="sortTable(2)">Length</th>
        <th onclick="sortTable(3)">Description(PDB)</th>
        <th onclick="sortTable(4)">Species</th>
        <th onclick="sortTable(5)">Phase Determination</th>
        <th onclick="sortTable(6)">Structure Determination</th>
        <th onclick="sortTable(7)">Res(Å)</th>
        <th onclick="sortTable(8)">Year</th>
        <th onclick="sortTable(9)">Journal</th>
      </tr>
      </thead>
      <tbody>
      <tr>
        <td name="td0"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Adocbl</b></a></td>
        <td name="td1"><a href="https://www.rcsb.org/structure/4GXY" target="_blank"><b>4GXY</b></a></td>
        <td name="td2">172</td>
        <td name="td3">RNA structure</td>
        <td name="td4">None</td>
        <td name="td5">SAD-Ir</td>
        <td name="td6">X-RAY DIFFRACTION</td>
        <td name="td7">3.05 Å</td>
        <td name="td8"><a href="https://pubmed.ncbi.nlm.nih.gov/23064646/" target="_blank"><b>2012</b></a></td>
        <td name="td9">Nat Struct Mol Biol</td>
      </tr>
      <tr>
        <td name="td0"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Adocbl</b></a></td>
        <td name="td1"><a href="https://www.rcsb.org/structure/4GXY" target="_blank"><b>4GXY</b></a></td>
        <td name="td2">172</td>
        <td name="td3">RNA structure</td>
        <td name="td4">None</td>
        <td name="td5">SAD-Ir</td>
        <td name="td6">X-RAY DIFFRACTION</td>
        <td name="td7">3.05 Å</td>
        <td name="td8"><a href="https://pubmed.ncbi.nlm.nih.gov/23064646/" target="_blank"><b>2012</b></a></td>
        <td name="td9">Nat Struct Mol Biol</td>
      </tr>
      </tbody>
    </table>
</div>

<div id="sheet2" class="sheet">
    <h2>Cofactors</h2>

    <table id="rnadetable">
      <thead>
      <tr>
        <th onclick="sortTable(0)">Name</th>
        <th onclick="sortTable(1)">PDB</th>
        <th onclick="sortTable(2)">Length</th>
        <th onclick="sortTable(3)">Description(PDB)</th>
        <th onclick="sortTable(4)">Species</th>
        <th onclick="sortTable(5)">Phase Determination</th>
        <th onclick="sortTable(6)">Structure Determination</th>
        <th onclick="sortTable(7)">Res(Å)</th>
        <th onclick="sortTable(8)">Year</th>
        <th onclick="sortTable(9)">Journal</th>
      </tr>
      </thead>
      <tbody>
       <tr>
            <td name="td0"><a href="https://ribocentre-switch.github.io/docs/Xanthine" target="_blank"><b>Xanthine-I</b></a></td>
            <td name="td1"><a href="https://www.rcsb.org/structure/7ELP" target="_blank"><b>7ELP</b></a></td>
            <td name="td2">45</td>
            <td name="td3">Crystal structure of xanthine riboswitch with xanthine, iridium hexammine soak</td>
            <td name="td4">Ideonella sp. B508-1</td>
            <td name="td5">SAD-Ir</td>
            <td name="td6">X-RAY DIFFRACTION</td>
            <td name="td7">2.79 Å</td>
            <td name="td8"><a href="https://pubmed.ncbi.nlm.nih.gov/34125892/" target="_blank"><b>2021</b></a></td>
            <td name="td9">Nucleic Acids Res</td>
        </tr>
      </tbody>
    </table>
</div>

<div id="sheet3" class="sheet">
    <h2>Cofactors</h2>

    <table id="rnapretable">
      <thead>
      <tr>
        <th onclick="sortTable(0)">Name</th>
        <th onclick="sortTable(1)">PDB</th>
        <th onclick="sortTable(2)">Length</th>
        <th onclick="sortTable(3)">Description(PDB)</th>
        <th onclick="sortTable(4)">Species</th>
        <th onclick="sortTable(5)">Phase Determination</th>
        <th onclick="sortTable(6)">Structure Determination</th>
        <th onclick="sortTable(7)">Res(Å)</th>
        <th onclick="sortTable(8)">Year</th>
        <th onclick="sortTable(9)">Journal</th>
      </tr>
      </thead>
      <tbody>
       <tr>
            <td name="td0"><a href="https://ribocentre-switch.github.io/docs/Xanthine" target="_blank"><b>Xanthine-I</b></a></td>
            <td name="td1"><a href="https://www.rcsb.org/structure/7ELP" target="_blank"><b>7ELP</b></a></td>
            <td name="td2">45</td>
            <td name="td3">Crystal structure of xanthine riboswitch with xanthine, iridium hexammine soak</td>
            <td name="td4">Ideonella sp. B508-1</td>
            <td name="td5">SAD-Ir</td>
            <td name="td6">X-RAY DIFFRACTION</td>
            <td name="td7">2.79 Å</td>
            <td name="td8"><a href="https://pubmed.ncbi.nlm.nih.gov/34125892/" target="_blank"><b>2021</b></a></td>
            <td name="td9">Nucleic Acids Res</td>
        </tr>
      </tbody>
    </table>
</div>

<script>
  $(document).ready(function() {
    $.noConflict();
    $('#cfttable').DataTable({
      dom: 'Bfrtip',
      searching: false,
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    });

    $('#rnadetable').DataTable({
      dom: 'Bfrtip',
      searching: false,
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    });
    $('#rnapretable').DataTable({
      dom: 'Bfrtip',
      searching: false,
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    });
  });
    

  function sortTable(columnIndex) {
    // TODO: Add sorting logic based on the columnIndex
  }

  function downloadExcel() {
    // TODO: Implement downloadExcel function
  }

  function searchSheets() {
    // TODO: Implement searchSheets function
  }

  function showSheet(sheetId) {
    // TODO: Implement showSheet function
  }

  function showSheet(sheetId) {
      // 隐藏所有 sheet
      var sheets = document.getElementsByClassName('sheet');
      for (var i = 0; i < sheets.length; i++) {
        sheets[i].style.display = 'none';
      }

      // 显示选定的 sheet
      var sheet = document.getElementById(sheetId);
      sheet.style.display = 'block';
    }
     function searchSheets() {
  var searchBox = document.getElementById('searchBox');
  var keyword = searchBox.value.toLowerCase();

  var sheets = document.getElementsByClassName('sheet');
  for (var i = 0; i < sheets.length; i++) {
    var sheet = sheets[i];
    var sheetTitle = sheet.getElementsByTagName('h2')[0].textContent.toLowerCase();
    var tableRows = sheet.getElementsByTagName('tr');

    // Loop through each row and cell of the sheet's table
    var showSheet = false;
    for (var j = 0; j < tableRows.length; j++) {
      var cells = tableRows[j].getElementsByTagName('td');
      for (var k = 0; k < cells.length; k++) {
        var cellText = cells[k].textContent.toLowerCase();
        if (cellText.includes(keyword)) {
          showSheet = true;
          break;
        }
      }
    }

    // Show or hide the sheet based on whether the keyword was found
    if (sheetTitle.includes(keyword) || showSheet) {
      sheet.style.display = 'block';
    } else {
      sheet.style.display = 'none';
    }
  }
}  

function downloadExcel() {
  var selectElement = document.getElementById('downloadOptions');
  var selectedValue = selectElement.value;

  // Check if a valid option was selected
  if (selectedValue !== '') {
    // Create a temporary link element with the download URL
    var link = document.createElement('a');
    link.href = selectedValue;
    link.download = selectedValue.split('/').pop(); // Set the filename to the last part of the URL
    document.body.appendChild(link);

    // Trigger a click event on the link to start the download
    link.click();

    // Remove the link from the DOM
    document.body.removeChild(link);
  }
}

</script>

</body>
</html>
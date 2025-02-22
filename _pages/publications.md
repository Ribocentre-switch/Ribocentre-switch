---
title: "Riboswitch - Publication"
layout: gridlay
excerpt: "Riboswitches: A riboswitch database"
sitemap: True
permalink: /publications/
---
<html lang="en">
<head>
<!--set sort order in table header begin-->
<meta http-equiv="Content-type" content="text/html; charset=utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no">
  <title>Ribozyme applications</title>
  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.12.1/css/jquery.dataTables.min.css">
  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/buttons/2.2.3/css/buttons.dataTables.min.css">

  <script type="text/javascript" src="https://code.jquery.com/jquery-3.5.1.js"></script>
  <script type="text/javascript" src="https://cdn.datatables.net/1.12.1/js/jquery.dataTables.min.js"></script>
  <!--set sort order in table header finish-->
  <style>
    .header_box {
    border: none;
    background: #efefef;
    font-size:24px
  }
  h2{
    font-size:20px;
    font-weight: bold
  }
/* button container style */
    .button-container {
      display: flex;
      justify-content: left;
      align-items: center;
      height: 50px;
    }
    /* button style */
    .button {
      display: block;
      padding: 10px;
      margin-right: 10px;
      text-align: center;
      background-color: #efefef;
      color: #005826;
      text-decoration: none;
      font-size: 16px;
      border: 1px solid #005826;
      border-radius: 5px;
    }
    /* mource button style */
    .button:hover {
      background-color: #999;
      cursor: pointer;
    }
    /* 样式表格 */
.table-style1 {
        border: 2px solid #ffffff;
        border: 2px solid #ffffff;
		    border: 2px solid #ffffff;
		    border-radius: 5px;
		    background-color: #fff;
		    border-radius: 5px;
        }
		  .table-style1 th {
        background-color: #005826;
        background-color: #005826;
        background-color: #005826;
        color: rgba(255,255,255,0.9);
		    cursor: pointer;
        }
		  .table-style1 td {
		    background-color: #ffffff;
		    background-color: #f9f9f9;
		    background-color: #f9f9f9;
		    }		
		  .table-style1 th, .table-style1 td {
		  padding: 10px 10px;
		}
    table.dataTable.no-footer {
  border-bottom: 1px solid rgba(0, 0, 0, 0);
}
    /* hide all sheet */
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
    border-color: #2354C4;
  }
  /* Style the placeholder text */
  #searchBox::placeholder {
    font-size: 16px;
  }
  /* Horizontal layout of search box and download box */
    .form-container {
      display: flex;
      align-items: center;
      overflow:auto
    }
    .form-container input {
      margin-right: 10px;
    }
    /* Download box position setting */
    .form-container select {
      margin-left: auto;
      padding: 10px;
      font-size: 16px;
      border: 2px solid #ccc;
      border-radius: 4px;
      width: 300px;
    }
    
    .button.clicked {
    background-color: #999;
}
  </style>
</head>

<body onload="showSheet('sheet1')">
<h1 class="post-title" itemprop="name headline">Publications</h1>
    
This page list the reviews and articles about riboswitches. 
Click into different sections:
<br><br><br>
<div class="form-container">
  <!-- search box -->
  <input type="text" id="searchBox" placeholder="Search by keyword..." onfocus="showAllSheets()" oninput="searchTables()"><br><br>
  <select id="downloadOptions">
    <option value="" disabled selected>Select an option</option>
    <option value="/downloads/publications_page/Reviews.xlsx">Reviews</option>
    <option value="/downloads/publications_page/Articles.xlsx">Articles</option>
    <option value="/downloads/publications_page/All_tables.xlsx">All tables in this page</option>
  </select>
  <!-- Download button -->
  <button class="button" onclick="downloadExcel()">Download</button>
</div>
<br>
  <!-- button -->
  <div class="button-container">
      <button class="button" onclick="showSheet('sheet1')">Reviews</button>
      <button class="button" onclick="showSheet('sheet2')">Articles</button>
  </div>
        
<div id="sheet1" class="sheet">
    <h2>Reviews</h2>
    <table id="reviewtable" class="table-style1">
      <thead>
      <tr>
        <th onclick="sortTable(0)">Year</th>
        <th onclick="sortTable(1)">Author</th>
        <th onclick="sortTable(1)">Title</th>
        <th onclick="sortTable(3)">Journal</th>
      </tr>
      </thead>
      <tbody>
        
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/14523920/" target="_blank"><b>2003</b></a></td>
        <td name="td1">Winkler, W. C. & Breaker, R. R.</td>
        <td name="td2">Genetic control by metabolite-binding riboswitches.</td>
        <td name="td3">Chembiochem</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12676109/" target="_blank"><b>2003</b></a></td>
        <td name="td1">Lai E. C.</td>
        <td name="td2">RNA sensors and riboswitches: self-regulating messages.</td>
        <td name="td3">Curr Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15173824/" target="_blank"><b>2004</b></a></td>
        <td name="td1">Mandal, M. & Breaker, R. R.</td>
        <td name="td2">Gene regulation by riboswitches.</td>
        <td name="td3">Nat. Rev. Mol. Cell Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/14729327/" target="_blank"><b>2004</b></a></td>
        <td name="td1">Nudler, E., & Mironov, A. S.</td>
        <td name="td2">The riboswitch control of bacterial metabolism.</td>
        <td name="td3">Trends Biochem Sci</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15549109/" target="_blank"><b>2004</b></a></td>
        <td name="td1">Batey, R. T., Gilbert, S. D., & Montange, R. K.</td>
        <td name="td2">Structure of a natural guanine-responsive riboswitch complexed with the metabolite hypoxanthine.</td>
        <td name="td3">Nature</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/14698618/" target="_blank"><b>2004</b></a></td>
        <td name="td1">Vitreschak, A. G., Rodionov, D. A., Mironov, A. A., & Gelfand, M. S.</td>
        <td name="td2">Riboswitches: the oldest mechanism for the regulation of gene expression?</td>
        <td name="td3">Trends Genet</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15342904/" target="_blank"><b>2004</b></a></td>
        <td name="td1">Templeton, G. W., & Moorhead, G. B.</td>
        <td name="td2">A renaissance of metabolite sensing and signaling: from modular domains to riboswitches.</td>
        <td name="td3">Plant Cell</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15363900/" target="_blank"><b>2004</b></a></td>
        <td name="td1">Abreu-Goodger, C., Ontiveros-Palacios, N., Ciria, R., & Merino, E.</td>
        <td name="td2">Conserved regulatory motifs in bacteria: riboswitches and beyond.</td>
        <td name="td3">Trends Genet</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16153177/" target="_blank"><b>2005</b></a></td>
        <td name="td1">Winkler, W. C. & Breaker, R. R.</td>
        <td name="td2">Regulation of bacterial gene expression by riboswitches.</td>
        <td name="td3">Annu. Rev. Microbiol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15919195/" target="_blank"><b>2005</b></a></td>
        <td name="td1">Tucker, B. J. & Breaker, R. R.</td>
        <td name="td2">Riboswitches as versatile gene control elements.</td>
        <td name="td3">Curr. Opin. Struct. Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16226486/" target="_blank"><b>2005</b></a></td>
        <td name="td1">Winkler W. C.</td>
        <td name="td2">Riboswitches and the role of noncoding RNAs in bacterial metabolic control.</td>
        <td name="td3">Curr Opin Chem Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17381305/" target="_blank"><b>2006</b></a></td>
        <td name="td1">Gilbert, S. D., Montange, R. K., Stoddard, C. D., & Batey, R. T.</td>
        <td name="td2">Structural studies of the purine and SAM binding riboswitches.</td>
        <td name="td3">Cold Spring Harb Symp Quant Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17160062/" target="_blank"><b>2006</b></a></td>
        <td name="td1">Blount, K. F. & Breaker, R. R.</td>
        <td name="td2">Riboswitches as antibacterial drug targets.</td>
        <td name="td3">Nat. Biotechnol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17092822/" target="_blank"><b>2006</b></a></td>
        <td name="td1">Grundy, F. J., & Henkin, T. M.</td>
        <td name="td2">From ribosome to riboswitch: control of gene expression in bacteria by RNA structural rearrangements.</td>
        <td name="td3">Crit Rev Biochem Mol Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16839869/" target="_blank"><b>2006</b></a></td>
        <td name="td1">Nudler E.</td>
        <td name="td2">Flipping riboswitches.</td>
        <td name="td3">Cell</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17381302/" target="_blank"><b>2006</b></a></td>
        <td name="td1">Henkin, T. M., & Grundy, F. J.</td>
        <td name="td2">Sensing metabolic signals with nascent RNA transcripts: the T box and S box riboswitches as paradigms.</td>
        <td name="td3">Cold Spring Harb Symp Quant Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16545107/" target="_blank"><b>2006</b></a></td>
        <td name="td1">Loenen W. A.</td>
        <td name="td2">S-Adenosylmethionine: jack of all trades and master of everything?</td>
        <td name="td3">Biochem Soc Trans</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17383225/" target="_blank"><b>2007</b></a></td>
        <td name="td1">Coppins, R. L., Hall, K. B., & Groisman, E. A.</td>
        <td name="td2">The intricate world of riboswitches.</td>
        <td name="td3">Curr Opin Microbiol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17355861/" target="_blank"><b>2007</b></a></td>
        <td name="td1">Miranda-Ríos J.</td>
        <td name="td2">The THI-box riboswitch, or how RNA binds thiamin pyrophosphate.</td>
        <td name="td3">Structure</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17574837/" target="_blank"><b>2007</b></a></td>
        <td name="td1">Edwards, T. E., Klein, D. J., & Ferré-D'Amaré, A. R.</td>
        <td name="td2">Riboswitches: small-molecule recognition by gene regulatory RNAs.</td>
        <td name="td3">Curr Opin Struct Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18443629/" target="_blank"><b>2008</b></a></td>
        <td name="td1">Wang, J. X. & Breaker, R. R.</td>
        <td name="td2">Riboswitches that sense S-adenosylmethionine and S-adenosylhomocysteine.</td>
        <td name="td3">Biochem</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18072940/" target="_blank"><b>2008</b></a></td>
        <td name="td1">Kim, J. N. & Breaker, R. R.</td>
        <td name="td2">Purine sensing by riboswitches.</td>
        <td name="td3">Biol. Cell</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19141470/" target="_blank"><b>2008</b></a></td>
        <td name="td1">Henkin T. M.</td>
        <td name="td2">Riboswitch RNAs: using RNA to sense cellular metabolism.</td>
        <td name="td3">Genes Dev</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18573075/" target="_blank"><b>2008</b></a></td>
        <td name="td1">Montange, R. K., & Batey, R. T.</td>
        <td name="td2">Riboswitches: emerging themes in RNA structure and function.</td>
        <td name="td3">Annu Rev Biophys</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18430893/" target="_blank"><b>2008</b></a></td>
        <td name="td1">Cochrane, J. C., & Strobel, S. A.</td>
        <td name="td2">Riboswitch effectors as protein enzyme cofactors.</td>
        <td name="td3">RNA</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18388492/" target="_blank"><b>2008</b></a></td>
        <td name="td1">Suess, B., & Weigand, J. E.</td>
        <td name="td2">Engineered riboswitches: overview, problems and trends.</td>
        <td name="td3">RNA Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18778966/" target="_blank"><b>2008</b></a></td>
        <td name="td1">Bocobza, S. E., & Aharoni, A.</td>
        <td name="td2">Switching the light on plant riboswitches.</td>
        <td name="td3">rends Plant Sci</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19298181/" target="_blank"><b>2009</b></a></td>
        <td name="td1">Roth, A. & Breaker, R. R.</td>
        <td name="td2">The structural and functional diversity of metabolite-binding riboswitches.</td>
        <td name="td3">Annu. Rev. Biochem.</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19595806/" target="_blank"><b>2009</b></a></td>
        <td name="td1">Garst, A. D., & Batey, R. T.</td>
        <td name="td2">A switch in time: detailing the life of a riboswitch.</td>
        <td name="td3">Biochim Biophys Acta</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19303767/" target="_blank"><b>2009</b></a></td>
        <td name="td1">Serganov A.</td>
        <td name="td2">The long and the short of riboswitches.</td>
        <td name="td3">Curr Opin Struct Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19101979/" target="_blank"><b>2009</b></a></td>
        <td name="td1">Blouin, S., Mulhbacher, J., Penedo, J. C., & Lafontaine, D. A.</td>
        <td name="td2">Riboswitches: ancient and promising genetic regulators.</td>
        <td name="td3">Chembiochem</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19619684/" target="_blank"><b>2009</b></a></td>
        <td name="td1">Serganov, A., & Patel, D. J.</td>
        <td name="td2">Amino acid recognition and gene regulation by riboswitches.</td>
        <td name="td3">Biochim Biophys Acta</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20009507/" target="_blank"><b>2010</b></a></td>
        <td name="td1">Wachter A.</td>
        <td name="td2">Riboswitch-mediated control of gene expression in eukaryotes.</td>
        <td name="td3">RNA Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20458165/" target="_blank"><b>2010</b></a></td>
        <td name="td1">Baird, N. J., Kulshina, N., & Ferré-D'Amaré, A. R.</td>
        <td name="td2">Riboswitch function: flipping the switch or tuning the dimmer?</td>
        <td name="td3">RNA Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20061810/" target="_blank"><b>2010</b></a></td>
        <td name="td1">Smith, A. M., Fuchs, R. T., Grundy, F. J., & Henkin, T. M</td>
        <td name="td2">Riboswitch RNAs: regulation of gene expression by direct monitoring of a physiological signal.</td>
        <td name="td3">RNA Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20061809/" target="_blank"><b>2010</b></a></td>
        <td name="td1">Serganov A.</td>
        <td name="td2">Determination of riboswitch structures: light at the end of the tunnel?</td>
        <td name="td3">RNA Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20050612/" target="_blank"><b>2010</b></a></td>
        <td name="td1">Topp, S., & Gallivan, J. P.</td>
        <td name="td2">Emerging applications of riboswitches in chemical biology.</td>
        <td name="td3">ACS Chem Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21925376/" target="_blank"><b>2011</b></a></td>
        <td name="td1">Breaker, R. R.</td>
        <td name="td2">Prospects for riboswitch discovery and analysis.</td>
        <td name="td3">Mol. Cell</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21477128/" target="_blank"><b>2011</b></a></td>
        <td name="td1">Bastet, L., Dubé, A., Massé, E., & Lafontaine, D. A.</td>
        <td name="td2">New insights into riboswitch regulation mechanisms.</td>
        <td name="td3">Mol Microbiol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21678902/" target="_blank"><b>2011</b></a></td>
        <td name="td1">Haller, A., Soulière, M. F., & Micura, R.</td>
        <td name="td2">The dynamic nature of RNA as key to understanding riboswitch mechanisms.</td>
        <td name="td3">Acc Chem Res</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20943759/" target="_blank"><b>2011</b></a></td>
        <td name="td1">Garst, A. D., Edwards, A. L., & Batey, R. T.</td>
        <td name="td2">Riboswitches: structures and mechanisms.</td>
        <td name="td3">Cold Spring Harb Perspect Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21615107/" target="_blank"><b>2011</b></a></td>
        <td name="td1">Deigan, K. E., & Ferré-D'Amaré, A. R.</td>
        <td name="td2">Riboswitches: discovery of drugs that target bacterial gene-regulatory RNAs.</td>
        <td name="td3">Acc Chem Res</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21106649/" target="_blank"><b>2012</b></a></td>
        <td name="td1">Breaker, R. R.</td>
        <td name="td2">Riboswitches and the RNA world.</td>
        <td name="td3">Cold Spring Harb</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22577823/" target="_blank"><b>2012</b></a></td>
        <td name="td1">Serganov, A., & Patel, D. J.</td>
        <td name="td2">Metabolite recognition principles and molecular mechanisms underlying riboswitch function.</td>
        <td name="td3">Annu Rev Biophys</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21957061/" target="_blank"><b>2012</b></a></td>
        <td name="td1">Liberman, J. A., & Wedekind, J. E.</td>
        <td name="td2">Riboswitch structure in the ligand‐free state.</td>
        <td name="td3">Wiley Interdiscip Rev RNA</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22579413/" target="_blank"><b>2012</b></a></td>
        <td name="td1">Serganov, A., & Patel, D. J.</td>
        <td name="td2">Molecular recognition and function of riboswitches.</td>
        <td name="td3">Curr Opin Struct Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23332744/" target="_blank"><b>2013</b></a></td>
        <td name="td1">Serganov, A., & Nudler, E.</td>
        <td name="td2">A decade of riboswitches.</td>
        <td name="td3">Cell</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23163232/" target="_blank"><b>2013</b></a></td>
        <td name="td1">Penchovsky, R., & Stoilova, C. C.</td>
        <td name="td2">Riboswitch-based antibacterial drug discovery using high-throughput screening methods.</td>
        <td name="td3">Expert Opin Drug Discov</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24769285/" target="_blank"><b>2014</b></a></td>
        <td name="td1">Zhang, J., Jones, C. P., & Ferré-D'Amaré, A. R.</td>
        <td name="td2">Global analysis of riboswitches by small-angle X-ray scattering and calorimetry.</td>
        <td name="td3">Biochim Biophys Acta</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24583553/" target="_blank"><b>2014</b></a></td>
        <td name="td1">Peselis, A., & Serganov, A.</td>
        <td name="td2">Themes and variations in riboswitch structure and function.</td>
        <td name="td3">Biochim Biophys Acta</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24727093/" target="_blank"><b>2014</b></a></td>
        <td name="td1">Savinov, A., Perez, C. F., & Block, S. M.</td>
        <td name="td2">Single-molecule studies of riboswitch folding.</td>
        <td name="td3">Biochim Biophys Acta</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24816551/" target="_blank"><b>2014</b></a></td>
        <td name="td1">Henkin T. M.</td>
        <td name="td2">The T box riboswitch: A novel regulatory RNA that utilizes tRNA as its ligand.</td>
        <td name="td3">Biochim Biophys Acta</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24773387/" target="_blank"><b>2014</b></a></td>
        <td name="td1">Bocobza, S. E., & Aharoni, A.</td>
        <td name="td2">Small molecules that interact with RNA: riboswitch‐based gene control and its involvement in metabolic regulation in plants and algae.</td>
        <td name="td3">Plant J</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24590258/" target="_blank"><b>2014</b></a></td>
        <td name="td1">Porter, E. B., Marcano-Velázquez, J. G., & Batey, R. T.</td>
        <td name="td2">The purine riboswitch as a model system for exploring RNA biology and chemistry.</td>
        <td name="td3">Biochim Biophys Acta</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24863161/" target="_blank"><b>2014</b></a></td>
        <td name="td1">Biochim Biophys Acta. 2014 Oct;1839(10):1005-1019</td>
        <td name="td2">Fluorescence tools to investigate riboswitch structural dynamics.</td>
        <td name="td3">Biochim Biophys Acta</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15193315/" target="_blank"><b>2014</b></a></td>
        <td name="td1">Soukup, J. K., & Soukup, G. A.</td>
        <td name="td2">Riboswitches exert genetic control through metabolite-induced conformational change.</td>
        <td name="td3">Curr Opin Struct Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26143008/" target="_blank"><b>2015</b></a></td>
        <td name="td1">Peselis, A., Gao, A., & Serganov, A.</td>
        <td name="td2">Cooperativity, allostery and synergism in ligand binding to riboswitches.</td>
        <td name="td3">Biochimie</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25137633/" target="_blank"><b>2015</b></a></td>
        <td name="td1">Berens, C., & Suess, B.</td>
        <td name="td2">Riboswitch engineering—making the all-important second and third steps.</td>
        <td name="td3">Curr Opin Biotechnol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25708284/" target="_blank"><b>2015</b></a></td>
        <td name="td1">Mellin, J. R., & Cossart, P.</td>
        <td name="td2">Unexpected versatility in bacterial riboswitches.</td>
        <td name="td3">Trends Genet</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25727496/" target="_blank"><b>2015</b></a></td>
        <td name="td1">Fürtig, B., Nozinovic, S., Reining, A., & Schwalbe, H.</td>
        <td name="td2">Multiple conformational states of riboswitches fine-tune gene regulation.</td>
        <td name="td3">Curr Opin Struct Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27607554/" target="_blank"><b>2016</b></a></td>
        <td name="td1">Sherwood, A. V., & Henkin, T. M.</td>
        <td name="td2">Riboswitch-mediated gene regulation: novel RNA architectures dictate gene expression responses.</td>
        <td name="td3">Annu Rev Microbiol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28375729/" target="_blank"><b>2017</b></a></td>
        <td name="td1">Jones, C. P., & Ferré-D'Amaré, A. R.</td>
        <td name="td2">Long-range interactions in riboswitch control of gene expression.</td>
        <td name="td3">Annu Rev Biophys</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28375743/" target="_blank"><b>2017</b></a></td>
        <td name="td1">Hallberg, Z. F., Su, Y., Kitto, R. Z., & Hammond, M. C.</td>
        <td name="td2">Engineering and in vivo applications of riboswitches.</td>
        <td name="td3">Annu Rev Biochem</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30051797/" target="_blank"><b>2018</b></a></td>
        <td name="td1">Kreuzer, K. D., & Henkin, T. M.</td>
        <td name="td2">The T-box riboswitch: tRNA as an effector to modulate gene regulation.</td>
        <td name="td3">Microbiol Spectr</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29844057/" target="_blank"><b>2018</b></a></td>
        <td name="td1">Breaker, R. R.</td>
        <td name="td2">Riboswitches and Translation Control.</td>
        <td name="td3">Cold Spring Harb. Perspect. Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30084346/" target="_blank"><b>2018</b></a></td>
        <td name="td1">Lotz, T. S., & Suess, B.</td>
        <td name="td2">Small-Molecule-Binding Riboswitches.</td>
        <td name="td3">Microbiol Spectr</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31128223/" target="_blank"><b>2019</b></a></td>
        <td name="td1">Pavlova, N., Kaloudas, D., & Penchovsky, R.</td>
        <td name="td2">Riboswitch distribution, structure, and function in bacteria.</td>
        <td name="td3">Gene</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31079546/" target="_blank"><b>2019</b></a></td>
        <td name="td1">Pavlova, N., & Penchovsky, R.</td>
        <td name="td2">Genome-wide bioinformatics analysis of FMN, SAM-I, glmS, TPP, lysine, purine, cobalamin, and SAH riboswitches for their applications as allosteric antibacterial drug targets in human pathogenic bacteria.</td>
        <td name="td3">Expert Opin Ther Targets</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31238268/" target="_blank"><b>2019</b></a></td>
        <td name="td1">Yokobayashi Y.</td>
        <td name="td2">Aptamer-based and aptazyme-based riboswitches in mammalian cells.</td>
        <td name="td3">Curr Opin Chem Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31249101/" target="_blank"><b>2019</b></a></td>
        <td name="td1">Arnvig K. B.</td>
        <td name="td2">Riboswitches: choosing the best platform.</td>
        <td name="td3">Biochem Soc Trans</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32165489/" target="_blank"><b>2020</b></a></td>
        <td name="td1">Sherlock, M. E. & Breaker, R. R.</td>
        <td name="td2">Former orphan riboswitches reveal unexplored areas of bacterial metabolism, signaling, and gene control processes.</td>
        <td name="td3">RNA</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32036061/" target="_blank"><b>2020</b></a></td>
        <td name="td1">Bédard, A. V., Hien, E. D. M., & Lafontaine, D. A.</td>
        <td name="td2">Riboswitch regulation mechanisms: RNA, metabolites and regulatory proteins.</td>
        <td name="td3">Biochim Biophys Acta Gene Regul Mech</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33466288/" target="_blank"><b>2021</b></a></td>
        <td name="td1">Panchal, V., & Brenk, R.</td>
        <td name="td2">Riboswitches as drug targets for antibiotics.</td>
        <td name="td3">Antibiotics</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35595164/" target="_blank"><b>2022</b></a></td>
        <td name="td1">Hoetzel, J., & Suess, B.</td>
        <td name="td2">Structural changes in aptamers are essential for synthetic riboswitch engineering.</td>
        <td name="td3">J Mol Biol</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36275359/" target="_blank"><b>2022</b></a></td>
        <td name="td1">Vikram, Mishra, V., Rana, A., & Ahire, J. J.</td>
        <td name="td2">Riboswitch-mediated regulation of riboflavin biosynthesis genes in prokaryotes.</td>
        <td name="td3">3 Biotech</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36140022/" target="_blank"><b>2022</b></a></td>
        <td name="td1">Giarimoglou, N., Kouvela, A., Maniatis, A., Papakyriakou, A., Zhang, J., Stamatopoulou, V., & Stathopoulos, C.</td>
        <td name="td2">A riboswitch-driven era of new antibacterials.</td>
        <td name="td3">Antibiotics</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36150954/" target="_blank"><b>2023</b></a></td>
        <td name="td1">Kavita, K. & Breaker, R. R.</td>
        <td name="td2">Discovering riboswitches: the past and the future.</td>
        <td name="td3">Trends Biochem</td>
      </tr>

            
      <tr>
        <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36594112/" target="_blank"><b>2023</b></a></td>
        <td name="td1">Wakchaure, P. D., & Ganguly, B.</td>
        <td name="td2">Exploring the structure, function of thiamine pyrophosphate riboswitch, and designing small molecules for antibacterial activity.</td>
        <td name="td3">Wiley Interdiscip Rev RNA</td>
      </tr>

            
	</tbody>
    </table>
</div>        

<div id="sheet2" class="sheet">
    <h2>Articles</h2>
    <table id="researchtable" class="table-style1">
      <thead>
      <tr>
        <th onclick="sortTable(0)">Year</th>
        <th onclick="sortTable(3)">Riboswitch name</th>
        <th onclick="sortTable(1)">Author</th>
        <th onclick="sortTable(2)">Title</th>
         <th onclick="sortTable(4)">Journal</th>
        
        
      </tr>
      </thead>
      <tbody>
        
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/3052277/" target="_blank"><b>1988</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/2-dG" target="_blank"><b>2'-dG</b></a></td>
            <td name="td2">Reichard, P.<br></td>
            <td name="td3">Interactions between deoxyribonucleotide and DNA synthesis.</td>
            <td name="td4">Annu. Rev. Biochem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/1735721/" target="_blank"><b>1992</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/T-box" target="_blank"><b>T-box</b></a></td>
            <td name="td2">Henkin, T. M., Glass, B. L. & Grundy, F. J.<br></td>
            <td name="td3">Analysis of the Bacillus subtilis tyrS gene: conservation of a regulatory sequence in multiple tRNA synthetase genes.</td>
            <td name="td4">J. Bacteriol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/8348614/" target="_blank"><b>1993</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/T-box" target="_blank"><b>T-box</b></a></td>
            <td name="td2">Grundy, F. J. & Henkin, T. M.<br></td>
            <td name="td3">tRNA as a positive regulator of transcription antitermination in B. subtilis.</td>
            <td name="td4">Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/9098051/" target="_blank"><b>1997</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">Christiansen, L. C., Schou, S., Nygaard, P. & Saxild, H. H.<br></td>
            <td name="td3">Xanthine metabolism in Bacillus subtilis: characterization of the xpt-pbuX operon and evidence for purine- and nitrogen-controlled expression of genes involved in xanthine salvage and catabolism.</td>
            <td name="td4">J. Bacteriol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/9098051/" target="_blank"><b>1997</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanine" target="_blank"><b>Guanine</b></a></td>
            <td name="td2">Christiansen, L. C., Schou, S., Nygaard, P. & Saxild, H. H.<br></td>
            <td name="td3">Xanthine metabolism in Bacillus subtilis: characterization of the xpt-pbuX operon and evidence for purine- and nitrogen-controlled expression of genes involved in xanthine salvage and catabolism.</td>
            <td name="td4">J. Bacteriol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/10094622/" target="_blank"><b>1998</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Grundy, F. J. & Henkin, T. M.<br></td>
            <td name="td3">The S box regulon: a new global transcription termination control system for methionine and cysteine biosynthesis genes in gram-positive bacteria.</td>
            <td name="td4">Mol. Microbiol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/10529804/" target="_blank"><b>1999</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Gelfand, M. S., Mironov, A. A., Jomantas, J., Kozlov, Y. I. & Perumov, D. A.<br></td>
            <td name="td3">A conserved RNA structure element involved in the regulation of bacterial riboflavin synthesis genes.</td>
            <td name="td4">Trends Genet</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/10382260/" target="_blank"><b>1999</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Begley, T. P. et al.<br></td>
            <td name="td3">Thiamin biosynthesis in prokaryotes.</td>
            <td name="td4">Arch. Microbiol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/10382260/" target="_blank"><b>1999</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/HMP-PP" target="_blank"><b>HMP-PP</b></a></td>
            <td name="td2">Begley, T. P. et al.<br></td>
            <td name="td3">Thiamin biosynthesis in prokaryotes.</td>
            <td name="td4">Arch. Microbiol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/10852957/" target="_blank"><b>2000</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Nou, X. & Kadner, R. J.<br></td>
            <td name="td3">Adenosylcobalamin inhibits ribosome binding to btuB RNA.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/11470904/" target="_blank"><b>2001</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Miranda-Ríos, J., Navarro, M. & Soberón, M.<br></td>
            <td name="td3">A conserved RNA structure (thi box) is involved in regulation of thiamin biosynthetic gene expression in bacteria.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12136096/" target="_blank"><b>2002</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Vitreschak, A. G., Rodionov, D. A., Mironov, A. A. & Gelfand, M. S.<br></td>
            <td name="td3">Regulation of riboflavin biosynthesis and transport genes in bacteria by transcriptional and translational attenuation.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12456892/" target="_blank"><b>2002</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Winkler, W. C., Cohen-Chalamish, S. & Breaker, R. R.<br></td>
            <td name="td3">An mRNA structure that controls gene expression by binding FMN.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12410317/" target="_blank"><b>2002</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Winkler, W., Nahvi, A. & Breaker, R. R.<br></td>
            <td name="td3">Thiamine derivatives bind messenger RNAs directly to regulate bacterial gene expression.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12323379/" target="_blank"><b>2002</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Nahvi, A. et al.<br></td>
            <td name="td3">Genetic control by a metabolite binding mRNA.</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/14523230/" target="_blank"><b>2003</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Grundy, F. J., Lehman, S. C. & Henkin, T. M.<br></td>
            <td name="td3">The L box regulon: lysine sensing by leader RNAs of bacterial lysine biosynthesis genes</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/14597663/" target="_blank"><b>2003</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Sudarsan, N., Wickiser, J. K., Nakamura, S., Ebert, M. S. & Breaker, R. R.<br></td>
            <td name="td3">An mRNA structure in bacteria that controls gene expression by binding lysine</td>
            <td name="td4">Genes Dev</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12923093/" target="_blank"><b>2003</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">Johansen, L. E., Nygaard, P., Lassen, C., Agersø, Y. & Saxild, H. H.<br></td>
            <td name="td3">Definition of a second Bacillus subtilis pur regulon comprising the pur and  xpt-pbuX operons plus pbuG, nupG (yxjA), and pbuE (ydhL).</td>
            <td name="td4">J. Bacteriol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12787499/" target="_blank"><b>2003</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanine" target="_blank"><b>Guanine</b></a></td>
            <td name="td2">Mandal, M., Boese, B., Barrick, J. E., Winkler, W. C. & Breaker, R. R.<br></td>
            <td name="td3">Riboswitches Control Fundamental Biochemical Pathways in Bacillus subtilis and Other Bacteria.</td>
            <td name="td4">Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12756322/" target="_blank"><b>2003</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Sudarsan, N., Barrick, J. E. & Breaker, R. R.<br></td>
            <td name="td3">Metabolite-binding RNA domains are present in the genes of eukaryotes.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12910260/" target="_blank"><b>2003</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Winkler, W. C., Nahvi, A., Sudarsan, N., Barrick, J. E., & Breaker, R. R<br></td>
            <td name="td3">An mRNA structure that controls gene expression by binding S-adenosylmethionine.</td>
            <td name="td4">Nat. Struct. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12626738/" target="_blank"><b>2003</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">McDaniel, B. A., Grundy, F. J., Artsimovitch, I., & Henkin, T. M.<br></td>
            <td name="td3">Transcription termination control of the S box system: direct measurement of S-adenosylmethionine by the leader RNA.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12923257/" target="_blank"><b>2003</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Vitreschak, A. G., Rodionov, D. A., Mironov, A. A. & Gelfand, M. S.<br></td>
            <td name="td3">Regulation of the vitamin B12 metabolism and transport in bacteria by a conserved RNA structural element.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/12869542/" target="_blank"><b>2003</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Rodionov, D. A., Vitreschak, A. G., Mironov, A. A. & Gelfand, M. S.<br></td>
            <td name="td3">Comparative genomics of the vitamin B12 metabolism and regulation in prokaryotes.</td>
            <td name="td4">J. Biol. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/14675766/" target="_blank"><b>2003</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Kubodera, T., M. Watanabe, K. Yoshiuchi, N. Yamashita, A. Nishimura, S. Nakai, K. Gomi and H. Hanamoto.<br></td>
            <td name="td3">Thiamine-regulated gene expression of Aspergillus oryzae thiA requires splicing of the intron containing a riboswitch-like domain in the 5'-UTR</td>
            <td name="td4">FEBS Lett</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/14718920/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">Mandal, M. & Breaker, R. R.<br></td>
            <td name="td3">Adenine riboswitches and gene activation by disruption of a transcription terminator.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15610857/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">Serganov, A. et al.<br></td>
            <td name="td3">Structural Basis for Discriminative Regulation of Gene Expression by Adenine- and Guanine-Sensing mRNAs.</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15610857/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanine" target="_blank"><b>Guanine</b></a></td>
            <td name="td2">Serganov, A. et al.<br></td>
            <td name="td3">Structural Basis for Discriminative Regulation of Gene Expression by Adenine- and Guanine-Sensing mRNAs.</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15096624/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ppGpp" target="_blank"><b>ppGpp</b></a></td>
            <td name="td2">Barrick, J. E. et al.<br></td>
            <td name="td3">New RNA motifs suggest an expanded scope for riboswitches in bacterial genetic control.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15096624/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PRPP" target="_blank"><b>PRPP</b></a></td>
            <td name="td2">Barrick, J. E. et al.<br></td>
            <td name="td3">New RNA motifs suggest an expanded scope for riboswitches in bacterial genetic control.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15096624/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ADP" target="_blank"><b>ADP</b></a></td>
            <td name="td2">Barrick, J. E. et al.<br></td>
            <td name="td3">New RNA motifs suggest an expanded scope for riboswitches in bacterial genetic control.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15096624/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-AMP" target="_blank"><b>c-di-AMP</b></a></td>
            <td name="td2">Barrick, J. E. et al.<br></td>
            <td name="td3">New RNA motifs suggest an expanded scope for riboswitches in bacterial genetic control.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15096624/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Magnesium" target="_blank"><b>Magnesium</b></a></td>
            <td name="td2">Barrick, J. E. et al.<br></td>
            <td name="td3">New RNA motifs suggest an expanded scope for riboswitches in bacterial genetic control.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15096624/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Manganese" target="_blank"><b>Manganese</b></a></td>
            <td name="td2">Barrick, J. E. et al.<br></td>
            <td name="td3">New RNA motifs suggest an expanded scope for riboswitches in bacterial genetic control.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15549109/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanine" target="_blank"><b>Guanine</b></a></td>
            <td name="td2">Batey, R. T., Gilbert, S. D. & Montange, R. K.<br></td>
            <td name="td3">Structure of a natural guanine-responsive riboswitch complexed with the  metabolite hypoxanthine.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15029187" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Winkler, W. C., Nahvi, A., Roth, A., Collins, J. A. & Breaker, R. R.<br></td>
            <td name="td3">Control of gene expression by a natural metabolite-responsive ribozyme.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15048102" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Knudsen, S. M. & Ellington, A. D.<br></td>
            <td name="td3">Ribozyme déjà vu.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15472076/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Mandal, M. et al.<br></td>
            <td name="td3">A glycine-dependent riboswitch that uses cooperative binding to control gene expression</td>
            <td name="td4">Science</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/14704351/" target="_blank"><b>2004</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Nahvi, A., Barrick, J. E. & Breaker, R. R.<br></td>
            <td name="td3">Coenzyme B12 riboswitches are widespread genetic control elements in prokaryotes.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15890195/" target="_blank"><b>2005</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/T-box" target="_blank"><b>T-box</b></a></td>
            <td name="td2">Yousef, M. R., Grundy, F. J. & Henkin, T. M.<br></td>
            <td name="td3">Structural transitions induced by the interaction between tRNA(Gly) and the Bacillus subtilis glyQS T box leader RNA.</td>
            <td name="td4">J. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15808508/" target="_blank"><b>2005</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Wickiser, J. K., Winkler, W. C., Breaker, R. R. & Crothers, D. M.<br></td>
            <td name="td3">The speed of RNA transcription and metabolite binding kinetics operate an FMN riboswitch.</td>
            <td name="td4">Mol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16201765/" target="_blank"><b>2005</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">Wickiser, J. K., Cheah, M. T., Breaker, R. R. & Crothers, D. M.<br></td>
            <td name="td3">The Kinetics of Ligand Binding by an Adenine-Sensing Riboswitch.</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16261263/" target="_blank"><b>2005</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>MoCo</b></a></td>
            <td name="td2">Schwarz, G.<br></td>
            <td name="td3">Molybdenum cofactor biosynthesis and deficiency.</td>
            <td name="td4">Cell. Mol. Life Sci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16261263/" target="_blank"><b>2005</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>Wco</b></a></td>
            <td name="td2">Schwarz, G.<br></td>
            <td name="td3">Molybdenum cofactor biosynthesis and deficiency.</td>
            <td name="td4">Cell. Mol. Life Sci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/15862294/" target="_blank"><b>2005</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Yamauchi, T. et al.<br></td>
            <td name="td3">Roles of Mg2+ in TPP-dependent riboswitch.</td>
            <td name="td4">FEBS Lett</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16356850/" target="_blank"><b>2005</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Sudarsan, N., Cohen-Chalamish, S., Nakamura, S., Emilsson, G. M. & Breaker, R. R.<br></td>
            <td name="td3">Thiamine pyrophosphate riboswitches are targets for the antimicrobial compound pyrithiamine.</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16086852/" target="_blank"><b>2005</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Corbino, K. A., Barrick, J. E., Lim, J., Welz, R., Tucker, B. J., Puskarz, I., Mandal, M., Rudnick, N. D., & Breaker, R. R.<br></td>
            <td name="td3">Evidence for a second class of S-adenosylmethionine riboswitches and other regulatory RNA motifs in alpha-proteobacteria.</td>
            <td name="td4">Genome Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16931335/" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">Lemay, J. F., Penedo, J. C., Tremblay, R., Lilley, D. M. & Lafontaine, D. A.<br></td>
            <td name="td3">Folding of the Adenine Riboswitch.</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16650860/" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanine" target="_blank"><b>Guanine</b></a></td>
            <td name="td2">Gilbert, S. D., Stoddard, C. D., Wise, S. J. & Batey, R. T.<br></td>
            <td name="td3">Thermodynamic and Kinetic Characterization of Ligand Binding to the Purine Riboswitch Aptamer Domain.</td>
            <td name="td4">J. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16615891/" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Magnesium" target="_blank"><b>Magnesium</b></a></td>
            <td name="td2">Cromie, M. J., Shi, Y., Latifi, T. & Groisman, E. A.<br></td>
            <td name="td3">An RNA sensor for intracellular Mg(2+).</td>
            <td name="td4">Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16699515" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Jansen, J. A., McCarthy, T. J., Soukup, G. A. & Soukup, J. K.<br></td>
            <td name="td3">Backbone and nucleobase contacts to glucosamine-6-phosphate in the glmS ribozyme.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16990543" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Klein, D. J. & Ferré-D’Amaré, A. R.<br></td>
            <td name="td3">Structural basis of glmS ribozyme activation by glucosamine-6-phosphate.</td>
            <td name="td4">Science</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16464827" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Soukup, G. A.<br></td>
            <td name="td3">Core requirements for glmS ribozyme self-cleavage reveal a putative pseudoknot structure.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16675665/" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Thore, S., Leibundgut, M. & Ban, N.<br></td>
            <td name="td3">Structure of the eukaryotic thiamine pyrophosphate riboswitch with its regulatory ligand.</td>
            <td name="td4">Science</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16728979/" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Serganov, A., Polonskaia, A., Phan, A. T., Breaker, R. R. & Patel, D. J.<br></td>
            <td name="td3">Structural basis for gene regulation by a thiamine pyrophosphate-sensing riboswitch.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16962976/" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Edwards, T. E. & Ferré-D’Amaré, A. R.<br></td>
            <td name="td3">Crystal Structures of the Thi-Box Riboswitch Bound to Thiamine Pyrophosphate Analogs Reveal Adaptive RNA-Small Molecule. Recognition</td>
            <td name="td4">Structure</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16810258/" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Montange, R. K., & Batey, R. T.<br></td>
            <td name="td3">Structure of the S-adenosylmethionine riboswitch regulatory mRNA element.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16381055/" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Lim, J., Winkler, W. C., Nakamura, S., Scott, V., & Breaker, R. R.<br></td>
            <td name="td3">Molecular-recognition characteristics of SAM-binding riboswitches.</td>
            <td name="td4">Angew. Chem. Int. Ed Engl</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16491091/" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Fuchs, R. T., Grundy, F. J., & Henkin, T. M.<br></td>
            <td name="td3">The S(MK) box is a new SAM-binding RNA for translational regulation of SAM synthetase.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/16484375" target="_blank"><b>2006</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Roth, A., Nahvi, A., Lee, M., Jona, I. & Breaker, R. R.<br></td>
            <td name="td3">Characteristics of the glmS ribozyme suggest only structural roles for divalent metal ions.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17585050/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Blouin, S. & Lafontaine, D. A.<br></td>
            <td name="td3">A loop loop interaction and a K-turn motif located in the lysine aptamer domain are important for the riboswitch gene regulation control</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17143270/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Blount, K. F., Wang, J. X., Lim, J., Sudarsan, N. & Breaker, R. R.<br></td>
            <td name="td3">Antibacterial lysine analogs that target lysine riboswitches</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17621584/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>MoCo</b></a></td>
            <td name="td2">Weinberg, Z. et al.<br></td>
            <td name="td3">Identification of 22 candidate structured RNAs in bacteria using the CMfinder comparative genomics pipeline.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17621584/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>Wco</b></a></td>
            <td name="td2">Weinberg, Z. et al.<br></td>
            <td name="td3">Identification of 22 candidate structured RNAs in bacteria using the CMfinder comparative genomics pipeline.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17621584/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Weinberg, Z. et al.<br></td>
            <td name="td3">Identification of 22 candidate structured RNAs in bacteria using the CMfinder comparative genomics pipeline.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17621584/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-AMP-GMP" target="_blank"><b>c-AMP-GMP</b></a></td>
            <td name="td2">Weinberg, Z. et al.<br></td>
            <td name="td3">Identification of 22 candidate structured RNAs in bacteria using the CMfinder comparative genomics pipeline.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17621584/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-GMP" target="_blank"><b>c-di-GMP</b></a></td>
            <td name="td2">Weinberg, Z. et al.<br></td>
            <td name="td3">Identification of 22 candidate structured RNAs in bacteria using the CMfinder comparative genomics pipeline.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17911257/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/2-dG" target="_blank"><b>2'-dG</b></a></td>
            <td name="td2">Kim, J. N., Roth, A. & Breaker, R. R.<br></td>
            <td name="td3">Guanine riboswitch variants from Mesoplasma florum selectively recognize  2'-deoxyguanosine.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17803910/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Magnesium" target="_blank"><b>Magnesium</b></a></td>
            <td name="td2">Dann, C. E., 3rd et al.<br></td>
            <td name="td3">Structure and mechanism of a metal-sensing regulatory RNA.</td>
            <td name="td4">Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18006684/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Bocobza, S. et al.<br></td>
            <td name="td3">Riboswitch-dependent gene regulation and its evolution in the plant kingdom.</td>
            <td name="td4">Genes Dev</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17468745/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Cheah, M. T., Wachter, A., Sudarsan, N. & Breaker, R. R.<br></td>
            <td name="td3">Control of alternative RNA splicing and gene expression by eukaryotic riboswitches.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17993623/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Wachter, A. et al.<br></td>
            <td name="td3">Riboswitch control of gene expression in plants by splicing and alternative 3' end processing of mRNAs.</td>
            <td name="td4">Plant Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17118400/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Lipfert, J. et al.<br></td>
            <td name="td3">Structural transitions and thermodynamics of a glycine-dependent riboswitch from Vibrio cholerae</td>
            <td name="td4">J. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17616982/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Yao, Z., Barrick, J., Weinberg, Z., Neph, S., Breaker, R., Tompa, M., and Ruzzo, W.L.<br></td>
            <td name="td3">A computational pipeline for high-throughput discovery of cis-regulatory noncoding RNA in prokaryotes.</td>
            <td name="td4">PLoS Comput. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17384645/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Roth, A. et al<br></td>
            <td name="td3">A riboswitch selective for the queuosine precursor preQ1 contains an unusually small aptamer domain</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/17360376/" target="_blank"><b>2007</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Fuchs, R. T., Grundy, F. J., & Henkin, T. M.<br></td>
            <td name="td3">S-adenosylmethionine directly inhibits binding of 30S ribosomal subunits to the S(MK) box translational riboswitch RNA.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18593706/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Garst, A. D., Héroux, A., Rambo, R. P. & Batey, R. T.<br></td>
            <td name="td3">Crystal structure of the lysine riboswitch regulatory mRNA element</td>
            <td name="td4">J. Biol. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18784651/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Serganov, A., Huang, L. & Patel, D. J.<br></td>
            <td name="td3">Structural insights into amino acid binding and gene control by a lysine riboswitch</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18374645/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAH" target="_blank"><b>SAH</b></a></td>
            <td name="td2">Wang, J. X., Lee, E. R., Morales, D. R., Lim, J., & Breaker, R. R.<br></td>
            <td name="td3">Riboswitches that sense S-adenosylhomocysteine and activate genes involved in coenzyme recycling.</td>
            <td name="td4">Mol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18363797/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>MoCo</b></a></td>
            <td name="td2">Regulski, E. E. et al.<br></td>
            <td name="td3">A widespread riboswitch candidate that controls bacterial genes involved in molybdenum cofactor and tungsten cofactor metabolism.</td>
            <td name="td4">Mol. Microbiol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18363797/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>Wco</b></a></td>
            <td name="td2">Regulski, E. E. et al.<br></td>
            <td name="td3">A widespread riboswitch candidate that controls bacterial genes involved in molybdenum cofactor and tungsten cofactor metabolism.</td>
            <td name="td4">Mol. Microbiol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18154309/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>MoCo</b></a></td>
            <td name="td2">Bevers, L. E. et al.<br></td>
            <td name="td3">Function of MoaB proteins in the biosynthesis of the molybdenum and tungsten cofactors.</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18154309/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>Wco</b></a></td>
            <td name="td2">Bevers, L. E. et al.<br></td>
            <td name="td3">Function of MoaB proteins in the biosynthesis of the molybdenum and tungsten cofactors.</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18533652/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Thore, S., Frick, C. & Ban, N.<br></td>
            <td name="td3">Structural basis of thiamine pyrophosphate analogues binding to the eukaryotic riboswitch.</td>
            <td name="td4">J. Am. Chem. Soc</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18042658/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Kwon, M. & Strobel, S. A.<br></td>
            <td name="td3">Chemical basis of glycine riboswitch cooperativity</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18369181/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Weinberg, Z., Regulski, E. E., Hammond, M. C., Barrick, J. E., Yao, Z., Ruzzo, W. L., & Breaker, R. R.<br></td>
            <td name="td3">The aptamer core of SAM-IV riboswitches mimics the ligand-binding site of SAM-I riboswitches.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18204466/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Gilbert, S. D., Rambo, R. P., Van Tyne, D., & Batey, R. T.<br></td>
            <td name="td3">Structure of the SAM-II riboswitch bound to S-adenosylmethionine.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18305186/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Meyer, M. M., Roth, A., Chervin, S. M., Garcia, G. A. & Breaker, R. R<br></td>
            <td name="td3">Confirmation of a second natural preQ1 aptamer class in Streptococcaceae bacteria</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18806797/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Lu, C., Smith, A. M., Fuchs, R. T., Ding, F., Rajashankar, K., Henkin, T. M., & Ke, A.<br></td>
            <td name="td3">Crystal structures of the SAM-III/S(MK) riboswitch reveal the SAM-dependent translation inhibition mechanism.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/18635805/" target="_blank"><b>2008</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-GMP" target="_blank"><b>c-di-GMP</b></a></td>
            <td name="td2">Sudarsan, N. et al.<br></td>
            <td name="td3">Riboswitches in eubacteria sense the second messenger cyclic di-GMP</td>
            <td name="td4">Science</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19258532/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/T-box" target="_blank"><b>T-box</b></a></td>
            <td name="td2">Gutiérrez-Preciado, A., Henkin, T. M., Grundy, F. J., Yanofsky, C. & Merino, E.<br></td>
            <td name="td3">Biochemical features and functional implications of the RNA-based T-box regulatory mechanism.</td>
            <td name="td4">Microbiol. Mol. Biol. Rev</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19246992/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Lee, E. R., Blount, K. F. & Breaker, R. R.<br></td>
            <td name="td3">Roseoflavin is a natural antibacterial compound that binds to FMN riboswitches and regulates gene expression.</td>
            <td name="td4">RNA Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19169240/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Serganov, A., Huang, L. & Patel, D. J.<br></td>
            <td name="td3">Coenzyme recognition and gene regulation by a flavin mononucleotide riboswitch.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19523903/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanine" target="_blank"><b>Guanine</b></a></td>
            <td name="td2">Gilbert, S. D., Reyes, F. E., Edwards, A. L. & Batey, R. T.<br></td>
            <td name="td3">Adaptive Ligand Binding by the Purine Riboswitch in the Recognition of Guanine and Adenine Analogs.</td>
            <td name="td4">Structure</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19619558/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Magnesium" target="_blank"><b>Magnesium</b></a></td>
            <td name="td2">Wakeman, C. A., Ramesh, A. & Winkler, W. C.<br></td>
            <td name="td3">Multiple metal-binding cores are required for metalloregulation by M-box riboswitch RNAs.</td>
            <td name="td4">J. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19228039" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Cochrane, J. C., Lipchock, S. V., Smith, K. D. & Strobel, S. A.<br></td>
            <td name="td3">Structural and chemical basis for glucosamine 6-phosphate binding and activation of the glmS ribozyme.</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19531245/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Meyer, M. M., Ames, T. D., Smith, D. P., Weinberg, Z., Schwalbach, M. S., Giovannoni, S. J., & Breaker, R. R.<br></td>
            <td name="td3">Identification of candidate structured RNAs in the marine organism 'Candidatus Pelagibacter Ubique'.</td>
            <td name="td4">BMC Genomics</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19776155/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Poiata, E., Meyer, M. M., Ames, T. D., & Breaker, R. R.<br></td>
            <td name="td3">A variant riboswitch aptamer class for S-adenosylmethionine common in marine bacteria.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19234468/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Klein, D. J., Edwards, T. E. & Ferré-D’Amaré, A. R.<br></td>
            <td name="td3">Cocrystal structure of a class I preQ1 riboswitch reveals a pseudoknot recognizing an essential hypermodified nucleobase.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19285444/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Kang, M., Peterson, R. & Feigon, J.<br></td>
            <td name="td3">Structural Insights into riboswitch control of the biosynthesis of queuosine, a  modified nucleotide found in the anticodon of Trna.</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19261617/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Spitale, R. C., Torelli, A. T., Krucinska, J., Bandarian, V. & Wedekind, J. E.<br></td>
            <td name="td3">The Structural Basis for Recognition of the PreQ0 Metabolite by an Unusually Small Riboswitch Aptamer Domain.</td>
            <td name="td4">J. Biol. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19898477/" target="_blank"><b>2009</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-GMP" target="_blank"><b>c-di-GMP</b></a></td>
            <td name="td2">Smith, K. D. et al<br></td>
            <td name="td3">Structural basis of ligand binding by a c-di-GMP riboswitch</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20022916/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">Delfosse, V. et al.<br></td>
            <td name="td3">Riboswitch structure: an internal residue mimicking the purine ligand.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20864509/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAH" target="_blank"><b>SAH</b></a></td>
            <td name="td2">Edwards, A. L., Reyes, F. E., Héroux, A., & Batey, R. T.<br></td>
            <td name="td3">Structural basis for recognition of S-adenosylhomocysteine by riboswitches.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20435898/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAH" target="_blank"><b>SAH</b></a></td>
            <td name="td2">Chou, M. Y., Lin, S. C., & Chang, K. Y.<br></td>
            <td name="td3">Stimulation of -1 programmed ribosomal frameshifting by a metabolite-responsive RNA pseudoknot.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20230605/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Weinberg, Z., Wang, J. X., Bogue, J., Yang, J., Corbino, K., Moy, R. H., & Breaker, R. R.<br></td>
            <td name="td3">Comparative genomics reveals 104 candidate structured RNAs from bacteria, archaea, and their metagenomes.</td>
            <td name="td4">Genome Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20230605/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Weinberg, Z., Wang, J. X., Bogue, J., Yang, J., Corbino, K., Moy, R. H., & Breaker, R. R.<br></td>
            <td name="td3">Comparative genomics reveals 104 candidate structured RNAs from bacteria, archaea, and their metagenomes.</td>
            <td name="td4">Genome Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20230605/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-SAH" target="_blank"><b>SAM-SAH</b></a></td>
            <td name="td2">Weinberg, Z., Wang, J. X., Bogue, J., Yang, J., Corbino, K., Moy, R. H., & Breaker, R. R.<br></td>
            <td name="td3">Comparative genomics reveals 104 candidate structured RNAs from bacteria, archaea, and their metagenomes.</td>
            <td name="td4">Genome Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20230605/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Weinberg, Z., Wang, J. X., Bogue, J., Yang, J., Corbino, K., Moy, R. H., & Breaker, R. R.<br></td>
            <td name="td3">Comparative genomics reveals 104 candidate structured RNAs from bacteria, archaea, and their metagenomes.</td>
            <td name="td4">Genome Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20230605/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Fluoride" target="_blank"><b>Fluoride</b></a></td>
            <td name="td2">Weinberg, Z., Wang, J. X., Bogue, J., Yang, J., Corbino, K., Moy, R. H., & Breaker, R. R.<br></td>
            <td name="td3">Comparative genomics reveals 104 candidate structured RNAs from bacteria, archaea, and their metagenomes.</td>
            <td name="td4">Genome Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/19948769/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Kulshina, N., Edwards, T. E. & Ferré-D’Amaré, A. R.<br></td>
            <td name="td3">Thermodynamic analysis of ligand binding and ligand binding-induced tertiary structure formation by the thiamine pyrophosphate. riboswitch</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21145485/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Huang, L., Serganov, A. & Patel, D. J.<br></td>
            <td name="td3">Structural insights into ligand recognition by a sensing domain of the cooperative glycine riboswitch</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20194520/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Lipfert, J., Sim, A. Y. L., Herschlag, D. & Doniach, S.<br></td>
            <td name="td3">Dissecting electrostatic screening, specific ion binding, and ligand binding in an energetic model for glycine riboswitch folding</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20006621/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Montange, R. K., Mondragón, E., van Tyne, D., Garst, A. D., Ceres, P., & Batey, R. T.<br></td>
            <td name="td3">Discrimination between closely related cellular metabolites by the SAM-I riboswitch.</td>
            <td name="td4">J. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20637415/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Stoddard, C. D., Montange, R. K., Hennelly, S. P., Rambo, R. P., Sanbonmatsu, K. Y., & Batey, R. T.<br></td>
            <td name="td3">Free state conformational sampling of the SAM-I riboswitch aptamer domain.</td>
            <td name="td4">Structure</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20951706/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Lu, C., Ding, F., Chowdhury, A., Pradhan, V., Tomsic, J., Holmes, W. M., Henkin, T. M., & Ke, A.<br></td>
            <td name="td3">SAM recognition and conformational switching mechanism in the Bacillus subtilis yitJ S box/SAM-I riboswitch.</td>
            <td name="td4">J. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20659680/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/THF" target="_blank"><b>THF</b></a></td>
            <td name="td2">Ames, T. D., Rodionov, D. A., Weinberg, Z. & Breaker, R. R.<br></td>
            <td name="td3">A eubacterial riboswitch class that senses the coenzyme tetrahydrofolate.</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20534493/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Rieder, U., Kreutz, C. & Micura, R.<br></td>
            <td name="td3">Folding of a transcriptionally acting preQ1 riboswitch.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20614931/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Priyakumar U. D.<br></td>
            <td name="td3">Atomistic details of the ligand discrimination mechanism of S(MK)/SAM-III riboswitch.</td>
            <td name="td4">J. Phys. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21143313/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Smith, A. M., Fuchs, R. T., Grundy, F. J., & Henkin, T. M.<br></td>
            <td name="td3">The SAM-responsive S(MK) box is a reversible riboswitch.</td>
            <td name="td4">Mol. Microbiol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20690679/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-GMP" target="_blank"><b>c-di-GMP</b></a></td>
            <td name="td2">Smith, K. D., Lipchock, S. V., Livingston, A. L., Shanahan, C. A. & Strobel, S. A.<br></td>
            <td name="td3">Structural and biochemical determinants of ligand binding by the c-di-GMP riboswitch</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/20705859/" target="_blank"><b>2010</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-GMP" target="_blank"><b>c-di-GMP</b></a></td>
            <td name="td2">Lee, E. R., Baker, J. L., Weinberg, Z., Sudarsan, N. & Breaker, R. R.<br></td>
            <td name="td3">An allosteric self-splicing ribozyme triggered by a bacterial second messenger</td>
            <td name="td4">Science</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21282981/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glutamine" target="_blank"><b>Glutamine</b></a></td>
            <td name="td2">Ames, T. D. & Breaker, R. R.<br></td>
            <td name="td3">Bacterial aptamers that selectively bind glutamine</td>
            <td name="td4">RNA Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21169337/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Blouin, S., Chinnappan, R. & Lafontaine, D. A.<br></td>
            <td name="td3">Folding of the lysine riboswitch: importance of peripheral elements for transcriptional regulation</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21745821/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Vicens, Q., Mondragón, E. & Batey, R. T.<br></td>
            <td name="td3">Molecular sensing by the aptamer domain of the FMN riboswitch: a general model for ligand binding by conformational selection.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21841796/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/2-dG" target="_blank"><b>2'-dG</b></a></td>
            <td name="td2">Pikovskaya, O., Polonskaia, A., Patel, D. J. & Serganov, A.<br></td>
            <td name="td3">Structural principles of nucleoside selectivity in a 2′-deoxyguanosine riboswitch.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21890900/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanine" target="_blank"><b>Guanine</b></a></td>
            <td name="td2">Buck, J. et al.<br></td>
            <td name="td3">Influence of ground-state structure and Mg 2+ binding on folding kinetics of the guanine-sensing riboswitch aptamer domain.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21315082/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Magnesium" target="_blank"><b>Magnesium</b></a></td>
            <td name="td2">Ramesh, A., Wakeman, C. A. & Winkler, W. C.<br></td>
            <td name="td3">Insights into metalloregulation by M-box riboswitch RNAs via structural analysis of manganese-bound complexes.</td>
            <td name="td4">J. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21317896" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Watson, P. Y. & Fedor, M. J.<br></td>
            <td name="td3">The glmS riboswitch integrates signals from activating and inhibitory metabolites in vivo.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21439473/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Butler, E. B., Xiong, Y., Wang, J. & Strobel, S. A.<br></td>
            <td name="td3">Structural basis of cooperative ligand binding by the glycine riboswitch</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21098652/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Erion, T. V. & Strobel, S. A.<br></td>
            <td name="td3">Identification of a tertiary interaction important for cooperative ligand binding by the glycine riboswitch</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21532599/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Heppell, B., Blouin, S., Dussault, A. M., Mulhbacher, J., Ennifar, E., Penedo, J. C., & Lafontaine, D. A.<br></td>
            <td name="td3">Molecular insights into the ligand-controlled organization of the SAM-I riboswitch.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21873197/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/THF" target="_blank"><b>THF</b></a></td>
            <td name="td2">Huang, L., Ishibe-Murakami, S., Patel, D. J. & Serganov, A.<br></td>
            <td name="td3">Long-range pseudoknot interactions dictate the regulatory response in the tetrahydrofolate riboswitch.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21906956/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/THF" target="_blank"><b>THF</b></a></td>
            <td name="td2">Trausch, J. J., Ceres, P., Reyes, F. E. & Batey, R. T.<br></td>
            <td name="td3">The structure of a tetrahydrofolate-sensing riboswitch reveals two ligand binding sites in a single aptamer.</td>
            <td name="td4">Structure</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21532598/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Haller, A., Rieder, U., Aigner, M., Blanchard, S. C., & Micura, R.<br></td>
            <td name="td3">Conformational capture of the SAM-II riboswitch.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21592962/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Jenkins, J. L., Krucinska, J., McCarty, R. M., Bandarian, V. & Wedekind, J. E.<br></td>
            <td name="td3">Comparison of a PreQ1 Riboswitch Aptamer in Metabolite-bound and Free States with Implications for Gene Regulation.</td>
            <td name="td4">J. Biol. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21549712/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Lu, C., Smith, A. M., Ding, F., Chowdhury, A., Henkin, T. M., & Ke, A.<br></td>
            <td name="td3">Variable sequences outside the SAM-binding core critically influence the conformational dynamics of the SAM-III/SMK box riboswitch.</td>
            <td name="td4">J. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/21518891/" target="_blank"><b>2011</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-GMP" target="_blank"><b>c-di-GMP</b></a></td>
            <td name="td2">Smith, K. D., Shanahan, C. A., Moore, E. L., Simon, A. C. & Strobel, S. A.<br></td>
            <td name="td3">Structural basis of differential ligand recognition by two classes of bis-(3'-5')-cyclic dimeric guanosine monophosphate-binding riboswitches</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22771573/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Garst, A. D., Porter, E. B. & Batey, R. T.<br></td>
            <td name="td3">Insights into the regulatory landscape of the lysine riboswitch</td>
            <td name="td4">J. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22961337/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Budhathoki, P., Bernal-Perez, L. F., Annunziata, O. & Ryu, Y.<br></td>
            <td name="td3">Rationally-designed fluorescent lysine riboswitch probes</td>
            <td name="td4">Org. Biomol. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22416067/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Wilson-Mitchell, S. N., Grundy, F. J. & Henkin, T. M.<br></td>
            <td name="td3">Analysis of lysine recognition and specificity of the Bacillus subtilis L box riboswitch</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23087247/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">Frieda, K. L. & Block, S. M.<br></td>
            <td name="td3">Direct observation of cotranscriptional folding in an adenine riboswitch.</td>
            <td name="td4">Science</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23113700" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Viladoms, J. & Fedor, M. J.<br></td>
            <td name="td3">The glmS ribozyme cofactor is a general acid-base catalyst.</td>
            <td name="td4">J. Am. Chem. Soc</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22336759/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Eschbach, S. H., St-Pierre, P., Penedo, J. C., & Lafontaine, D. A.<br></td>
            <td name="td3">Folding of the SAM-I riboswitch: a tale with a twist.</td>
            <td name="td4">RNA Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22543867/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Boyapati, V. K., Huang, W., Spedale, J., & Aboul-Ela, F.<br></td>
            <td name="td3">Basis for ligand discrimination between ON and OFF state riboswitch conformations: the case of the SAM-I riboswitch.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23086297/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-AMP" target="_blank"><b>c-di-AMP</b></a></td>
            <td name="td2">Watson, P. Y. & Fedor, M. J.<br></td>
            <td name="td3">The ydaO motif is an ATP-sensing riboswitch in Bacillus subtilis.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23064232/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Johnson, J. E., Reyes, F. E., Polaski, J. T. & Batey, R. T.<br></td>
            <td name="td3">B12 cofactors directly stabilize an mRNA regulatory switch.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23064646/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Peselis, A. & Serganov, A.<br></td>
            <td name="td3">Structural insights into ligand binding and gene expression control by an adenosylcobalamin riboswitch.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22139931/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Chen, B., Zuo, X., Wang, Y. X., & Dayie, T. K.<br></td>
            <td name="td3">Multiple conformations of SAM-II riboswitch detected with SAXS and NMR spectroscopy.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22194311/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Doshi, U., Kelley, J. M., & Hamelberg, D.<br></td>
            <td name="td3">Atomic-level insights into metabolite recognition and specificity of the SAM-II riboswitch.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22775200/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Santner, T., Rieder, U., Kreutz, C. & Micura, R.<br></td>
            <td name="td3">Pseudoknot preorganization of the preQ1 class I riboswitch.</td>
            <td name="td4">J. Am. Chem. Soc</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22194412/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Fluoride" target="_blank"><b>Fluoride</b></a></td>
            <td name="td2">Baker, J. L. et al.<br></td>
            <td name="td3">Widespread genetic switches and toxicity resistance proteins for fluoride.</td>
            <td name="td4">Science</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22678284/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Fluoride" target="_blank"><b>Fluoride</b></a></td>
            <td name="td2">Ren, A., Rajashankar, K. R. & Patel, D. J.<br></td>
            <td name="td3">Fluoride ion encapsulation by Mg2+ ions and phosphates in a fluoride riboswitch.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/22148472/" target="_blank"><b>2012</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-GMP" target="_blank"><b>c-di-GMP</b></a></td>
            <td name="td2">Smith, K. D., Lipchock, S. V. & Strobel, S. A.<br></td>
            <td name="td3">Structural and biochemical characterization of linear dinucleotide analogues bound to the c-di-GMP-I aptamer</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23892783/" target="_blank"><b>2013</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/T-box" target="_blank"><b>T-box</b></a></td>
            <td name="td2">Zhang, J. & Ferré-D’Amaré, A. R.<br></td>
            <td name="td3">Co-crystal structure of a T-box riboswitch stem I domain in complex with its cognate tRNA.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23201473/" target="_blank"><b>2013</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>MoCo</b></a></td>
            <td name="td2">Iobbi-Nivol, C. & Leimkühler, .<br></td>
            <td name="td3">Molybdenum enzymes, their maturation and molybdenum cofactor biosynthesis in Escherichia coli.</td>
            <td name="td4">Biochim. Biophys</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23201473/" target="_blank"><b>2013</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>Wco</b></a></td>
            <td name="td2">Iobbi-Nivol, C. & Leimkühler, .<br></td>
            <td name="td3">Molybdenum enzymes, their maturation and molybdenum cofactor biosynthesis in Escherichia coli.</td>
            <td name="td4">Biochim. Biophys</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24141192/" target="_blank"><b>2013</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-AMP" target="_blank"><b>c-di-AMP</b></a></td>
            <td name="td2">Nelson, J. W. et al.<br></td>
            <td name="td3">Riboswitches in eubacteria sense the second messenger c-di-AMP.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23940363/" target="_blank"><b>2013</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Soulière, M. F. et al.<br></td>
            <td name="td3">Tuning a riboswitch response through structural extension of a pseudoknot.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23584677/" target="_blank"><b>2013</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Liberman, J. A., Salim, M., Krucinska, J. & Wedekind, J. E.<br></td>
            <td name="td3">Structure of a class II preQ1 riboswitch reveals ligand recognition by a new fold.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/23023210/" target="_blank"><b>2013</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-GMP" target="_blank"><b>c-di-GMP</b></a></td>
            <td name="td2">Kalia, D. et al.<br></td>
            <td name="td3">Nucleotide, c-di-GMP, c-di-AMP, cGMP, cAMP, (p)ppGpp signaling in bacteria and implications in pathogenesis</td>
            <td name="td4">Chem. Soc. Rev</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24863160/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Price IR, Grigg JC, Ke A.<br></td>
            <td name="td3">Common themes and differences in SAM recognition among SAM riboswitches.</td>
            <td name="td4">Biochim Biophys Acta</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24863160/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Price IR, Grigg JC, Ke A.<br></td>
            <td name="td3">Common themes and differences in SAM recognition among SAM riboswitches.</td>
            <td name="td4">Biochim Biophys Acta</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24863160/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Price IR, Grigg JC, Ke A.<br></td>
            <td name="td3">Common themes and differences in SAM recognition among SAM riboswitches.</td>
            <td name="td4">Biochim Biophys Acta</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24768306/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Warner, K. D. et al.<br></td>
            <td name="td3">Validating fragment-based drug discovery for biological RNAs: lead fragments bind and remodel the TPP riboswitch specifically.</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25246650/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Ruff, K. M. & Strobel, S. A.<br></td>
            <td name="td3">Ligand binding by the tandem glycine riboswitch depends on aptamer dimerization but not double ligand occupancy</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24753586/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Trausch, J. J., Xu, Z., Edwards, A. L., Reyes, F. E., Ross, P. E., Knight, R., & Batey, R. T.<br></td>
            <td name="td3">Structural basis for diversity in the SAM clan of riboswitches.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24388757/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/THF" target="_blank"><b>THF</b></a></td>
            <td name="td2">Trausch, J. J. & Batey, R. T.<br></td>
            <td name="td3">A disconnect between high-affinity binding and efficient regulation by antifolates and purines in the tetrahydrofolate riboswitch.</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25086509/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-AMP" target="_blank"><b>c-di-AMP</b></a></td>
            <td name="td2">Ren, A. & Patel, D. J.<br></td>
            <td name="td3">c-di-AMP binds the ydaO riboswitch in two pseudo-symmetry-related pockets.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25086507/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-AMP" target="_blank"><b>c-di-AMP</b></a></td>
            <td name="td2">Gao, A. & Serganov, A.<br></td>
            <td name="td3">Structural insights into recognition of c-di-AMP by the ydaO riboswitch.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25271255/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-AMP" target="_blank"><b>c-di-AMP</b></a></td>
            <td name="td2">Jones, C. P. & Ferré-D’Amaré, A. R.<br></td>
            <td name="td3">Crystal structure of a c-di-AMP riboswitch reveals an internally pseudo-dimeric RNA.</td>
            <td name="td4">EMBO J</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24243114/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Choudhary, P. K. & Sigel, R. K.<br></td>
            <td name="td3">Mg2+-induced conformational changes in the btuB riboswitch from E. coli.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/24469808/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Kang, M., Eichhorn, C. D. & Feigon, J.<br></td>
            <td name="td3">Structural determinants for ligand capture by a class II preQ1 riboswitch.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25036777/" target="_blank"><b>2014</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">McCown, P. J., Liang, J. J., Weinberg, Z. & Breaker, R. R.<br></td>
            <td name="td3">Structural, Functional, and Taxonomic Diversity of Three PreQ1 Riboswitch Classes.</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26655897/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glutamine" target="_blank"><b>Glutamine</b></a></td>
            <td name="td2">Ren, A. et al.<br></td>
            <td name="td3">Structural and Dynamic Basis for Low-Affinity, High-Selectivity Binding of L-Glutamine by the Glutamine Riboswitch</td>
            <td name="td4">Cell Rep</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26300047/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Zhou, L.-B. & Zeng, A.-P.<br></td>
            <td name="td3">Engineering a Lysine-ON Riboswitch for Metabolic Control of Lysine Production in Corynebacterium glutamicum</td>
            <td name="td4">ACS Synth. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25575181/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Zhou, L.-B. & Zeng, A.-P.<br></td>
            <td name="td3">Exploring lysine riboswitch for metabolic flux control and improvement of L-lysine synthesis in Corynebacterium glutamicum</td>
            <td name="td4">ACS Synth. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26403229/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Smith-Peter, E., Lamontagne, A.-M. & Lafontaine, D. A.<br></td>
            <td name="td3">Role of lysine binding residues in the global folding of the lysC riboswitch</td>
            <td name="td4">RNA Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25583497/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/T-box" target="_blank"><b>T-box</b></a></td>
            <td name="td2">Sherwood, A. V., Grundy, F. J. & Henkin, T. M.<br></td>
            <td name="td3">T box riboswitches in Actinobacteria: translational regulation via novel tRNA interactions.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26169403/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Blount, K. F. et al.<br></td>
            <td name="td3">Novel riboswitch-binding flavin analog that protects mice against Clostridium difficile infection without inhibiting cecal flora.</td>
            <td name="td4">Antimicrob. Agents Chemother</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26416753/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Howe, J. A. et al.<br></td>
            <td name="td3">Selective small-molecule inhibition of an RNA structural element.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25794617/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NiCo" target="_blank"><b>NiCo</b></a></td>
            <td name="td2">Furukawa, K. et al.<br></td>
            <td name="td3">Bacterial riboswitches cooperatively bind Ni(2+) or Co(2+) ions and control  expression of heavy metal transporters.</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25848023/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-AMP-GMP" target="_blank"><b>c-AMP-GMP</b></a></td>
            <td name="td2">Nelson, J. W. et al.<br></td>
            <td name="td3">Control of bacterial exoelectrogenesis by c-AMP-GMP.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25818298/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-AMP-GMP" target="_blank"><b>c-AMP-GMP</b></a></td>
            <td name="td2">Ren, A. et al.<br></td>
            <td name="td3">Structural basis for molecular discrimination by a 3',3'-cGAMP sensing riboswitch.</td>
            <td name="td4">Cell Rep</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25848022/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-AMP-GMP" target="_blank"><b>c-AMP-GMP</b></a></td>
            <td name="td2">Kellenberger, C. A. et al.<br></td>
            <td name="td3">GEMM-I riboswitches from Geobacter sense the bacterial second messenger cyclic AMP-GMP.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25616067/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Kim, P. B., Nelson, J. W. & Breaker, R. R.<br></td>
            <td name="td3">An ancient riboswitch class in bacteria regulates purine biosynthesis and one-carbon metabolism</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26118534/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Ren, A., Rajashankar, K. R. & Patel, D. J.<br></td>
            <td name="td3">Global RNA Fold and Molecular Recognition for a pfl Riboswitch Bound to ZMP, a Master Regulator of One-Carbon Metabolism</td>
            <td name="td4">Structure</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26144884/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Trausch, J. J., Marcano-Velázquez, J. G., Matyjasik, M. M. & Batey, R. T.<br></td>
            <td name="td3">Metal Ion-Mediated Nucleobase Recognition by the ZTP Riboswitch</td>
            <td name="td4">Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26280533/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Jones, C. P. & Ferré-D’Amaré, A. R.<br></td>
            <td name="td3">Recognition of the bacterial alarmone ZMP through long-distance association of two RNA subdomains</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26223188/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanine" target="_blank"><b>Guanine</b></a></td>
            <td name="td2">Hernandez, A. R. et al.<br></td>
            <td name="td3">A Crystal Structure of a Functional RNA Molecule Containing an Artificial Nucleobase Pair.</td>
            <td name="td4">Angew. Chem. Int. Ed Engl</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25941396/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>MoCo</b></a></td>
            <td name="td2">Hover, B. M., Tonthat, N. K., Schumacher, M. A. & Yokoyama, K.<br></td>
            <td name="td3">Mechanism of pyranopterin ring formation in molybdenum cofactor biosynthesis.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25941396/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>Wco</b></a></td>
            <td name="td2">Hover, B. M., Tonthat, N. K., Schumacher, M. A. & Yokoyama, K.<br></td>
            <td name="td3">Mechanism of pyranopterin ring formation in molybdenum cofactor biosynthesis.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25243980/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Yadav, S., Swati, D. & Chandrasekharan, H.<br></td>
            <td name="td3">Thiamine pyrophosphate riboswitch in some representative plant species: a bioinformatics study.</td>
            <td name="td4">J. Comput. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25794618/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Manganese" target="_blank"><b>Manganese</b></a></td>
            <td name="td2">Dambach, M. et al.<br></td>
            <td name="td3">The ubiquitous yybP-ykoY riboswitch is a manganese-responsive regulatory element.</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25794619/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Manganese" target="_blank"><b>Manganese</b></a></td>
            <td name="td2">Price, I. R., Gaballa, A., Ding, F., Helmann, J. D. & Ke, A.<br></td>
            <td name="td3">Mn(2+)-sensing mechanisms of yybP-ykoY orphan riboswitches.</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25451761/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Xue, X., Yongjun, W., & Zhihong, L.<br></td>
            <td name="td3">Folding of SAM-II riboswitch explored by replica-exchange molecular dynamics simulation.</td>
            <td name="td4">J. Theor. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26106162/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Liberman, J. A.<br></td>
            <td name="td3">Structural analysis of a class III preQ1 riboswitch reveals an aptamer distant from a ribosome-binding site regulated by fast dynamics.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25487435/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Fluoride" target="_blank"><b>Fluoride</b></a></td>
            <td name="td2">Chawla, M., Credendino, R., Poater, A., Oliva, R. & Cavallo, L.<br></td>
            <td name="td3">Structural stability, acidity, and halide selectivity of the fluoride riboswitch recognition site.</td>
            <td name="td4">J. Am. Chem. Soc</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/25512308/" target="_blank"><b>2015</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-GMP" target="_blank"><b>c-di-GMP</b></a></td>
            <td name="td2">Bordeleau, E. et al.<br></td>
            <td name="td3">Cyclic di-GMP riboswitch-regulated type IV pili contribute to aggregation of Clostridium difficile</td>
            <td name="td4">J. Bacteriol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27485612/" target="_blank"><b>2016</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Howe, J. A., L. Xiao, T. O. Fischmann, H. Wang, H. Tang, A. Villafania, R. Zhang, C. M. Barbieri and T. Roemer.<br></td>
            <td name="td3">Atomic resolution mechanistic studies of ribocil: A highly selective unnatural ligand mimic of the E. coli FMN riboswitch.</td>
            <td name="td4">RNA Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26843526/" target="_blank"><b>2016</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Azaaromatic" target="_blank"><b>Azaaromatic</b></a></td>
            <td name="td2">Li, S., Hwang, X. Y., Stav, S. & Breaker, R. R.<br></td>
            <td name="td3">The yjdF riboswitch candidate regulates gene expression by binding diverse azaaromatic compounds.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27220466/" target="_blank"><b>2016</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Ketterer, S., Gladis, L., Kozica, A. & Meier, M.<br></td>
            <td name="td3">Engineering and characterization of fluorogenic glycine riboswitches</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27659053/" target="_blank"><b>2016</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Ruff, K. M., Muhammad, A., McCown, P. J., Breaker, R. R. & Strobel, S. A.<br></td>
            <td name="td3">Singlet glycine riboswitches bind ligand as well as tandem riboswitches</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/26800479/" target="_blank"><b>2016</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Chen, B., LeBlanc, R., & Dayie, T. K.<br></td>
            <td name="td3">SAM-II riboswitch samples at least two conformations in solution in the absence of ligand: implications for recognition.</td>
            <td name="td4">Angew. Chem. Int. Ed Engl</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27249101/" target="_blank"><b>2016</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Suresh, G., Srinivasan, H., Nanda, S., & Priyakumar, U. D.<br></td>
            <td name="td3">Ligand-induced stabilization of a duplex-like architecture is crucial for the switching mechanism of the SAM-III riboswitch.</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27934232/" target="_blank"><b>2016</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Gong, S., Wang, Y., Wang, Z., Wang, Y., & Zhang, W.<br></td>
            <td name="td3">Reversible-switch mechanism of the SAM-III riboswitch.</td>
            <td name="td4">J. Phys. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28873470/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Mukherjee, S., Barash, D. & Sengupta, S.<br></td>
            <td name="td3">Comparative genomics and phylogenomic analyses of lysine riboswitch distributions in bacteria</td>
            <td name="td4">PLoS One</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28265071/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Weinberg, Z., Nelson, J. W., Lünse, C. E., Sherlock, M. E. & Breaker, R. R.<br></td>
            <td name="td3">Bioinformatic analysis of riboswitch structures uncovers variant classes with altered ligand specificity.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28265071/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/2-dG" target="_blank"><b>2'-dG</b></a></td>
            <td name="td2">Weinberg, Z., Nelson, J. W., Lünse, C. E., Sherlock, M. E. & Breaker, R. R.<br></td>
            <td name="td3">Bioinformatic analysis of riboswitch structures uncovers variant classes with altered ligand specificity.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27841871/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">Stagno, J. R. et al.<br></td>
            <td name="td3">Structures of riboswitch RNA reaction states by mix-and-inject XFEL serial crystallography.</td>
            <td name="td4">Nature</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28977401/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/THF" target="_blank"><b>THF</b></a></td>
            <td name="td2">Weinberg, Z., Lünse, C. E., Corbino, K. A., Ames, T. D., Nelson, J. W., Roth, A., Perkins, K. R., Sherlock, M. E., & Breaker, R. R.<br></td>
            <td name="td3">Detection of 224 candidate structured RNAs by comparative analysis of specific subsets of intergenic regions.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28977401/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NAD" target="_blank"><b>NAD+-I</b></a></td>
            <td name="td2">Weinberg, Z., Lünse, C. E., Corbino, K. A., Ames, T. D., Nelson, J. W., Roth, A., Perkins, K. R., Sherlock, M. E., & Breaker, R. R.<br></td>
            <td name="td3">Detection of 224 candidate structured RNAs by comparative analysis of specific subsets of intergenic regions.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28977401/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-SAH" target="_blank"><b>SAM-SAH</b></a></td>
            <td name="td2">Weinberg, Z., Lünse, C. E., Corbino, K. A., Ames, T. D., Nelson, J. W., Roth, A., Perkins, K. R., Sherlock, M. E., & Breaker, R. R.<br></td>
            <td name="td3">Detection of 224 candidate structured RNAs by comparative analysis of specific subsets of intergenic regions.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28977401/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PRA" target="_blank"><b>PRA</b></a></td>
            <td name="td2">Weinberg, Z., Lünse, C. E., Corbino, K. A., Ames, T. D., Nelson, J. W., Roth, A., Perkins, K. R., Sherlock, M. E., & Breaker, R. R.<br></td>
            <td name="td3">Detection of 224 candidate structured RNAs by comparative analysis of specific subsets of intergenic regions.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28977401/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Xanthine" target="_blank"><b>Xanthine</b></a></td>
            <td name="td2">Weinberg, Z., Lünse, C. E., Corbino, K. A., Ames, T. D., Nelson, J. W., Roth, A., Perkins, K. R., Sherlock, M. E., & Breaker, R. R.<br></td>
            <td name="td3">Detection of 224 candidate structured RNAs by comparative analysis of specific subsets of intergenic regions.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28977401/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Li" target="_blank"><b>Li+</b></a></td>
            <td name="td2">Weinberg, Z., Lünse, C. E., Corbino, K. A., Ames, T. D., Nelson, J. W., Roth, A., Perkins, K. R., Sherlock, M. E., & Breaker, R. R.<br></td>
            <td name="td3">Detection of 224 candidate structured RNAs by comparative analysis of specific subsets of intergenic regions.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28977401/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Na" target="_blank"><b>Na+</b></a></td>
            <td name="td2">Weinberg, Z., Lünse, C. E., Corbino, K. A., Ames, T. D., Nelson, J. W., Roth, A., Perkins, K. R., Sherlock, M. E., & Breaker, R. R.<br></td>
            <td name="td3">Detection of 224 candidate structured RNAs by comparative analysis of specific subsets of intergenic regions.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27989440/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Nelson, J. W., Atilho, R. M., Sherlock, M. E., Stockbridge, R. B. & Breaker, R. R.<br></td>
            <td name="td3">Metabolism of Free Guanidine in Bacteria Is Regulated by a Widespread Riboswitch Class.</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27989440/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ADP" target="_blank"><b>ADP</b></a></td>
            <td name="td2">Nelson, J. W., Atilho, R. M., Sherlock, M. E., Stockbridge, R. B. & Breaker, R. R.<br></td>
            <td name="td3">Metabolism of Free Guanidine in Bacteria Is Regulated by a Widespread Riboswitch Class.</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27989440/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PRPP" target="_blank"><b>PRPP</b></a></td>
            <td name="td2">Nelson, J. W., Atilho, R. M., Sherlock, M. E., Stockbridge, R. B. & Breaker, R. R.<br></td>
            <td name="td3">Metabolism of Free Guanidine in Bacteria Is Regulated by a Widespread Riboswitch Class.</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/27989440/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ppGpp" target="_blank"><b>ppGpp</b></a></td>
            <td name="td2">Nelson, J. W., Atilho, R. M., Sherlock, M. E., Stockbridge, R. B. & Breaker, R. R.<br></td>
            <td name="td3">Metabolism of Free Guanidine in Bacteria Is Regulated by a Widespread Riboswitch Class.</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28001368/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Sherlock, M. E., Malkowski, S. N. & Breaker, R. R.<br></td>
            <td name="td3">Biochemical Validation of a Second Guanidine Riboswitch Class in Bacteria.</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28001372/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Sherlock, M. E. & Breaker, R. R.<br></td>
            <td name="td3">Biochemical Validation of a Third Guanidine Riboswitch Class in Bacteria.</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28017522/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Reiss, C. W., Xiong, Y. & Strobel, S. A.<br></td>
            <td name="td3">Structural Basis for Ligand Binding to the Guanidine-I Riboswitch.</td>
            <td name="td4">Structure</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28096518/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Battaglia, R. A., Price, I. R. & Ke, A.<br></td>
            <td name="td3">ykkCStructural basis for guanidine sensing by the family of riboswitches.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28529131/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Huang, L., Wang, J. & Lilley, D. M. J.<br></td>
            <td name="td3">The Structure of the Guanidine-II Riboswitch.</td>
            <td name="td4">Cell Chem Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28600356/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Reiss, C. W. & Strobel, S. A.<br></td>
            <td name="td3">Structural basis for ligand binding to the guanidine-II riboswitch.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28988949/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Huang, L., Wang, J., Wilson, T. J. & Lilley, D. M. J.<br></td>
            <td name="td3">Structure of the Guanidine III Riboswitch.</td>
            <td name="td4">Cell Chem Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28192411" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Bingaman, J. L. et al.<br></td>
            <td name="td3">The GlcN6P cofactor plays multiple catalytic roles in the glmS ribozyme.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29089431/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Babina, A. M., Lea, N. E. & Meyer, M. M.<br></td>
            <td name="td3">In Vivo Behavior of the Tandem Glycine Riboswitch in Bacillus subtilis</td>
            <td name="td4">MBio</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28701520/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Dussault, A.-M., Dubé, A., Jacques, F., Grondin, J. P., and Lafontaine, D. A.<br></td>
            <td name="td3">Ligand recognition and helical stacking formation are intimately linked in the SAM-I riboswitch regulatory mechanism.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28920931/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Manz, C., Kobitski, A. Y., Samanta, A., Keller, B. G., Jäschke, A., & Nienhaus, G. U.<br></td>
            <td name="td3">Single-molecule FRET reveals the energy landscape of the full-length SAM-I riboswitch.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28377919/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Choudhary, P. K., Gallo, S. & Sigel, R. K.<br></td>
            <td name="td3">Tb(3+)-Cleavage Assays Reveal Specific Mg(2+) Binding Sites Necessary to Pre-fold the btuB Riboswitch for AdoCbl Binding.</td>
            <td name="td4">Frontiers in chemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28483920/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Polaski, J. T., Webster, S. M., Johnson, J. E. & Batey, R. T.<br></td>
            <td name="td3">Cobalamin riboswitches exhibit a broad range of ability to discriminate between methylcobalamin and adenosylcobalamin.</td>
            <td name="td4">J. Biol. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28248966/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Roy, S., Lammert, H., Hayes, R. L., Chen, B., LeBlanc, R., Dayie, T. K., Onuchic, J. N., & Sanbonmatsu, K. Y.<br></td>
            <td name="td3">A magnesium-induced triplex pre-organizes the SAM-II riboswitch.</td>
            <td name="td4">PLoS Comput. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/28719589/" target="_blank"><b>2017</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Fluoride" target="_blank"><b>Fluoride</b></a></td>
            <td name="td2">Zhao, B., Guffy, S. L., Williams, B. & Zhang, Q.<br></td>
            <td name="td3">An excited state underlies gene regulation of a transcriptional riboswitch.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30085248/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glutamine" target="_blank"><b>Glutamine</b></a></td>
            <td name="td2">Klähn, S. et al.<br></td>
            <td name="td3">A glutamine riboswitch is a key element for the regulation of glutamine synthetase in cyanobacteria</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29412640/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Rizvi, N. F. et al.<br></td>
            <td name="td3">Discovery of Selective RNA-Binding Small Molecules by Affinity-Selection Mass Spectrometry.</td>
            <td name="td4">ACS Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30107111/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Vicens, Q. et al.<br></td>
            <td name="td3">Structure-Activity Relationship of Flavin Analogues That Target the Flavin Mononucleotide Riboswitch.</td>
            <td name="td4">ACS Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30006500/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-AMP-GMP" target="_blank"><b>c-AMP-GMP</b></a></td>
            <td name="td2">Keller, H., Weickhmann, A. K., Bock, T. & Wöhnert, J.<br></td>
            <td name="td3">Adenine protonation enables cyclic-di-GMP binding to cyclic-GAMP sensing riboswitches.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30423927/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-AMP-GMP" target="_blank"><b>c-AMP-GMP</b></a></td>
            <td name="td2">Li, C., Zhao, X., Zhu, X., Xie, P. & Chen, G.<br></td>
            <td name="td3">Structural Studies of the 3',3'-cGAMP Riboswitch Induced by Cognate and Noncognate Ligands Using Molecular Dynamics Simulation.</td>
            <td name="td4">Int. J. Mol. Sci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30051308/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-SAH" target="_blank"><b>SAM-SAH</b></a></td>
            <td name="td2">Weickhmann, A. K., Keller, H., Duchardt-Ferner, E., Strebitzer, E., Juen, M. A., Kremser, J., Wurm, J. P., Kreutz, C., & Wöhnert, J.<br></td>
            <td name="td3">NMR resonance assignments for the SAM/SAH-binding riboswitch RNA bound to S-adenosylhomocysteine.</td>
            <td name="td4">Biomol. NMR Assign</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29106323/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-VI" target="_blank"><b>SAM-VI</b></a></td>
            <td name="td2">Mirihana Arachchilage, G., Sherlock, M. E., Weinberg, Z., & Breaker, R. R.<br></td>
            <td name="td3">SAM-VI RNAs selectively bind S-adenosylmethionine and exhibit similarities to SAM-III riboswitches.</td>
            <td name="td4">RNA Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29504937/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ppGpp" target="_blank"><b>ppGpp</b></a></td>
            <td name="td2">Sherlock, M. E., Sudarsan, N., Stav, S. & Breaker, R. R.<br></td>
            <td name="td3">Tandem riboswitches form a natural Boolean logic gate to control purine metabolism in bacteria.</td>
            <td name="td4">Elife</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29504937/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PRPP" target="_blank"><b>PRPP</b></a></td>
            <td name="td2">Sherlock, M. E., Sudarsan, N., Stav, S. & Breaker, R. R.<br></td>
            <td name="td3">Tandem riboswitches form a natural Boolean logic gate to control purine metabolism in bacteria.</td>
            <td name="td4">Elife</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29504937/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ADP" target="_blank"><b>ADP</b></a></td>
            <td name="td2">Sherlock, M. E., Sudarsan, N., Stav, S. & Breaker, R. R.<br></td>
            <td name="td3">Tandem riboswitches form a natural Boolean logic gate to control purine metabolism in bacteria.</td>
            <td name="td4">Elife</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29784782/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ppGpp" target="_blank"><b>ppGpp</b></a></td>
            <td name="td2">Sherlock, M. E., Sudarsan, N. & Breaker, R. R.<br></td>
            <td name="td3">Riboswitches for the alarmone ppGpp expand the collection of RNA-based signaling systems.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30120360/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PRPP" target="_blank"><b>PRPP</b></a></td>
            <td name="td2">Peselis, A. & Serganov, A.<br></td>
            <td name="td3">ykkC riboswitches employ an add-on helix to adjust specificity for polyanionic ligands.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30120360/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ppGpp" target="_blank"><b>ppGpp</b></a></td>
            <td name="td2">Peselis, A. & Serganov, A.<br></td>
            <td name="td3">ykkC riboswitches employ an add-on helix to adjust specificity for polyanionic ligands.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29877798/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PRPP" target="_blank"><b>PRPP</b></a></td>
            <td name="td2">Knappenberger, A. J., Reiss, C. W. & Strobel, S. A.<br></td>
            <td name="td3">Structures of two aptamers with differing ligand specificity reveal ruggedness in the functional landscape of RNA.</td>
            <td name="td4">Elife</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29223402/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Azaaromatic" target="_blank"><b>Azaaromatic</b></a></td>
            <td name="td2">Gong, S., Wang, Y., Wang, Z., Wang, Y. & Zhang, W.<br></td>
            <td name="td3">Genetic regulation mechanism of the yjdF riboswitch.</td>
            <td name="td4">J. Theor. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29615754/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Mukherjee, S., Retwitzer, Barash, D. & Sengupta, S.<br></td>
            <td name="td3">Phylogenomic and comparative analysis of the distribution and regulatory patterns of TPP riboswitches in fungi.</td>
            <td name="td4">Sci. Rep</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29805037/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Manganese" target="_blank"><b>Manganese</b></a></td>
            <td name="td2">Bachas, S. T. & Ferré-D’Amaré, A. R.<br></td>
            <td name="td3">Convergent Use of Heptacoordination for Cation Selectivity by RNA and Protein Metalloregulators.</td>
            <td name="td4">Cell Chem Biol 25, 962–973</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29527194/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Khani, A., Popp, N., Kreikemeyer, B. & Patenge, N.<br></td>
            <td name="td3">A Glycine Riboswitch in Controls Expression of a Sodium:Alanine Symporter Family Protein Gene</td>
            <td name="td4">Front. Microbiol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29604896/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Manz, C., Kobitski, A. Y., Samanta, A., Jäschke, A., & Nienhaus, G. U.<br></td>
            <td name="td3">The multi-state energy landscape of the SAM-I riboswitch: A single-molecule Förster resonance energy transfer spectroscopy study.</td>
            <td name="td4">J. Chem. Phys</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29931337/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Huang, L., & Lilley, D. M. J.<br></td>
            <td name="td3">Structure and ligand binding of the SAM-V riboswitch.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30388413/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Widom, J. R. et al.<br></td>
            <td name="td3">Ligand Modulates Cross-Coupling between Riboswitch Folding and Transcriptional Pausing.</td>
            <td name="td4">Mol. Cell</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/29693296/" target="_blank"><b>2018</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-GMP" target="_blank"><b>c-di-GMP</b></a></td>
            <td name="td2">Inuzuka, S. et al.<br></td>
            <td name="td3">Recognition of cyclic-di-GMP by a riboswitch conducts translational repression through masking the ribosome-binding site distant from the aptamer domain</td>
            <td name="td4">Genes Cells</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31216023/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glutamine" target="_blank"><b>Glutamine</b></a></td>
            <td name="td2">Huang, L., Wang, J., Watkins, A. M., Das, R. & Lilley, D. M. J.<br></td>
            <td name="td3">Structure and ligand binding of the glutamine-II riboswitch</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31740853/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/T-box" target="_blank"><b>T-box</b></a></td>
            <td name="td2">Battaglia, R. A., Grigg, J. C. & Ke, A.<br></td>
            <td name="td3">Structural basis for tRNA decoding and aminoacylation sensing by T-box riboregulators.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31740854/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/T-box" target="_blank"><b>T-box</b></a></td>
            <td name="td2">Li, S. et al.<br></td>
            <td name="td3">Structural basis of amino acid surveillance by higher-order tRNA-mRNA interactions.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31792446/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/T-box" target="_blank"><b>T-box</b></a></td>
            <td name="td2">Weaver, J. W. & Serganov, A.<br></td>
            <td name="td3">T-box RNA gets boxed.</td>
            <td name="td4">Nat. Struct. Mol. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31598729/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/2-dG" target="_blank"><b>2'-dG</b></a></td>
            <td name="td2">Matyjasik, M. M. & Batey, R. T.<br></td>
            <td name="td3">Structural basis for 2′-deoxyguanosine recognition by the 2′-dG-II class of riboswitches.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30590743/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-SAH" target="_blank"><b>SAM-SAH</b></a></td>
            <td name="td2">Weickhmann, A. K., Keller, H., Wurm, J. P., Strebitzer, E., Juen, M. A., Kremser, J., Weinberg, Z., Kreutz, C., Duchardt-Ferner, E., & Wöhnert, J.<br></td>
            <td name="td3">The structure of the SAM/SAH-binding riboswitch.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31282869/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Jones, C. et al.<br></td>
            <td name="td3">Co-crystal structure of the Fusobacterium ulcerans ZTP riboswitch using an X-ray free-electron laser</td>
            <td name="td4">Acta Crystallogr. Sect. F Struct. Biol. Cryst. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31636437/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Strobel, E. J., Cheng, L., Berman, K. E., Carlson, P. D. & Lucks, J. B.<br></td>
            <td name="td3">A ligand-gated strand displacement mechanism for ZTP riboswitch transcription control</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31609568/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Perkins, K. R., Atilho, R. M., Moon, M. H. & Breaker, R. R.<br></td>
            <td name="td3">Employing a ZTP Riboswitch to Detect Bacterial Folate Biosynthesis Inhibitors in a Small Molecule High-Throughput Screen</td>
            <td name="td4">ACS Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30609994/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Huang, L., Wang, J., Wilson, T. J. & Lilley, D. M. J.<br></td>
            <td name="td3">Structure-guided design of a high-affinity ligand for a riboswitch.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31844059/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-VI" target="_blank"><b>SAM-VI</b></a></td>
            <td name="td2">Sun, A., Gasser, C., Li, F., Chen, H., Mair, S., Krasheninina, O., Micura, R., & Ren, A.<br></td>
            <td name="td3">SAM-VI riboswitch structure and signature for ligand discrimination.</td>
            <td name="td4">Nat. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30902049/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Stav, S. et al.<br></td>
            <td name="td3">Genome-wide discovery of structured noncoding RNAs in bacteria.</td>
            <td name="td4">BMC Microbiol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30902049/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/HMP-PP" target="_blank"><b>HMP-PP</b></a></td>
            <td name="td2">Stav, S. et al.<br></td>
            <td name="td3">Genome-wide discovery of structured noncoding RNAs in bacteria.</td>
            <td name="td4">BMC Microbiol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31165873/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Manganese" target="_blank"><b>Manganese</b></a></td>
            <td name="td2">Martin, J. E. et al.<br></td>
            <td name="td3">A Mn-sensing riboswitch activates expression of a Mn2+/Ca2+ ATPase transporter in Streptococcus.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31541094/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Manganese" target="_blank"><b>Manganese</b></a></td>
            <td name="td2">Suddala, K. C. et al.<br></td>
            <td name="td3">Local-to-global signal transduction at the core of a Mn sensing riboswitch.</td>
            <td name="td4">Nat. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31550137/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Zhou, L. et al.<br></td>
            <td name="td3">Characterization and Engineering of a Clostridium Glycine Riboswitch and Its Use To Control a Novel Metabolic Pathway for 5-Aminolevulinic Acid Production in Escherichia coli</td>
            <td name="td4">ACS Synth. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30081631/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ADP" target="_blank"><b>ADP</b></a></td>
            <td name="td2">Sherlock, M. E., Sadeeshkumar, H. & Breaker, R. R.<br></td>
            <td name="td3">Variant Bacterial Riboswitches Associated with Nucleotide Hydrolase Genes Sense Nucleoside Diphosphates.</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31796736/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Zhang, K., Li, S., Kappel, K., Pintilie, G., Su, Z., Mou, T. C., Schmid, M. F., Das, R., & Chiu, W.<br></td>
            <td name="td3">Cryo-EM structure of a 40 kDa SAM-IV riboswitch RNA at 3.7 Å resolution.</td>
            <td name="td4">Nat. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31186369/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/THF" target="_blank"><b>THF</b></a></td>
            <td name="td2">Chen, X., Mirihana, A. G. & Breaker, R. R.<br></td>
            <td name="td3">Biochemical validation of a second class of tetrahydrofolate riboswitches in bacteria.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31044176/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-AMP" target="_blank"><b>c-di-AMP</b></a></td>
            <td name="td2">Wang, X. et al.<br></td>
            <td name="td3">A c-di-AMP riboswitch controlling kdpFABC operon transcription regulates the potassium transporter system in Bacillus thuringiensis.</td>
            <td name="td4">Commun Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31467147/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NAD" target="_blank"><b>NAD+-I</b></a></td>
            <td name="td2">Malkowski, S. N., Spencer, T. C. J. & Breaker, R. R.<br></td>
            <td name="td3">Evidence that the nadA motif is a bacterial riboswitch for the ubiquitous enzyme  cofactor NAD</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30940810/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Connelly, C. M. et al.<br></td>
            <td name="td3">Synthetic ligands for PreQ1 riboswitches provide structural and mechanistic insights into targeting RNA tertiary structure.</td>
            <td name="td4">Nat. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/30950790/" target="_blank"><b>2019</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/HMP-PP" target="_blank"><b>HMP-PP</b></a></td>
            <td name="td2">Atilho, R. M., Mirihana, A. G., Greenlee, E. B., Knecht, K. M. & Breaker, R. R.<br></td>
            <td name="td3">A bacterial riboswitch class for the thiamin precursor HMP-PP employs a terminator-embedded aptamer.</td>
            <td name="td4">Elife</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32706360/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Sung, H.-L. & Nesbitt, D. J.<br></td>
            <td name="td3">High pressure single-molecule FRET studies of the lysine riboswitch: cationic and osmolytic effects on pressure induced denaturation</td>
            <td name="td4">Phys. Chem. Chem. Phys</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33103111/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Wilt, H. M., Yu, P., Tan, K., Wang, Y. X. & Stagno, J. R.<br></td>
            <td name="td3">FMN riboswitch aptamer symmetry facilitates conformational switching through mutually exclusive coaxial stacking configurations.</td>
            <td name="td4">Journal of structural biology</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32250107/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NiCo" target="_blank"><b>NiCo</b></a></td>
            <td name="td2">Xu, J. & Cotruvo, J. A., Jr.<br></td>
            <td name="td3">The (NiCo) Riboswitch Responds to Iron(II).</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32520325/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-SAH" target="_blank"><b>SAM-SAH</b></a></td>
            <td name="td2">Huang, L., Liao, T. W., Wang, J., Ha, T., & Lilley, D. M. J.<br></td>
            <td name="td3">Crystal structure and ligand-induced folding of the SAM/SAH riboswitch.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32795418/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Tran, B. et al.<br></td>
            <td name="td3">Parallel Discovery Strategies Provide a Basis for Riboswitch Ligand Design</td>
            <td name="td4">Cell Chem Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32913225/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Hua, B. et al.<br></td>
            <td name="td3">Real-time monitoring of single ZTP riboswitches reveals a complex and kinetically controlled decision landscape</td>
            <td name="td4">Nat. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32857846/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Wuebben, C., Vicino, M. F., Mueller, M. & Schiemann, O.<br></td>
            <td name="td3">Do the P1 and P2 hairpins of the Guanidine-II riboswitch interact?</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33236895/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Salvail, H., Balaji, A., Yu, D., Roth, A. & Breaker, R. R.<br></td>
            <td name="td3">Biochemical Validation of a Fourth Guanidine Riboswitch Class in Bacteria.</td>
            <td name="td4">Biochemistry</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33237283/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Lenkeit, F., Eckert, I., Hartig, J. S. & Weinberg, Z.<br></td>
            <td name="td3">Discovery and characterization of a fourth class of guanidine riboswitches.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32843366/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PRA" target="_blank"><b>PRA</b></a></td>
            <td name="td2">Malkowski, S. N., Atilho, R. M., Greenlee, E. B., Weinberg, C. E. & Breaker, R. R.<br></td>
            <td name="td3">A rare bacterial RNA motif is implicated in the regulation of the purF gene whose encoded enzyme synthesizes phosphoribosylamine.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32345632/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Xanthine" target="_blank"><b>Xanthine</b></a></td>
            <td name="td2">Yu, D. & Breaker, R. R.<br></td>
            <td name="td3">A bacterial riboswitch class senses xanthine and uric acid to regulate genes associated with purine oxidation.</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32726320/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Subki, A., Ho, C. L., Ismail, N. F. N., Aa, Z. A. & Zn, B. Y.<br></td>
            <td name="td3">Identification and characterisation of thiamine pyrophosphate (TPP) riboswitch in Elaeis guineensis.</td>
            <td name="td4">PLoS One</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32616928/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Kappel, K. et al.<br></td>
            <td name="td3">Accelerated cryo-EM-guided determination of three-dimensional RNA-only structures</td>
            <td name="td4">Nat</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/31992591/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Torgerson, C. D., Hiller, D. A. & Strobel, S. A.<br></td>
            <td name="td3">The asymmetry and cooperativity of tandem glycine riboswitch aptamers</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32493973/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Tang, D. J., Du, X., Shi, Q., Zhang, J. L., He, Y. P., Chen, Y. M., Ming, Z., Wang, D., Zhong, W. Y., Liang, Y. W., Liu, J. Y., Huang, J. M., Zhong, Y. S., An, S. Q., Gu, H., & Tang, J. L.<br></td>
            <td name="td3">A SAM-I riboswitch with the ability to sense and respond to uncharged initiator tRNA.</td>
            <td name="td4">Nat. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32295864/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NAD" target="_blank"><b>NAD+-I</b></a></td>
            <td name="td2">Huang, L., Wang, J. & Lilley, D. M. J.<br></td>
            <td name="td3">Structure and ligand binding of the ADP-binding domain of the NAD+ riboswitch</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33170270/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NAD" target="_blank"><b>NAD+-I</b></a></td>
            <td name="td2">Chen, H. et al.<br></td>
            <td name="td3">Structural distinctions between NAD+ riboswitch domains 1 and 2 determine  differential folding and ligand binding</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32544228/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Chan, C. W. & Mondragón, A.<br></td>
            <td name="td3">Crystal structure of an atypical cobalamin riboswitch reveals RNA structural adaptability as basis for promiscuous ligand binding.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/32597951/" target="_blank"><b>2020</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Schroeder, G. M. et al.<br></td>
            <td name="td3">Analysis of a preQ1-I riboswitch in effector-free and bound states reveals a metabolite-programmed nucleobase-stacking spine that controls gene regulation.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/34242760/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Harale, B. et al.<br></td>
            <td name="td3">Synthesis and evaluation of antimycobacterial activity of riboflavin derivatives.</td>
            <td name="td4">Bioorg. Med. Chem. Lett</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33963862/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">St-Pierre, P. et al.<br></td>
            <td name="td3">A structural intermediate pre-organizes the add adenine riboswitch for ligand recognition.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33590553/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Sinn, M., Hauth, F., Lenkeit, F., Weinberg, Z. & Hartig, J. S.<br></td>
            <td name="td3">Widespread bacterial utilization of guanidine as nitrogen source.</td>
            <td name="td4">Mol. Microbiol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/34487413/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ppGpp" target="_blank"><b>ppGpp</b></a></td>
            <td name="td2">Sun, Z. et al.<br></td>
            <td name="td3">Live-Cell Imaging of Guanosine Tetra- and Pentaphosphate (p)ppGpp with RNA-based Fluorescent Sensors*.</td>
            <td name="td4">Angew. Chem. Int. Ed Engl</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/34125892/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Xanthine" target="_blank"><b>Xanthine</b></a></td>
            <td name="td2">Xu, X. et al.<br></td>
            <td name="td3">Insights into xanthine riboswitch structure and metal ion-mediated ligand recognition.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/34734706" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/GlcN6P" target="_blank"><b>GlcN6P</b></a></td>
            <td name="td2">Traykovska, M., Popova, K. B. & Penchovsky, R.<br></td>
            <td name="td3">Targeting glmS Ribozyme with Chimeric Antisense Oligonucleotides for Antibacterial Drug Development.</td>
            <td name="td4">ACS Synth. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33571639/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/THF" target="_blank"><b>THF</b></a></td>
            <td name="td2">Wilt, H. M., Yu, P., Tan, K., Wang, Y. X. & Stagno, J. R.<br></td>
            <td name="td3">Tying the knot in the tetrahydrofolate (THF) riboswitch: A molecular basis for gene regulation.</td>
            <td name="td4">J. Struct. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33970790/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NAD2" target="_blank"><b>NAD+-II</b></a></td>
            <td name="td2">Brewer, K. I. et al.<br></td>
            <td name="td3">Comprehensive discovery of novel structured noncoding RNAs in 26 bacterial genomes</td>
            <td name="td4">RNA Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33087526/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NAD2" target="_blank"><b>NAD+-II</b></a></td>
            <td name="td2">Panchapakesan, S. S. S., Corey, L., Malkowski, S. N., Higgs, G. & Breaker, R. R.<br></td>
            <td name="td3">A second riboswitch class for the enzyme cofactor NAD</td>
            <td name="td4">RNA</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/33683130/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Ma, B., Bai, G., Nussinov, R., Ding, J. & Wang, Y.-X.<br></td>
            <td name="td3">Conformational Ensemble of AdoCbl Riboswitch Provides Stable Structural Elements for Conformation Selection and Population Shift in Cobalamin Recognition.</td>
            <td name="td4">J. Phys. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/34162884/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Flemmich, L., Heel, S., Moreno, S., Breuker, K. & Micura, R.<br></td>
            <td name="td3">A natural riboswitch scaffold with self-methylation activity.</td>
            <td name="td4">Nat. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/34782462/" target="_blank"><b>2021</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Fluoride" target="_blank"><b>Fluoride</b></a></td>
            <td name="td2">Chauvier, A., Ajmera, P., Yadav, R. & Walter, N. G.<br></td>
            <td name="td3">Dynamic competition between a ligand and transcription factor NusA governs riboswitch-mediated transcription regulation.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35440139/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/FMN" target="_blank"><b>FMN</b></a></td>
            <td name="td2">Traykovska, M. & Penchovsky, R.<br></td>
            <td name="td3">Engineering Antisense Oligonucleotides as Antibacterial Agents That Target FMN Riboswitches and Inhibit the Growth of Staphylococcus aureus, Listeria monocytogenes, and Escherichia coli.</td>
            <td name="td4">ACS Synth. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35427920/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NiCo" target="_blank"><b>NiCo</b></a></td>
            <td name="td2">Xu, J. & Cotruvo, J. A., Jr.<br></td>
            <td name="td3">Iron-responsive riboswitches.</td>
            <td name="td4">Curr. Opin. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35996475/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NiCo" target="_blank"><b>NiCo</b></a></td>
            <td name="td2">Xu, J. & Cotruvo, J. A., Jr.<br></td>
            <td name="td3">Reconsidering the (NiCo) Riboswitch as an Iron Riboswitch.</td>
            <td name="td4">ACS Bio Med Chem Au</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35163114/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-AMP-GMP" target="_blank"><b>c-AMP-GMP</b></a></td>
            <td name="td2">Tan, Z. et al.<br></td>
            <td name="td3">The Signaling Pathway That cGAMP Riboswitches Found: Analysis and Application of Riboswitches to Study cGAMP Signaling in Geobacter sulfurreducens.</td>
            <td name="td4">Int. J. Mol. Sci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/34937909/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Adenine" target="_blank"><b>Adenine</b></a></td>
            <td name="td2">Dey, S. K. et al.<br></td>
            <td name="td3">Repurposing an adenine riboswitch into a fluorogenic imaging and sensing tag.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35622895/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/2-dG" target="_blank"><b>2'-dG</b></a></td>
            <td name="td2">Hamal, D. S., Panchapakesan, S. S. S., Slattery, P., Roth, A. & Breaker, R. R.<br></td>
            <td name="td3">Variants of the guanine riboswitch class exhibit altered ligand specificities for xanthine, guanine, or 2′-deoxyguanosine.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35622895/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanine" target="_blank"><b>Guanine</b></a></td>
            <td name="td2">Hamal, D. S., Panchapakesan, S. S. S., Slattery, P., Roth, A. & Breaker, R. R.<br></td>
            <td name="td3">Variants of the guanine riboswitch class exhibit altered ligand specificities for xanthine, guanine, or 2′-deoxyguanosine.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35622895/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Xanthine" target="_blank"><b>Xanthine</b></a></td>
            <td name="td2">Hamal, D. S., Panchapakesan, S. S. S., Slattery, P., Roth, A. & Breaker, R. R.<br></td>
            <td name="td3">Variants of the guanine riboswitch class exhibit altered ligand specificities for xanthine, guanine, or 2′-deoxyguanosine.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35573739/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Guanidine" target="_blank"><b>Guanidine</b></a></td>
            <td name="td2">Fuks, C., Falkner, S., Schwierz, N. & Hengesbach, M.<br></td>
            <td name="td3">Combining Coarse-Grained Simulations and Single Molecule Analysis Reveals a Three-State Folding Model of the Guanidine-II Riboswitch.</td>
            <td name="td4">Front Mol Biosci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35427649/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Azaaromatic" target="_blank"><b>Azaaromatic</b></a></td>
            <td name="td2">Trachman, R. J., 3rd, Passalacqua, L. F. M. & Ferré-D’Amaré, A. R.<br></td>
            <td name="td3">The bacterial yjdF riboswitch regulates translation through its tRNA-like fold.</td>
            <td name="td4">J. Biol. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35060698/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Zeller, M. J. et al.<br></td>
            <td name="td3">Subsite Ligand Recognition and Cooperativity in the TPP Riboswitch: Implications for Fragment-Linking in RNA Ligand Discovery.</td>
            <td name="td4">ACS Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35561226/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Zeller, M. J. et al.<br></td>
            <td name="td3">SHAPE-enabled fragment-based ligand discovery for RNA.</td>
            <td name="td4">Proc. Natl. Acad. Sci. U. S. A</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35392910/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Glycine" target="_blank"><b>Glycine</b></a></td>
            <td name="td2">Hong, K.-Q., Zhang, J., Jin, B., Chen, T. & Wang, Z.-W.<br></td>
            <td name="td3">Development and characterization of a glycine biosensor system for fine-tuned metabolic regulation in Escherichia coli</td>
            <td name="td4">Microb. Cell Fact</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36352003/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Li" target="_blank"><b>Li+</b></a></td>
            <td name="td2">White, N., Sadeeshkumar, H., Sun, A., Sudarsan, N. & Breaker, R. R.<br></td>
            <td name="td3">Lithium-sensing riboswitch classes regulate expression of bacterial cation transporter genes.</td>
            <td name="td4">Sci. Rep</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35017488/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/PreQ" target="_blank"><b>PreQ1</b></a></td>
            <td name="td2">Schroeder, G. M. et al.<br></td>
            <td name="td3">A small RNA that cooperatively senses two stacked metabolites in one pocket for gene control.</td>
            <td name="td4">Nat. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35017489/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Fluoride" target="_blank"><b>Fluoride</b></a></td>
            <td name="td2">Yadav, R., Widom, J. R., Chauvier, A. & Walter, N. G.<br></td>
            <td name="td3">An anionic ligand snap-locks a long-range interaction in a magnesium-folded riboswitch.</td>
            <td name="td4">Nat. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36440874/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Chen, J., Zeng, Q., Wang, W., Sun, H., & Hu, G.<br></td>
            <td name="td3">Decoding the identification mechanism of an SAM-III riboswitch on ligands through multiple independent gaussian-accelerated molecular dynamics simulations.</td>
            <td name="td4">J. Chem. Inf. Model</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/35879547/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Na" target="_blank"><b>Na+</b></a></td>
            <td name="td2">White, N., Sadeeshkumar, H., Sun, A., Sudarsan, N. & Breaker, R. R.<br></td>
            <td name="td3">Na riboswitches regulate genes for diverse physiological processes in bacteria.</td>
            <td name="td4">Nat. Chem. Biol</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36139956/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>MoCo</b></a></td>
            <td name="td2">Pavlova, N. & Penchovsky, R.<br></td>
            <td name="td3">Bioinformatics and Genomic Analyses of the Suitability of Eight Riboswitches for Antibacterial Drug Targets.</td>
            <td name="td4">Antibiotics</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36139956/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>Wco</b></a></td>
            <td name="td2">Pavlova, N. & Penchovsky, R.<br></td>
            <td name="td3">Bioinformatics and Genomic Analyses of the Suitability of Eight Riboswitches for Antibacterial Drug Targets.</td>
            <td name="td4">Antibiotics</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36139956/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Magnesium" target="_blank"><b>Magnesium</b></a></td>
            <td name="td2">Pavlova, N. & Penchovsky, R.<br></td>
            <td name="td3">Bioinformatics and Genomic Analyses of the Suitability of Eight Riboswitches for Antibacterial Drug Targets.</td>
            <td name="td4">Antibiotics</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36421306/" target="_blank"><b>2022</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Traykovska, M., & Penchovsky, R.<br></td>
            <td name="td3">Targeting SAM-I riboswitch using antisense oligonucleotide technology for inhibiting the growth of staphylococcus aureus and listeria monocytogenes.</td>
            <td name="td4">Antibiotics</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36459353/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-I_clan" target="_blank"><b>SAM-I_clan</b></a></td>
            <td name="td2">Zheng L, Song Q, Xu X, Shen X, Li C, Li H, Chen H, Ren A.<br></td>
            <td name="td3">Structure-based insights into recognition and regulation of SAM-sensing riboswitches.</td>
            <td name="td4">Sci China Life Sci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36459353/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-II_clan" target="_blank"><b>SAM-II_clan</b></a></td>
            <td name="td2">Zheng L, Song Q, Xu X, Shen X, Li C, Li H, Chen H, Ren A.<br></td>
            <td name="td3">Structure-based insights into recognition and regulation of SAM-sensing riboswitches.</td>
            <td name="td4">Sci China Life Sci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36459353/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-III" target="_blank"><b>SAM-III</b></a></td>
            <td name="td2">Zheng L, Song Q, Xu X, Shen X, Li C, Li H, Chen H, Ren A.<br></td>
            <td name="td3">Structure-based insights into recognition and regulation of SAM-sensing riboswitches.</td>
            <td name="td4">Sci China Life Sci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36459353/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-VI" target="_blank"><b>SAM-VI</b></a></td>
            <td name="td2">Zheng L, Song Q, Xu X, Shen X, Li C, Li H, Chen H, Ren A.<br></td>
            <td name="td3">Structure-based insights into recognition and regulation of SAM-sensing riboswitches.</td>
            <td name="td4">Sci China Life Sci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36459353/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAH" target="_blank"><b>SAH</b></a></td>
            <td name="td2">Zheng L, Song Q, Xu X, Shen X, Li C, Li H, Chen H, Ren A.<br></td>
            <td name="td3">Structure-based insights into recognition and regulation of SAM-sensing riboswitches.</td>
            <td name="td4">Sci China Life Sci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36459353/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-SAH" target="_blank"><b>SAM-SAH</b></a></td>
            <td name="td2">Zheng L, Song Q, Xu X, Shen X, Li C, Li H, Chen H, Ren A.<br></td>
            <td name="td3">Structure-based insights into recognition and regulation of SAM-sensing riboswitches.</td>
            <td name="td4">Sci China Life Sci</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36916791/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Lysine" target="_blank"><b>Lysine</b></a></td>
            <td name="td2">Marton Menendez, A. & Nesbitt, D. J.<br></td>
            <td name="td3">Ionic Cooperativity between Lysine and Potassium in the Lysine Riboswitch: Single-Molecule Kinetic and Thermodynamic Studies</td>
            <td name="td4">J. Phys. Chem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36945415/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-SAH" target="_blank"><b>SAM-SAH</b></a></td>
            <td name="td2">Hu, G., & Zhou, H. X.<br></td>
            <td name="td3">Magnesium ions mediate ligand binding and conformational transition of the SAM/SAH riboswitch.</td>
            <td name="td4">BioRxiv</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36864761/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/ZTP" target="_blank"><b>ZTP</b></a></td>
            <td name="td2">Bushhouse, D. Z. & Lucks, J. B.<br></td>
            <td name="td3">Tuning strand displacement kinetics enables programmable ZTP riboswitch dynamic range in vivo</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/37087479/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/SAM-VI" target="_blank"><b>SAM-VI</b></a></td>
            <td name="td2">Xue, Y., Li, J., Chen, D., Zhao, X., Hong, L., & Liu, Y.<br></td>
            <td name="td3">Observation of structural switch in nascent SAM-VI riboswitch during transcription at single-nucleotide and single-molecule resolution.</td>
            <td name="td4">Nat. Commun</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36774787/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>MoCo</b></a></td>
            <td name="td2">Amadei, F., Reichenbach, M., Gallo, S. & Sigel, R. K. O.<br></td>
            <td name="td3">The structural features of the ligand-free moaA riboswitch and its ion-dependent folding.</td>
            <td name="td4">J. Inorg. Biochem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36774787/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/MoCo&Wco" target="_blank"><b>Wco</b></a></td>
            <td name="td2">Amadei, F., Reichenbach, M., Gallo, S. & Sigel, R. K. O.<br></td>
            <td name="td3">The structural features of the ligand-free moaA riboswitch and its ion-dependent folding.</td>
            <td name="td4">J. Inorg. Biochem</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/37253356/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/TPP" target="_blank"><b>TPP</b></a></td>
            <td name="td2">Lee, H. K. et al.<br></td>
            <td name="td3">Crystal structure of Escherichia coli thiamine pyrophosphate-sensing riboswitch in the apo state.</td>
            <td name="td4">Structure</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36620887/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/THF" target="_blank"><b>THF</b></a></td>
            <td name="td2">Xu, L., Xiao, Y., Zhang, J. & Fang, X.<br></td>
            <td name="td3">Structural insights into translation regulation by the THF-II riboswitch.</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36838266/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/c-di-AMP" target="_blank"><b>c-di-AMP</b></a></td>
            <td name="td2">Reich, S. J. et al.<br></td>
            <td name="td3">C-di-AMP Is a Second Messenger in Corynebacterium glutamicum That Regulates Expression of a Cell Wall-Related Peptidase via a Riboswitch.</td>
            <td name="td4">Microorganisms</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36610789/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NAD2" target="_blank"><b>NAD+-II</b></a></td>
            <td name="td2">Xu, X. et al.<br></td>
            <td name="td3">Structure-based investigations of the NAD+-II riboswitch</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/36840714/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/NAD2" target="_blank"><b>NAD+-II</b></a></td>
            <td name="td2">Peng, X., Liao, W., Lin, X., Lilley, D. M. J. & Huang, L.<br></td>
            <td name="td3">Crystal structures of the NAD+-II riboswitch reveal two distinct ligand-binding pockets</td>
            <td name="td4">Nucleic Acids Res</td>
            
        </tr>

            
        <tr>
            <td name="td0"><a href="https://pubmed.ncbi.nlm.nih.gov/37094176/" target="_blank"><b>2023</b> </a></td>
            <td name="td1"><a href="https://ribocentre-switch.github.io/docs/Cobalamine" target="_blank"><b>Cobalamine</b></a></td>
            <td name="td2">Lennon, S. R. et al.<br></td>
            <td name="td3">Targeting Riboswitches with Beta-Axial-Substituted Cobalamins.</td>
            <td name="td4">ACS Chem. Biol</td>
            
        </tr>

            
	</tbody>
    </table>
</div>       

<script>
var tables = [];
    var currentSheet = 'sheet1';
     $(document).ready(function() {
    $.noConflict();
    tables.push($('#reviewtable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));

    tables.push($('#researchtable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));

    tables.push($('#rnapretable').DataTable({
      dom: 'Bfrtip',
      buttons: [
        'copy', 'csv', 'excel', 'pdf', 'print'
      ]
    }));

    
    
    
    // Hide the search box for DataTables
      $('#reviewtable_filter').css('display', 'none');
      $('#researchtable_filter').css('display', 'none');
      $('#rnapretable_filter').css('display', 'none');
       
      
      // Show the initial sheet (sheet1) and hide others
    showSheet('sheet1');
    hideAllSheetsExcept('sheet1');
  });

  function sortTable(columnIndex) {
    // TODO: Add sorting logic based on the columnIndex
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
  
  
  function showSheet(sheetId) {
// add .button.clicked  style in the begining style
    // Hide the current sheet
    if (currentSheet) {
        var currentSheetElement = document.getElementById(currentSheet);
        currentSheetElement.style.display = 'none';
    }

    // Show the selected sheet
    var sheet = document.getElementById(sheetId);
    sheet.style.display = 'block';

    // Update the current sheet
    currentSheet = sheetId;

    // Get all buttons
    var buttons = document.querySelectorAll('.button');

    // Remove clicked class from all buttons
    buttons.forEach(function(btn) {
        btn.classList.remove('clicked');
    });

    // Add clicked class to the clicked button using event.target
    event.target.classList.add('clicked');
}

  function hideAllSheetsExcept(sheetId) {
    var sheets = document.getElementsByClassName('sheet');
    for (var i = 0; i < sheets.length; i++) {
      var sheet = sheets[i];
      if (sheet.id !== sheetId) {
        sheet.style.display = 'none';
      }
    }
    }

    function showAllSheets() {
      var sheets = document.getElementsByClassName('sheet');
      for (var i = 0; i < sheets.length; i++) {
        sheets[i].style.display = 'block';
      }
    }

    function searchTables() {
      var keyword = $('#searchBox').val().toLowerCase();

      tables.forEach(function(table) {
        table.search(keyword).draw();
      });
      // Filter the sheets based on search results
    filterSheets();
  }

  function filterSheets() {
    var keyword = $('#searchBox').val().toLowerCase();
    var sheets = document.getElementsByClassName('sheet');

    for (var i = 0; i < sheets.length; i++) {
      var sheet = sheets[i];
      var table = tables[i];

      var displaySheet = false;

      table.rows().eq(0).each(function(index) {
        var row = table.row(index);
        var rowData = row.data().join(' ').toLowerCase();
        var display = rowData.includes(keyword) ? '' : 'none';
        row.nodes().to$().css('display', display);

        if (display !== 'none') {
          displaySheet = true;
        }
      });

      if (displaySheet) {
        $('#' + sheet.id).show();
      } else {
        $('#' + sheet.id).hide();
      }
    }
  }  
  </script>
        
    </body>
</html><br><br>
        
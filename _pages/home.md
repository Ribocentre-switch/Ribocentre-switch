---
title: "Ribocentre - Home"
layout: homelay
excerpt: "Ribocentre: A ribozyme database"
sitemap: false
permalink: /
---
<html lang="zh-cn">
<head>
<meta charset="utf-8"> 
<style>
  button, input, optgroup, select, textarea {
    color: #005826;
    font: inherit;
    font-weight: bold;
    margin: 0;
}
  .box_style{
    background: #f4f4f4;
  }
  .wrapper {
    display: block;
    position: relative;
    width: 100%;
    margin: 0;
    padding: 0;
    text-align: left;
    word-wrap: break-word;
    }
  .sectiontitle {
    display: block;
    max-width: 100%;
    margin: 0 auto ;
    text-align: left;
    background :#fff;
    }
  body {
    padding-top: 70px;
  }
  .well {
    max-width: 70%;
    margin: 0 auto;
    border-top: 3px solid black;
    }
  .smallwell {
    max-width: 100%;
    margin: 0 auto;
    border-top: 3px solid black;
    }
  .gsc-search-button-v2, .gsc-search-button-v2:hover, .gsc-search-button-v2:focus {
    border-color: #005826;
    background-color: #005826;
    }
</style>
</head>
<body>
<div class="wrapper box_style" >
<br>
  <div class="well" style="border: 1px solid #C9C9C9; background-color: #fff;">
    <section class="sectiontitle"> 
  
    <h1 class="post-title" itemprop="name headline"><strong>Welcome to Ribocentre-switch</strong></h1><br><br><br>
      <div class="smallwell" style="border: 1px solid #C9C9C9; background-color: #fff;">
        <strong style="color:#005826;font-weight: bold">Riboswitch</strong>  is a regulatory segment of a messenger RNA molecule that binds a small molecule, resulting in a change in production of the proteins encoded by the mRNA.[1][2][3][4] Thus, an mRNA that contains a riboswitch is directly involved in regulating its own activity, in response to the concentrations of its effector molecule. The discovery that modern organisms use RNA to bind small molecules, and discriminate against closely related analogs, expanded the known natural capabilities of RNA beyond its ability to code for proteins, catalyze reactions, or to bind other RNA or protein macromolecules.

  The original definition of the term "riboswitch" specified that they directly sense small-molecule metabolite concentrations.[5] Although this definition remains in common use, some biologists have used a broader definition that includes other cis-regulatory RNAs. However, this article will discuss only metabolite-binding riboswitches.

  Most known riboswitches occur in bacteria, but functional riboswitches of one type (the TPP riboswitch) have been discovered in archaea, plants and certain fungi. TPP riboswitches have also been found in eukaryotes eukaryotes that function via alternative splicing of mRNA..<br>
      </div><br><br>
    
  <div class="wrapper box_style " style="background-color: #fff">

  <button class="tablink" onclick="openPage('Home', this, 'white' )" id="defaultOpen" style="font-size: 20px;">Search by sequence</button>
  <button class="tablink" onclick="openPage('Contact', this, 'white')" style="font-size: 20px;">Search by text</button>
<div class="wrapper search_bg " style="border: 1px solid #C9C9C9;">

<div id="Home" class="tabcontent" style="width: 100%;height: 250px; overflow-x:hidden;overflow-y: auto;">
<html>
  <head>
    <title>Sequence search</title>
  </head>
  <body>
    <rnacentral-sequence-search
            databases='["ribocentre"]'
            examples='[
              {"description": "c-di-GMP-II-GAG riboswitch", "urs": "", "sequence": "CUGCACGCGGGAGGCUGUGAUCCGCCGGACGUACCGACUGCGGCCACCGCAGUCCGGCGGGGAGCCACUGGUGAGACCGGCCCCCGAAG"},
              {"description": "TPP riboswitch (THI element)", "urs": "", "sequence": "GTGTCCACTCACGGGTGCGCTTCATTAAGCGCTGAGAATAAACCGTTTGAACCTGATCCGGGTTATGCCGGCGATAGGAAGAGAATTATGCATAATG"}
            ]'
            rfam="true"
    />
  <script type="text/javascript" src="https://www.ribocentre.org/js/RNAcentral-sequence-search.js"></script></body>
</html>
</div>

<div id="Contact" class="tabcontent" style="width: 100%;height: 250px; overflow-x:hidden;overflow-y: auto;">
<html>
<div style="text-align:center;"><font size="5"> Search in Ribocentre </font></div>
      <!--<div class="well">-->
      <script async src="https://cse.google.com/cse.js?cx=2dcb771063bc36a13"></script>
      <div class="gcse-searchbox-only" style="text-align:center;"></div>
        <p><b>Example:&nbsp;</b>
          <a href="https://www.ribocentre.org/search.html?q=rna#gsc.tab=0&gsc.q=rna&gsc.page=1"  target="_blank">RNA</a>&nbsp;&nbsp;
          <a href="https://www.ribocentre.org/search.html?q=Ribo#gsc.tab=0&gsc.q=Ribo&gsc.page=1"  target="_blank">Ribo</a>&nbsp;&nbsp;
          <a href="https://www.ribocentre.org/search.html?q=breaker#gsc.tab=0&gsc.q=breaker&gsc.page=1"  target="_blank">Breaker</a>&nbsp;&nbsp;<br>
          <b>Quick links:&nbsp;</b>
          <a href="https://www.ribocentre.org/ribozyme">Ribozymes</a>&nbsp;&nbsp;
          <a href="https://www.ribocentre.org/publications">Publications</a>&nbsp;&nbsp;
          <a href="https://www.ribocentre.org/docs/VS-ribozyme.html" target="_blank"> VS with 3D structures</a>&nbsp;&nbsp;
          <a href="https://www.ribocentre.org/Helps">Teams</a>&nbsp;&nbsp;
        </p>
      <br>
</html>
</div>


<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
</div>
</div>
  
      </section>
   </div>
    <br>
  
</div>
<br>
</body>
</html>








  
 






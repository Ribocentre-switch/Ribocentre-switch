---
layout: post
title:  "PRPP"
date:   2023-05-17 00:00:00
author: Wenjian Liao, Zhizhong Lu
permalink: /docs/PRPP/
---
<p style="font-size: 24px"><strong>Rfam ID: <a href="https://rfam.org/family/nan" target="_blank">nan</a></strong> (nan)<br /></p>
 
<br />
<html>
<head>
  <title>Horizontally arranged click buttons</title>
  <style>
    /* Button Container Styles */
    .button-container {
      display: flex;
      justify-content: left;
      align-items: center;
      height: 50px;
    }
    
    /* Button Style */
    .button {
      display: block;
      padding: 10px;
      font-size:24px;
      margin-right: 10px;
      text-align: center;
      background-color: #efefef;
      color: #005826;
      text-decoration: none;
      border: 1px solid #005826;
      border-radius: 5px;
    }
    
    /* Mouse Hover Style */
    .button:hover {
      background-color: #999;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <p style="font-size: 16px">Click the buttons to navigate to different sections:</p>
  
  <div class="button-container">
    <a class="button" href="#timeline" >Timeline</a>
    <a class="button" href="#description">Description</a>
    <a class="button" href="#Structure and Ligand recognition">Structure&recognition</a>
    <a class="button" href="#references">References</a>
  </div>
</body>
</html>

<html lang="zh-cn">
<head>
<meta charset="utf-8"> 
<style>
  .header_box {
    border: none;
    background: #efefef;
    font-size:24px
  }
  blockquote {
  margin: 0 0 0px;
  }
</style>
</head>
<p><br /></p>
<p class="header_box" id="timeline">Timeline</p>
<div class="timeline" >
  <div class="year">
    <div class="inner">
      <span>Start</span>
    </div>
  </div>
  <ul class="days">
          
    <timelineli class="day">
     <div class="events">
       <p ><a href="https://pubmed.ncbi.nlm.nih.gov/15096624/" target="_blank">2004</a><sup>[<a href="#ref1">1</a>]</sup>&emsp;Discovery of <i>ykkC</i> motif that exhibit characteristics of riboswitch function</p>
     </div>
    </timelineli>
        

    <timelineli class="day">
     <div class="events">
       <p >Separation of <i>ykkC</i> subtype 2&emsp;<a href="https://pubmed.ncbi.nlm.nih.gov/27989440/" target="_blank">2017</a><sup>[<a href="#ref2">2</a>]</sup></p>
     </div>
    </timelineli>
        

    <timelineli class="day">
     <div class="events">
       <p ><a href="https://pubmed.ncbi.nlm.nih.gov/29504937/" target="_blank">2018</a><sup>[<a href="#ref3">3</a>]</sup>&emsp;Identification of <i>ykkC</i> subtype 2b RNAs as PRPP riboswitches, which occur in a tandem arrangement with a guanine aptamer in 127 examples</p>
     </div>
    </timelineli>
        

    <timelineli class="day">
     <div class="events">
       <p >Crystal structures of the PRPP riboswitch bound to PRPP&emsp;<a href="https://pubmed.ncbi.nlm.nih.gov/29877798/" target="_blank">2018</a><sup>[<a href="#ref4">4</a>]</sup></p>
     </div>
    </timelineli>
        

    <timelineli class="day">
     <div class="events">
       <p ><a href="https://pubmed.ncbi.nlm.nih.gov/30120360/" target="_blank">2018</a><sup>[<a href="#ref5">5</a>]</sup>&emsp;Crystal structures of the PRPP riboswitch bound to PRPP</p>
     </div>
    </timelineli>
        

  </ul>
  <div class="year year--end">
    <div class="inner">
      <span>2023...</span>
    </div>
  </div>
</div>
</html>
<br><br>
         
<font ><p class="header_box" id="description">Description</p></font>
<font >The <i>ykkC</i> RNAs were initially found in 2004 and in 2017,<i>ykkC</i> subtype 2 RNAs were separated from <i>ykkC</i> RNAs. Further analysis of the RNA sequences and consensus models of <i>ykkC</i> subtype 2 RNAs, and the assessment of the diverse types of genes found downstream of these RNAs, revealed that there are probably at least four additional distinct riboswitch classes present within the <i>ykkC</i> subtype 2 collection, termed <i>ykkC</i> subtypes 2a-2d. Phosphoribosyl pyrophosphate (PRPP, 5-phosphoribosyl-1-pyrophosphate) was identified as the ligand for <i>ykkC</i> subtype 2b RNAs (PRPP riboswitches)<sup>[<a href="#ref1">1</a>-<a href="#ref3">3</a>]</sup>.</font>
<p><br /></p>
             
> Gene association
            
<font><p>Representatives of PRPP riboswitch commonly associate with genes for <i>de novo</i> purine biosynthesis in bacteria. The genes commonly asssociated with PRPP riboswitches are shown in orange <sup>[<a href="#ref3">3</a>]</sup>.</p></font>
<table class="table table-bordered" style="table-layout:fixed;width:1000px;margin-left:auto;margin-right:auto;">
<tr >
<td style="text-align:center;padding-bottom: 0px;padding-left: 0px;padding-top: 0px;padding-right: 0px">
  <img src="/images/gene_association/PRPP_riboswitch_gene_association.svg" alt="drawing" style="width:1000px;margin-top: 0px;margin-bottom: 0px;" >
</td>
</tr>
</table>
<p><br /></p>
                 
> Gene regulation
                
<font><p>Putative mechanisms for regulation of gene expression by PRPP riboswitches from <i>Heliobacterium modesticaldum</i>. We present the  prototypical mechanism, but not all possible mechanisms<sup>[<a href="#ref3">3</a>]</sup>.</p></font>
<table class="table table-bordered" style="table-layout:fixed;width:1000px;margin-left:auto;margin-right:auto;"><tr>
  <td style="text-align:center;padding-bottom: 0px;padding-left: 0px;padding-top: 0px;padding-right: 0px">
  <img src="/images/gene_regulation/PRPP_riboswitch_gene_regulation.svg" alt="drawing" style="width:1000px;margin-top: 0px;margin-bottom: 0px;" >
  </td>
</tr>
</table>
<br><br>
                         
<p class="header_box" id="Structure and Ligand recognition">Structure and Ligand recognition</p>
> 2D representation
        
<font><p>Top: Consensus sequence and secondary structure model for the PRPP riboswitch. Bottom: Secondary structure depictions of the <i>Thermoanaerobacter mathranii</i> PRPP riboswitch according to PDB ID: 6CK5<sup>[<a href="#ref4">4</a>]</sup>.</p></font>
<font><p>5' GUGAAAGUGUACCUAGGGUUCCAGCCUAUUUGUAGGUGUUCGGACCGAGCGGUACAGGUAUAUUUUUAUAUACCACACCUUAGGGACAAAAGCCCGGGAGGAUAGGUUUCACUCGUA 3' (Sequence from bottom structure )</p><br></font>
<html>
<div>
    <div class="entry-content clearfix" itemprop="articleBody description" style="overflow: auto;">
        <div style="display: flex; justify-content: center;">
        <div>
        <div id="image-caption" style="text-align: left; margin-left: 20px;"></div>
            <table class="clear" cellspacing="5" style="border-spacing: 0; margin: 0 auto;">
                <tr>
                    <td style="border: 1px solid black;width:800px">
                        <div id="layer_pdb" style="display: block">
                            <a id="image-link0" href="#" title="">
                                <div id="zoom-wrapper0" class="zoom-wrapper0">
                                    <div id="zoom-area0" class="zoom-area0">
                                        <img id="image-preview0" src="#" height="500" />
                                    </div>
                                </div>
                            </a>
                        </div>
                    </td>
                    <td class="left" style="border: none; padding: 0; vertical-align: top">
                        <div class="image-wrapper" style="margin-bottom: 40px;">
                            <img id="image-a0" src="/images/2D/PRPP_riboswitch_2D1.svg" width="200" style="border: 1px solid black; cursor: zoom-in;margin-top: 0px;margin-bottom: 0px;" alt="big.png"/>
                            <div class="button-wrapper">
                                <a class="btn " href="javascript:showImage0('/images/2D/PRPP_riboswitch_2D1.svg');">&lt;&lt; Switch to</a>
                            </div>
                        </div>
                        <div class="image-wrapper" >
                            <img id="image-b" src="/images/2D/PRPP_riboswitch_2D2.svg" width="200" style="border: 1px solid black; cursor: zoom-in;margin-top: 0px;margin-bottom: 0px;" alt="down.png"/>
                            <div class="button-wrapper">
                                <a class="btn " href="javascript:showImage0('/images/2D/PRPP_riboswitch_2D2.svg');">&lt;&lt; Switch to</a>
                            </div>
                        </div>
                    </td>
                </tr>
            </table>
        </div>
        </div>
    </div>
</div>

<style>
    .image-wrapper {
        display: block;
        text-align: center;
        margin-bottom: 20px;
    }

    .button-wrapper {
        text-align: left;
    }

    .btn {
      
      padding: 10px;
      font-size:16px;
      margin-right: 10px;
      text-align: left;
      background-color: #efefef;
      color: #005826;
      text-decoration: none;
      font-weight: bold;
      border: 1px solid #005826;
      border-radius: 5px;
      
    }
    /* Mouse Hover Style */
    .btn:hover {
      color: #005826;
      background-color: #999;
      cursor: pointer;
    }
    
    

    .zoom-wrapper0 {
        width: 800px;
        border: 1px solid #fff;
        overflow: hidden;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    
</style>

<script src="https://www.ribocentre.org/js/panzoom.js"></script>
<script type="text/javascript">
    function showImage0(imageUrl) {
        var imagePreview = document.getElementById("image-preview0");
        var imageLink = document.getElementById("image-link0");
        var imageCaption = document.getElementById("image-caption");

        imagePreview.src = imageUrl;
        imageLink.href = imageUrl;

       
    }

    window.addEventListener('DOMContentLoaded', (event) => {
        var imagePreview = document.getElementById("image-preview0");
        var imageLink = document.getElementById("image-link0");
        var rightImage = document.getElementById("image-a0");

        imagePreview.src = rightImage.src;
        imageLink.href = rightImage.src;
        
        var zoomArea = document.getElementById("zoom-area0");
        var panzoom = Panzoom(zoomArea, {
            maxScale: 6,
        });
        zoomArea.addEventListener("wheel", function(e) {
            e.preventDefault();
            panzoom.zoomWithWheel(e);
        });
        panzoom.zoom(0.8);
    });
</script>
</html>
 <p><br /></p>
                     
> 3D visualisation
                
<font >The overall structure of the <i>Thermoanaerobacter mathranii</i> PRPP riboswitch was generated from PDB ID: 6CK5 at 2.49 Å resolution bound with PRPP. PRPP (shown in sticks) is labeled in red. The metals (M) are colored dark grey. M1 and M3 are modeled as Ba<sup>2+</sup>, and M2 is modeled as Mg<sup>2+</sup>. Additional available structures that have been solved and detailed information are accessible on <i>Structures</i> page <sup>[<a href="#ref4">4</a>]</sup>.</font>
<div ><font ><p style="text-align:right;margin-bottom: 0px;">(Clicking the "Settings/Controls info" to turn Spin off)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p></font>
  <table class="table table-bordered" style="table-layout:fixed;width:1000px;margin-left:auto;margin-right:auto;"><tr>
  <td style="text-align:center;padding-bottom: 0px;padding-left: 0px;padding-top: 0px;padding-right: 0px">
  <img src="/images/3D/PRPP_riboswitch_3D1.svg" alt="drawing" style="width:500px;margin-top: 0px;margin-bottom: 0px;" >
  </td>
  <td style="text-align:center;padding-bottom: 0px;padding-left: 0px;padding-top: 0px;padding-right: 0px">
  <html lang="en">
    <head>
      <meta charset="utf-8" />
      <meta name="viewport" content="width=device-width, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <title>PDBe Molstar</title>
      <!-- Molstar CSS & JS -->
      <link rel="stylesheet" type="text/css" href="https://www.ebi.ac.uk/pdbe/pdb-component-library/css/pdbe-molstar-1.2.1.css">
      <script src="/js/mol/ro_pdbe-molstar-plugin-1.2.1.js"></script>
        <style>
          * {
              margin: 0;
              padding: 0;
              box-sizing: border-box;
          }
          .msp-plugin ::-webkit-scrollbar-thumb {
              background-color: #474748  !important;
          }
          .viewerSection1 {
            padding-top: 0px;
          }
          .controlsSection1 {
            width: 300px;
              display: flex;
              float:left;
              padding: 0px 0 0 0;
              height:25px;
            }
            .controlBox1 {
              border: 0px solid lightgray;
              padding: 0px;
              margin-bottom: 0px;
            }
          #myViewer1{
            float:left;
            width:500px;
            height: 500px;
            position:relative;
          }
        </style>
    </head>
    <body onload="customize()">
        <div class="controlsSection1">
            <button onclick="
              var selectSections1 = [
                {
  struct_asym_id: 'A', 
  start_residue_number:1, 
  end_residue_number:6, 
  color:{r:194,g:194,b:255}
},
{
  struct_asym_id: 'A', 
  start_residue_number:7, 
  end_residue_number:12, 
  color:{r:128,g:219,b:158}
},
{
  struct_asym_id: 'A', 
  start_residue_number:13, 
  end_residue_number:22, 
  color:{r:255,g:135,b:10}
},
{
  struct_asym_id: 'A', 
  start_residue_number:23, 
  end_residue_number:36, 
  color:{r:190,g:110,b:190}
},
{
  struct_asym_id: 'A', 
  start_residue_number:37, 
  end_residue_number:49, 
  color:{r:255,g:135,b:10}
},
{
  struct_asym_id: 'A', 
  start_residue_number:50, 
  end_residue_number:55, 
  color:{r:128,g:219,b:158}
},
{
  struct_asym_id: 'A', 
  start_residue_number:56, 
  end_residue_number:73, 
  color:{r:255,g:170,b:220}
},
{
  struct_asym_id: 'A', 
  start_residue_number:74, 
  end_residue_number:100, 
  color:{r:10,g:11,b:255}
},
{
  struct_asym_id: 'A', 
  start_residue_number:101, 
  end_residue_number:110, 
  color:{r:194,g:194,b:255}
},
{
  struct_asym_id: 'A', 
  start_residue_number:217, 
  end_residue_number:217, 
  color:{r:255,g:11,b:12}
}
              ]
            viewerInstance1.visual.select({ data: selectSections1, nonSelectedColor: {r:255,g:255,b:255}})" style="float:right;height:25px;width: 120px;">Color Selection</button><br><br>
          <button button style="float: left;height:25px;width: 120px;" onclick="viewerInstance1.visual.clearSelection()">Clear Selection</button><br><br>
      </div>
    <div class="viewerSection1">
    <!-- Molstar container -->
      <div id="myViewer1"></div>
    </div>
    <script>
      var viewerInstance1 = new PDBeMolstarPlugin();
      var options1 = {
        customData:{
        url:'/docs/pdbfiles/6CK5.pdb',
        format: 'pdb'},
        expanded: false,
        hideControls: true,
        bgColor: {r:255, g:255, b:255},
        }
      var viewerContainer1 = document.getElementById('myViewer1');
      viewerInstance1.render(viewerContainer1, options1);
  window.addEventListener('load', function() {
    var colorSelectionButton1 = document.querySelector('.controlsSection1 button');
    colorSelectionButton1.click();
  });


    </script>
    </body>
    </html></td>
  </tr></table><br>
  </div>
  <p><br /></p>
                 
> Binding pocket
                    
<font><p>Left: Surface representation of the binding pocket of the <i>Thermoanaerobacter mathranii</i> PRPP riboswitch generated from PDB ID: 6CK5 2.49 Å. PRPP (shown in sticks) is labeled in red. Right: The hydrogen bonds and coordination to metal ions of the binding sites of the PRPP riboswitch bound with PRPP. M1 and M3 are modeled as Ba<sup>2+</sup>, and M2 is modeled as Mg<sup>2+</sup><sup>[<a href="#ref4">4</a>]</sup>.</p></font>
<table class="table table-bordered" style="table-layout:fixed;width:1000px;margin-left:auto;margin-right:auto;"><tr>
<td style="text-align:center;padding-bottom: 0px;padding-left: 0px;padding-top: 0px;padding-right: 0px"><img src="/images/binding_pockets/PRPP_riboswitch_binding_pockets1.svg" alt="drawing" style="width:500px"  px="" /></td>
<td style="text-align:center;padding-bottom: 0px;padding-left: 0px;padding-top: 0px;padding-right: 0px"><img src="/images/binding_pockets/PRPP_riboswitch_binding_pockets2.svg" alt="drawing" style="width:500px"  px="" /></td>
</tr>
</table>
<p><br /></p>
                     
> Ligand recognition
                

<font><p>Chemical structures of PRPP (phosphoribosyl pyrophosphate, or 5-phosphoribosyl-1-pyrophosphate). The apparent K<sub>D</sub> is shown on bottom. Refer to the corresponding references for comprehensive details regarding reaction conditions and species information in measuring the dissociation constant displayed below<sup>[<a href="#ref3">3</a>-<a href="#ref5">5</a>]</sup>.</p></font>
<table class="table table-bordered" style="table-layout:fixed;width:1000px;margin-left:auto;margin-right:auto;">
<tr>
<td style="text-align:center;padding-bottom: 0px;padding-left: 0px;padding-top: 0px;padding-right: 0px">
  <img src="/images/ligand_recognition/PRPP_riboswitch_ligand_recognition.svg" alt="drawing" style="width:1000px;margin-top: 0px;margin-bottom: 0px;" >
</td>
</tr>
</table>
<br /><br>
                 
<p class="header_box" id="references">References</p>
                
<a id="ref1"></a><font><strong>[1] New RNA motifs suggest an expanded scope for riboswitches in bacterial genetic control.</strong></font><br />
Barrick, J. E. et al.<br />
<a href="https://pubmed.ncbi.nlm.nih.gov/15096624/" target="_blank">Proc. Natl. Acad. Sci. U. S. A. 101, 6421–6426 (2004).</a>
<br />
                
<a id="ref2"></a><font><strong>[2] Metabolism of Free Guanidine in Bacteria Is Regulated by a Widespread Riboswitch Class.</strong></font><br />
Nelson, J. W., Atilho, R. M., Sherlock, M. E., Stockbridge, R. B. & Breaker, R. R.<br />
<a href="https://pubmed.ncbi.nlm.nih.gov/27989440/" target="_blank">Mol. Cell 65, (2017).</a>
<br />
                
<a id="ref3"></a><font><strong>[3] Tandem riboswitches form a natural Boolean logic gate to control purine metabolism in bacteria.</strong></font><br />
Sherlock, M. E., Sudarsan, N., Stav, S. & Breaker, R. R.<br />
<a href="https://pubmed.ncbi.nlm.nih.gov/29504937/" target="_blank">Elife 7, (2018).</a>
<br />
                
<a id="ref4"></a><font><strong>[4] Structures of two aptamers with differing ligand specificity reveal ruggedness in the functional landscape of RNA.</strong></font><br />
Knappenberger, A. J., Reiss, C. W. & Strobel, S. A.<br />
<a href="https://pubmed.ncbi.nlm.nih.gov/29877798/" target="_blank">Elife 7, (2018).</a>
<br />
                
<a id="ref5"></a><font><strong>[5] ykkC riboswitches employ an add-on helix to adjust specificity for polyanionic ligands.</strong></font><br />
Peselis, A. & Serganov, A.<br />
<a href="https://pubmed.ncbi.nlm.nih.gov/30120360/" target="_blank">Nat. Chem. Biol. 14, 887–894 (2018).</a>
<br />
                
---
layout: post
title:  "Hammerhead"
date:   2022-04-18T14:25:52-05:00
author: Huang Yuanyin, Lin Xiaowei
permalink: /test_3d/
---
> 3D visualisation

<font size=4>The overall structure of the hammerhead ribozyme is shown. This representation was generated from PDB ID: 3ZD5 at 2.2 Å resolution. Note the tertiary interaction between the terminal loop of helix II and the internal loop in helix I. </font>

<table>
<tr>
<td><img src="https://www.ribocentre.org/images/HammerheadPic/hammerhead3D&lt;/html&gt;.png" alt="drawing" style="weight:200px;height:350px;" border=0></td>
<td>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>PDBe Molstar</title>
    <!-- Molstar CSS & JS -->
    <link rel="stylesheet" type="text/css" href="https://www.ebi.ac.uk/pdbe/pdb-component-library/css/pdbe-molstar-1.2.1.css">
    <script src="https://www.ebi.ac.uk/pdbe/pdb-component-library/js/pdbe-molstar-plugin-1.2.1.js"></script>
        <script>
        function customize()
        {
            viewerInstance.canvas.setBgColor({r:255, g:255, b:255})
        }
        </script>

  <style>
      * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
      }
      .msp-plugin ::-webkit-scrollbar-thumb {
          background-color: #474748  !important;
      }
      .viewerSection {
        padding-top: 0px;
      }
      .controlsSection {
        width: 300px;
        float: margin-right;
        padding: 10px 0 0 0px;
        margin-right: 10px;
      }
      #myViewer{
        float:left;
        width:800px;
        height: 800px;
        position:relative;  
      }

  </style>
  </head>
  <body onload="customize()">
	   <body onload="customize()">
        <div class="controlsSection">
          <button onclick="
            var selectSections = [
              {
                struct_asym_id: 'B', 
                start_residue_number: 7, 
                end_residue_number: 12, 
                color:{r:0,g:111,b:222}
              },
              {
                struct_asym_id: 'B', 
                start_residue_number: 17, 
                end_residue_number: 20, 
                color:{r:0,g:111,b:222}
              },
              {
                struct_asym_id: 'A', 
                start_residue_number: 1, 
                end_residue_number: 5, 
                color:{r:0,g:111,b:222}
              },
              {
                struct_asym_id: 'A', 
                start_residue_number: 9, 
                end_residue_number: 14, 
                color:{r:0,g:111,b:222}
              },
              {
                struct_asym_id: 'A', 
                start_residue_number: 22, 
                end_residue_number: 25, 
                color:{r:192,g:109,b:35}
              },
              {
                struct_asym_id: 'A', 
                start_residue_number: 32, 
                end_residue_number: 35, 
                color:{r:192,g:109,b:35}
              },
              {
                struct_asym_id: 'B', 
                start_residue_number: 1, 
                end_residue_number: 5, 
                color:{r:104,g:175,b:49}
              },
              {
                struct_asym_id: 'A', 
                start_residue_number: 39, 
                end_residue_number: 43, 
                color:{r:104,g:175,b:49}
              },
              {
                struct_asym_id: 'A', 
                start_residue_number: 36, 
                end_residue_number: 36, 
                color:{r:0,g:0,b:207}
              },
              {
                struct_asym_id: 'A', 
                start_residue_number: 20, 
                end_residue_number: 20, 
                color:{r:245,g:0,b:0}
              },
              {
                struct_asym_id: 'B', 
                start_residue_number: 14, 
                end_residue_number: 14, 
                color:{r:0,g:111,b:222}
              }
              
            ]
          viewerInstance.visual.select({ data: selectSections, nonSelectedColor: {r:255,g:255,b:255}})" style="float:right;height:25px;">Color Selection</button><br><br>

        <button button style="float: left;height:25px;" onclick="viewerInstance.visual.clearSelection()">Clear Selection</button><br><br>

    </div>
    <div class="viewerSection">
  <!-- Molstar container -->
  <div id="myViewer">
  </div>
  <script>
    var viewerInstance = new PDBeMolstarPlugin();
    var options = {
      moleculeId: '3zd5',
      expanded: false,
      expanded: false,
      hideControls: true
      }
    var viewerContainer = document.getElementById('myViewer');
    viewerInstance.render(viewerContainer, options);
  </script>
</html></td></tr></table>
<p><br /></p>
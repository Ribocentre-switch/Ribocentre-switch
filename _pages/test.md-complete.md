---
layout: post
title:  "Hammerhead"
date:   2022-04-18T14:25:52-05:00
author: Huang Yuanyin, Lin Xiaowei
permalink: /test_complete/
---

## Structure

***

> 2D representation

<font size=4>The secondary structure of the full-length hammerhead ribozyme with the general acid (red) and base (blue) is shown. The large arrow (baby blue) points to the scissile bond. The green line notes the tertiary interaction between the terminal loop of helix II and the internal loop in helix I. </font><br>

<table><tr>
<td>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<style>
   body {
    width: 100%;
    height: 100vh;
}
   button {
   margin-right: 0px;
}
   .main-container {
    display: flex;
    align-items: left;
    justify-content: center;
    height: 100%;
}
   .zoom-wrapper1 {
    width: 450px;
    height: 400px;
    border: 1px solid #fff;
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>
    <div class="main-container">
        <div class="zoom-wrapper1">
            <div class="zoom-area1">
                <img src="https://www.ribocentre.org/images/HammerheadPic/Hammerhead2D.svg" alt="drawing" style="height:160px" />
            </div>
        </div>
    </div>
    <script src="https://www.ribocentre.org/js/panzoom.js"></script>
    <script type='text/javascript'>
      var zoomWraper1 = document.querySelector(".zoom-wrapper1");
      var panzoom1 = Panzoom(document.querySelector(".zoom-area1"), {
      maxScale: 6
      });
      zoomWraper1.addEventListener("wheel", panzoom1.zoomWithWheel);
      panzoom1.zoom(300 / document.querySelector(".zoom-area1 img").height);
      panzoom2.pan(0, 0);
      </script>
</td>
<td>
<link rel="stylesheet" type="text/css" href="https://www.ribocentre.org/css/fornac.css" media="screen" />

<div id="custom_colors"></div>
<form onsubmit="return handleCustomColorApply()" class="optionsform">
  <textarea id="CustomColorText" name="CustomColorText" textarea name="hide" style="display:none;" >
    1-5:#68AF31 56:blue 40:red 59-63:#68AF31 7-12:#18529A 14:#18529A 17-25:#18529A 29-34:#18529A 42-45:#C06D23 52-55:#C06D23 
  </textarea>
</form>
<meta charset="utf-8" />
    <script type="text/javascript" src="https://www.ribocentre.org/js/jquery.js"></script>
    <script type="text/javascript" src="https://www.ribocentre.org/js/d3.js"></script>
    <script type='text/javascript' src='https://www.ribocentre.org/js/demo/rsvfornac.js'></script>
    <script type="text/javascript">
      "use strict"
      function customColorsContainer() {
         let container = new fornac.FornaContainer("#custom_colors",
                 {'applyForce': 1,'editable':'true', 'initialSize':[450,400]});
         let options = {'structure': '(((((.((((((.(..(((()))))...)))))).......((((......))))...)))))',
             'sequence':             'GGCGUCCUGGUAUCCAAUCCGGAUGUACUACCAGCUGAUGAGUCCCAAAUAGGACGAAACGCC'
         };
         container.addRNA(options.structure, options);
         return container;
     }
     let cc = customColorsContainer();
 
     function handleCustomColorApply() {
       cc.addCustomColorsText(document.getElementById("CustomColorText").value);
       return false;
     }
     handleCustomColorApply();
 
     </script>

</td>
</tr></table><br>

> 3D visualisation

<font size=4>The overall structure of the hammerhead ribozyme is shown. This representation was generated from PDB ID: 3ZD5 at 2.2 Å resolution. Note the tertiary interaction between the terminal loop of helix II and the internal loop in helix I. </font>
<table><tr>
<td><img src="https://www.ribocentre.org/images/HammerheadPic/hammerhead3D.png" alt="drawing" style="weight:200px;height:350px;" border="0" /></td>
<td>
  <html lang="en">
    <head>
      <meta charset="utf-8" />
      <meta name="viewport" content="width=device-width, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
      <title>PDBe Molstar - Helper functions</title>
      <!-- Molstar CSS & JS -->
      <link rel="stylesheet" type="text/css" href="https://www.ebi.ac.uk/pdbe/pdb-component-library/css/pdbe-molstar-3.0.0.css">
      <script type="text/javascript" src="https://www.ebi.ac.uk/pdbe/pdb-component-library/js/pdbe-molstar-plugin-3.0.0.js"></script>
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
            background-color: #474748 !important;
        }
        .viewerSection {
          padding-top: 0px;
        }
        .controlsSection {
          width: 300px;
          display: flex;
          float:left;
          padding: 0px 0 0 0;
          height:25px;
        }
        .controlBox {
          border: 0px solid lightgray;
          padding: 0px;
          margin-bottom: 0px;
        }
        #myViewer{
          float:left;
          width:450px;
          height: 455px;
          position:relative;
        }
  </style>
  </head>
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
      <div id="myViewer"></div>
      
    </div>
    <script>

      //Create plugin instance
      var viewerInstance = new PDBeMolstarPlugin();
  
      //Set options (Checkout available options list in the documentation)
      var options = {
        moleculeId: '3zd5',
        hideControls: true
      }
      
      //Get element from HTML/Template to place the viewer 
      var viewerContainer = document.getElementById('myViewer');
  
      //Call render method to display the 3D view
      viewerInstance.render(viewerContainer, options);
      
    </script>
  </body>

</html>
</td>
</tr></table>


---
layout: post
title:  "HDV"
date:   2022-06-23 
author: Lin xiaowei,Liao wenjian
categories: /HMP/
---
## 2D representation 

Secondary structure depictions of the HDV ribozyme with the scissile phosphates (blue arrow )and the general acid (red circle ) and base (blue dot) are shown. The HDV ribozymes act with the direct involvement of metal ions shown by green spheres with octahedral coordination of red water molecules of hydration.

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
    
    <div class="zoom-wrapper1">
        <div class="zoom-area1">
            <img src="https://www.ribocentre.org/images/HDVPic/HDV2D.svg" alt="drawing" style="width:135px;height:140px" />
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
     3-9:#E60012 33-39:#E60012 12-18:#036EB8 69-74:#036EB8 19-21:#2EA7E0 30-32:#2EA7E0 23-24:#F39800 40-41:#F39800 46-49:#E6A8CA 60-63:#E6A8CA
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
         let options = {'structure': '..(((((((...[[[[[[(((.[[.....))))))))))]]....((((..........)))).....]]]]]]',
             'sequence':             'AUGGCCGGCAUGGUCCCAGCCUCCUCGCUGGCGCCGGCUGGGCAACACCAUUGCACUCCGGUGGUGAAUGGGAC'
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



  







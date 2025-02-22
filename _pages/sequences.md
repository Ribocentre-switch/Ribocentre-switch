---
title: "Riboswitches - Sequences"
layout: riboswitch
excerpt: "Riboswitches: A riboswitch database"
sitemap: True
permalink: /sequences/
---
<h1 class="post-title" itemprop="name headline">Sequences</h1>
Shows the sequence of Riboswitch (Rfam ID for fasta file download). We keep the U in the partial sequence because it is consistent with the sequence information in the fasta file. ( We provide the script could change T into U on the page). <a href="https://www.ribocentre.org/downloads/sequence-T2U.ipynb" target="_blank" download="sequence-T2U.ipynb"><button class="btn btn-secondary"><span class="glyphicon glyphicon-download-alt"></span>&nbsp;&nbsp;Download Script</button></a><br><br>
<html>
<head>
<style>
     .header_box {
    border: none;
    background: #efefef;
    font-size:24px
  }
  h2{
    font-size:20px
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
    /* 隐藏所有 sheet */
    .sheet {
      display: none;
    }
    /*一闪一闪*/
    .updating-text {
      animation: updateText 2s infinite;
      font-weight:bold;
      color:#005826
    }
    @keyframes updateText {
      0%, 100% {
        opacity: 1;
      }
      50% {
        opacity: 0.3;
      }
    }
    /*一闪一闪*/
</style>
</head>
<div class="sectiontitle" style="border: 1px solid #C9C9C9; background-color: #fff;">
<p class="header_box" >Search by sequence<span class="updating-text"> (Continuously updated)</span></p>
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
</div>

<br>
<div class="sectiontitle" style="border: 1px solid #C9C9C9; background-color: #fff;">
<p class="header_box" >About sequence in Riboswitch database</p>
The table below presents the complete collection of currently available sequences from RNAcentre. Click 'download' to obtain the desired target sequence.<br><br>

        
 <div style="display: flex;overflow:auto">
    <table style="flex: 1;" class="table-style1">
      <tr>
        <th>Name</th>
        <th>Rfam ID</th>
        <th>Download linker</th>
      </tr>
        
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/FMN' target='_blank'>FMN</a></td>
      <td>RF00050</td>
      <td><a href="/downloads/sequences/RF00050.fa.gz" onclick="downloadFile('/downloads/sequences/RF00050.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/TPP' target='_blank'>TPP</a></td>
      <td>RF00059</td>
      <td><a href="/downloads/sequences/RF00059.fa.gz" onclick="downloadFile('/downloads/sequences/RF00059.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Manganese' target='_blank'>Mn2+</a></td>
      <td>RF00080</td>
      <td><a href="/downloads/sequences/RF00080.fa.gz" onclick="downloadFile('/downloads/sequences/RF00080.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/SAM-I_clan' target='_blank'>SAM-I</a></td>
      <td>RF00162</td>
      <td><a href="/downloads/sequences/RF00162.fa.gz" onclick="downloadFile('/downloads/sequences/RF00162.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Guanine' target='_blank'>Guanine</a></td>
      <td>RF00167</td>
      <td><a href="/downloads/sequences/RF00167.fa.gz" onclick="downloadFile('/downloads/sequences/RF00167.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Lysine' target='_blank'>Lysine</a></td>
      <td>RF00168</td>
      <td><a href="/downloads/sequences/RF00168.fa.gz" onclick="downloadFile('/downloads/sequences/RF00168.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Cobalamine' target='_blank'>AdoCbl</a></td>
      <td>RF00174</td>
      <td><a href="/downloads/sequences/RF00174.fa.gz" onclick="downloadFile('/downloads/sequences/RF00174.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/T-box' target='_blank'>T-box</a></td>
      <td>RF00230</td>
      <td><a href="/downloads/sequences/RF00230.fa.gz" onclick="downloadFile('/downloads/sequences/RF00230.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/GlcN6P' target='_blank'>GlcN6P</a></td>
      <td>RF00234</td>
      <td><a href="/downloads/sequences/RF00234.fa.gz" onclick="downloadFile('/downloads/sequences/RF00234.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/c-di-AMP' target='_blank'>c-di-AMP</a></td>
      <td>RF00379</td>
      <td><a href="/downloads/sequences/RF00379.fa.gz" onclick="downloadFile('/downloads/sequences/RF00379.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Magnesium' target='_blank'>Mg2＋-I</a></td>
      <td>RF00380</td>
      <td><a href="/downloads/sequences/RF00380.fa.gz" onclick="downloadFile('/downloads/sequences/RF00380.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Guanidine' target='_blank'>Guanidine-I</a></td>
      <td>RF00442</td>
      <td><a href="/downloads/sequences/RF00442.fa.gz" onclick="downloadFile('/downloads/sequences/RF00442.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Glycine' target='_blank'>Glycine</a></td>
      <td>RF00504</td>
      <td><a href="/downloads/sequences/RF00504.fa.gz" onclick="downloadFile('/downloads/sequences/RF00504.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/SAM-II_clan' target='_blank'>SAM-II</a></td>
      <td>RF00521</td>
      <td><a href="/downloads/sequences/RF00521.fa.gz" onclick="downloadFile('/downloads/sequences/RF00521.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/PreQ' target='_blank'>PreQ1-I</a></td>
      <td>RF00522</td>
      <td><a href="/downloads/sequences/RF00522.fa.gz" onclick="downloadFile('/downloads/sequences/RF00522.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/SAM-I_clan' target='_blank'>SAM-IV</a></td>
      <td>RF00634</td>
      <td><a href="/downloads/sequences/RF00634.fa.gz" onclick="downloadFile('/downloads/sequences/RF00634.fa.gz')">Download</a></td>
    </tr> 
            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/c-di-GMP' target='_blank'>c-di-GMP</a></td>
      <td>RF01051</td>
      <td><a href="/downloads/sequences/RF01051.fa.gz" onclick="downloadFile('/downloads/sequences/RF01051.fa.gz')">Download</a></td>
    </tr> 
            
</table>
    
<div style="width: 20px;"></div>
        
    <table style="flex: 1;" class="table-style1">
      <tr>
        <th>Name</th>
        <th>Rfam ID</th>
        <th>Download linker</th>
      </tr>
        
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/PreQ' target='_blank'>PreQ1-II</a></td>
      <td>RF01054</td>
      <td><a href="/downloads/sequences/RF01054.fa.gz" onclick="downloadFile('/downloads/sequences/RF01054.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/MoCo&Wco' target='_blank'>MoCo</a></td>
      <td>RF01055</td>
      <td><a href="/downloads/sequences/RF01055.fa.gz" onclick="downloadFile('/downloads/sequences/RF01055.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Magnesium' target='_blank'>Mg2＋-II</a></td>
      <td>RF01056</td>
      <td><a href="/downloads/sequences/RF01056.fa.gz" onclick="downloadFile('/downloads/sequences/RF01056.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/SAH' target='_blank'>SAH</a></td>
      <td>RF01057</td>
      <td><a href="/downloads/sequences/RF01057.fa.gz" onclick="downloadFile('/downloads/sequences/RF01057.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Guanidine' target='_blank'>Guanidine-II</a></td>
      <td>RF01068</td>
      <td><a href="/downloads/sequences/RF01068.fa.gz" onclick="downloadFile('/downloads/sequences/RF01068.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Cobalamine' target='_blank'>AdoCbl</a></td>
      <td>RF01482</td>
      <td><a href="/downloads/sequences/RF01482.fa.gz" onclick="downloadFile('/downloads/sequences/RF01482.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Cobalamine' target='_blank'>AqCbl</a></td>
      <td>RF01689</td>
      <td><a href="/downloads/sequences/RF01689.fa.gz" onclick="downloadFile('/downloads/sequences/RF01689.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Glutamine' target='_blank'>Glutamine-II</a></td>
      <td>RF01704</td>
      <td><a href="/downloads/sequences/RF01704.fa.gz" onclick="downloadFile('/downloads/sequences/RF01704.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/SAM-I_clan' target='_blank'>SAM-I/IV</a></td>
      <td>RF01725</td>
      <td><a href="/downloads/sequences/RF01725.fa.gz" onclick="downloadFile('/downloads/sequences/RF01725.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/SAM-SAH' target='_blank'>SAM-SAH</a></td>
      <td>RF01727</td>
      <td><a href="/downloads/sequences/RF01727.fa.gz" onclick="downloadFile('/downloads/sequences/RF01727.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Fluoride' target='_blank'>Fluoride</a></td>
      <td>RF01734</td>
      <td><a href="/downloads/sequences/RF01734.fa.gz" onclick="downloadFile('/downloads/sequences/RF01734.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Glutamine' target='_blank'>Glutamine-I</a></td>
      <td>RF01739</td>
      <td><a href="/downloads/sequences/RF01739.fa.gz" onclick="downloadFile('/downloads/sequences/RF01739.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/ZTP' target='_blank'>ZTP</a></td>
      <td>RF01750</td>
      <td><a href="/downloads/sequences/RF01750.fa.gz" onclick="downloadFile('/downloads/sequences/RF01750.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Guanidine' target='_blank'>Guanidine-III</a></td>
      <td>RF01763</td>
      <td><a href="/downloads/sequences/RF01763.fa.gz" onclick="downloadFile('/downloads/sequences/RF01763.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Azaaromatic' target='_blank'>Azaaromatic</a></td>
      <td>RF01764</td>
      <td><a href="/downloads/sequences/RF01764.fa.gz" onclick="downloadFile('/downloads/sequences/RF01764.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/SAM-III' target='_blank'>SAM-III</a></td>
      <td>RF01767</td>
      <td><a href="/downloads/sequences/RF01767.fa.gz" onclick="downloadFile('/downloads/sequences/RF01767.fa.gz')">Download</a></td>
    </tr> 
                    
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/c-di-GMP' target='_blank'>c-di-GMP-II</a></td>
      <td>RF01786</td>
      <td><a href="/downloads/sequences/RF01786.fa.gz" onclick="downloadFile('/downloads/sequences/RF01786.fa.gz')">Download</a></td>
    </tr> 
                    
</table>
    
<div style="width: 20px;"></div>
        
    <table style="flex: 1;" class="table-style1">
      <tr>
        <th>Name</th>
        <th>Rfam ID</th>
        <th>Download linker</th>
      </tr>
        
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/SAM-II_clan' target='_blank'>SAM-V</a></td>
      <td>RF01826</td>
      <td><a href="/downloads/sequences/RF01826.fa.gz" onclick="downloadFile('/downloads/sequences/RF01826.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/THF' target='_blank'>THF-I</a></td>
      <td>RF01831</td>
      <td><a href="/downloads/sequences/RF01831.fa.gz" onclick="downloadFile('/downloads/sequences/RF01831.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/PreQ' target='_blank'>preQ1-III</a></td>
      <td>RF02680</td>
      <td><a href="/downloads/sequences/RF02680.fa.gz" onclick="downloadFile('/downloads/sequences/RF02680.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/NiCo' target='_blank'>NiCo</a></td>
      <td>RF02683</td>
      <td><a href="/downloads/sequences/RF02683.fa.gz" onclick="downloadFile('/downloads/sequences/RF02683.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/SAM-VI' target='_blank'>SAM-VI</a></td>
      <td>RF02885</td>
      <td><a href="/downloads/sequences/RF02885.fa.gz" onclick="downloadFile('/downloads/sequences/RF02885.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/PRA' target='_blank'>PRA</a></td>
      <td>RF02974</td>
      <td><a href="/downloads/sequences/RF02974.fa.gz" onclick="downloadFile('/downloads/sequences/RF02974.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/THF' target='_blank'>THF-II</a></td>
      <td>RF02977</td>
      <td><a href="/downloads/sequences/RF02977.fa.gz" onclick="downloadFile('/downloads/sequences/RF02977.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/NAD' target='_blank'>NAD+-I</a></td>
      <td>RF03013</td>
      <td><a href="/downloads/sequences/RF03013.fa.gz" onclick="downloadFile('/downloads/sequences/RF03013.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Li' target='_blank'>Li+-II</a></td>
      <td>RF03038</td>
      <td><a href="/downloads/sequences/RF03038.fa.gz" onclick="downloadFile('/downloads/sequences/RF03038.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Xanthine' target='_blank'>Xanthine-I</a></td>
      <td>RF03054</td>
      <td><a href="/downloads/sequences/RF03054.fa.gz" onclick="downloadFile('/downloads/sequences/RF03054.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Li' target='_blank'>Li+-I</a></td>
      <td>RF03057</td>
      <td><a href="/downloads/sequences/RF03057.fa.gz" onclick="downloadFile('/downloads/sequences/RF03057.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/Na' target='_blank'>Na+-I</a></td>
      <td>RF03071</td>
      <td><a href="/downloads/sequences/RF03071.fa.gz" onclick="downloadFile('/downloads/sequences/RF03071.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/2-dG' target='_blank'>2-dG-II</a></td>
      <td>RF03165</td>
      <td><a href="/downloads/sequences/RF03165.fa.gz" onclick="downloadFile('/downloads/sequences/RF03165.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/c-di-GMP' target='_blank'>c-di-GMP</a></td>
      <td>RF03167</td>
      <td><a href="/downloads/sequences/RF03167.fa.gz" onclick="downloadFile('/downloads/sequences/RF03167.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/c-di-GMP' target='_blank'>c-di-GMP</a></td>
      <td>RF03168</td>
      <td><a href="/downloads/sequences/RF03168.fa.gz" onclick="downloadFile('/downloads/sequences/RF03168.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/c-di-GMP' target='_blank'>c-di-GMP</a></td>
      <td>RF03169</td>
      <td><a href="/downloads/sequences/RF03169.fa.gz" onclick="downloadFile('/downloads/sequences/RF03169.fa.gz')">Download</a></td>
    </tr> 
                            
     <tr>
      <td><a href='https://riboswitch.ribocentre.org/docs/c-di-GMP' target='_blank'>c-di-GMP</a></td>
      <td>RF03170</td>
      <td><a href="/downloads/sequences/RF03170.fa.gz" onclick="downloadFile('/downloads/sequences/RF03170.fa.gz')">Download</a></td>
    </tr> 
                            
</table>
    
   
  </div>
</div>
        
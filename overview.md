<div class="keyboard">
   <link rel="stylesheet" href="table_hide.css"/>
   <link rel="stylesheet"
         type="text/css"
         href="https://cdn.datatables.net/1.11.4/css/jquery.dataTables.css"/>
   <script type="text/javascript"
           charset="utf8"
           src="https://code.jquery.com/jquery-3.5.1.js"> </script>
   <script charset="utf8"
           type="text/javascript"
           src="https://cdn.datatables.net/1.11.4/js/jquery.dataTables.min.js"> </script>
   <script type="text/javascript">
            $(document).ready(function () {
                $('#table_id').DataTable({
                    "scrollX": "1800px",
                    "scrollCollapse": true,
                    "pagingType": "full_numbers",
                    "ordering": true,
                    "info": true,
                });
            });</script>
   <h1>Code chart</h1>
   <p>
            The Aletheia document image analysis system, Transkribus and LAREX offer the possibility to install additional virtual keyboards or to customize them.
            This repository offers about 80 keyboards based on the data snapshot of
            <a href="https://mufi.info/" target="_blank">MUFI: The Medieval Unicode Font Initiative</a>
      <a href="https://mufi.info/m.php?p=mufiexport" target="_blank">(MUFI data as json)</a>.
        </p>
   <p>Would you like to use the keyboard in Aletheia or in Transkribus or in LAREX. Then download and
            install the necessary virtual keyboard. You can find more information about using
            Virtual Keyboards in  
            <a href="https://www.primaresearch.org/www/assets/tools/Aletheia%20User%20Guide.pdf#page=91"
         target="_blank">Aletheia User Guide</a> or
            <a href="https://readcoop.eu/de/glossary/virtual-keyboard/"
         target="_blank">Transkribus Glossar,</a> or
            <a href="https://github.com/OCR4all/LAREX/issues/317" target="_blank">LAREX</a> or
            <a href="https://github.com/qurator-spk/neat" target="_blank">QURATOR-neat</a>.
            
        </p>
   <h3>Links:</h3>
   <ul>
      <li>MUFI: The Medieval Unicode Font Initiative <a href="https://mufi.info/">https://mufi.info/</a>
      </li>
      <li>Aletheia <a href="https://www.primaresearch.org/tools/Aletheia">https://www.primaresearch.org/tools/Aletheia</a>
      </li>
      <li>Transkribus <a href="https://readcoop.eu/transkribus/">https://readcoop.eu/transkribus/</a>
      </li>
      <li>LAREX <a href="https://github.com/OCR4all/LAREX">https://github.com/OCR4all/LAREX</a>
      </li>
      <li>QURATOR-neat <a href="https://github.com/qurator-spk/neat" target="_blank">https://github.com/qurator-spk/neat</a>
      </li>
   </ul>
   <h2>Recommendation</h2>
   <p> We recommended to use the Junicode font. This font supports UNICODE
            and also MUFI encoding. Before you start working with the virtual keyboards in Altheia
            you should have the Junicode font installed on your computer.<br/>
      <ul>
         <h3>Links:</h3>
         <li>
            <a href="https://junicode.sourceforge.io/" target="_blank">Junicode</a>
         </li>
         <li>
            <a href="https://psb1558.github.io/Junicode-font/" target="_blank">Junicode 2</a>
         </li>
      </ul>
   </p>
   <h2>Download and Installation</h2>
   <details>
      <summary>For Aletheia</summary>
      <p>
         <strong>Download:</strong> You can either choose a specific
            virtual keyboard from the table and/or download the whole keyboard archive. A virtual
            keyboard is an xml file that you need to import into Alteheia. The keyboard archive is a
            zip file. Before you want to install the keyboards you have to unpack the zip
            file.</p>
      <div class="container">
         <div class="column">
            <h3>Installation:<br/>
            </h3>
            <video width="520" height="440" controls="true">
               <source src="doc/keyboard.mp4" type="video/mp4"/> Your browser does not support
                    the video tag. </video>
         </div>
         <div class="column">
            <h3>Links:</h3>
            <a href="https://github.com/tboenig/keyboardGT/releases/download/v99/keyboardGT-v99.zip">
                    keyboard archiv as zip</a>
         </div>
      </div>
   </details>
   <details>
      <summary>For Transcribus</summary>
      <div class="container">
         <div class="column">
            <p>
                Download the <strong>virtualKeyboards.xml</strong> file and copy it to the program directory of your Transkribus installation. 
                You should archive the existing file. The new virtualKeyboards file replaces this file.
            </p>
         </div>
         <div class="column">
            <h3>Links:</h3>
            <a href="keyboards/transkribus/virtualKeyboards.xml" target="_blank">
                    virtualKeyboards.xml
                </a>
         </div>
      </div>
   </details>
   <details>
      <summary>For LAREX</summary>
      <p>
                Download the <strong>keyboard text files</strong> and copy the files to the appropriate directory.
            </p>
   </details>
   <details>
      <summary>For QURATOR-neat</summary>
      <p>
                Download the <strong>keyboard text files</strong> and copy the files to the appropriate directory.
            </p>
   </details>
   <hr/>
   <table id="table_id">
      <thead>
         <tr>
            <th style="position: sticky !important; left: 0 !important;">Code chart</th>
            <th>
               <span class="big">⌨</span> Virtual Keyboard Layouts<br/>for Aletheia</th>
            <th>
               <span class="big">⌨</span> Virtual Keyboard Layouts<br/>for Transkribus</th>
            <th>
               <span class="big">⌨</span> Virtual Keyboard Layouts<br/>for LAREX</th>
            <th>
               <span class="big">⌨</span> Virtual Keyboard Layouts<br/>for QURATOR-neat</th>
            <th>
               <span class="big">💁</span> Browse by code chart<br/>(Link to MUFI)</th>
         </tr>
      </thead>
      <tbody>
         <tr>
            <th>Alphabetic Presentation Forms </th>
            <td>
               <a href="keyboards/aletheia/AlphPresForm.xml" target="_blank">AlphPresForm</a>
            </td>
            <td>
               <a href="keyboards/transkribus/AlphPresForm/virtualKeyboards.xml"
                  target="_blank">AlphPresForm</a>
            </td>
            <td>
               <a href="keyboards/LAREX/AlphPresForm.txt" target="_blank">AlphPresForm</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/AlphPresForm.txt" target="_blank">AlphPresForm</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/AlphPresForm.json" target="_blank">AlphPresForm</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=40"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Ancient Symbols </th>
            <td>
               <a href="keyboards/aletheia/AncSymb.xml" target="_blank">AncSymb</a>
            </td>
            <td>
               <a href="keyboards/transkribus/AncSymb/virtualKeyboards.xml"
                  target="_blank">AncSymb</a>
            </td>
            <td>
               <a href="keyboards/LAREX/AncSymb.txt" target="_blank">AncSymb</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/AncSymb.txt" target="_blank">AncSymb</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/AncSymb.json" target="_blank">AncSymb</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=75"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Arrows </th>
            <td>
               <a href="keyboards/aletheia/Arrows.xml" target="_blank">Arrows</a>
            </td>
            <td>
               <a href="keyboards/transkribus/Arrows/virtualKeyboards.xml"
                  target="_blank">Arrows</a>
            </td>
            <td>
               <a href="keyboards/LAREX/Arrows.txt" target="_blank">Arrows</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/Arrows.txt" target="_blank">Arrows</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/Arrows.json" target="_blank">Arrows</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=76"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Basic Latin </th>
            <td>
               <a href="keyboards/aletheia/BasLat.xml" target="_blank">BasLat</a>
            </td>
            <td>
               <a href="keyboards/transkribus/BasLat/virtualKeyboards.xml"
                  target="_blank">BasLat</a>
            </td>
            <td>
               <a href="keyboards/LAREX/BasLat.txt" target="_blank">BasLat</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/BasLat.txt" target="_blank">BasLat</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/BasLat.json" target="_blank">BasLat</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=1"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Combining Diacritical Marks </th>
            <td>
               <a href="keyboards/aletheia/CombDiaMk.xml" target="_blank">CombDiaMk</a>
            </td>
            <td>
               <a href="keyboards/transkribus/CombDiaMk/virtualKeyboards.xml"
                  target="_blank">CombDiaMk</a>
            </td>
            <td>
               <a href="keyboards/LAREX/CombDiaMk.txt" target="_blank">CombDiaMk</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/CombDiaMk.txt" target="_blank">CombDiaMk</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/CombDiaMk.json" target="_blank">CombDiaMk</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=58"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Combining Diacritical Marks Supplement </th>
            <td>
               <a href="keyboards/aletheia/CombDiaMkS.xml" target="_blank">CombDiaMkS</a>
            </td>
            <td>
               <a href="keyboards/transkribus/CombDiaMkS/virtualKeyboards.xml"
                  target="_blank">CombDiaMkS</a>
            </td>
            <td>
               <a href="keyboards/LAREX/CombDiaMkS.txt" target="_blank">CombDiaMkS</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/CombDiaMkS.txt" target="_blank">CombDiaMkS</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/CombDiaMkS.json" target="_blank">CombDiaMkS</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=59"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Currency Symbols </th>
            <td>
               <a href="keyboards/aletheia/CurrSymb.xml" target="_blank">CurrSymb</a>
            </td>
            <td>
               <a href="keyboards/transkribus/CurrSymb/virtualKeyboards.xml"
                  target="_blank">CurrSymb</a>
            </td>
            <td>
               <a href="keyboards/LAREX/CurrSymb.txt" target="_blank">CurrSymb</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/CurrSymb.txt" target="_blank">CurrSymb</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/CurrSymb.json" target="_blank">CurrSymb</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=73"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Dingbats </th>
            <td>
               <a href="keyboards/aletheia/Dingbats.xml" target="_blank">Dingbats</a>
            </td>
            <td>
               <a href="keyboards/transkribus/Dingbats/virtualKeyboards.xml"
                  target="_blank">Dingbats</a>
            </td>
            <td>
               <a href="keyboards/LAREX/Dingbats.txt" target="_blank">Dingbats</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/Dingbats.txt" target="_blank">Dingbats</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/Dingbats.json" target="_blank">Dingbats</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=72"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>General Punctuation </th>
            <td>
               <a href="keyboards/aletheia/GenPunct.xml" target="_blank">GenPunct</a>
            </td>
            <td>
               <a href="keyboards/transkribus/GenPunct/virtualKeyboards.xml"
                  target="_blank">GenPunct</a>
            </td>
            <td>
               <a href="keyboards/LAREX/GenPunct.txt" target="_blank">GenPunct</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/GenPunct.txt" target="_blank">GenPunct</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/GenPunct.json" target="_blank">GenPunct</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=62"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Geometric Shapes </th>
            <td>
               <a href="keyboards/aletheia/GeomShap.xml" target="_blank">GeomShap</a>
            </td>
            <td>
               <a href="keyboards/transkribus/GeomShap/virtualKeyboards.xml"
                  target="_blank">GeomShap</a>
            </td>
            <td>
               <a href="keyboards/LAREX/GeomShap.txt" target="_blank">GeomShap</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/GeomShap.txt" target="_blank">GeomShap</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/GeomShap.json" target="_blank">GeomShap</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=77"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Georgian </th>
            <td>
               <a href="keyboards/aletheia/Georgian.xml" target="_blank">Georgian</a>
            </td>
            <td>
               <a href="keyboards/transkribus/Georgian/virtualKeyboards.xml"
                  target="_blank">Georgian</a>
            </td>
            <td>
               <a href="keyboards/LAREX/Georgian.txt" target="_blank">Georgian</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/Georgian.txt" target="_blank">Georgian</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/Georgian.json" target="_blank">Georgian</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=66"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Greek and Coptic </th>
            <td>
               <a href="keyboards/aletheia/GkCo.xml" target="_blank">GkCo</a>
            </td>
            <td>
               <a href="keyboards/transkribus/GkCo/virtualKeyboards.xml" target="_blank">GkCo</a>
            </td>
            <td>
               <a href="keyboards/LAREX/GkCo.txt" target="_blank">GkCo</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/GkCo.txt" target="_blank">GkCo</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/GkCo.json" target="_blank">GkCo</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=80"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>IPA Extensions </th>
            <td>
               <a href="keyboards/aletheia/IPAExt.xml" target="_blank">IPAExt</a>
            </td>
            <td>
               <a href="keyboards/transkribus/IPAExt/virtualKeyboards.xml"
                  target="_blank">IPAExt</a>
            </td>
            <td>
               <a href="keyboards/LAREX/IPAExt.txt" target="_blank">IPAExt</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/IPAExt.txt" target="_blank">IPAExt</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/IPAExt.json" target="_blank">IPAExt</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=28"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin-1 Supplement </th>
            <td>
               <a href="keyboards/aletheia/Lat1Suppl.xml" target="_blank">Lat1Suppl</a>
            </td>
            <td>
               <a href="keyboards/transkribus/Lat1Suppl/virtualKeyboards.xml"
                  target="_blank">Lat1Suppl</a>
            </td>
            <td>
               <a href="keyboards/LAREX/Lat1Suppl.txt" target="_blank">Lat1Suppl</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/Lat1Suppl.txt" target="_blank">Lat1Suppl</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/Lat1Suppl.json" target="_blank">Lat1Suppl</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=4"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended-A </th>
            <td>
               <a href="keyboards/aletheia/LatExtA.xml" target="_blank">LatExtA</a>
            </td>
            <td>
               <a href="keyboards/transkribus/LatExtA/virtualKeyboards.xml"
                  target="_blank">LatExtA</a>
            </td>
            <td>
               <a href="keyboards/LAREX/LatExtA.txt" target="_blank">LatExtA</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/LatExtA.txt" target="_blank">LatExtA</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/LatExtA.json" target="_blank">LatExtA</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=5"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended Additional </th>
            <td>
               <a href="keyboards/aletheia/LatExtAdd.xml" target="_blank">LatExtAdd</a>
            </td>
            <td>
               <a href="keyboards/transkribus/LatExtAdd/virtualKeyboards.xml"
                  target="_blank">LatExtAdd</a>
            </td>
            <td>
               <a href="keyboards/LAREX/LatExtAdd.txt" target="_blank">LatExtAdd</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/LatExtAdd.txt" target="_blank">LatExtAdd</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/LatExtAdd.json" target="_blank">LatExtAdd</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=7"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended-B </th>
            <td>
               <a href="keyboards/aletheia/LatExtB.xml" target="_blank">LatExtB</a>
            </td>
            <td>
               <a href="keyboards/transkribus/LatExtB/virtualKeyboards.xml"
                  target="_blank">LatExtB</a>
            </td>
            <td>
               <a href="keyboards/LAREX/LatExtB.txt" target="_blank">LatExtB</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/LatExtB.txt" target="_blank">LatExtB</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/LatExtB.json" target="_blank">LatExtB</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=8"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended-C </th>
            <td>
               <a href="keyboards/aletheia/LatExtC.xml" target="_blank">LatExtC</a>
            </td>
            <td>
               <a href="keyboards/transkribus/LatExtC/virtualKeyboards.xml"
                  target="_blank">LatExtC</a>
            </td>
            <td>
               <a href="keyboards/LAREX/LatExtC.txt" target="_blank">LatExtC</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/LatExtC.txt" target="_blank">LatExtC</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/LatExtC.json" target="_blank">LatExtC</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=43"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended-D </th>
            <td>
               <a href="keyboards/aletheia/LatExtD.xml" target="_blank">LatExtD</a>
            </td>
            <td>
               <a href="keyboards/transkribus/LatExtD/virtualKeyboards.xml"
                  target="_blank">LatExtD</a>
            </td>
            <td>
               <a href="keyboards/LAREX/LatExtD.txt" target="_blank">LatExtD</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/LatExtD.txt" target="_blank">LatExtD</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/LatExtD.json" target="_blank">LatExtD</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=18"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended-E </th>
            <td>
               <a href="keyboards/aletheia/LatExtE.xml" target="_blank">LatExtE</a>
            </td>
            <td>
               <a href="keyboards/transkribus/LatExtE/virtualKeyboards.xml"
                  target="_blank">LatExtE</a>
            </td>
            <td>
               <a href="keyboards/LAREX/LatExtE.txt" target="_blank">LatExtE</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/LatExtE.txt" target="_blank">LatExtE</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/LatExtE.json" target="_blank">LatExtE</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=82"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Letterlike Symbols </th>
            <td>
               <a href="keyboards/aletheia/LettSymb.xml" target="_blank">LettSymb</a>
            </td>
            <td>
               <a href="keyboards/transkribus/LettSymb/virtualKeyboards.xml"
                  target="_blank">LettSymb</a>
            </td>
            <td>
               <a href="keyboards/LAREX/LettSymb.txt" target="_blank">LettSymb</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/LettSymb.txt" target="_blank">LettSymb</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/LettSymb.json" target="_blank">LettSymb</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=41"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Mathematical Operators </th>
            <td>
               <a href="keyboards/aletheia/MathOp.xml" target="_blank">MathOp</a>
            </td>
            <td>
               <a href="keyboards/transkribus/MathOp/virtualKeyboards.xml"
                  target="_blank">MathOp</a>
            </td>
            <td>
               <a href="keyboards/LAREX/MathOp.txt" target="_blank">MathOp</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/MathOp.txt" target="_blank">MathOp</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/MathOp.json" target="_blank">MathOp</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=64"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Miscellaneous Mathematical Symbols-A </th>
            <td>
               <a href="keyboards/aletheia/MiMaSymbA.xml" target="_blank">MiMaSymbA</a>
            </td>
            <td>
               <a href="keyboards/transkribus/MiMaSymbA/virtualKeyboards.xml"
                  target="_blank">MiMaSymbA</a>
            </td>
            <td>
               <a href="keyboards/LAREX/MiMaSymbA.txt" target="_blank">MiMaSymbA</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/MiMaSymbA.txt" target="_blank">MiMaSymbA</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/MiMaSymbA.json" target="_blank">MiMaSymbA</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=70"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Miscellaneous Technical </th>
            <td>
               <a href="keyboards/aletheia/MiscTech.xml" target="_blank">MiscTech</a>
            </td>
            <td>
               <a href="keyboards/transkribus/MiscTech/virtualKeyboards.xml"
                  target="_blank">MiscTech</a>
            </td>
            <td>
               <a href="keyboards/LAREX/MiscTech.txt" target="_blank">MiscTech</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/MiscTech.txt" target="_blank">MiscTech</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/MiscTech.json" target="_blank">MiscTech</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=78"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Number Forms </th>
            <td>
               <a href="keyboards/aletheia/NumbFo.xml" target="_blank">NumbFo</a>
            </td>
            <td>
               <a href="keyboards/transkribus/NumbFo/virtualKeyboards.xml"
                  target="_blank">NumbFo</a>
            </td>
            <td>
               <a href="keyboards/LAREX/NumbFo.txt" target="_blank">NumbFo</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/NumbFo.txt" target="_blank">NumbFo</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/NumbFo.json" target="_blank">NumbFo</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=30"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 1: Base characters </th>
            <td>
               <a href="keyboards/aletheia/PUA-1.xml" target="_blank">PUA-1</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-1/virtualKeyboards.xml" target="_blank">PUA-1</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-1.txt" target="_blank">PUA-1</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-1.txt" target="_blank">PUA-1</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-1.json" target="_blank">PUA-1</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=19"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 10: Metrical symbols </th>
            <td>
               <a href="keyboards/aletheia/PUA-10.xml" target="_blank">PUA-10</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-10/virtualKeyboards.xml"
                  target="_blank">PUA-10</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-10.txt" target="_blank">PUA-10</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-10.txt" target="_blank">PUA-10</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-10.json" target="_blank">PUA-10</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=79"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 11: Additional number forms </th>
            <td>
               <a href="keyboards/aletheia/PUA-11.xml" target="_blank">PUA-11</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-11/virtualKeyboards.xml"
                  target="_blank">PUA-11</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-11.txt" target="_blank">PUA-11</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-11.txt" target="_blank">PUA-11</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-11.json" target="_blank">PUA-11</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=57"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 12: Weight, currency and measurement </th>
            <td>
               <a href="keyboards/aletheia/PUA-12.xml" target="_blank">PUA-12</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-12/virtualKeyboards.xml"
                  target="_blank">PUA-12</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-12.txt" target="_blank">PUA-12</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-12.txt" target="_blank">PUA-12</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-12.json" target="_blank">PUA-12</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=74"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 13: Modified base-line characters </th>
            <td>
               <a href="keyboards/aletheia/PUA-13.xml" target="_blank">PUA-13</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-13/virtualKeyboards.xml"
                  target="_blank">PUA-13</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-13.txt" target="_blank">PUA-13</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-13.txt" target="_blank">PUA-13</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-13.json" target="_blank">PUA-13</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=47"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 14: Other base-line characters </th>
            <td>
               <a href="keyboards/aletheia/PUA-14.xml" target="_blank">PUA-14</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-14/virtualKeyboards.xml"
                  target="_blank">PUA-14</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-14.txt" target="_blank">PUA-14</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-14.txt" target="_blank">PUA-14</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-14.json" target="_blank">PUA-14</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=84"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 15: Characters with macron or overline </th>
            <td>
               <a href="keyboards/aletheia/PUA-15.xml" target="_blank">PUA-15</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-15/virtualKeyboards.xml"
                  target="_blank">PUA-15</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-15.txt" target="_blank">PUA-15</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-15.txt" target="_blank">PUA-15</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-15.json" target="_blank">PUA-15</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=29"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 16: Characters with acute accent </th>
            <td>
               <a href="keyboards/aletheia/PUA-16.xml" target="_blank">PUA-16</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-16/virtualKeyboards.xml"
                  target="_blank">PUA-16</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-16.txt" target="_blank">PUA-16</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-16.txt" target="_blank">PUA-16</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-16.json" target="_blank">PUA-16</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=22"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 17: Characters with double acute accent </th>
            <td>
               <a href="keyboards/aletheia/PUA-17.xml" target="_blank">PUA-17</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-17/virtualKeyboards.xml"
                  target="_blank">PUA-17</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-17.txt" target="_blank">PUA-17</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-17.txt" target="_blank">PUA-17</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-17.json" target="_blank">PUA-17</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=12"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 18: Characters with dot above </th>
            <td>
               <a href="keyboards/aletheia/PUA-18.xml" target="_blank">PUA-18</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-18/virtualKeyboards.xml"
                  target="_blank">PUA-18</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-18.txt" target="_blank">PUA-18</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-18.txt" target="_blank">PUA-18</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-18.json" target="_blank">PUA-18</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=21"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 19: Characters with dot below </th>
            <td>
               <a href="keyboards/aletheia/PUA-19.xml" target="_blank">PUA-19</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-19/virtualKeyboards.xml"
                  target="_blank">PUA-19</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-19.txt" target="_blank">PUA-19</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-19.txt" target="_blank">PUA-19</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-19.json" target="_blank">PUA-19</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=20"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 2: Small capitals </th>
            <td>
               <a href="keyboards/aletheia/PUA-2.xml" target="_blank">PUA-2</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-2/virtualKeyboards.xml" target="_blank">PUA-2</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-2.txt" target="_blank">PUA-2</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-2.txt" target="_blank">PUA-2</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-2.json" target="_blank">PUA-2</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=51"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 20: Characters with diaeresis </th>
            <td>
               <a href="keyboards/aletheia/PUA-20.xml" target="_blank">PUA-20</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-20/virtualKeyboards.xml"
                  target="_blank">PUA-20</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-20.txt" target="_blank">PUA-20</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-20.txt" target="_blank">PUA-20</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-20.json" target="_blank">PUA-20</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=9"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 21: Characters with curl above (reversed ogonek) </th>
            <td>
               <a href="keyboards/aletheia/PUA-21.xml" target="_blank">PUA-21</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-21/virtualKeyboards.xml"
                  target="_blank">PUA-21</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-21.txt" target="_blank">PUA-21</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-21.txt" target="_blank">PUA-21</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-21.json" target="_blank">PUA-21</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=6"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 22: Characters with ogonek </th>
            <td>
               <a href="keyboards/aletheia/PUA-22.xml" target="_blank">PUA-22</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-22/virtualKeyboards.xml"
                  target="_blank">PUA-22</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-22.txt" target="_blank">PUA-22</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-22.txt" target="_blank">PUA-22</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-22.json" target="_blank">PUA-22</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=24"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 23: Characters with breve </th>
            <td>
               <a href="keyboards/aletheia/PUA-23.xml" target="_blank">PUA-23</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-23/virtualKeyboards.xml"
                  target="_blank">PUA-23</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-23.txt" target="_blank">PUA-23</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-23.txt" target="_blank">PUA-23</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-23.json" target="_blank">PUA-23</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=26"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 24: Characters with breve below </th>
            <td>
               <a href="keyboards/aletheia/PUA-24.xml" target="_blank">PUA-24</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-24/virtualKeyboards.xml"
                  target="_blank">PUA-24</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-24.txt" target="_blank">PUA-24</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-24.txt" target="_blank">PUA-24</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-24.json" target="_blank">PUA-24</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=44"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 25: Characters with circumflex </th>
            <td>
               <a href="keyboards/aletheia/PUA-25.xml" target="_blank">PUA-25</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-25/virtualKeyboards.xml"
                  target="_blank">PUA-25</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-25.txt" target="_blank">PUA-25</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-25.txt" target="_blank">PUA-25</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-25.json" target="_blank">PUA-25</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=39"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 26: Characters with ring above </th>
            <td>
               <a href="keyboards/aletheia/PUA-26.xml" target="_blank">PUA-26</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-26/virtualKeyboards.xml"
                  target="_blank">PUA-26</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-26.txt" target="_blank">PUA-26</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-26.txt" target="_blank">PUA-26</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-26.json" target="_blank">PUA-26</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=25"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 27: Characters with ring below </th>
            <td>
               <a href="keyboards/aletheia/PUA-27.xml" target="_blank">PUA-27</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-27/virtualKeyboards.xml"
                  target="_blank">PUA-27</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-27.txt" target="_blank">PUA-27</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-27.txt" target="_blank">PUA-27</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-27.json" target="_blank">PUA-27</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=46"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 28: Characters with tilde </th>
            <td>
               <a href="keyboards/aletheia/PUA-28.xml" target="_blank">PUA-28</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-28/virtualKeyboards.xml"
                  target="_blank">PUA-28</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-28.txt" target="_blank">PUA-28</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-28.txt" target="_blank">PUA-28</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-28.json" target="_blank">PUA-28</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=52"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 29: Characters with curly bar above </th>
            <td>
               <a href="keyboards/aletheia/PUA-29.xml" target="_blank">PUA-29</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-29/virtualKeyboards.xml"
                  target="_blank">PUA-29</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-29.txt" target="_blank">PUA-29</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-29.txt" target="_blank">PUA-29</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-29.json" target="_blank">PUA-29</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=55"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 3: Enlarged minuscules </th>
            <td>
               <a href="keyboards/aletheia/PUA-3.xml" target="_blank">PUA-3</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-3/virtualKeyboards.xml" target="_blank">PUA-3</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-3.txt" target="_blank">PUA-3</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-3.txt" target="_blank">PUA-3</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-3.json" target="_blank">PUA-3</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=2"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 30: Characters with vertical bar above </th>
            <td>
               <a href="keyboards/aletheia/PUA-30.xml" target="_blank">PUA-30</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-30/virtualKeyboards.xml"
                  target="_blank">PUA-30</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-30.txt" target="_blank">PUA-30</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-30.txt" target="_blank">PUA-30</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-30.json" target="_blank">PUA-30</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=54"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 31: Characters with superscript letters </th>
            <td>
               <a href="keyboards/aletheia/PUA-31.xml" target="_blank">PUA-31</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-31/virtualKeyboards.xml"
                  target="_blank">PUA-31</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-31.txt" target="_blank">PUA-31</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-31.txt" target="_blank">PUA-31</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-31.json" target="_blank">PUA-31</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=27"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 32: Characters with acute accent and dot above </th>
            <td>
               <a href="keyboards/aletheia/PUA-32.xml" target="_blank">PUA-32</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-32/virtualKeyboards.xml"
                  target="_blank">PUA-32</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-32.txt" target="_blank">PUA-32</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-32.txt" target="_blank">PUA-32</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-32.json" target="_blank">PUA-32</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=13"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 33: Characters with acute accent and dot below </th>
            <td>
               <a href="keyboards/aletheia/PUA-33.xml" target="_blank">PUA-33</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-33/virtualKeyboards.xml"
                  target="_blank">PUA-33</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-33.txt" target="_blank">PUA-33</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-33.txt" target="_blank">PUA-33</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-33.json" target="_blank">PUA-33</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=35"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 34: Characters with acute accent and diaeresis </th>
            <td>
               <a href="keyboards/aletheia/PUA-34.xml" target="_blank">PUA-34</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-34/virtualKeyboards.xml"
                  target="_blank">PUA-34</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-34.txt" target="_blank">PUA-34</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-34.txt" target="_blank">PUA-34</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-34.json" target="_blank">PUA-34</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=50"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 35: Characters with acute accent and curl above (reversed ogonek) </th>
            <td>
               <a href="keyboards/aletheia/PUA-35.xml" target="_blank">PUA-35</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-35/virtualKeyboards.xml"
                  target="_blank">PUA-35</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-35.txt" target="_blank">PUA-35</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-35.txt" target="_blank">PUA-35</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-35.json" target="_blank">PUA-35</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=48"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 36: Characters with acute accent and ogonek </th>
            <td>
               <a href="keyboards/aletheia/PUA-36.xml" target="_blank">PUA-36</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-36/virtualKeyboards.xml"
                  target="_blank">PUA-36</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-36.txt" target="_blank">PUA-36</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-36.txt" target="_blank">PUA-36</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-36.json" target="_blank">PUA-36</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=11"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 37: Characters with double acute accent and ogonek </th>
            <td>
               <a href="keyboards/aletheia/PUA-37.xml" target="_blank">PUA-37</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-37/virtualKeyboards.xml"
                  target="_blank">PUA-37</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-37.txt" target="_blank">PUA-37</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-37.txt" target="_blank">PUA-37</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-37.json" target="_blank">PUA-37</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=37"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 38: Characters with dot above and ogonek </th>
            <td>
               <a href="keyboards/aletheia/PUA-38.xml" target="_blank">PUA-38</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-38/virtualKeyboards.xml"
                  target="_blank">PUA-38</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-38.txt" target="_blank">PUA-38</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-38.txt" target="_blank">PUA-38</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-38.json" target="_blank">PUA-38</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=32"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 39: Characters with dot below and ogonek </th>
            <td>
               <a href="keyboards/aletheia/PUA-39.xml" target="_blank">PUA-39</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-39/virtualKeyboards.xml"
                  target="_blank">PUA-39</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-39.txt" target="_blank">PUA-39</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-39.txt" target="_blank">PUA-39</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-39.json" target="_blank">PUA-39</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=33"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 4: Base-line abbreviation characters </th>
            <td>
               <a href="keyboards/aletheia/PUA-4.xml" target="_blank">PUA-4</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-4/virtualKeyboards.xml" target="_blank">PUA-4</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-4.txt" target="_blank">PUA-4</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-4.txt" target="_blank">PUA-4</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-4.json" target="_blank">PUA-4</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=63"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 40: Characters with diaeresis and macron </th>
            <td>
               <a href="keyboards/aletheia/PUA-40.xml" target="_blank">PUA-40</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-40/virtualKeyboards.xml"
                  target="_blank">PUA-40</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-40.txt" target="_blank">PUA-40</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-40.txt" target="_blank">PUA-40</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-40.json" target="_blank">PUA-40</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=34"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 41: Characters with diaeresis and circumflex </th>
            <td>
               <a href="keyboards/aletheia/PUA-41.xml" target="_blank">PUA-41</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-41/virtualKeyboards.xml"
                  target="_blank">PUA-41</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-41.txt" target="_blank">PUA-41</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-41.txt" target="_blank">PUA-41</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-41.json" target="_blank">PUA-41</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=14"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 42: Characters with diaeresis and dot below </th>
            <td>
               <a href="keyboards/aletheia/PUA-42.xml" target="_blank">PUA-42</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-42/virtualKeyboards.xml"
                  target="_blank">PUA-42</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-42.txt" target="_blank">PUA-42</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-42.txt" target="_blank">PUA-42</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-42.json" target="_blank">PUA-42</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=10"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 43: Characters with ogonek and curl above (reversed ogonek) </th>
            <td>
               <a href="keyboards/aletheia/PUA-43.xml" target="_blank">PUA-43</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-43/virtualKeyboards.xml"
                  target="_blank">PUA-43</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-43.txt" target="_blank">PUA-43</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-43.txt" target="_blank">PUA-43</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-43.json" target="_blank">PUA-43</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=31"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 44: Characters with ogonek and circumflex </th>
            <td>
               <a href="keyboards/aletheia/PUA-44.xml" target="_blank">PUA-44</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-44/virtualKeyboards.xml"
                  target="_blank">PUA-44</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-44.txt" target="_blank">PUA-44</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-44.txt" target="_blank">PUA-44</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-44.json" target="_blank">PUA-44</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=38"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 45: Characters with ring above and circumflex </th>
            <td>
               <a href="keyboards/aletheia/PUA-45.xml" target="_blank">PUA-45</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-45/virtualKeyboards.xml"
                  target="_blank">PUA-45</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-45.txt" target="_blank">PUA-45</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-45.txt" target="_blank">PUA-45</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-45.json" target="_blank">PUA-45</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=15"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 46: Characters with macron and breve </th>
            <td>
               <a href="keyboards/aletheia/PUA-46.xml" target="_blank">PUA-46</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-46/virtualKeyboards.xml"
                  target="_blank">PUA-46</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-46.txt" target="_blank">PUA-46</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-46.txt" target="_blank">PUA-46</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-46.json" target="_blank">PUA-46</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=16"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 47: Characters with macron and acute accent </th>
            <td>
               <a href="keyboards/aletheia/PUA-47.xml" target="_blank">PUA-47</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-47/virtualKeyboards.xml"
                  target="_blank">PUA-47</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-47.txt" target="_blank">PUA-47</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-47.txt" target="_blank">PUA-47</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-47.json" target="_blank">PUA-47</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=17"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 48: Characters with ogonek, dot above and acute accent </th>
            <td>
               <a href="keyboards/aletheia/PUA-48.xml" target="_blank">PUA-48</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-48/virtualKeyboards.xml"
                  target="_blank">PUA-48</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-48.txt" target="_blank">PUA-48</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-48.txt" target="_blank">PUA-48</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-48.json" target="_blank">PUA-48</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=36"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 5: Modified base-line abbreviation characters </th>
            <td>
               <a href="keyboards/aletheia/PUA-5.xml" target="_blank">PUA-5</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-5/virtualKeyboards.xml" target="_blank">PUA-5</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-5.txt" target="_blank">PUA-5</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-5.txt" target="_blank">PUA-5</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-5.json" target="_blank">PUA-5</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=42"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 51: Variant letter forms </th>
            <td>
               <a href="keyboards/aletheia/PUA-51.xml" target="_blank">PUA-51</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-51/virtualKeyboards.xml"
                  target="_blank">PUA-51</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-51.txt" target="_blank">PUA-51</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-51.txt" target="_blank">PUA-51</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-51.json" target="_blank">PUA-51</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=83"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 6: Combining Marks </th>
            <td>
               <a href="keyboards/aletheia/PUA-6.xml" target="_blank">PUA-6</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-6/virtualKeyboards.xml" target="_blank">PUA-6</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-6.txt" target="_blank">PUA-6</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-6.txt" target="_blank">PUA-6</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-6.json" target="_blank">PUA-6</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=61"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 7: Combining superscript characters </th>
            <td>
               <a href="keyboards/aletheia/PUA-7.xml" target="_blank">PUA-7</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-7/virtualKeyboards.xml" target="_blank">PUA-7</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-7.txt" target="_blank">PUA-7</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-7.txt" target="_blank">PUA-7</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-7.json" target="_blank">PUA-7</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=60"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 8: Punctuation marks </th>
            <td>
               <a href="keyboards/aletheia/PUA-8.xml" target="_blank">PUA-8</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-8/virtualKeyboards.xml" target="_blank">PUA-8</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-8.txt" target="_blank">PUA-8</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-8.txt" target="_blank">PUA-8</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-8.json" target="_blank">PUA-8</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=71"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 9: Critical and epigraphical signs </th>
            <td>
               <a href="keyboards/aletheia/PUA-9.xml" target="_blank">PUA-9</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PUA-9/virtualKeyboards.xml" target="_blank">PUA-9</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PUA-9.txt" target="_blank">PUA-9</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PUA-9.txt" target="_blank">PUA-9</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PUA-9.json" target="_blank">PUA-9</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=67"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Phonetic Extensions </th>
            <td>
               <a href="keyboards/aletheia/PhonExt.xml" target="_blank">PhonExt</a>
            </td>
            <td>
               <a href="keyboards/transkribus/PhonExt/virtualKeyboards.xml"
                  target="_blank">PhonExt</a>
            </td>
            <td>
               <a href="keyboards/LAREX/PhonExt.txt" target="_blank">PhonExt</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/PhonExt.txt" target="_blank">PhonExt</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/PhonExt.json" target="_blank">PhonExt</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=3"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Runic </th>
            <td>
               <a href="keyboards/aletheia/Run.xml" target="_blank">Run</a>
            </td>
            <td>
               <a href="keyboards/transkribus/Run/virtualKeyboards.xml" target="_blank">Run</a>
            </td>
            <td>
               <a href="keyboards/LAREX/Run.txt" target="_blank">Run</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/Run.txt" target="_blank">Run</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/Run.json" target="_blank">Run</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=65"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Spacing Modifier Letters </th>
            <td>
               <a href="keyboards/aletheia/SpModLet.xml" target="_blank">SpModLet</a>
            </td>
            <td>
               <a href="keyboards/transkribus/SpModLet/virtualKeyboards.xml"
                  target="_blank">SpModLet</a>
            </td>
            <td>
               <a href="keyboards/LAREX/SpModLet.txt" target="_blank">SpModLet</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/SpModLet.txt" target="_blank">SpModLet</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/SpModLet.json" target="_blank">SpModLet</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=56"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Superscripts and Subscripts </th>
            <td>
               <a href="keyboards/aletheia/SupSub.xml" target="_blank">SupSub</a>
            </td>
            <td>
               <a href="keyboards/transkribus/SupSub/virtualKeyboards.xml"
                  target="_blank">SupSub</a>
            </td>
            <td>
               <a href="keyboards/LAREX/SupSub.txt" target="_blank">SupSub</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/SupSub.txt" target="_blank">SupSub</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/SupSub.json" target="_blank">SupSub</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=81"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Supplemental Mathematical Operators </th>
            <td>
               <a href="keyboards/aletheia/SupplMathOp.xml" target="_blank">SupplMathOp</a>
            </td>
            <td>
               <a href="keyboards/transkribus/SupplMathOp/virtualKeyboards.xml"
                  target="_blank">SupplMathOp</a>
            </td>
            <td>
               <a href="keyboards/LAREX/SupplMathOp.txt" target="_blank">SupplMathOp</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/SupplMathOp.txt" target="_blank">SupplMathOp</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/SupplMathOp.json" target="_blank">SupplMathOp</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=68"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Supplemental Punctuation </th>
            <td>
               <a href="keyboards/aletheia/SupplPunct.xml" target="_blank">SupplPunct</a>
            </td>
            <td>
               <a href="keyboards/transkribus/SupplPunct/virtualKeyboards.xml"
                  target="_blank">SupplPunct</a>
            </td>
            <td>
               <a href="keyboards/LAREX/SupplPunct.txt" target="_blank">SupplPunct</a>
            </td>
            <td>
               <a href="keyboards/qurator-neat/SupplPunct.txt" target="_blank">SupplPunct</a>
            </td>
            <td>
               <a href="keyboards/escriptorium/SupplPunct.json" target="_blank">SupplPunct</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=69"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
      </tbody>
   </table>
</div>

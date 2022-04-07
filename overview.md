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
            The Aletheia document image analysis system and Transkribus offer the possibility to install additional virtual keyboards or to customize them.
            This repository offers about 80 keyboards based on the data snapshot of
            <a href="https://mufi.info/" target="_blank">MUFI: The Medieval Unicode Font Initiative</a>
      <a href="https://mufi.info/m.php?p=mufiexport" target="_blank">(MUFI data as json)</a>.
        </p>
   <p>Would you like to use the keyboard in Aletheia or in Transkribus. Then download and
            install the necessary virtual keyboard. You can find more information about using
            Virtual Keyboards in the 
               <a href="https://www.primaresearch.org/www/assets/tools/Aletheia%20User%20Guide.pdf#page=91"
         target="_blank">Aletheia User Guide</a> or
               <a href="https://readcoop.eu/de/glossary/virtual-keyboard/"
         target="_blank">Transkribus Glossar.</a>
   </p>
   <h3>Links:</h3>
   <ul>
      <li>MUFI: The Medieval Unicode Font Initiative <a href="https://mufi.info/">https://mufi.info/</a>
      </li>
      <li>Aletheia <a href="https://www.primaresearch.org/tools/Aletheia">https://www.primaresearch.org/tools/Aletheia</a>
      </li>
      <li>Transkribus <a href="https://readcoop.eu/transkribus/">https://readcoop.eu/transkribus/</a>
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
   <h3>For Aletheia</h3>
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
         <a href="https://github.com/tboenig/keyboardGT/releases/download/v84/keyboardGT-v84.zip">
                    keyboard archiv as zip</a>
      </div>
   </div>
   <h3>For Transcribus</h3>
   <div class="container">
      <div class="column">
         <p>
                Download the <strong>virtualKeyboards.xml</strong> file and copy it to the program directory of your Transkribus installation. 
                You should archive the existing file. The new virtualKeyboards file replaces this file.
            </p>
      </div>
      <div class="column">
         <h3>Links:</h3>
         <a href="keyboards/virtualKeyboards.xml" target="_blank">
                    virtualKeyboards.xml
                </a>
      </div>
   </div>
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
               <span class="big">💁</span> Browse by code chart<br/>(Link to MUFI)</th>
         </tr>
      </thead>
      <tbody>
         <tr>
            <th>Alphabetic Presentation Forms </th>
            <td>
               <a href="keyboards/AlphPresForm.xml" target="_blank">AlphPresForm</a>
            </td>
            <td>
               <a href="keyboards/AlphPresForm/virtualKeyboards.xml" target="_blank">AlphPresForm</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=40"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Ancient Symbols </th>
            <td>
               <a href="keyboards/AncSymb.xml" target="_blank">AncSymb</a>
            </td>
            <td>
               <a href="keyboards/AncSymb/virtualKeyboards.xml" target="_blank">AncSymb</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=75"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Arrows </th>
            <td>
               <a href="keyboards/Arrows.xml" target="_blank">Arrows</a>
            </td>
            <td>
               <a href="keyboards/Arrows/virtualKeyboards.xml" target="_blank">Arrows</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=76"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Basic Latin </th>
            <td>
               <a href="keyboards/BasLat.xml" target="_blank">BasLat</a>
            </td>
            <td>
               <a href="keyboards/BasLat/virtualKeyboards.xml" target="_blank">BasLat</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=1"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Combining Diacritical Marks </th>
            <td>
               <a href="keyboards/CombDiaMk.xml" target="_blank">CombDiaMk</a>
            </td>
            <td>
               <a href="keyboards/CombDiaMk/virtualKeyboards.xml" target="_blank">CombDiaMk</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=58"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Combining Diacritical Marks Supplement </th>
            <td>
               <a href="keyboards/CombDiaMkS.xml" target="_blank">CombDiaMkS</a>
            </td>
            <td>
               <a href="keyboards/CombDiaMkS/virtualKeyboards.xml" target="_blank">CombDiaMkS</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=59"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Currency Symbols </th>
            <td>
               <a href="keyboards/CurrSymb.xml" target="_blank">CurrSymb</a>
            </td>
            <td>
               <a href="keyboards/CurrSymb/virtualKeyboards.xml" target="_blank">CurrSymb</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=73"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Dingbats </th>
            <td>
               <a href="keyboards/Dingbats.xml" target="_blank">Dingbats</a>
            </td>
            <td>
               <a href="keyboards/Dingbats/virtualKeyboards.xml" target="_blank">Dingbats</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=72"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>General Punctuation </th>
            <td>
               <a href="keyboards/GenPunct.xml" target="_blank">GenPunct</a>
            </td>
            <td>
               <a href="keyboards/GenPunct/virtualKeyboards.xml" target="_blank">GenPunct</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=62"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Geometric Shapes </th>
            <td>
               <a href="keyboards/GeomShap.xml" target="_blank">GeomShap</a>
            </td>
            <td>
               <a href="keyboards/GeomShap/virtualKeyboards.xml" target="_blank">GeomShap</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=77"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Georgian </th>
            <td>
               <a href="keyboards/Georgian.xml" target="_blank">Georgian</a>
            </td>
            <td>
               <a href="keyboards/Georgian/virtualKeyboards.xml" target="_blank">Georgian</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=66"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Greek and Coptic </th>
            <td>
               <a href="keyboards/GkCo.xml" target="_blank">GkCo</a>
            </td>
            <td>
               <a href="keyboards/GkCo/virtualKeyboards.xml" target="_blank">GkCo</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=80"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>IPA Extensions </th>
            <td>
               <a href="keyboards/IPAExt.xml" target="_blank">IPAExt</a>
            </td>
            <td>
               <a href="keyboards/IPAExt/virtualKeyboards.xml" target="_blank">IPAExt</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=28"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin-1 Supplement </th>
            <td>
               <a href="keyboards/Lat1Suppl.xml" target="_blank">Lat1Suppl</a>
            </td>
            <td>
               <a href="keyboards/Lat1Suppl/virtualKeyboards.xml" target="_blank">Lat1Suppl</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=4"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended-A </th>
            <td>
               <a href="keyboards/LatExtA.xml" target="_blank">LatExtA</a>
            </td>
            <td>
               <a href="keyboards/LatExtA/virtualKeyboards.xml" target="_blank">LatExtA</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=5"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended Additional </th>
            <td>
               <a href="keyboards/LatExtAdd.xml" target="_blank">LatExtAdd</a>
            </td>
            <td>
               <a href="keyboards/LatExtAdd/virtualKeyboards.xml" target="_blank">LatExtAdd</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=7"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended-B </th>
            <td>
               <a href="keyboards/LatExtB.xml" target="_blank">LatExtB</a>
            </td>
            <td>
               <a href="keyboards/LatExtB/virtualKeyboards.xml" target="_blank">LatExtB</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=8"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended-C </th>
            <td>
               <a href="keyboards/LatExtC.xml" target="_blank">LatExtC</a>
            </td>
            <td>
               <a href="keyboards/LatExtC/virtualKeyboards.xml" target="_blank">LatExtC</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=43"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended-D </th>
            <td>
               <a href="keyboards/LatExtD.xml" target="_blank">LatExtD</a>
            </td>
            <td>
               <a href="keyboards/LatExtD/virtualKeyboards.xml" target="_blank">LatExtD</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=18"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Latin Extended-E </th>
            <td>
               <a href="keyboards/LatExtE.xml" target="_blank">LatExtE</a>
            </td>
            <td>
               <a href="keyboards/LatExtE/virtualKeyboards.xml" target="_blank">LatExtE</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=82"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Letterlike Symbols </th>
            <td>
               <a href="keyboards/LettSymb.xml" target="_blank">LettSymb</a>
            </td>
            <td>
               <a href="keyboards/LettSymb/virtualKeyboards.xml" target="_blank">LettSymb</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=41"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Mathematical Operators </th>
            <td>
               <a href="keyboards/MathOp.xml" target="_blank">MathOp</a>
            </td>
            <td>
               <a href="keyboards/MathOp/virtualKeyboards.xml" target="_blank">MathOp</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=64"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Miscellaneous Mathematical Symbols-A </th>
            <td>
               <a href="keyboards/MiMaSymbA.xml" target="_blank">MiMaSymbA</a>
            </td>
            <td>
               <a href="keyboards/MiMaSymbA/virtualKeyboards.xml" target="_blank">MiMaSymbA</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=70"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Miscellaneous Technical </th>
            <td>
               <a href="keyboards/MiscTech.xml" target="_blank">MiscTech</a>
            </td>
            <td>
               <a href="keyboards/MiscTech/virtualKeyboards.xml" target="_blank">MiscTech</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=78"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Number Forms </th>
            <td>
               <a href="keyboards/NumbFo.xml" target="_blank">NumbFo</a>
            </td>
            <td>
               <a href="keyboards/NumbFo/virtualKeyboards.xml" target="_blank">NumbFo</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=30"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 1: Base characters </th>
            <td>
               <a href="keyboards/PUA-1.xml" target="_blank">PUA-1</a>
            </td>
            <td>
               <a href="keyboards/PUA-1/virtualKeyboards.xml" target="_blank">PUA-1</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=19"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 10: Metrical symbols </th>
            <td>
               <a href="keyboards/PUA-10.xml" target="_blank">PUA-10</a>
            </td>
            <td>
               <a href="keyboards/PUA-10/virtualKeyboards.xml" target="_blank">PUA-10</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=79"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 11: Additional number forms </th>
            <td>
               <a href="keyboards/PUA-11.xml" target="_blank">PUA-11</a>
            </td>
            <td>
               <a href="keyboards/PUA-11/virtualKeyboards.xml" target="_blank">PUA-11</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=57"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 12: Weight, currency and measurement </th>
            <td>
               <a href="keyboards/PUA-12.xml" target="_blank">PUA-12</a>
            </td>
            <td>
               <a href="keyboards/PUA-12/virtualKeyboards.xml" target="_blank">PUA-12</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=74"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 13: Modified base-line characters </th>
            <td>
               <a href="keyboards/PUA-13.xml" target="_blank">PUA-13</a>
            </td>
            <td>
               <a href="keyboards/PUA-13/virtualKeyboards.xml" target="_blank">PUA-13</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=47"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 14: Other base-line characters </th>
            <td>
               <a href="keyboards/PUA-14.xml" target="_blank">PUA-14</a>
            </td>
            <td>
               <a href="keyboards/PUA-14/virtualKeyboards.xml" target="_blank">PUA-14</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=84"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 15: Characters with macron or overline </th>
            <td>
               <a href="keyboards/PUA-15.xml" target="_blank">PUA-15</a>
            </td>
            <td>
               <a href="keyboards/PUA-15/virtualKeyboards.xml" target="_blank">PUA-15</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=29"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 16: Characters with acute accent </th>
            <td>
               <a href="keyboards/PUA-16.xml" target="_blank">PUA-16</a>
            </td>
            <td>
               <a href="keyboards/PUA-16/virtualKeyboards.xml" target="_blank">PUA-16</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=22"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 17: Characters with double acute accent </th>
            <td>
               <a href="keyboards/PUA-17.xml" target="_blank">PUA-17</a>
            </td>
            <td>
               <a href="keyboards/PUA-17/virtualKeyboards.xml" target="_blank">PUA-17</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=12"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 18: Characters with dot above </th>
            <td>
               <a href="keyboards/PUA-18.xml" target="_blank">PUA-18</a>
            </td>
            <td>
               <a href="keyboards/PUA-18/virtualKeyboards.xml" target="_blank">PUA-18</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=21"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 19: Characters with dot below </th>
            <td>
               <a href="keyboards/PUA-19.xml" target="_blank">PUA-19</a>
            </td>
            <td>
               <a href="keyboards/PUA-19/virtualKeyboards.xml" target="_blank">PUA-19</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=20"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 2: Small capitals </th>
            <td>
               <a href="keyboards/PUA-2.xml" target="_blank">PUA-2</a>
            </td>
            <td>
               <a href="keyboards/PUA-2/virtualKeyboards.xml" target="_blank">PUA-2</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=51"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 20: Characters with diaeresis </th>
            <td>
               <a href="keyboards/PUA-20.xml" target="_blank">PUA-20</a>
            </td>
            <td>
               <a href="keyboards/PUA-20/virtualKeyboards.xml" target="_blank">PUA-20</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=9"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 21: Characters with curl above (reversed ogonek) </th>
            <td>
               <a href="keyboards/PUA-21.xml" target="_blank">PUA-21</a>
            </td>
            <td>
               <a href="keyboards/PUA-21/virtualKeyboards.xml" target="_blank">PUA-21</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=6"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 22: Characters with ogonek </th>
            <td>
               <a href="keyboards/PUA-22.xml" target="_blank">PUA-22</a>
            </td>
            <td>
               <a href="keyboards/PUA-22/virtualKeyboards.xml" target="_blank">PUA-22</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=24"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 23: Characters with breve </th>
            <td>
               <a href="keyboards/PUA-23.xml" target="_blank">PUA-23</a>
            </td>
            <td>
               <a href="keyboards/PUA-23/virtualKeyboards.xml" target="_blank">PUA-23</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=26"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 24: Characters with breve below </th>
            <td>
               <a href="keyboards/PUA-24.xml" target="_blank">PUA-24</a>
            </td>
            <td>
               <a href="keyboards/PUA-24/virtualKeyboards.xml" target="_blank">PUA-24</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=44"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 25: Characters with circumflex </th>
            <td>
               <a href="keyboards/PUA-25.xml" target="_blank">PUA-25</a>
            </td>
            <td>
               <a href="keyboards/PUA-25/virtualKeyboards.xml" target="_blank">PUA-25</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=39"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 26: Characters with ring above </th>
            <td>
               <a href="keyboards/PUA-26.xml" target="_blank">PUA-26</a>
            </td>
            <td>
               <a href="keyboards/PUA-26/virtualKeyboards.xml" target="_blank">PUA-26</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=25"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 27: Characters with ring below </th>
            <td>
               <a href="keyboards/PUA-27.xml" target="_blank">PUA-27</a>
            </td>
            <td>
               <a href="keyboards/PUA-27/virtualKeyboards.xml" target="_blank">PUA-27</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=46"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 28: Characters with tilde </th>
            <td>
               <a href="keyboards/PUA-28.xml" target="_blank">PUA-28</a>
            </td>
            <td>
               <a href="keyboards/PUA-28/virtualKeyboards.xml" target="_blank">PUA-28</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=52"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 29: Characters with curly bar above </th>
            <td>
               <a href="keyboards/PUA-29.xml" target="_blank">PUA-29</a>
            </td>
            <td>
               <a href="keyboards/PUA-29/virtualKeyboards.xml" target="_blank">PUA-29</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=55"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 3: Enlarged minuscules </th>
            <td>
               <a href="keyboards/PUA-3.xml" target="_blank">PUA-3</a>
            </td>
            <td>
               <a href="keyboards/PUA-3/virtualKeyboards.xml" target="_blank">PUA-3</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=2"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 30: Characters with vertical bar above </th>
            <td>
               <a href="keyboards/PUA-30.xml" target="_blank">PUA-30</a>
            </td>
            <td>
               <a href="keyboards/PUA-30/virtualKeyboards.xml" target="_blank">PUA-30</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=54"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 31: Characters with superscript letters </th>
            <td>
               <a href="keyboards/PUA-31.xml" target="_blank">PUA-31</a>
            </td>
            <td>
               <a href="keyboards/PUA-31/virtualKeyboards.xml" target="_blank">PUA-31</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=27"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 32: Characters with acute accent and dot above </th>
            <td>
               <a href="keyboards/PUA-32.xml" target="_blank">PUA-32</a>
            </td>
            <td>
               <a href="keyboards/PUA-32/virtualKeyboards.xml" target="_blank">PUA-32</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=13"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 33: Characters with acute accent and dot below </th>
            <td>
               <a href="keyboards/PUA-33.xml" target="_blank">PUA-33</a>
            </td>
            <td>
               <a href="keyboards/PUA-33/virtualKeyboards.xml" target="_blank">PUA-33</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=35"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 34: Characters with acute accent and diaeresis </th>
            <td>
               <a href="keyboards/PUA-34.xml" target="_blank">PUA-34</a>
            </td>
            <td>
               <a href="keyboards/PUA-34/virtualKeyboards.xml" target="_blank">PUA-34</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=50"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 35: Characters with acute accent and curl above (reversed ogonek) </th>
            <td>
               <a href="keyboards/PUA-35.xml" target="_blank">PUA-35</a>
            </td>
            <td>
               <a href="keyboards/PUA-35/virtualKeyboards.xml" target="_blank">PUA-35</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=48"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 36: Characters with acute accent and ogonek </th>
            <td>
               <a href="keyboards/PUA-36.xml" target="_blank">PUA-36</a>
            </td>
            <td>
               <a href="keyboards/PUA-36/virtualKeyboards.xml" target="_blank">PUA-36</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=11"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 37: Characters with double acute accent and ogonek </th>
            <td>
               <a href="keyboards/PUA-37.xml" target="_blank">PUA-37</a>
            </td>
            <td>
               <a href="keyboards/PUA-37/virtualKeyboards.xml" target="_blank">PUA-37</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=37"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 38: Characters with dot above and ogonek </th>
            <td>
               <a href="keyboards/PUA-38.xml" target="_blank">PUA-38</a>
            </td>
            <td>
               <a href="keyboards/PUA-38/virtualKeyboards.xml" target="_blank">PUA-38</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=32"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 39: Characters with dot below and ogonek </th>
            <td>
               <a href="keyboards/PUA-39.xml" target="_blank">PUA-39</a>
            </td>
            <td>
               <a href="keyboards/PUA-39/virtualKeyboards.xml" target="_blank">PUA-39</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=33"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 4: Base-line abbreviation characters </th>
            <td>
               <a href="keyboards/PUA-4.xml" target="_blank">PUA-4</a>
            </td>
            <td>
               <a href="keyboards/PUA-4/virtualKeyboards.xml" target="_blank">PUA-4</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=63"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 40: Characters with diaeresis and macron </th>
            <td>
               <a href="keyboards/PUA-40.xml" target="_blank">PUA-40</a>
            </td>
            <td>
               <a href="keyboards/PUA-40/virtualKeyboards.xml" target="_blank">PUA-40</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=34"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 41: Characters with diaeresis and circumflex </th>
            <td>
               <a href="keyboards/PUA-41.xml" target="_blank">PUA-41</a>
            </td>
            <td>
               <a href="keyboards/PUA-41/virtualKeyboards.xml" target="_blank">PUA-41</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=14"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 42: Characters with diaeresis and dot below </th>
            <td>
               <a href="keyboards/PUA-42.xml" target="_blank">PUA-42</a>
            </td>
            <td>
               <a href="keyboards/PUA-42/virtualKeyboards.xml" target="_blank">PUA-42</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=10"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 43: Characters with ogonek and curl above (reversed ogonek) </th>
            <td>
               <a href="keyboards/PUA-43.xml" target="_blank">PUA-43</a>
            </td>
            <td>
               <a href="keyboards/PUA-43/virtualKeyboards.xml" target="_blank">PUA-43</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=31"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 44: Characters with ogonek and circumflex </th>
            <td>
               <a href="keyboards/PUA-44.xml" target="_blank">PUA-44</a>
            </td>
            <td>
               <a href="keyboards/PUA-44/virtualKeyboards.xml" target="_blank">PUA-44</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=38"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 45: Characters with ring above and circumflex </th>
            <td>
               <a href="keyboards/PUA-45.xml" target="_blank">PUA-45</a>
            </td>
            <td>
               <a href="keyboards/PUA-45/virtualKeyboards.xml" target="_blank">PUA-45</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=15"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 46: Characters with macron and breve </th>
            <td>
               <a href="keyboards/PUA-46.xml" target="_blank">PUA-46</a>
            </td>
            <td>
               <a href="keyboards/PUA-46/virtualKeyboards.xml" target="_blank">PUA-46</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=16"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 47: Characters with macron and acute accent </th>
            <td>
               <a href="keyboards/PUA-47.xml" target="_blank">PUA-47</a>
            </td>
            <td>
               <a href="keyboards/PUA-47/virtualKeyboards.xml" target="_blank">PUA-47</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=17"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 48: Characters with ogonek, dot above and acute accent </th>
            <td>
               <a href="keyboards/PUA-48.xml" target="_blank">PUA-48</a>
            </td>
            <td>
               <a href="keyboards/PUA-48/virtualKeyboards.xml" target="_blank">PUA-48</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=36"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 5: Modified base-line abbreviation characters </th>
            <td>
               <a href="keyboards/PUA-5.xml" target="_blank">PUA-5</a>
            </td>
            <td>
               <a href="keyboards/PUA-5/virtualKeyboards.xml" target="_blank">PUA-5</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=42"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 51: Variant letter forms </th>
            <td>
               <a href="keyboards/PUA-51.xml" target="_blank">PUA-51</a>
            </td>
            <td>
               <a href="keyboards/PUA-51/virtualKeyboards.xml" target="_blank">PUA-51</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=83"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 6: Combining Marks </th>
            <td>
               <a href="keyboards/PUA-6.xml" target="_blank">PUA-6</a>
            </td>
            <td>
               <a href="keyboards/PUA-6/virtualKeyboards.xml" target="_blank">PUA-6</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=61"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 7: Combining superscript characters </th>
            <td>
               <a href="keyboards/PUA-7.xml" target="_blank">PUA-7</a>
            </td>
            <td>
               <a href="keyboards/PUA-7/virtualKeyboards.xml" target="_blank">PUA-7</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=60"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 8: Punctuation marks </th>
            <td>
               <a href="keyboards/PUA-8.xml" target="_blank">PUA-8</a>
            </td>
            <td>
               <a href="keyboards/PUA-8/virtualKeyboards.xml" target="_blank">PUA-8</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=71"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Private Use Area 9: Critical and epigraphical signs </th>
            <td>
               <a href="keyboards/PUA-9.xml" target="_blank">PUA-9</a>
            </td>
            <td>
               <a href="keyboards/PUA-9/virtualKeyboards.xml" target="_blank">PUA-9</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=67"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Phonetic Extensions </th>
            <td>
               <a href="keyboards/PhonExt.xml" target="_blank">PhonExt</a>
            </td>
            <td>
               <a href="keyboards/PhonExt/virtualKeyboards.xml" target="_blank">PhonExt</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=3"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Runic </th>
            <td>
               <a href="keyboards/Run.xml" target="_blank">Run</a>
            </td>
            <td>
               <a href="keyboards/Run/virtualKeyboards.xml" target="_blank">Run</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=65"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Spacing Modifier Letters </th>
            <td>
               <a href="keyboards/SpModLet.xml" target="_blank">SpModLet</a>
            </td>
            <td>
               <a href="keyboards/SpModLet/virtualKeyboards.xml" target="_blank">SpModLet</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=56"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Superscripts and Subscripts </th>
            <td>
               <a href="keyboards/SupSub.xml" target="_blank">SupSub</a>
            </td>
            <td>
               <a href="keyboards/SupSub/virtualKeyboards.xml" target="_blank">SupSub</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=81"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Supplemental Mathematical Operators </th>
            <td>
               <a href="keyboards/SupplMathOp.xml" target="_blank">SupplMathOp</a>
            </td>
            <td>
               <a href="keyboards/SupplMathOp/virtualKeyboards.xml" target="_blank">SupplMathOp</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=68"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
         <tr>
            <th>Supplemental Punctuation </th>
            <td>
               <a href="keyboards/SupplPunct.xml" target="_blank">SupplPunct</a>
            </td>
            <td>
               <a href="keyboards/SupplPunct/virtualKeyboards.xml" target="_blank">SupplPunct</a>
            </td>
            <td><a href="https://mufi.info/m.php?p=mufichars&i=3&v=69"
                                target="_blank">Browse
                                charts</a></td>
         </tr>
      </tbody>
   </table>
</div>

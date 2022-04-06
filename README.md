# keyboardGT

The Aletheia document image analysis system and Transkribus offer the possibility to install additional virtual keyboards or to customize them.
This repository offers about 80 keyboards based on the [MUFI snapshot](https://mufi.info/m.php?p=mufiexport) for download on the [Github page](https://tboenig.github.io/keyboardGT/overview.html).



## Keyboard Production

The production of the keyboards is done automatically. 
An XSLT stylesheet and a Github action workflow are used.

If you want to create the keyboard on your computer 
- an XSLT processor is installed (Saxon is recommended)
- clone the repo and 
- the following command is necessary.

`java -jar saxon-he.jar -xsl:scripts/keyboard.xsl output=keyboards -s:scripts/keyboard.xsl `

📝 Note: The keybords are are stored in the folder `ghout/keyboards` on your system.

## See Also

- MUFI: The Medieval Unicode Font Initiative https://mufi.info/
- Aletheia https://www.primaresearch.org/tools/Aletheia
- Transkribus https://readcoop.eu/transkribus/
- Saxon https://www.saxonica.com/welcome/welcome.xml

# WatchOCR

WatchOCR uses cuneiform, and exactimage to create text searchable PDFs from image only PDFs and Tiffs. WatchOCR can be remotely configured to monitor a watched folder for newly scanned PDFs for OCR conversion.

WatchOCR can be remotely configured to monitor a watched folder for newly scanned PDFs for OCR conversion.

Forked from [rlangner](https://sourceforge.net/u/rlangner/profile/)'s script.

Source: http://sourceforge.net/projects/watchocr/

##Prequisites
* cuneiform
* exactimage
* ghostscript
* unpaper
* libtiff-tools
* unzip
* aspell-en (or other language)
* Optional:
  * oracle-java6-installer *(1)*
  * ant *(1)*
  * ZXing-1.6 *(1)*

## Installation
* Download zip then extract
* Copy watchocr and img2pdf into /usr/bin and make it executable

## Appendix
*(1)* for qrcode file rename

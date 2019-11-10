# Image Scanner
**Just a brief test**

### Ubuntu - Python 2.7.15+

Fire up your favorite terminal and clone the repo by typing
   git clone https://github.com/Adminixtrator/Docufix.io_.git

Then move into the Docufix.io_ folder and install requirements using
   pip install -r requirements.txt

Then run ImageScanner.py
   python ImageScanner.py

**Setting Tesseract path - Server configuration**
Install tesseract-ocr _(Already done by requirements.txt)_

Then get tessdata location by typing
   sudo find / -name "tessdata"

Then copy path and run
   export TESSDATA_PREFIX=path_copied   _(No Space between)_

Then get tesseract path 
   sudo find / -name "tesseract"

Copy path and replace **pt.pytesseract.tesseract_cmd** path in _ImageScanner.py_ 
   pt.pytesseract.tesseract_cmd=path_copied


_Go to 127.0.0.1:5000 on your browser and explore.._

### Use later version of browsers to have the most experience..


Drishti is a software that converts printed Hindi text to Braille.

Tesseract Open source library is used as an OCR to scan and convert printed Hindi text to unicode characters.

These characters are encoded into binary strings which are used to represent alphabets in braille. Arduino is used to display the characters by blinking of corresponsing LED's.

For the functioning of this software, You should have installed Tesseract and Leptonica and trained it for Hindi. 
You can download the dependencies using this Shell script: [Dependencies.sh](https://github.com/rahulchhabra07/Drishti/blob/master/Dependencies.sh).

After training, feed a JPEG image file containg printed Hindi text to the Python file. This creates a dialog box showing, the original image and translated text. Now click on next for displaying the text using arduino board.
A very simple python3 / python-pptx script that creates ppts for use in teaching English to beginners.

Installation
Clone or download the files.
Install the dependencies in requirements.txt
pip3 install python-pptx python-resize-image

Usage
Download images and put them in the /img directory. Name them according to whatever word or phrase you wish to teach (see examples).

Run the script:
python3 runme.py

Rename or copy the output file (a.pptx).

What it does
The first part of the presentation is used for introducing vocabulary and practicing phonics. The script will output a word, then the image, then the word again. You are supposed to modify or delete this last word deopending on what you want to teach (for example, you might want to get the children to complete __ee for tree because writing tree without scaffolding would be too hard).

The second part of the script generates a pogo drill. For each target word get children to jump to where the correct word is, there are ten slides per word. For example, for 'car' they have to find car ten times by jumping to the correct side.
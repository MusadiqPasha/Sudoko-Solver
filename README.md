# Sudoko-Solver
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 

- This repository contains a Python script that automates the game of Sudoku and enters it automatically into the website.
- It works on 3 websites  [SUDOKO.COM](https://sudoku.com/) , [LIVESUDOKO.COM](https://www.livesudoku.com/) and [USDOKO.COM](https://www.usdoku.com/)
- It uses `Pytesseract` to detect the numbers from the screenshot of the sudoko table and `Pyauotgui` to type the number's.

### What steps you have to follow??

- First install the [tesseract-OCR](https://tesseract-ocr.github.io/tessdoc/Downloads.html) and ADD IT TO PATH .
-  Download or clone my Repository to your device .
- type `pip install -r requirements.txt` in command prompt(this will install required package for project) .
- You should adjust the screenshot co-ordinates based on your display ratio like this . 
 <img src= "https://github.com/MusadiqPasha/Sudoko-Solver/blob/main/ScreenShots/region.png">
- Just run `sudokosolver.py` file .

### Project flow & explaination

- After you run the project , it'll ask you to choose the website that you opened.
    <img src='https://github.com/MusadiqPasha/Sudoko-Solver/blob/main/ScreenShots/gui.png'>
- It'll automatically take the screenshot of the region and convert it into numbers
- It'll open an excel file and ask you to confirm if the detected numbers are correct , if not then change them and SAVE the file before CLOSING.
- Then the program will solve the sudoko based on the number's in the excel file.



### Screenshots

<img src="https://github.com/MusadiqPasha/Sudoko-Solver/blob/main/ScreenShots/splitscreen.png">

<img src="https://github.com/MusadiqPasha/Sudoko-Solver/blob/main/ScreenShots/aftermath.png">


### Disclaimer
The Sudoko Solver is intended for educational purposes only. The authors and contributors of this repository are not responsible for any misuse or consequences resulting from the use of this software. Use it responsibly and at your own risk.


## Just follow me and Star ⭐ my repository 
## Thank You!!
## Happy typing!

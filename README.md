# Description
 A soundbox made in python and the qt framework

## Used librairies
 - Pyqt5
 - threading
 - playsound

## Installation
### Requirements:
 - python3.9
 - pip
 - all above librairies

### Process
 1- clone this repo `https://github.com/TheFourchette/PyBox.git`
 2- cd into PyBox
 3- Use the `pip install -r requirements.txt` to install required librairies
 4- Run by using `python main.py`

### Compilation
If for some reasons you want to compile that thing here's how to:
#### Requirements
 - all the above librairies
 - pyinstaller

#### Process
 Use this command in the PyBox folder `python -m PyInstaller -F main.py -n PyBox -w && rm -rf build && mv dist/PyBox Pybox && rm -rf dist *.spec *.prop`

 Now you have an executable named PyBox that you can execute

## Disclaimer
 Im still bad a doing things so keep in mind that this programm is WNIP(work not in progress).
 Feel free to modify it as you want!
 Btw the "stop all" button does nothing
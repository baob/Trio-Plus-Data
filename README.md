# Trio-Plus-Data
CONTENTS:
01 TLDR
02 Project Status
03 Working
04 Not working
05 Getting started
06 Going further


01 TLDR:
* Ultimate goal is to extract audio and midi data from the Digitech Trio Plus pedal's SD card for further use in your preferred DAW.

see: http://digitech.com/en/products/trio-plus

* Written in PYTHON3 (no dependencies)
* Tested on Windows, Linux


02 Project Status:
ALPHA

03 Working:
Extract audio from *.tlsd file if no overdub loops have been recorded

04 Not working:
Not correctly extracting audio in case there are overdub loops (possibly audio chunk alignment issue)
Not separating the different part sections of the song (only one wave file as output)
Any MIDI data support is missing at the moment

05 Getting started:
download and install the latest Python version for your computer from
https://www.python.org/downloads/

Record some stuff with the Trio Plus

Export the songs (the single files) onto your computer using the Digitech Trio Manager
http://digitech.com/en/softwares/

Place the Python script from this page (audio_from_trio_vX.X.py) in the same directory as the exported songs (*.tlsd) from the SD card

Fire up the script! -> LINUX users remember: you might need to change the endlines of the script (as it was edited on windows) <-

The subfolder 'Trio_wav_export' will be created and the audio contents of the songs will be written herein

06 Going further
Need help to further reverse-engineering the data
Look at my 'findings.txt' for what I found out so far

Let's have fun!

# ms_notepad_tricks
This is a collection of tricks and tips for using Microsoft Notepad. It seems that they also work for Textpad, Notepad++, etc. Let's see...

This repository was created as a way of logging the teachings from the video "Secrets of Windows Notepad" (https://www.youtube.com/watch?v=B5C7CH_A8Xo), authored by ThioJoe (https://www.youtube.com/@ThioJoe). So, please, all cretits on this nice peace of knowledge goes to him.

## Secret #1
### .LOG for auto-logging file

Create an auto-logging file that will automatically add a new line with a date-time stamp to itself everytime you open it. Very useful to keep track of your activities and timesheet. Just add .LOG at the first line and leave it there.

## Secret #2
### F5 - or - Menu Edit > Time/Date

This will add a date/time stamp to your current document.

## Secret #3
### Character codes on page setup

Go to menu File > Page Setup, in the Header and Footer sections and add one or more of the following:

- &L - Will left-align any characters that follow it.
- &C - Will center any characters that follow it.
- &R - Will right-align any characters that follow it.
- &D - Will put the current date.
- &T - Will put the current time.
- &F - Will put the name of the document.
- &P - Will put the page number.


## Secret #4
### Command Line Arguments

Very useful for any operation that deals with text files from command line or automates this kind of activity. Can be a powerful alternative for using along with scripts that deal with text files.

#### notepad /A file_a.txt

This one will open file_a.txt with ANSI encoding. Or you can go to menu File > Open..., and choose the desired Encoding option.

#### notepad /W example_w.txt

This one will open file_w.txt with UTF-16 LE encoding (at least in my computer). Can you help me explain this command line better?
Or you can go to menu File > Open..., and choose the desired Encoding option.

#### notepad /P example_p.txt

This will print the file_p.txt to your default printer.

#### notepad /PT example_pt.txt whateverPtinterName someDriver.dll

This one you will have to test and then tell me what this is about.

#### notepad /.SETUP

This one also you will have to test and then tell me what this is about.
It opens a kind of dummy unclickable window. Maybe it was used for some kind of Windows setup in the past or in the present? Who knows?




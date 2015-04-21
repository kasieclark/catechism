# catechism
Trivia game in MIPS architecture.
INSTALL & RUN INSTRUCTIONS (PC ONLY)*:

1) Open and install PCSpim

2) When the installer is finished, it should ask if you would like to adjust the settings of the assembler. Click 'Yes' or the affirmative.

3) Uncheck the lower most box (should be something like 'Load unchecked exceptions')

4) Open PCSpim. Click the file folder icon in the toolbar.

5) Navigate to the game folder and select Catechism.asm

6) To run, click the icon in the toolbar that looks like a document with an arrow pointing down.

7) A window will pop up. Copy/Paste the following: 0x00400000

8) If there are any errors, please refer to contact.

9) If there are any uninitialize/unreferenced variables, just click OK and continue to run.

10) Play!

*Able to be run on Mac and Linux given that a compiler can be run. Instructions most likely differ. If you would like to provide instructions for how to install and 

play on Mac and Linux systems, please e-mail them to the contact below.

INSTRUCTIONS:

True/False: 1/2 Respectively
A/B/C/D: 1/2/3/4 Respectively
Yes/No: 1/2 Respectively


CONTACT:

kasclark@student.methodist.edu
For any errors at runtime and/or compile time.
If you would like to modify the sourcecode, please seek permission by e-mailing me at the above and also at kasie.clark@aol.com


Thanks for downloading, testing, and playing! :)


ERROR LOG:

v. 1.1.0:

Known errors:

None

Fixed errors:

All previous errors fixed.
All sections coded completely.
Spelling and code may be subject to change after this point.

v. 1.0.9:

Known errors:

1) dWin, dLoss, and xLoss display incorrect score (but will route correctly.)

Fixed errors:

1) From win menu if selected to continue, now branches to appropriate reInit to, obviously, reInit. (Fixes error #2 from v. 1.0.8.)

2) Error #1 from v. 1.0.8

3) Error #2 from v. 1.0.8

4) Error #2 from v. 1.0.5 - Not fixed, but cause is known and is not an error, but a simple compile override as section has not yet been written.


v. 1.0.8:

Known errors:

1) Getting 1 question wrong on Easy section will branch immediately to a loss and back to the main menu.

2) Continuing to medium section from Easy section causes misprints in compile?

3) Medium win computes correct score but displays Easy win message.

Fixed errors:

1) Counter math updated to fit proper passing scores.

2) Some variables deleted due to no use.

3) Three reInit sections now included to re-initialize registers/variable to beginning points (inserted before medium section, difficult section, expert section.)

v. 1.0.7:

Known errors:

1) End of medium section asks you if you want to proceed to the medium section.

2) End of difficult section asks if you want to proceed to the easy section.

Fixed errors:

1) Medium counter has correct redirect.

2) Medium question placeholder errors fixed.

3) All sections aside from Learn are completely coded.

v. 1.0.6: 

Known errors:

1) mTally math incorrect.

2) Medium counter has wrong redirect.

3) Some medium question placeholders have copy/paste errors.

4) dTally math incorrect.

v 1.0.5: 

Known errors:

1) No play sections above easy will play

2) Entering '2' from the main menu still causes the play section to run.

3) Continuing to medium section prompts error message to print followed by the close message, not allowing user to functionally re-run the program without going back to PCSpim to do so.

Fixed errors:

1) All correct answers in easy section computes and displays correct score.

2) Score computes and displays correctly for a 'fail' score.

100% Functional sections:

1) Play
 >1) Easy

3) Inform

4) Exit

v 1.0.4: 

Known errors:

1) If all answers correct in easy section, score does not compute correctly.

2) If all answers incorrect in easy section, score does not compute correctly and the console displays the winning message as well as the option to continue to the medium section.

3) Entering '2' from the main menu still causes the play section to run.

4) Continuing to medium section prompts error message to print followed by the close message, not allowing user to functionally re-run the program without going back to PCSpim to do so.

Fixed errors:

1) Able to advance past question 1 of easy section.

2) No unitialized values/variables. (___start is a standard)


100% Functional sections:

3) Inform

4) Exit

v 1.0.1:

Only easy section can be accessed at this time. 
Some sections may not all work properly. 
Heavy beta mode.





Catechism © Kasie Clark 2015

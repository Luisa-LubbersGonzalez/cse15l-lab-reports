# *Lab Report #4*

## VIM Steps 4-9
For Step 4, the keys pressed were: ```ssh llubbersgonzalez@ieng6.ucsd.edu<ENTER>```
This was just me logging onto ieng6 to be able to complete the steps 
![Image](Step4.png)

For Step 5: the keys were: ```git clone <CMD> V<ENTER>```, ```rm -rf lab7<ENTER>```, ```<up><up><ENTER>```
I pasted the ssh link that I had gotten from my forked repository of Lab 7, then I had to delete the previouly clonned repo using `rm` because I had practiced the steps before. Then I just went up twice to access the `git clone` I had used before in my history
![Image](Step5.png)

For Step 6, the keys used were: ```cd lab7/<ENTER>```, ```ls<ENTER>```, ```cat tesh.sh<ENTER>```, ```bash test.sh<ENTER>```
I `cd`d into the necessary directory, listed all the file present, `cat`ed test.sh to make sure that the tests look ok and had no bugs, and then ran the tests with `bash`
![Image](Step6.png)

For Step 7, the keys were: ```vim ListExamplesTest.java<ENTER>```, ```:q!```, ```vim ListExamples.java```, ```:44```, ```i <right><right><right><right><right><right><BACKSPACE> 2 <ESC>```, ```:wq```, ```<up><ENTER>```, ```:q!```
This step was quite long. I started by accessing the testers using Vim to verify that the error wasn't in the testers, and it wasn't. I then exited the file without saving any changes (because none were made) and accessed ListExamples with vim. I recognized the error in the file was on line 44, where it needed to update index2 so I went to that line. I entered edit mode with `i` and then proceded to the part that needed to be changed (1 to a 2) and hit `<ESC>` to get out of insert mode. I saved my changes in the file with `:wq` and then accessed the file again using vim to ensure that the save was in fact, made. I exited the file without editing anything again using `:q!`
![Image](Step7.1.png) ![Image](Step7.2.png) ![Image](Step7.3.png) ![Image](Step7.4)

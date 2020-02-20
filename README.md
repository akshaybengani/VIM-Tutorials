# VIM Tutorials
* Vim is an advanced text editor.
* Vim = VI + IMproved.
* Vi is actually created as an text editor for the unix operating system.
* Vi is short for "visual"
* Vi has been replaced with VIM
* VIM is installed in almost everywhere.
* Some programs default editors are also assigned to VIM.
* VIM provides some amazing features include macros, registers, command repetation, auto completion, text object searching, filters, and global substitutions.
* VIM is cross platform and available everywhere.
* VIM provides syntax highlighting over different types of file types even system configuration files.
* VIM commands are case-sensitive

## VIM Modes
When you start VIM you get ```normal``` mode which is also called as command mode because anything you type here will be interpreted as command.
* Normal / Command Mode
* Insert Mode
* Line Mode
* There are othe modes too...

The other variations of these modes are based on these 3 modes, we will be learning other modes at the end.
* To enter ```insert``` mode, type ```i``` while in normal mode.
* To leave ```insert``` mode, press escape.
* To enter ```line``` mode, type ```:``` while in normal mode.
* ```Line``` mode is basically called as last line mode over here you can use commands to save the file, turn on and off VIM controls, and various actions.
* Keep in mind you can always enter into ```normal``` mode by pressing escape key.

### Start and Exit VIM
* To get started with vim open your terminal and type ```vim```
* To exit VIM you need to enter in Line mode, so type ```:``` to enter line mode and type ```q``` as an exit command.

### Create new file using VIM and save it
* Open terminal and type ```vim filename``` this will open VIM.
* As by default we get normal mode so to enter into ```insert``` mode use ```i``` then add your text in the file.
* Now in order to save the file you have to enter in ```line``` mode where you have a command called ```:w``` to save the file.
* And if you want to exit with saving you can use ```:wq``` this will not only save your file but also exits vim.

### VIM Essential Navigation
Navigation in ```normal``` mode or ```command mode```
* To move ```down``` a line, press ```j```
* To move ```up``` a line, press ```k```
* To move to the ```right```, press ```l```
* To move to the ```left```, press ```h```
* You can also press and hold a navigation key so that it repeats.
* To move all the way to the top of the file, press and hold ```k```
* To move all the way to the bottom of the file, press and hold ```j```
* To move forward in the file, use ```Ctrl-f```. Hold down the control key and press ```f```.
```Ctrl-f``` is the same as the ```page down``` operation.
* To move backward in the file, use ```Ctrl-b```. Hold down the control key and press ```b```.
```Ctrl-b``` is the same as the ```page up``` operation.
* To move forward by word, use ```w```. To move forward by word using white space as
word boundaries, use ```W```.
* To move backward by word, use ```b```. To move backword by word using white space
as word boundaries, use ```B```.
* To go to the begining of the file, type ```1gg``` or just ```gg```.
* To move to the last line of the file, type ```$G``` or just ```G```.
* To go to a specific line number use <LINE_NUMBER>gg or <LINE_NUMBER>G.  For
example, to go to line 27, type 27gg or 27G.
* You can even use line mode to go to a specific line.  For example, to move to
line 32, you would type ":32<ENTER>".  To go to the last line, use ":$<ENTER>".

This training is being provided by LinuxTrainingAcademy.com.

The rest of this file is comprised of random sentences.  This will give you a
chance to practice.  There is no need to study the contents of the remaining
portions of this file.

  Far far away, behind the wild mountains, far from the countries Vokalia and
Consonantia, there live the blind texts. Separated they live in Bookmarksgrove
right at the coast of the Semantics, a large language ocean.

  A small river named Duden flows by their place and supplies it with the
necessary regelialia. It is a paradisematic country, in which roasted parts of
sentences fly into your mouth.

  Even the all-powerful Pointing has no control about the blind texts it is an
almost unorthographic life One day however a small line of blind text by the
name of Lorem Ipsum decided to leave for the far World of Grammar.

  The Big Oxmox advised her not to do so, because there were thousands of bad
Commas, wild Question Marks and devious Semikoli, but the Little Blind Text
didn't listen. She packed her seven versalia, put her initial into the belt and
made herself on the way. When she reached the first hills of the Italic
Mountains, she had a last view back on the skyline of her hometown
Bookmarksgrove, the headline of Alphabet Village and the subline of her own
road, the Line Lane. Pityful a rethoric question ran over her cheek, then she
continued her way.

  On her way she met a copy. The copy warned the Little Blind Text, that where
it came from it would have been rewritten a thousand times and everything that
was left from its origin would be the word "and" and the Little Blind Text
should turn around and return to its own, safe country.

  But nothing the copy said could convince her and so it didn't take long until
a few insidious Copy Writers ambushed her, made her drunk with Longe and Parole
and dragged her into their agency, where they abused her for their projects
again and again. And if she hasn't been rewritten, then they are still using
her.

This training is being provided by LinuxTrainingAcademy.com.









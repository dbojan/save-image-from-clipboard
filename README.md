# save-image-from-clipboard
v 2025-03-30-1  

## what is it:  
save image from memory (clipboard), to a .png file in the program dir. for windows

## installation:
righ click and select save link as: [here](https://raw.githubusercontent.com/dbojan/save-image-from-clipboard/refs/heads/main/save_image.zip)

## how to use:  
-click on 'print screen' key on keyboard. this will copy image of your screen to the computer memory.  
-start save_image.exe, which will save image from memory, to file date_time.png in the program dir.

if you add "test" to the program shortcut, or use from the command line:  
save_image.exe "test name"  
or  
save_image.exe test

image will be saved as "test name.png" or test.png  
if test.png exists, new file will be named test_1.png, then test_2.png ...

if you want delay:  
-maximize window, set everything for the recording  
-click "print screen" on the keyboard. image will be copied to computer memory.  
-you can minimize screen.  
-got to save_image folder, and start save_image.exe  
you DO have to be looking at the maximized window of the application, when you click on 'print screen' key on the keyboard  
you don't have to be looking at the maximized window of the application, when you start save_image.exe

OR

-start save_image_with_delay.bat by double clicking it  
-do your thing (maximize window, etc)  
-press 'print screen' on keyboard  
-5 seconds later program will save image from clipboard to file.

you can edit .bat file, with text editor, like notepad, or notepad++ .

If you do not copy image to memory first, program will not save anything.


you can also copy image to the memory using paint program. click on square icon ('Select'), make square using mouse, click on copy icon in the program.  
star save_image.exe

https://forum.colemak.com/topic/870-hacked-msklc-to-enable-remapping-capslock/

Instructions:

(1) Download and install Microsoft keyboard Layout Creator 1.4 (MSKLC) from Microsofts website.

(2) Copy a backup of the file C:\Program Files\Microsoft Keyboard Layout Creator 1.4\inc\kbd.h
    In 64bit windows its: C:\Program Files (x86)\Microsoft Keyboard Layout Creator 1.4\inc\kbd.h
    Keep this backup in a safe place so you can easily restore the file if need be.

(3) Open (EDIT) kbd.h in notepad.  Scroll down till you see the keyboard type 4 definitions.
    Now replace where it says "CAPTITAL" with "BACK".
    Save the file.  And now 'copy and replace' it back into the %MSKLC%\inc directory so MSKLC will now use the new definition when it runs.

(4) Run MSKLC as you normally would.
    Create or import a layout and then "build DLL and Setup Package".

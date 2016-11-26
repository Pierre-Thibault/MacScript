# MacScript

Little AppleScript to make life easier on the Mac.

Here some AppleScript scripts that you might find useful.
(for the moment there is just one script)

## ContextualMenu.scpt

Fix the non working contextual menu key.

### Dependencies

To use this script you need [BlueM/cliclick](https://github.com/BlueM/cliclick). So install it first. The script is expecting clickclick to be in `~/bin` so edit the script if you have installed  clickclick elsewhere.

### Description

If you have a keyboard with a contextual menu key then it does not work automatically on the Mac. This is because MacOS does not support this key. So I made a script that is simulating a control-click so I can after that assign the script to the contextual menu key on the keyboard using a shortcut utility application. I suggest to use [Apptivate](http://www.apptivateapp.com/) because it works well for free but you can use another app if you prefer. Control-click normally brings the menu contextual where the mouse pointer is located. This means that the menu contextual may appear outside the field you are typing in. So this is not perfect but I find it useful anyway.

### How to use

To use the script simply put it in a safe place of your choice on your drive. Then assign a shortcut to the script in Apptivate or another shortcut utility.

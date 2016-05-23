# Manual Installation Instructions
If you're using windows, save your sanity and install Notepad ++. Or use notepad if you're a masochist.

Download the newest release. You want the manual install version.
https://github.com/Grewfisk/nerd.nu-Moderation-GUI/releases

##### If you only have keyboard bindings and no GUI buttons/labels:
1. Ensure Minecraft is closed. It will overwrite the files you're editing on exit.
2. Open the macromod settings folder at .minecraft/liteconfig/common/macros/
3. Copy the .chatfilter.txt file from the downloaded zip into the macros directory, replacing the existing file.
4. Copy the .gui.xml  file from the downloaded zip into the macros directory, replacing the existing file.
5. Open .minecraft/liteconfig/common/macros/.macros.txt in a text editor.
6. Paste the contents of .macros.txt from the zip file at the bottom of the file and save the file.
7. You're now ready to use! Start up minecraft and press the [~] key to open macro mod. You should see the Requests screen by default.

##### If you have both keyboard bindings and GUI buttons/labels:
1. Ensure Minecraft is closed. It will overwrite the files you're editing on exit.
2. Open the macromod settings folder at .minecraft/liteconfig/common/macros/
3. Copy the .chatfilter.txt file from the downloaded zip into the macros directory, replacing the existing file.
5. Open .minecraft/liteconfig/common/macros/.gui.xml in a text editor.
6.Paste the contents of .gui.xml from the zip file at the bottom of the file, on the line above `</gui>` and the line below `</gc:guilayout>`. Save the file.<br />![Paste between the tags on a new line](https://raw.githubusercontent.com/Grewfisk/nerd.nu-Moderation-GUI/master/images/editguixml.png)
7. Open .minecraft/liteconfig/common/macros/.macros.txt in a text editor.
8. Paste the contents of .macros.txt from the zip file at the bottom of the file and save the file.
9. Start up minecraft and press the [~] key to open macro mod.
10. Click the "Edit key bindings" icon.<br />![Edit key bindings](https://raw.githubusercontent.com/Grewfisk/nerd.nu-Moderation-GUI/master/images/editkeybindings.png)
11. Click the "GUI Editor" icon<br />![GUI Editor](https://raw.githubusercontent.com/Grewfisk/nerd.nu-Moderation-GUI/master/images/guieditor.png)
12. Find "Mod Requests" in the list of available screens<br />![Available screens](https://raw.githubusercontent.com/Grewfisk/nerd.nu-Moderation-GUI/master/images/availablescreens.png)
13. Drag and drop it into the "playback" slot, replacing default<br />![playback default](https://raw.githubusercontent.com/Grewfisk/nerd.nu-Moderation-GUI/master/images/playbackdefault.png)
14. Hit OK and exit out of macromod
15. Press [~] again and now you should see the Requests Screen.

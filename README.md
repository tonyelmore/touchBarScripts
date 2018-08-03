# touchBarScripts
This is a script that can be put into BetterTouchTool (https://folivora.ai/) to toggle the Mute / Unmute Audio while in Zoom.
You will have to spend the $6.50 or $20.00 for BetterTouchTool
The only program that seems to not play well with this is VisualStudio Code

To use this script...
1. In BetterTouchTool select "TouchBar" along tab bar
2. Select "+ Widget/Gesture"
3. Select "Run Apple Script and Show results" from the drop down
4. Select "Send Shortcut to Specific App" from the Predefined Action drop down
    * Select Shift-Cmd-A as the shortcut
    * Select zoom.us as the application
5. Under "Advanced Configuration" paste in this script
6. You can optionally add an icon
7. On the "Appearance & Setting" tab
    * Drag and drop the icon from zoom.us into the "icon" box
    * To get the icon, right click on the zoom.us file in Applications, select "Show Package Contents"... the icon file is "Contents/Res    ources/ZPLogo.icns"

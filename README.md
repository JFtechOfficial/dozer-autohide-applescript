# Dozer Autohide
Add autohide funtion to Dozer (by [Mortennn]((https://github.com/Mortennn/Dozer)).

# How To
Use applescript to run dozer after starup and sen ket code to hide the menu items.

1. Download and install Dozer.

2. Open Scrpit Editor and add this into file:

```applescript
tell application "Dozer" to activate
tell application "System Events" to key code 43 using {control down}
```

You need to replace (43 using {control down}) with your shortcut, and should setup this shortcut in Dozer in order to work.
[Complete list of AppleScript key codes])https://eastmanreference.com/complete-list-of-applescript-key-codes)

You may encounter a system warning says that "Script Editor is not allow to send key code", you need to go to `System Preference > Security & Privacy > Privacy tab > Accessibility` and check script editor.

3. Save as Application. You can put this file anywhere you like.

4. Got to `System Preference > Users & Groups > Login items` and add this applescript file into list.

5. Done!

# ToggleNet
macOS tool for turning network services on and off


Download and extract ToggleNet.zip
Open ToggleNet.app
Add to your login items if you want it to always be on.

NOTE: If you get the "This App is Broken, Move to Trash" error. You can run this command to fix it.
xattr -d com.apple.quarantine /path/to/app

If you moved the App to the Application folder, the command should be: 
xattr -d com.apple.quarantine /Applications/ToggleNet.app

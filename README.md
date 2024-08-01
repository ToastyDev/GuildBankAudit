# Guild Bank Audit
A tool for players who want to manage their guild banks outside of the game. The addon will output a compiled list of all items with a complete count of each item.
The idea was to save hours of manual data entry into a spreadsheet, and create a way to do it with one copy & paste!

# Buttons!
Buttons have been added to the guild bank frame! Same rules apply for pre loading bank tabs for the popup to work properly.

# THE BUTTONS DO NOT WORK WITH ADDONS THAT REPLACE THE BLIZZARD GUILD BANK FRAME!
You will need to disable these addons to see the buttons. The slash commands below will still work if you would prefer to keep your addons enabled.

All commands can be used with "/gba", "/gbank", or "/guildbankaudit" followed by one of the following commands:
- all -> scans the entire bank and displays entire output. You must manually click each tab within your guild bank, the addon cant see what hasn't been loaded.
- tab -> scans the current selected tab
- money -> grabs money related information and shows the total gold in the bank, the difference since your last scan, and the latest transactions
- options -> opens the options panel to toggle output behavior
- help -> displays a version of this in game
- bugged -> displays a window with the link to report any bugs

# Available Options
- Add a WoWhead link to the output of a scan. Automatically detects which client is running and changes the link
- Toggle whether to add the in game gold/silver/copper icons to the money log scans
- Toggle whether to add the Blizzard time stamps to the money log scans
- (EXPERIMENTAL) Toggle whether to create an extended money log where log scans are saved in its own table. This can only see entries currently in the guild bank due to client limitations. There is a good chance that entries will be missed unless you run this often. 

# Not A Bug List
- The number of entries in the money log is limited by Blizzard. They push the oldest transactions out as new ones are recorded. Otherwise the data stored would grow to insane levels across the whole game.

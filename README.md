# Debugger Commands

This gitpages contains a list of commands from different debuggers

Current debuggers:

* WinDbg (Windows Debugger)
* GDB (GNU Debugger)
* GDB-PWNDBG (GNU Debugger with Pwndbg)

## To add a new debugger to the table

1. Create a json object for the the debugger in `Commands.json`, put at least one field (the command/description/example) to populate the table
2. Create a new button in `index.html` that looks like the following: `<button class="filter_button" onclick="filterButton('WinDbg');">WinDbg</button>`. Ensure that the string you're passing into the `filterButton()` function is exatly the same as the name of the new json object from step 1
3. Within the javascript portion in `index.html`, add the name of the new json object from step 1 in the list `var toolList`

View the page [here](https://josh-vr.github.io/Debugger-Commands/)!

Sources (in progress):

* [https://sites.google.com/site/taesaza0/etc/windbgcheatsheet](https://sites.google.com/site/taesaza0/etc/windbgcheatsheet)
* [https://theartofdev.com/windbg-cheat-sheet/](https://theartofdev.com/windbg-cheat-sheet/)
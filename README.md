killu
=====
This script pretty much the same as killall -u user proc  
The reason for this tool is I don't want to install the psmisc package  
Nothing wrong with it, but if I don't need the whole package. Or even all of killall's options, so I figured I'd save some space. 

Usage
=====
    This program sends the KILL signal to all processes that match a provided name and are run by a provider user 
    USAGE: ./killu [username] [process]
    Example: Kill all python processes ran by miku
    ./killu miku python

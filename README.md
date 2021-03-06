IntelliJ keyboard shortcuts
===========================

Since I'm using __IntelliJ__ based IDEs (such as PyCharm) quite a lot these days, and I've noticed
some issues with sync-settings functionality, I want to document the shortcuts I've added or just
use a lot so I can re-create them when syncing bugs out.

I'm in the process of learning IDEA defaults instead of my finger-memory of Sublime Text kb shortcuts;
it's painful but I think it's worth it as I work so much in IDEA based IDEs nowadays!


Favorites - general
-------------------

|    Keyboard Shortcut           |     Description                             |
|-------------------------------:|---------------------------------------------|
|                   Shift, Shift | Search everything; both settings,           |
|                                | content of project files and probably       |
|                                | more I don't even know about!               |
|                                | Really handy when unsure of what kb         |
|                                | shortcut is used for something              |
|                                | (also displays kb shortcut to the right     |
|                                | of each option so learning builtin here)    |
|                        Alt + J | Select next occurance.                      |
|         Ctrl + Shift + Alt + J | Select all occurances. Possibly more        |
|                                | Python-aware than ST's Alt + F3             |
|                       Ctrl + W | Close current window                        |
|                       Ctrl + L | Increase selection by surrounding           |
|                                | cursor or previous selection in             |
|                                | closest natural 'delimiter scope'           |
|                 Ctrl + Alt + S | Settings. Especially useful                 |
|                                | when fiddling with .venv and such           |
|             Ctrl + PgUp/PgDown | Switch to left/right editor tab.            |
|             Ctrl + Shift + T   | Reveal edited file in project tree          |
|                         Escape | Focus editor window (whenever any other     |
|                                | window has focus)                           |
|                        Alt + 1 | Focus project window (bring it up if        |
|                                | it's closed)                                |
|                        Alt + 4 | Focus Run Window (handy with programs       |
|                                | using input(..))                            |
|                      Alt + 2,2 | Bring up and hide Favorites window,         |
|                                | basically giving focus to editor            |
|                                | window. To get back from project or         |
|                                | run window quickly!                         |

 
Favorites - edit and refactor
-----------------------------

|    Keyboard Shortcut           |     Description                             |
|-------------------------------:|---------------------------------------------|
| Ctrl + Alt + Shift + L, Enter  |   Reformat file (or selection if present)   |
| Ctrl + Alt + Shift + T         |   Refactor this (bring up refactoring menu) |
| Ctrl + Shift + D               |   Duplicate current row.                    |
| Ctrl + Shift + Up/Down         |   Move line (or selection) up/down.         |
| Ctrl + J                       |   Snippet menu. Basically using this for    |
|                                |   `if __name__ == '__main__':` only :)      |
| Shift + Alt + mouse drag       |   Block select                              |
| Ctrl + \[ or \]                |   Unindent or indent selection              |


Custom shortcuts - debugger
---------------------------

|    Keyboard Shortcut           |     Description                             |
|-------------------------------:|---------------------------------------------|
|                             F5 | Step Into                                   |
|                     Shift + F5 | Step Over                                   |
|               Shift + Alt + F5 | Stop Out Of                                 |


Custom shortcuts
----------------
Some things are just missing shortcuts for my workflow, so I've come up with my own:


|    Keyboard Shortcut           |     Description                             |
|-------------------------------:|---------------------------------------------|
|                       Ctrl + O | File -> Open (duh! This is the first        |
|                                | editor/IDE/desktop software that has        |
|                                | lacked open kb shortcut since I started     |
|                                | using software in the 80's... very          |
|                                | surprising!)                                |
|                 Ctrl + Alt + W | Collapse all definitions                    |
|         Ctrl + Alt + Shift + W | Close other editor windows                  |
|                                | (when browsing lots of code this is         |
|                                | handy for focusing on one of them)          |
|               Ctrl + Shift + S | Save As                                     |
|                       Ctrl + K | Commit window                               |
|               Ctrl + Shift + K | Push window                                 |
|                       Ctrl + T | Update project                              |
|         Ctrl + Shift + Alt + E | Go to next error in file                    |


Not assigned yet: Run with coverage. Using this a lot when doing approval testing


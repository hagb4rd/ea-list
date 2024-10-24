
Manage lists quickly via sh

LIST_DIRECTORY=$HOME/.list

lists are maintained in this directory.


LIST_EDITOR=nano 
LIST_X_EDITOR=gedit 

depending on wheather DISPLAY is set (graphical desktop) one of both editors is chosen 

al <listname> <element> 

adds element to listname. if no element given, edit list in editor

el <listname> 

opens all elements of listname as files in editor

** Text Editor **

-A text editor is a tool used to create, open, edit and save text files in linux.
-examples: vi, vim, nano, kate, atom

what is vi?
--vi stands for Visual Interface. it is a classic text editor commanly found on unix system bt havin
limited features.

VIM ?
--> vim stands for VI iMproved 
-->it is advanced version of vi with more advanced features. 


Vim modes:
1. Normal mode: (default mode)
--> it is a default mode when you open vim. it can be accessed from other modes using 'esc' 
2. Insert Mode:
--> this mode allows you to enter and edit text. to enter in insert mode use 'i'
3. Command-line mode/command execute command:
--> this mode allows you to execute commands. type ":" and then enter commands at a prompt.
4. Visual Mode:
--> A mode that provides additional options for selecting text. and to enter visual mode use "v"


**syntax to open file**
vim  <file_name>
vim  demo.txt

**saving and quitting**
1. saving a file =  use :w amd enter
2. exiting a file= use :q and enter
3. saving and quiiting =  use :wq amd enter
4. display line numbers= use :set nu
5. hide line numbers= use :set nonu

**cursor movement shortcuts**
h = move left
j = move down
K = move up
l = move right
OR
use arrow keys
gg = go to the beginning of the file.
shift + g = move to the end of the file.
shift + h = move to the top of the screen
shift + m = move to the middle of the screen
shift + l = move to the bottom of the screen
<n>gg / :n = move to the nth line
10gg / :10 = move to the 10th line 


**Search and Replace**
1. forward search: (top to bottom)
synatx: /word
eg: /AWS

2. backword search: (bottom to up)
syntax: ?word
eg: ?AWS
press 'n' for the next occurance of the search word.

*replace word:
syntax = :%s/word1/word2/g
--> this command is used to replace word1 with word2 globally
eg= :%s/AWS/Microsozt Azure/g
Hw:
1. replace single occurance
-->
2. to replace single occurance defined on number line 
--> 


**undo and redo** 
u = to undo last changes
ctrl+r = to redo the changes

**delete, cut, copy and paste**

dd = delete current line
<n>dd = delete n lines from the current line
15dd = delete 15 lines from current line
dw = delete a word
<n>dw = delete n words

cc = cut current line
<n>cc = cut n lines
cw = cut the word
<n>cw = cut n words

yy = copy current line
<n>yy = copy n lines
yw = copy a word
<n>yw = copy n word

p = to paste the cut/copied text
<n>p = paste n times

**Visual Mode**
u = change the case of the visually selected text to UPPERCASE
shift+u = change the case of the visually selected text to LOWERCASE
~ = invert the case of the visually selected text. (lowercase become uppercase and vice versa)




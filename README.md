# My Notes:

## Markdown (.md) notes (Day 2): 
Contains example from [rwx](https://rwx.gg/basicmark/)

`block`  

*italic*  

**bold**

```
bar/fence
```

```js
console.log("fence js- add color syntax")
```
link to [mattiwos.com](https://mattiwos.com)  

2 spaces to go to new line_ _  

seperater = ----  

~~~~Markdown

```js
second fense
```
~~~~

>"insert quote"(Mattiwos).  

To check avalibality of javascript/html [here](https://caniuse.com/)
## Terminal/linux 
pwd == shows current location (working station). 
ls = shows files in current directory.  
mkdir (name) = makes folder   
clear = clears the terminal screen.    
cd (Directory) = to go into a directory.   
tab key = completion.     
control-s = suspends terminal.   
control-z = contuineis to run in the background and goes to comm
and line    
control-c =cancels current process.   
control-d = sends of end of file signal.  
cd .. = go up one level in dirs. 
mv [current name] [new name] = to move/rename file.    
touch [file name] = makes file.    
rm = deletes file. 
cat = spits of content of the file  
ping (website)= to check internet connection.  
traceroute (website) = pings every router/server it goes through and prints it.   
scp (file) (sshaddress) = sends files form local comp to remote comp.  
file (filename) = prints out what the file type is   
less (filename) = lets us view contents of file and scroll up and down  
cp item directory= copy files and eirectorie(Used for long files)  
ln [-s to create sysmbolic link]*file* *link* = creates hard and symbolic links  
wildcards are * , ??? -number of characters and etc  
type *command* = displays what kind of command the shell will execute 
such as the location or if its a shell builtin command  
which *command* = displays an executable's location  
help *command* = gets help for shell builtins  
man *program* = displays a programs manual page  
whatis *command* = displays a oneline maunual page descriptions  
info - displays a program's info entry  
alias *name*='*command*' = creates an alias for a command  
unalias *name* = removes alias
*item1* > *item2* = redirection operator which sends the output of item one to item 2 asn an input  
*item1*[ls -l /usr/bin] >> *item2*[output.txt] = appends redirected output to a file instead of overwriting the file  
cat [file] = reads one or more files and copies them to standard output  

Piplines: The capability of commands to read data from standard input and
sned to standard output  




### VIM

sudo apt install vim.  

vimtutor   

i = insert mode
v = visual mode
:set nu = adds numbers to vi
:set unnu = removes line numbers in vi  
:w = saves files 
SHIFT + zz = (normal) saves and exits.  
hjkl = home row (arrows).  
y = to copy highlighed area 
p = to paste
e = to move to end of words
f (letter) = moves to the next place the letter exists in the current
line  

b = moves backward a letter   
GG = to goes to end of file  
gg = goes to the beginnning of the file

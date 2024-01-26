<!-- Syntax for beautiful comments and readme

Heading
# for H1
## for H2
### for H3
#### for h4


Text style
**your text** for bold
_your text_ for italic
some text [link](https://google.com) — for adding a link
- list item — adding - will bring the list
  ![image](some — image-url).png — this is how you can add an image
  > some text — it will add padding/quote


Code
```javascript
if (isAwesome) {
  return true;
}
``` -->

**Terminal is nothing but another interface to do the things on your machine**

- `pwd` - print working directory
- `cd` - change directory to navigate b/w folders (`cd ../..` : to jump do directories `cd ~` : from any directory to home directory or `cd frontend/scripts` to move into internal directories and we can give absolute path too `cd ~/hello`: this is in home directory and hello there)
- `ls` - listing all the files in the current folder (`-a` for hidden files, `-l` for more details, `-lh` to get size)
- `mkdir` - make directory/folder (`mkdir hello && cd hello` combined command) (`mkdir -p frontend/scripts` recursive make folder inside a folder) -` touch` - to create a file
- `cat` - print content of the file
- `clear` - clear the working space take you to the top of terminal
- `mv` - move files from one folder to other (mv (file/folder name) (place where to move)) or can be used for rename
- `cp` - copy the files (cp -r -copy recursive folder content)
- `grep` - global search for the regualr expression (`ls | grep .js` piping the result of ls flows to next command)
- `rm` filename - delete a file
- `rmdir` foldername - delete a folder
- `chmod` - change file permission (modify the read, write and execute permissions of a file)
- `ls > new.txt` - dump the result of ls to new.txt if you ue again then content will be replaced
- `ls >> new.txt` - to append
- `command1 && command2` - execute first command followed by second one

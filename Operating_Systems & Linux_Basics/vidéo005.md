## Title : Working with VIM Editor

The unix test editor is VIM :
Why do we need VIM ? and How to work with VIM ?

Why do we not use the visual text editor ? (GUI)

<hr>

### Use cases to use text editor in CLI : 

--> Small Modifications can be faster.
--> Faster to create and edit in the same time.
--> support multiple formats
<hr>

### Working with VIM and its commands
sudo apt install vim
cd Documents/java-app (inside java-app you should have a file named Readme.md)
vim Readme.md  // To open file with Vim (inside the file you will have the contenu of your file)

in VIM, we have two modes : Command mode and edit Mode

type "i" key to switch to insert Mode.

and add the text what you want in your file.

after, press **esc** to switch to cammand Mode.

To save the file, type : 

**:wq** and button enter(means write file to disk and quit VIM)

Cat readme.md (to print the content of file and chaeck modfications)

if you tape : 

**:q!** that means quit without changing the changes.

if we want to delete lines in our file, cliq on esc and **dd** to delete on line. You can delete a 10 lines by taping : **d10** to delte a 10 lines.

when you delete 10 lines for exp and you want to undo these changes, you can tape : **u** (to undo)

to go to the end of the line, tape **shift and A** or **shift and 0** to go to the beginning of the line.

to search for exp for the word patter,in the file, tape : **/pattern**

if we want to replace the world nginx in the file(les mots lkol) by the world web-app, tape: **:%s/nginx/web-app**








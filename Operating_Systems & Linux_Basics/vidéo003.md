## Setup a Linux virtual machine

## Part 2 : Basic Linux Commands
pwd : print working directory to show current directory
--> Return par exp : /home/nana

ls : list folders and files

How to go in differnt directories ?

cd Documents 

cd ..
cd / (to go to the root folder)

cd [FolderNameOne]/[FolderNameTwo]/[FolderNameThree]

cd ../.. (to return to the folderNameOne)

cd ~ (to go to the home directory)

How to create a directory ?

mkdir  folder_name

<hr>

**File operations**
How to create a file ?

touch [filename]

How to remove a file ?
rm [filename]

How to delete a non-empty directory and all the files within it ?
rm -r [directory_name]

<hr>

**Navigating in the file system**

**More File and Directory Operations**

mv [filename] [new_filename]  // Rename the file to a new filename

cp -r [dirname] [new_dirname] // Copy dirname to new_dirname

**Some More useful commands**

ls -R Documents  //Afficher le contenu du répertoire courant (ici, Documents), et  tous les sous-répertoires.

history  // gives a list of all past commands typed in the current terminal

to paste copied text into terminal : you can use CTRL + shift + v 

cat [filename] = Display the file content

**Execute commands superuser**

we can't execute for exp this command : 
adduser admin 

to execute this command we must write :
sudo adduser admin





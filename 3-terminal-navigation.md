# Assignment 3 - Terminal Navigation

The terminal lets me control my computer by typing commands instead of clicking. Below is what each command does.

# Commands I learned

**Looking around**
- `pwd` : shows which folder I am in right now
- `ls` : shows the files and folders inside this folder
- `ls -la` : shows everything, including hidden files, with more details

**Making things**
- `mkdir practice` : makes a new folder called practice
- `mkdir -p css/images` : makes a folder inside a folder in one go
- `touch index.html` : makes a new empty file called index.html

**Moving around**
- `cd practice` : goes inside the practice folder
- `cd ..` : goes back one folder
- `cd ~` : goes straight to the home folder

**Copying, renaming, deleting**
- `cp index.html backup.html` : makes a copy of the file
- `mv backup.html old.html` : renames the file (or moves it)
- `rm old.html` : deletes a file
- `rm -r css` : deletes a folder and everything inside it

**Other useful ones**
- `cat index.html` : shows what is written inside a file
- `clear` : cleans the terminal screen
- `code .` : opens the current folder in VS Code

Note: on Windows PowerShell, `touch` is `ni`, `ls -la` is `ls -Force` and `clear` is `cls`.

## Practice exercise

**Task:** Starting from the home folder, make a `website` folder that has `index.html`, a `css` folder with `style.css`, and an `images` folder. Then practice moving around and renaming.

**What I did, step by step:**

1. Go to the home folder:
   `cd ~`
2. Make the folders `css` and `images` inside `website`:
   `mkdir -p website/css website/images`
3. Make the two files:
   `touch website/index.html website/css/style.css`
4. Go inside the css folder:
   `cd website/css`
5. Come back to the website folder:
   `cd ..`
6. See everything inside, including the subfolders:
   `ls -R`
7. Rename index.html to home.html:
   `mv index.html home.html`
8. Rename it back to index.html:
   `mv home.html index.html`
9. Open the folder in VS Code:
   `code .`
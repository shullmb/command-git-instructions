# Navigation Terminal
**cd** -> Change directory
- `cd ~` change directory to Home
**ls** -> Display what is in current dir with short list
**l** -> display complete file info in directory
**pwd** -> present working directory
**open** -> command will open file in default program or dir in finder

# File Manipulation
**man** -> opens manual for commands
- `$ man [command]` - wil display tons of info on command -- `q` to quit
**|** -> pipe executes command on left, then executes command on right
- `$ [command] | [command2]` - does not work for every command
**>** -> redirects output to a file
- `$ echo 'text to add' > [fileName]` - output to directed filename !!will overwrite
- `$ echo 'text to add' >> [fileName]` - output appended to filename
**mkdir** -> create new directory from current position
**touch** -> create new file within current directory
**mv** -> move files
- `$ mv [currentFileName] [newFileName]` - rename file
- `$ mv [filename] ./[newDirectory]/[newFileName]` - move and rename file (newDirectory must exist)
**rm** -> removes files or directories
- `$ rm [fileName]` - removes file from system
- `$ rm -r [directory]` - recursively removes directory and all child directories and files
**grep** -> will search through documents for strings
- `$ cat [fileName]` | grep 'string to search' -- will search contents of
- `-n` - will display line number of found string/s
- `-A [num]` -  will print [num] subsequent lines
- `-B [num]` - will print [num] preceding lines
**cat** -> reads file and outputs to terminal
- `S cat [fileName]` - will display file contents
- `S cat [fileName] [fileName2] ...` - will concatenate and display file contents of multiple files


# Git Commands
**git init** -> this will add a local git repo to a directory
**git status** -> this will show files that are untracked or tracked for next commit
**git add** -> this will add file/files to staging for next commit
- `$ git add [fileName]` - will add individual file to staging
- `$ git add -A` - will add all files to staging
- `$ git add .` - will add all files to staging
**git commit** -> takes staged files and creates save point/commit number
- `$ git commit -m '[meaningful commit message]'` - commits with meaningful status message
**git log** -> shows full log of all commits
**git checkout** -> creates a new branch
- `$ git checkout -b [branchName]` - create new branch and switches to it
- `$ git checkout [branchName]` - switches to that branch

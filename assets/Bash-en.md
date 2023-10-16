# Terminal Guide

## Concepts

-   **Graphical User Interface (GUIs)** - file explorer
-   **Command Line Interface (CLIs)** - terminal
-   **Up/Down** - navigate through command history
-   **~** - user directory (/c/Users/User/)
-   **`** - execute a text editor inside the terminal
-   **ctrl + c** - to escape from any blocking code
<!-- -   \***\*\*\*\*** - wraps everything
-   \***\*(nombre)\*\*\*** - wraps a set -->

## Commands

-   **pwd (print work directory)** - show the current directory
-   **pushd (route name)** - access to another route without losing the current route
-   **popd (route name)** - go back to the previous route
-   **file (file name)** - look at the format of the file
-   **which (command)** - see if a command is installed
-   **history** - shows the history of all executed commands
-   **whoami** - shows the current user
-   **help (command) (--help)** - shows all the commands
-   **clear** - cleans the terminal
-   **ls (list storage)** - files of the current folder
-   **touch (file name) (file name)** - create files
-   **echo "text" > (file name)** - create files with content
-   **cat (file name)** - shows the text content of a file
-   **cat > (file name)** - replace the text content of a file in the terminal
-   **cat >> (file name)** - add text content to a file in the terminal
-   **mkdir (folder name) (folder name)** - create directories
-   **rmdir (folder name) (folder name)** - delete empty directories
-   **rm -r (file name) (file name)** - remove a directory and files within it
-   **rm (file name) (file name)** - remove a file
-   **mv (origin directory) (file name)** - move a file
-   **mv (Old name) (New name)** - rename a file
-   **cp (origin directory) (file name)** - copy a file
-   **find** - search a file (_you can use regular expressions_)
-   **ps** - returns a list of the current processes
-   **kill (ID)** - kills a process
-   **nano (file name)** - open nano editor in the terminal
-   **vim** - open vim editor in the terminal
-   **code (directory route)** - open the current directory in Visual Studio Code
-   **alias** - show the alias of those commands you created
-   **alias (alias)="(command)"** - create an alias
-   **unalias (alias)** - delete an alias

## cd Commands

-   **cd (change directory)** - change to another directory (_To enter a directory that has empty spaces in the name, just wrap the directory's name in "" or put a \ before the space_)
-   **cd ~** - go to the User directory
-   **cd ..** - go to the parent directory of the current one
-   **cd /** - go to the root directory
-   **cd (c/d)** - go to hard drive disks directories (_c/d/etc_)
-   **cd ../../** - go back two parent directories
-   **cd -** - go back to the previous directory

## Tips

> **"command + -letters"** = command option:
>
> -   **-a** - show all files
> -   **-l** - show the specifications of the file
> -   **-a** - show hidden files

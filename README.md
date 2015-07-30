### Bashmarks is a shell script that allows you to save and jump to commonly used directories. Now supports tab completion.

## Install

1. git clone git://github.com/congdepeng/bashmarks.git
2. make install
3. source **~/.local/bin/bashmarks.sh** from within your **~.bash\_profile** or **~/.bashrc** file

## Shell Commands

    save_mark <bookmark_name> - Saves the current directory as "bookmark_name"
    f <bookmark_name> - Goes (cd) to the directory associated with "bookmark_name"
    print_mark <bookmark_name> - Prints the directory associated with "bookmark_name"
    delete_mark <bookmark_name> - Deletes the bookmark
    list_mark                 - Lists all available bookmarks
    
## Example Usage

    $ cd /var/www/
    $ save_mark webfolder
    $ cd /usr/local/lib/
    $ save_mark locallib
    $ list_mark
    $ g web<tab>
    $ g webfolder

## Where Bashmarks are stored
    
All of your directory bookmarks are saved in a file called ".sdirs" in your HOME directory.

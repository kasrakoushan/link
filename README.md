# link
A shell script for easily-accessible web bookmarks

# Installation

Just save Link somewhere on disk and add its path to your .bash_profile file. Wherever you save it, also add empty text files called links and names.

# Commands

## list
```link list```
Lists all of the keywords you've saved.

## add
```link add [keyword] [link]```
Adds a particular link/keyword combination to your list. Be sure the link starts with http://, or else the script will think you're referring to a file on disk.

## remove
```link remove [keyword]```
Removes a given keyword from your list if it exists.

## go to link
```link [keyword]```
Opens the web link (or file) that the keyword refers to.

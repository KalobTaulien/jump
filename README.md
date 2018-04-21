# Jump

I've been using this tool for quite some time. When I first went to Ubuntu OS I _loved_ this tool, [made by Jeroen Janssens](http://jeroenjanssens.com/2013/08/16/quickly-navigate-your-filesystem-from-the-command-line.html). But the autocomplete doesn't seem to work on Macbook Pros so with the help from [thornycrackers](https://github.com/thornycrackers) we got it working for Mac OS. 

## Installation
Throw the `jump.sh` contents into your `.bashrc`, `.bash_profile` or `.profile`, which ever one you use most or prefer then source your file, ie. `source ~/.bash_profile`

## Usage
Open your terminal and `cd` into a directory you want to bookmark. Type `mark shortcutname`. Now from any directory you can type `jump shortcutname` and immediately be brought to the marked (bookmarked) directory. 

Use `marks` to list all the bookmarks you have.
Use `unmark shortcutname` to remove a bookmark. 
Use `jump shortcutname` to jump to your bookrmarked directory.
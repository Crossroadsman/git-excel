git-excel
=========

Note: keep an eye on [git-xltrail](https://github.com/xlwings/git-xltrail), a git extension for handling Excel files. 
It currently only works on Windows.

What it Is
----------

Tweaks to improve quality of life when using git for Excel version control.

Specifically, this currently tells git to treat `xlsx` files as `zip` and then to use `unzip` on these files before 
performing a diff.



Installation
------------

### In the Repo To Be Managed ###

Edit the `.gitattributes` file in the repo. Add the contents from this repo's `.gitattributes`.

### At the User Profile level ###

Edit `~/.gitconfig`. Add the contents from this repo's `.gitconfig`.

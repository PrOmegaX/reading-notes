​***GIT/VERSION CONTROL***

To understand GIT you need to understand version control first.
Verison control allows you to go back and see privious files,
or to simple set files by recording any changes that you make.

**GIT** itself is a DVCS which stands for DISTRIBUTED VERSION CONTOL
if a centrailzed version contol shut down then colloborating users can
no longer collaborate on files and cant save changes or new versions,
if the hard disk gets currpted theres a chance to loose everything aswell
GIT being a DVCS once again allows its clients repositories to be mirrored 
your data/backups can be put directly into the server + replace lost infomantion.

Commands if you need help
git help command
git command --help
man git-command

cd test (cd = change directory)
git add *.c
git commit -m “any message here”

If you want to create a clone of an all ready existing repo or to copy all versions 
of the file for your project into your hardrive you can use the code:

git clone https://github.com/test

and this code to save into your directory

$ git clone https://github.com/test mydirectory

vim-latex
=========

Mirror of vim-latex from Sourceforge (http://sourceforge.net/projects/vim-latex/files/snapshots/)
Homepage: http://vim-latex.sourceforge.net/index.php?subject=manual&title=Manual#user-manual

Current Version: vim-latex-1.8.23-20130116.788-git2ef9956.tar.gz (287.7 kB)


Installation Instructions
Step 1 of 4: Download and extract the archives
Extract one of the archives above into your ~/vimfiles directory (if you are using windows) or ~/.vim directory (if you are using *nix).

If you are updating after a long time, it might be a good idea to remove the ~/vimfiles/ftplugin/latex-suite directory from previous installations before reinstalling.

NOTE: If you already have some latex ftplugin files, read the Advanced Installation Instructions to make sure you do not over-write any of your files.
Step 2 of 4: Set a few things in .vimrc
The recommended settings for vim-latex in your .vimrc file are now only described in the vim-latex manual.
Step 3 of 4: Install the help files
To install the included latex-suite.txt and latexhelp.txt files as vim help files, start vim and do the following:

helptags ~/.vim/doc     (for *nix users)
helptags ~/vimfiles/doc     (for windows users)
Step 4 of 4: Done!
Thats it! You are done! Now start editing a latex file in vim. Latex-Suite should start up automatically. You can do

:help latex-suite.txt

from within vim to get the online Latex-Suite reference. 


Vim Omnicompletion Template using Python
========================================

Author: Sean Reifschneider <jafo@tummy.com>  
2011-11-29  
Placed into the Public Domain

Introduction
------------

Vim Omnicompletion is an extremely powerful tool, but I spent quite a
lot of time initially figuring out exactly how to make it happen.  Part
of that was due to being only somewhat familiar with the vim scripting
language, so I really wanted to write it in Python.

My goal with this template is to make it dead simple for a Python
programmer to create Omni-completion functions for vim.

To Use
------

   * Copy this file in "~/.vim/plugins".

   * Rename this file to a new name, likely called something about what
   you are completing and "complete".  For example, the completion
   for Python in vim is stored in a file called "pythoncomplete.vim".

   * Search for "@@@" in this file and make the changes mentioned.

   * Start up vim and do ":set omnifunc=YOURFILENAME#Complete" where
   "YOURFILENAME" is the name of the file you created in step 1 above.

   * Start typing something and then type Control-X Control-O to bring
   up the completion menu.

If you've had good or bad luck with this, please let me know!

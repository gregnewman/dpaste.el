=====================================
dpaste.el - Emacs mode for dpaste.com
=====================================


git clone git://github.com/gregnewman/dpaste.el.git and add to your .emacs

or 

git submodule add git://github.com/gregnewman/dpaste.el.git vendor/dpaste


**M-x dpaste-buffer**

Will post the current buffer to dpaste.com and put the curl to the paste in the kill-ring

**M-x dpaste-region-or-buffer**

Will post the marked region or current buffer to dpaste.com and put the curl to the paste in the kill-ring

**TODO:**

Finish adding support for additional fields; language, poster, title

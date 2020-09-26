# HW01: Text Editor Tutorials

Name: <Michael Bonds>
Course: <Effective Programming>

## Vim

#### Question 1
Vim's user-specific configuration file is located in the home directory: ~/. vimrc , and Vim files of current user are located inside ~/. vim/ . The global configuration file is located at /etc/vimrc . You may be lucky enough to have syntax highlighting already switched on in your version of Vim. If not, edit a vimrc file (either /etc/vimrc or, preferably,.vimrc in your home directory) 
#### Question 2
Vim isn’t limited to what you get “out of the box.” It’s possible to extend Vim pretty heavily, and many people have added features to Vim far and above plain old text editing.
A plugin is loaded automatically when Vim starts.
#### Question 3
Using Vundle. 
## Emacs

#### Question 1
When Emacs is started, it normally tries to load a Lisp program from an initialization file, or init file for short. This file, if it exists, specifies how to initialize Emacs for you. Emacs looks for your init file using the filenames ~/.emacs, ~/.emacs.el, or ~/.emacs.d/init.el; you can choose to use any one of these three names (see Find Init). Here, ~/ stands for your home directory.
https://www.gnu.org/software/emacs/manual/html_node/efaq-w32/Location-of-init-file.html
https://www.emacswiki.org/emacs/InitFile

#### Question 2
The Emacs editor predates Linux, and was once far more popular, but it has fallen into relative obscurity over the years. In a mega-thread on the emacs-devel mailing list, participants discussed various ideas for making Emacs more "attractive", in both aesthetic and in "appealing to more users" senses of that term. Any improvements to Emacs in that regard have numerous hurdles to overcome, however. There are technical questions and, naturally, licensing considerations, but there is also the philosophical question of what it is, exactly, that stops the venerable text editor from being more popular.
Yes, Emacs have a plugin. Their plugins are known as "Add-ons".

#### Question 3
Ropemacs (Custom) : A refactoring library
    - Auto Completion with rope (Custom) : Tested to work well with Rope
    - Flymake + pyflakes (Custom): Highlight errors on the fly, improved
      from the standard version
    - Virtualenv : Original, In-development tool for using virtualenv in
      emacs.
    - Custom Yasnippet Snippets
    - Cython Mode: a mode for highlighting cython files
    - latest python.el (fgallina/python.el)
    - nosetests integration (nose.el)


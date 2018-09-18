# vim-config
my vim config to share amongst my machines

In Ubuntu/Lubuntu 16.04, I have success with installing vim-gnome-py2

sudo apt-get install vim-gnome-py2
My vim --version | grep python after installing it:

$ vim --version | grep python
+cryptv          +linebreak       +python          +vreplace
+cscope          +lispindent      -python3         +wildignore
You may need to remove other packages such as vim-gnome, vim-gtk, vim-nox ... to avoid conflicts.

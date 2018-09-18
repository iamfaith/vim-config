# vim-config
my vim config to share amongst my machines

In Ubuntu/Lubuntu 16.04, I have success with installing vim-gnome-py2

sudo apt-get install vim-gnome-py2
My vim --version | grep python after installing it:

$ vim --version | grep python
+cryptv          +linebreak       +python          +vreplace
+cscope          +lispindent      -python3         +wildignore
You may need to remove other packages such as vim-gnome, vim-gtk, vim-nox ... to avoid conflicts.

install requests first

For python3:-  sudo python3 -m pip uninstall pip && sudo apt install python3-pip --reinstall.

By this , you can simply install packages using pip3. to check use pip3 --version.

For older versions, use : sudo python -m pip uninstall pip && sudo apt install python-pip --reinstall.

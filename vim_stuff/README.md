## Some vim spice & souce for setting up from scratch:

**First step:**
`mkdir -p ~/.vim/Vundle`

**Second step**: Install Vundle

`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

**Third Step**: Clone my .vimrc

**Fourth Step**: Installing all plugins mentioned in .vimrc

Enter vim and enter:
`:PluginInstall`

**Fifth Step**: Installing Meslo fonts
should grab the fonts from : https://github.com/powerline/fonts/tree/master/Meslo

and install it in directory: /usr/share/fonts/opentype,

don't forget to rebuid the font cache. simply enter: `sudo fc-cache -fv`

**My workspace after setting things up:**

![screen_shot_example](https://cloud.githubusercontent.com/assets/1729719/19620899/237071ea-988f-11e6-94df-464e08fa6608.jpg)

# nvim-config

#install neovim 

```bash
Sudo dnf install neovim
```

#install vimplug 

```bash
curl -fLo ~/.var/app/io.neovim.nvim/data/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

```

#install configuration

Create the "nvim" directory inside .config on your home directory, and paste the init.vim inside.

#install plugins

Inside neo-vim execute the commands 

```
:PlugInstall
```

that command will install all the plugin listed on the init.vim file, this file is executed every time you open a new nvim instance.




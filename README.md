# local-bin
here resides the local bin scripts for my linux systems

### first create the folder required

```shell
mkdir -p ~/.local/bin
```

### clone repository

```shell
git clone https://github.com/vishmaycode/local-bin.git ~/.local/bin
```

### add local bin to path in .bashrc

```shell
export PATH="$HOME/.local/bin:$PATH"
```

### necessary permissions

```shell
chmod +x ~/.local/bin/*
```

Scripts
1. flameshot-save - is a screenshot tool flameshot's extension to save the files to ~/Pictures/Screenshots after clicking using Ctrl + PrintScr
2. ssh-manager - is a ssh manager which saves the endpoints in ~/.config/ssh-manager/config to easy the process of remembering multiple ssh endpoints
3. tmux-sessionizer - is a fork of tmux sessionizer by The Primeagen [https://github.com/theprimeagen/tmux-sessionizer](https://github.com/theprimeagen/tmux-sessionizer), tailerd for my directory structure

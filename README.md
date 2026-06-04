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

### add local bin to path in .bashrc/.zshrc

```shell
export PATH="$HOME/.local/bin:$PATH"
```

### Scripts
1. ssh-manager: Manages SSH endpoints, storing them in ~/.config/ssh-manager/config for easy access to multiple SSH connections.
2. ssh-forwarder: Manages SSH port forwarding, storing them in ~/.config/ssh-forwarder/config for easy access.
3. smartmux: A tmux session manager inspired by tmux-sessionizer by ThePrimeagen [https://github.com/theprimeagen/tmux-sessionizer](https://github.com/theprimeagen/tmux-sessionizer). It adds support for custom tmux layouts: just add a .tmux-layout bash script in your project folder, and smartmux will load it on session start. Example .tmux-layout included in the repo.
4. switchhost: This is a simple script to switch between two host file entries for when I am connected to home network or outside network
5. flameshot-save: A screenshot tool extension for Flameshot to save files to ~/Pictures/Screenshots and also clipboard using Ctrl + PrintScr (set manually).
6. hyperland-save: A screenshot tool extension for hyperland to save files to ~/Pictures/Screenshots and also clipboard using Ctrl + PrintScr (set manually).


### Licensing
- All code in this repository is licensed under the Apache License 2.0 (see LICENSE file).

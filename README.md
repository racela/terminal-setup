# terminal-setup
How I setup my terminal using neovim and tmux

## Install NeoVim
`$ sudo apt-get update` <br>
`$ sudo add-apt-repository ppa:neovim-ppa/unstable` <br>
`$ sudo apt-get install neovim`

## install tmux
`$ sudo apt-get install tmux`

## Clone files and move to HOME directory
`$ cd /tmp && git clone https://github.com/racela/terminal-setup` <br>
`$ mv -r /tmp/terminal-setup/.config ~` <br>
`$ mv -r /tmp/terminal-setup/.tmux.conf ~`

## Install win32yank
`$ curl -sLo/tmp/win32yank.zip https://github.com/equalsraf/win32yank/releases/download/v0.0.4/win32yank-x64.zip` <br>
`$ unzip -p /tmp/win32yank.zip win32yank.exe > /tmp/win32yank.exe` <br>
`$ sudo apt install unzip` <br>
`$ unzip -p /tmp/win32yank.zip win32yank.exe > /tmp/win32yank.exe` <br>
`$ chmod +x /tmp/win32yank.exe` <br>
`$ sudo mv /tmp/win32yank.exe /usr/local/bin/`

## Install build-essential
`$ sudo apt-get install build-essential` <br>

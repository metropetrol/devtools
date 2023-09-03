### My dev tool setup
This is how to setup my preferred dev tools.

#### Install the following
1. zsh, `brew install zsh`
1. [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh#prerequisites)
1. [powerlevel10k](https://github.com/romkatv/powerlevel10k#getting-started)
1. helix, `brew install helix`
1. zellij, `brew install zellij`

#### Copy the config files to their respective places:
1. zellij, copy files to `~/.config/zellij` 
1. helix, copy files to `~/.config/helix`
1. copy zsh config to `~/.zshrc`, `cat zsh/zshrc >> ~/.zshrc`

#### Configure some tools:
1. powerlevel10k, `p10k configure`
1. git
```
git config --global --set pull.rebase true
git config --global --add alias.dag "log -n 20 --graph --all --format='format:%<|(1)%C(yellow)%h%C(reset) %<|(1)%C(blue)%an%C(reset) %<|(1)%C(magenta)%as%C(reset)%C(auto)%d%C(reset)%n%s' --date-order"  
```

## Install basic dev applications - git, curl

```
sudo apt install curl
sudo apt install git
sudo apt-get install build-essential libssl-dev
curl https://raw.githubusercontent.com/creationix/nvm/v0.25.0/install.sh | bash
```

## Install zsh and oh-my-zsh
```
sudo apt install zsh
chsh -s $(which zsh)
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install custom fonts
```
mkdir -p ~/.local/share/fonts
cd ~/.local/share/fonts && curl -fLo "Droid Sans Mono for Powerline Nerd Font Complete.otf" https://github.com/ryanoasis/nerd-fonts/raw/master/patched-fonts/DroidSansMono/complete/Droid%20Sans%20Mono%20Nerd%20Font%20Complete.otf
```
Set terminal font to droid sans

## Download lsd ls extension
Navigate to [Peltoche/lsd](https://github.com/Peltoche/lsd/releases) and follow the install steps specific to your operating system.
```
sudo dpkg -i lsd_0.16.0_amd64.deb
```

Replace your dotfiles with the ones provided in this repository.
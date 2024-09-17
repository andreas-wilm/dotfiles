# My dotfiles

# To set up

ln -s $(pwd)/tmux.conf ~/.tmux.conf

ln -s $(pwd)/starship.toml ~/.config/starship.toml

ln -s $(pwd)/kickstart.nvim ~/.config/nvim

ln -s $(pwd)/alacritty/ ~/.config/alacritty

git pull --recurse-submodules

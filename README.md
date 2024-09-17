# My dotfiles

# To set up

ln -s $(pwd)/tmux.conf ~/.tmux.conf

ln -s $(pwd)/starship.toml ~/.config/starship.toml

ln -s $(pwd)/kickstart.nvim ~/.config/nvim

ln -s $(pwd)/alacritty/ ~/.config/alacritty

# on init only
git submodule update --init --remote --recursive
# otherwise
git pull --recurse-submodules

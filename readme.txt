xrdb -merge .Xresources

for installing:
sudo pacman -Syyu <package>

for deleting:
sudo pacman -Rns <package>

for searching packages:
sudo pacman -Ql <package>

to look at contents of this repo
tree -a -I '.git'

if Xmodmap not loaded for some reason (for swapping ctrl, caps)
xmodmap ~/.Xmodmap

for getting ohmyzsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

for getting vundle
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

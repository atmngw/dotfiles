# installation

## vim
clone .vimrc and .vim/

git clone https://github.com/Shougo/neobundle.vim ~/.vim/bundle/neobundle.vim

execution :NeoBundleInstall in vim

cd ~/.vim/dict
wget https://raw.github.com/Cside/dotfiles/master/.vim/dict/perl.dict
wget https://raw.github.com/Cside/dotfiles/master/.vim/dict/php.dict

mkdir ~/.vim/snippets
git clone https://github.com/honza/vim-snippets.git snippets

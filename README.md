# Cara Install vim di termux 
apt install vim nodejs-lts git curl -y

# install coc
mkdir -p ~/.vim/pack/coc/start
cd ~/.vim/pack/coc/start
git clone --depth=1 --branch release https://github.com/neoclide/coc.nvim.git

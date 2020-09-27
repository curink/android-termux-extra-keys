# termux extra keys

mkdir -p ~/.termux && cd .termux && wget https://raw.githubusercontent.com/curink/termux-extra-keys/master/termux.properties

# atau

mkdir $HOME/.termux/ ;echo "extra-keys = [['ESC','/','-','HOME','UP','END','PGUP'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1

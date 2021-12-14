# termux extra keys
```bash
mkdir -p ~/.termux && cd .termux && wget https://raw.githubusercontent.com/curink/termux-extra-keys/master/termux.properties
```
# atau
```bash
mkdir $HOME/.termux/ ;echo "extra-keys = [['ESC','/','-','HOME','UP','END','PGUP'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1
```

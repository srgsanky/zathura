# Using this configuration

```bash
mkdir -p ~/.config/zathura/

git clone https://github.com/srgsanky/zathura.git ~/.config/zathura
```

## Install Zathura in Mac

```bash
brew tap zegervdv/zathura
brew install girara --HEAD
brew install zathura --HEAD --with-synctex
brew install zathura-pdf-poppler
mkdir -p $(brew --prefix zathura)/lib/zathura
ln -s $(brew --prefix zathura-pdf-poppler)/libpdf-poppler.dylib $(brew --prefix zathura)/lib/zathura/libpdf-poppler.dylib
```

The above commands are from <https://github.com/lervag/vimtex/blob/b8bb79b5fb27e9030ade92e75cd9375416f2c666/doc/vimtex.txt#L6729>


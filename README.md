# dotfiles-installer

## Command Line Tools (macOS only) 

xcode-select --install 

## Git install 

cd ~ && git clone --depth=1 https://gitlab.com/yozz/dotfiles.git && dotfiles/bootstrap 

## Curl install 

cd ~ && curl -sL https://github.com/yozzi/dotfiles-installer/archive/master.tar.gz | tar xz && cd dotfiles-installer-master && ./install && cd ~

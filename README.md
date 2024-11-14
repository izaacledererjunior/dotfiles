# dotfiles

Dependências 

Instalar MesloFonts no Ubuntu
wget -P ~/Downloads https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/Meslo.zip
unzip ~/Downloads/Meslo.zip -d ~/Downloads/MesloNerdFont
mkdir -p ~/.local/share/fonts
mv ~/Downloads/MesloNerdFont/*.ttf ~/.local/share/fonts/
fc-cache -fv
fc-list | grep "MesloLGS"



# Programas I3WM 

-> pavucontrol 
-> flameshot 
-> simplescreenrecord
-> zsh 
-> gtop
-> https://github.com/betterlockscreen/betterlockscreen



# Configurações Gerais

-> Apenas usuário root, sem usuário sudo


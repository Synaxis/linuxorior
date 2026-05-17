ubuntu 26 terminal icon to normal 
mkdir -p ~/.local/share/applications && cp /usr/share/applications/org.gnome.Ptyxis.desktop ~/.local/share/applications/ && sed -i 's/^Icon=.*/Icon=utilities-terminal/' ~/.local/share/applications/org.gnome.Ptyxis.desktop && update-desktop-database ~/.local/share/applications/

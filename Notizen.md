# TODO-Liste

- Notizen Datei adden
- Notizen Datei pushen
- ROM bauen aus Infos in lokalem Clone
- Kleinigkeit ändern im Code
- ROM mit kleiner Änderung bauen
- Github Turorial beenden (siehe unten)

# Informationen

Debian Daten		    Name = aaa	PW = bbb
Youtube Tutorials	    https://www.youtube.com/watch?v=q0H_22K9f9Q&list=PLLNv9Lq6kDmTIYfN5NvgQRvfOHTOXl0uU&index=2
Pokeemerald Extension	https://rh-hideout.github.io/pokeemerald-expansion/index.html
Github Tutorial         https://github.com/TeamAquasHideout/Team-Aquas-Asset-Repo/wiki/The-Basics-of-GitHub

## ROM erzeugen

Debian öffnen
Alles einmal updaten		sudo apt update && sudo apt upgrade
Diesen Ordner einhängen 	cd /mnt/c/Users/Jo/Desktop/Emerald
nproc Wert auslesen		    nproc
ROM bauen   		        make -j[nproc number]
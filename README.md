# Firewalld_Games
This repository contains firewalld services for various games.


## Usage
To install a service, copy the XML file to ```/etc/firewalld/services/```

To enable a service, execute the following commands:
```
firewall-cmd --add-service=<SERVICE> --zone=<ZONE> --permanent
firewall-cmd --reload
```

To disable a service, execute the following commands:
```
firewall-cmd --remove-service=<SERVICE> --zone=<ZONE> --permanent
firewall-cmd --reload
```

See [firewalld documentation](https://firewalld.org/documentation/) for more details.
## Games
* [0 A.D](https://play0ad.com/)
* Anno 1602
* [Anno 1800](https://www.ubisoft.com/de-de/game/anno/1800)
* [Factorio](https://www.factorio.com/)
* [Minecraft](https://www.minecraft.net)
* [Sid Meier's Civilization IV](https://civilization.com/civilization-4/)
* [Sid Meier's Civilization V](https://civilization.com/civilization-5/)
* [Stellaris](https://www.paradoxinteractive.com/games/stellaris)
* [Stronghold Crusader](https://fireflyworlds.com/games/strongholdcrusader/)
* [SuperTuxKart](https://supertuxkart.net/Main_Page)
* [Terraria](https://terraria.org/)
* [The Settlers History Collection](https://www.ubisoft.com/en-us/game/the-settlers/history-collection)
* [Zero-K](https://zero-k.info/)


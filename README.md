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
* [Factorio](https://www.factorio.com/)
* [Minecraft](https://www.minecraft.net)
* [Stellaris](https://www.paradoxinteractive.com/games/stellaris)
* [Stronghold Crusader](https://fireflyworlds.com/games/strongholdcrusader/)
* [SuperTuxKart](https://supertuxkart.net/Main_Page)
* [Terraria](https://terraria.org/)


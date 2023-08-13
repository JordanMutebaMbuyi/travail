## README tpcalculateur.bash 
Programme d'installation tpcalculateur.bash

MUTEBA  MBUYI  Jordan 
MAMBAKA  NDONGALA Theo 
KABUO   HANGI   Grace 
NZANZU YIBIFU    Asser 
MBAYI  OLEMI    Jacques 
NTANGU  NSINGA   Jérémie 
MASONSA  BAVUIDINSI   Christian 
LUMBU  LEKA Grady 
KAMANGO  BETSHINDO   Alberto 
NKAN BISSION   Jérémie 
 etudiants L2 (Génie-Info, 2021-2022) Dr. Christian Bope

## Objectif ##

Création d'un package regroupant les différents logiciels nécessaire sur toutes les Distributions dérivées du DEBIAN avec un très large choix de paquets pour les Mathématiciens  et Informaticiens.

Comme avantages :

- Ce large choix de logiciel est accessible directement au sein d'une interface graphique unifiée ;
- Il y a une description de chaque logiciel directement dans l'interface ce qui vous permet de voir au premier coup d'œil ce qui peux vous intéresser ou non,
- Simple à utiliser : pour installer les logiciels, il suffit juste d’insérer  les numéros correspondants,
- Intègre différentes méthodes d'installations (installation via apt install, installation d'un paquet deb récupéré sur le site de l'éditeur, installation via un PPA ou le dépot de l'éditeur, installation via un Snap, installation avec Flatpak et le dépot Flathub, récupération au format AppImage, installation via un script etc...
(À noter que pour ceux qui n'aiment pas les paquets universels, sachez qu'aucun n'est coché par défaut et que, quand un logiciel est proposé en paquet universel, c'est explicitement indiqué dans le nom lors du choix).


## Compatibilité ##

Le script est destiné principalement à la version de base des distributions dérivées debian (Gnome).
Cela ne veut pas dire qu'il ne peut pas être utilisé sur une autre configuration mais qu'il a été testé/validé surtout pour celle-ci.

- Ce script est fait pour "Bash" (shell par défaut sous Ubuntu) mais pas pour les autres Shell donc si vous l'avez modifié manuellement sur votre Ubuntu pour mettre, par exemple, "Zsh" à la place, le script ne fonctionnera pas correctement (certaines fonctions non-compatibles).

- Si vous souhaitez utiliser le script sur une variante d'Ubuntu plutôt que la version de base (par exemple Xubuntu, Kubuntu, Ubuntu Mate, Linux Mint, ElementaryOS...), je vous recommande fortement au lancement de bien choisir l'option "Tous les choix décochés" par défaut afin de ne pas avoir des paquets utiles pour Gnome uniquement cochés par défaut (ce qui n'aura aucun intérêt pour vous vu que vous n'utilisez pas Gnome avec votre variante). Si vous utilisez KDE (notamment avec Kubuntu ou KDENeon), attention à bien cocher des logiciels cohérents avec cet environnement.

## Récupération / Lancement du script

Il y a 2 méthodes :

- Premiere methode: Télécharger le contenu du script (répertoire tpcalculateur.bash) sur ce github (soit par l'interface web soit via la commande wget), décompresser le contenu, penser à mettre le droit d'execution sur le script et lancer le "tpcalculateur.bash" à l'intérieur sans sudo (les sudo se trouvent à l'intérieur du script). En ligne de commande, cela donne donc :

> wget https://github.com/.... (donc le lien)
> unzip unikin.zip && 
> cd Unikin_Pack-v1.0/ && chmod +x Unikin_Pack-v1.0.sh &&
> ./Unikin_Pack-v1.0.sh

- Deuxieme methode: utiliser git clone (avec l'avantage de pouvoir faire la mise a jour du script sans le retélécharger manuellement). Il vous faudra en pré-requis avoir installé git (sudo apt install git).

> installer git (sudo apt install git) 
> git clone https://github.com/cdbope/unikin.git && cd Unikin_Pack-v1.0/ 
> chmod +x Unikin_Pack-v1.0.sh (droit d'excution du fichier shell)
> ./Unikin_Pack-v1.0.sh

Avec la deuxieme methode, si vous voulez réutiliser le script plus tard et vérifier si il y a pas eu une nouvelle mise a jour du script entre temps, dans le dossier du script, il suffira de faire :
> git pull





***Bonne installation Unikin_Pack-v1.0 ! ;-)***




Contact: christia.bope@unikin.ac.cd et jordanmuteba22@gmail.com

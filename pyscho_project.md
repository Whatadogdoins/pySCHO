# Comment coder un jeux de rôle en python?
## Définition d'un jeux de rôle
RPG = un personnages + des stats + un niveau + des équipements + des épreuves
## Notre jeux de rôle
### Des épreuves basées sur le combat et les enigmes

exemple d'énigme : le labyrinthe

**combat** : possibilité de coruption (don d'or = évité combat); possibilité de persuation (dépend du charisme du personnage). Si persuation ou corruption réussie alors on évite le combat sinon on a un malus pendant le combat. les monstres on un attribut résistance a la persuation et un attribut résistance a la corruption. !TO CODE!
les statistiques du personnage sont modifié par son équipement pour le combat.

### Monde

!TO WRITE! elf; gobelins == fantasy...


### Histoire

Histoire : Deux empires qui sont en guerre sur un grand continent ; autres îles domniée par des barbares; une île est possédée par un roi viking et des jarls / earls(conte); 

- La fôret de la tentation : reliée au désert par le sud et aux montagnes par le sud ouest.
- région du désert: reliée à la jungle par le sud ouest aux montagnes par l'ouest.
- région des montagnes: 
- région des marais: 
- région de la jungle: reliée au montagnes par le nord aux désert par le nord est et au marais par l'ouest.
- région scandinave (archipelle): reliée au montagne par l'est et au marais par le sud est et de loin à la forêt de la tentation au nord est (mais c'est loing).
## gestion du code
gestion des modifications (historique + travail en commun) grâce au protocole git et au site github.
github permet aussi de gerer les bugs et les demande d'amélioration des utilisateurs (issues).

## Stockage des données
utilisation d'une base de donnée SQL. !TO WRITE!
importation vers python via du CSV

### Pourquoi une base de donnée plutôt que des multiple tableaux ?
!TO WRITE!

## Python
### Gestion du parcour
6 zones (régions) avec chacune un réseaux d'événnement (combat, énigme, rencontre).

### Programmation orienté objet
#### Utilisation des *class*
!TO DO MERMAID CLASS!
- méthode
- accesseur
- mutateurs

*class* monstre:

*class* personnage:
- equipement (coder sous formes de dictionnaires en fonction des emplacements sur le code) !TO CODE!

## Perspective
graphisme avec TKINTER ou Turtle.

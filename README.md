# UnrealPlatformerBluePrint
Introduction to blueprint of unreal engine with simple platformer

## TODO list (French)
- Camera :
- [x] Le joueur contrôle une caméra third person avec la souris ou le gamepad

- [x] La caméra ne doit pas passer au travers de l’environnement et revenir à sa place de
manière “smooth”

- Player :
- [x] Le joueur peut déplacer son personnage dans l’environnement avec les touches W,
A, S, D (déplacement avant, gauche, arrière et droite dans le référentiel de la
caméra)

- [x] Le joueur doit toujours s’orienter dans la direction vers laquelle il se déplace, il ne
doit pas straffer ni marcher en arrière.

- [ ] Les différents réglages (vitesse, saut, air control…) sont à régler afin qu’ils soient le
plus agréables possibles

- [ ] Le joueur démarre avec 5 points de vie (tweakable dans l’éditeur

- [ ] Le joueur pourra se débarrasser de ses ennemis en leur sautant sur la tête, et
seulement sur la tête

- [ ] Le reste du temps, une collision direct avec ennemi lui infligera au moins 1 point de
dégâts

- [ ] Si le joueur perd tous ses points de vie, on affichera un “game over” à l’écran. Appuyer sur une touche réinitialisera le niveau.

- Ennemis :
- [ ]  Dans le niveau, des ennemis pourront soit être placés, soit spawnés depuis des
points précis.

- [ ] Le comportement de base sera un déplacement direct vers le joueur afin d’entrer en
collision avec celui-ci, lorsqu’il entrera dans sa zone de détection (réglable depuis
l’éditeur)

- [ ] L’ennemi de base n’aura qu’un point de vie

- [ ] D’autres ennemis, plus avancés, auront 2 points de vie. S’ils sont blessés par le
joueur ils retourneront se cacher vers leur point de spawn où ils pourront récupérer leur point de vie en restant immobile 5 secondes

- [ ] Un ennemi tué laissera à sa place une coeur que le joueur pourra récupérer pour regagner un point de vie

- Collectibles :
- [ ] Des coeurs seront réparties dans tout le niveau et seront droppées par les ennemis
tués. Le joueur pourra les ramasser en passant simplement dessus.

- Niveau :
- [ ] vous devez créer un niveau procurant une boucle de jeux de 5 minutes min avec des
plateformes mais aussi des zones de dégâts (pointes, lave, feu…)

- [ ] Vous pouvez utiliser soit des brushes soit l'éditeur de terrain. ( pas obligatoire)

- [ ] Des bumpers seront placés à des endroits judicieux afin de permettre d’accéder à
des plateformes en hauteur. Lorsque le joueur entre en contact avec eux, il
effectuera un rebond physique, soit dans une direction réglée dans l’actor bumper,
soit en miroir de son déplacement initial.

- [ ] Vous devez gérer correctement les collisions afin que le joueur ne puisse pas tomber
du niveau

- HUD :
- [ ] Un HUD, simple, indiquera le nombre de points de vie restants

- Features additionnelles :
- [ ] temps limité pour finir le niveau
- [ ] Un tableau des meilleurs scores
- [ ] Un ou des niveaux supplémentaires
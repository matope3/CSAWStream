
# Réalisation STREAM CSAW idées

## ***ATEM <-> OBS :***

- Utiliser l'ATEM **uniquement** pour gérer les caméras en cut semble être le plus pratique

- Sur OBS on aura alors **une seule** source **vidéo** provernant de l'ATEM

- Pour gérer les video à diffuser, tout se fera sur OBS. Grâce à ça le lancement sera synchronisé avec le changement de scène (contrairement au petit boitier que nous a montré Fred ou il fallait réussir à lancer la bonne vidéo à la main au bon moment ...)

- Pour gérer les scene d'OBS et potentiellement de l'ATEM en même temps en fonction des besoins on pourra utiliser **BitFocus Companion** (j'en reparle plus tard)


## ***OBS :***

- OBS dispose d'un fonction **multi-view** comme l'ATEM qui sera bien pratique pour voir toutes les scenes en même temps

- Un mode studio est aussi disponible avec la fonctionnalité de **Preview & Program** qui sera nécessaire pour ne pas changer de scene par erreur ou être sur de balancer le bon contenu en le prévisualisant. (l'ATEM n'aura pas le même mode de changement de scene car les caméra doivent juste être cut, ça doit être rapide)


## ***Le son :***

- Je pense que le son doit être découplé de l'ATEM et les cam, pour que l'ingé son soit tranquille à gérer les micro sur la table de mix pendant que le réal gère les cam et les scènes.

- Il faudrait tester la ptite Alesis du coup en usb voir ce que ça donne avant vu que c'est le seul truc qu'on a pas testé et dans le pire des cas on branchera les micro comme on l'avait fait sur les cam mais dans ce cas il faudra config un controlleur midi pour au moins controller le son autrement qu'à la souris


## ***BitFocus Companion :***

- En gros ça permet **d'émuler un stream deck** (c'est aussi compatible avec les vrais stream deck).

- un serveur tourne sur le pc qui run OBS et BlackMagic (ATEM) en se connectant à eux on peut alors avoir des preset de boutons et des variables disponibles en fonction de ce qui est fait qu'on dispose sur des pages comme un stream deck

- Via une tablette, ou n'importe quel peripherique on peut s'y connecter pour avoir la page du stream deck

C'est très mal expliqué mais **très cool**.

***Petit détail :*** *Pour l'utiliser avec OBS il faut la version 27.x et pas 28.x car la 28.x à le plugin websocket-obs v5 nativement, BitFocus n'aime pas cette version et fait des connexions en boucles.
Il faut avoir du coup OBS 27.x et installer le plugin websocket-obs v4.x pour avoir une connexion stable entre les deux.*


## ***DA :***

- Il faudrait être fixé sur qui s'occupe de la DA ...

- Je suis chaud pour faire des ptits sources web dynamiques/animées (j'ai vite fait commencé)

- Il faudrait faire une **transition WebM** quali aussi (avec after effect c'est le plus ~~simple~~ performant)

- L'idée ça serait aussi d'avoir une genre de charte graphique / musicale

	- Sur le site du CSAW :

		- Noir : #000000  $\color{#000000}\blacksquare$

		- Bleu : #12B6B5 $\color{#12B6B5}\blacksquare$

		- Violet : #512B67 $\color{#512B67}\blacksquare$ (vs #951b81 $\color{#951b81}\blacksquare$  ESISAR)

		- Font : Klavika (Bold Caps & Regular Plain)

	- Musique :

		- Pourquoi pas du Mid-Tempo ...

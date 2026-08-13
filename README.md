# Four solaire Low-tech

Ce répertoire contient tous les éléments afin de construire un four solaire low-tech DIY démontable.

<img width="1920" height="1080" alt="Four Solaire Fermé" src="https://github.com/user-attachments/assets/3374dbf6-afc6-4b7c-959d-253a0b2da04b" />



Ce four a été réalisé par Q.Raball dans le cadres du stage WINS 2026 de la HEIG-VD : https://heig-vd.ch/campus/ateliers-jeunes/wins/

Il a grandement été inspiré par le four Atominique dont la documentation, les plans, les instructions sont disponibles ici : https://four-atominique.retzien.fr/index.php?title=Accueil
Il reprend aussi certain élément intéressant du séchoir solaire des "Chemins de faire" disponible ici : https://wiki.lowtechlab.org/wiki/S%C3%A9choir_solaire_d%C3%A9montable

## Structure du Git
### Le dossier "CAO" contient les éléments suivants :
- Un fichier de prévisualisation du four au format EDrawings avec les deux configuration du four (ouvert/fermé). Le format EDrawings est très simple d'utilisation et pratique. Il est possible de bouger l'assemblage, de cacher certaines parties, de mettre en transparence certain éléments et permet de garder les configurations, les textures, la nomenclature, etc... Le logiciel est disponible gratuitement ici : https://www.edrawingsviewer.com/download-edrawings
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/fd0068ed-4317-41c4-a9ba-3c94d6a543da" />

- Dossier "STEP" avec toutes les pièces en 3D, au format STEP, ainsi que les fichiers d'assemblages final (Assemblage_Four_Deflecteur.STEP).
- Dossier "Solidworks" avec toutes les pièces en 3D, au format solidworks 2024, ainsi que les fichiers d'assemblages final (Assemblage_Four_Deflecteur.SLDASM).

### Le dossier "Docs" contient les éléments suivants : 
- Un dossier "BOM" avec la liste du matériel nécessaire à la fabrication (BOM), avec dimensions, quantités, prix, lien d'achat. Le classeur contient trois onglets: Le BOM par sous-assemblage, le BOM par type de composant et une liste de choix de miroirs pour l'intérieur et l'extérieur du four au cas où ceux dans les les autres ne sont plus disponibles à l'achat.
<img width="1894" height="778" alt="image" src="https://github.com/user-attachments/assets/34618da0-ed45-4ba0-a03d-0dbc04a2f959" />

- Un dossier "Retour d'expérience" avec les différents problèmes rencontrés et les solutions mises en place.
- Un dossier "Choix des matériaux" avec les différents matériaux utilisés, les raisons des choix et les alternatives possibles.


### Le dossier "Plan" contient les éléments suivants : 
- Dossier "DXF" avec les fichiers de découpes afin de découper les panneaux de bois par technologie laser.
- Dossier "PDF" avec tous les plans des pièces avec assemblage, usinages et cotes
<img width="1253" height="923" alt="image" src="https://github.com/user-attachments/assets/f6e74684-03e6-482c-92f2-1464f8452a14" />

- Dossier "Solidworks" avec tous les fichiers de mises en plan au format Solidworks 2024

### Le dossier "Vids" contient les éléments suivants : 
- Les animations de montages pour les différents sous-assemblages du fours. Ne pas hésiter à ralentir la vidéo ou à mettre sur pause pour améliorer la compréhension.
<img width="800" height="617" alt="Boite-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/260bcfaf-1b56-4905-b74d-f4ba2a7ab159" />

## Liste des outils nécessaire à la fabrication et au montage
### Fabrication
- De quoi mesurer (règle, mètre déroulant) et écrire sur le bois (crayon de préférence).
- Une équerre à chapeau (DIN 875-2 idéalement), pour tracer des perpendiculaires et servir de guide à la découpe.
- Des serre-joints, ou pinces de bridage afin de maintenir deux éléments ensemble. Cela peut être pratique pour les positions des perçages si le plan n'est pas respecté à la lettre.
- Une scie (sauteuse) pour la découpe des tasseaux de bois et des tôles / miroirs. Un cutter peut être utile aussi.
- Une perceuse à colonne avec un jeu de mèches à bois. La plupart des trous sont Ø5, Ø9 ou Ø10. Les pré-trous pour les vis peuvent être fait avec une mèche de Ø2 (à adapter en fonction de la dureté du bois et de la taille des vis utilisées).
- Des mèches pour lamage droit / mèche à façonner / mèche-fraise plate de Ø20 ou Ø21 pour les têtes de vis et une de Ø13 ou Ø14 pour les écrous.
- Une mèche à tôle de Ø5 pour percer la tôle en acier. Une mèche standard peut se coincer et peut être dangereux.
- Eventuellement, une petite perceuse électroportative sur batterie peut être utile.

### Montage
- Tournevis / visseuse avec embout adapté aux vis utilisées.
- Clé à fourche taille 13 et clé à douille taille 13 pour la fixation des vis 6 pans dans les tasseaux.
- Des limes plates et rondes pour adapter les jeux entre les pièces et la taille des trous si nécessaire. Eventuellement une ponceuse peut être aussi utile.
- Des serre-joints, ou pinces de bridage afin de maintenir deux éléments ensemble. Cela peut être pratique pour assembler les tasseaux aux panneaux de bois.

<img width="1920" height="1080" alt="Four Solaire Ouvert (3)" src="https://github.com/user-attachments/assets/41fd2d23-7234-4313-a584-c52661167f8c" />


## Améliorations possibles / recommandées
- Afin de protéger les miroirs des rayures lorsqu'on les replies, les miroirs sont tapissés derrière la surface réfléchissante d'un tissus fin, et les charnières sont recouvertes d'un feutre. Des patins en caoutchouc ont été ajoutés sur le bas du cadre pour éviter que le grand miroir du dessus repose sur le bois directement.
- Remplacer les tringles en acier par un dispositif plus rigide. Au vu de la longueur des tringles prévues, elles ont tendances à fléchir. Pour éviter le fléchissement, il faut soit agrandir le diamètre de la tringle, soit raccourcir celle-ci. Sinon, il est aussi possible de changer le dispositif de réglage par une plaque en bois avec des secteurs. Un exemple de système de réglage est proposé à la fois dans les fichiers de découpes, les plans. Ne pas hésiter à adapter les formes, le nombre de trous à convenance.
- Il peut être judicieux d'ajouter un tablard sur le dessus afin de poser le plat à cuisiner pour ouvrir la porte. Par contre, si le dispositif est fixe, il devient plus compliqué de stocker le four à plat une fois démonté. Il est aussi plus compliqué de faire une four de protection adaptée avec un tel élément qui dépasse.
- Comme le four est lourd et encombrant, il peut être bien de le monter sur un chariot ou de rajouter des pieds à roulettes pour le déplacer. Un module supplémentaire sera inclus pour la version 2 du four.
- Le choix des matériaux pour les miroirs dépend fortement du budget à disposition. Plusieurs solutions sont possibles: plaques inox miroirs (lourd), panneaux de bois recouvert d'un film miroir (moins durable, plus simple), miroirs en plastiques (peut jaunir avec le temps), panneau Alucobond/Dibond (très cher et impossible d'avoir en petite quantité).
- Afin d'éviter au déflecteurs latéraux de se refermer avec le vent, il peut être judicieux de percer le cadre du déflecteur avec le support latéral servant à maintenir l'angle afin d'y mettre un clou. Cela permettra de bloquer la rotation du déflecteur.

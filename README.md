<a name="br1"></a> 

Rapport de projet de programmaꢀon

Groupe OS1a

Introducꢀon :

Ce rapport vise à rendre compte du projet de programmaꢀon réalisé par le groupe

OS1a, qui portait sur la créaꢀon d’une version du jeu Peegle.

Ce dernier est un jeu en deux dimensions dont le but est de détruire des billes colorées,

appelées pegs, en ꢀrant sur elles un nombre limité de balles depuis le haut de l’écran.

Rendu visuel du jeu créé.

La cahier des charges pour la réalisaꢀon de ce projet était le suivant :

Travail minimal :

•

Implémentaꢀon d’un moteur physique qui gère la trajectoire d’une balle

ainsi que ses rebonds.

•

Créaꢀon de quelques niveaux ainsi que d’un menu permeꢁant de

naviguer entre les niveaux.

Amélioraꢀons suggérées :

•

Ajout de diﬀérents types de pegs et de diﬀérents eﬀets visuels.

•

Ajout d’un éditeur de niveaux permeꢁant à l’uꢀlisateur de créer des

niveaux au travers d’une interface graphique.

•

Générateur de niveaux aléatoires.



<a name="br2"></a> 

Travail eﬀectué :

Toutes les foncꢀonnalités de base du jeu citées plus haut ont été implémentées, ainsi

que toutes les amélioraꢀons suggérées, et d’autres extensions encore. Voici un résumé en

quelques points des éléments les plus importants présents dans la version ﬁnale du jeu :

Éléments menꢀonnés dans le cahier des charges :

•

•

Physique eﬀecꢀve des balles. Les balles lancées par l’uꢀlisateur au cours du jeu

reproduisent de manière ﬁdèle le mouvement d’une balle ꢀrée par un canon et

soumise à la gravité. Elles rebondissent correctement contre les pegs de diﬀérentes

tailles.

Menu permeꢁant de naviguer entre les niveaux. L’uꢀlisateur du jeu peut accéder à un

menu où sont répertoriés tous les niveaux créés, ainsi que sa progression sur ceux-ci.

Les niveaux aﬃchés sont associés à une image miniature permeꢁant à l’uꢀlisateur de

voir quel est leur aspect général.

Menu principal, depuis lequel on peut accéder au menu de sélecꢀon en cliquant sur « Niveaux ».

Menu de sélecꢀon des niveaux, avec aperçu des niveaux, foncꢀon de recherche et sauvegarde de la

progression.



<a name="br3"></a> 

•

•

•

Diﬀérents types de pegs. Les pegs présents dans les niveaux varient par leur couleur

(bleu, vert, rouge, violet) ainsi que par leur taille. On peut aussi leur appliquer

diﬀérentes foncꢀons de mouvement, comme il sera décrit plus tard.

Diﬀérents eﬀets visuels. L’uꢀlisateur peut choisir dans les opꢀons du jeu d’appliquer

des eﬀets visuels diﬀérents, comme de choisir l’arrière-plan du jeu et l’apparence de la

balle (boule noire, ballon de foot ou de basket, balle de tennis ou smiley).

Éditeur de niveaux et créaꢀon de niveau. Le jeu est doté d’un éditeur de niveau équipé

de nombreuses opꢀons. Il permet de placer des pegs sur un terrain en faisant varier

leur taille, leur couleur, leur vitesse, et les foncꢀons d’alignement et de mouvement

(décrites plus bas) qui leur seront appliquées. L’éditeur permet aussi de choisir le nom

et le nombre de balles iniꢀales du niveau créé ainsi que de simuler son déroulement

en animant le terrain, pour voir quel serait le rendu réel du niveau. Les niveaux créés

peuvent ensuite être déﬁnis comme appartenant soit à la progression de niveaux

(Campagne), soit à un répertoire à part (Perso).

Niveau en cours de créaꢀon dans l’éditeur.

•

Générateur de niveaux aléatoire. L’uꢀlisateur peut choisir à tout moment de jouer à

un niveau contenant des pegs dont le nombre, le placement et la couleur sont choisies

aléatoirement.

Éléments supplémentaires :

•

Diﬀérents eﬀets sonores. Le jeu est doté de musiques de fond et d’un son produit

lorsque les balles touchent des pegs. Ces eﬀets peuvent être acꢀvés ou désacꢀvés

depuis les opꢀons du jeu.

•

Foncꢀonnalité de score et de combos. Les niveaux du jeu ont chacun des scores ﬁxés

à aꢁeindre pour décrocher une, deux ou trois étoiles. Au cours d’une parꢀe et au fur

et à mesure qu’il détruit des pegs, l’uꢀlisateur voit son score augmenter sur une barre

située à droite du terrain. S’il détruit plusieurs pegs au cours d’un seul lancer, il réalise

un combo et gagne plus de points. Son score augmente alors plus rapidement et un

message associé au combo apparaît au centre du terrain.



<a name="br4"></a> 

Interface de jeu, avec barre de score à droite, et nombre de balles restantes à gauche.

•

•

Sauvegarde des niveaux. Les niveaux créés dans l’éditeur peuvent être sauvegardés

localement sur l’ordinateur de l’uꢀlisateur et être rechargés lors du lancement du jeu

suivant.

Sauvegarde de la progression de l’uꢀlisateur. La progression d’un joueur dans les

niveaux de la campagne est également sauvegardée localement, de telle sorte que

l’uꢀlisateur voit combien d’étoiles il a obtenu sur chacun des niveaux même après que

le jeu a été fermé et relancé.

•

•

Recherche de niveaux. Dans le menu de sélecꢀon des niveaux, l’uꢀlisateur peut uꢀliser

une foncꢀon de recherche qui lui permet de rechercher un niveau en tapant son nom

ou une chaîne de caractères contenue dans son nom.

Foncꢀonnalité de sélecꢀon. L’éditeur de niveaux conꢀent une foncꢀonnalité de

sélecꢀon, qui permet à l’uꢀlisateur de sélecꢀonner un ou plusieurs pegs déjà placés

pour leur donner ou modiﬁer leurs aꢁributs. Ceꢁe sélecꢀon se fait en maintenant

appuyée la souris sur le terrain et en la glissant, ce qui fait apparaître un rectangle de

sélecꢀon comme sur le bureau d’un PC classique.

•

•

Foncꢀons d’alignement. L’éditeur de niveaux est équipé d’opꢀons permeꢁant

d’appliquer diﬀérentes foncꢀons d’alignement sur les pegs sélecꢀonnés par

l’uꢀlisateur. Ce dernier peut ainsi aligner les pegs sélecꢀonnés horizontalement,

verꢀcalement, suivant la diagonale du rectangle de sélecꢀon, autour du centre du

terrain ou du rectangle de sélecꢀon, ou encore suivant l’ellipse inscrite dans le

rectangle de sélecꢀon.

Foncꢀons de mouvement. L’uꢀlisateur peut appliquer aux pegs d’un niveau en cours

de créaꢀon diﬀérentes foncꢀons de mouvement, comme des translaꢀons horizontales,

ou des rotaꢀons circulaires ou ellipꢀques. Les pegs dotés d’une ou de plusieurs

foncꢀons de mouvement se déplaceront donc sur le terrain au cours d’un niveau, à une

vitesse qui peut être déﬁnie depuis l’éditeur.



<a name="br5"></a> 

Architecture du projet :

Le code source du projet est réparꢀ en tout sur 15 classes, elles-mêmes divisées en

deux répertoires : Modèle et Vue. La descripꢀon des classes ainsi que des relaꢀons qu’elles

ont entre elles est représenté sur le diagramme UML présent sur la page suivante.

Conclusion :

Le projet a été porté à un stade où tous les éléments du cahier des charges iniꢀal ont

été implémentés, et où de nombreuses extensions ont été ajoutées. Le jeu est foncꢀonnel et

oﬀre la possibilité à l’uꢀlisateur de créer des niveaux variés et de les sauvegarder. La navigaꢀon

au sein de l’interface de jeu est rendue possible par un ensemble de menus connectés les uns

aux autres.

Un développement plus en avant du projet pourrait consister éventuellement à ajouter

de nouvelles foncꢀons de mouvement applicables aux pegs, et à créer des niveaux pour

densiﬁer la campagne.




<a name="br6"></a> 


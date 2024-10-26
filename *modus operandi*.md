---
title: "*Modus Operandi*"
order: 6
in_menu: true
---
En tant qu'amateur de carto et de graphisme, et très agacé par la surutilisation de la voiture au quotidien , je n'ai pas pu résister à en créer un pour ma commune.

#### Quel logiciel ?

Il me fallait une version vectorielle, c'est plus propre, n'empêche pas une version bitmap et permet de l'utiliser plus librement sur différents supports : numériques, panneaux physiques, etc.

J'ai utilisé [Inkscape](https://inkscape.org/fr/) pour tout composer, logiciel libre que je connais un peu.

#### Mode de déplacement

Je souhaitais réaliser le mien en 2 versions : une piéton et l'autre cycliste.

Piéton parce qu'à mon avis, c'est le mode de déplacement dont on surestime le plus le temps de déplacement et que tout le monde n'ose pas faire du vélo en ville.

Cycliste parce que c'est le véhicule le plus pertinent à l'échelle d'une ville (et ce serait bien que nos dirigeants le comprennent).

L'exemple du *metrominuto* de Saint-Brieuc mélangeant les 2 est à mon sens surchargé et les zones que l'on peut atteindre en vélo sont bien plus nombreuses : il faut changer d'échelle.

#### _Look and feel_

Concernant la présentation, je ne souhaitais pas garder cet aspect quadrillage avec des tracés dont la taille n'est pas proportionnelle à la distance.

Pour ce faire, j'ai utilisé un fond de carte [OpenStreetMap](https://www.openstreetmap.fr/) (What Else ? ☕) qui ne m'a servi que temporairement pour placer les points d'intérêts. Pour ce faire, j'ai utilisé la fonction *partager* du site officiel qui permet de générer une image de la carte.

Ensuite, j'ai placé des icônes aux points d'intérêt de la ville, puis j'ai connecté les points entre eux de manière rectiligne en appliquant des couleurs au hasard. Le côté rectiligne sans quadrillage faisait un peu brouillon, j'ai commencé à courber les traits selon l'itinéraire réel, rendu validé.

Afin que les points d'intérêts soit compris directement, j'ai choisi de prendre des libertés avec certains toponymes et décidé d'y rajouter une icône. Il faut savoir que beaucoup de personnes ne connaissent pas leur environnement direct, même dans le cas d'une petite ville (ici, 10 000 habitants).

Ainsi, au lieu d'indiquer "place du 8 mai 45", il était plus clair d'indiquer écoles/collège ; etc.

#### Temps de trajet

Concernant les temps de trajets, j'ai utilisé le site [OpenRouteService](https://maps.openrouteservice.org/) que j'apprécie pour ses isochrones. Ça a été l'occasion de corriger des erreurs de carto sur OSM : connections manquantes d'un côté de la rue à l'autre ou encore place piétonne entraînant des détours conséquents dans le calcul d'itinéraire.

Je souhaitais aussi intégrer la distance en mètres. Malheureusement, le manque de place m'a fait préférer la lisibilité.

Le réel problème qui s'est posé est de savoir où placer de manière pertinente les points de départ et  d'arrivée. Dans le cas d'une grande zone, le met-on à son entrée principale, à l'entrée la plus près de là où on vient, ou au centre ?

Si je calcule le temps de trajet pour y arriver, le point à l'entrée la plus proche est plus pertinent. Mais si je calcule un trajet qui traverse cette zone, il me manquera le temps de traversée, non négligeable à pied.
Inversement, si je calcule un trajet qui longe plusieurs de ces zones, je n'ai pas besoin d'aller en leur centre et d'avoir un temps de trajet plus long que la réalité !

Pour les lotissements, qui se trouvent en périphérie de la ville, j'ai choisi un point à l'entrée et pour les zones plus intérieures, j'ai pris un point central.

#### Supports

Je souhaitais aussi lier ce *metrominuto* à une version en ligne de manière que les gens puissent la trouver et la consulter sur leur téléphone. J'ai peu d'espoir que la mairie s'en saisisse pour réaliser un affichage physique, mais qui sait ?

J'avais pensé créer un QR code amenant vers une version [uMap]( https://umap.openstreetmap.fr/fr/about/) de ce *metrominuto*. Elle se serait présenté avec les itinéraires réels (les gens ne connaissent vraiment pas leur territoire, encore moins les venelles !) de la même couleur que leur trait schématique calqués sur un fond de carte OSM-FR qui a l'avantage d'être riche en informations piéton et accessibilité.

J'ai finalement opté pour un lien direct vers le même document numérique. Peut-être que je créerai cette version uMap, à voir.

#### Habillage

Afin de d'apporter un peu relief et de repérage, certains *metrominutos* possèdent des éléments géographiques remarquables de la ville : rivière, couloir vert, parcs, etc.

Ma ville n'ayant aucun élément structurant traversant (à part des départementales), j'ai opté pour le tracé de l'enveloppe urbaine.

Restait l'habillage et le tour était joué. Je suis parti sur une couleur bleue et un panneau piéton customisé. La version vélo sera sur le même modèle, verte avec un panneau cycliste customisé.

Dans un deuxième temps, lors de la réalisation du premier [**centrominuto**](https://bifurquons.github.io/metrominuto/centrominuto.html), j'ai rajouté un encadré inférieur pour vanter les bienfaits des déplacements actifs. 

## Et le vélo ?

![metrominuto-vélo](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fc/Metrominuto-cycliste-Cabestany.svg/823px-Metrominuto-cycliste-Cabestany.svg.png)

> [cabestany-à-vélo](https://upload.wikimedia.org/wikipedia/commons/f/fc/Metrominuto-cycliste-Cabestany.svg) 
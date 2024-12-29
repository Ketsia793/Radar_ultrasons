**Radar à ultrasons**

## À propos
Il s'agit ici d'un projet Arduino inspiré d'un tuto mais refondé car il y avait des erreurs dans les lignes de codes tant dans le Arduino cloud que
dans le processing cloud. 
Erreurs repérées :
- au niveau des boucles for dans le Arduino cloud qui assurent le bon mouvement du servomteur sans que celui-ci soit saccadé.
- au niveau de la reconnaissance du port par le processing cloud 
- au niveau du balayage du grapique qui ne s'effectuait pas via le processing cloud, il a donc fallu ajouter une condition qui prenait en compte
la data indiqué via les ultrasons qui permettent de savoir à quelle distance se situe l'objet.

## Caractéristiques
État du projet : Prototype /
Nombre de participants : 1 (solo) /
Technologies : C++/Java / Arduino IDE 2.3.4 / Processing 4.3.1.
Refactorisation : Non /
Responsivité : Non /
UX/UI : Non /
IDE : VSCode /
OS : Mac /

## Utilisation
S'exécute via Arduino IDE 2.3.4 et Processing 4.3.1.

## Sources
Youtube / Arduino 

## Contributions
Aidée par un camarade pour le code review 

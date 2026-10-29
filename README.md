Saisie et affichage d'un nombre en JavaScript
Description

Ce projet est un petit programme JavaScript exécuté avec Node.js. Il demande à un utilisateur de saisir un nombre dans le terminal, convertit la saisie en valeur numérique, puis affiche le résultat.

Ce projet me permet de découvrir les bases de JavaScript avec Node.js, notamment la saisie utilisateur et l'affichage dans la console.

Fonctionnalités
Demande à l'utilisateur de saisir un nombre.
Convertit la saisie en nombre grâce à la fonction Number().
Affiche le nombre saisi dans le terminal.
Ferme l'interface de saisie après l'affichage du résultat.
Prérequis

Pour exécuter ce programme, il faut avoir installé Node.js sur son ordinateur.

Téléchargement : https://nodejs.org/

Installation
Télécharge ou clone le projet.
Ouvre un terminal dans le dossier du projet.
Vérifie que Node.js est installé avec la commande suivante :
bash
node -v

Utilisation

Exécute le script avec la commande suivante, en supposant que le fichier s'appelle index.js :

bash
node index.js


Le programme demande ensuite de saisir un nombre.

Exemple d'exécution
text
entrez un nombre : 25
le nombre est 25

Explication du code
require("node:readline") : importe le module readline de Node.js pour lire les saisies dans le terminal.
readline.createInterface() : crée une interface de lecture utilisant le terminal comme entrée et sortie.
rl.question() : affiche une question et attend la réponse de l'utilisateur.
Number(answer) : convertit la réponse saisie en valeur numérique.
console.log() : affiche le résultat dans le terminal.
rl.close() : ferme l'interface de saisie une fois le traitement terminé.
Technologies utilisées
JavaScript
Node.js
Module natif node:readline
Auteur

Projet d'apprentissage JavaScript.
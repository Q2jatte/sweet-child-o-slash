# README - Projet HTML avec Bootstrap personnalisé (SCSS)

Ce projet est une démonstration d'un site web HTML utilisant Bootstrap pour la mise en page et la conception, ainsi que SCSS pour personnaliser le style Bootstrap. Il est conçu pour être exécuté sur un serveur Node.js.

## Installation

1. Assurez-vous d'avoir Node.js installé sur votre système. Si ce n'est pas le cas, vous pouvez le télécharger depuis [le site officiel de Node.js](https://nodejs.org/).

2. Clonez ce dépôt Git sur votre ordinateur.

3. Accédez au répertoire du projet.


4. Installez les dépendances Node.js à l'aide de la commande suivante :

npm install


## Personnalisation du Bootstrap avec SCSS

Le style Bootstrap de ce projet peut être personnalisé en modifiant les fichiers SCSS situés dans le répertoire `scss`. Vous pouvez ajouter vos propres variables SCSS dans `assets/scss/_custom.scss` et personnaliser le style Bootstrap en modifiant d'autres fichiers SCSS.

Une fois que vous avez apporté des modifications aux fichiers SCSS, vous devez les compiler en CSS en utilisant la commande suivante :

npm run scss:complie


Cela générera un fichier CSS personnalisé dans le répertoire `asstes/css`.

## Exécution du serveur Node.js

Pour exécuter le serveur Node.js et visualiser le site web, utilisez la commande suivante :

npm start


Le site sera accessible à l'adresse [http://localhost:3000](http://localhost:3000) dans votre navigateur.

## Contribuer

Si vous souhaitez contribuer à ce projet, n'hésitez pas à créer une pull request ou à ouvrir des issues pour signaler des problèmes ou des suggestions d'amélioration.

Merci d'avoir choisi ce projet comme point de départ pour votre site web Bootstrap personnalisé en utilisant SCSS et Node.js !





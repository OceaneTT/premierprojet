# Documentation de l'Exercice Git

## Objectif
Cet exercice a pour objectif de vous apprendre à manipuler Git en créant un projet, en utilisant un repository Git, en créant une page HTML, et en synchronisant vos fichiers entre Visual Studio Code (VS Code) et Git. Vous allez également apprendre à utiliser les commandes `commit` et `push`.

## Étapes de l'Exercice

### 1. Apprendre à manipuler Git
Git est un système de contrôle de version distribué qui permet de suivre les modifications apportées à des fichiers. Pour commencer, familiarisez-vous avec les commandes de base de Git après l'avoir installé sur votre machine.

### 2. Créer son premier projet et son premier repository Git
**Créer un nouveau répertoire** pour votre projet sur votre machine. Puis, **initialiser un repository Git** dans ce répertoire avec la commande suivante :
git init

Cette commande crée un nouveau repository Git dans le répertoire.

### 3. Créer une page HTML pour une location de licorne
Dans votre répertoire de projet, créez un fichier nommé `index.html` avec une structure de base pour une page de location de licorne.

### 4. Synchroniser les fichiers entre VS Code et Git
Ouvrez votre projet dans **Visual Studio Code (VS Code)**. Utilisez les fonctionnalités intégrées de Git dans VS Code pour **ajouter et suivre les modifications de vos fichiers**. Cela facilitera la gestion de votre projet.

### 5. Utilisation des commandes commit et push
Pour enregistrer vos modifications dans le repository Git local, utilisez la commande `commit` :

git add .
git commit -m "Ajout de la page HTML pour la location de licorne"

Ensuite, poussez vos modifications vers un repository distant (par exemple, sur GitHub) :

git remote add origin [URL de votre repository distant]
git push -u origin master


## Conclusion
Vous avez maintenant appris à créer et gérer un repository Git, à créer une page HTML, et à synchroniser vos fichiers entre VS Code et Git. Vous avez également appris à utiliser les commandes essentielles `commit` et `push` pour enregistrer et partager vos modifications. Félicitations pour avoir complété cet exercice !

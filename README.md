
# Git & Github

<img src="/images/git-logo.svg" height="50">               <img src="/images/github-logo.png" height="100">

### Git

Pour télécharger **Git**, voici le lien [https://git-scm.com/downloads](https://git-scm.com/downloads)


##### Definition 

Git est une outil de versioning les outils de versioning ont pour objectif de memoriser toute creation?modification ou supression des differents fichier d'un projet afin de vous permettre de retracer toute l'evolution du projet,fichier par fichier.

##### 1ère étape

initialise Git dans le projet : **git init**

##### 2ème étape

Faire le lien entre votre repository **distant** et **local**, pour cela créer un repository sur github. Lorsqu'il est fait
récupérer la commande suivante => git remote add origin https://urlDuDepot.git Le lien doit être bien
évidemment celui de votre repository. Entrer cette commande sur votre terminal.

##### 3ème étape (Non Obligatoire)

vérification du lien entre git et gite hub : **git remote -v**

Si les liens de votre repository github apparait tout est bon !

A partir de maintenant vous n'aurez plus besoin de faire les etapes au dessus !

###### Le Commit

Réaliser un commit, deux étapes doivent être réalisées :

1. D'abord l'ajout des fichiers à prendre en photo : **git add .**

2. Ensuite, la prise de photo elle-même : **git commit -m "commentaire à mettre ici"**

3. Mettre votre repository Github à jour : **git push origin master**

## The End...
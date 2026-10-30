# Commands git

PREPARATION DE GIT ET DE GITHUB
## 1- Télécharger git (github en local) sur internet et installe le
## 2- Crée un dossier de projet et ouvre y gitbash
## 3- Va sur internet pour créer un compte github ou si il existe deja alors crées en un "new repectory" et donnes lui le nom du dossier créé
## 4-Sur le terminal gitbash, fais tout possible pour te retrover dans le dossier de ton projet
## 5- Tape "git init" pour initialiser le dossier; comme ca une branche 'main' ou 'master' va se créer . c'est ta branche principale
## 6- Tape "git status" pour voie la statut de ton dossier
## 7-Cree un fichier .md pour chaque dossier pour y mettre ce que tu fais (c'est important)
echo "CE QUE TU VEUX Y METTRE" > readme.md
## 8- peut etre que le fichier "readme.md" ne serait pas existant, tu dois l'ajouter en faisant : git add readme.md
## 9- la commande git commit -m "creation du fichier readme.md" [cette commande nous permet d'enregistrer le changement apporté]

# LES COMMANDES QU'ON UTILISE TRES SOUVENT

## 1- CREE FICHIER / MODIFICATION
## 2- git add .
## 3- git commit -m "message à mettre"
## 4- git push


# COMMANDES GIT
## 1- git init 
- permet d'initialiser un repertoire en etant dans celui ci
- ex: etant dans le repertoire git-commands, on tape la commande : 
- git init

## 2- git add 
- permet d'ajouter un fichier ou des modification dans le stagging
- ex: git add . (le point represente le tout)

## 3- git commit
- permet d'enregistrer une modification en local
- ex : git commit -m "message"
- le message est important c'est pourquoi ce "-m"
- ou
- git commit -am "message" [a parce qu'on veut add aussi simultanement le fichier qui a été créé]

## 4- git status
- permet de verifier l'etat du repertoire

## 5- git log
- permet de voir ce qui s'est passé dans le repertoire

# POUR CREER UNE BRANCH

## 1- git branch nomDeLaBranch
-le nom de la branch doit précéder de "feature/"

## 2- git branch
- pour determiner sur quelle branch faut-il se connecter

## 3- git chechout nomDeBranchSurLaquelleOnVeutSeConnecter
 - creer fichier ou modifier
 - git add .
 - git commit -m "mesage"
 - git puch
 - git push --set-upstream origin nomDeLaNouvelleBranchCréée [pour matcher original branch à la nouvelle créée]

## 4- git checkout -b feature/css
- c'est une nouvelle branch créee nommée feature/css et sur laquelle on se connecte directement

## git pull
- pour recuperer des ajout fait du github au local
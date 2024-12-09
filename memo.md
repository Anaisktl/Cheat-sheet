# **GIT. GITHUB.**

Git est un système de gestion de version décentralisé open source qui facilite les activités Github sur votre ordinateur.



## *- Configuration des outils.*

Configurer les informations de l'utilisateur pour tous les dépôts locaux.

* $ git config --global user.name "[nom]"

Définit le nom que vous voulez associez à toutes vos opérations de commmit

* $ git config --global user.mail "[adresse mail]"

Définit l'email que vous voulez associer à toutes vos opérations de commmit

* $ git config --global color.ui auto

Active la colorisationd de la sortie en ligne de commande 
  

## *- Créer des dépôts.*

Démarrer un nouveau dépôt ou en obtenir un depuis une URL existante

* $ git init [nom-du-projet]

Crée un dépôt local à partir du nom spécifié

* $ git clone (url)

Télécharge un projet et tout son historique de versions


## *- Effecturer des changements*

Consulter les modifications et effectuer une opération de commmit

* $ git status

Liste tous les nouveaux fichiers et les fichiers modifiés à commiter

* $ git diff

Montre les modifications de fichier qui ne sont pas encore indexées

* $ git add [fichier]

Ajoute instantané du fichier, en préparation pour le suivi de version

* $ git diff --staged

Montre les différences de fichier entre la version indexée et la dernière version

* $ git reset [fichier]

Enleve le fichier de l'index, mais conserve son contenu

* $ git commit -m "[message descriptif]"


## *- Grouper des changements*

Nommer une série de commits et combiner les résultats de travaux terminés

* $ git branch

Liste toutes les branches locales dans le dépôt courant 

* $ branch [nom-de-branche]

Crée une nouvelle branche

* $ git checkout [nom-de-branche]

Bascule sur la branche spéicifié et met à jour le répertoire de travail

* git merge [nom-de-branche]

Combine dans la branche courante l'historique de la branche spécifiée 

* git branch -d [nom-de-branche]

Supprime la branche spécifié 


## *- Changements au niveau des noms de fichiers*

Déplacer et supprimer des fichiers sous suivi de version

* git rm [fichier]

Supprime le fichier du répertoire de travail et met à jour l'index

* git rm --cached [fichier]

Supprime le fichier du système de suivi de version mais le préserve localement

* git mv [fichier-nom] [fichier-nouveau-nom]

Renomme le fichier et prépare le changement pour un commit
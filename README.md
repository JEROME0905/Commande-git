**Commande Git**

git init : Permet d'initialiser le répository git.

git help config : Donne accès à tous les paramètres de configurations.

git config --global user.email"mettre son email" : Permet de renseigner son email.

git config --global user.name "Jerome" : Pemet d'ajouter son prénom. Utile pour savoir qui a fait le commit.

touch readme.md : Création d'un fichier readme.md.

git status : Donne l'état du dossier en cour.

git add readme.md : Permet d'indexer un fichier avant son commit.

git commit -m "titre du commit" : Permet de créer un historique du fichier en mettant un commentaire avec -m

git commit -a -m "commentaire" : Permet de faire les deux opérations précédentes en une .

git add --all : Indéxé tous les nouveaux fichiers.

git add ".html" : Indexe tous les fichiers .html.

touch.gitignore : Créer un fichier gitignore pour ignorer des fichiers.

git log : affiche l'historique des fichiers.

git log -n 2 : Affiche les deux derniers commits de l'historique.

git log oneline : Affiche tous les commits sur une ligne.

git log -p readme.md : Permet de regarder les commits d'un fichier spécifiques.

git log -n 2 -p readme.md : Permet d'afficher les deux derniers commits du fichier readme.md.

git diff : Permet de voir la différence entre les modifications en cour et le dernier commit.
  
git checkout SHA : Permet de se positionner sur un commit donné.

git checkout master : Permet de revenir au dernier commit de l'historique.

git revert SHA : Permet de supprimer les modifications d'un fichier. Pas de perte d'historique.

clear : Nettoie l'écran.

git reset HEAD index.html : Permet de revenir en arrière si on a indéxé un fichier

git reset --hard : Permet de revenir en arrière au dernier commit

git reset HEAD^ --soft : Permet de revenir en arrière et laisse toutes les modifications indéxés. le ^ indique le nombre de fois en arrière.

git reset HEAD^ --mixed : Permet de revenir en arrière et ne laisse aucun fichier indéxé.

git reset HEAD^ --hard : Supprime le dernier commit.

git branch nomDeMaBranche : création d'une nouvelle branche.

git checkout nomDeMaBranche : nom de la branche sur laquelle on veut aller.

git checkout master : Permet de revenir à la branche principal.

git merge redesign : Fusion de la branche redesign sur master.

git branch -d redesign : Permet la suppression d'une branche.



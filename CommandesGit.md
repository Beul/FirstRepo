Initialiser repository
	git init dans le fichier concerné
ajouter fichier à l'index
	git add nom_fichier
Ajouter tous fichiers à l'index 
	git add .
Commit
	git commit -m "commentaire"
Historique
	git log
Mise à jour d'un fichier déjà ajouté à l'index
	git commit -a -m "commentaire" (-a met à jour les fichiers déjà existant dans l'index)
Remonter à un commit précédent
	git checkout SHADuCommit
Revenir au commit le plus récent (branche principale)
	git checkout master
Revert commit (créer un nouveau commit qui fait l'inverse du précédent)
	git revert SHADuCommit
Modifier le message du dernier commit (attention slmt si pas déjà pushé sur l'origine)
	git commit --amend -m "Nv message"
Annuler tous changements depuis dernier commit
	git reset --hard
Clone autre repo
	git clone "CleHttps"
Push sur origin
	git push origin master
Pull sur origin
	git pull origin master
Voir les branches
	git branch
Créer Branch
	git branch NomDeLaBranche
Changer branch
	git checkout NomDeLaBranche

Ajout conflit dans branchTest

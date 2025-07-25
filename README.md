# Documentation de mon tuto

## Initialisation du projet
* git init // création d'un dossier .git contenant tous les fichiers nécessaires à Git pour suivre les versions du projet.

* git add README.md // Ajoute le fichier README.md dans la zone index. Prépare ce fichier pour le prochain commit. on peut aussi utiliser git add . pour ajouter tous les fichiers.

* git commit -m "first commit" // Fait un commit (enregistrement) du fichier ajouté avec un message "first commit". Cela sauvegarde l'état du fichier dans l'historique Git local avec une description.

* git branch -M main // Renomme la branche courante en main (forcément avec -M). Par défaut, Git utilise master, mais main est la nouvelle convention. -M force le changement même si la branche main existe déjà.

* git remote add origin git@github.com:babacar61/test.git // Ajoute un dépôt distant nommé origin pointant vers l'URL git@github.com:babacar61/test.git. Cela permet de lier ton dépôt local à celui sur GitHub (en SSH ici), pour pouvoir y pousser du code.

* git push -u origin main // Pousse (envoie) la branche locale main vers la branche main du dépôt distant origin. Le -u (ou --set-upstream) : Configure la branche main locale pour suivre la branche main distante. Cela permet de faire ensuite juste git push ou git pull sans arguments.




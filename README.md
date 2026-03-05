Description
Ce projet fait partie d’un TP de BTS SIO permettant d’apprendre à utiliser le système de gestion de versions Git et la plateforme GitHub.
L’objectif est de travailler uniquement en ligne de commande pour manipuler un repository Git.
Chaque groupe doit créer une page HTML présentant un jeu vidéo, puis intégrer cette page au projet.
Objectifs du projet
Apprendre à utiliser les commandes principales de Git :
    • cloner un repository
    • créer une branche
    • modifier des fichiers
    • enregistrer des modifications (commit)
    • fusionner une branche
    • envoyer les modifications sur GitHub
Structure du projet
Le projet contient les dossiers suivants :
/
index.html
/pages
    exemple.html
    pagex.html
/images
README.md
Description des fichiers
index.html
Page principale contenant les liens vers les pages des groupes.
pages/exemple.html
Page d’exemple montrant le résultat attendu.
⚠️ Ce fichier ne doit pas être modifié.
pages/pagex.html
Modèle de page servant de base pour créer la page de chaque groupe.
images/
Dossier contenant les images associées aux pages.
Travail à réaliser
Chaque groupe doit :
    1. Créer une branche
    2. Copier le modèle pagex.html
    3. Modifier la page
    4. Ajouter une image
    5. Enregistrer les modifications avec Git
    6. Fusionner la branche avec main
    7. Envoyer les modifications sur GitHub
Étapes du projet
1. Cloner le repository
Cloner le projet depuis GitHub :
git clone URL_DU_REPOSITORY
2. Se placer dans le dossier du projet
cd atelier-git-1-jeux-video
3. Créer une branche
Chaque groupe doit travailler dans sa propre branche.
Exemple pour le groupe 1 :
git checkout -b groupe1
Vérifier les branches :
git branch
4. Créer la page du groupe
Copier le modèle pagex.html.
Exemple :
cp pages/pagex.html pages/page1.html
5. Modifier la page
Modifier uniquement le fichier :
pages/page1.html
Remplacer les éléments suivants :
    • Groupe X → Groupe 1
    • imageX.jpg → groupe1.jpg
Ajouter :
    • les noms des membres du groupe
    • le nom du jeu vidéo
    • une description du jeu
6. Ajouter l’image
Ajouter l’image dans le dossier :
images/
Nom obligatoire :
groupe1.jpg
7. Vérifier les modifications
git status
8. Enregistrer les modifications
Ajouter les fichiers :
git add .

Créer un commit :
git commit -m "Groupe 1 : ajout page et image"
9. Fusionner avec la branche principale
Revenir sur main :
git checkout main
Mettre à jour le projet :
git pull
Fusionner la branche :
git merge groupe1
10. Envoyer les modifications sur GitHub
git push
Vérification finale
Lorsque le travail est terminé :
    1. Vérifier que la branche a été fusionnée dans main
    2. Vérifier que les modifications sont visibles sur GitHub
    3. Faire un git pull
    4. Ouvrir le fichier index.html
Vérifier que :
    • la page du groupe est accessible
    • l’image s’affiche correctement
Résultat attendu
À la fin du TP :
    • chaque groupe possède sa page HTML
    • toutes les pages sont accessibles depuis index.html
    • toutes les modifications sont présentes sur GitHub

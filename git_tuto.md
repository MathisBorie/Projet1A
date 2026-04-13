## Phase 1 : Avant de bosser

`git checkout main` (Switch sur la branche principale)

`git pull origin main` (Récupération du travail des autres)

`git checkout -b ma_branche` (Création d'une zone de travail isolée)

## Phase 2 : Pendant le code

`git add .` (Préparation des fichiers modifiés)

`git commit -m "mon message"` (Enregistrement local des modifs)

`git push origin ma_branche` (Envoi de ta branche sur GitHub)

## Phase 3 : Validation (Sur le site GitHub)

`Open Pull Request` (Demande de fusion au groupe)

`Discussion / Review` (Vérification par les collègues)

`Merge Pull Request` (Fusion finale dans le projet commun)

## Phase 4 : Après le merge

`git checkout main` (Retour sur la branche propre)

`git pull origin main` (Mise à jour de ton ordi avec la fusion)

`git branch -d ma_branche` (Suppression de la branche inutile)

## En cas de pépin (Mise à jour en cours de route)

`git merge main` (Importer le travail récent des potes dans ta branche actuelle)
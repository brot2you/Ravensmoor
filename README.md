# Ravensmoor — The Mystery Board Game (V19)

Jeu d’enquête victorien pour apprendre le **past perfect simple et continu** en anglais (3e, A2+/B1).
Quatre enquêtes complètes dans le même manoir : **Murder at Ravensmoor**, **The Missing Sapphire**, **The Midnight Letter** et **The Locked Library**.
À venir (cartes « Coming soon ») : The Last Train (illustrations à générer, voir `ILLUSTRATIONS-LAST-TRAIN.md`), The Ravensmoor Secret.
Aucun compte, aucun serveur, aucune IA en ligne : tout tourne dans le navigateur, progression enregistrée sur l’appareil.

## Mise en ligne (GitHub Pages)
1. Dans le dépôt `brot2you/Ravensmoor`, **supprimer l’ancien contenu** (anciens `README-V*.txt`, ancien dossier `assets/`).
2. Déposer à la racine : `index.html`, `.nojekyll`, `README.md` et le dossier `assets/` complet.
3. Adresse : https://brot2you.github.io/Ravensmoor/

## Mode station (QR codes)
- Enquête 01 : `?suspect=colonel|doctor|clara|reed|voss|gardener|potts` (compatible avec les cartes déjà imprimées).
- Enquête 02 : `?case=2&suspect=…`
- Enquête 03 : `?case=3&suspect=…`
- Enquête 04 : `?case=4&suspect=…`
- Cartes imprimables dans le *Teacher’s desk*.

## Contenu
- 8 pièces, 24 objets illustrés, 7 témoins, 1 menteur par enquête.
- Chaque indice se révèle après un défi de langue ; interrogatoires écrits avec correction des questions.
- Carnet, grille de déduction, Language Lab (cours, 10 QCM, 5 questions à reconstruire, chronologie).
- Accusation notée sur 10 (coupable, 3 indices, mensonge, past perfect), 3 tentatives, rang de détective.
- Espace enseignant en français : déroulé, cartes QR, fiche élève, corrigé, réinitialisation.

Technique : fichier HTML unique, JavaScript ES5 (compatible iOS Safari), données dans un bloc JSON.
Gratuit — BROT2YOU.

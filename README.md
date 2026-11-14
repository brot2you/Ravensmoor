# Ravensmoor — The Mystery Board Game (V25)

Jeu d’enquête victorien pour travailler le **past continuous** (ce que chacun était en train de faire) et le **past perfect** (ce qui s’était passé avant) en anglais (3e, A2+/B1).
Six enquêtes complètes, un coupable différent à chaque fois : **Murder at Ravensmoor**, **The Missing Sapphire**, **The Midnight Letter**, **The Locked Library**, **The Last Train** (dans le train de nuit) et **The Ravensmoor Secret**, qui relie toutes les autres.

Ordre chronologique de l’histoire : 02 (déc. 1890) → 05 (janv. 1891) → 04 (mars) → 03 (juin) → 06 (3 oct.) → 01 (10 oct.).
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
- Enquête 05 : `?case=5&suspect=…`
- Enquête 06 : `?case=6&suspect=…`
- Cartes imprimables dans le *Teacher’s desk*.

## Contenu
- 8 lieux (manoir ou train), 24 objets illustrés, 7 témoins, 1 menteur par enquête.
- Chaque indice se révèle après un défi de langue ; interrogatoires écrits avec correction des questions.
- Carnet, grille de déduction, Language Lab (cours, 10 QCM, 5 questions à reconstruire, chronologie).
- Accusation notée sur 10 (coupable, 3 indices, mensonge, past continuous + past perfect), 3 tentatives, rang de détective.
- Espace enseignant en français : déroulé, cartes QR, fiche élève, corrigé, réinitialisation.

Technique : fichier HTML unique, JavaScript ES5 (compatible iOS Safari), données dans un bloc JSON.
Gratuit — BROT2YOU.

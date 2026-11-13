# The Last Train — illustrations à générer (33 images)

**Intrigue prévue (enquête 05) :** décembre 1891, train de nuit Londres → Ravensmoor. M. Blackwood, l’avocat qui apporte le nouveau testament de Lord Ashford, disparaît entre deux gares avec sa serviette. Les 7 suspects habituels sont à bord : les portraits actuels restent valables.

**Formats**
- Plan et scènes : paysage 16:10 (environ 1600 × 1000 px), sans personnage, sans texte.
- Objets : carrés, sur un **vrai fond transparent** (PNG). Surtout pas de damier « dessiné » dans l’image.
- PNG accepté partout : je fais la conversion en .webp.

**Noms de fichiers à me renvoyer**
- `train-board.png` (le plan)
- `train-platform.png`, `train-engine.png`, `train-luggage.png`, `train-dining.png`, `train-firstclass.png`, `train-sleeper.png`, `train-corridor.png`, `train-observation.png`
- Objets : `train-<voiture>-1.png`, `-2.png`, `-3.png` (dans l’ordre des listes ci-dessous)

---

## 1. Le plan du train (1 image)

```
Cutaway side view of a Victorian night train in 1891, eight cars in a single row from left to right: station platform, steam locomotive, luggage van, dining car, first-class compartments, sleeping car, corridor car, observation car; interiors visible through cut-away walls, warm lamplight glowing inside, snowy night landscape around, rich reds, golds and deep blues, highly detailed painterly illustration, mystery board game style, clear empty space above each car, no people, no text, wide 16:10
```

## 2. Les 8 voitures (8 images)

Préfixe commun à coller avant chaque description :
```
Victorian night train interior, December 1891, warm gas-lamp light, polished mahogany and brass, deep reds and golds, snow outside the windows, highly detailed painterly illustration, cozy mystery board game style, no people, no text, wide 16:10 —
```

| Fichier | Description à ajouter |
|---|---|
| `train-platform` | King’s Cross station platform at night, steam, iron and glass roof, big station clock, luggage trolleys, newspaper stand |
| `train-engine` | steam locomotive cab, glowing firebox, coal tender, brass gauges and levers, driver’s lantern |
| `train-luggage` | luggage van, stacked leather trunks and hatboxes, mail sacks, a caged dog basket, swaying oil lamp |
| `train-dining` | elegant dining car, white tablecloths, silver tea service, crystal glasses, menu cards, velvet seats |
| `train-firstclass` | first-class compartment, plush red seats facing each other, luggage rack with a briefcase, lace curtains |
| `train-sleeper` | sleeping car compartment, made-up berth with pillows, small washbasin, folded nightclothes, blind half drawn |
| `train-corridor` | long narrow train corridor, row of compartment doors, red emergency cord along the ceiling, frosted windows |
| `train-observation` | observation car at the back, large windows onto the snowy night, armchairs, brass telescope, card table |

## 3. Les 24 objets (4 planches de 6)

Modèle de prompt pour chaque planche (même style que les objets du manoir) :
```
Set of 6 ornate Victorian objects, each isolated on a transparent background, gold filigree and fleur-de-lis details, rich reds and golds, glowing rim light, highly detailed painterly game icons, consistent style: [les 6 objets]
```

**Planche A**
1. `train-platform-1` — a luggage label tied with string
2. `train-platform-2` — a brass railway station clock
3. `train-platform-3` — a folded Victorian newspaper
4. `train-engine-1` — a coal shovel
5. `train-engine-2` — a train driver’s leather logbook
6. `train-engine-3` — a railway signal lantern

**Planche B**
1. `train-luggage-1` — a leather travelling trunk
2. `train-luggage-2` — a round hatbox with a ribbon
3. `train-luggage-3` — a brass padlock with its key
4. `train-dining-1` — a porcelain teacup and saucer
5. `train-dining-2` — a dining car menu card
6. `train-dining-3` — a bottle of red wine with a wax seal

**Planche C**
1. `train-firstclass-1` — a lawyer’s leather briefcase
2. `train-firstclass-2` — a pair of gentleman’s leather gloves
3. `train-firstclass-3` — round gold-rimmed reading spectacles
4. `train-sleeper-1` — a sleeping car berth ticket
5. `train-sleeper-2` — a leather toiletry case
6. `train-sleeper-3` — a silk sleeping mask

**Planche D**
1. `train-corridor-1` — a red emergency cord handle
2. `train-corridor-2` — a conductor’s brass ticket punch
3. `train-corridor-3` — a torn piece of a document with a red wax seal
4. `train-observation-1` — a brass pocket telescope
5. `train-observation-2` — a printed railway timetable
6. `train-observation-3` — a deck of playing cards

---

**Côté code (à faire par Claude quand les images seront prêtes) :** donner à chaque enquête ses propres lieux (aujourd’hui les 8 pièces du manoir sont communes à toutes), écrire l’enquête 05 à partir de ce que les images montrent réellement, puis tester.

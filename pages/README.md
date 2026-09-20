# Pages événement

`map.html` est le **template UI** partagé.
Chaque voyage a un JSON dans ce dossier.

## Ouvrir une page

`map.html?page=tokyo-jan-2027`

Sans paramètre, Tokyo janvier 2027 s’affiche.

## Créer une nouvelle page

1. Copier `_template.json` vers `pages/mon-voyage.json`.
2. Remplir `title`, `kicker`, `places`, `days`.
3. Soit coller les fiches dans `events`, soit lister des fichiers JSON dans `sources`.
4. Ouvrir `map.html?page=mon-voyage`.

## Quoi modifier où

- UI (filtres, carte, couleurs de types, cartes) → `map.html` uniquement. Toutes les pages changent.
- Dates, lieux, liste d’événements → le JSON de la page seulement.

# AISB V2

Structure complète PWA : données séparées, partitions PNG, audio MP3, favoris et vitesses 50/75/100 %.

## GitHub Pages
Téléverser le contenu de ce dossier à la racine du dépôt. Pages doit publier depuis `main` / `(root)`.

## Ajouter un audio
1. Copier le MP3 dans `audio/`.
2. Ouvrir `data/repertoire.json`.
3. Dans le morceau concerné, remplacer `"audio": []` par :
```json
"audio": [{"file":"audio/father-kelly.mp3","label":"Version AISB"}]
```

Les suites 01 à 10 disposent déjà de leurs PNG. Les entrées 11 à 50 sont prêtes mais leurs images doivent encore être ajoutées.

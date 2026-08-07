# Galerie d'images

Galerie d'images libres de droit, consultable en ligne :
**https://resortnamur.github.io/galerie/**

## Comment ajouter des images

1. Déposer les images dans un sous-dossier de `images/` — le nom du dossier devient le nom de la catégorie affichée sur le site.
   - Exemple : `images/Paysages/mon-image.png` créera (ou alimentera) la catégorie **Paysages**.
2. Valider et pousser les changements :

   ```
   git add .
   git commit -m "Ajout d'images"
   git push
   ```

3. Le site se met à jour automatiquement en 1 à 2 minutes. **Aucun autre fichier à modifier** : la page détecte seule les dossiers et les images.

## Conseils

- Formats acceptés : `.png`, `.jpg`, `.jpeg`, `.webp`, `.gif`, `.avif`.
- Préférer des noms de fichiers simples, sans espaces ni accents (ex. `aqua-01.png`).
- Éviter les fichiers trop lourds (idéalement moins de 5 Mo) pour un chargement rapide.
- ⚠️ Le dépôt est **public** : n'y placer que des images libres de droit et destinées à être vues par tous.

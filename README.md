# Quiz

Site statique : `index.html` + dossier `photos/`. Aucun build.

## Mettre en ligne

```bash
git init
git add .
git commit -m "Quiz"
git branch -M main
git remote add origin git@github.com:maiba-engineering/NOM-DU-DEPOT.git
git push -u origin main
```

Puis sur GitHub : Settings > Pages > Source : branche `main`, dossier `/ (root)`.
Adresse : `https://maiba-engineering.github.io/NOM-DU-DEPOT/`

## Ajouter une photo

Deposer le fichier dans `photos/` avec ce nom, rien d'autre a modifier :

    qst<numero de question>_cuis<1 ou 2>.jpg

Exemples : `qst4_cuis1.jpg`, `qst16_cuis2.jpg`.

- Extensions reconnues : `.jpg`, `.jpeg`, `.png`, `.webp`, en minuscules. Pas de HEIC.
- Cadrage portrait 4:5, sujet au centre (le cadre recadre au centre).
- Une question affiche le duel en images des qu'au moins une de ses deux photos existe.
- Deplacer une photo vers une autre question = renommer le fichier.

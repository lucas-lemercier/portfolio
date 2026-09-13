# Portfolio BTS SIO SISR — Lucas

## Mettre en ligne gratuitement avec GitHub Pages

1. Crée un compte sur https://github.com si tu n'en as pas.
2. Crée un nouveau dépôt (repository), par exemple nommé `portfolio`.
   Coche "Public".
3. Sur ton ordinateur, dans ce dossier, exécute :
   ```
   git init
   git add .
   git commit -m "Premier envoi du portfolio"
   git branch -M main
   git remote add origin https://github.com/TON-PSEUDO/portfolio.git
   git push -u origin main
   ```
4. Sur GitHub, va dans **Settings → Pages** du dépôt.
5. Dans "Branch", choisis `main` et le dossier `/ (root)`, puis Save.
6. Après 1-2 minutes, ton site est en ligne à l'adresse :
   `https://TON-PSEUDO.github.io/portfolio/`


## Mettre à jour le site ensuite

Après avoir modifié des fichiers :
```
git add .
git commit -m "Description de ce que tu as changé"
git push
```
Le site se met à jour automatiquement en 1-2 minutes.

## Ajouter une nouvelle fiche de veille

1. Copie `modele-fiche-veille.md`, remplis-la.
2. Convertis-la en page HTML dans le dossier `veille/` (reprends le style des autres pages,
   ou demande à Claude de la convertir).
3. Ajoute une carte correspondante dans `veille.html`.

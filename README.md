# codein23.github.io

Page d'accueil du compte GitHub — liste les projets en ligne.

Sert `https://codein23.github.io/`, qui renvoie vers :

| Projet | URL |
|---|---|
| Trade Journal + Analytics | https://codein23.github.io/trade-journal/ |
| FX Journal Dashboard | https://codein23.github.io/fx-journal-dashboard/ |
| Kynder Braids | https://codein23.github.io/kynderbraids/ |

## Fonctionnement

Un seul fichier `index.html`, sans build ni dépendance. GitHub Pages le sert
directement depuis la branche `main`. Les aperçus de chaque projet sont des
`iframe` du site réel : ils restent donc toujours à jour tout seuls.

## Ajouter un projet

Dupliquer un bloc `<article class="row reveal">` dans `index.html`, puis changer :

- le titre et la couleur de pastille (`--dot`)
- la description et la liste `.stack`
- les trois URL (bouton, lien du cadre, `src` de l'iframe) et le texte `.frame-url`

Penser à mettre à jour le compteur `<b>3</b> projets en ligne` dans le hero.

## Publier

```bash
git add -A
git commit -m "maj"
git push
```

Le site est à jour en une minute environ.

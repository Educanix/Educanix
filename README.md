# Educanix — Site web

Site vitrine pour Educanix (Thaïs Marque, éducatrice canine — Uzès, Gard),
généré à partir de la maquette Canva fournie.

## Contenu
- `index.html` — toutes les sections du site (accueil, l'éducateur, la méthode,
  prestations détaillées, à savoir, partenaires, contact, mentions légales)
- `style.css` — mise en forme (couleurs et polices reprises de la maquette)
- `script.js` — menu mobile + année automatique dans le pied de page
- `assets/images/` — images extraites de la maquette et optimisées pour le web

## Mettre en ligne avec GitHub Pages
1. Créez un nouveau dépôt sur GitHub (public).
2. Ajoutez tous ces fichiers à la racine du dépôt (pas dans un sous-dossier),
   en conservant la structure `assets/images/...`.
3. Poussez (`git add . && git commit -m "site Educanix" && git push`).
4. Dans le dépôt GitHub : Settings → Pages → Source : sélectionnez la branche
   `main` et le dossier `/ (root)`, puis Save.
5. Après 1-2 minutes, le site sera visible à l'adresse indiquée en haut de
   cette page (généralement `https://<votre-nom-utilisateur>.github.io/<nom-du-depot>/`).

## À personnaliser avant mise en ligne
- Ligne "Nom hébergeur du site" dans les mentions légales (bas de page) : à
  compléter une fois l'hébergeur choisi (GitHub Pages, OVH, etc.).
- Les liens Facebook/Instagram/TikTok pointent vers du texte simple ; vous
  pouvez les transformer en vrais liens cliquables si besoin.
- Les polices "Anton" et "Alegreya" sont chargées depuis Google Fonts (nécessite
  une connexion internet une fois le site en ligne — c'est normal et gratuit).

## Structure des fichiers
```
index.html
style.css
script.js
assets/
  images/
    ... (toutes les images du site)
```

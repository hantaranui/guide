# Interface de guide projet

Cette interface est un petit site statique compatible avec Netlify. Elle est préremplie avec les deux guides SynOps fournis.

## Utilisation

Ouvrir `index.html` dans un navigateur, puis:

- ajouter ou modifier les blocs du guide;
- chercher un mot-clé dans la barre de recherche;
- filtrer par catégorie;
- retrouver rapidement les réponses de la catégorie `Questions jury`;
- exporter le guide en JSON;
- réimporter un JSON précédemment exporté.

Les modifications sont sauvegardées dans le navigateur avec `localStorage`.

## Mise en ligne sur Netlify

1. Déposer ce dossier dans un dépôt GitHub ou le glisser directement dans Netlify Drop.
2. Aucun build command n'est nécessaire.
3. Le dossier de publication est la racine du projet.

## Personnalisation

Les blocs extraits des documents sont dans `guide-data.js`. Les blocs d'exemple de secours sont dans `script.js`, dans la variable `starterBlocks`.

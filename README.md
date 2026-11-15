# Jardin — calendrier des plantations

Site statique publié avec GitHub Pages.

- `calendrier_plantes.html` — la page (lit `plantes.csv` au chargement ; un sélecteur de fichier permet aussi de charger un CSV local)
- `plantes.csv` — les données (séparateur `;`, UTF-8)
- `index.html` — point d'entrée qui redirige vers la page

Les colonnes `amies` / `ennemies` ont été remplies à partir du tableau
« association des plantes au potager » (jardipartage) : cases vertes = bonnes
associations, rouges = mauvaises.

## Sous-site `/recettes/`

`recettes/` est une copie du dépôt [recettes](https://github.com/bernard44600/recettes)
(carnet de recettes statique), publiée ici en attendant que GitHub Pages soit activé
sur ce dépôt-là. Pour la mettre à jour :
`rsync -a --delete ../git_recettes/ recettes/ --exclude .git --exclude .github`

Déploiement du projet dans GitHub Pages:

Création d'un repository webpack-sample-deploy: [ici](http://github.com/ftoumHub/webpack-sample-deploy)

Une fois les sources ajoutées au repository, on va créer une branche nommée 'gh-pages'.

```bash
git checkout -b gh-pages

git subtree push --prefix dist origin gh-pages
```

Le contenu est ensuite accessible à l'url : http://ftoumHub.github.io/webpack-sample-deploy
# Publication de blogs
Articles de blog tech.
Ce dépôt contient une liste d'articles de blogs techniques.

# 🎃 HacktoberFest 2023 🎃

Si vous êtes venu ici pour le Hacktoberfest 🦇️ :

Célébrez l'[Hacktoberfest](https://hacktoberfest.com/) en vous impliquant dans la communauté open source en accomplissant certaines tâches dans ce projet.

## C'est quoi le Hacktoberfest ?

HacktoberFest est l'événement annuel de digitalocean qui encourage les gens à contribuer à l'open source tout au long du mois d'octobre. Une grande partie de l'infrastructure technologique moderne, y compris certains des propres produits de digitalocean, repose sur des projets open source construits et maintenus par des personnes passionnées qui n'ont souvent pas le personnel ou les budgets pour faire bien plus que maintenir le projet en vie. HacktoberFest consiste à redonner à ces projets, à affiner les compétences et à célébrer tout ce qui est open source, en particulier les personnes qui rendent l'open source si spécial.

[https://hacktoberfest.com/](https://hacktoberfest.com/)

Ce dépôt est ouvert à tous les membres de la communauté GitHub. Tout membre peut contribuer à ce projet sans être un collaborateur.

## Comment puis-je contribuer ?

Vous pouvez contribuer à ce dépôt

N'hésitez pas à contribuer !
PS : Vos contributions doivent suivre la ligne directrice de contribution :

- Fork ce référentiel (Cliquez sur le bouton Fork en haut à droite de cette page, cliquez sur votre image de profil)
- Clonez votre fork sur votre machine locale

``` démarque
git clone https://github.com/your-username/blog-posts.git
```

- Créer une branche

``` démarque
git checkout -b blog main
```

- Effectuez vos modifications. Créez un fichier (filename=`<your-githubusername.json>
- Énumérez tous les articles de blog technique (vous pouvez les rechercher sur Google), autant que vous le souhaitez. Il doit respecter le format :

## Pour une simple publication.
Utilisez ce format si vous souhaitez soumettre plusieurs articles de blog. [Exemple](https://github.com/Developer-Student-Clubs-UBa/blog-posts/blob/main/example-multiple.json)
```json
{
  "des postes": [
    {
    "Title": "Titre de l'article de blog",
    "Description": "Une courte description",
    "URL": "Lien vers l'article de blog",
    "Author": "Auteur du contenu du blog"
  },
    {
    "Title": "Configurer un serveur apache sur Ubuntu",
    "Description": "Un résumé du processus d'installation d'un serveur apache",
    "Link": "https://onecode.hashnode.dev/setting-up-an-apache-server-on-ubuntu",
    "Author": "Ndi Lionel"
  }
   ]
}
```

# Exemples
1. [Simple](https://github.com/Developer-Student-Clubs-UBa/blog-posts/blob/main/example-single.json)
2. [Multiple](https://github.com/Developer-Student-Clubs-UBa/blog-posts/blob/main/example-multiple.json)

# Commit
Veuillez noter ce qui suit avant de faire un `commit`
1. Les liens des articles de blog doivent être en direct et publics.
2. Tous les auteurs doivent être le(s) véritable(s) auteur(s) de la publication.
3. Tous les domaines publics sont acceptés.
4. Votre PR sera fermé si vous fournissez un auteur de blog invalide.
5. Aucune modification de fichiers existants à dessein. Si vous remarquez un problème avec un fichier, veuillez créer un [Problème](https://github.com/Developer-Student-Clubs-UBa/blog-posts/issues/new)

```markdown
git add .
git commit -m 'feat: added my blog post: <github-username>'
git push origin blog
```

- Créez une nouvelle demande d'extraction à partir de votre dépôt enfourché (Cliquez sur le bouton `New Pull Request` situé en haut de votre dépôt). Assurez-vous de comparer les fourches, puis sélectionnez ce dépôt comme cible
- Ajouter des examinateurs (facultatif)
- Attendez la revue de votre requete et l'approbation de la fusion !

- **Veuillez laisser une ETOILE à ce dépôt** si vous vous êtes amusé !

Fait avec :purple_heart:
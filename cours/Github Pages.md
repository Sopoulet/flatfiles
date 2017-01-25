Github Pages
=


Github : Hébergeur des dépôts open source
Github Pages : Site associé à votre dépôt Github pour présenter le code.
username.github.io
https://sopoulet.github.io/flatfiles/ 

Pour mettre en place Github pages, il suffit de se rendre dans les Settings du repository

Jekyll : générateur de site web static codé en ruby.



### Commandes Jekyll
```
gem install jekyll : permet d'installer jekyll
```
```
jekyll new "monSite" : créer un nouveau site
```
```
jekyll serve : à la racine de notre site, il permet de mettre en place un serveur pour notre site pour appliquer les modifications.
```

### Fichiers

_congif.yml : fichier de configuration où l'on trouve des variables gloables qui serviront sur les différentes parties du template.
```
{{site.titre}} : affiche la valeur associé à la clé titre présente dans le fichier de config
```



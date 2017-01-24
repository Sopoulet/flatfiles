---
layout: cours
nom: Collection jekyll
---

## Collection Jekyll

Les collections ressemblent aux pages et aux posts, mais elles n'ont pas de dates.

Dans le fichier _ config.yml on ajoute une ou des collections :
Pour une collection dans le dossier cours

```
collections :
  cours :
    outpul : true
```
Dans le fichier cours.md on reprend la boucle des posts :
```
{% for cours in site.cours %}
<p>{{cours.content}}</p><br/>
{% endfor %}
```
*cours* est une variable que l'on nomme comme on le souhaite.
On ajoute une en-tête dans les cours, des méta-données, pour la collection jekyll et on créer un template cours
```
layout: cours
nom : cours 

```



##CSS

On créé un dossier assets
Dans le fichier head.html on ajoute le lien de la feuille de style en *absolute*
```
href="{{site.baseurl}}/assets/css/style.css"
```



##SASS

Le SASS est natif dans jekyll.
Renommer le fichier style.css en style.scss

On y ajoute une en-tête pour jekyll
```


```

Puis des variables

```
$color-primary: #eee;
body{background: $color-primary;}
```
Le lien reste inchanger dans le fichier head.html

---
layout: cours
nom: Boucles jekyll
---


# Généralités

Les valeurs dans l'en-tête sont en YAML, Front Matter.

---

# Structure


Fichier _page.html_ dans le dossier layouts => imbrication de template.


 Accueil | Contact | Equipe
 --- | --- | ---
 layout : default | layout : page | layout : page
  | #titre | #titre


 Flatfiles, fichiers MD.
 dossier site, répertoire des fichier générés, à ne pas modifier.

 ---

# Boucles

```
 {% for page in site.pages %}
  <a href="page.url">{{page.title}}</a>
 {% endfor %}
 ```


 Permet d'afficher le titre de la page dans la page elle-même, sans fichier de template.

 ---

# Billets 

 Créer dossier _posts et dans le dossier _layouts le fichier posts.html.


 Dans index.html :

```
 {% for post in site.posts %}
  <h3>{{post.title}}</h3>
  <p>{{post.content}}</p>
  <a href="{{post.url}}">Lire l'article seul</a>
 {% endfor %}
 ```


 Cette boucle permet d'afficher le titre, le contenu, le résumé etc.

 Placer la boucle dans la page avec l'article.

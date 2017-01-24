---
layout: cours
nom: Template include
---

## Structure :octopus: 

* flatfiles
  * index.html
  * _config.yml
* _layouts
  * default.html


-
index : page d'accueil.

_layouts : dossier des fichiers du template.

dafault.html : template de base, n'y placer que les éléments de base, communs à toutes les pages.

config : variables globales.
-


---

## Élements

Dans index.html, placer "layout: default" dans l'en-tête du fichier, entre les tirets.

Dans default.html, appeler le contenu : {{content}}.

Création de 3 éléments, head.html / header.html / footer.html.

Ces fichiers seront appeler dans le template default.html, on peut séparer d'autres éléments dans des fichiers distinces, comme le menu (nav.html).
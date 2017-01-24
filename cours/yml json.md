---
layout: cours
nom: YML et JSON
---

# Data

Importer ses propres données sur notre site à partir de fichiers YML ou JSON.


- Dossier _data qui contient les fichiers de données
- Page membre dans le tableau Json, lecture des informations du tableau, et affichage :

 nomTableau.attribut 
 ex: member.nom 

# Assignation

- Assignation équipe de football à l'équipe de football d'un membre
```
{% assign footballteam = {{membre.footballteam}} %}
```

- Assignation club et valeur tableau ligue, avec condition WHERE : key, footballteam

# Remarques
Dièse : commentaire en YML.

/!\ modifier les URL entre la version locale et la version en ligne

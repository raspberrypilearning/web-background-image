Tu peux ajouter une image d'arrière-plan qui apparaîtra derrière d'autres éléments de ta page web.

![Un arrière-plan de circuit électronique coloré derrière le contenu principal d'une page web.](images/background-image.png)

Trouve cette déclaration de style dans `style.css` :

--- code ---
---
language: CSS
filename: style.css
line_numbers: false
---

/*ajouter une image d'arrière-plan au corps */

body {
  /*background-image: url('name.jpg');*/ /*Décommenter et changer le nom du fichier pour ajouter une image d'arrière-plan */
  /*background-repeat: repeat;*/ /* Faire répéter l'image */
  /*background-size: cover;*/ /* Faire en sorte que l'image recouvre tout le conteneur */
}

--- /code ---

Supprime les marqueurs de commentaires `/*` et `*/` et remplace `name.jpg` par le nom de ton image d'arrière-plan.

--- code ---
---
language: CSS
filename: style.css
line_numbers: false
---

/* ajouter une image d'arrière-plan au corps */

body {
  background-image: url('mybackground.png'); /*Décommenter et changer le nom du fichier pour ajouter une image d'arrière-plan */
  /*background-repeat: repeat;*/ /* Faire répéter l'image */
  /*background-size: cover;*/ /* Faire en sorte que l'image recouvre tout le conteneur */
}

--- /code ---

Tu peux également essayer de supprimer les commentaires des autres propriétés.

**Astuce :** tu n'as pas besoin de mettre à jour le HTML car ce style s'applique directement à la balise `<body>`. Tu peux créer une classe pour appliquer une image d'arrière-plan à des éléments spécifiques.

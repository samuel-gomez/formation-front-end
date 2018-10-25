# Enoncé : Page CV : les images

- Récupérer le document Word
- Insérer Les images 640/768/1183.png
- Mettre les informations relatives à l’image dans ses attributs (ex: nom de la personne)
- Charger une image différente pour les résolutions à 320, 640, 768
- Définir une taille de container en fonction de la résolution : 320/500/768
- Ajouter une partie Loisirs
  - Un titre
  - Pour représenter chaque loisir, utiliser les figures
- Valider sa page sur le W3C : [https://validator.w3.org/#validate_by_input](https://validator.w3.org/#validate_by_input)

## Explication

L'image renvoyée se base sur le pixel ratio de l'écran.

Le calcul est : 

`taille de l'image / taille du container = ratio`

Si mon pixel ratio est de 2,  

Ratio renvoyé en fonction de la taille de l'image : 

* image de 640px
  * 640/ 320 = 2
  * 640/ 500 = 1,28
  * 640/ 768 = 0,83
* image de 768px
  * 768/ 320 = 2,4
  * 768/ 500 = 1,536
  * 768/ 768 = 1
* image de 1183px
  * 1183/ 320 = 3,69
  * 1183/ 500 = 2,3
  * 1183/ 768 = 1?54


On peut insérer toutes sortes de données dans un tableau : des nombres, des chaines de caractère, des variables et même d'autres tableaux !  
Voici la méthode :
```ruby
["mais", "où", "et", "donc", "or", "ni", "car" ]
```
Attribuons le tableau à un variable pour effectuer des opérations dessus :
```ruby
grammaire = ["mais", "où", "et", "donc", "or", "ni", "car" ]
```

# Rechercher dans un tableau
Gardons notre tableau grammaire.
```ruby
grammaire = ["mais", "où", "et", "donc", "or", "ni", "car" ]
```
Nous pouvons extraire un élément du tableau grâce à son indice. Par exemple si nous voulons afficher `"et"`, il faut écrire la ligne suivante :
```ruby
print grammaire[2]
```
[[attention]]
| Un tableau débute toujours à l'indice 0
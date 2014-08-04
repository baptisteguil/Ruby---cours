En Ruby, vous pouvez convertir des variables en utilisant une *méthode*.  
Nous verrons ce qu'est une *méthode* dans un autre chapitre, ici vous devez juste mettre à la fin de votre variable l'une de ces expressions :

Code  |  Action
------|------
.to_s  |  Convertir en chaine de caractère (string)
.to_i  |  Convertir en entier (int)
.to_f  |  Convertir en flottant (float)
.to_a  |  Convertir en tableau (array)

### Exemple
```ruby
x = 3
x.to_s
```
Prenons le cas d'un programme qui demande l'age à l'utilisateur, ensuite nous voudrions savoir s'il est majeur ou mineur. S'il a moins de 18 ans il est mineur, sinon il est majeur.  
Remarquez les termes `si` et `sinon`, il suffit de les remplacer par leurs équivalent anglais `if` et `else`.

[[information]]
| A partir de maintenant, il va avoir un nombre de lignes de code assez important. Pour écrire le code dans des fichiers, consultez le chapitre [Ecrire le code dans des fichiers]() de la partie [Annexe]().

### Exemple
```ruby
age = gets.chomp

if age < 18 #si age est inférieur à 18
	print "Vous êtes mineur"
else #sinon
	print "Vous êtes majeur"
end

```
[[attention]]
| Toutes les conditions et le boucles se terminent par le mot-clé `end`. Ne l'oubliez pas je ne le répéterai pas !
Ici, nous vérifions si la variable `age` est inférieur à 18 grace à `<`. Essayez de rentrer des âges inférieurs ou supérieurs à 18 et admirez le travail :magicien: .  

# Opérateurs de comparaison
Les conditions (ainsi que les boucles) introduisent de nouveaux opérateurs.
Voici le tableau des opérateurs de comparaison.

Opérateur | Signification
-----|-----
  <  |  Strictement inférieur à
  >  |  Strictement supérieur à
  <= |  Inférieur ou égal à
  >= |  Supérieur ou égal à
  == |  Égale 
  != |  Différent de
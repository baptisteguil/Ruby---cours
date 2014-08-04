Une boucle permet de répéter une instruction tant qu'une condition est vrai.  
Encore une fois, remarquez le terme `tant que`, ici il sera remplacé par sont équivalent anglais `while`.

Pour cet exemple, nous allons faire un programme qui récite un table de multiplication. La boucle se répétera `tant que` la table n'aura pas atteint 10. Voyez plutôt :
```ruby
n = 0
while n < 10 #tant que n est inférieur à 10 exécuter le code
	print n * 8 #ici la table de 8
	n = n + 1 #rajouter 1 à n pour que la boucle ne tourne pas en rond et atteigne 10
	print " "
end
```
Exécutez le programme et voyez par vous même :
```bash
0 8 16 24 32 40 48 56 64 72
```
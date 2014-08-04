`case...when` est une autre forme de condition.  
Prenons l'exemple d'un programme qui vérifierai l'admission ou la mention selon une note à un examen. Dans notre cas, avoir en dessous de 6 est un échec, au dessus de 12 la mention assez bien, de 14 la mention bien et de 16 la mention très bien.  
Faire ce programme avec des `if` et des `else` serait long et contraignant. En effet, la forme de condition `case...when` permettent permet de simplifier en offrant plusieurs choix. Voyez plutôt :

```ruby
note = 18 #Modifiez la note ici 

case note
	when 0..6
		print "Vous n'avez pas réussi l'examen"
	when 6..12
		print "Vous avez réussi l'examen"
	when 12..14
		print "Vous avez réussi l'examen avec mention assez bien"
	when 14..16
		print "Vous avez réussi l'examen avec mention bien"
	when 16..20
		print "Vous avez réussi l'examen avec mention très bien"
	else
		print "La note entrée est incorrecte"
end
```
Je ne vous laisse même pas imaginer la ~~galère~~ l'embêtement que ça aurait été avec des `if` et des `else`.
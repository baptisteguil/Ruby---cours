La boucle `do` sert à afficher les éléments d'un tableau.  
Prenons l'exemple d'un menu de restaurant :
```ruby
menu_viande = ["un steak haché", "une entrecôte", "un rôti", "un faux-filet"]
menu_viande.each do |m|
    print "Voulez-vous " + m + " pour le diner de ce soir ?"
end
```
Tout d'abord, nous déclarons le tableau `menu_viande`. Ensuite nous débutons l'itération qui parcourt chaque élément du tableau, `do` répète les instructions pour chaque élément du tableau. Ça donne donc :
```bash
Voulez-vous un steak haché pour le diner de ce soir ?
Voulez-vous une entrecôte pour le diner de ce soir ?
Voulez-vous un rôti pour le diner de ce soir ?
Voulez-vous un faux-filet pour le diner de ce soir ?
```
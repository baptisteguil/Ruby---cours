Le but du programme que vous allez écrire est de déterminer si une année est bissextile ou non.  
Voici les "règles du jeu" : Une année est dite bissextile si c'est un multiple de 4, sauf si c'est un multiple de 100. Toutefois, elle est considérée comme bissextile si c'est un multiple de 400.  
Ce n'est pas très clair, peut être qu'un arbre vous simplifiera le principe.

- Si une année n'est pas multiple de 4, on s'arrête là, elle n'est pas bissextile.
- Si elle est multiple de 4, on regarde si elle est multiple de 100.
    - Si c'est le cas, on regarde si elle est multiple de 400.
        - Si c'est le cas, l'année est bissextile
        - Sinon, elle n'est pas bissextile.
    - Sinon, elle est bissextile.
Exercice 27
===========

a)  Comme le 25 : il faut diviser le nombre de permutations des 8 lettres par le nombre de permutations des lettres qui reviennent plusieurs fois :

    ..  math::

         \frac{8!}{2!} = 20160

b)  Ce cas est particulièrement difficile. Il faut commencer à placer le premier E. S'il est au début du mot, il reste 6 possibilités pour le deuxième, s'il est en deuxième position, il reste 5 positions possibles pour le deuxième E, s'il est en 3e position, il reste 4 positions possibles pour le deuxième E, etc ...

    Voici les 6 possibles où le premier E se trouve en début de mot

    ::

        E _ E _ _ _ _ _
        E _ _ E _ _ _ _
        ...
        E _ _ _ _ _ _ E

    Voici les 5 possibilités où le premier E se trouve en deuxième position

    ::

        _ E _ E _ _ _ _
        _ E _ _ E _ _ _
        ...
        _ E _ _ _ _ _ E

    Voici les 4 possibilités où le premier E se trouve en deuxième position :

    ::

        _ _ E _ E _ _ _
        _ _ E _ _ E _ _
        ...
        _ _ E _ _ _ _ E

    On peut continuer ainsi jusqu'à la dernière position possible pour le premier E : à savoir la 6e position :

    ::

        _ _ _ _ _ E _ E

    Il n'y a alors qu'une seule possibilité de placer le deuxième E : tout à la fin
    
    Si on fait le bilan des courses, il y a donc 6 + 5 + 4 + 3 + 2 + 1 = 21 façons de placer les E pour qu'ils ne soient pas à côté.

    Comme toutes les autres lettres sont différentes, il suffit de multiplier le nombre de placements possibles pour les E par le nombre de permutations des autres lettres, ce qui fait

    ..  math::

        21 * 6! = 15120

    ..  note::

        Si on est malin, on peut faire le problème beaucoup plus simplement en comptant le nombre de possibilités où les E **sont** côte à côte : 

        ::

            E E _ _ _ _ _ _ 
            _ E E _ _ _ _ _ 
            _ _ E E _ _ _ _
            ...
            _ _ _ _ _ _ E E

            ==> 7 possibilités de mettre les E côté à côté

        Comme il y a :math:`C^{8}_{2}` possibilités de placer les lettres E (de choisir les cases où l'on mettre un E parmi les 8), le nombre de placement où les E ne sont pas côté à côté vaut

        ..  math::

            C^{8}_{2} - 7 = 28 - 7 = 21


c)  On peut donc construire le mot selon les étapes suivantes :

    1.  Choisir les 3 voyelles qui seront au début du mot

        ::

            A E U ==> 6 permutations
            A E E ==> 3 permutations
            U E E ==> 3 permutations

        Ce qui fait en tout 12 permtuations pour le choix des 3 premières voyelles

    2.  placer les autres lettres : il y a alors :math:`5!` permutations possible des 5 dernières lettres qui sont toutes différentes


    Le nombre d'anagrammes vaut donc

    ..  math::

        12 * 5! = 1440
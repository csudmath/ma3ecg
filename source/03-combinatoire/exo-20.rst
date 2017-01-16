Exercice 20
===========

..  warning:: 

    Les personnes au sein d'une délégation sont interchangeables (on ne tient pas compte de l'ordre au sein des délégations) et on ne tient pas non plus compte de l'ordre des délégations.


a)  On constitue les délégations de la manière suivante :

    1.  Choisir 3 personnes parmi 9 pour constituer la première délégation ==> :math:`C^{9}_{3}` possibilités.

    
    2.  Choisir 3 personnes parmi les 6 restantes pour constituer la deuxième délégation ==> :math:`C^{6}_{3}` possibilités.
    
    
    3.  Choisir 3 personnes parmi les 3 restantes pour constituer la deuxième délégation ==> :math:`C^{3}_{3} = 1` possibilités.
    

    ..  admonition:: Au total
        :class: tip

        Comme l'ordre des délégations ne compte pas, il faut diviser le tout par :math:`3!` qui correspond aux permutations possibles d'un ensemble de 3 éléments (les trois délégations).

        Il y a donc 

        ..  math::

            C^{9}_{3}
            \cdot
            C^{6}_{3}
            \cdot
            C^{3}_{3}
            \cdot
            \dfrac{1}{3!}
            =
            280 \text{ possibilités}


b)  On constitue les délégations de la manière suivante :

    1.  Choisir 2 personnes parmi 9 pour constituer la première délégation ==> :math:`C^{9}_{2}` possibilités.

    
    2.  Choisir 3 personnes parmi les 7 restantes pour constituer la deuxième délégation ==> :math:`C^{7}_{3}` possibilités.
    
    
    3.  Choisir 4 personnes parmi les 4 restantes pour constituer la deuxième délégation ==> :math:`C^{4}_{4} = 1` possibilités.
    

    ..  admonition:: Au total
        :class: tip

        Comme les délégations sont discernables de par leur nombre de participants, on ne peut pas les confondre et il n'est cette fois-ci pas nécessaire de diviser par :math:`3!`.
        

        Il y a donc 

        ..  math::

            C^{9}_{2}
            \cdot
            C^{7}_{3}
            \cdot
            C^{4}_{4}
            =
            1260 \text{ possibilités}

 
c)  On constitue les délégations de la manière suivante :

    1.  Choisir 2 personnes parmi 9 pour constituer la première délégation ==> :math:`C^{9}_{2}` possibilités.

    
    2.  Choisir 2 personnes parmi les 7 restantes pour constituer la deuxième délégation ==> :math:`C^{7}_{2}` possibilités.
    
    
    3.  Choisir 5 personnes parmi les 5 restantes pour constituer la deuxième délégation ==> :math:`C^{5}_{5} = 1` possibilités.
    

    ..  admonition:: Au total
        :class: tip

        Comme les deux délégations comportant 2 personnes ne sont pas discernables (on ne peut pas les distinguer), il faut diviser le tout par :math:`2!` (2 étant le nombre de délégations qui ne sont pas discernables entre elles).

        Il y a donc 

        ..  math::

            C^{9}_{2}
            \cdot
            C^{7}_{2}
            \cdot
            C^{5}_{5}
            \cdot
            \dfrac{1}{2!}
            =
            378 \text{ possibilités}

..  warning::

    S'il y avait plusieurs groupes de délégations qui ne sont pas discernables entre elles, par exemple 2 délégations de deux personnes et 4 délégations de 3 personnes, il faudrait diviser par :math:`2! \cdot 4!`
        

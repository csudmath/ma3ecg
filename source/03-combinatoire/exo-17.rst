Exercice 17
===========

a)  Lorsqu'il n'y a pas de contrainte, c'est comme si l'on avait 13 chiens et
    que l'on cherche toutes les possibilités de les placer sur 13 positions en
    tenant compte de l'ordre. Il s'agit donc d'une permutation de 13 éléments
    dont le nombre s'élève à

    ..  math:: 

        P_{13} = 13! = 6227020800.

b)  Le fait que les dalmatiens occupent les places paires veut simplement dire
    qu'il y a 6 places fixes attribuées aux dalmatiens et les restantes aux
    lévriers. Ainsi, le placement se fait en deux étapes :

    1.  Placement des lévriers sur les positions impaires : :math:`P_7 = 7!`
    2.  Placement des dalmatiens sur les positions paires : :math:`P_6 = 6!`

    En tout, le nombre de possibilités s'élève donc à 

    ..  math::

        P_6 \cdot P_7 = 6! \cdot 7! = 3628800.


c)  Pour que les dalmatiens soient à la suite les uns des autres, il faut encore
    rajouter une étape supplémentaire par rapport au point précédent. 
   
    
    1.  Placement du bloc de 6 cases juxtaposées : il y a 8 façons de choisir ce bloc de 6 cases.
    1.  Placement des lévriers sur les positions impaires : :math:`P_7 = 7!`
    2.  Placement des dalmatiens sur les positions paires : :math:`P_6 = 6!`

    En tout, le nombre de possibilités s'élève donc à 

    ..  math::

        8\cdot P_6 \cdot P_7 = 8\cdot 6! \cdot 7! = 29030400.
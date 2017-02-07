Exercice 26
===========

Désignons par la lettre P un lancer qui tombe sur "pile" et par F un lancer qui tombe sur "face".

a)  Cela revient à se demander combien il y a de possibilités d'obtenir le mot FFFFFFFF. Il y a 8 "choix" à faire, mais à chaque fois, on ne peut choisir que "F". Du coup, le nombre de possibilités vaut

    ..  math::

        1^8 = 1

b)  Cela revient à se demander combien il y a de possibilités de choisir deux positions parmi 8 dans lesquelles on mettra un F :

     ..  math::

        C^{8}_{2} = 28

    Le reste des positions seront remplies par des P, ce qui ne constitue pas un choix : les P sont imposés dans toutes les autres cases

c)  Même logique

    ..  math::

         C^{8}_{3} = 56

d)  Même logique

    ..  math::

        C^{8}_{4} = 70


e)  Il faut commencer par calculer le nombre de possibilités au total, sans contraintes, à savoir calculer le nombre de mots que l'on peut faire avec les lettres P et F avec répétitions

    ..  math::

        2^8 = 256

    Ensuite, il faut soustraire le nombre de mots qui ne contiennent pas de F

    ..  math::

        1^{8} = 1

    et le nombre de mots qui contiennent exactement un F 

    ..  math::

        C^{8}_{1} = 8

    Au final, on a donc le nombre suivant de lancers qui contiennent au moins deux faces :

    ..  math::

        256 - 1 - 8 = 247
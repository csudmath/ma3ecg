Exercice 21
===========

a)  On constitue les répartitions de la manière suivante : pour chaque boule, il y a deux choix possibles l'urne de gauche ou celle de droite.
    

    ..  admonition:: Au total
        :class: tip

        Il y a donc :math:`2^{10} = 1024` dispositions différentes


b)  Il faut donc au moins une boule par urne. Pour dénombrer les possibilités où aucune urne est vide, il faut commencer par dénombrer les possibilités pour qu'une urne soit vide. Il y a deux possibilités pour qu'une urne soit vide : soit c'est celle de gauche qui est vide, soit c'est celle de droite. 

    Pour que l'urne de gauche soit vide, il faut que toutes les boules soient mises dans l'urne de droite, et il n'y a qu'une seule façon de le faire : pour chaque boule, il n'y a alors qu'un choix possible : l'urne de droite, ce qui fait :math:`1^{10} = 1` possibilité.

    Pour que l'urne de droite soit vide, c'est pareil et il n'y a qu'une possibilité d'arriver à cette situation : toutes les boules doivent être mises dans l'urne de gauche.

    ..  admonition:: Bilan des courses
        :class: tip

        Il y a donc :math:`1024 - 2 = 1022` possibilités de placer les boules pour qu'aucune des deux urnes ne soit vide.
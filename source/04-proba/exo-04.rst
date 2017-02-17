Exercice 4
===========

a)  L'événement "obtenir un produit de 12" est composé des issues suivantes

    ..  math::

        A = \{ 
            (2;6) ;
            (3;4) ;
            (4;3) ;
            (6;2)
        \}

    La probabilité d'obtenir cet événement vaut donc

    ..  math::

        P(A) = \frac{ \text{ #favorables } } { \text{cas possibles} }
        = 
        \frac{4}{36}
        = 
        \frac{1}{9}


b)  Voici une liste des 14 issues menant à l'événement :math:`B` "Obtenir un produit inférieur ou égal à 6" : 

    ::

        1 1
        1 2
        1 3
        1 4
        1 5
        1 6
        2 1
        2 2
        2 3
        3 1
        3 2
        4 1
        5 1
        6 1

    La probabilité de l'événement vaut donc :math:`P(B) = \frac{14}{36} =0.3\overline{8}`.

c)  L'événement C = "Obtenir un produit plus grand que 6" est exactement le contraire de l'événement :math:`B`. On a donc :math:`C = \overline{B}`. De ce fait, 

    ..  math::

        P(C) = P(\overline{B}) = 1 - P(B) = 1 - \frac{14}{36} = \frac{22}{36}
        =
        \frac{11}{18}
        \approx
        0.6\overline{1}

    Pour obtenir un produit pair, il faut qu'au moins un des deux nombres soit pair. De ce fait, en supposant que le premier nombre est pair, il y a :math:`3 \cdot 6 = 18` possibilités.

    ::

        2 1
        2 2
        2 3
        2 4
        2 5
        2 6
        4 1
        4 2
        4 3
        4 4
        4 5
        4 6
        6 1
        6 2
        6 3
        6 4
        6 5
        6 6

    Mais il y a encore d'autres possibilités d'obtenir un nombre pair : toutes celles où c'est le deuxième nombre qui est pair et le premier impair, à savoir

    ::

        1 2
        3 2
        5 2

        1 4
        3 4
        5 4

        1 6
        3 6
        5 6

    En tout, il y a donc :math:`3\cdot 6 + 3 \cdot 3 = 27` issues qui mènent à un produit pair. La probabilité de l'événement :math:`D = \text{"obtenir un produit pair"}` vaut donc 

    ..  math::

        P() = \frac{27}{36} = \frac{3}{4}

e)  L'événement :math:`E = \text{"obtenir un produit impair"}` est le contraire de :math:`D` et, de ce fait, 

    ..  math::

        P(E) = P(\overline{D}) = 1 - P(D) = 1 - \frac{3}{4} = \frac{1}{4}


..  admonition:: Remarque
    :class: tip

    Il aurait été bien plus facile de commencer par calculer la probabilité d'obtenir un produit impair, car les issues sont celles où les deux nombres sont impairs, ce qui fait :math:`3 \cdot 3 = 9`. On aurait ensuite pu calculer la probabilité d'obtenir un produit pair en passant à l'événement contraire.



salut
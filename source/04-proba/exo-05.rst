Exercice 5
===========

La taille de l'univers :math:`\Omega`, notée :math:`| \Omega | = 6^3 = 216`

a) Soit :math:`A` l'événement "Obtenir le même nombre sur les trois dés. On a  

    ..  math::

        A = \{ 111, 222, 333, 444, 555, 666 \}

    et par conséquent :math:`P(A) = \frac{6}{216} = \frac{1}{36} = 0.02\overline{7}`

b)  Notons :math:`B_i` l'événement "Obtenir une somme égale à :math:`i`. On a alors

    *   :math:`B_1 = \emptyset`
    *   :math:`B_2 = \emptyset`
    *   :math:`B_3 = \{ 111 \}`
    *   :math:`B_4 = \{ 211 ; 121 ; 112 \}`
    *   :math:`B_5 = \{ 122 ; 212 ; 221; 113; 131; 311 \}`

    ..  tip::
    
        De manière générale, on peut déterminer déterminer combien il y a de manière d'obtenir une somme de la manière suivante.

        1)  On commence par écrire les décompositions possibles de la somme sans tenir compte de l'ordre

            *   :math:`5 = 1 + 2 + 2`
            *   :math:`5 = 1 + 1 + 3`

        2)  On détermine le nombre de permutations différentes de ces nombres qu'il est possible de faire. C'est comme si l'on demandait le nombre d'anagrammes possibles avec le mot ABB. Il s'agirait alors de calculer le nombre de permutations de 3 lettres (:math:`3!`) et de diviser par les répétitions : (:math:`2!`). Cela donne donc

        ..  math::

            \frac{3!}{2!}
            =
            \frac{6}{2}
            =
            3

        3)  Additionner le tout. On a donc

            *   1-2-2 ==> :math:`\frac{3!}{2!} = 3` permutations
            *   1-1-3 ==> :math:`\frac{3!}{2!} = 3` permutations

            Ce qui donne au total :math:`3 + 3 = 6` issues possibles pour obtenir la somme 3


c)  Soit :math:`C` l'événement "Obtenir une somme supérieure ou égale à 5". Au lieu de faire tout l'inventaire des issues favorables à :math:`C`, il est préférable de passer par le complément en déterminant la probabilité du contraire, à savoir "Obtenir une somme de 1, 2, 3 ou 4". On a donc

    ..  math::

        \overline{C} = 
        P_1 \cup
        P_2 \cup
        P_3 \cup
        P_4
        =
        P_3 \cup
        P_4

    Comme les événements :math:`P_i` sont incompatibles deux à deux, on peut déterminer 

    ..  math::

        P(C) =
        1 - P(\overline{C}) =
        1 - P(P_3 \cup P_4) =
        1 - \frac{1 + 3}{216} =
        \frac{216 - 4}{216} =
        \frac{212}{216} =
        \approx
        0.981


d)  Soit :math:`D` l'événement "Obtenir un produit inférieur ou égal à 6". Pour déterminer :math:`D`, considérons les événements :math:`P_i` "Obtenir un produit égal à :math:`i`". On a alors

    *   :math:`P_1 = \{ 111 \}` ==> :math:`| P_1 | = 1`
    *   :math:`P_2` contient toutes les permutations différentes de  112 ==> :math:`| P_2 | = \frac{3!}{2!} = 3`
    *   :math:`P_3` contient toutes les permutations différentes de  113 ==> :math:`| P_3 | = \frac{3!}{2!} = 3`
    *   :math:`P_4` contient toutes les permutations différentes de  114 et de 122 ==> :math:`| P_4 | = \frac{3!}{2!} + \frac{3!}{2!} = 6`
    *   :math:`P_5` contient toutes les permutations différentes de  115 :math:`| P_5 | = \frac{3!}{2!} = 3`
    *   :math:`P_6` contient toutes les permutations différentes de  116 ==> :math:`\frac{3!}{2!} = 3` et toutes les permutations de 123 ==> :math:`3! = 6`, ce qui fait en tout 9 possibilités.

    Comme les événements :math:`P_i` sont incompatibles et que :math:`D = P_1 \cup P_2 \cup P_3 \cup P_4 \cup P_5 \cup P_6`, on a :math:`| D | = 1 + 3 + 3 + 6 + 3 + 9 = 25` cas favorables à l'événement :math:`D`. 

    On a donc finalement que :math:`P(D) = \frac{25}{216}`


e)  L'événement :math:`E` "obtenir un produit plus grand que 6" est le contraire de l'événement :math:`D`. On a donc

    ..  math::

        P(E) = P(\overline{D}) = 1 - P(D) = 1 - \frac{25}{216} = \frac{216 - 25}{216} = \frac{191}{216} \approx 0.884

f)  Soit :math:`F` l'événement "Le nombre 1 apparaît exactement une fois". Les cas favorables peuvent être dénombrés de la manière suivante

    1)  Choix de la position du 1 ==> 3 possibilités
    2)  5 choix possibles pour chacune des deux cases restantes ==> 25 possibilités

    Au total, il y a donc :math:`3 \cdot 5^2 = 75` cas favorables. On a donc :math:`P(F) = \frac{75}{216} \approx 0.347`

g)  Soit :math:`G` l'événement "Le nombre 1 apparaît au moiins une fois". Il est préférable de passer par le contraire "n'obtenir aucun 1". Les cas favorables à :math:`\overline{G}` peuvent être dénombrés de la manière suivante : :math:`| \overline{G} | = 5^3 = 125`. Il y a donc :math:`216 - 125 = 91` cas favorables à :math:`G` et 

    ..  math::

        P(G) = \frac{91}{216} \approx 0.421
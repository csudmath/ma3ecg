Exercice 16
===========

a)  Comme on ne tient pas compte de l'ordre des cartes dans une       main, il faut considérer des combinaisons de 12 cartes choisies parmi 36

    ..  math:: 

        C^{36}_{12} = 1251677700

b)  Puisque la main contient les 4 as, ces 4 cartes sont imposées (et ne constituent de ce fait pas un choix). On pourrait dire que l'on doit faire une combinaison de 4 cartes parmi 4, ce qui fait :math:`C^{4}_{4} = \frac{4!}{0!\cdot 4!} = 1` possibilités. Une fois ces 4 as mis dans la main, il reste à choisir :math:`12-4 = 8` cartes parmi :math:`32` puisque les as ne peuvent plus être choisis. 

    ..  admonition:: Au total
        :class: tip

        En multipliant toutes ces possibilités (étapes dans la constitution de la main),
        on obtient :math:`C^{4}_{4} \cdot C^{32}_{8} = C^{32}_{8} = 10518300` possibilités.



c)  Si la main contient exactement 1 as, il faut les étapes suivantes pour constituer la main :

    1.  Choisir l'as : :math:`C^{4}:{1} = 4` possibilités
    2.  On choisit les 11 autres cartes parmi les 32 cartes restantes (puisque aucun des as ne peut être choisi à cette étape)

    ..  admonition:: Au total
        :class: tip

        Il y a donc :math:`C^{4}_{1} \cdot C^{32}_{11} = 516097920` possibilités.



d)  Comme la main ne contient ni as ni roi, on doit choisir 12 cartes parmi :math:`36 - 2\times4 = 28`


    ..  math:: 

        C^{28}_{2} = 30421755


e)  Il faut que la main contienne 1, 2, 3 ou 4 rois. Il est très fastidieux de calculer directement toutes ces cas. Lorsque la donnée contient le mot "au moins", il faut passer par le cas contraire en calculant le nombre de mains qui ne comportent aucun roi.

    *   Nombre de mains ne comportant pas de rois : choisir 12 cartes parmi 32 : :math:`C^{32}_{12}`.

    *   Nombre de possibilités totales - nombre de possibilités sans roi

    ..  admonition:: Au total
        :class: tip

        Il y a donc :math:`C^{36}_{12} - C{32}_{12} = 1025884860` possibilités.



f)  La main doit donc contenir aucun roi ou 1 seul roi. Il suffit d'additionner ces deux cas :

    *   Aucun roi (12 parmi 32) : :math:`C^{32}_{12}`
    *   Exactement 1 roi = comme le c) : :math:`C^{4}_{1} \cdot C^{32}_{11} = 4 \cdot C^{32}_{11}= 516097920`

    ..  admonition:: Au total
        :class: tip

        Il y a donc :math:`C^{32}_{12} + 4 \cdot C^{32}_{11} = 741890760` possibilités.

        

g)  étapes dans le choix des cartes

    1.  Comme l'as de trèfle est imposé, cela ne constitue pas un choix ==> 1 possibilité de choix. 

    2.  Choix des carreaux : 4 parmi 9 : :math:`C^9_4`

    3.  Il ne reste plus que 36 - 1 - 9 = 26 cartes parmi lesquelles choisir les 12 - 1 - 4 = 7 cartes restantes : :math:`C^{26}_{7}`

    ..  admonition:: Au total
        :class: tip

        Il y a donc :math:`1 \cdot C^9_4 \cdot C^{26}_{7} = 82882800` possibilités.


h)  Là encore, il faut procéder par étapes :

    1.  Choisir les 5 piques : :math:`C^{9}_{5}`
    2.  Choisir les 4 coeurs : :math:`C^{9}_{4}`
    3.  Choisir les 2 carreaux : :math:`C^{9}_{2}`
    4.  Choisir les 1 trèfle : :math:`C^{9}_{1}`

    ..  admonition:: Au total
        :class: tip

        Il y a donc :math:`C^{9}_{5} \cdot C^{9}_{4} \cdot C^{9}_{2} \cdot C^{9}_{1} = 5143824` possibilités.

i)  Cet item est certainement le plus difficile de tout l'exercice. Voici les étapes nécessaires pour constituer la main

    1.  Choix de la couleur parmi laquelle choisir les 5 cartes (attention il y a 4 couleurs : coeur, carreaux, trèfles, piques) : 4 possibilités

    2.  Choisir les 5 cartes de cette première couleur : :math:`C^{9}_{5}`

    3.  Choix de la deuxième couleur dont on prendra 4 cartes : 3 possibilités

    4.  Choisir les 4 cartes de cette deuxième couleur : :math:`C^{9}_{4}`

    5.  Choix de la troisième couleur dont on prendra 2 cartes : 2 possibilités

    6.  Choisir les 2 cartes de cette troisième couleur : :math:`C^{9}_{2}`

    7.  Choix de la quatrième couleur dont on prendra 1 cartes : 1 seul possibilité restante

    8.  Choisir la carte de cette quatrième couleur : :math:`C^{9}_{1} = 9`

    ..  admonition:: Au total
        :class: tip

        Il y a donc :math:`4 \cdot 3 \cdot 2 \cdot 1 \cdot C^{9}_{5} \cdot C^{9}_{4} \cdot C^{9}_{2} \cdot C^{9}_{1} = 4! \cdot C^{9}_{5} \cdot C^{9}_{4} \cdot C^{9}_{2} \cdot C^{9}_{1} = 123451776` possibilités.


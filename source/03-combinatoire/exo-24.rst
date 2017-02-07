Exercice 24
===========

Les carreaux de même couleurs sont indiscernables. Il y a deux façons de voir ce problème

Première méthode
----------------

La première méthode consiste à s'imaginer tous les rectangles alignés les uns après les autres dans l'ordre et que l'on va peindre les 5 premiers en rouge, les 7 suivants en bleu, les 3 suivants en jaune et les 3 derniers en noir. 

Vu comme ceci, le problème revient alors à déterminer le nombre de permutations qu'il y a de l'ensemble de carreaux, ce qui fait :math:`18!`.

Mais attention, puisque les 5 premiers carreaux seront tous rouges (ce qui les rend indiscernables), leur ordre ne compte pas et il faut diviser par le nombre de permutations de cet ensemble de 5 carreaux, à savoir :math:`5!`. De même, puisque 7 carreaux bleus sont indiscernables entre eux, il faut encore diviser par les permutations de cet ensemble de 7 éléments, à savoir :math:`7!`. Il faut encore faire de même pour les permutations des deux derniers sous-ensembles de carreaux de taille 3.

Au final, le nombre de possibilités différentes de changer l'ordre des carreaux sera

..  math::

     \frac{18!}{5!\cdot 7!   \cdot 3! \cdot 3!} = 294053760


Deuxième méthode 
----------------

La deuxième méthode consiste à effectuer plusieurs choix successifs :

1.  Choisir les 5 carreaux qui seront peints en rouge parmi 18, ce qui fait :math:`C^{18}_{5}`.


2.  Choisir les 7 carreaux qui seront peints en bleu parmi les 13 restants, ce qui fait :math:`C^{13}_{7}`.


3.  Choisir les 3 carreaux qui seront peints en jaune parmi 6 restants, ce qui fait :math:`C^{6}_{3}`


4.  Choisir les 3 carreaux qui seront peints en noir parmi les 3 derniers carreaux restants, ce qui fait :math:`C^{3}_{3} = 1`

Au final, le nombre de coloriages différents vaut donc

..  math::

    C^{18}_{5} \cdot C^{13}_{7} \cdot C^{6}_{3} \cdot C^{3}_{3} = 294053760


..  note:: 

    Remarquez que les deux calculs sont parfaitement équivalents. En effet, 

    ..  math::

        C^{18}_{5} \cdot C^{13}_{7} \cdot C^{6}_{3} \cdot C^{3}_{3}
        =
        \frac{18!}{13! \cdot 5!}
        \cdot
        \frac{13!}{6! \cdot 7!}
        \cdot
        \frac{6!}{3! \cdot 3!}
        \cdot
        \frac{3!}{3!\cdot 0!} \\
        =
        \frac{18!}{5!\cdot 7!   \cdot 3! \cdot 3!} = 294053760

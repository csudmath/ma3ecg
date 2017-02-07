Exercice 25
===========

Il faut tout d'abord remarquer que le mot ``COMBINATOIRE`` contient 2 lettres
``I`` et deux lettres ``O``. De ce fait, le nombre d'anagrammes possibles
correspond au nombre de permutations possibles des 12 lettres constituant le mot
``COMBINATOIRE``. Mais comme il ne faut pas compter à double permutations des deux lettres ``I``, il faut diviser par le nombre de permutations des ``I`` (:math:`2! = 2`). Il faut faire pareil pour les permutations des deux lettres ``O``.

On a donc au final le nombre suivant d'anagrammes :

..  math::

    \frac{12!}{2! \cdot 2!} = 119750400
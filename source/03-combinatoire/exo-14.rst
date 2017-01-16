Exercice 14
===========

Pour que le professeur puisse raconter 3 histoires par année sans jamais redire les trois mêmes histoires (on ne tient pas compte de l'ordre), il faut que :math:`C^{x}_{3} \geq 40` où :math:`x` est le nombre d'histoires dont il dispose. 

Il y a deux manières de résoudre ce problème qui revient en fait à résoudre l'inéquation :math:`C^{x}_{3} \geq 40` :

1)  Par tâtonnement (il est évident qu'il faut que :math:`x > 3`) 

    *   Pour :math:`x = 4`, on a :math:`C^{x}_{3} = C^{4}_{3} = \frac{4!}{1! \cdot 3!} = 4`, ce qui est trop petit.
    *   Pour :math:`x = 5`, on a :math:`C^{x}_{3} = C^{5}_{3} = \frac{5!}{2! \cdot 3!} = 10`, ce qui est trop petit.
    *   Pour :math:`x = 6`, on a :math:`C^{x}_{3} = C^{6}_{3} = \frac{6!}{3! \cdot 3!} = 20`, ce qui est trop petit.
    *   Pour :math:`x = 7`, on a :math:`C^{x}_{3} = C^{7}_{3} = \frac{7!}{4! \cdot 3!} = 35`, ce qui est trop petit.
    *   Pour :math:`x = 8`, on a :math:`C^{x}_{3} = C^{8}_{3} = \frac{8!}{5! \cdot 3!} = 56`, ce qui permet de tenir pendant les 40 ans en ne racontant jamais les trois mêmes histoires.
    

2)  Vous savez sans doute qu'on préfère une méthode qui fonctionne à tous les coups plutôt que de devoir se contenter de tâtonner. On peut y parvenir en résolvant l'inéquation 

    ..  math:: 

        C^{x}_{3} \geq 40, x \in \mathbb{N} \\
        \dfrac{x!}{(x-3)! \cdot 3!} \geq 40 \\
        \dfrac{x\cdot (x-1) \cdot (x-2) }{3!} \geq 40 \\
        \dfrac{x\cdot (x-1) \cdot (x-2) }{6} \geq 40 \\
        \dfrac{ x^3 - 3x^2 + 2x }{6} \geq 40 \\
        x^3 - 3x^2 + 2x  \geq 240 \\
        x^3 - 3x^2 + 2x  - 240 \geq 0 \\
    
    Le problème est que cette inéquation est du troisème degré. Il est cependant possible de la résoudre graphiquement avec vos connaissances pour trouver la réponse :

    ..  figure:: https://s3.amazonaws.com/grapher/exports/e3e7gxpunw.png
        :align: center

        Résolution graphique de l'inéquation :math:`x^3 - 3x^2 + 2x  - 240 \geq 0`
    
    On voit bien que la courbe passe en-dessus de l'axe :math:`Ox` entre 7 et 8. Comme :math:`x` doit prendre des valeurs entières, il faut donc que soit au minimum de 8. Il lui faut donc au minimum 8 histoires.


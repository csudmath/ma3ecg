Exercice 9
===========


..  tip::   

    *   Lorsque l'on fait un tirage **simultané**, on ne tient pas compte de
        l'ordre de tirage puisque toutes les boules sont tirées en même temps.

    *   Puisque tous les objets sont des entités différentes, il faut imaginer
        qu'ils ont deux attributs : un couleur et un numéro. On pourrait donc
        représenter tout le sachet de la manière suivante

        ..  math::

            \{ R_1 ; R_2 ; R_3 ; B_1 ; B_2 ; B_3 ; B_4 ; J_1 ; J_2 ; J_3 ; J_4 ; J_5 \}

    *   Dans tout l'exercice, on tire toujours trois boules dans un sac de 12.
        Le nombre de possibilités sans contrainte (cas possibles au dénominateur de
        la probabilité) est donc toujours

        ..  math::

            C^{12}_3 = 220



a)  Soit :math:`A` l'événement "Les trois objets sont jaunes"

    ..  admonition:: Cas favorables
        :class: tip
    
        Nombre de combinaisons différentes de choix de 3 "J" parmi les 5, sans tenir compte de l'ordre :math:`C^5_3`



    ..  math::

        P(A) = 
        \frac{C^5_3}{C^{12}_3}
        = 
        0.0\overline{45}

b)  Soit :math:`B` l'événement "tirer un objet de chaque couleur"

    ..  admonition:: Cas favorables
        :class: tip
    
        Il y a :math:`C^3_1 = 3` possibilités de tirer un
        rouge, :math:`C^4_1 = 4` possibilités de tirer un bleu et :math:`C^5_1 = 5`
        possibilités de tirer un jaune. De ce fait, le nombre de possibilités de tirer les lettres RBJ est, sans tenir compte de l'ordre, :math:`C^3_1 \cdot C^4_1 \cdot C^5_1`.

        ..  math::

            C^3_1 \cdot C^4_1 \cdot C^5_1


    De ce fait, la probabilité vaut

    ..  math::

        P(B) =
        \frac{
            C^3_1 \cdot C^4_1 \cdot C^5_1
        }
        {C^{12}_3}
        =
        0.\overline{27}


c)  Soit :math:`C` l'événement "Aucun objet n'est rouge".

    ..  attention:: 

        Le contraire de "Aucun objet n'est rouge" n'est pas "Tous les objets sont rouges" mais "Au moins un objet est rouge".


    ..  admonition:: Cas favorables
        :class: tip

        Puisque l'on ne peut pas tirer un objet rouge, il n'y a que 9 objets possibles. Il y a donc 9 objets parmi lesquels choisir les 3 objets, à savoir :math:`C^9_3`.


    De ce fait, la probabilité vaut

    ..  math::

        P(C) =
        \frac{
            C^9_3
        }
        {C^{12}_3}
        =
        0.3\overline{81}


d)  Soit :math:`D` l'événement "Au moins un objet rouge".

    Les événements :math:`C` et :math:`D` sont contraires. De ce fait, la probabilité vaut

    ..  math::

        P(D) = P(\overline{C}) = 1 - P(C)
        =
        1 - \frac{
            C^9_3
        }
        {C^{12}_3}
        =
        0.6\overline{18}


e)  Soit :math:`E` l'événement "Au moins deux objets bleus".

    ..  admonition:: Cas favorables
        :class: tip

        Il y a deux cas à traiter

        1.  Deux objets bleus et un autre objet : :math:`C^4_2 \cdot C^8_1`

        2.  Trois objets bleus : :math:`C^4_3`

        Au final, le nombre de cas favorables est donc

        ..  math::

            C^4_2 \cdot C^8_1 + C^4_3 = 52


    De ce fait, la probabilité vaut

    ..  math::

        P(E) =
        \frac{
            C^4_2 \cdot C^8_1 + C^4_3
        }
        {C^{12}_3}
        =
        0.23\overline{63}



f)  Soit :math:`F` l'événement "Au moins un objet rouge".

    Les événements :math:`E` et :math:`F` sont contraires. De ce fait, la probabilité vaut

    ..  math::

        P(F) = P(\overline{E}) = 1 - P(E)
        =
        1 - \frac{
            C^4_2 \cdot C^8_1 + C^4_3
        }
        {C^{12}_3}
        =
        0.76\overline{36}
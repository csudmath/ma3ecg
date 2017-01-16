Exercice 22
===========

a)  On constitue les répartitions de la manière suivante : pour chaque boule, il y a 3 choix possibles :
    

    ..  admonition:: Au total
        :class: tip

        Il y a donc :math:`3^{10} = 59049` répartitions différentes


b)  Cette partie est plus subtile que dans l'exercice 21 car il y a deux nombreuses façons pour qu'il y ait au moins une urne vide. Les situations suivantes mènent au cas où au moins une urne est vide

    *   la première est vide ==> :math:`2^{10} = 1024` possibilités de placer les boules
    *   la deuxième est vide ==> :math:`2^{10} = 1024` possibilités de placer les boules
    *   la troisième est vide ==> :math:`2^{10} = 1024` possibilités de placer les boules
    *   la première et la deuxième sont vides ==> :math:`1^{10} = 1` possibilités de placer les boules
    *   la première et la troisième sont vides ==> :math:`1^{10} = 1` possibilités de placer les boules
    *   la deuxième et la troisième sont vides ==> :math:`1^{10} = 1` possibilités de placer les boules



    ..  admonition:: Bilan des courses
        :class: tip

        Il y a donc :math:`59049 - 3 \cdot 1024 - 3 = 55974` possibilités de placer les boules pour qu'aucune des trois urnes ne soit vide.
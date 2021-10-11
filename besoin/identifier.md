Identifier les besoins de manière unique
=======================================

Les **besoins** doivent être identifiés de manière unique. Il faut en effet que chaque besoin ait un identifiant unique dans votre projet.

Cet identifiant permet de distinguer le besoin de n'importe quel autre besoin quel que soit son état d'avancement.

Si les besoins n'ont pas d'identifiant, on peut mélanger plusieurs besoins. Cela a pour conséquence de mal maîtriser la gestion des besoins. Au pire, on peut oublier des besoins et ainsi ne pas réaliser un logiciel correspondant aux besoins exprimés.

Objectif
--------

Cette pratique est très simple à mettre en oeuvre. Il suffit de donner un identifiant unique à chaque besoin.

La manière la plus simple est d'attribuer un numéro à chaque création de besoin. Ce numéro peut être construit de manière incrémental (on commence à partir du numéro 1 et on ajoute 1 à chaque nouveau besoin).

Il est déconseillé de donner une sémantique à l'identifiant pour par exemple donner du sens au besoin. Certains projets utilisent des préfixes aux identifiants pour grouper les besoins entre eux. Au long terme, cela est contre productif. Il vaut mieux garder un unique objectif qui est d'identifier les besoins de manière unique dans le projet.

Contrôle
--------

Pour contrôler cette pratique, il suffit de parcourir tous les besoins et de vérifier qu'ils ont chacun un identifiant unique. On peut alors prouver que cette pratique est bien respectée.

On peut même demander quel mécanisme est utilisé pour trouver un nouvel identifiant.

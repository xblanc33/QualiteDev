Identifier les issues de manière unique
=======================================

Les **issues** doivent être identifiées de manière unique. Il faut en effet que chaque issue ait un identifiant unique dans votre projet.

Cet identifiant permet de distinguer l'issue de n'importe quelle autre issue quel que soit son état d'avancement.

Si les issues n'ont pas d'identifiant, on peut mélanger plusieurs issues. Cela a pour conséquence de mal maîtriser la gestion des issues. Au pire, on peut oublier des issues et ainsi ne pas réaliser un logiciel correspondant au besoin exprimé.

Objectif
--------

Cette pratique est très simple à mettre en oeuvre. Il suffit de donner un identifiant unique à chaque issue.

La manière la plus simple est d'attribuer un numéro à chaque création d'issue. Ce numéro peut être construit de manière incrémental (on commence à partir du numéro 1 et on ajoute 1 à chaque nouvelle issue).

Il est déconseillé de donner une sémantique à l'identifiant pour par exemple donner du sens à l'issue. Certains projets utilisent des préfixes aux identifiants pour grouper les issues entre elles. Au long terme, cela est contre productif. Il vaut mieux garder un unique objectif qui est d'identifier les issues de manière unique dans le projet.

Contrôle
--------

Pour contrôler cette pratique, il suffit de parcourir toutes les issues et de vérifier qu'elles ont chacune un identifiant unique. On peut alors prouver que cette pratique est bien respectée.

On peut même demander quel mécanisme est utilisé pour trouver un nouvel identifiant.

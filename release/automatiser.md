Automatiser la production des releases
=====================================

Construire une release est une opération importante. Il faut d'abord s'assurer de la qualité de tous les éléments constituant la release (que le code compile, qu'il soit de qualité, que les tests passent, que la documentation soit à jour, etc.). Une fois cela fait, il faut packager tous ces artefacts et permettre leur installation. Enfin, il faut s'assurer que l'installation de la release est aisée.

Réaliser cette opération manuellement est source d'erreur. Il faut donc automatiser la production des releases pour offrir des garanties quant à leur qualité.

Objectif
--------

L'automatisation de la production des releases nécessite de disposer d'une chaîne de production logiciel. Cette chaîne sert la qualité du [code source](../code), des [tests](../test) et de la [doc](../doc).

Elle doit de plus assurer le packaging des ressources constituant la release, vérifier que la release est facilement installable et enfin l'archiver.

Contrôle
--------

Vérifier l'automatisation de la production des releases ne peut se faire que par un expert.

L'expert va regarder la chaîne de production logiciel et vérifier que celle-ci remplie bien ses missions.

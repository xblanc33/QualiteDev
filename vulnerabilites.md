_Coder sans vulnérabilités_
==========================

Tout développement logiciel doit être réalisé en ayant en tête les possibles vulnérabilités
qui découlent d'une mauvaise utilisation d'une bibliothèque, d'un manque de vérification des
données externes, de mauvaises pratiques de programmation.

Les failles découvertes dans les logiciels sont répertoriées au sein des [Common Vulnerability and Exposure](https://cve.mitre.org).

Pour le cas des applications web, les causes des failles les plus souvent répertoriées sont disponibles
sur le site de [Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page).

Objectif
--------

L'objectif de cette pratique est de s'assurer que tout membre de l'équipe de développement
est conscient des failles les plus courantes existant autour des langages et bibliothèques utilisées.

Il est important de s'abonner aux listes de notification d'alertes de sécurité des bibliothèques ou logiciels utilisés.

Il est important d'utiliser des outils d'analyse statique de code pour vérifier de manière automatique que
les vulnérabilités courantes sont prises en compte dans le développement de l'application.

Contrôle
--------

Le contrôle de cette pratique se fait essentiellement par revue de code par un expert.

Si un outil d'analyse statique de code est mis en place, il est possible de surveiller les métriques de vulnérabilité
durant le cycle de développement.

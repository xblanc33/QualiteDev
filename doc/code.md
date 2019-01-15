Documenter le code
==================

Le code source d'une application doit-il être documenté ou le code s'explique-t-il lui même ?

A cette question, la réponse de Robert C. Martin est des plus éclairée : **"ne commentez pas un code mal écrit, réécrivez le !"**

Avec ce principe en tête, on comprend rapidement que la documentation du code doit être très légère, mais surtout qu'elle ne doit être écrite que si elle ajoute quelque chose au code.

Objectif
--------

Cette pratique consiste à bien documenter le code source de son application. Pour ce faire, il n'existe qu'une seule règle : le bon sens.

Déjà, il est toujours intéressant de rapidement documenter l'architecture de votre application. Un petit document, même très léger et très haut niveau, aide à mieux comprendre l'architecture globale d'une application. On peut y décrire les principaux composants, leur responsabilité et leurs relations. Sans cette documentation, les nouveaux développeurs auront plus de mal à comprendre le code, et ils devront passer beaucoup plus de temps à appréhender l'architecture de l'application avant de ne pouvoir être opérationnels.

Ensuite, il faut évidemment documenter les API. Pour ce faire, il est très intéressant d'exploiter les outils de documentation (JavaDoc, Doxygen, OpenAPI, etc.) qui permettent d'écrire la documentation dans le code et de générer des documentations en HMTL.

Enfin, la documentation des instructions dans le code source est à prendre avec des pincettes. C'est envisageable sur de très rares cas.

Contrôle
--------

Vérifier la documentation du code source ne peut se faire que par l'audit d'un expert.

L'expert va vérfier que la documentation de l'architecture existe, ainsi que celle des API, et enfin que les instructions dans le code ne sont pas commentées.

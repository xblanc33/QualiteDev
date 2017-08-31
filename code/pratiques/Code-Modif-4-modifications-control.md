 Type | ID | Importance
 ---- | -- | --
 Code source | Code-Modif-3 | Incontournable

Les modifications (commit) doivent être vérifiés
================================================

Chaque modification (commit) est réalisé par un développeur. De fait, l'erreur étant humaine, elle peut contenir des fautes.

Tous les commits doivent donc être vérifié avant d'être réellement appliqué. Cette vérification devrait se faire par d'autre développeurs que l'auteur du commit. Un commit vérifié avant son application a de plus grande chance de voir les potentielles erreurs qu'il contient détectéee. La qualité du code sera ainsi fortement améliorée.

Si un commit n'est pas vérifié, les potentielles erreurs qu'il contient ne seront détectées que plus tardivement. Cela a donc un impact négatif sur la qualité du code. 



Objectif
--------

Tout commit doit être vérifié avant d'être intégré définitivement au code source. 

Il faut donc mettre en place des mécanismes permettant la vérification au plus tôt des commits. Cette vérification peut se faire en utilisant par exemple le concept de pull-request proposé dans des plates-formes telles que GitHub.

Contrôle
--------
Cette pratique peut être prouvée si un mécanisme automatique de vérification (pull-request) a été mis en place. 
La preuve consiste simplement à vérifier que le mécanisme a été mise en place et qu'il est mis en oeuvre. 

Si aucun mécanisme automatique n'a été mis en place, cette pratique n'est pas prouvable et il n'est pas non plus possible de disposer d'indices permettant de mesurer son application. Il est donc uniquement possible d'avoir des impressions quant à son suivie, en demandant aux développeurs si des revues de code sont réalisée lors de chaque commit.


Contrôler les modifications du code (l'intégration)
===================================================

Chaque modification (commit) est réalisé par un développeur. De fait, l'erreur étant humaine, elle peut contenir des fautes.

Tous les commits doivent donc être vérifiés avant d'être réellement intégrés. Cette vérification devra se faire par quelqu'un autre que l'auteur du commit.
L'objet de cette vérification est multiple: la compilation se fait, les tests passent, le code suit les chartes de qualité, etc.

Il existe différentes façons de faire cette vérification : revue de code, check automatisé lors d'une pull-request, validation d'un développeur plus chevronné (l'intégrateur), etc.

Un commit vérifié ainsi avant son intégration a de plus grande chance de voir les potentielles erreurs qu'il contient détectées. La qualité du code sera ainsi fortement améliorée.

Si un commit n'est pas vérifié, les potentielles erreurs qu'il contient ne seront détectées que plus tardivement. Cela a donc un impact négatif sur la qualité du code.

Objectif
--------

Tout commit doit être vérifié avant d'être intégré définitivement au code source.

Il faut donc mettre en place des mécanismes permettant la vérification au plus tôt des commits. Cette vérification peut se faire en mettant en place une approche de code review plus ou moins automatisée.

Contrôle
--------
Cette pratique peut être prouvée si un mécanisme automatique de vérification (pull-request) a été mis en place.
La preuve consiste simplement à vérifier que le mécanisme a été mis en place et qu'il est mis en oeuvre.

Si aucun mécanisme automatique n'a été mis en place, cette pratique n'est pas prouvable et il n'est pas non plus possible de disposer d'indices permettant de mesurer son application. Il est donc uniquement possible d'avoir des impressions quant à son suivi, en demandant aux développeurs si des revues de code sont réalisées lors de chaque commit.

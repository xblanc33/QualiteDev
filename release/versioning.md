_Choisir une politique d'identifiant de version_
==========================

Il est important de décider d'une politique d'identification des versions qui indique clairement
si la nouvelle version apporte simplement des correctifs de sécurités, des modifications mineures 
dans les fonctionnalités ou des changements majeurs.

En effet, des correctifs de sécurité doivent être appliqués de toute urgence. Les changements
apportés par la nouvelle version seront très limités pour ne pas nécessiter une nouvelle qualification 
en environnement de production.

Une mise à jour de fonctionnalité mineure garantira généralement une compatibilité ascendante, donc
limitera les problèmes de mise à jour en production. Si une validation en environnement de recette 
est nécessaire, il est cependant attendu que la qualification ne prenne pas trop de temps.

Une mise à jour de fonctionnalité majeure ne garantira généralement pas une compatibilité ascendante 
totale. Il y aura généralement des problèmes de compatibilités de dépendances, de greffons, de logiciels 
tiers qui demanderont un effort de qualification important avant mise en production.

Objectif
--------

Ce principe a pour but d'aider l'utilisateur à déterminer rapidement à la dénomination de la version
la criticité de la mise à jour, et l'effort qui sera nécessaire pour la qualifier en production.

Une numérotation des versions sous la forme `X.Y.Z` horodatée avec

- `X` la version majeure
- `Y` la version mineure
- `Z` la version des correctifs  

est souvent utilisée.

Une autre solution est d'utiliser une version horodatée (année, mois) ou (année, mois, jour) avec un qualificatif
*Long Term Support* pour les versions qui ont vocation à être mises à jour sur la durée, et qui serviront de
référence pour la compatibilité ascendante.

Contrôle
--------

Le contrôle ne peut être fait que par un expert.

Il existe des outils qui permettent de gérer de manière automatique la numérotation de type `X.Y.Z` lors du processus de développement.


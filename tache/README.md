Recueil de bonnes pratiques pour les taches
============================================

Une tâche, c'est quoi ?
------------------------

Une **tâche** décrit un travail qui va être effectué par un développeur dans l'objectif de réaliser une ou plusieurs [issues](../issue).

Faire une tâche c'est essentiellement [coder](../code) mais cela peut aussi être la rédaction ou l'exécution d'un test ([tester](../test)), d'une [documentation](../doc) ou la construction et le déploiement d'une [release](../release).

Une tâche a bien souvent une granularité fine, limitée dans le temps et l'espace. Une tâche est souvent affectée à un seul développeur et ne nécessite au plus que quelques jours de travail. Si une tâche est réalisée par plusieurs développeurs et nécessite plusieurs jours c'est bien souvent qu'elle est mal dimensionnée. Une très grande tâche est une entreprise bien plus grande (un mini projet) qui nécessite la réalisation de plusieurs tâches (plus petites).

Une tâche doit être précise. Les tâches sont bien souvent rédigées par des développeurs et faites par d'autres développeurs. Il faut donc que les développeurs qui feront les tâches comprennent sans ambiguité ce qu'ils doivent faire. La "definition of done" doit être des plus précise. En outre, si la tâche est du code, les tests sont-ils inclus dans la tâche ou sont-ils dans une autre tâche ? Impossible de répondre à cette question sans détailler très précisement la tâche.

Une tâche est obligatoirement liée à une ou plusieurs issues. Sinon c'est qu'un travail est fait mais qu'il ne sert pas l'objectif du besoin. En principe, la réalisation d'une issue nécessite de faire plusieurs tâches. Certaines tâches, les tâches d'infrastructure par exemple (installation d'un environnement de développement, de test ou d'intégration continu), sont naturellement liées à toutes les issues d'un projet. Si les tâches ne sont pas liées aux issues ou si le lien n'est pas explicite, on ne peut alors pas savoir ce qu'il reste à faire (RAF: Reste A Faire) pour réaliser une issue. On n'a alors aucune vision sur l'avancement du projet.

Une fois rédigées, l'équipe peut s'organiser pour savoir qui doit faire quelle tâche et quand. Pour se faire il existe deux grandes méthodes. La première méthode vise à trouver l'organisation la plus idéale en temps et en ressources. Cette organisation est classiquement faite par le chef de projet qui va ordonner les tâches en fonction de leur coût (en temps) et des ressources dont il dispose. La deuxième méthode consiste à laisser l'équipe (et donc les développeurs) s'organiser dynamiquement. Chaque développeur peut par exemple choisir tous les matins les tâches qu'il peut faire dans la journée. Si l'organisation n'est pas faite les tâches n'avancent pas, et le projet se transforme en échec.

Dès lors que l'organisation est faite, il ne reste plus qu'à faire les tâches et à suivre leur réalisation. Classiquement on dit qu'une tâche est "à faire", "en cours de réalisation" et "faite". Bien évidemment il est possible d'ajouter d'autre étape si on veut faire un suivi plus précis de l'avancement des tâches. Le suivi des tâches est absolument indispensable pour mesurer l'avancement du projet. Il permet de connaître la vitesse de croisière du projet (combien d'issue sont réalisée en combien de temps) et permet ainsi de faire des projections sur les dates de livraison.

Qu'est-ce que la qualité d'une tâche ?
--------------------------------------

Les tâches sont au coeur de l'avancement du projet. La qualité des tâches d'un projet fait la qualité réelle d'un projet.

La qualité d'une tâche c'est essentiellement sa rédaction et sa gestion :

* la granularité qui doit être limitée
* la précision qui doit être très fine
* le lien avec les issues qui doit être clairement défini
* l'organisation qui doit être établie
* le suivi qui doit être réalisé

Liste des bonnes pratiques :
----------------------------

### Rédaction

* [limiter le travail demandé par une tâche](./limiter.md)
* [préciser le travail à faire](./preciser.md)
* [lier les tâches aux issues](./lier.md)

### Gestion 

* [organiser vos tâches](./organiser.md)
* [faire un suivi de l'avancement des tâches](./suivre.md)

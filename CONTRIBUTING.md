# Contribuer à CONTRIBUTING.md

Tout d'abord, merci d'avoir pris le temps de contribuer ! ❤️

Tous les types de contributions sont encouragés et appréciés. Voir la [Table des matières](#table-of-contents) pour les différentes façons de contribuer et les détails sur la façon dont ce projet les gère. Veillez à lire la section correspondante avant d'apporter votre contribution. Cela nous facilitera la tâche, à nous les mainteneurs, et facilitera l'expérience de toutes les personnes impliquées. La communauté attend vos contributions avec impatience. 🎉

> Et si vous aimez le projet, mais que vous n'avez pas le temps d'y contribuer, ce n'est pas grave. Il existe d'autres moyens simples de soutenir le projet et de montrer votre appréciation, et nous en serions également très heureux :
> - Mettez le projet en vedette
> - Tweeter à propos du projet
> - Faites référence à ce projet dans le fichier readme de votre projet
> - Mentionnez le projet lors de rencontres locales et parlez-en à vos amis/collègues


## Table des matières

- Code de conduite](#code-de-conduite)
- [J'ai une question](#i-j'ai-une-question)
- [Je veux contribuer](#i-jeveux-contribuer)
- [Signaler des bogues](#reporting-bugs)
- [Suggérer des améliorations](#suggesting-enhancements)
- [Votre première contribution au code](#votre-première-contribution-au-code)
- [Améliorer la documentation](#améliorer-la-documentation)
- [Guides de style](#guides de style)
- Messages d'engagement](#messagesd'engagement)
- [Rejoindre l'équipe du projet](#join-the-project-team)


## Code de conduite

Ce projet et tous ceux qui y participent sont régis par le code de conduite suivant
Code de conduite [CONTRIBUTING.md](blob/master/CODE_OF_CONDUCT.md).
En participant au projet, vous devez respecter ce code. Veuillez signaler tout comportement inacceptable
à <>.


## J'ai une question

> Si vous souhaitez poser une question, nous supposons que vous avez lu la [Documentation]() disponible.

Avant de poser une question, il est préférable de rechercher les [Problèmes](/issues) existants qui pourraient vous aider. Si vous avez trouvé un problème approprié et que vous avez encore besoin d'éclaircissements, vous pouvez écrire votre question dans ce problème. Il est également conseillé de commencer par chercher des réponses sur l'internet.

Si vous ressentez toujours le besoin de poser une question et d'obtenir des éclaircissements, nous vous recommandons de procéder comme suit :

- Ouvrez une [question] (/questions/nouvelles).
- Fournissez autant de contexte que possible sur ce que vous rencontrez.
- Indiquez les versions du projet et de la plateforme (nodejs, npm, etc.), en fonction de ce qui semble pertinent.

Nous nous occuperons du problème dès que possible.



## Je veux contribuer

### Mentions légales 
> Lorsque vous contribuez à ce projet, vous devez accepter que vous êtes l'auteur de 100% du contenu, que vous avez les droits nécessaires sur le contenu et que le contenu que vous contribuez peut être fourni sous la licence du projet.

### Signaler des bogues


#### Avant de soumettre un rapport de bogue

Un bon rapport de bogue ne doit pas obliger les autres à vous relancer pour obtenir plus d'informations. C'est pourquoi nous vous demandons d'enquêter soigneusement, de collecter des informations et de décrire le problème en détail dans votre rapport. Veuillez suivre les étapes suivantes à l'avance afin de nous aider à corriger tout bogue potentiel le plus rapidement possible.

- Assurez-vous que vous utilisez la dernière version du logiciel.
- Déterminez si votre bogue est réellement un bogue et non une erreur de votre part, par exemple si vous utilisez des composants/versions d'environnement incompatibles (assurez-vous d'avoir lu la [documentation](). Si vous cherchez de l'aide, vous pouvez consulter [cette section](#i-j'ai-une-question)).
- Pour voir si d'autres utilisateurs ont rencontré (et peut-être déjà résolu) le même problème que vous, vérifiez s'il n'existe pas déjà un rapport de bogue pour votre bogue ou erreur dans le [bug tracker](issues?q=label%3Abug).
- Veillez également à faire des recherches sur Internet (y compris sur Stack Overflow) pour voir si des utilisateurs en dehors de la communauté GitHub ont discuté du problème.
- Recueillir des informations sur le bogue :
- Trace de pile (Traceback)
- Système d'exploitation, plateforme et version (Windows, Linux, macOS, x86, ARM)
- Version de l'interpréteur, du compilateur, du SDK, de l'environnement d'exécution, du gestionnaire de paquets, selon ce qui semble pertinent.
- Eventuellement votre entrée et la sortie
- Pouvez-vous reproduire le problème de manière fiable ? Et pouvez-vous également le reproduire avec des versions plus anciennes ?


#### Comment puis-je soumettre un bon rapport de bogue ?

> Vous ne devez jamais signaler de problèmes de sécurité, de vulnérabilités ou de bogues contenant des informations sensibles sur le système de suivi des problèmes ou ailleurs en public. Au lieu de cela, les bogues sensibles doivent être envoyés par courriel à <>.


Nous utilisons GitHub issues pour suivre les bogues et les erreurs. Si vous rencontrez un problème avec le projet :

- Ouvrez un [Issue](/issues/new). (Comme nous ne pouvons pas être sûrs à ce stade qu'il s'agit d'un bogue ou non, nous vous demandons de ne pas parler de bogue pour l'instant et de ne pas étiqueter le problème).
- Expliquez le comportement auquel vous vous attendez et le comportement réel.
- Veuillez fournir autant de contexte que possible et décrire les *étapes de reproduction* que quelqu'un d'autre peut suivre pour recréer le problème par lui-même. Cela inclut généralement votre code. Pour les bons rapports de bogue, vous devez isoler le problème et créer un cas de test réduit.
- Fournissez les informations que vous avez recueillies dans la section précédente.

Une fois qu'il est classé :

- L'équipe de projet étiquettera le problème en conséquence.
- Un membre de l'équipe essaiera de reproduire le problème à l'aide des étapes fournies. S'il n'y a pas d'étapes de reproduction ou pas de moyen évident de reproduire le problème, l'équipe vous demandera ces étapes et marquera le problème comme ayant besoin d'être reproduit. Les bogues marqués `needs-repro` ne seront pas traités tant qu'ils n'auront pas été reproduits.
- Si l'équipe est capable de reproduire le problème, il sera marqué `needs-fix`, ainsi qu'éventuellement d'autres tags (comme `critical`), et le problème sera laissé pour être [implémenté par quelqu'un] (#votre-première-contribution-au-code).

### Suggestion d'améliorations

Cette section vous guide dans la soumission d'une suggestion d'amélioration pour CONTRIBUTING.md, **y compris des fonctionnalités entièrement nouvelles et des améliorations mineures de fonctionnalités existantes**. Le respect de ces directives aidera les responsables et la communauté à comprendre votre suggestion et à trouver des suggestions connexes.


#### Avant de soumettre une amélioration

- Assurez-vous que vous utilisez la dernière version.
- Lisez attentivement la [documentation]() et vérifiez que la fonctionnalité n'est pas déjà couverte, peut-être par une configuration individuelle.
- Effectuez une [recherche](/issues) pour voir si l'amélioration a déjà été suggérée. Si c'est le cas, ajoutez un commentaire au problème existant au lieu d'en ouvrir un nouveau.
- Vérifiez si votre idée correspond à la portée et aux objectifs du projet. C'est à vous de présenter des arguments solides pour convaincre les développeurs du projet du bien-fondé de cette fonctionnalité. Gardez à l'esprit que nous voulons des fonctionnalités qui seront utiles à la majorité de nos utilisateurs et pas seulement à un petit sous-ensemble. Si vous ne visez qu'une minorité d'utilisateurs, envisagez d'écrire une bibliothèque de modules complémentaires/plugins.


#### Comment soumettre une bonne suggestion d'amélioration ?

Les suggestions d'amélioration sont suivies en tant que [GitHub issues](/issues).

- Utilisez un **titre clair et descriptif** pour le problème afin d'identifier la suggestion.
- Fournissez une **description étape par étape de l'amélioration suggérée** avec autant de détails que possible.
- Décrivez le comportement actuel** et **expliquez quel comportement vous vous attendiez à voir à la place** et pourquoi. À ce stade, vous pouvez également dire quelles sont les alternatives qui ne fonctionnent pas pour vous.
- Vous pouvez **inclure des captures d'écran et des GIF animés** qui vous aideront à démontrer les étapes ou à mettre en évidence la partie sur laquelle porte la suggestion. Vous pouvez utiliser [cet outil](https://www.cockos.com/licecap/) pour enregistrer des GIF sous macOS et Windows, et [cet outil](https://github.com/colinkeenan/silentcast) ou [cet outil](https://github.com/GNOME/byzanz) sous Linux. 
- Expliquez pourquoi cette amélioration serait utile** à la plupart des utilisateurs de CONTRIBUTING.md. Vous pouvez également signaler les autres projets qui ont mieux résolu le problème et qui pourraient servir d'inspiration.



### Votre première contribution au code


### Améliorer la documentation


## Guides de style
### Messages d'engagement


## Rejoindre l'équipe du projet



## Attribution
Ce guide est basé sur le **contributing.md**. [Make your own](https://contributing.md/)!
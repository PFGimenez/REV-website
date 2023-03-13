---
layout: page
title: SuperviZ
subtitle: A project on security supervision and orchestration
---

<img src="/superviz/assets/img/wp.png">

## Lot 0 – Gestion de projet

Sur le plan scientifique, le projet est conjointement piloté par Ludovic Mé (Inria) et Hervé Debar (Institut Mines-Télécom – Télécom SudParis). Ils ont en charge tous les aspects relatifs à ce pilotage scientifique, à savoir :

- L’organisation d’un bureau qui a pour objectif d’assurer le fonctionnement scientifique du projet, et en particulier d’assurer le bon déroulement des actions communes à plusieurs partenaires (co-encadrement de thèses, ingénieurs et post-doctorants).
- L’organisation d’un comité de suivi, composé de représentants des industriels et gouvernementaux ayant des activités dans le domaine de la supervision de sécurité.  
- La validation des publications et des recrutements, notamment l’organisation de jurys de recrutement et de mi-parcours pour les doctorants.

Sur le plan administratif, le projet est géré par un chef de projet à temps partiel, recruté par Inria. Ce chef de projet a en charge :

- L’organisation matérielle des réunions et des événements du projet, la diffusion des comptes-rendus et le suivi des actions.
- La mise en œuvre des outils de communication publics (site web, réseaux sociaux) du projet (avec un focus sur twitter et linkedin).
- Le suivi des risques et des actions de remédiation.
- Le contrôle qualité et la soumission des livrables.
- Le suivi financier du projet.


## Lot 1 : identifier et gérer le risque

Ce lot concerne la partie amont de la détection, avec l’identification des vulnérabilités présentes sur un système d’information, pour permettre :

- de qualifier et de quantifier les besoins de détection, 
- d’évaluer la couverture des mécanismes de détection et de réponse face aux risques, et 
- d’intégrer l’information CTI dans la supervision.

Il produit des méthodes et outils permettant d’évaluer le niveau de risque d’une infrastructure, de surveiller/visualiser la propagation d’un attaquant dans un environnement vulnérable et de s’y adapter.


## lot 2 : détecter des attaques

La détection comportementale est challengée par la difficulté à obtenir des modèles fiables, que ce soit par l’apprentissage – technique largement majoritaire – ou par d’autres moyens (spécifications, politique de sécurité, etc.). De plus, les alertes proposées par ces détecteurs comportementaux manquent de capacité à expliquer la source du problème et à proposer des mécanismes de remédiation. Le lot se focalise d’une part sur l’amélioration des capacités de détection, d’autre part sur leur robustesse, et finalement sur leur utilisation dans des environnements très spécifiques (mobile, immersif).


## lot 3 : Résister et répondre aux attaques

Ce lot a pour but de traiter les sujets post-détection de la boucle du NIST cybersecurity framework (respond and recover). Il propose de nouveaux mécanismes d’évaluation du risque par corrélation d’alertes et de réponse aux attaques, et étudie des méthodes pour réagir de manière automatisée aux attaques informatiques, dans les environnements IT d’une part, dans les environnements industriels d’autre part.


## lot 4 : rendre la supervision sûre et la plus efficace possible

Face à la complexité croissante d’organiser la supervision de la sécurité, ce lot s’intéresse à la mise en place d’une supervision efficace, ce qui intègre la résistance aux attaques spécifiquement orientées contre elle.


## lot 5 : concevoir des méthodes de validation des approches et mécanismes de détection

Ce lot a pour but de proposer à l’ensemble des autres lots des méthodes pour la validation expérimentale des résultats et ainsi permettre le benchmarking. Il se focalise donc sur les aspects méthodologiques de la validation des outils de détection. Il est complémentaire du lot 6 qui propose le développement de plates-formes et outils associés. Les problématiques de méthodologie nécessitant une bonne connaissance des mécanismes de détection, les travaux menés dans ce lot sont organisés autour de sujets de post-doctorat.


## lot 6 : développer des platesformes d’expérimentation

La plateforme globale qui sera construite au cours du projet sera constituée d’un réseau de dispositifs (ou plateformes locales) localisés chez divers partenaires, avec des nœuds importants à Paris, Nancy, Grenoble et Toulouse. 

Le but de cette plateforme est de mettre en place un environnement numérique opérationnel permettant de mettre en valeur différentes briques logicielles développées par les laboratoires dans le cadre des thèses et post-docs réalisés et de scénariser un environnement de supervision global qui permette d'activer telle ou telle solution en fonction d'un contexte opérationnel ou de résultats obtenus. Cette plateforme logicielle pourra ainsi être vue comme un bac à sable technique de solutions innovantes et de permettre de faire cohabiter les résultats de différents partenaires au sein d'un même démonstrateur. Les enjeux sont multiples : tout d'abord, ils permettent de faire monter en maturité des solutions prometteuses dans le volet technique en poussant leur développement au niveau d'une plateforme de mutualisation de développements. Ensuite, le fait de bâtir une approche combinant des résultats de différents partenaires va permettre de favoriser les échanges scientifiques et techniques des différentes équipes et aussi d'avoir des bases de données partageables entre ces partenaires. Finalement, cela permettra aussi de valoriser les résultats obtenus au travers de démonstrateurs opérationnels qui pourront être valorisés auprès de la communauté cybersécurité. 

Ce lot est complémentaire du lot 5, qui développe les outils méthodologiques pour la validation. Plus spécifiquement, les méthodes développées dans le lot 5 ont vocation à être déployées sur la plateforme.



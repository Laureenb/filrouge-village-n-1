# filrouge-village-n-1

### Phase 2 : Design de la solution "one-pager v2"

**Objectifs d’apprentissage**

* UX study d'un onepager responsive, qui annonce l’arrivée prochaine de la solution. Cette page comporte obligatoirement un formulaire d'inscription à une newsletter, fonctionnel, dans une db) ---> UX prototyping via balsamiq et invision
* intégration HTML/CSS de ce onepager
* une transaction client -> serveur -> client
* ce site contient une table MySQL permettant de recevoir les emails des gens s'inscrivant à la newsletter
* Déploiement sur un hébergeur classique, par exemple [hebergratuit.com](http://www.hebergratuit.com) ou [https://www.hostinger.fr/](https://www.hostinger.fr/). Une autre possibilité gratuite : [heroku](http://heroku.com/) pour le php, [freemysqlhosting.net](https://www.freemysqlhosting.net) pour la base de données MySQL.

**À livrer**

Dans le repos, ajouter un lien vers les prototype low-def + prototype high-def du onepager sur invision, ainsi que les fichiers du onepager v2.

* prototype low-def (balsamiq + invision.com)
* prototype high-def (figma.com)
* le one-pager en HTML/CSS/JS 
* la page doit obtenir le meilleur score possible au lighthouse test
* implémenter Google Analytics et donner l'accès aux contacts du client (l'équipe qui a rédigé le cahier des charges)

**Badges**

Possibilité d'obtenir les badges HTML sémantique + CSS + Lighthouse

**Temps imparti**: 5 jours, en groupe.

**Etapes**
- Consulter le tableau de suivi pour connaitre le projet à travailler pour cette phase.
- Forker le repository du groupe en charge de l'étape précédente.
- Activer les "Issues" du repo (voir "Settings")
- L'équipe identifie les tâches et se les réparti en tenant compte des objectifs d'apprentissage de chaque membre sur cette phase.
- Chaque tâche devient une Issue assignée au membre du groupe qui l'a obtenue
- Utiliser le "Projects board" du repo pour la gestion des tâches / Issues (colonnes: todo / doing / Done)
- Readme: ajouter les noms des membres de l'équipe pour cette phase.
- inclure le lien vers la demo en ligne dans le readme file.
- Le jour de la remise, envoyer le lien vers le readme sur Ryver.

Utiliser cette même procédure à chaque relai entre les phases.

# Projet :
![Pinterest](https://i.imgur.com/S7hvUQQ.png "The Red Line")
## Charte graphique
- Polices : **Asap** (voir issues).
- Couleurs : Réutiliser les couleurs du logo.
- One Page v1 : https://thomaspnt.github.io/Village-Num-1/
## Description
### Le client
Le Village n°1 (http://www.levillage1.be/) propose un accompagnement aux personnes handicapées afin de pouvoir les réinsérer professionnellement. Ils proposent des services aux entreprises ainsi qu'aux particuliers, ils offrent de la main d'oeuvre pour des services très variés comme entretien de jardin, titre service, service rénovation,...

### Type de site
Portail d'information/outil de communication.
### Public ciblé
Entreprises/particuliers/personnes handicapées demandeurs d'emploi.
### Le problème
Un grand manque de clarté et d'accessibilité. Trop d'informations qui sautent aux yeux.
### Résultat souhaité
#### Visuel
- Un design plus accessible et plus agréable à regarder.
- Une vision plus claire des services proposés.
- Pouvoir savoir en quelques secondes l'intérêt de la société.
#### Services
- Réaliser un service de "Taxis sociaux." Savoir le prix à payer pour un déplacement en fonction du point A au point B. Il doit être déterminable par le temps OU par le kilométrage. Mettre en place un système de réservations en ligne.
- Le client demande également un système de forum.
- Rendre le site accessible aux aveugles. Pouvoir utiliser le site les yeux bandés.
#### Contenu
- Garder ce qui semble cohérent. Le résultat doit être clair et accessible avant tout.
- Oublier la partie Multimédia et la partie Focus.
- Garder le système de F.A.Q.
#### Technologies
- Développer le site en React/Meteor.
## UML
![UML](https://contattafiles.s3-us-west-1.amazonaws.com/tnt14094/Xeij2dbt2EiGf72/filrouge.png "UML")
## Dev's note
- Web hosting is InfinityFree.net
- DB hosting FreeMySQLHosting.net

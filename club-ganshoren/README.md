# Ganshoren Shooting Club
- **Where ?** : At [Becode]()
- **When ?** :  From 31/05/2018 to ?
- **By who ?** : [Me]()
- **The Website** : [HERE]() - *Phase 1 version*.

## About

[FR]
Dans le cadre de ma formation de web devellopeur à [Becode](), le [Fil rouge](), est un projet qui a pour objectifs de nous permettre d'apprendre sur base de demandes réalistes.
Chaque projet est inspiré de situations et besoins réels, mais **ne fera pas l'objet d'une remise à un client "réel"**.

## Phases

- **Phase 1** : (guerilla style) : un one-pager en 8 heures.
- **Phase 2** : (managed style) : étude de la demande
- **Phase 3** : Design de la solution "one-pager v2"
- **Phase 4** : Création d’un "multipage website"
- **Phase 5** : développement d'un Backoffice (CMS)
- **Phase 6** : Application mobile / PWA


## Phase 1: Guerilla

- repository : `filrouge-0-guerrilla`
- team : `false`
- Durée : `21600s`
- remise: [formulaire](https://goo.gl/forms/ov5m6hVD4ZUxY2Yc2)

### Objectifs

- Réaliser un one-pager.
- Choisir une template sur [html5up.net](https://html5up.net/) (ou autre)
- Le modifier en utilisant le contenu rassemblé
- Une fois publié, utiliser le [Lighthouse Test](https://developers.google.com/web/tools/lighthouse/) et améliore le code pour améliorer ses scores dans tous les domaines.
- Si possible, trouve un nom de domaine gratuit
- Publier le résultat sur ce [formulaire](https://goo.gl/forms/ov5m6hVD4ZUxY2Yc2) avant la fin de la deadline.

#### Difficultés rencontrées

Face à ce challenge, réaliser un site web *satisficing* en six heures est en réalité très difficile. Mon projet, étant de réaliser un site pour un centre de tir, j'ai eu des difficultés à rassembler un contenu qui était quasi innexistant. Merci [Guillaume]() ! :-P
Ayant peu d'éléments, j'ai opté par réaliser ma propre maquette, plutôt que prendre un template. En me disant qu'une bonne maquette permet un code facile, j'ai y passé ma matinée dessus. 

#### Méthodes de travail

- De façon à rendre le projects dans les délais, j'ai fouillé dans mes projets projets précédents, en espèrant trouver des éléments qui fonctionneraient avec la maquette dessiné.
- J'ai trouvé un site que j'avais fait avec le pluggin `fullpage.js` de [Alvaro Trigo](). Ce pluggin permet de faire des *one-pager* en responsive, des transitions entre sections, entre autres.
- En amont j'ai exploré les animations css pour créer une [cible en animation](https://codepen.io/pedroseromenho/pen/GGJKog). C'est encore à retravailler, pour eventuellement la rajouter plus tard autant que `screen splash` ou autre.
- Malgré le côté pratique du pluggin `fullpage.js`, j'ai eu face à des problèmes de responsive. Ce pluggin contient son propre css et je n'ai pas dédié assez de temps pour le craquer correctement.

#### Test lighthouse

Le résultat n'est pas assez satisfaisant. Le pluggin detecte des problèmes de lisibilité, du code en trop,... En effet cette typo en blanc dans le `menu` et le `footer` ne facilite pas la lecture.

![test](light-house.png)

#### Le Mockup

![mockup](mockup.png)

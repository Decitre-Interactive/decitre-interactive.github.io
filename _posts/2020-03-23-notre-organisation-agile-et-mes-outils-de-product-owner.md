---
layout: post
title: Notre organisation Agile et mes outils de Product Owner
author: jmartel
date: 2020-03-23 12:00:00+01:00
excerpt: Notre organisation Agile et mes outils de Product Owner
---

Cela va bientôt faire un an que je suis Product Owner (PO) au sein de Decitre interactive. Comme le nom de mon métier l’indique, notre organisation se base sur la méthodologie agile, et plus précisément Scrum mais en version adaptée.

Cela faisait six ans que le CTO avait mis en place cette méthodologie au sein de l’équipe Web et que des prédécesseurs ont tenté de l’élargir à l’équipe ERP. Mettre en place une telle méthodologie au sein d’une entreprise historique et de commerçant de livre relève du tour de force.

Depuis mon arrivée, je me suis intégrée à cette organisation rondement menée, tout en apportant ma petite touche et nous sommes aujourd’hui satisfaits des outils mis en place. C’est pour cela que je souhaite vous les présenter ici.

 > **Disclaimer** : c’est une organisation adaptée à nos besoins, cet article a pour unique but de vous inspirer, on sait que nous n’appliquons pas Scrum stricto sensu et on est très à l’aise avec cela.


## Notre organisation agile

Decitre Interactive est constituée de deux équipes de développement:

-  Une équipe dédiée à l’ERP interne et travaillant avec tous les services internes
-  Une équipe Web travaillant pour les sites e-commerce du groupe (decitre.fr et furet.com), leurs déclinaisons en marque blanche et notre outil de recherche bibliographique

Nous n’avons pas de Scrum Master, mais c’est un rôle important garant de la méthodologie agile normalement. C'était notre CTO qui avait ce rôle et désormais c’est moi-même en tant que Product Owner/Manager. Je travaille pour les deux équipes de développement et les onze services internes.

En termes de planning, nous fonctionnons sur deux sprints de deux semaines entrecoupés d’une “Techweek" d’une semaine. La Techweek est un terme interne, mais l’idée est que 20% du temps de développement soit dédié à des sujets techniques choisis (par exemple la suppression de la dette technique) et portés par l’équipe, favorisant ainsi l’échange et les expérimentations.

À mon arrivée, il existait un grand décalage en termes d’appropriation de la méthode agile entre les deux équipes, l’une étant familière des environnements Web et habituée aux pratiques agiles, l’autre moins. Mon prédécesseur avait fait une harmonisation des calendriers afin que les deux équipes soient sur les mêmes dates, ce qui est salvateur en cas de développements devant être synchronisés sur les deux équipes.

<figure>
    <img
        class="lozad"
        width="400" height="170"
        src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw=="
        data-src="https://media3.giphy.com/media/gfTPmNCC7PKHevwp25/200.webp?cid=790b7611a3159a3c6cdc0f2eaf3d80282fe016cf096c26d4&rid=200.webp"
    />
    <noscript><img src="https://media3.giphy.com/media/gfTPmNCC7PKHevwp25/200.webp?cid=790b7611a3159a3c6cdc0f2eaf3d80282fe016cf096c26d4&rid=200.webp" /></noscript>

    <figcaption>Synchronisation ! (source : <a href="https://media.giphy.com/media/gfTPmNCC7PKHevwp25/giphy.gif">https://media.giphy.com/media/gfTPmNCC7PKHevwp25/giphy.gif</a>)</figcaption>
</figure>


Pour chaque équipe, nous utilisons un google doc avec les jours hommes, la proposition de backlog et de sprint, ainsi que le debrief et le burdownchart.

### Débrief

Au début de chaque sprint, il y a un debrief de sprint précédent permettant à chaque membre de l’équipe de s'exprimer sur son ressenti pendant le sprint. Nous travaillons en grande confiance et bienveillance, tous les sujets peuvent être abordés et tous les points positifs ou négatifs peuvent être soulevés.

Nous tentons de mettre en place des actions en cas de difficultés par exemple la rédaction de process interne, la réalisation d’outils internes ou des échanges avec un service en particulier. Nous évaluons ensuite le sprint sur quatre, le zéro et les décimales étant interdits.

### Planification et chiffrage

Nous faisons ensuite une planification de sprint. En tant que PO, je travaille les roadmaps et les users stories avec chacune des équipes ainsi que les priorisations et propose un backlog. Les développeurs les chiffrent du mieux possible, si possible en amont via une réunion de chiffrage ou via un document partagé, mais dans tous les cas le chiffrage est revu et réajusté en fonction de la personne qui prend le sujet au moment de la planification.

Les réunions de chiffrage ont lieu chaque techweek car cela demande que tous les développeurs soient présents pendant une à deux heures. Ces grandes réunions de chiffrage sont complétées par des points de chiffrages asynchrones via un document que nous faisons avant chaque planification.

Ces réunions permettent :
*  aux développeurs de débattre sur les chiffrages et ainsi d’échanger sur les méthodes,
 * de challenger les spécifications et d’équilibrer les prises de décisions entre les juniors et les séniors,
 * d'avoir une idée de grandeur du temps passé,
 * soumettre des interrogations techniques.

Nous utilisons la technique du [planning poker](https://blog.myagilepartner.fr/index.php/2017/04/09/scrum-planning-poker/), j’ai fabriqué un deck à partir de vieilles cartes de fidélité Decitre sur lesquelles j’ai mis la suite de Fibonacci.

<figure>
    <img
        class="lozad"
        width="600" height="450"
        src="data:image;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDACgcHiMeGSgjISMtKygwPGRBPDc3PHtYXUlkkYCZlo+AjIqgtObDoKrarYqMyP/L2u71////m8H////6/+b9//j/2wBDASstLTw1PHZBQXb4pYyl+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj/wgARCAAPABQDASIAAhEBAxEB/8QAFgABAQEAAAAAAAAAAAAAAAAAAAID/8QAFQEBAQAAAAAAAAAAAAAAAAAAAAH/2gAMAwEAAhADEAAAAbZXGqh//8QAGhABAAEFAAAAAAAAAAAAAAAAAQACESEyQf/aAAgBAQABBQKqdGO18jP/xAAUEQEAAAAAAAAAAAAAAAAAAAAQ/9oACAEDAQE/AT//xAAUEQEAAAAAAAAAAAAAAAAAAAAQ/9oACAECAQE/AT//xAAUEAEAAAAAAAAAAAAAAAAAAAAg/9oACAEBAAY/Al//xAAbEAACAgMBAAAAAAAAAAAAAAAAAREhMUFhkf/aAAgBAQABPyHjJfgZcoSVeiF5ENH/2gAMAwEAAgADAAAAEKsv/8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAwEBPxA//8QAFREBAQAAAAAAAAAAAAAAAAAAABH/2gAIAQIBAT8QV//EABoQAQEBAAMBAAAAAAAAAAAAAAERACExQZH/2gAIAQEAAT8QSiegn3cGllfbpwiXhDyZm+kwYTpwk7MZRpv/2Q=="
        data-src="{{ '/assets/posts/outils-po/deck-1.jpg' | prepend: site.baseurl  }}"
        data-srcset="{{ '/assets/posts/outils-po/deck-1.jpg' | prepend: site.baseurl  }} 1x, {{ '/assets/posts/outils-po/deck-2.jpg' | prepend: site.baseurl  }} 2x"
    />
    <noscript><img src="{{ '/assets/posts/outils-po/deck-1.jpg' | prepend: site.baseurl  }}" /></noscript>


    <figcaption>Notre deck de planning poker</figcaption>
</figure>

### Morning meeting

Tous les jours nous avons un point quotidien à 11h pendant lequel chaque personne de l’équipe de développement répond à trois questions : qu’est-ce que j’ai fait, quelles ont été mes difficultés et qu’est-ce que je compte faire. Nous mettons également à jour jour le board (tableau blanc dans l’open space) et le burndown chart sur lesquels nous reviendrons plus loin.

Pour chaque membre de l’équipe, le board est un vrai support pour savoir où nous en sommes à n'importe quel moment. En fin de sprint, je peux ainsi voir les sujets qui sont en cours et anticiper les reports par exemple.

Comme notre équipe peut faire du remote, tous ces points et réunions sont faisables à distance, en tant normal (hors période de confinement ;) ) il y a toujours au moins une personne de l’équipe présente physiquement dans les bureaux.


Nous remplissons également un Niko Niko, permettant de s’exprimer sur notre humeur et notre perception individuelle de la journée, nous exprimons ainsi toute problématique et essayons, si possible, de la traiter rapidement sans attendre le debrief.

<figure>
    <img
        class="lozad"
        width="600" height="211"
        src="data:image;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDACgcHiMeGSgjISMtKygwPGRBPDc3PHtYXUlkkYCZlo+AjIqgtObDoKrarYqMyP/L2u71////m8H////6/+b9//j/2wBDASstLTw1PHZBQXb4pYyl+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj/wgARCAAHABQDASIAAhEBAxEB/8QAFgABAQEAAAAAAAAAAAAAAAAAAAEE/8QAFAEBAAAAAAAAAAAAAAAAAAAAAP/aAAwDAQACEAMQAAAB1AoP/8QAFBABAAAAAAAAAAAAAAAAAAAAEP/aAAgBAQABBQJ//8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAwEBPwE//8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAgEBPwE//8QAFBABAAAAAAAAAAAAAAAAAAAAEP/aAAgBAQAGPwJ//8QAFxAAAwEAAAAAAAAAAAAAAAAAAAEQEf/aAAgBAQABPyFGT//aAAwDAQACAAMAAAAQcA//xAAUEQEAAAAAAAAAAAAAAAAAAAAQ/9oACAEDAQE/ED//xAAUEQEAAAAAAAAAAAAAAAAAAAAQ/9oACAECAQE/ED//xAAXEAADAQAAAAAAAAAAAAAAAAAAARFR/9oACAEBAAE/EETpGIiw/9k="
        data-src="{{ '/assets/posts/outils-po/niko-niko-1.jpg' | prepend: site.baseurl  }}"
        data-srcset="{{ '/assets/posts/outils-po/niko-niko-1.jpg' | prepend: site.baseurl  }} 1x, {{ '/assets/posts/outils-po/niko-niko-2.jpg' | prepend: site.baseurl  }} 2x"
    />
    <noscript><img src="{{ '/assets/posts/outils-po/niko-niko-1.jpg' | prepend: site.baseurl  }}" /></noscript>

    <figcaption>Notre niko niko</figcaption>
</figure>


Enfin, nous faisons des ateliers Definition Of Done à l’arrivée d’un nouveau collaborateur afin d’être tous sur la même longueur d’onde sur ce qu’est un produit fini, sur notre façon de faire et la stack technique. Pour cet atelier, j’utilise [ce kit](http://coach-agile.com/wp-content/uploads/2017/07/DOD-KARDS-FR.pdf) qui est ensuite complété par tous les membres de l’équipe qui le souhaite. Je le synthétise ensuite sur une feuille que nous signons tous et nous affichons sur notre board avec les remarques de chacun.


## Nos outils de suivi

### Scrum board

Nous avons un board classique composé de quatre colonnes, A faire, en cours, en validation et terminé. Chaque développeur a une couleur de magnet et les tickets sont suivis comme cela sur le board.

Les tickets correspondent aux user story à traiter et sont tous dans notre outil de ticketing Redmine, le chiffrage est également visible sur le ticket et nous faisons un dépilage quotidien pour ne laisser que le reste à faire. Nous n’utilisons pas de post-it mais des tickets de caisse grâce à [la super invention](https://tech.decitre.fr/posts/impression-des-tickets-du-sprint) de notre ancien collègue Vincent.


### Le burndown chart

Le dépilage quotidien nous permet de suivre notre vélocité et l’avancement grâce à notre burndown chart.


<figure>
    <video controls width="600" preload="metadata">
        <source src="{{ '/assets/posts/outils-po/sprints.mp4' | prepend: site.baseurl  }}"  type="video/mp4">
    </video>

    <figcaption>3 ans de burndown chart</figcaption>
</figure>


Lors d’une techweek nous avons mis en place des tableaux de bord afin qu’en tant que PO je puisse suivre et communiquer avec les services fonctionnels autours de nos avancements. Les voici:

### Tableaux de bord automatisés

*L’évaluation de l’encours* : à mon arrivée, le backlog en nombre de tickets total était supérieur à deux mille, certains tickets dataient d’il y a plus de cinq ans et beaucoup n’étaient plus suivis par personne.

Il y a eu une grosse étape de rationalisation et de travail qualitatif avec chaque service pour parvenir à un backlog propre, divisé par deux a minima (encore un peu trop garni à mon goût, mais il faut y aller par étape 😉 ). L’importance du backlog est source de frustration pour les équipes fonctionnelles qui ont tendance à voir la quantité plus que le travail effectif à effectuer derrière chaque ticket.

Pour atténuer cela, j’ai mis en place un tableau de bord reprenant le nombre de tickets par équipe ainsi qu’une estimation en termes de volume. Je monitore également l’évolution entre chaque sprint permettant ainsi d’ajuster avec les opérations de rationalisation, de chiffrage et de travail de spécification avec chaque service.

 <figure>
    <img
        class="lozad"
        width="500"
        height="275"
        src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw=="
        data-src="https://media.giphy.com/media/DUtVdGeIU8lmo/giphy.gif"
    />
    <noscript><img src="https://media.giphy.com/media/DUtVdGeIU8lmo/giphy.gif" /></noscript>

    <figcaption>Have you tried to turning it off and on again ? (source : <a href="https://media.giphy.com/media/DUtVdGeIU8lmo/giphy.gif">https://media.giphy.com/media/DUtVdGeIU8lmo/giphy.gif</a>)</figcaption>
</figure>

*L’évaluation du support et du temps de développement disponible* : les produits existant depuis de nombreuses années, chaque équipe de développement ne fait pas que du projet, et doit réserver une partie de son temps au support utilisateur et à l’exploitation.

Lorsque j’organise mes sprints, je dois donc tenir compte de ce temps-là en mettant un temps de focalisation que j’ajuste au fur et à mesure en fonction des périodes, des mises en production, des vacances, etc. Pour évaluer cela, je m’appuyais historiquement sur notre CTO. Maintenant j’ai mis en place des indicateurs sur le taux de support, le temps de développement disponible, et la focale en fonction du sprint permettant d’utiliser cet historique pour anticiper les futurs temps disponibles.

Ces données quantitatives sont alimentées par des données qualitatives afin de lisser l’exceptionnel, tout est extrait par équipe et non pas individuellement. **Le but n’étant pas de surveiller, mais d’analyser, on regarde cela tous ensemble lors des debriefs**.


## Nos outils de communication


Comme précisé plus haut, nous utilisons l’outil de ticketing Redmine, c’est le moyen de communication principal entre la technique et le fonctionnel.

Il permet de s’échanger des informations sur un sujet et que cela soit historisé, de s’assigner des tickets, de transmettre des degrés d’urgence, d’indiquer dans quel sprint le ticket sera traité, etc.

 

Notre ancien CTO avait mis en place un intranet, accessible à toute personne travaillant chez Decitre et prenant toutes les informations de Redmine. Il permet:

-   la suggestion de priorisation par service et par ticket que je dois prendre en compte en temps que PO.
-   la visualisation de nos sprints avec les tickets, le temps et l’avancement
-   Tous les slides de “release" présentant ce qui a été livré en production dans le mois écoulé donc sur les deux sprints consécutifs
-   les tableaux de bord.
    

<figure>
    <img
        class="lozad"
        width="600" height="131"
        src="data:image;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDACgcHiMeGSgjISMtKygwPGRBPDc3PHtYXUlkkYCZlo+AjIqgtObDoKrarYqMyP/L2u71////m8H////6/+b9//j/2wBDASstLTw1PHZBQXb4pYyl+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj/wgARCAAEABQDASIAAhEBAxEB/8QAFgABAQEAAAAAAAAAAAAAAAAAAAEE/8QAFAEBAAAAAAAAAAAAAAAAAAAAAP/aAAwDAQACEAMQAAAB1goP/8QAFBABAAAAAAAAAAAAAAAAAAAAEP/aAAgBAQABBQJ//8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAwEBPwE//8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAgEBPwE//8QAFBABAAAAAAAAAAAAAAAAAAAAEP/aAAgBAQAGPwJ//8QAGBAAAgMAAAAAAAAAAAAAAAAAAAEQITH/2gAIAQEAAT8hwbqP/9oADAMBAAIAAwAAABAAD//EABQRAQAAAAAAAAAAAAAAAAAAABD/2gAIAQMBAT8QP//EABQRAQAAAAAAAAAAAAAAAAAAABD/2gAIAQIBAT8QP//EABcQAAMBAAAAAAAAAAAAAAAAAAABIaH/2gAIAQEAAT8QUTRgTh//2Q=="
        data-src="{{ '/assets/posts/outils-po/intranet-1.jpg' | prepend: site.baseurl  }}"
        data-srcset="{{ '/assets/posts/outils-po/intranet-1.jpg' | prepend: site.baseurl  }} 1x, {{ '/assets/posts/outils-po/intranet-2.jpg' | prepend: site.baseurl  }} 2x"
    />
    <noscript><img src="{{ '/assets/posts/outils-po/intranet-1.jpg' | prepend: site.baseurl  }}" /></noscript>

    <figcaption>Extrait de notre intranet de priorisation</figcaption>
</figure>

Ainsi tout est disponible pour tout le monde quelque soit son poste, nous avons une grande ouverture et transparence.

 

Nous ne faisons pas de démonstration de sprint, contrairement à la méthodologie scrum classique où on livre itération par itération, nous livrons en continu. Quand une nouvelle fonctionnalité est mise en production, la recette est gérée en direct avec le demandeur qui transmet ensuite à son équipe, par ailleurs nous sommes plusieurs centaines de salariés et plus d’une dizaine de services cela nous prendrait trop de temps.

<figure>
    <img
        class="lozad"
        width="600" height="325"
        src="data:image;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDACgcHiMeGSgjISMtKygwPGRBPDc3PHtYXUlkkYCZlo+AjIqgtObDoKrarYqMyP/L2u71////m8H////6/+b9//j/2wBDASstLTw1PHZBQXb4pYyl+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj/wgARCAALABQDASIAAhEBAxEB/8QAFgABAQEAAAAAAAAAAAAAAAAAAAEE/8QAFAEBAAAAAAAAAAAAAAAAAAAAAP/aAAwDAQACEAMQAAAB10AP/8QAFBABAAAAAAAAAAAAAAAAAAAAIP/aAAgBAQABBQJf/8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAwEBPwE//8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAgEBPwE//8QAFBABAAAAAAAAAAAAAAAAAAAAIP/aAAgBAQAGPwJf/8QAFBABAAAAAAAAAAAAAAAAAAAAIP/aAAgBAQABPyFf/9oADAMBAAIAAwAAABCzz//EABQRAQAAAAAAAAAAAAAAAAAAABD/2gAIAQMBAT8QP//EABQRAQAAAAAAAAAAAAAAAAAAABD/2gAIAQIBAT8QP//EABkQAAMAAwAAAAAAAAAAAAAAAAABERAx8P/aAAgBAQABPxBk6i0QmP/Z"
        data-src="{{ '/assets/posts/outils-po/exemple-slide-release-1.jpg' | prepend: site.baseurl  }}"
        data-srcset="{{ '/assets/posts/outils-po/exemple-slide-release-1.jpg' | prepend: site.baseurl  }} 1x, {{ '/assets/posts/outils-po/exemple-slide-release-2.jpg' | prepend: site.baseurl  }} 2x"
    />
    <noscript><img src="{{ '/assets/posts/outils-po/exemple-slide-release-1.jpg' | prepend: site.baseurl  }}" /></noscript>

    <figcaption>Extrait de la release de février</figcaption>
</figure>


Pour autant, nous communiquons sur nos releases en présentant les points importants et terminés dans le mois sous forme de slides. Pour les créer, j’utilise les slides [reveal.js](https://revealjs.com/#/) que les développeurs intègrent ensuite dans l’intranet.

Enfin, il y a un kick-off hebdomadaire de dix minutes entre les services numériques pour présenter les points importants en cours. Il y a également une réunion bimensuelle avec tous les managers pendant laquelle je présente la roadmap macro avec l'état d'avancement et nous évoquons à ce moment-là les points de blocages ou les décisions si besoin.

 
## Conclusion

Vous avez maintenant un aperçu de notre organisation et de notre outillage. Nous mettons un point d’honneur à faire cela de façon transparente, même si j’agrège les données, elles sont toutes consultables par toutes et tous, tout le temps et nous les repassons ensemble lors des debriefs. Il est très important aussi de travailler en grande confiance et ces outils ne sont en rien des outils de surveillance, mais de mesure, c’est pour cela que la plupart ne sont pas nommés individuellement, mais en équipe.

Les outils ludiques et visuels remportent facilement les suffrages des plus réfractaires, ils décomplexent, les exercices et l’humour sont les meilleurs outils pour la mise en confiance.

Cette organisation est sans doute encore améliorable, mais elle nous convient bien et nous permet de répondre aujourd’hui à toutes nos problématiques organisationnelles tout en étant agile et chaque membre de l'équipe se sent à l’aise avec et les fonctionnels le comprennent, il y a donc une meilleure cohésion et compréhension d’équipe ce qui est, pour moi, le plus important et notre plus grande réussite.

 <figure>
    <img
        class="lozad"
        width="478"
        height="322"
        src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw=="
        data-src="https://media.giphy.com/media/XgN7BVqzswKxrLWNkj/giphy.gif"
    />
    <noscript><img src="https://media.giphy.com/media/XgN7BVqzswKxrLWNkj/giphy.gif" /></noscript>

    <figcaption>Dream Team (source : <a href="https://media.giphy.com/media/XgN7BVqzswKxrLWNkj/giphy.gif">https://media.giphy.com/media/XgN7BVqzswKxrLWNkj/giphy.gif</a>)</figcaption>
</figure>

 

Enfin, merci à tous les développeurs (présents et passés) et notre CTO de m'accompagner et de me soutenir dans nos expérimentations jusqu’à ce que ça fonctionne :)

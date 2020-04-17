---
layout: post
title: Fonctionnement des astreintes au sein de Decitre Interactive
author: agallou
date: 2020-04-23 10:00:00+01:00
excerpt: Retour sur le fonctionnement des astreintes au sein de Decitre Interactive
---

Chez Decitre Interactive, nous devons gérer plusieurs sites. Que cela soit des sites d'ecommerce (en notre propre nom ou en marque blanche, pour des professionnels ou des particuliers), ou des outils en SaaS que nous fournissons à des bibliothèques et des librairies.

Ces sites d’ecommerce sont notamment critiques. En journée nous sommes disponibles pour intervenir en cas de problème. Mais en soirée ou le week-end s’il y a un bug ou que le site est inaccessible, nous pouvons perdre des ventes, voire faire baisser notre image de marque.

Pour ces raisons, nous nous devons d’intervenir le plus rapidement possible même en dehors de toute heure travaillée si un problème urgent arrive sur les plateformes que nous gérons. Nos services doivent être pleinement accessibles en permanence.

Dans cette optique voilà maintenant plus de 3 années que des astreintes sont en place dans notre équipe. Nous allons donc vous présenter comment celles-ci fonctionnent.

# Une mise en place nécessaire

Avant la mise en place de ces astreintes, si un problème survenait il n’y avait aucun cadre :  personne n’était d’astreinte, nous intervenions à notre bon vouloir, et si nous détections le problème. Cela ne pouvait pas continuer comme cela.

Un roulement avec une personne d’astreinte a été mis en place. Cette mise en place s’est accompagnée d’une compensation à la journée d’astreinte ainsi qu’à l’heure d’intervention s’il y en a. 

Au niveau des règles d’intervention, elles sont simples : la personne d’astreinte doit se tenir prête à intervenir en une heure maximum après avoir été alertée.

# Répartition dans l’équipe

## Fonctionnement

Nous avons donc des roulements d’une semaine : chaque personne de l’équipe est d’astreinte pendant 7 jours d’affilés.

Nous essayons de prévoir ce planning pour les 2 prochains mois, afin de prendre en compte les congés ou contraintes de chacun. Ce planning n’est, bien entendu, pas figé, et selon nos imprévus, il nous arrive parfois de nous échanger des journées ou semaines d’astreinte.

## Outillage

### Saisie

Utilisant extensivement G Suite, nous saisissons nos astreintes dans un Google Spreadsheet à 3 colonnes : une pour la date, une pour la personne d’astreinte et la dernière optionnelle pour noter les éventuels congés ou indisponibilités afin de simplifier la lecture et préparation du planning.

Voici à quoi ressemble ce document : 

<figure>
    <img 
        class="lozad" 
        width="700" height="209"
        src="data:image;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDACgcHiMeGSgjISMtKygwPGRBPDc3PHtYXUlkkYCZlo+AjIqgtObDoKrarYqMyP/L2u71////m8H////6/+b9//j/2wBDASstLTw1PHZBQXb4pYyl+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj/wgARCAAGABQDASIAAhEBAxEB/8QAFgABAQEAAAAAAAAAAAAAAAAAAAEE/8QAFAEBAAAAAAAAAAAAAAAAAAAAAP/aAAwDAQACEAMQAAAB10AP/8QAFBABAAAAAAAAAAAAAAAAAAAAEP/aAAgBAQABBQJ//8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAwEBPwE//8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAgEBPwE//8QAFBABAAAAAAAAAAAAAAAAAAAAEP/aAAgBAQAGPwJ//8QAFRABAQAAAAAAAAAAAAAAAAAAARD/2gAIAQEAAT8hL//aAAwDAQACAAMAAAAQ88//xAAUEQEAAAAAAAAAAAAAAAAAAAAQ/9oACAEDAQE/ED//xAAUEQEAAAAAAAAAAAAAAAAAAAAQ/9oACAECAQE/ED//xAAXEAADAQAAAAAAAAAAAAAAAAABEDFx/9oACAEBAAE/EKOv/9k="
        data-src="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/spreadsheet-1.jpg' | prepend: site.baseurl  }}" 
        data-srcset="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/spreadsheet-1.jpg' | prepend: site.baseurl  }} 1x, {{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/spreadsheet-2.jpg' | prepend: site.baseurl  }} 2x" 
    />
    <noscript><img src="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/spreadsheet-1.jpg' | prepend: site.baseurl  }}" /></noscript>

    <figcaption>Extrait du Google Spreadsheet que nous utilisons pour programmer les astreintes</figcaption>
</figure>

### Consultation

Le Spreadsheet est très simple pour constituer le planning, mais il n’est pas forcément idéal pour avoir une vision sur celui-ci, pour comparer ce planning avec nos plannings personnels et pour pouvoir se souvenir que l’on est d’astreinte.

Pour cela nous avons donc mis en place des fichiers ICS qui nous permettent de consulter notre planning, 

Le script pour générer ces fichiers est très simple, vous pouvez le retrouver à [cette adresse](https://gist.github.com/agallou/a18a518e1f99b42fea996c8694973a28).

Il nous permet de générer deux types de calendriers : un par personne et un global.

Voici ci-dessous un exemple de calendrier avec uniquement nos astreintes en filtrant sur notre nom. Celui-ci est généralement ajouté dans notre outil de calendrier personnel.

<figure>
    <img 
        class="lozad" 
        width="700" height="357"
        src="data:image;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDACgcHiMeGSgjISMtKygwPGRBPDc3PHtYXUlkkYCZlo+AjIqgtObDoKrarYqMyP/L2u71////m8H////6/+b9//j/2wBDASstLTw1PHZBQXb4pYyl+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj/wgARCAAKABQDASIAAhEBAxEB/8QAFQABAQAAAAAAAAAAAAAAAAAAAAT/xAAUAQEAAAAAAAAAAAAAAAAAAAAA/9oADAMBAAIQAxAAAAGwAH//xAAUEAEAAAAAAAAAAAAAAAAAAAAg/9oACAEBAAEFAl//xAAUEQEAAAAAAAAAAAAAAAAAAAAQ/9oACAEDAQE/AT//xAAUEQEAAAAAAAAAAAAAAAAAAAAQ/9oACAECAQE/AT//xAAUEAEAAAAAAAAAAAAAAAAAAAAg/9oACAEBAAY/Al//xAAUEAEAAAAAAAAAAAAAAAAAAAAg/9oACAEBAAE/IV//2gAMAwEAAgADAAAAEPPP/8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAwEBPxA//8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAgEBPxA//8QAFhABAQEAAAAAAAAAAAAAAAAAASBh/9oACAEBAAE/EA2v/9k="
        data-src="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/calendrier_filter-1.jpg' | prepend: site.baseurl  }}" 
        data-srcset="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/calendrier_filter-1.jpg' | prepend: site.baseurl  }} 1x, {{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/calendrier_filter-2.jpg' | prepend: site.baseurl  }} 2x" 
    />
    <noscript><img src="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/calendrier_filter-1.jpg' | prepend: site.baseurl  }}" /></noscript>

    <figcaption>Exemple de calendrier affichant les asteintes pour une personne</figcaption>
</figure>


Et voici ci-dessous un exemple de calendrier avec toutes les astreintes. Celui-ci est généralement ajouté dans notre outil de calendrier professionnel.

<figure>
    <img 
        class="lozad" 
        width="700" height="362"
        src="data:image;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDACgcHiMeGSgjISMtKygwPGRBPDc3PHtYXUlkkYCZlo+AjIqgtObDoKrarYqMyP/L2u71////m8H////6/+b9//j/2wBDASstLTw1PHZBQXb4pYyl+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj/wgARCAAKABQDASIAAhEBAxEB/8QAFQABAQAAAAAAAAAAAAAAAAAAAAT/xAAUAQEAAAAAAAAAAAAAAAAAAAAA/9oADAMBAAIQAxAAAAGwAH//xAAUEAEAAAAAAAAAAAAAAAAAAAAg/9oACAEBAAEFAl//xAAUEQEAAAAAAAAAAAAAAAAAAAAQ/9oACAEDAQE/AT//xAAUEQEAAAAAAAAAAAAAAAAAAAAQ/9oACAECAQE/AT//xAAUEAEAAAAAAAAAAAAAAAAAAAAg/9oACAEBAAY/Al//xAAUEAEAAAAAAAAAAAAAAAAAAAAg/9oACAEBAAE/IV//2gAMAwEAAgADAAAAEHPP/8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAwEBPxA//8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAgEBPxA//8QAGBAAAwEBAAAAAAAAAAAAAAAAAAEhIFH/2gAIAQEAAT8QSfSlx//Z"
        data-src="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/calendrier_all-1.jpg' | prepend: site.baseurl  }}" 
        data-srcset="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/calendrier_all-1.jpg' | prepend: site.baseurl  }} 1x, {{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/calendrier_all-2.jpg' | prepend: site.baseurl  }} 2x" 
    />
    <noscript><img src="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/calendrier_all-1.jpg' | prepend: site.baseurl  }}" /></noscript>

    <figcaption>Exemple de calendrier affichant toutes les asteintes</figcaption>
</figure>

# Alerting

## Des sources de notification diverses

Toutes nos applications ne sont pas hébergées de la même façon. Parfois certains de nos serveurs sont infogérés, parfois nous maintenons nous même complètement les serveurs. Dans tous les cas l’alerting, en cas de problème, pour l’astreinte reste le même.

Le Spreadsheet et le calendrier nous ont donc permis de nous assurer qu’une personne sera d’astreinte. Mais comment la personne est-elle prévenue en cas de problème ?

Nous avons plusieurs sources pour nous remonter ces problèmes : 
* des sondes Pingdom
* des tests 2befficient
* des remontées par certains services.

Nous utilisons pingdom, pour monitorer l’accès aux sites, en faisant bien attention d’utiliser la fonctionnalité ”Check for string” afin de détecter la présence de certains mots sur la page pour avoir un contrôle supplémentaire.

Sur un site ecommerce, le tunnel de commande est une fonctionnalité clé : c’est un point critique du site. Nous utilisons donc [2befficient](https://www.2befficient.fr/fr_fr/) afin de passer régulièrement des commandes comme nos clients et clientes le feraient, et d’être prévenus s’il y a un changement, une erreur lors de cette commande (ce service nous permet notamment de faire aussi des comparaisons visuelles).

Parfois nous avons certains services internes qui peuvent nous contacter, par exemple, le service en charge de l’ERP.

Dans tous les cas les notifications sont tout le temps faites sur un numéro unique d’astreinte : les sondes pingdom et 2befficient nous envoient des SMS, et les services internes concernés ont connaissance du numéro unique d’astreinte.

## Un numéro d’astreinte unique

Nous avons donc un numéro unique pour joindre notre astreinte, mais potentiellement plusieurs personnes qui peuvent la gérer. S’échanger un téléphone était pour nous une solution inenvisageable : celle-ci est peu pratique, source d’oublis et non adaptée au travail à distance.

Toute personne effectuant l’astreinte a donc un téléphone, de la marque Crosscall, qui résiste à tout, mais surtout qui a une très grande autonomie. En effet, il ne faudrait pas que le téléphone soit déchargé pendant notre semaine d’astreinte.

<figure>
    <img 
        class="lozad" 
        width="700" height="525"
        src="data:image;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDACgcHiMeGSgjISMtKygwPGRBPDc3PHtYXUlkkYCZlo+AjIqgtObDoKrarYqMyP/L2u71////m8H////6/+b9//j/2wBDASstLTw1PHZBQXb4pYyl+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj4+Pj/wgARCAAPABQDASIAAhEBAxEB/8QAFwAAAwEAAAAAAAAAAAAAAAAAAAMEAv/EABUBAQEAAAAAAAAAAAAAAAAAAAEC/9oADAMBAAIQAxAAAAEXTLLoSJ//xAAZEAADAQEBAAAAAAAAAAAAAAAAAQIREhP/2gAIAQEAAQUC607o9GVCZSw0/8QAFBEBAAAAAAAAAAAAAAAAAAAAEP/aAAgBAwEBPwE//8QAFREBAQAAAAAAAAAAAAAAAAAAABH/2gAIAQIBAT8BR//EABYQAAMAAAAAAAAAAAAAAAAAABAgQf/aAAgBAQAGPwIRP//EABsQAAICAwEAAAAAAAAAAAAAAAARASEQUWFx/9oACAEBAAE/IZlZrw7YnBkbsbZ//9oADAMBAAIAAwAAABBrP//EABURAQEAAAAAAAAAAAAAAAAAAAAR/9oACAEDAQE/EFf/xAAWEQADAAAAAAAAAAAAAAAAAAABEBH/2gAIAQIBAT8QET//xAAdEAEAAgICAwAAAAAAAAAAAAABABExQVGBIWFx/9oACAEBAAE/EHm/gLBAHw36DK9LpJYNewj8VwjHRbqf/9k="
        data-src="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/telephone-1.jpg' | prepend: site.baseurl  }}" 
        data-srcset="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/telephone-1.jpg' | prepend: site.baseurl  }} 1x, {{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/telephone-2.jpg' | prepend: site.baseurl  }} 2x" 
    />
    <noscript><img src="{{ '/assets/posts/fonctionnement-asteintes-au-sein-de-decitre-interactive/telephone-1.jpg' | prepend: site.baseurl  }}" /></noscript>

    <figcaption>Nous avons un téléphone très resistant</figcaption>
</figure>

Pourquoi utiliser un second téléphone et ne pas envoyer les notifications sur un téléphone personnel ?

* Même si certains téléphones permettent des notifications personnalisées, cela permet que ce téléphone soit toujours sur sonnerie, jamais sur muet et pouvoir l’entendre en toute occasion.
* Cela permet d’avoir un téléphone qui ne tombera pas à cours de batterie comme pourrait l’être un smartphone personnel.
* Cela permet de bien séparer les choses, ne pas l’avoir sur soi quand on n’est pas d’astreinte et conserver un bon rapport entre vie professionnelle et vie personnelle.

Afin d’avoir un numéro unique nous utilisons [Twilio]([https://www.twilio.com/).  Ce service nous a permis d’acheter chez eux un numéro de téléphone. Nous redirigeons ensuite ce numéro de téléphone vers la personne d’astreinte en ayant configuré [ce script](https://gist.github.com/agallou/16e8967fd67f7213f7997725fbff0164) en calback dans l’administration de Twilio.

Ce script va lire le Google Spreadsheet, et rechercher pour la date du jour qui est la personne d’astreinte, et renvoyer le numéro de cette personne à Twilio. Twilio va ensuite transférer les appels et SMS vers ce numéro.

Le script est hébergé dans notre infrastructure, mais celle-ci pourrait ne pas répondre, si c’est elle qui a un problème. Heureusement Twilio est très bien fait et nous permet de configurer une URL de fallback dans le cas où le premier appel n’a pas fonctionné. Nous avons donc le script hébergé sur deux plateformes totalement différentes, l’une chez Scaleway/Online et l’autre chez Claranet/Typhon ce qui permet d’être notifié même si l’une de nos infras ne répond plus.

# Le mot de la fin

Nous avons donc un système d’astreinte qui fonctionne plutôt bien. Notre plateforme est plutôt stable, et les interventions restent exceptionnelles, mais nécessaires. Après coup, nous cherchons toujours à planifier des changements afin que le problème ne survienne à nouveau. Si vous avez des questions sur notre gestion des astreintes ou souhaitez partager votre expérience, n’hésitez pas à en parler dans les commentaires de ce billet de blog.

Nous recrutons un/une Product Owner ainsi qu’un/une développeur/développeuse, vous pouvez retrouver toutes les offres sur [notre site dédié](https://www.decitre-recrutement.com/).







# Projet d'un site en Bootstrap

Le but de ce projet était de réaliser le site vitrine d'une franchise de restaurants.

La franchise est fictive mais le type de nourriture (burger, pizza, asiatique,...) est laissé au choix de l’apprenant.

Le site doit être responsive : Au moins pour les smartphones (xs) et pour les tabettes (md).

Nous devions réaliser minimum 5 pages accessibles par une barre de navigation (navbar) présente sur toutes les
pages et menant aux différentes rubriques : Accueil, Carte, Photos, Restaurants, Contact.

## Composition du site

En utilisant Bootsrap, nous devions placer des éléments spécifiques sur chacune des pages. A savoir :

- Sur la page Accueil :
    
    - Un composant Jumbotron
    - Deux panneaux (panel) pour afficher des news (genre promotions, news ou évènements de la semaine)
        
    
- Sur la page Carte :
        
    - Les menus présentés sous forme de liste groupée avec badges
        
- Sur la page Photos :
    
    - Une galerie photos (minimum 10) et une pagination (3 photos par page)
    
- Sur la page Restaurants :
    
    - L'adresse, un plan d'accès (Google maps) et les heures d'ouverture d’au moins deux restaurants
        
    
- Sur la page Contact :
    
    - Un formulaire de contact comprenant nom, prénom, e-mail, liste déroulante (objet du message avec un select et des options), un champs de texte (pour le message) et un bouton d'envoi
                
            
La seule **contrainte** que nous avions lors de la réalisation de ce projet est de ne pas utiliser de thème déjà tout fait (templates).


Comme dit plus haut, nous devions réaliser ce projet à l'aide de Bootstrap, qui est une collection d'outils de développement utiles à la création du design de sites et d'applications web.
Cette collection contient entre autre des codes HTML et CSS, des formulaires, boutons, outils de navigation et autres éléments interactifs.


### Ce que ce projet m'a appris :

- Être le plus sémantique possible (Eviter de mettre trop de div [Bien que parfois on n'a pas trop le choix d'en avoir..] )
- Utiliser Bootstrap
- Utiliser les Media Queries, ou le Responsive Web Design de son autre nom, qui est une adaptation dynamique de pages HTML et CSS 
        selon le périphérique de consultation utilisé.
- Bien sûr être organisé dans la réalisation des cinq pages du site.
            
### Le site en responsive :


Voici le site du restaurant en responsive, c'est-à-dire adapté sur les différents supports demandés, à savoir le support tablette et le support smartphone.

- Le site sur ordinateur :

    <img src = "https://zupimages.net/up/19/21/ndgc.png" alt = "site-responsive">

- Le site sur tablette :

    <img src = "https://image.noelshack.com/fichiers/2019/21/2/1558466691-site-md.png" title = "site-md" alt = "site-responsive">

- Le site sur smartphone :

    <img src = "https://image.noelshack.com/fichiers/2019/21/2/1558466690-site-xs.png" title = "site-xs" alt = "site-responsive">


### Problèmes rencontrés :

Les seules problèmes que j'ai rencontré lors de la réalisation de ce projet sont :
        
- La galerie photos.
            Au départ j'étais parti sur l'idée d'un carousel et je demandais comment c'était possible d'inclure la pagination dessus.
            Finalement la réalisation était plus simple que je ne le pensais, mais néanmoins j'ai perdu pas mal de temps là-dessus.
            
- La liste des menus.

    <img src = "https://image.noelshack.com/fichiers/2019/21/2/1558466690-listes-menus.png" title = "site-xs" alt = "site-responsive">
                
                
Comme la photo le montre, les colonnes ont différentes tailles. La colonne "desserts" ne se place pas exactement en-dessous
de la colonne "entrées". Elle commence là où s'arrête la colonne la plus longue présente au-dessus. Et il m'est impossible de
la placer sans tricher avec des margin et compagnie (Ce dont je n'ai pas fait.)

Lien du Github-pages : https://oliwood89.github.io/restaurant-css-framework/

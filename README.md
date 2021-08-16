# PID2021
2e Session travail PID - Réservations


PID – Projet Réservations
Contexte
Dans le cadre de la formation en Bachelier en Informatique de gestion, d’une part, et en BES de Web Developer, d’autre part, le présent projet s’inscrit dans une double finalité, à savoir :
    • se former au développement d’une application Web dynamique au moyen d’outils de développement RAD et en développant une méthodologie professionnelle dans un contexte de travail collaboratif (travail de groupe et support en classe) ;
    • se préparer au Travail de Fin d’Études en explorant les besoins fonctionnels du TFE dans un contexte moins contraignant, et en développant les compétences adéquates et son autonomie.
Gestion du projet
    • https://openclassrooms.com/courses/4192086-gerez-votre-projet-informatique-facilement 
    • https://openclassrooms.com/courses/4296701-gerez-un-projet-digital-avec-une-methodologie-en-cascade 
    • https://openclassrooms.com/courses/4507926-initiez-vous-a-la-gestion-de-projet-agile 


Itération 0 – Découverte du projet
Introduction
Présentation du projet
Le projet consiste à informatiser la gestion des réservations de spectacles d’une société de production. Celle-ci gère un catalogue reprenant des spectacles, leurs auteurs et leurs metteurs en scènes, les comédiens, ainsi que les lieux et les dates de représentations.
L’internaute pourra consulter librement le catalogue des spectacles affichant le lieu et les prochaines dates de représentation. Il pourra effectuer des recherches, des tris et des filtres à travers les pages du catalogue.
Le membre pourra réserver des places pour une représentation d’un spectacle, consulter la liste de ses réservations et modifier ses données de profil.
L’administrateur pourra gérer son catalogue à travers un back-office sécurisé. Par exemple, il pourra ajouter, modifier et supprimer un spectacle manuellement, importer/exporter des données au format CSV, mais aussi mettre à jour la liste des spectacles grâce aux nouveautés publiées par un Web service tiers.
À son tour, l’application devra produire d’une part son propre Web service (une API authentifiée avec système d’affiliation), d’autre part un flux RSS (par exemple, la liste des prochaines représentations).
Cahier de charges techniques
    • Développer une application Web en respectant les contraintes suivantes
        ◦ utiliser la programmation orientée objet (langages Java, PHP ou Python),
        ◦ exploiter un framework (Spring Boot, Symfony, Laravel, CakePHP, Django),
        ◦ gérer les erreurs de programmation au moyen d’outils ou de techniques de débogage et y apporter une solution pertinente,
        ◦ utiliser à bon escient la documentation disponible,
        ◦ optimisation du code, du cache et des échanges avec la base de données,
        ◦ gérer un catalogue d’éléments (produits, membres ou services) :
            ▪ effectuer des recherches dans le catalogue,
            ▪ paginer, trier et filtrer les résultats de la requête,
            ▪ sélectionner des éléments du catalogue et effectuer des actions groupées,
            ▪ sélectionner un élément du catalogue et en afficher le détail,
            ▪ gérer la sécurisation et les droits d’accès aux contenus (droits d’accès par rôle administrateur, utilisateur public, utilisateur enregistré, gestionnaire, etc.),
            ▪ afficher des contenus de manière différenciée (accessibilité, langue, sécurité, fonctionnalités, disponibilité de l’information, etc.), en fonction des profils utilisateurs,
            ▪ optimisé par programmation asynchrone (AJAX, JSON, XML,…),
            ▪ exploiter des fichiers de données structurées (XML, CSV, texte,..) en lecture/écriture (importer/exporter le catalogue),
            ▪ intégrer des services internes et tiers (RESTful Web services),
        ◦ déployer un back-office d’administration (interface administrateur sécurisé) :
            ▪ gérer les contenus dynamiques,
            ▪ modifier ses données de profil,
            ▪ configurer une interface utilisateur (couleur, affichage,…),
            ▪ interagir avec un système de gestion de bases de données (récupérer, ajouter, modifier, supprimer des enregistrements, etc.) ;
    • Veiller à la sécurité
        ◦ utiliser des outils spécifiques de protection et d’identification,
        ◦ protéger l’application contre les injections SQL, attaques XSS, vols de session,  détournement de cookies, etc.,
        ◦ définir la réécriture d’url,
        ◦ configurer des paramétrages et restrictions d’accès au serveur.

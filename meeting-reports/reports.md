

---

[Compte rendu point ecoCode du 13.01.2023]

**Sujets abordés :**

* Hackathon :
    * Site web : ecocode-challenge.davidson.fr (hébergé chez Davidson)
    * Passage du repo ecocode-challenge en privé (doublon avec le site web)
* EcoLinter
* Matrice de règles : stocké sur les repo ecoCode et ecoCode-mobile. Le projet ecoCode-challenge ferra référence à ces matrices.
* Guide des bonnes pratiques de dev
    * Créer un CONTRIBUTING.md sur chaque projet pour décrire ces bonnes pratiques

**Actions :**

* @Geoffrey Lalloué :
    * Renommer cnmur en “cnumr” sur message de portabilité des repo ecoCode et ecoLinter
    * Envoyer un message sur le slack CNUMR pour annoncer la migration
    * Préparer mail à Frédéric Bordage
* Constituer le backlog du projet (kanban) pour lister les actions
* Renommer le fichier de matrice et le positionner à la racine du projet sous le nom : RULES.md : @Olivier Le Goaër (mobile) & @Geoffrey Lalloué (standard)
* Initier un fichier CONTRIBUTING.md par projet : @David DE CARVALHO (standard) & @Olivier Le Goaër (mobile)
* Passage du repo ecocode-challenge en privé (avant suppression) :  @Olivier Le Goaër
* Mettre à jour README repo ecocode pour virer la partie mobile :  @Geoffrey Lalloué
* Créer un channel #ecoCodeLinter pour discuter de l’avenir du projet et comment eventuellement le réintégrer @Geoffrey Lalloué

**Prochains événements :**

Prochain rdv des contributeurs (ouvert à tous) : vendredi 20 janvier à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 20.01.2023]

**Sujets abordés :**

* Annonce effectuée auprès du cnumr et Frédéric Bordage sur la migration
* Ajout des projets Snapp’ “ecocode rule specification” et “sonar-rule-android-project” au repo
* Backlog projet créé : https://github.com/orgs/green-code-initiative/projects/2/views/1
* Nouveau channel #ecolinter créé pour discuter de l’avenir du projet ecoLinter
* Communication :
    * Nouveau channel #communication
    * Linkedin : Est-ce que le collectif reprend la main sur le compte ecoCode existant ? Est-ce qu’on crée un compte Green Code initiative ?
    * Twitter ? Créer un compte ?

**Actions :**

* @Julien HERTOUT
: Ajout des projets Snapp’ “ecocode rule specification” et “sonar-rule-android-project” au repo
* @David DE CARVALHO
: création d’un repo ecoCode-common pour centraliser les docs et outils communs (starter-pack, doc d’install, etc...)
* @Maxime DUBOIS
: se renseigne auprès de Snapp’ pour donner les droits admin au collectif sur le compte Linkedin ecoCode
* @Maxime DUBOIS
: voir avec amélie Snapp’ pour récupérer support de présentation ecoCode-mobile existant

**Prochains événements :**

Prochain rdv des contributeurs (ouvert à tous) : vendredi 27 janvier à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 27.01.2023]

**Sujets abordés :**

* Debrief sur point Crédit Agricole d’organisation du Hackaton 2023
    * Proposer un point à Véronique vendredi prochain sur point ecoCode
* Véracité des règles :
    * Lancer le chantier de validation (ETS DIff / reference a un référentiel existant / validation chercheur
    * Après complétion des règles, il faudra commencer à faire du ménage
* ecoLinter
    * ecoCode s’appuie sur un repo maven et ecoLinter sur un package.json => fonctionnement différent
    * Questions : est-ce qu’on split la partie CSS et JS ?
* Communication
    * Linkedin :
        * Snapp’ donne les accès admin aux personnes intéressées pour la page ecoCode
        * Green Code Initiative : page société à but non lucratif
    * Eclipse Foundation : contact entrant sur accompagnement du projet
    * Github pages : Snapp’ regarde si ressources dispo en interne pour avancer sur le sujet
* Dockerisation

**Actions :**
* @David DE CARVALHO
: Créer une team maintainer pour donner plus de droits sur le Github => OK
* @Maxime Malgorn
: vérification de faisabilité intégration ecoLinter dans ecoCode
* @Maxime DUBOIS
: création page Green Code Initiative sur linkedin + accès admin au compte ecoCode => (https://www.linkedin.com/company/green-code-initiative)

**Prochains événements :**

:mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 3 février à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 03.02.2023]

**Sujets abordés :**

* Hackaton 2023
  * Communication lancée semaine prochaine
  * Mi-février : lancement du site web et ouverture des inscriptions
  * Sponsoring :
    * Présentation aux partenaires potentiels effectuée S4
    * Plusieurs participations officialisées
  * Etudiants, contacts entrants :
    * Epitech
    * EFREI
    * TSP
    * INSA Lyon
  * Site web : Piloté par Johann BRESSE
    * 1 landing page :white_check_mark:
    * 1 page formulaire (nom / prénom / email / entreprise / présentiel-distanciel / appartenance à une équipe ? / langages de développement / repas)
  * Partenaires : seront affichés sur le site internet et cités dans les articles de comm’ . Point d’entrée : Véronique
  * Défis :
    * Défis 1 : javascript / Php / Java / Python
      * Mettre à jour les kanbans projet
    * Défis 2 : défricheurs : ouvert a tous les langages
* ecoLinter : test de l’APi sonar par 
@Maxime Malgorn
 qui confirme que rien n’est disponible

**Actions :**
-

**Prochains événements :**
* Prochain rdv des contributeurs (ouvert à tous) : vendredi 10 février à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 10.02.2023]

**Sujets abordés :**

* Hackathon 2023
  * Identification des coachs (travail en cours - @Jules Delecour)
  * Clarification du rôle de coach -> faire un petit doc ?
  * Proposition de commencer le hackathon par une présentation technique ou un TP pour faciliter la mise en route des newbies
  * A valider : quels pré-requis sont demandés aux participant·es ? (lecture de la doc, installation d'outils, etc.) -> @David DE CARVALHO a créé un script qui vérifie la config d'un poste pour valider les pré-requis. Recommander de le faire avant (dans le mail de confirmation d'inscription ?), au pire le faire au tout début du hackathon pour ceux qui n'ont pas pu le faire avant.
  * Alerte problème de compatibilité SonarQube avec Apple M1. A vérifier et documenter.
  * Il faut clarifier les objectifs du défi Spotters, comment organiser les équipes, quels outils de mesure utiliser, où livrer le résultat de leur travail (PR, discussion ?), etc. -> Proposition : Réactiver le dépôt ecoCode-challenge pour le hackathon et le vider pour qu'il serve uniquement à déposer le résultat du travail des spotters. Bien distinguer mobile et standard car les outils ne sont pas les mêmes.
  * Le référentiel de règles Android a été intégré au référentiel du Cnumr avec les 115 bonnes pratiques. Les propositions de règles doivent elles être poussées sur le dépôt du Cnumr ou faut-il faire un filtre en amont pendant le hackathon ? Qu'en est-il pour les règles d'ecoCode standard ? 
* Suivi des actions en cours : 
  * Vérification de faisabilité intégration ecoLinter dans ecoCode : @Maxime Malgorn a regardé la partie JS et CSS. Conclusion : on est obligé de passer par un plugin ESLint pour faire l'analyse. En attente de retour pour pousser une première version (coquille vide). 
  * Site web : publier actualité hackathon sur le site ecocode.io le 20/02 (date de lancement des communications autour de l'évènement)
  * Github Pages : Snapp' avance sur le sujet, il faut clarifier ce qu'on conserve ou pas

**Actions :**

* @Julien HERTOUT: Vérifier et documenter problème de compatibilité SonarQube avec Apple M1 
* @David DE CARVALHO: Réactiver le dépôt ecoCode-challenge pour le hackathon et le vider 
* @Maxime DUBOIS: publier actualité hackathon sur le site ecocode.io le 20/02
* @Maxime DUBOIS: Github Pages : clarifier ce qu'on conserve ou pas

**Prochains événements :**

* Prochain rdv des contributeurs (ouvert à tous) : vendredi 17 février à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 17.02.2023]

**Sujets abordés :**
* Hackathon 2023
  * Point des coachs : 03.03.2023
  * Conférences : 
    * Outils + rex ecoCode en DSI (30min) => Mathilde Alliance
    * Inspiration : projet Open-source : 
      * Idées : Eclipse Foundation / Jhipster
  * Jurys : 
    * Recherches de jurys qui pourraient s’impliquer dans le projet par la suite
    * Nombre : 10 max
    * Pistes : 
      * Yannick Tremblais
      * 1 personne du collectif non coach
      * 1 de la eclipse foundation
      * 1 de accenture
  * Goodies : Limiter aux max (pistes : livre)
  * Outils de validation des prérequis technique développé par @David DE CARVALHO 
* Docs
  * Mise en commun des docs dans ecoCode-common
  * Les docs spécifiques des projets (standard / mobile / linter) feront référence aux docs communes du common
* Eclipse Foundation : 
  * Présentation des contacts pris / attentes / demandes
  * On se laisse une semaine de reflexion pour en reparler semaine prochaine
* Linkedin : 
  * Tout le monde peut proposer quelque chose dans le canal de discussion
  * Relecture / Validation par @Maxime DUBOIS & @Geoffrey Lalloué 
  * Intégration d’edwidge dans la boucle après le hackaton

**Prochains événements :**
:mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 24 février à 14h sur https://meet.treebal.green/ecoCode

---

[Compte rendu point ecoCode du 24.02.2023]

**Sujets abordés :**
* Hackathon 2023
  * Point des coachs : 03.03.2023
    * 15 personnes
  * Conférences :
    * Liste à jour : https://ecocode-workspace.slack.com/archives/C04J1CW4M51/p1676909352671799
  * Jurys :
    * liste à jour : https://ecocode-workspace.slack.com/archives/C04J1CW4M51/p1676913937061399
  * Partenariats : 
    * faire suivre les logos des entreprises à jules et thierry
  * Date d’ouverture des inscriptions : 28/02
* Communication externe
  * Préparer une liste des slides génériques de présentation du projet
    * 1 support générique sur fonctionnement du projet
    * 1 support technique ecoCode
    * 1 support technique ecoCode-mobile
    * 1 support organisationnel pour présentation aux entreprises
  * Article Programmez! => lead @Geoffrey Lalloué, date de rendu : 20/03
* Eclipse Foundation :
  * On se laisse encore un peu de temps de reflexion pour en reparler prochainement

**Actions :** 
* @Maxime DUBOIS: demander adresse mail des jury pour faire suivre à Jules
* @Geoffrey Lalloué: Refaire une passe sur le repo EcoCode vers les liens ecoCode-mobile
* Spotters : Les guider sur le repo GIT
* @Geoffrey Lalloué: supprimer le fichier ecoCode/web-rules.md at main · green-code-initiative/ecoCode (github.com) et remplacer dans la matrice par un lien vers repo cnumr

**Prochains événements :**

:mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 10 mars à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 03.03.2023]

**Sujets abordés :**
* Hackathon 2023
  * Point coachs fait le 03.03.2023, support à partager @Jules Delecour
  * Prévoir une matrice de compétences / connaissances pour identifier des référents parmi les coachs @Jules Delecour
  * Conférences : planning en cours de finalisation
  * Jurys : trop de candidatures, sélection en cours
  * Clarifier le parcours d'accueil : où aller, quoi lire, quoi faire ?
  * Organisation :
    * Kanban pour les Spotters (cf Identified Rules dans ecoCode-Mobile) @Maxime DUBOIS @Jules Delecour
    * Issues pour les Builders (prévoir un tag spécifique pour le challenge, et un moyen de prévenir les autres qu'on prend une règle) @Olivier Le Goaër @Jules Delecour
  * Outils de validation des prérequis techniques OK

**Prochains événements :**

:mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 10 mars à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 10.03.2023]

**Sujets abordés :**
* Hackathon 2023
  * ✅ Point coach fait le 03.03.2023, support à partager @Jules Delecour 
  * ✅ Point jury fait le 10.02.2023, 12 personnes @Jules Delecour 
  * 37 inscrits en une semaine
  * Prévoir une matrice de compétences / connaissances pour identifier des référents parmi les coachs @Jules Delecour 
  * Conférences : planning en cours de finalisation @Jules Delecour 
  * Clarifier le parcours d'accueil : où aller, quoi lire, quoi faire ? @Jules Delecour 
  * Organisation : 
    * ✅ Kanban pour les Spotters (cf Identified Rules dans ecoCode-Mobile) @Maxime DUBOIS @Jules Delecour 
    * Issues pour les Builders (prévoir un tag spécifique pour le challenge, et un moyen de prévenir les autres qu'on prend une règle) @Olivier Le Goaër @Jules Delecour 
    * Prévoir une présentation du dépôt, de son organisation, et du workflow pour le hackathon @David DE CARVALHO 
    * Prévoir le workflow pour permettre la revue de code dès le jeudi matin @David DE CARVALHO 
    * ✅ Outils de validation des prérequis techniques
* Site ecocode.io
  * Clarifier ce qu'on y met pour pouvoir l'utiliser comme support lors de présentations
  * Passage en GitHub Pages @Geoffrey Lalloué 
  * Mise à jour du contenu @Maxime DUBOIS et l'équipe Snapp' (après le hackathon)
* Société Générale : premier lot de 3 règles simples pour python
  * 2 règles validées (concaténation de strings, copie de tableau)
  * 1 règle mise de côté (Internet in the loop)
  * Proposition de règles complémentaires par des développeurs de la Société Générale, à étudier @Julien HERTOUT 
  * Travail sur un fork privé, PR finale effectuée par la Société Générale sur le dépôt ecoCode
* Distribution des plugins sur le marketplace SonarQube
  * projets de test @David DE CARVALHO 


**Prochains événements :**

:mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 17 mars à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 17.03.2023]

**Sujets abordés :**

* Hackathon 2023
  * 55 inscrits pour le moment
  * :white_check_mark: liste des jurys validé
  * :white_check_mark: Liste des coachs validé
  * :white_check_mark: conférenciers validés
  * :white_check_mark: Planning validé
  * A terminer de préparer :
    * intro du challenge :
      * vidéo d’intro
      * planning
      * Présentation orga + format pitchs
      * présentation des défis et prise en main
    * repo ecoCode-challenge : compléter les parties spotter et builder
  * Builders : liste des règles candidates : ecoCode Standard - Candidate Rules (github.com)
* Article “Programmez” : voir channel #communication pour relecture
  * Envoi le 20/03 et publication dans le numéro n°257
  * Proposition d’article sur le rex du hackaton

**Actions :**

* :white_check_mark: Marquer comme “pinned” les repo ecoCode et ecoCode-mobile sous l’orga GCI

Prochains événements :

:mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 24 mars à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 24.03.2023]

**Sujets abordés :**
* Hackathon 2023
  * :white_check_mark: Evénement maintenu en présentiel
  * :white_check_mark: 87 inscrits sur les 80 prévus, dont 77 sur site -> les inscriptions sont fermées (rediriger vers Véronique en cas de contact)
  * :white_check_mark: Liste des jurys validée
  * :white_check_mark: Liste des coachs validée
  * :white_check_mark: Liste des conférenciers validée (3 le mercredi et 3 le jeudi)
  * :white_check_mark: Planning validé
  * :white_check_mark: Discord mis en place pour l'organisation au cours de l'évènement. On recherche un animateur Discord pour les personnes à distance.
  * :white_check_mark: Présentation du dépôt et de la doc pour le début du hackathon. Voir avec Julien et Maxime M. pour partager la présentation.
  * A terminer de préparer :
    * intro du challenge : @Maxime DUBOIS
      * vidéo d’intro
      * planning
      * Présentation orga + format pitchs :
      * présentation des défis et prise en main
    * repo ecoCode-challenge : revoir les parties spotters et builders (Kanban, matrice des règles, etc.)
  * Builders : liste des règles candidates : ecoCode Standard - Candidate Rules (github.com)

**Actions :**

* Retrouver le template de présentation ecoCode : @Maxime DUBOIS
* Préparer la présentation : @Maxime DUBOIS et @Jules Delecour
* Revoir les parties spotters et builders dans la doc (Kanban, matrice des règles, etc.) : @Jules Delecour


**Prochains événements :**

:mega: Prochain rdv des contributeurs (ouvert à tous) : lundi 3 avril à 11h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 07.04.2023]

**Sujets abordés :**
* Hackathon 2023
  * Gros succès !! :partying_face:
  * Préparation de la comm’ en cours chez davidson, snapp’, rex Page Jaunes
  * Discord : gros +
  * Avoir des coachs à distance permet + de réactivité
* Discussions à avoir prochainement : 
  * organisation : définir les membres de la core-team et contributors + droits associés 
    * Ouverture de la discussion sur le canal #organization 
  * Découpage du repo ecoCode par langage : 1 langage = 1 repo ?
  * Plan de comm’ sur le reste de l’année à prévoir
    * relancer Edwige (solocal)
    * communiquer d’avantage pour la communauté

**Actions :**
* @tous : Proposer son DRAFT d’organisation github sur le canal #organization 
* :broom: nettoyage des PR builders et issues des spotters

**Prochains événements :**

:mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 14 avril à 14h sur Eco Code | Treebal Meet
Après le 14 avril nous repasserons sur un rythme d’1 réunion tous les 15 jours

---

[Compte rendu point ecoCode du 05.05.2023]

**Sujets abordés :**

* traitement de la masse de nos PRs :
  * acceptation de donner droits à des gens bons techniquement (ex : Davidson) en inter-contrat ?
  * avis @david et @julien (à rediscuter tous ensemble) :
    * leur permettre de faire de review technique (mettre en commentaire leurs remarques)
    * dans un second temps, on pourra leur proposer d'intégre un des team "contributors" qui ont le droit de valider les PRs et donc de merger
* Quid des PRs avec "review done" depuis un mois et que ça ne bouge pas ?
  * au bout d'un certains temps, on devra certainement prendre en charge le code => pb : le code provient d'un fork
    * TODO DDC : tester si possibilité de créer une branche avec le code d'uyne PR et pouvoir ensuite modifier et merger nous-mêmes
    * à date : 6 PRs avec "review done" qui n'ont pas bougé depuis 3 semaines
* retour du hackathon (actions)
  * => quels sont les critères d'acceptation d'une PR ? créer un template d'issue pour une nouvelle PR à destination d'implem d'une nouvelle règle
  * créer un template pour nouvelle règle ? implem VS conception
  * check pour que une PR soit la plus propre possible => check si dans doc ou à faire !
  * prendre une PR d'exemple comme référence ? ex : https://github.com/green-code-initiative/ecoCode/pull/152 

@Gilles - Voici un exemple de DoD pour les PR :

* [ ] Implement rule
* [ ] Add documentation and tags on the rule, along with triggering and non triggering examples
* [ ] Write Unit tests (triggering and non triggering cases)
* [ ] Update RULES.md (remove the rule line)
* [ ] Create PR on the test project to add a triggering case
* [ ] Fix potential SonarCloud.io issues
* [ ] update CHANGELOG.md
(dernière ligne ajoutée par @david)

**Actions :**

* @david : tester si possibilité de créer une branche avec le code d'une PR (créée à partir d'un fork) et pouvoir ensuite modifier et merger nous-mêmes ce code
* @tous : décider à partir de quand on prend en charge le code nous-même des PRs qui ne bougent plus
* @david : checker si DoD d'une PR est présent ou non dans la doc
* @tous : rediscuter du process d'intégration de nouveaux contributors car pas clair pour tous
* @tous : trancher sur le DoD de PR (template d'issue ou pas ?) ?

---

[Compte rendu point ecoCode du 12.05.2023]

**Sujets abordés :**

* rediscuter du process d’intégration de nouveaux contributors car pas clair pour tous (voir CR précédent friday-meet)
  * proposition reprise du channel core-team (channel privé, sorry) https://ecocode-workspace.slack.com/archives/C052X4DRW4X/p1681499218679839
  * Sera partagé sur le channel #organization 
  * Ajouter les règles de rétrogradage
  * Validation du process dans 2 semaines
* ruleID : décider de la nomenclature à adopter (voir discussions sur ce channel plus haut)
  * sonarsource rule specifications : Search (sonarsource.github.io)
  * Sonar rules : https://rules.sonarsource.com
  * :bulb:idée : développer un projet reprenant le modèle des rule specifications de sonarsource de manière dynamique
  * Décisions : 
    * :white_check_mark: Ajouter EC en préfix de tous les ruleID : 8 votes sur 8
    * :white_check_mark: Définition du ruleID en “EC + ID” (suppression du trigramme) : 7 votes sur 8
    * :white_check_mark: centralisation de toutes les règles : 8 votes sur 8
  * la centralisation des règles pourrait être fait dans le projet ecoCode existant
* Point sur les PRs : à partir de combien de temps de NON réponse par le commiter après une review, on se dit qu’on fait nous-mêmes les modifs demandées afin de merger au plus vite ?
  * Décision : 1 mois
  * Workflow github pour tagguer automatiquement les PR en attente au bout d’1 mois + envois de mail auto au commiter (voir code ici proposé par @Gilles: https://ecocode-workspace.slack.com/archives/C04CVKHA68H/p1683896285478909)
* :mega: Rappel : les friday-meet ont maintenant lieu toutes les 2 semaines

**Actions :**

* @Geoffrey Lalloué: publier sur #organization la proposition d’intégration des contributors + proposer règles de rétrogradage
* Mettre en place le workflow de tag auto pour PR en attente

**Prochains événements :**

* :mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 26 mai à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 26.05.2023]

**Sujets abordés :**

* Communication et business - Snapp' X Emmanuel ESPIAS
  * Présentation Emmanuel
  * Développement d'un modèle économique pour Snapp' sans dénaturer le projet open source
  * Réfléchir aux possibilités de développement économique pour le projet et le collectif
  * Première action : Création d'une page entreprise ecoCode sur LinkedIn à laquelle chacun pourra se rattacher
* Validation du process d’intégration / rétrogradage de nouveaux contributors ou core-team members suite à proposition faite sur canal #organization
  * Partager sur le Wiki public (@Geoffrey Lalloué)
  * Renommer le dépôt actuel "private-wiki" (@David DE CARVALHO)
* Structuration du dépôt :
  * le projet ecoCode devient le référentiel de règles
  * la documentation commune est dans le projet ecoCode-common
  * chaque plugin est géré dans un projet spécifique (Java, PHP, Python, Android, etc.)
  * réfléchir à un dépôt pour le site web ecocode.io avec CI pour déploiement depuis GitHub et mise à jour par la communauté. Voir pour un hébergement (potentiellement gratuit pour les projets open source, ou financé par le Crédit Agricole)
* Roadmap produit 2023 : partage d’idées sur les thèmes techniques / communication / collectif / ...
  * Il faut trouver des gens pour porter des projets -> poster des "offres d'emploi" sur LinkedIn
  * Validation des règles (mesure ou références)
  * Ménage dans les règles, regarder celles qui existent dans le catalogue Sonar
  * ecoCode Android Kotlin
  * ecoCode HTML
  * ecoCode Infra
  * ecoCode IA
* Plugin HTML : réflexion en cours
* Diffusion sur la marketplace Sonar
  * Point sur l'avancée :
    * Java, Python, PHP OK mais seulement une certaine version -> réfléchir à un process d'automatisation
    * JavaScript en cours
    * Mobile en cours
  * Communication :
    * Publication faite sur LinkedIn pour les plugins disponibles.
    * A faire à chaque nouveau plugin

**Actions :**

* Prévoir un point dédié au plugin HTML pour les aspects techniques  (@Maxime Malgorn)
* Mettre en place le workflow de tag auto pour PR en attente (@David DE CARVALHO)

**Prochains événements :**

:mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 9 juin à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 09.06.2023]

**Sujets abordés :**

* Actions à suivre :
  * Création d'une page entreprise ecoCode sur LinkedIn à laquelle chacun pourra se rattacher -> partager le document (
@Emmanuel ESPIAS)
  * Validation du process d’intégration / rétrogradage de nouveaux contributors ou core-team members suite à proposition faite sur canal #organization
    * Partager sur le Wiki public (@Geoffrey Lalloué)
    * Renommer le dépôt actuel "private-wiki" (@David DE CARVALHO)
  * Prévoir un point dédié au plugin HTML pour les aspects techniques  (@Maxime Malgorn)
  * Mettre en place le workflow de tag auto pour PR en attente (@David DE CARVALHO) -> fait sur le plugin iOS, à généraliser
* Nouveau venu : Julien Wilhelm (Temesis, contributeur RGESN, membre de Green-IT)
* Participation à BDX I/O :
  * plusieurs formats possibles :
    * quickie (inspiration)
    * atelier (plutôt technique)
    * keynote (45 mn)
  * Envoyer propositions à @Emmanuel ESPIAS qui centralise les sujets et relaye auprès des organisateurs
* Participation à Open Source Expérience (6 et 7 décembre 2023 à Paris, candidatures jusqu'au 25 juin) (@Julien Wilhelm)
* Utilisation du référentiel ASCPEM : intéressant, mais plutôt orienté performances et pas green coding. Eventuellement source d'inspiration pour des règles ecoCode. Olivier a répondu.
* Découpage technique de la partie frontend d'ecoCode : cf discussions sur le canal #dev-js. Aujourd'hui on a un plugin JavaScript qui contient des règles frontend et backend. Pertinence de la création d'un plugin frontend (HTML, CSS, JS) ? Peut-être trop tôt au vu du nombre de règles. Utiliser des tags ou des profils prédéfinis ?
* Evaluation et validation des règles (cf https://github.com/green-code-initiative/ecoCode/issues/198 et rule EC2). C'est de la R&D, il faut recruter des académiques (
@Olivier Le Goaër). Faire un appel à contributions, prévoir un work package pour le prochain hackathon? En attendant, on peut enlever la règle single quote / double quote en python si elle n'est pas pertinente. Cette règle reste cependant valide dans d'autres langages.

**Prochains événements :**

:mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 23 juin à 14h sur Eco Code | Treebal Meet

---

[Compte rendu point ecoCode du 23.06.2023]

**Sujets abordés :**
* Actions à suivre :
  * Création d'une page entreprise ecoCode sur LinkedIn à laquelle chacun pourra se rattacher -> partager le document (
@Emmanuel ESPIAS)  :white_check_mark:
  * Site web : Arborescence proposée par @Emmanuel ESPIAS sur Canva, maquettes réalisées par Jacques -> partager sur le canal #communication (@Maxime DUBOIS) Ensuite Snapp' devrait avoir de la disponibilité pour développer le site. Techno à valider avec le collectif (@Greg). En profiter pour vérifier les contrastes sur la charte graphique, et faire une déclaration environnementale (https://declaration.greenit.fr/)
  * Validation du process d’intégration / rétrogradage de nouveaux contributors ou core-team members suite à proposition faite sur canal #organization
    * Partager sur le Wiki public (@Geoffrey Lalloué)
    * Renommer le dépôt actuel "private-wiki" (@David DE CARVALHO)
  * Prévoir un point dédié au plugin HTML pour les aspects techniques  (@Maxime Malgorn) -> on va proposer un plugin JavaScript et un plugin HTML
  * Mettre en place le workflow de tag auto pour PR en attente -> fait sur le plugin iOS, à tester et généraliser (@David DE CARVALHO)
* Découpage des dépôts :
  * ecocode-ios en cours (v1.1.0)
  * renommage d'ecocode-mobile en ecocode-android en cours
  * ecocode-linter devient ecocode-javascript
  * ecocode standard : finalisation des PR du hackathon puis découpage
  * centralisation des règles
* Publication des dépendances communes sur maven central (@Greg), habilitations pour publication sur maven central : déterminer quel compte on utilise -> créer un compte pour le collectif (@David DE CARVALHO)
* Présentation générique : format vs format web -> regarder ce qu'on peut faire avec marp au niveau de l'export ppt pour les non techniciens (@Julien Wilhelm)
* Roadmap : priorisation et assignation -> lister les sujets pour que chaque membre puisse se positionner sur certains sujets (@Geoffrey Lalloué)
* Participation au Dev Fest de Nantes 19/10 et 20/10 : sujet proposé par @David DE CARVALHO et @Johanna D.
* Participation à BDX I/O le 10/11 (dépôt des sujets avant le 19/07)
* Participation à Open Source Expérience (6 et 7 décembre 2023) à Paris : le Crédit Agricole y va

**Prochains événements :**

:mega: Prochain rdv des contributeurs (ouvert à tous) : vendredi 7 juillet à 14h sur Eco Code | Treebal Meet
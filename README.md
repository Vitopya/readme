# L'Odyssée de Teams

## Glossaire

|Terme|Définition|
|----|-----|
|**Administrateur tenant Microsoft Teams**|Utilisateur.ice ayant un accès à la console Microsoft Teams pour installer et configurer L'Odyssée|
|**Cockpit**|Interface principale d'accueil du jeu de L'Odyssée de Teams|
|**Explorateur.ice**|Utilisateur.ice ayant le rôle de joueur.euse avec un accès standard à L'Odyssée|
|**L'Odyssée de Teams**|Serious game destiné à l'apprentissage des usages et bonnes pratiques de Microsoft Teams|
|**Maître du jeu/ Commandant**|Utilisateur.ice ayant le rôle d'administrateur de jeu avec un accès aux interfaces Maître du jeu|
|**Mission**|Module de 45 questions hebdomadaire activable et désactivable par le Maître du jeu|
|**Outillage**|Fonctionnalité Maître du jeu pour configurer le logo d'une organisation et arrêter le jeu en cours|


## Sommaire
* [Intro](#Intro)
* [Guide d’installation de l’application L’Odyssée de Teams](#guide-dinstallation-de-lapplication-lodyssée-de-teams)
    * [Avant-propos](avant-propos)
    * [Un pare-feu bloque l’installation](#un-pare-feu-bloque-linstallation)
    * [À propos de Saegus](#À-propos-de-Saegus)
    * [5 étapes pour une installation réussie](#5-étapes-pour-une-installation-réussie)
* [Premiers pas pour activer L'Odyssée de Teams - Le rôle du Maître du jeu](#premiers-pas-pour-activer-lodyssée-de-teams---le-rôle-du-maître-du-jeu)
    * [Introduction](#Introduction)
    * [Devenir Maître du jeu et configuration d'une saison L'Odyssée de Teams](#devenir-maître-du-jeu-et-configuration-dune-saison)
    * [Première connexion](#Première-connexion)
* [FAQ](#FAQ)

    
## Introduction
L’Odyssée de Teams est un serious game conçu par Microsoft sous la forme d’une web application ayant pour but de fidéliser l’adoption et les usages de Microsoft Teams auprès des utilisateurs au sein des organisations. Au cours d’une saison de 4 semaines, répondez à plus de 200 questions réparties en 8 thématiques et sous 3 niveaux de difficulté. Collectionnez les médailles d’accomplissement ainsi que les points au classement pour tenter de remporter les précieux lots mis en jeu tout en approfondissant vos connaissances de Teams. L'application propose un mode de gestion de jeu pour les Maîtres du jeu ainsi qu'un kit d'assets de communication clé en main pour soutenir vos actions de communication.
Plusieurs étapes sont nécessaires pour correctement déployer le jeu :
- Installation de l'application
- Déclaration et activation du jeu par les Maîtres du jeu
- Lancement d'une saison intergalactique
Ce Read.me a pour objectif de vous aider pas-à-pas pour chacune de ces étapes.

## Guide d’installation de l’application L’Odyssée de Teams

### Avant-propos
L’Odyssée de Teams est une web application dont le package au format .zip doit être installé sur le store Microsoft Teams de votre organisation. Cette manipulation requiert des droits d'accès spécifiques à la console Admin Microsoft Teams.
Si votre organisation a désactivé le store Microsoft Teams, vous trouverez ci-dessous un lien de réactivation afin de vous permettre de procéder à l’installation de l'application.

https://docs.microsoft.com/fr-fr/MicrosoftTeams/manage-apps

NB : Notez qu’il n’y a aucun port spécifique à ouvrir lors de la manipulation.

### Un pare-feu bloque l’installation
Si un pare-feu ou un proxy quelconque bloque le processus d'installation, le lien ci-dessous vous permet d’ajouter une règle (policy) pour autoriser les appels à cette URL.

https://odyssee-de-teams.saegus.com/

### À propos de Saegus
Saegus est une consultech française partenaire de Microsoft qui a co-conçu L'Odyssée de Teams. Saegus héberge les données du jeu suivantes sur son store Azure (RGPD compliant) :
- Les noms des utilisateur.ice.s
- L’ID du tenant des utilisateur.ice.s

NB : Les données hébergées sont entièrement cryptées. 30 jours après la fin du jeu, les données sont entièrement effacées.

### 5 étapes pour une installation réussie

#### 1ère étape : Accédez à votre console Admin Microsoft Teams
Dans un premier temps, rendez vous sur votre console Admin Microsoft Teams. L’adresse URL suivante vous permet d'y accéder directement en l'insérant dans votre barre de recherche de navigateur.

https://admin.teams.microsoft.com

#### 2ème étape : Manage Apps
Dans la barre latérale de gauche de votre console, cliquez sur «Teams apps» puis sur «Manage Apps».

<img width="964" alt="2021-11-05 15 10 02" src="https://user-images.githubusercontent.com/93584324/140523769-543c3461-07c4-4ad5-8e7c-b4d80951f44b.png">

#### 3ème étape : Uploadez le fichier .zip sur votre tenant
Cliquez sur le bouton «Upload» puis sur «Select a file» pour aller chercher le fichier .zip de l’application sur votre ordinateur. Si l'import est un succès, l'icône et le nom de l'application apparaîtront.

<img width="1177" alt="2021-11-05 15 17 00" src="https://user-images.githubusercontent.com/93584324/140524694-e5c8cee5-91ba-4e51-bfe1-7a4b5acb7446.png">

#### 4ème étape : Policies
Toujours via votre barre latérale de gauche, cliquez sur «Setup policies» puis sur la Policy désirée. Notez que la policy «Global» proposée correspond à l’ensemble des utilisateur.ice.s de votre tenant Teams.
Si vous souhaitez configurer un accès spécifique à une population d'utilisateur.ice.s de votre tenant, vous devrez cliquer sur "+ Add" afin de configurer une nouvelle policy.

<img width="712" alt="2021-11-05 15 18 00" src="https://user-images.githubusercontent.com/93584324/140524850-b5b50e5e-8d40-49f3-ba33-bfc863495865.png">

#### 5ème étape : Configurez une policy
Cliquez sur votre policy afin d'entrer dans le volet de configuration.
- Veillez à toujours avoir les toggles "Upload custom app" et "Allow user pinning" d'activés.
- Pour associer L'Odyssée de Teams à votre policy, cliquez sur le premier bouton «Add apps» pour ouvrir le volet latéral de recherche. Recherchez L'Odyssée de Teams puis sélectionnez-la en cliquant sur "Add".
- Enfin, il vous est possible d'épingler l'application par défaut sur la barre de navigation Teams des utilisateur.ice.s pour garantir un accès rapide. Pour cela, ajoutez l'application en cliquant sur "+ Add apps" dans la partie "Pinned apps".

<img width="1099" alt="2021-11-05 15 18 54" src="https://user-images.githubusercontent.com/93584324/140524967-90c8f406-4daf-4ea2-9374-d12e2cf76139.png">

<img width="697" alt="021-11-05 15 19 46" src="https://user-images.githubusercontent.com/93584324/140525127-4824967e-b1ae-4d57-83fd-162a2e5d1159.png">

Félicitations ! L'application L'Odyssée de Teams est maintenant installée et configurée pour utilisation !


## Premiers pas pour activer L'Odyssée de Teams - Le rôle du Maître du jeu

### Introduction
Maintenant que l'application L'Odyssée de Teams a été correctement installée sur votre tenant Microsoft Teams, il est nécessaire de l'activer. Pour cela, le Maître du jeu intervient. Tant que le jeu n'a pas été activé par l'un.e des Maîtres du jeu, les Explorateur.ice.s ne pourront pas accéder aux interfaces de jeu.

### Devenir Maître du jeu et configuration d'une saison
Un.e Maître du jeu a pour objectif de gérer une saison de 4 semaines pendant lesquelles les Explorateur.ice.s répondront à plus de 200 questions. Un.e Maître du jeu a à sa disposition des interfaces spécifiques qui lui permettront d'installer le logo de son organisation, mettre le jeu en pause, activer les modules de questions chaque semaine et accéder aux statistiques de jeu en temps réel.

Un.e Maître du jeu peut également être responsable de la partie communication en interne autour et tout le long d'une saison. Pour cela, un kit d'assets de communication clé en main est mis à sa disposition.

Pour attribuer le rôle de Maître du jeu à un utilisateur.ice, la personne doit se déclarer en envoyant un email à l'adresse : joseph.deffayet@saegus.com avec les informations suivantes :
- Adresse email du ou des Maîtres du jeu
- Date de lancement souhaitée pour la saison L'Odyssée de Teams

NB : Une adresse email déclarée en tant que Maître du jeu ne pourra pas accéder au jeu en tant qu'Explorateur.ice.
Dès la réception email de la bonne création de l'environnement de jeu par Saegus, le ou la Maître du jeu peut se rendre sur l'application pour l'activer.

### Première connexion
Lors de votre première connexion, acceptez les conditions de Règlement Général sur la Protection des Données (RGPD) puis sélectionnez votre avatar (vaisseau). Cet avatar ne sera pas modifiable par la suite, choisissez-le judicieusement ! Vous êtes alors redirigé.e vers l'interface principale : le cockpit. À ce moment-là, le jeu est activé et accessible pour l'ensemble des Explorateur.ice.s.
 
 <img width="547" alt="Annotation 2021-11-02 155038" src="https://user-images.githubusercontent.com/93584324/139871200-33bdf7d8-1d34-48cf-ada8-d03988050254.png">

### Activer le premier module de questions
Tant qu'un des modules n'est pas activé, les Explorateur.ice.s n'auront pas accès aux questions du jeu. Pour activer un module, rendez vous dans l'onglet "Planning" de votre interface puis dans le sous-onglet "Programme et missions". Pour activer un module de questions, cliquez sur "Mission en attente". Les Explorateur.ice.s ont désormais accès aux 45 questions de la semaine. Répétez cette action chaque semaine de la saison.

NB : Si vous avez mis le jeu en pause via l'onglet "Outillage", vous pouvez le réactiver à tout moment en cliquant simplement sur l'un des modules de questions.

Félicitations, la saison L'Odyssée de Teams est maintenant lancée !

### Guide du Maître du jeu - Pour aller plus loin
Toutes les informations spécifiques au rôle de Maître du jeu sont disponibles dans le document "L'Odyssée de Teams - Règles_Admin.pdf" fourni avec le jeu.

## FAQ

### Installation & gestion

#### Mon organisation ne dispose pas de toutes les fonctionnalités de Microsoft Teams, est-il possible de ne pas déployer les questions correspondantes aux Explorateur.ice.s ?
Il est possible de désactiver des thématiques de questions propres à chaque grande fonctionnalité de Microsoft Teams. Pour cela, rendez-vous dans l'onglet "Planning" de votre interface Maître du jeu. Dans le sous-onglet "Programme et missions", cliquez sur "Configuration" pour accéder à un menu interactif qui vous permettra de désactiver jusqu'à deux thématiques de questions. Il n'est pas possible de désactiver plus de deux thématiques afin de garantir le bon fonctionnement du jeu.

#### Est-ce qu'une réinstallation est nécessaire si une nouvelle fonctionnalité est ajoutée au jeu ?
Non, aucune nouvelle installation n'est nécessaire pour accéder aux nouvelles fonctionnalités. Si une nouvelle installation est nécessaire, une note sera mise à disposition des organisations avec le détail et la raison.

#### Est-ce que j'ai besoin de créer un compte pour jouer à l'application L'Odyssée de Teams ?
Non, il n'y pas besoin de créer un compte ou de s'authentifier pour accéder au jeu. Il s'agit d'une authentification transparente avec le compte utilisateur connecté sur Microsoft Teams (SSO).

#### Est-il possible de jouer au jeu tout en étant dans le rôle de Maître du jeu ?
Non, il n'est pas possible d'accéder aux interfaces Explorateur.ice en tant que Maître du jeu. Il n'est donc pas possible de participer au jeu. Il est recommandé d'utiliser un autre compte.

### Jeu

#### En combien de temps se joue L'Odyssée de Teams ?
L'Odyssée de Teams est un jeu conçu pour être joué sur 4 semaines de 5 jours ouvrés.

#### Est-ce que le jeu est accessible le week-end ?
Non, le jeu est inaccessible le week-end.

#### Est-ce que le jeu est accessible sur l'application Teams mobile ?
Oui, le jeu est accessible sur Teams mobile pour les Explorateur.ice.s. Il est vivement recommandé aux Maîtres du jeu de n'accéder aux interfaces Maîtres du jeu que sur l'application desktop.

#### Est-il possible de consulter l'ensemble des thématiques et questions du jeu ?
Oui, il est possible de consulter les questions de L'Odyssée de Teams dans le document "L'Odyssée de Teams - Questions & réponses.xlsx".

#### Existe t-il des conseils pour aider les Explorateur.ice.s à comprendre et jouer au jeu ?
Oui, il existe un guide pour aider les joueur.euse.s à comprendre et assimiler le fonctionnement et les mécaniques du jeu. Ce guide se nomme "L'Odyssée de Teams - Guide_Explorateur.pdf" et est également téléchargeable depuis l'interface de jeu du joueur.euse via l'onglet "Règles du jeu".
De la même manière, il existe un guide pour accompagner les Maîtres du jeu "L'Odyssée de Teams - Guide Maître du jeu.pdf".

### Sécurité & Data access

#### Les données sont-elles cryptées ?
Oui. Un développement spécifique au cryptage des noms et ID des utilisateur.ice.s a été fait dans le but de prévenir d'éventuels intrusions et autres risques. Tous les détails relatifs au cryptage sont disponibles dans le document "Odyssée_ReleaseNote_Cryptage.pdf".

#### Est-ce que L'Odyssée de Teams dispose de RGPD et où puis-je les consulter ?
Oui, L'Odyssée de Teams dispose de RGPD qui sont accessibles dès la première connexion au jeu par l'utilisateur.ice qu'il.elle soit Explorateur.ice ou Maître du jeu. Une validation des conditions est nécessaire pour pouvoir accéder au contenu du jeu. L'ensemble de ces RGPD est également consultable dans le document "Teams_Odyssey - Disclaimer.pdf".

#### Combien de temps sont conservées les données de jeu de mon organisation sur le serveur Azure de Saegus ?
Les données de jeu d'une organisation sont conservées jusqu'à 30 jours après la fin d'une saison. Conformément aux RGPD qui sont associées à l'application, les données de jeu sont entièrement supprimées par Saegus. Une fiche de confirmation de suppression officielle est envoyée à l'organisation après effacement. Une fois que les données de jeu sont supprimées, il n'est alors plus possible de les récupérer.

#### Existe t-il un document regroupant l'ensemble des données de sécurité et d'accès pour L'Odyssée de Teams ?
Oui, ce document est disponible sous le nom de "Microsoft - Security and data access.pdf".

#### Quelles sont les informations liées au compte Azure Saegus qui héberge les données de jeu de L'Odyssée de Teams ?
Les informations du compte Azure de Saegus sont les suivantes :
- Hosting Azure : Apps service: France-Central; Database: France-Central; Location: Paris (https://azure.microsoft.com/en-us/global-infrastructure/geographies/#geographies)
- Global compliance : CIS Benchmark, CSA STAR Attestation, CSA STAR Certification, CSA STAR Self-Assessment, ISO 20000, ISO 22301, ISO 27001, ISO 27017, ISO 27018, ISO 27701, ISO 9001, SOC 1, SOC 2, SOC 3, WCAG 2.0 Regional/Country Compliance HDS, EN 301 549, ENISA IAF, EU Model Clauses, EU-US Privacy Shield, GDPR Industry Compliance AMF/ACPR, EBA, CDSA, GxP, PCI DSS, Shared Assessments, TruSight
- SSO authentication : SSO authentification (login Microsoft teams) with @microsoft/teams-js SDK And Graph API.
Communication is secured by a token exchange (JWT - RFC 7519)

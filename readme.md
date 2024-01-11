# Projet GL02 - Logiciel de gestion des locaux d'une université

# Contexte

L'université centrale de la république de Sealand (SRU) souhaite faciliter la gestion de ses locaux ainsi que l'organisation de ses usagers (enseignants et étudiants) en leur proposant un outil de suivi d'occupation des salles de cours. 

Le système de planification générale des cours (PGC) réalise un export de l'emploi du temps au format CRU qui établit des créneaux de cours hebdomadaires avec chaque salle disponible.

Un cours est précédé par le caractère +, puis chaque ligne défini un créneau d’enseignement avec son type, le
capacitaire du créneau, son horaire, son index de sous-groupe et enfin la salle.
La SRU passe commande à votre équipe pour la réalisation d'un utilitaire en invite de commande où ses usagers
pourront demander pour un cours donnée les salles associées et également récupérer les capacités maximales en
terme de nombre de place d'une salle donnée. 

Les usagers pourront voir à quel moment de la semaine une certaine
salle est libre (pour travailler ensemble) ou quelles salles seront libres pour un créneau donné dans la semaine.
Grâce à ce nouvel outil de suivi, un étudiant ou un enseignant pourra également générer un fichier iCalendar (RFC
5545) entre deux dates données pour les enseignement (CM, TD ou TP) auxquels il participe et ainsi l'intégrer à son
propre logiciel d'agenda.
Votre logiciel devra également vérifier la qualité des données d'emploi du temps dans la mesure où un créneau dans
une salle ne peut être utilisé que par un seul enseignement et sans recouvrement possible.


Par ailleurs l'université souhaite que cet outil l'aide à réaliser un suivi de l'occupation des locaux. Elle demande la
génération d'une visualisation synthétique du taux d'occupation des salles et un classement par capacité d'accueil
(ie, combien de salles de 24 places). L'idée est pour le gestionnaire des locaux de pouvoir identifier quelles salles
sont sous-exploitées ou sur-exploitées pour pouvoir enquêter sur la question et décider des aménagements futurs.

# Installation

Ce logiciel nécessite l'installation de :
- **Node.js** : https://nodejs.org/en 
- **Git** : https://git-scm.com/

#### Git :
Pour cloner le dépôt contenant le logiciel :

``` 
git clone https://github.com/Veitzen/GL02_A23_LesCompilateursCosmiques_.git
```

#### Dépendances :

Pour installer les dépendances du logiciel, on réalise la commande :
``` 
npm install [nom du package]
```

Voici la liste des dépendances :

- exceljs

# Utilisation

Pour l'utilisation du logiciel, veuillez vous reférer sur la page du guide de démarrage utilisateur du wiki  :

https://github.com/Veitzen/GL02_A23_LesCompilateursCosmiques_/wiki/Guide-de-d%C3%A9marrage-utilisateur

# Développeurs 

Pour ceux qui veulent contribuer au projet, veuillez vous reférer sur la page sur le guide destiné aux développeurs du wiki :

https://github.com/Veitzen/GL02_A23_LesCompilateursCosmiques_/wiki/Guide-destin%C3%A9-aux-d%C3%A9veloppeurs

On vous dispose également du cahier de recettes et du plan de test réalisé :

https://github.com/Veitzen/GL02_A23_LesCompilateursCosmiques_/wiki/Cahier-de-recettes-%E2%80%90-plan-de-test

# Licence

Ce projet est sous la licence MIT disponible sur le lien : https://github.com/Veitzen/GL02_A23_LesCompilateursCosmiques_/blob/main/LICENSE

# Contributeurs du projet :

**Équipe "Les Compilateurs Cosmiques"** :

- M. Chivas (matthieu.chivas@utt.fr)
- M. Florian Bonelli (florian.bonelli@utt.fr)
- M. Adrien Laugier (adrien.laugier@utt.fr)
- Mme Jeanne Raynaud (jeanne.raynaud@utt.fr)
- Mme Alice Tréché (alice.treche@utt.fr)

**Équipe "Les boss  du CDC"** :

- M. Hoang-Viêt Le (hoang_viet.le@utt.fr)
- M. Louis Delhomme (louis.delhomme@utt.fr)
- Mme Clémence Vu (clemence.vu@utt.fr)
- M. Brayan Takam Talla (vigny_brayan.takam_talla@utt.fr)

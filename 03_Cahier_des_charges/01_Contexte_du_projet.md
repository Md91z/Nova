\# CAHIER DES CHARGES



\## Projet de système d'information — Banque NOVA



\*\*Projet :\*\* Banque NOVA

\*\*Formation :\*\* BTS SIO — Option SISR

\*\*Version :\*\* 1.0

\*\*Statut :\*\* Projet / conception



\---



\# 1. Présentation du projet



\## 1.1 Présentation de l'entreprise



Banque NOVA est une banque fictive destinée aux particuliers et aux professionnels.



L'entreprise compte 25 collaborateurs répartis dans plusieurs services :



\* Direction

\* Accueil / Administration

\* Conseillers bancaires

\* Comptabilité

\* Ressources humaines

\* Informatique

\* Sécurité



Le présent projet concerne exclusivement le système d'information interne de Banque NOVA.



Les données utilisées dans le projet sont fictives et aucune donnée bancaire réelle ne sera utilisée.



\---



\# 2. Contexte



L'organisation de Banque NOVA nécessite un système d'information permettant aux collaborateurs d'accéder aux ressources nécessaires à leur activité tout en respectant les exigences de sécurité et de confidentialité.



L'entreprise doit notamment pouvoir :



\* gérer les comptes utilisateurs ;

\* contrôler les accès aux ressources ;

\* partager des documents ;

\* fournir des services informatiques internes ;

\* proposer un support aux utilisateurs ;

\* surveiller les services ;

\* protéger les données ;

\* sauvegarder les informations importantes ;

\* assurer le rétablissement des services en cas d'incident.



Le projet consiste donc à concevoir une infrastructure informatique cohérente et adaptée à une organisation de 25 utilisateurs.



\---



\# 3. Problématique



> \*\*Comment Banque NOVA peut-elle mettre en place un système d'information sécurisé, centralisé et disponible permettant à ses 25 collaborateurs d'accéder efficacement aux ressources de l'entreprise tout en protégeant les données sensibles de ses clients ?\*\*



Cette problématique constitue le fil conducteur du projet.



Les choix techniques devront répondre à un besoin identifié et être justifiés.



\---



\# 4. Besoins



Le besoin principal est de disposer d'un système d'information centralisé permettant aux collaborateurs d'utiliser les ressources informatiques nécessaires à leur activité tout en maîtrisant les accès et les risques.



Les besoins identifiés sont :



\* centraliser les comptes utilisateurs ;

\* organiser les utilisateurs par service ;

\* contrôler les droits d'accès ;

\* permettre le partage sécurisé de fichiers ;

\* fournir des services Web ;

\* permettre la gestion des demandes et incidents ;

\* superviser l'infrastructure ;

\* sauvegarder les données ;

\* restaurer les données en cas d'incident ;

\* segmenter le réseau ;

\* contrôler les communications ;

\* assurer le maintien ou le rétablissement des services essentiels ;

\* documenter l'infrastructure et les procédures.



\---



\# 5. Objectifs



Le projet doit permettre à Banque NOVA de disposer d'un système d'information :



\* centralisé ;

\* sécurisé ;

\* segmenté ;

\* administrable ;

\* documenté ;

\* supervisé ;

\* sauvegardé ;

\* évolutif.



Les objectifs techniques et organisationnels sont notamment :



1\. Centraliser l'authentification des utilisateurs.

2\. Organiser les utilisateurs par service.

3\. Mettre en place une gestion des droits.

4\. Segmenter le réseau avec des VLAN.

5\. Séparer les ressources internes des services publics.

6\. Mettre en place un serveur de fichiers.

7\. Mettre à disposition un système de support.

8\. Développer ou intégrer une application Web répondant à un besoin interne.

9\. Relier l'application à une base de données.

10\. Faire communiquer l'application avec un service externe.

11\. Superviser les équipements et services importants.

12\. Mettre en place une stratégie de sauvegarde.

13\. Réaliser un test de restauration.

14\. Préparer les procédures de gestion des incidents.

15\. Tester et documenter la solution.



\---



\# 6. Utilisateurs



| Utilisateur    | Besoins principaux                                                              |

| -------------- | ------------------------------------------------------------------------------- |

| Direction      | Accéder aux informations et ressources nécessaires à la gestion de l'entreprise |

| Conseillers    | Accéder aux ressources nécessaires à leur activité                              |

| Administration | Gérer les documents et ressources administratives                               |

| Comptabilité   | Accéder aux ressources comptables                                               |

| RH             | Accéder aux ressources RH protégées                                             |

| Informatique   | Administrer et superviser le système d'information                              |

| Sécurité       | Accéder aux ressources nécessaires au suivi de la sécurité                      |

| Invités        | Disposer d'un accès réseau limité et isolé                                      |



Les droits doivent être attribués selon le profil et les besoins de chaque utilisateur.



\---



\# 7. Fonctionnalités attendues



\## 7.1 Gestion des utilisateurs



Le système doit permettre :



\* de créer des comptes ;

\* de modifier les comptes ;

\* de désactiver les comptes ;

\* d'organiser les utilisateurs ;

\* de gérer les groupes ;

\* d'appliquer des politiques de sécurité.



\## 7.2 Gestion des fichiers



Le système doit permettre :



\* de stocker les documents ;

\* de partager les ressources ;

\* de séparer les données par service ;

\* de contrôler les permissions ;

\* de limiter l'accès aux données sensibles.



\## 7.3 Support informatique



Les utilisateurs doivent pouvoir déclarer des demandes et incidents.



Les demandes doivent pouvoir être :



\* collectées ;

\* enregistrées ;

\* catégorisées ;

\* affectées ;

\* suivies ;

\* traitées ;

\* clôturées.



\## 7.4 Application NOVA SUPPORT



Une application Web interne nommée \*\*NOVA SUPPORT\*\* est prévue.



Elle doit permettre notamment :



\* l'authentification ;

\* la création d'un ticket ;

\* la description d'un incident ;

\* la sélection d'une catégorie ;

\* la définition d'une priorité ;

\* le suivi du statut ;

\* l'affectation à un technicien ;

\* l'ajout de commentaires ;

\* la consultation de l'historique ;

\* la clôture du ticket.



L'application devra être reliée à une base de données et communiquer avec au moins un service externe.



\---



\# 8. Site vitrine



Un site vitrine public doit présenter :



\* Banque NOVA ;

\* son activité ;

\* ses services ;

\* ses coordonnées ;

\* des informations générales sur l'entreprise.



Le site ne doit contenir aucune donnée bancaire réelle.



Il sera placé dans une zone dédiée aux services publics.



\---



\# 9. Gestion des tickets et ITIL



Un outil de gestion des tickets sera mis en place afin de structurer le support informatique.



GLPI pourra être utilisé comme outil de support.



La gestion devra notamment prendre en compte :



\* les demandes ;

\* les incidents ;

\* les priorités ;

\* les catégories ;

\* l'affectation ;

\* le traitement ;

\* la résolution ;

\* la clôture ;

\* l'historique.



L'utilisation de GLPI devra être cohérente avec l'application NOVA SUPPORT afin d'éviter les doublons fonctionnels inutiles.



\---



\# 10. Infrastructure



L'infrastructure sera composée de plusieurs machines ou machines virtuelles.



Les principaux services prévus sont :



| Service             | Fonction                               |

| ------------------- | -------------------------------------- |

| Active Directory    | Gestion centralisée des utilisateurs   |

| DNS                 | Résolution des noms                    |

| DHCP                | Attribution des paramètres réseau      |

| Serveur fichiers    | Stockage et partage                    |

| Serveur Web         | Hébergement du site                    |

| Serveur application | Hébergement de NOVA SUPPORT            |

| Serveur BDD         | Stockage des données applicatives      |

| GLPI                | Gestion des tickets                    |

| Zabbix              | Supervision                            |

| Sauvegarde          | Protection et restauration des données |



\---



\# 11. Architecture réseau



L'architecture réseau repose sur une segmentation par VLAN.



Les VLAN prévus sont :



| VLAN | Service        | Réseau           |

| ---: | -------------- | ---------------- |

|   10 | Direction      | 192.168.10.0/24  |

|   20 | Conseillers    | 192.168.20.0/24  |

|   30 | Administration | 192.168.30.0/24  |

|   40 | Comptabilité   | 192.168.40.0/24  |

|   50 | RH             | 192.168.50.0/24  |

|   60 | Informatique   | 192.168.60.0/24  |

|   70 | Serveurs       | 192.168.70.0/24  |

|   80 | Invités        | 192.168.80.0/24  |

|   90 | Management     | 192.168.90.0/24  |

|  100 | DMZ            | 192.168.100.0/24 |



Chaque réseau disposera d'une passerelle adaptée à l'architecture retenue.



\---



\# 12. Sécurité réseau



La sécurité réseau reposera notamment sur :



\* la segmentation VLAN ;

\* le routage contrôlé ;

\* le filtrage réseau ;

\* la séparation du réseau invité ;

\* la séparation de la DMZ ;

\* la gestion des droits ;

\* la supervision ;

\* la sauvegarde ;

\* la journalisation.



Le principe du moindre privilège sera appliqué.



Un utilisateur ne doit accéder qu'aux ressources nécessaires à son activité.



\---



\# 13. DMZ



Les services accessibles depuis Internet seront séparés du réseau interne.



Le site Web public sera placé dans la DMZ.



La DMZ prévue utilise :



`192.168.100.0/24`



Le serveur Web public prévu est :



`SRV-WEB — 192.168.100.10`



Les communications entre Internet, la DMZ et le réseau interne devront être contrôlées.



\---



\# 14. Serveurs



Les serveurs prévus sont :



| Serveur         | Adresse prévue | Fonction          |

| --------------- | -------------- | ----------------- |

| SRV-AD-DNS-DHCP | 192.168.70.10  | AD / DNS / DHCP   |

| SRV-FICHIERS    | 192.168.70.20  | Fichiers          |

| SRV-GLPI        | 192.168.70.30  | Tickets / support |

| SRV-ZABBIX      | 192.168.70.40  | Supervision       |

| SRV-BDD         | 192.168.70.50  | Base de données   |

| SRV-APP         | 192.168.70.60  | Application       |

| SRV-WEB         | 192.168.100.10 | Site Web public   |



Ces valeurs correspondent à la maquette réseau actuelle et pourront être ajustées si la mise en œuvre réelle impose une modification.



\---



\# 15. Active Directory



Le domaine prévu est :



`novabank.local`



L'organisation logique pourra être structurée selon les services :



```text

NOVABANK

│

├── Utilisateurs

│   ├── Direction

│   ├── Conseillers

│   ├── Administration

│   ├── Comptabilite

│   ├── RH

│   ├── Informatique

│   └── Securite

│

├── Groupes

├── Ordinateurs

└── Serveurs

```



Les groupes seront utilisés pour faciliter l'attribution des permissions.



\---



\# 16. Gestion des droits



Les droits seront attribués en fonction :



\* du service ;

\* du rôle ;

\* du besoin d'accès ;

\* de la sensibilité des données.



Les permissions seront documentées dans une matrice des droits.



Les ressources sensibles devront être protégées contre les accès non autorisés.



\---



\# 17. Base de données



La base de données de l'application devra permettre de stocker les informations nécessaires au fonctionnement de NOVA SUPPORT.



Les principales entités prévues sont :



\* Utilisateur ;

\* Service ;

\* Ticket ;

\* Catégorie ;

\* Priorité ;

\* Statut ;

\* Commentaire.



Le modèle de données sera détaillé dans la partie dédiée à la conception de la base de données.



\---



\# 18. Service externe



L'application devra communiquer avec au moins un service externe.



Le scénario retenu pourra notamment être une notification par e-mail lors de la création d'un ticket important.



Le service externe ne devra recevoir que les informations nécessaires.



Les données sensibles ou inutiles ne devront pas être transmises.



\---



\# 19. Supervision



La supervision permettra de surveiller notamment :



\* la disponibilité des serveurs ;

\* l'utilisation CPU ;

\* la mémoire ;

\* l'espace disque ;

\* le réseau ;

\* les services ;

\* les alertes.



Zabbix est prévu comme solution de supervision.



Les alertes devront permettre d'identifier les incidents afin de faciliter leur traitement.



\---



\# 20. Sauvegarde



Une stratégie de sauvegarde devra être mise en place.



Elle devra définir :



\* les données sauvegardées ;

\* la fréquence ;

\* la destination ;

\* la durée de conservation ;

\* les contrôles ;

\* les procédures de restauration.



Un test de restauration devra être réalisé et documenté.



\---



\# 21. Continuité de service



Les services essentiels devront disposer de mesures permettant leur rétablissement après incident.



Les services critiques seront notamment :



\* Active Directory ;

\* DNS ;

\* DHCP ;

\* fichiers ;

\* application ;

\* base de données ;

\* support ;

\* supervision.



Les objectifs de reprise seront définis en fonction des possibilités réelles du projet.



Aucune haute disponibilité irréaliste ne sera annoncée.



\---



\# 22. Sécurité des utilisateurs



Des règles d'utilisation seront définies concernant notamment :



\* les mots de passe ;

\* le verrouillage des comptes ;

\* le phishing ;

\* les pièces jointes ;

\* les supports amovibles ;

\* les données sensibles ;

\* l'utilisation des ressources ;

\* les signalements d'incidents.



Les utilisateurs devront disposer de procédures et supports adaptés.



\---



\# 23. Analyse du trafic et indicateurs



Des indicateurs permettront notamment de suivre :



\* la disponibilité des services ;

\* le trafic réseau ;

\* les incidents ;

\* les tickets ;

\* les performances ;

\* les sauvegardes ;

\* l'avancement du projet.



Les valeurs réelles seront renseignées après réalisation des tests.



\---



\# 24. Contraintes



\## Contraintes fonctionnelles



La solution doit :



\* répondre aux besoins des 25 collaborateurs ;

\* permettre la gestion des utilisateurs ;

\* fournir les services nécessaires ;

\* permettre la gestion des incidents ;

\* assurer la sauvegarde des données.



\## Contraintes techniques



La solution doit être :



\* réalisable dans un environnement étudiant ;

\* documentée ;

\* testable ;

\* évolutive ;

\* cohérente avec les ressources disponibles.



\## Contraintes de sécurité



Les données doivent être protégées contre :



\* les accès non autorisés ;

\* les erreurs utilisateurs ;

\* les pannes ;

\* les incidents informatiques.



\## Contraintes de délai



Le projet doit être planifié et suivi à l'aide d'un outil de gestion de projet.



\## Contraintes budgétaires



Les solutions open source pourront être privilégiées lorsque leur utilisation est techniquement pertinente.



Le choix d'une solution devra cependant prendre en compte :



\* le coût ;

\* la sécurité ;

\* la maintenance ;

\* les compétences nécessaires ;

\* l'évolutivité.



\---



\# 25. Méthode MoSCoW



| Priorité | Fonctionnalité                                          |

| -------- | ------------------------------------------------------- |

| MUST     | Infrastructure réseau                                   |

| MUST     | Gestion des utilisateurs                                |

| MUST     | Gestion des droits                                      |

| MUST     | Serveur de fichiers                                     |

| MUST     | Site vitrine                                            |

| MUST     | Application Web                                         |

| MUST     | Base de données                                         |

| MUST     | Gestion des tickets                                     |

| MUST     | Sauvegarde                                              |

| MUST     | Test de restauration                                    |

| MUST     | Supervision                                             |

| MUST     | Tests de validation                                     |

| SHOULD   | DMZ                                                     |

| SHOULD   | Notification externe                                    |

| SHOULD   | Documentation utilisateur                               |

| SHOULD   | Indicateurs                                             |

| COULD    | MFA                                                     |

| COULD    | SIEM                                                    |

| COULD    | EDR                                                     |

| COULD    | Redondance avancée                                      |

| WON'T    | Haute disponibilité complète dans la maquette étudiante |

| WON'T    | Véritable système bancaire                              |

| WON'T    | Gestion de paiements réels                              |



\---



\# 26. Critères de validation



Le projet sera considéré comme fonctionnel lorsque les éléments principaux auront été :



\* configurés ;

\* testés ;

\* documentés ;

\* validés.



Les tests devront notamment vérifier :



\* l'authentification ;

\* le réseau ;

\* les VLAN ;

\* les droits ;

\* les services ;

\* l'application ;

\* la base de données ;

\* les tickets ;

\* la supervision ;

\* la sauvegarde ;

\* la restauration.



Les résultats devront être conservés comme preuves du projet.



\---



\# 27. Livrables



Les principaux livrables sont :



\* cahier des charges ;

\* architecture du système d'information ;

\* schéma réseau ;

\* plan d'adressage ;

\* plan VLAN ;

\* inventaire des ressources ;

\* tableau des serveurs ;

\* architecture Active Directory ;

\* matrice des droits ;

\* MCD ;

\* modèle relationnel ;

\* documentation de l'application ;

\* documentation GLPI ;

\* documentation supervision ;

\* stratégie de sauvegarde ;

\* procédure de restauration ;

\* plan de tests ;

\* procédures techniques ;

\* documentation utilisateur ;

\* planning ;

\* preuves de réalisation ;

\* scénario de démonstration ;

\* support de soutenance.



\---



\# 28. Évolutions possibles



À moyen terme, Banque NOVA pourrait faire évoluer son infrastructure avec :



\* un second contrôleur de domaine ;

\* de la redondance ;

\* du stockage redondant ;

\* une authentification multifacteur ;

\* un VPN renforcé ;

\* un SIEM ;

\* un EDR ;

\* une supervision plus avancée ;

\* un PRA complet.



Ces éléments sont considérés comme des évolutions et ne seront pas présentés comme réalisés sans preuve.



\---



\# 29. Statut du projet



Le présent cahier des charges décrit la solution cible et les travaux prévus.



Les éléments effectivement réalisés seront distingués des éléments :



\* prévus ;

\* en cours ;

\* à tester ;

\* validés.



Aucune réalisation technique ne sera déclarée comme terminée sans preuve correspondante.




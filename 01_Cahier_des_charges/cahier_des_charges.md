\# CAHIER DES CHARGES — BANQUE NOVA



\## Projet BTS SIO — Option SISR



\---



\# 1. Présentation du projet



\## 1.1 Nom du projet



\*\*Banque NOVA — Conception et sécurisation du système d'information\*\*



\## 1.2 Nature du projet



Banque NOVA est une banque fictive destinée aux particuliers et aux professionnels.



L'entreprise compte 25 collaborateurs répartis dans plusieurs services.



Le projet consiste à concevoir et mettre en place une infrastructure informatique permettant aux collaborateurs d'utiliser les ressources du système d'information dans un environnement sécurisé, centralisé et administrable.



Le projet est réalisé dans le cadre du BTS SIO, option SISR.



Aucune donnée bancaire réelle ne sera utilisée.



\---



\# 2. Problématique



> \*\*Comment Banque NOVA peut-elle mettre en place un système d'information sécurisé, centralisé et disponible permettant à ses 25 collaborateurs d'accéder efficacement aux ressources de l'entreprise tout en protégeant les données sensibles de ses clients ?\*\*



Cette problématique constitue le fil conducteur du projet.



Les choix techniques devront répondre aux besoins identifiés et être justifiés par rapport au contexte de l'entreprise.



\---



\# 3. Contexte



Banque NOVA souhaite disposer d'un système d'information permettant à ses collaborateurs de travailler efficacement tout en assurant la confidentialité, l'intégrité et la disponibilité des ressources informatiques.



L'entreprise dispose de plusieurs services ayant des besoins et des niveaux d'accès différents.



Les principales problématiques identifiées sont :



\- la centralisation des comptes utilisateurs ;

\- la gestion des droits d'accès ;

\- la segmentation du réseau ;

\- la protection des serveurs ;

\- la sécurisation des communications ;

\- la disponibilité des services ;

\- la gestion des incidents ;

\- la supervision de l'infrastructure ;

\- la sauvegarde des données ;

\- la restauration après incident ;

\- la documentation de l'infrastructure.



\---



\# 4. Organisation de l'entreprise



Banque NOVA compte 25 collaborateurs répartis entre les services suivants :



| Service | Nombre approximatif | Besoins principaux |

|---|---:|---|

| Direction | 2 | Accès aux ressources de direction |

| Accueil | 3 | Ressources communes et outils internes |

| Conseillers | 8 | Applications métier et ressources communes |

| Administration | 3 | Documents administratifs |

| Comptabilité | 3 | Ressources comptables |

| Ressources humaines | 2 | Données RH |

| Informatique | 2 | Administration du SI |

| Sécurité | 2 | Suivi et contrôle de la sécurité |

| \*\*Total\*\* | \*\*25\*\* | |



Les données et ressources accessibles varient selon le service de chaque utilisateur.



\---



\# 5. Objectifs du projet



\## 5.1 Objectif principal



Mettre en place un système d'information sécurisé, centralisé, administrable et adapté aux besoins de 25 collaborateurs.



\## 5.2 Objectifs techniques



Le projet devra permettre de :



\- segmenter le réseau à l'aide de VLAN ;

\- mettre en place un plan d'adressage IP cohérent ;

\- centraliser les utilisateurs avec Active Directory ;

\- mettre en place DNS ;

\- mettre en place DHCP ;

\- mettre en place un serveur de fichiers ;

\- contrôler les communications réseau ;

\- mettre en place un pare-feu ;

\- isoler les services publics dans une DMZ ;

\- déployer des services applicatifs ;

\- mettre en place une base de données ;

\- proposer une solution de gestion des tickets ;

\- superviser l'infrastructure ;

\- mettre en place une stratégie de sauvegarde ;

\- tester la restauration des données ;

\- documenter les procédures techniques et utilisateurs.



\---



\# 6. Besoins fonctionnels



Le système d'information doit permettre :



\### Gestion des utilisateurs



\- création des comptes ;

\- authentification ;

\- gestion des groupes ;

\- gestion des droits ;

\- modification et désactivation des comptes.



\### Gestion des ressources



\- accès aux partages réseau ;

\- accès aux applications ;

\- accès aux ressources selon le service ;

\- protection des données sensibles.



\### Gestion du réseau



\- communication entre les différents équipements ;

\- accès à Internet ;

\- segmentation des utilisateurs ;

\- isolation du réseau invité ;

\- accès contrôlé aux serveurs.



\### Support informatique



Les utilisateurs doivent pouvoir déclarer leurs incidents et demandes.



Les demandes doivent pouvoir être :



\- collectées ;

\- suivies ;

\- affectées ;

\- traitées ;

\- clôturées.



\### Supervision



L'infrastructure doit pouvoir être surveillée afin d'identifier :



\- les indisponibilités ;

\- les problèmes de ressources ;

\- les problèmes réseau ;

\- les services arrêtés.



\### Sauvegarde



Les données importantes doivent être sauvegardées.



Une procédure de restauration doit être prévue et testée.



\---



\# 7. Besoins non fonctionnels



Le système doit respecter plusieurs exigences.



\## Sécurité



Les ressources doivent être protégées contre les accès non autorisés.



\## Disponibilité



Les services essentiels doivent pouvoir être rétablis après un incident.



\## Confidentialité



Les utilisateurs ne doivent accéder qu'aux données nécessaires à leurs fonctions.



\## Intégrité



Les données doivent être protégées contre les modifications non autorisées.



\## Évolutivité



L'infrastructure doit pouvoir évoluer avec l'entreprise.



\## Maintenabilité



Les configurations et procédures doivent être documentées afin de faciliter l'administration.



\---



\# 8. Architecture générale prévue



L'infrastructure reposera principalement sur une architecture virtualisée.



Les principaux composants prévus sont :



\- pare-feu ;

\- routeur ;

\- switch cœur ;

\- switches d'accès ;

\- réseau utilisateurs ;

\- réseau serveurs ;

\- DMZ ;

\- serveurs virtualisés ;

\- postes clients.



Les différents services seront séparés logiquement grâce aux VLAN.



\---



\# 9. Principaux services prévus



| Service | Fonction |

|---|---|

| Active Directory | Gestion centralisée des utilisateurs et ordinateurs |

| DNS | Résolution des noms |

| DHCP | Attribution automatique des adresses IP |

| Serveur de fichiers | Stockage et partage des documents |

| GLPI | Gestion des tickets et du support |

| Zabbix | Supervision |

| Serveur Web | Hébergement du site public |

| Serveur BDD | Stockage des données applicatives |

| Serveur Application | Hébergement de NOVA SUPPORT |

| Pare-feu | Filtrage et sécurisation des flux |



\---



\# 10. Sécurité réseau



La sécurité reposera notamment sur :



\- segmentation par VLAN ;

\- pare-feu ;

\- DMZ ;

\- filtrage des flux ;

\- contrôle des droits ;

\- Active Directory ;

\- politiques de sécurité ;

\- HTTPS ;

\- supervision ;

\- sauvegardes ;

\- mises à jour ;

\- sensibilisation des utilisateurs.



Le principe du moindre privilège sera appliqué.



\---



\# 11. Gestion des droits



Les droits d'accès seront définis selon :



\- le service ;

\- la fonction de l'utilisateur ;

\- les ressources nécessaires ;

\- le niveau de sensibilité des données.



Les permissions seront principalement gérées à l'aide de groupes afin de simplifier l'administration.



\---



\# 12. Application NOVA SUPPORT



Une application interne appelée \*\*NOVA SUPPORT\*\* est prévue.



Elle permettra aux collaborateurs de déclarer leurs incidents informatiques.



Fonctionnalités prévues :



\- authentification ;

\- création d'un ticket ;

\- description du problème ;

\- catégorie ;

\- priorité ;

\- statut ;

\- affectation ;

\- commentaires ;

\- historique ;

\- clôture.



L'application sera reliée à une base de données.



Elle pourra également communiquer avec un service externe afin de transmettre des notifications.



\---



\# 13. Gestion des incidents



La gestion des incidents s'appuiera sur les principes ITIL.



Le cycle prévu est :



\*\*Déclaration → Qualification → Affectation → Diagnostic → Résolution → Vérification → Clôture\*\*



GLPI pourra être utilisé comme outil de gestion du support.



\---



\# 14. Supervision



Une solution de supervision sera mise en place afin de surveiller notamment :



\- disponibilité des serveurs ;

\- CPU ;

\- mémoire ;

\- espace disque ;

\- interfaces réseau ;

\- services ;

\- équipements réseau.



Zabbix est retenu comme solution de supervision prévue.



\---



\# 15. Sauvegarde



Une stratégie de sauvegarde sera définie afin de protéger les données et configurations importantes.



Elle devra préciser :



\- les données sauvegardées ;

\- la fréquence ;

\- la durée de conservation ;

\- la destination ;

\- le contrôle des sauvegardes ;

\- la procédure de restauration.



Un test de restauration devra être réalisé et documenté.



\---



\# 16. Tests



Les principaux services devront être testés avant leur validation.



Les tests porteront notamment sur :



\- Active Directory ;

\- DNS ;

\- DHCP ;

\- VLAN ;

\- routage ;

\- pare-feu ;

\- accès Internet ;

\- accès aux serveurs ;

\- permissions ;

\- application ;

\- base de données ;

\- GLPI ;

\- supervision ;

\- sauvegarde ;

\- restauration.



Les résultats réels seront renseignés après réalisation des tests.



\---



\# 17. Planning prévisionnel



Le projet est prévu sur une période d'environ un mois.



\### Semaine 1



\- analyse ;

\- cahier des charges ;

\- architecture ;

\- plan IP ;

\- VLAN.



\### Semaine 2



\- infrastructure ;

\- virtualisation ;

\- Active Directory ;

\- DNS ;

\- DHCP ;

\- serveur de fichiers.



\### Semaine 3



\- sécurité ;

\- pare-feu ;

\- DMZ ;

\- application ;

\- base de données ;

\- GLPI.



\### Semaine 4



\- supervision ;

\- sauvegardes ;

\- restauration ;

\- tests ;

\- documentation ;

\- préparation de la soutenance.



\---



\# 18. Livrables



Les principaux livrables seront :



\- cahier des charges ;

\- architecture du système d'information ;

\- schéma réseau ;

\- plan d'adressage IP ;

\- plan VLAN ;

\- documentation des serveurs ;

\- configuration réseau ;

\- documentation Active Directory ;

\- matrice des droits ;

\- documentation sécurité ;

\- application NOVA SUPPORT ;

\- modèle de base de données ;

\- documentation GLPI ;

\- supervision ;

\- stratégie de sauvegarde ;

\- procédures de restauration ;

\- plan de tests ;

\- procédures techniques ;

\- planning ;

\- documentation utilisateur ;

\- support de soutenance.



\---



\# 19. Contraintes



Le projet doit :



\- rester réalisable par un étudiant de deuxième année BTS SIO SISR ;

\- rester cohérent avec une entreprise de 25 collaborateurs ;

\- privilégier des solutions réalistes ;

\- ne pas utiliser de données bancaires réelles ;

\- distinguer les éléments prévus des éléments réellement réalisés ;

\- documenter les choix techniques ;

\- permettre la démonstration des principaux services.



\---



\# 20. Limites et évolutions



Certaines fonctionnalités pourront être considérées comme des évolutions futures :



\- second contrôleur de domaine ;

\- haute disponibilité ;

\- stockage redondant ;

\- MFA ;

\- EDR ;

\- SIEM ;

\- PRA complet ;

\- réplication ;

\- infrastructure redondante.



Ces éléments ne seront pas présentés comme réalisés s'ils ne sont pas effectivement mis en œuvre.



\---



\# 21. Critères de réussite



Le projet sera considéré comme fonctionnel lorsque les principaux services auront été :



1\. installés ;

2\. configurés ;

3\. sécurisés ;

4\. testés ;

5\. documentés.



Les résultats des tests seront ajoutés au dossier au fur et à mesure de la réalisation du projet.



\---



\# 22. État du projet



| Élément | État |

|---|---|

| Cahier des charges | En cours |

| Architecture réseau | En cours |

| Packet Tracer | En cours |

| Plan IP | À finaliser |

| VLAN | À finaliser |

| Serveurs | Prévu |

| Active Directory | Prévu |

| Sécurité | Prévu |

| Application | Prévu |

| GLPI | Prévu |

| Supervision | Prévu |

| Sauvegarde | Prévu |

| Tests | À réaliser |

| Documentation | En cours |

| Soutenance | À préparer |


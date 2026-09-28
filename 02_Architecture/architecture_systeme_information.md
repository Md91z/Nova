\# ARCHITECTURE DU SYSTÈME D'INFORMATION — BANQUE NOVA



\## 1. Présentation



L'architecture du système d'information de Banque NOVA est conçue pour répondre aux besoins de 25 collaborateurs répartis dans plusieurs services.



L'objectif est de fournir une infrastructure :



\- centralisée ;

\- segmentée ;

\- sécurisée ;

\- administrable ;

\- évolutive ;

\- adaptée à une organisation de 25 collaborateurs.



L'architecture est conçue autour d'un réseau local segmenté par VLAN et d'une infrastructure serveur permettant de centraliser les principaux services informatiques.



\---



\# 2. Architecture générale



L'architecture générale peut être représentée de la manière suivante :



```text

&#x20;                        INTERNET

&#x20;                           │

&#x20;                           │

&#x20;                      \[ Routeur ]

&#x20;                           │

&#x20;                           │

&#x20;                      \[ Pare-feu ]

&#x20;                           │

&#x20;                           │

&#x20;                   \[ Switch principal ]

&#x20;                           │

&#x20;            ┌──────────┼──────────┐

&#x20;            │              │              │

&#x20;         VLAN 10        VLAN 20        VLAN 30

&#x20;        Direction      Conseillers    Administration

&#x20;            │              │              │

&#x20;          PC              PC              PC

&#x20;            │              │              │

&#x20;            └──────────┼──────────┘

&#x20;                           │

&#x20;                      VLAN Serveurs

&#x20;                           │

&#x20;         ┌────────────┼ ────────────┐

&#x20;         │                 │                 │

&#x20;      Serveur AD        Serveur Web       Serveur BDD

&#x20;      DNS / DHCP       Application       Base de données

&#x20;         │                 │                 │

&#x20;         └────────────┼─────────────┘

&#x20;                           │

&#x20;                      Infrastructure

&#x20;                        de support

&#x20;                           │

&#x20;                 ┌──────┴───────┐

&#x20;                 │                   │

&#x20;               GLPI                Zabbix


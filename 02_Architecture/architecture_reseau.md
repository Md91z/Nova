\# ARCHITECTURE RÉSEAU — BANQUE NOVA



\## 1. Objectif



L'objectif de l'architecture réseau est de fournir une infrastructure segmentée permettant de séparer les différents services de Banque NOVA.



La segmentation doit permettre de contrôler les communications entre les utilisateurs, les serveurs et les équipements d'administration.



\---



\# 2. Principe de fonctionnement



Le réseau repose sur plusieurs VLAN.



Chaque VLAN constitue un réseau logique indépendant.



Les communications entre VLAN nécessitent un équipement de couche 3 ou un mécanisme de routage inter-VLAN.



Le pare-feu permet de contrôler les communications entre les différentes zones.



\---



\# 3. VLAN prévus



| VLAN | Nom | Réseau prévu | Passerelle prévue |

|---:|---|---|---|

| 10 | Direction | 192.168.10.0/24 | 192.168.10.1 |

| 20 | Conseillers | 192.168.20.0/24 | 192.168.20.1 |

| 30 | Administration | 192.168.30.0/24 | 192.168.30.1 |

| 40 | Comptabilité | 192.168.40.0/24 | 192.168.40.1 |

| 50 | RH | 192.168.50.0/24 | 192.168.50.1 |

| 60 | Informatique | 192.168.60.0/24 | 192.168.60.1 |

| 70 | Serveurs | 192.168.70.0/24 | 192.168.70.1 |

| 80 | Invités | 192.168.80.0/24 | 192.168.80.1 |

| 90 | Management | 192.168.90.0/24 | 192.168.90.1 |



> Ces informations devront être vérifiées et adaptées à la configuration réellement présente dans Packet Tracer.



\---



\# 4. Ports Access



Les ports connectés directement aux postes utilisateurs sont configurés en mode access.



Exemple :



```text

PC Direction

&#x20;    │

&#x20;    │

&#x20;  Access

&#x20;    │

VLAN 10


\# 1. Architecture du système d'information



\## 1.1 Vue générale



L'architecture du système d'information de Banque NOVA est conçue pour répondre aux besoins d'une organisation de 25 collaborateurs.



Elle repose sur plusieurs niveaux :



\- accès Internet ;

\- pare-feu ;

\- réseau interne ;

\- segmentation par VLAN ;

\- serveurs ;

\- postes utilisateurs ;

\- zone DMZ ;

\- services de supervision et de sauvegarde.



\## 1.2 Architecture logique



```text

&#x20;                        INTERNET

&#x20;                           |

&#x20;                           |

&#x20;                      \[ pfSense ]

&#x20;                      /         \\

&#x20;                     /           \\

&#x20;                  DMZ             LAN

&#x20;                   |               |

&#x20;             \[Serveur Web]      \[Switch]

&#x20;             \[NOVA SUPPORT]        |

&#x20;                                   |

&#x20;             +---------------------+----------------------+

&#x20;             |          |          |          |           |

&#x20;         VLAN 10     VLAN 20     VLAN 30    VLAN 40    VLAN 50

&#x20;         Direction   Conseillers Administration Comptabilité RH



&#x20;                                   |

&#x20;                             VLAN 60 - IT

&#x20;                                   |

&#x20;                             Administration



&#x20;                                   |

&#x20;                             VLAN 70 - Serveurs

&#x20;                                   |

&#x20;                 +-----------------+----------------+

&#x20;                 |                 |                |

&#x20;                AD/DNS/DHCP     Fichiers          GLPI

&#x20;                 |                                  |

&#x20;                 |                               Zabbix

&#x20;                 |

&#x20;               BDD


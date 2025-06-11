# Wireshark
Analyse de protocoles réseau avec Wireshark - capture de paquets, examen du modèle OSI, et documentation du handshake TCP avec captures d'écran détaillées.

## Analyse Réseau Wireshark

## Description

Analyse de protocoles réseau avec Wireshark - capture de paquets, examen du modèle OSI, et documentation du handshake TCP avec captures d'écran détaillées.

Ce projet documente l'analyse de protocoles réseau avec Wireshark, incluant la capture de paquets DNS, ARP, TCP et l'analyse des couches du modèle OSI.

## Contenu

### Protocoles analysés
- **DNS** - Résolution de noms de domaine
- **ARP** - Résolution d'adresses MAC
- **TCP** - Handshake et connexions
- **HTTP/HTTPS** - Trafic web

### Analyses réalisées
- Capture de paquets en temps réel
- Identification des couches OSI
- Analyse du handshake TCP (SYN, SYN-ACK, ACK)
- Interprétation des données hexadécimales
- Filtrage du trafic réseau

## Outils utilisés

- **Wireshark** - Analyseur de protocoles
- **VMware** - Environnement de test
- Filtres réseau pour isolation du trafic

## Structure des fichiers

```
├── Guide-Analyse-Wireshark.md    # Document principal
├── README.md                     # Ce fichier
└── captures/                     # Captures d'écran
    ├── interface-wireshark.png
    ├── paquets-dns.png
    ├── handshake-tcp.png
    └── analyse-osi.png
```

## Résultats principaux

### Handshake TCP
1. **SYN** - Demande de connexion
2. **SYN-ACK** - Réponse du serveur  
3. **ACK** - Confirmation du client

### Protocoles identifiés
| Protocol | Port | Description |
|----------|------|-------------|
| DNS | 53 | Résolution de noms |
| HTTP | 80 | Navigation web |
| HTTPS | 443 | Navigation sécurisée |

## Utilisation

1. Cloner le repository
2. Ouvrir le fichier `Guide-Analyse-Wireshark.md`
3. Consulter les captures d'écran
4. Reproduire les analyses avec Wireshark

## Notes

- Projet éducatif sur l'analyse réseau
- Utilisation éthique de Wireshark requise
- Respect des politiques de confidentialité




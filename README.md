# Wazuh Custom Rules

> Regles SIEM Wazuh personnalisees pour environnements Linux et reseaux africains.

![Wazuh](https://img.shields.io/badge/Wazuh-4.7-005571?style=flat-square)
![Author](https://img.shields.io/badge/Author-ibramoha2-CC0000?style=flat-square)

## Installation
```bash
cp rules/*.xml /var/ossec/etc/rules/
systemctl restart wazuh-manager
```

## Regles disponibles

| Fichier | Description |
|---------|-------------|
| `ssh_rules.xml` | Detection brute-force SSH et connexions suspectes |
| `integrity_rules.xml` | Surveillance intégrité fichiers systeme |
| `privilege_rules.xml` | Detection escalade de privileges |
| `network_rules.xml` | Anomalies reseau (scans, exfiltration) |

**Auteur :** [@ibramoha2](https://github.com/ibramoha2) | Niger
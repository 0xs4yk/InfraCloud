
# Exercice : Calcul des coûts d’une Infrastructure as a Service

MAXENCE LANCOSME M2 INFRA CLOUD

---
## Coûts des services Cloud pour différents providers

### Infrastructure n°1
- **Serveurs** : 1 serveur
  - **RAM** : 16 Go
  - **vCPU** : 4
  - **Stockage disque** : 100 Go

| Cloud Provider | Coût estimé ($USD) |
|----------------|---------------------|
| AWS            | $116,26             |
| GCP            | $100,20             |
| OVH            | $55,40              |

---

### Infrastructure n°2
- **Serveurs** : 6 serveurs
  - **RAM** : 6 Go
  - **vCPU** : 3
  - **Stockage disque** : 20 Go par serveur
  - **Particularité** : 3 serveurs éteints la nuit de 22h à 6h

| Cloud Provider | Coût estimé ($USD) |
|----------------|---------------------|
| AWS            | $587,32             |
| GCP            | $447,64             |
| OVH            | $551,52             |

---

### Infrastructure n°3
- **Serveurs** : 3 serveurs
  - **RAM** : 4 Go
  - **vCPU** : 2
  - **Stockage disque** : 50 Go par serveur
- **Load balancer** : 1 load balancer (5 Mb/s de données)
- **Base de données managée** :
  - **RAM** : 8 Go
  - **vCPU** : 2
  - **Stockage disque** : 10 Go

| Cloud Provider | Coût estimé ($USD) |
|----------------|---------------------|
| AWS            | $446,82             |
| GCP            | $281,00             |
| OVH            | $214,29             |

---

## Comparaison des résultats finaux pour chaque infra
| Cloud Provider | Infrastructure n°1 | Infrastructure n°2 | Infrastructure n°3 | Coût Total ($USD) |
|----------------|---------------------|---------------------|---------------------|---------------------|
| AWS            | $116,26             | $587,32             | $446,82             | $1,150.40           |
| GCP            | $100,20             | $447,64             | $281,00             | $828.84             |
| OVH            | $55,40              | $551,52             | $214,29             | $821.21             |
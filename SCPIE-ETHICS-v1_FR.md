#  Engagements éthiques – Projets SCPIE / OSINT


## 1. Sensibilisation au double usage  
Chaque modèle, capteur ou pipeline OSINT publié comporte un paragraphe dédié aux risques d’usage abusif, notamment dans des contextes industriels ou de surveillance.

## 2. Minimisation des données  
Je ne collecte que des données ouvertes ou légalement accessibles. Aucune donnée à caractère personnel sans consentement explicite.

## 3. Transparence par défaut  
Tous les artefacts non sensibles (code, jeux de données, tableaux de bord) sont publiés sous licence MIT ou CC-BY-SA dans un délai de 30 jours.

## 4. Divulgation responsable  
Toute vulnérabilité détectée dans un système OT/IT est d’abord signalée en privé. La publication publique intervient après 90 jours, sauf correction anticipée.

## 5. Signalements sécurisés  
Pour m'envoyer des informations sensibles de manière anonyme :  
1. Chiffre ton message avec ma clé PGP publique :  
   [📎 Télécharger](https://raw.githubusercontent.com/AtomicForesight/-SCPIE-roadmap/main/docs/scpie_pubkey.asc) )

| 🇬🇧 English | [SCPIE-ETHICS-v1_EN.md](./SCPIE-ETHICS-v1_EN.md) |

### 🔐 Contact sécurisé PGP  
**Pour des communications chiffrées :**  

1. **Télécharge ma clé publique** :  
   → [📎 scpie_pubkey.asc](https://github.com/AtomicForesight/SCPIE-roadmap/raw/main/docs/scpie_pubkey.asc)  

2. **Importe et chiffre** :  
   ```bash
   # 1. Importe ma clé
   curl -L https://github.com/tonpseudo/SCPIE-roadmap/raw/main/docs/scpie_pubkey.asc | gpg --import
   
   # 2. Chiffre ton fichier
   gpg --encrypt --recipient "Dimitri Arnoult (SCPIE)" --output rapport.asc rapport.pdf

# 📦 APK Distribution – CampusBiotechDigital

Ce dépôt est utilisé pour la **distribution publique** d'applications Android (.apk) dans le cadre des projets de réalité virtuelle développés par Campus Biotech Digital.

## 🎯 Objectif

Ce dépôt permet de :

- Fournir un lien stable et public vers les `.apk` nécessaires à l'installation sur les casques Meta Quest via **Meta Managed Services for Education (MMSE)**.
- Centraliser les différentes versions publiées (via [Releases](https://github.com/CampusBiotechDigital/apk-distribution/releases)) pour une gestion simple et sécurisée.

## 🔐 À propos des APKs

Les fichiers `.apk` publiés ici sont compilés et signés pour la production.  
Aucun code source ou élément sensible n’est exposé dans ce dépôt.

Pour des raisons de sécurité :
- Aucun fichier `.apk` ne contient de clés d’API ou secrets embarqués
- Tous les builds sont obfusqués avec ProGuard/R8

## 🚀 Comment utiliser un APK dans MMSE

1. Allez dans la section **Releases** du dépôt
2. Copiez le lien direct vers le fichier `.apk`
3. Collez ce lien dans la console d’administration MMSE lors de l’ajout d’une application personnalisée

Exemple de lien :
https://github.com/CampusBiotechDigital/apk-distribution/releases/download/v1.0.0/monapp.apk

---

## 📂 Structure des releases

Chaque release contient :
- Un fichier `.apk` nommé clairement (`NomApp_Version.apk`)
- Un changelog décrivant les nouveautés ou corrections
- Un tag de version (`v1.0.0`, `v1.1.0`, etc.)

---

## 👨‍🔧 Mainteneur

Gilles Montenach – [Campus Biotech Digital](https://campusbiotechdigital.ch)

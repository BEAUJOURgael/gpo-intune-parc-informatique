# gpo-intune-parc-informatique
# 💼 Gestion de Parc Informatique avec Windows Server 2016 & Microsoft Intune

## 🧠 Description du projet
Ce projet présente la mise en place de **stratégies de groupe (GPO)** sur **Windows Server 2016**, puis leur **exportation vers Microsoft Intune** afin de centraliser la gestion d’un parc informatique.  
L’objectif était d’unifier la sécurité, les configurations système et les mises à jour des postes utilisateurs.

---

## 🎯 Objectifs
- Centraliser la gestion des postes à distance  
- Appliquer automatiquement les politiques système (GPO)  
- Déployer des configurations standardisées via Microsoft Intune  
- Assurer la sécurité et la conformité du parc

---

## 🧰 Outils et technologies
- 🪟 **Windows Server 2016**
- 🧩 **Active Directory**
- ⚙️ **GPO (Group Policy Objects)**
- ☁️ **Microsoft Intune**
- 💻 **PowerShell**
- 🔐 **Gestion de parc informatique**

---

## 🔍 Étapes réalisées
1. Création d’un domaine Active Directory sous Windows Server 2016  
2. Mise en place et test de plusieurs stratégies de groupe (GPO)  
3. Exportation des GPO au format `.xml` / `.pol`  
4. Importation et adaptation sous **Microsoft Intune**  
5. Déploiement et supervision des politiques sur plusieurs postes clients  

---

## 🧩 Résultat
✅ Un environnement **hybride Active Directory + Intune** permettant de :  
- Gérer les postes à distance  
- Appliquer automatiquement les règles de sécurité  
- Simplifier le support utilisateur et la maintenance


# 🛡️ Assistant IAM - Tableau de bord sécurité & audit intelligent

![Version](https://img.shields.io/badge/version-1.0-blue)
![Statut](https://img.shields.io/badge/statut-POC-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

> **🔗 Lien de démonstration :** [comfy-dolphin-f7f41d-maeatech.netlify.app](https://comfy-dolphin-f7f41d-maeatech.netlify.app)

## 📋 À propos

Ce **Proof of Concept (POC)** démontre la faisabilité d'un outil centralisé de supervision IAM (Identity & Access Management) enrichi par l'intelligence artificielle. Il permet aux équipes sécurité et IT de :

- 📊 **Visualiser** en temps réel le niveau de risque des comptes utilisateurs
- 🚨 **Détecter** les comportements anormaux (impossible travel, exfiltration, horaires suspect)
- 🎯 **Prioriser** les actions de remédiation avec un plan d'action P1/P2/P3
- 🤖 **Interagir** avec un assistant IA pour des analyses contextuelles
- 📄 **Générer** des rapports d'audit structurés

## ✨ Fonctionnalités

| Module | Description |
|--------|-------------|
| **Vue globale** | KPIs temps réel, distribution des scores, évolution 30 jours |
| **Comptes & risques** | Analyse détaillée par utilisateur (score, permissions, anomalies) |
| **Timeline** | Chronologie des événements de sécurité sur 7 jours |
| **Remédiation** | Plan d'action priorisé avec propriétaires et délais |
| **Analyste IA** | Chat contextualisé pour l'investigation |
| **Rapport d'audit** | Génération automatique de rapports structurés |

## 🎯 Cas d'usage simulés

| Utilisateur | Rôle | Score | Risque | Anomalies détectées |
|-------------|------|-------|--------|---------------------|
| Alice Dupont | Admin Systèmes | 88 | Critique | MFA absent, impossible travel, actions nocturnes |
| Claire Lambert | RH (départ J-5) | 92 | Critique | Exfiltration de 4200 dossiers, Dropboat |
| Marc Keller | Dev Backend | 61 | Élevé | Push prod sans PR, API key partagée |
| Sarah Leroy | Analyste BI | 22 | Faible | Connexion hors horaire (normale) |
| Pierre Dumas | Comptabilité | 9 | Minimal | Aucune anomalie |

## 🏗️ Architecture technique

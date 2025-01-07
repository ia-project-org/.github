# 🏦 Banking Credit Eligibility System 

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Keycloak](https://img.shields.io/badge/Keycloak-7B1FA2?style=for-the-badge&logo=keycloak&logoColor=white)](https://www.keycloak.org/)

## 📋 Description

Application web innovante pour l'évaluation automatisée de l'éligibilité aux crédits bancaires, combinant intelligence artificielle et analyse financière pour des décisions plus précises et personnalisées.

## 🎯 Objectifs du Projet

- 🤖 **Automatisation Intelligente**: Évaluation automatique de l'éligibilité au crédit via machine learning
- 🛡️ **Gestion des Risques**: Minimisation des risques financiers grâce à une analyse approfondie
- 💡 **Recommandations Personnalisées**: Suggestions adaptées aux profils clients
- 🎯 **Efficacité Opérationnelle**: Interface intuitive pour les agents bancaires
- 📊 **Analyse Complète**: Intégration des indicateurs financiers clés

## 🔧 Technologies Utilisées

### Backend
- 🍃 **Spring Boot**: Framework principal pour les microservices
- 🐍 **Python/Django**: Traitement des données et modèles ML
- 🔄 **Spring Batch**: Traitement des données par lots
- 🔐 **Keycloak**: Gestion de l'authentification et autorisation

### Frontend
- ⚛️ **React**: Interface utilisateur moderne et responsive
- 🎨 **Material-UI**: Composants UI élégants

### Architecture & Outils
- 🏗️ **Architecture Microservices**: Pour une meilleure scalabilité
- 📑 **Mindee**: Extraction intelligente de documents
- 🔍 **Eureka**: Découverte de services
- 🌐 **API Gateway**: Gestion centralisée des requêtes

## 🏗️ Architecture du Système

Notre système est basé sur une architecture microservices moderne comprenant:

- **API Gateway**: Point d'entrée centralisé
- **Service d'Éligibilité**: Évaluation des demandes de crédit
- **Service Bancaire**: Gestion des opérations bancaires
- **IAM Keycloak**: Gestion des identités et accès
- **Eureka Server**: Découverte de services
- **Configuration Externe**: Gestion centralisée des configurations

## 🚀 Installation et Démarrage

```bash
# Cloner le repository
git clone [url-du-repo]

# Backend (Spring Boot)
cd backend
mvn spring-boot:run

# Frontend (React)
cd frontend
npm install
npm start

# Services Keycloak
docker-compose up -d keycloak
```

## 💡 Fonctionnalités Principales

1. 📝 **Évaluation Automatique**
   - Analyse instantanée des profils clients
   - Scoring crédit automatisé
   - Vérification des critères d'éligibilité

2. 📊 **Tableaux de Bord**
   - Vue d'ensemble des demandes
   - Statistiques en temps réel
   - Suivi des performances

3. 🤝 **Recommandations**
   - Suggestions personnalisées
   - Alternatives de crédit
   - Conseils d'optimisation

## 👥 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à:

1. 🍴 Forker le projet
2. 🔧 Créer une branche pour votre fonctionnalité
3. 📝 Commiter vos changements
4. 🚀 Pusher vers la branche
5. 🔍 Ouvrir une Pull Request

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE.md](LICENSE.md) pour plus de détails.

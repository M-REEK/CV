---
title: "Parcours Professionnel"
date: 2025-12-24
draft: false
---

## Lead Developer & Solution Architect — RCF Notre Dame (64 Radios)
*Lyon | Depuis 2024*

**Rôle :** Responsable de l'architecture logicielle et de l'infrastructure de l'écosystème web (64 radios locales). Direction technique d'une équipe de 2 développeurs et référent sur les choix technologiques.

### 🏗️ Architecture Headless & Front-end (Nuxt 3/4)
* **Migration Framework :** Pilotage de la transition vers **Nuxt 3** (moteur Nitro). Travail actuel sur l'interopérabilité avec **Nuxt 4**.
* **Back office commun :** Pilotage des évolutions d'un back office **Drupal** commun aux 64 radios. 
* **Découplage API :** Evolution de l'**API** Drupal pour servir le site média. Evolutions d'un système de gestion de droits permettant l'étanchéité des contenus entre les 64 entités radios.
* **Optimisation des performances :** Gestion d'un trafic de **460 000 sessions/mois**. Optimisation du rendu (SSR) et configuration de **Nginx** (reverse proxy, cache, gestion des headers) sous Linux.
* **Productivité IA :** Intégration systématique de l'IA générative (**Gemini, ChatGPT, Mistral**) dans le work flow (sécurité, optimisation, performances), et de **GitHub Copilot** pour l'accélération du développement quotidien.

### ☁️ Ingénierie Cloud & Middleware CRM (Stack AWS)
Conception et maintenance d'un middleware serverless assurant la liaison entre différents services et le CRM propriétaire (gestion des donateurs et leads).

* **Pipeline Serverless :** Orchestration via **AWS CloudFormation** (Infrastructure as Code).
* **Flux de données :** Exposition des endpoints via **API Gateway**, logique métier traitée par **AWS Lambda** (Producer / Worker).
* **Résilience & Découplage :** Utilisation de files d'attente **AWS SQS** pour l'ingestion asynchrone des données. Ce choix technique garantit la persistance des données et l'absorption des pics de charge lors des campagnes nationales de dons, sans impacter les temps de réponse.
* **Sécurité & État :** Gestion des secrets via **AWS Secrets Manager** et stockage des états de synchronisation/logs dans **DynamoDB**.
* **DevOps :** Conteneurisation des services via **Docker** et gestion des enregistrements DNS (zones, alias, entrées TXT) pour l'ensemble du parc de domaines chez **OVH**.

---

## Développeur Fullstack — Union RCF
*Lyon | 2022 – 2024*

### Conception & Industrialisation
* **Outil métier "Programmation Radio" :** Développement complet d'une application interne permettant aux radios de partager et collaborer sur leurs grilles de programmes, leurs métadonnées.
* **Refonte Orientée Objet :** Migration du code legacy procédural vers une architecture **POO (PHP/Drupal)**. Mise en place de classes d'objets et de composants réutilisables.
* **Optimisation Database :** Structuration et requêtage complexe sous **MySQL**. (Apprentissage et veille active sur **PostgreSQL**).
* **API First :** Normalisation des flux pour garantir une consommation identique par le site média et les applications mobiles.
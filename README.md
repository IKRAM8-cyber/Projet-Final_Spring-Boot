**_APPLICATION DE GESTION DES COMPTES BANCAIRES BASEE SUR UN AGENT IA:**_ 

Ce projet consiste à développer une application complète de gestion des comptes bancaires, reposant sur une architecture Backend Spring Boot, un Frontend Angular, une sécurité basée sur Spring Security & JWT, et une extension intelligente via un Chatbot AI (RAG).

Chaque client peut posséder un ou plusieurs comptes bancaires, et chaque compte peut enregistrer plusieurs opérations bancaires de type DEBIT ou CREDIT.

Le projet suit une architecture moderne RESTful, sécurisée, modulaire et extensible.

**OBJECTIF DE PROJET  :**

Gérer les clients, comptes bancaires et opérations

Implémenter une API REST sécurisée

Développer une interface utilisateur Angular intuitive

Mettre en place un système d’authentification JWT

Ajouter un Chatbot AI intelligent pour l’assistance et l’analyse

 **TYPES DE **COMPTES** :**
Compte Courant (CurrentAccount)

Découvert autorisé (Overdraft)

Compte Épargne (SavingAccount)

Taux d’intérêt (Interest Rate)

**TYPES D'OPERATIONS:** 

 DEBIT

 CREDIT

**TECHNOLOGIES UTILISEES :** 
_-Backend_

* Java 17
* 
* Spring Boot 3
* 
* Spring Data JPA (Hibernate)
* 
* Spring Security
* 
* JWT (JSON Web Token)
* 
* Swagger / OpenAPI (springdoc)
* 
* H2 / MySQL

_-Frontend_

* Angular
* 
* Bootstrap
* 
* ChartJS (ng2-charts)
* 
* AI & Chatbot
* 
* OpenAI API
* 
* RAG (Retrieval Augmented Generation)
* Telegram Bot API

**ARCHITECTURE DU PROJET :**

* Frontend (screenshots/screen-frontend.png)
* Backend (screenshots/Screen-Bckend.png)

**Fonctionnalités Implémentées**

 **Backend :**

* Création du projet Spring Boot
* Entités JPA
* Repositories Spring Data JPA
* Tests DAO
* Couche Service & DTOs
* REST Controllers
* API RESTful testées
* Documentation Swagger

  **Sécurité :**

* Authentification avec Spring Security
* JWT Access Token & Refresh Token
* Gestion des rôles (ADMIN, USER)
* Protection des routes API
* Changement de mot de passe utilisateur
* Traçabilité des actions par utilisateur authentifié

**Frontend Angular**
**Gestion des clients :**

**Ajout**

* Modification
* 
* Suppression
* 
* Recherche

**Gestion des comptes :**

* Création de comptes
* 
* Consultation
* 
* Administration

**Gestion des opérations :**

* Débit / Crédit
* 
* Authentification sécurisée (JWT)
* 
* Dashboard avec graphiques (ChartJS)



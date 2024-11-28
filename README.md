# Vbil - Plateforme de Gestion de Facturation et de Suivi de Paiement

**Vbil** est une solution web complète et hautement sécurisée conçue pour automatiser la gestion de la facturation et du suivi des paiements. Cette plateforme vise à simplifier les processus administratifs complexes tout en fournissant des outils performants pour gérer les utilisateurs, les entreprises, les services, ainsi qu'un tableau de bord interactif et des notifications en temps réel pour garantir une gestion optimale des finances et des paiements.

## Présentation

**Vbil** offre une interface utilisateur intuitive et moderne, adaptée aux besoins des professionnels qui cherchent à automatiser la création de factures, à suivre le statut des paiements et à gérer les paramètres des entreprises de manière efficace.

---


## Aperçu de l'application

### Page d'accueil
Voici un aperçu de la **page d'accueil** de l'application, qui inclut l'interface de connexion et les principales sections accessibles aux utilisateurs.

![Page d'accueil](assets/vbill.png)

---

## Démonstration

Pour voir la démo en ligne de l'application, suivez ce lien vers la page LinkedIn associée à **Vbil** :

[Voir la démo de l'application sur LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7243907017386463232/)

---

## Fonctionnalités

### **Gestion des utilisateurs**
- **Inscription et authentification sécurisée** :
  - Authentification à deux facteurs (2FA) pour garantir une sécurité optimale des comptes.
  - Réinitialisation de mot de passe via e-mail pour une gestion facile et sécurisée des accès.
- **Gestion des profils utilisateurs** :
  - Permet la modification des informations personnelles.
  - Définition des rôles avec des permissions granulaire (administrateurs, utilisateurs).

### **Gestion des entreprises**
- Paramétrage des informations essentielles de l'entreprise : nom, adresse, TVA, timbre fiscal.
- Configuration des devises utilisées pour la facturation.

### **Gestion des services**
- Création, modification et suppression des services proposés avec catégorisation par type.
- Organisation simplifiée des services pour une meilleure gestion et suivi.

### **Facturation automatique**
- Génération automatique des factures incluant :
  - Calcul automatique de la TVA et des timbres fiscaux, selon les règles fiscales en vigueur.
  - Téléchargement facile des factures en format PDF pour une gestion administrative sans friction.

### **Suivi des paiements**
- **Gestion du statut des paiements** :
  - Suivi des paiements des factures, avec les statuts : "Payé", "En attente", "Partiellement payé".
  - Historique complet des paiements, pour une gestion financière transparente.
- **Notifications en temps réel** :
  - Alertes automatiques pour toute modification de statut de paiement afin d'assurer un suivi instantané.

### **Tableaux de bord interactifs**
- **Statistiques financières détaillées** :
  - Visualisation du nombre total de factures émises, de leur statut et de leur répartition par type.
- **Graphiques dynamiques** :
  - Graphiques interactifs pour suivre l'évolution des paiements, avec une distribution visuelle claire des statuts des factures.

### **Notifications**
- Envoi de notifications en temps réel directement dans l'application pour tenir les utilisateurs informés sur l'état des factures et des paiements.

---

## Technologies utilisées

**Vbil** repose sur une architecture moderne et sécurisée, combinant des technologies robustes pour garantir la performance et la sécurité de la plateforme.

- **Frontend** : Développé avec **ReactJS** et **Ant Design** pour offrir une interface utilisateur fluide et réactive.
- **Backend** : **NestJS** avec **MongoDB** pour une gestion des données optimale et une architecture scalable.
- **Authentification sécurisée** : **JWT** (JSON Web Token) pour l'authentification des utilisateurs et la gestion des sessions.
- **Envoi d'emails** : **NodeMailer** est utilisé pour l'envoi de mails de vérification de compte et de réinitialisation de mot de passe.
- **Graphiques interactifs** : **Chart.js** est utilisé pour générer des graphiques dynamiques dans le tableau de bord.
- **Sécurité** : L'application est protégée avec une authentification à deux facteurs (2FA) pour sécuriser les comptes des utilisateurs.

---


## Installation

### Prérequis
Avant de commencer, assurez-vous que vous avez installé **Node.js** et **npm** sur votre machine.

### Installation du Backend
1. Clonez le projet depuis le dépôt GitHub :
   ```bash
   git clone https://github.com/raniasouissi/Plateforme-de-gestion-de-facturation-et-de-suivi-de-paiement-VBIL.git


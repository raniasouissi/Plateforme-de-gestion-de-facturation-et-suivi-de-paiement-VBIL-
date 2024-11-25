# **Vbil - Plateforme de Gestion de Facturation et de Suivi de Paiement**

**Vbil** est une solution complète et intuitive pour automatiser la gestion de facturation et suivre les paiements efficacement. La plateforme est conçue pour simplifier les tâches administratives tout en offrant des outils performants, un tableau de bord interactif, et des notifications pour une gestion optimale.

---

## **Fonctionnalités principales**

### **Gestion des utilisateurs**
- **Inscription et authentification sécurisée** :
  - Authentification à deux facteurs (2FA).
  - Réinitialisation de mot de passe par e-mail.
- **Gestion de profil** :
  - Modification des informations personnelles.
  - Définition des rôles (administrateurs, utilisateurs).

### **Gestion des entreprises**
- Paramétrage des informations de l’entreprise : nom, adresse, TVA, timbre fiscal.
- Configuration des devises pour les factures.

### **Gestion des services**
- Ajout et modification des services offerts avec catégorisation.
- Organisation des services par type pour une gestion simplifiée.

### **Facturation automatique**
- Génération automatique des factures incluant :
  - TVA calculée automatiquement.
  - Application des timbres fiscaux selon la réglementation.
- Téléchargement des factures en format PDF.


### **Suivi des paiements**
- **Statut des paiements** :
  - Factures marquées comme "Payé", "En attente" ou "Partiellement payé".
  - Historique détaillé des paiements.
- Notifications automatiques intégrées pour :
  - Les rappels des paiements en retard.
  - Les changements de statut des paiements.
- Visualisation des transactions récentes.

### **Tableaux de bord interactifs**
- **Statistiques financières** :

  - Nombre de factures émises.
    
- **Graphiques dynamiques** :
  
  - Évolution des revenus.
  - Distribution des statuts des factures.

### **Notifications**
- Envoi de notifications directement dans l'application pour alerter les utilisateurs.
- Rappels automatiques pour les échéances importantes.

---

## **Technologies utilisées**
- **Frontend** : ReactJS avec Ant Design pour une interface utilisateur intuitive.
- **Backend** : NestJS et MongoDB pour la gestion des données.
- **Notifications** : NodeMailer pour l’envoi des e-mails.
- **Graphiques interactifs** : Chart.js pour les tableaux de bord.
- **Sécurité** : JWT pour l’authentification et le suivi des sessions.

---

## **Installation**

### **1. Cloner le dépôt**
```bash
git clone https://github.com/raniasouissi/-plateforme-de-gestion-de-facturation-et-suivi-de-paiement-VBIL-.git

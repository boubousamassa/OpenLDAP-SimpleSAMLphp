# TP – OpenLDAP et fédération d’identité avec SimpleSAMLphp

## Objectif du projet
Ce TP consiste à déployer un annuaire OpenLDAP et à mettre en place une fédération d’identité via SimpleSAMLphp.  
L’objectif est de centraliser l’authentification, structurer les utilisateurs dans LDAP et configurer un fournisseur d’identité (IdP) SAML connecté à l’annuaire.

---

## 🧱 Architecture du système
Le TP repose sur deux serveurs principaux :

### Serveur OpenLDAP
- Annuaire centralisé
- Arborescence d’organisation (OUs)
- Groupes et utilisateurs
- Authentification LDAP

### Serveur SimpleSAMLphp
- Fournisseur d’identité (IdP)
- Connexion à OpenLDAP
- Interface web d’authentification
- Tests SAML

---

## Fonctionnalités principales

###  Déploiement OpenLDAP
- Installation du serveur LDAP  
- Configuration du domaine LDAP  
- Création des OUs : People, Groups, Admins 
- Ajout d’utilisateurs et groupes  
- Tests d’authentification via ldapsearch  

###  Déploiement SimpleSAMLphp
- Installation de SimpleSAMLphp  
- Configuration de l’IdP  
- Connexion à OpenLDAP comme backend d’authentification  
- Configuration des attributs SAML  
- Accès à l’interface web d’administration  

###  Tests d’authentification
- Connexion via interface SimpleSAMLphp  
- Vérification des attributs renvoyés  
- Validation de la fédération d’identité  


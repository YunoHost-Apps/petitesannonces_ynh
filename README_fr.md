# PetitesAnnonces pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/petitesannonces.svg)](https://dash.yunohost.org/appci/app/petitesannonces)  
[![Installer petitesannonces avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=petitesannonces)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer PetitesAnnonces rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Grâce à cet outil, créer simplement et rapidement votre site de Petites Annonces.

Les fonctionnalités de cette outils sont :  
  * Affichage des annonces mises en ligne  
  * Tri selon la région, la catégorie et mot-clés  
  * Ajout/suppression d'annonces  
  * Possibilité d'envoyer un message à celui qui a déposé l'annonce  


**Version incluse:**  0.1.0~ynh2

## Captures d'écran

![demo](doc/demo.png)

<!-- 
## Démo

* [Démo officielle](Lien vers un site de démonstration de cette application) 
-->
## Configuration

Comment configurer cette application: via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle: https://framagit.org/anto1ne/petitesannonces  
 * Documentation YunoHost: Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

L'authentification LDAP et HTTP est-elle prise en charge? : Non   
L'application peut-elle être utilisée par plusieurs utilisateurs?  : Non  

#### Architectures supportées

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/petitesannonces%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/petitesannonces/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/petitesannonces%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/petitesannonces/)

## Limitations

* Limitations connues : jeune application en cours de développement.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application : RAS

**Plus d'informations sur la page de documentation:**  
https://yunohost.org/packaging_apps

## Liens

 * Signaler un bug: https://github.com/YunoHost-Apps/petitesannonces_ynh/issues
 * Site de l'application: https://framagit.org/anto1ne/petitesannonces
 * Dépôt de l'application principale: https://framagit.org/anto1ne/petitesannonces
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/petitesannonces_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/petitesannonces_ynh/tree/testing --debug
ou
sudo yunohost app upgrade petitesannonces -u https://github.com/YunoHost-Apps/petitesannonces_ynh/tree/testing --debug
```

---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 8a895d104abd20910aa37ec2ec3b6eeaccd8c461

---


# RÉVISION INTERNE - Notes de mise à jour d’Adobe Experience Cloud - janvier 2020

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

> [!NOTE] Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) pour être averti par e-mail de la publication des prochaines versions. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : Janvier 2020**

* [Interface d’Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (liens vers l’aide de la solution)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (liens vers l’aide de la solution)
* [!DNL Advertising Cloud](#adcloud) (Mis à jour le 8 novembre 2019)

Vous cherchez la page d’accueil de l’aide ? Voir la [documentation d’Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Status.adobe.com

Avec votre Adobe ID, vous pouvez vous abonner à des notifications d’événement d’état, en fonction de vos préférences de produit, de région et d’événement.

| Fonction | Description |
| -----------| ---------- |
| S’abonner à des notifications électroniques en temps réel | <ul><li>Prise en charge d’Experience Cloud, de Creative Cloud, de Document Cloud, d’AEP et des services Adobe</li><li>Prise en charge des préférences de région et de type d’événement</li><li>Prise en charge UX pour les surfaces Web, mobiles et tablettes</li></ul> |
| Gestion des préférences de notifications | <ul><li>Modifier et enregistrer les préférences de notification à tout moment</li><li>Se désabonner des notifications à tout moment</li><li>Élément</li></ul> |
| Livraison personnalisée et plus rapide des courriers électroniques | <ul><li>Les notifications d’événement sont envoyées dès que les OSC et les CMR sont ouverts, mis à jour ou fermés.</li><li>Recevez uniquement les notifications d&#39;événement correspondant aux préférences configurées</li><li>Notifications localisées reçues en fonction de la langue configurée dans les préférences de votre compte</li></ul> |
| Notifications personnalisées intégrées au produit | Les événements correspondant à vos préférences de notification et aux droits des produits apparaissent dans le panneau Annonce. |

## Interface d’Experience Cloud {#ecloud}

Notes de mise à jour de l’interface d’Experience Cloud et de l’administration des produits.

* Élément
* Élément

Pour consulter la documentation du produit, voir [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notes de mise à jour d’Experience Platform, d’Experience Platform Launch, d’Identity Service et des bulletins de sécurité.

* [Notes de mise à jour d’Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/security.html) (Tous les produits Adobe)

### Experience Platform Launch {#launch}

Pour consulter les notes de mise à jour et la documentation du produit, voir [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## [!DNL Analytics] {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices) (**Mis à jour le 18 décembre 2019**)
* [AppMeasurement](#appm)

Pour consulter la documentation du produit, voir [Accueil de l’aide Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- | 
|  |  |

#### Correctifs

* Correction
* Correction

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Nouveau domaine Adobe Analytics | 18 décembre 2019 | Le 16 janvier 2020, Adobe Analytics se déplacera vers un nouveau domaine : https://experience.adobe.com/analytics. Cette modification peut entraîner des problèmes de cookies lors du chargement d’Analytics dans Safari. La désactivation de la case à cocher &quot;Empêcher le suivi inter-sites&quot; dans les préférences de confidentialité de Safari permet d’activer les cookies entre domaines (et toutes les expériences inter-sites) et d’Analytics de fonctionner sur ce nouveau domaine Adobe Experience Cloud. Les utilisateurs peuvent utiliser d’autres navigateurs sans problème, car cela affecte uniquement les utilisateurs de Safari. |
| Abandon de l’option **[!UICONTROL Afficher l’archive]** | 30 octobre 2019 | Annonce de l’abandon en janvier 2020 de l’option **[!UICONTROL Afficher l’archive]**dans le Gestionnaire de tableaux de bord (**[!UICONTROL  Composants > Tableaux de bord]**). |
| Abandon de l’option **[!UICONTROL Exiger des restrictions d’identification par IP]** | 30 octobre 2019 | Annonce de l’abandon en janvier 2020 de la liste blanche des identifications par IP (**[!UICONTROL Exiger des restrictions d’identification par IP]**) dans le menu**[!UICONTROL  Admin > Paramètres de la société > Sécurité]**. |
| Mise à jour de la gestion de l’attribut SameSite sur les cookies | 15 octobre 2019 | En août 2019, Adobe a annoncé l’ajout de l’attribut SameSite à tous les cookies définis par Analytics. Une mise à jour de la logique est appliquée lorsque :<ul><li>Tous les cookies tiers qui ne sont pas basés sur Webkit ont un attribut SameSite défini sur `none`.</li><li>L’attribut SameSite n’est pas défini pour tous les autres cookies.</li></ul> |
| Fin de la prise en charge de TLS 1.1 | 3 octobre 2019 | D’ici le 31 mars 2020, Adobe Analytics supprimera la prise en charge de TLS 1.1. Ce changement s’inscrit dans le cadre des efforts que nous déployons pour respecter les meilleures normes de sécurité et promouvoir la sécurité des données de nos clients. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | Pour les clients basés à Londres et à Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Mise à jour des totaux de tableau à structure libre d’Analysis Workspace | 12 septembre 2019 | En octobre 2019, les lignes total du tableau à structure libre commenceront à tenir compte des [filtres de rapport](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) appliqués. À ce jour, les totaux ne prennent en compte que la segmentation. Grâce à cette modification, les visualisations dépendantes sont mises à jour (par exemple, visualisations [!UICONTROL Nombre de résumés]), ainsi que les données CSV et PDF exportées. |
| Modification à venir concernant le champ `createDate` pour les utilisateurs d’Analytics | 30 août 2019 | En octobre ou novembre 2019, le champ `createDate` pour les utilisateurs d’Analytics sera mis à jour de l’heure normale du Pacifique des États-Unis vers une valeur Date/Heure correctement formatée avec les informations sur le fuseau horaire. (AN-183468) |
| Prise en charge des décalages de fuseau horaire historiques | 8 août 2019 | Analytics gère désormais automatiquement les décalages de fuseau horaire pour les accès horodatés. Après cette modification du 8 août, les systèmes qui chargent les données pour un traitement historique n’auront plus besoin d’ajuster les décalages de fuseau horaire avant d’envoyer les données. |
| Limites du créateur de règles de classification | Ajout le 5 juin 2019 | Ces limites ne sont pas nouvelles, mais elles ont été ajoutées à la documentation [ici](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nouvelles limites des opérateurs de segment | Ajout le 31 mai 2019 | À compter du 18 juillet 2019, les opérateurs de segment _contient n’importe lequel_, _ne contient pas n’importe lequel_, _contient tous les_ et _ne contient pas tous les_ seront limités à 100 mots par champ d’entrée. Après cette date, la limite sera appliquée à tous les segments nouveaux et modifiés. Les segments existants qui dépassent la limite continueront à être pris en charge, mais ne pourront pas être modifiés ou enregistrés tant que le champ d’entrée dépasse la limite. Ces limites sont appliquées dans le cadre d’efforts continus visant à améliorer les performances des requêtes. |
| Modifications concernant la prise en charge des **[!UICONTROL classifications activées par date]**et des**[!UICONTROL  classifications numériques 2]** | Mise à jour le 28 mai 2019 | La possibilité d’importer des classifications numériques 2 et des classifications activées par date a été supprimée du code base. Cette modification a pris effet lors de la version de maintenance de juillet 2019. S’il y a des colonnes numériques ou des colonnes activées par date dans le fichier d’importation, ces cellules seront ignorées et les autres données de ce fichier seront importées normalement. <br/>Les classifications existantes peuvent toujours être exportées par le biais du workflow de classification standard et sont toujours disponibles dans les rapports. |
| Modification des calculs des _totaux des rapports_ | Mise à jour le 9 juillet 2019 | Le **18 juin 2019**, Adobe Analytics a uniformisé les calculs des _totaux des rapports_ pour toutes les dimensions et mesures. Pour cette raison, les totaux de certains rapports ont été modifiés (notamment les rapports Props ou Attributs du client). Avant cette modification, certains totaux incluaient ou excluaient la ligne _Non spécifié_ dans le total, peu importe si elle apparaissait ou _non_ dans le rapport. <br/>À compter du 18 juin 2019, le poste _Non spécifié_ apparaîtra toujours dans le total du rapport, même s’il n’apparaît pas comme poste sur le rapport. En outre, les segments qui utilisent la logique _existe_ ou _n’existe pas_ peuvent afficher des résultats différents pour certaines dimensions après cette modification, en particulier les dimensions dont _Non spécifié_ possède un nom spécial, comme l’élément de ligne « Tapé/Marqué » pour la dimension Type de référent ou l’élément de ligne « Autre » pour la dimension Type de périphérique. Cette modification concernera Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder et l’API Reporting.<br>**Remarque **: Ce calcul du total _des_rapports s’appelle désormais _Total_général. Voir Espace de travail d’analyse : Mettre à jour vers les totaux des tableaux à structure libre&quot; ci-dessus. |
| Mise à jour des téléchargements CSV d’Analysis Workspace | 10 avril 2019 | À partir du 11 avril 2019, plusieurs modifications seront apportées aux **[!UICONTROL téléchargements CSV]**(et**[!UICONTORL  copies dans le Presse-papiers]**) depuis Analysis Workspace pour supprimer le formatage des données exportées.  <ul><li>Le séparateur des milliers ne sera plus inclu. Le séparateur décimal sera toujours inclus et se conformera au format défini sous **[!UICONTROL Composants > Paramètres de rapport > Séparateur des milliers]**. Remarque : Les valeurs numériques qui utilisent une virgule comme séparateur décimal continuent à être placées entre guillemets dans le fichier CSV exporté.</li><li>Aucun symbole de devise ne sera affiché.</li><li>Aucun symbole de pourcentage ne sera affiché. Les pourcentages seront sous forme décimale. Par exemple, 75 % sera représenté comme 0,75.</li><li>La durée sera indiquée en secondes.</li><li>Les tableaux de cohortes affichent uniquement les valeurs brutes. Les pourcentages sont supprimés.</li><li>Si un nombre n’est pas valide, une cellule vide s’affichera.</li></ul> |
| Modification à venir de la commande du débogueur Analysis Workspace | 4 avril 2019 | Le **13 juin 2019**, la commande de la console permettant d’activer le débogueur Analysis Workspace sera remplacée par adobeTools.debug.includeOberonXml. adobe.tools.debug.includeOberonXml cessera de fonctionner après cette date. |
| Numéros de version des navigateurs mobiles | 7 février 2019 | Le niveau de troncation des numéros de version des navigateurs mobiles est modifié depuis le 8 janvier 2019 (de 2 à 1). Depuis lors, seuls les deux premiers niveaux des versions sont affichés (par ex. _Firefox 64.0.2_ apparaît désormais sous la forme _Firefox 64.0_). |
| Fin de vie d’[!DNL Ad Hoc Analysis] | 29 janvier 2019 | Le 6 août 2018, Adobe a annoncé la prochaine fin de vie d’[!DNL Ad Hoc Analysis]. dont la date sera communiquée dès que possible.<br/>Pour plus d’informations, y compris les versions de Java compatibles durant cette période, consultez la section [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Liens d’[!DNL Analytics] rapports courts | 14 janvier 2019 | Tout lien d’[!DNL Analytics] rapport court qui n’aura pas été consulté pendant un an sera nettoyé et supprimé à compter du jeudi 17 janvier 2019, selon un calendrier progressif. |
| Flux de données : colonne post_product_list – modification de taille | 9 janvier 2019 | Le 7 février 2019, Adobe prévoit d’étendre la taille de la colonne post_product_list de 64 Ko à 16 Mo. Cette modification garantit que les valeurs eVar de marchandisage ajoutées à la colonne post_product_list lors du traitement ne causent pas de troncature de valeurs de produits et de revenus. Si certains de vos processus assimilent des valeurs post_product_list, assurez-vous qu’ils peuvent gérer des valeurs allant jusqu’à 16 Mo en longueur ou entraîneront une troncature des valeurs à 16 Ko afin d’éviter les problèmes d’assimilation de données. |
| Modifications de gestion concernant les points de terminaison inactifs [!DNL Analytics Live Stream] | 20 décembre 2018 | À compter du 1er février 2019, les points de terminaison [!DNL Live Stream] n’ayant reçu aucune connexion d’utilisateurs actifs durant 90 jours pourront être désactivés. Vous pouvez contacter l’assistance clientèle pour obtenir des renseignements au sujet de vos points de terminaison [!DNL Live Stream] et, si besoin, demander leur réactivation. De plus, veuillez vous assurer que vos processus client maintiennent une connexion permanente, comme prévu par la configuration du service, et qu’ils sont mis en œuvre pour se reconnecter lorsque la connexion est désactivée ou interrompue. |
| Mise à jour d’Adobe [!DNL Report Builder] en raison de la fin de la prise en charge du protocole TLS 1.0 | 7 septembre 2018 | En raison de la fin de la prise en charge du protocole TLS 1.0, nous avons recommandé aux utilisateurs de [!DNL Report Builder] de télécharger la version v5.6.21 avant février 2019. À compter de cette date, les versions antérieures de [!DNL Report Builder] ne fonctionneront plus. |

### [!DNL AppMeasurement] {#appm}

Voir [Notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

### Nouvelles fonctionnalités, améliorations et correctifs dans Audience Manager {#aam-new-features}

| Fonction | Description |
|--- |----|
|  |  |

### Améliorations {#aam-enhancements}

Pour plus d’informations, veuillez contacter votre conseiller Audience Manager ou l’assistance clientèle.

### Correctifs et améliorations {#aam-fixes-and-improvements}

* Correction
* Correction

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Versions de produit

### Auto-assistance

* **Mises à jour de la documentation AEM**

   Découvrez les modifications et mises à jour importantes apportées à la documentation d’Adobe Experience Manager au cours des trois derniers mois.

   Voir [Documentation AEM : Mises à jour récentes de la documentation](https://helpx.adobe.com/experience-manager/documentation-updates.html).

### Ressources supplémentaires

* [Formation et assistance pour AEM 6.5 – Accueil](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Formation et assistance pour AEM 6.4 – Accueil](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Formation et assistance pour AEM 6.3 – Accueil](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Formation et assistance pour AEM 6.2 – Accueil](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notes de mise à jour de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Ressources de documentation

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/support/campaign/standard.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)  – [Calendrier des versions](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

| Affichage | Fonction |
|------|---------|
|  |  |

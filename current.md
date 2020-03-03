---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 9ed727b23cbc90965f44c4bb914728bbc2394d6b

---


# Notes de mise à jour d’Adobe Experience Cloud   - Mars 2020

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!NOTE]
>Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) (mises à jour produit prioritaires d’Adobe) pour être averti par e-mail de la publication des prochaines versions. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : mars 2020**

(Les dates de lancements de chaque produit peuvent varier)

* [État du système Adobe](#status)
* [Interface d’Experience Cloud et services principaux](#ecloud) (Mise à jour : **26 février 2020**)
* [Experience Platform](#platform)
* [Mobile Services et SDK mobiles](#mobile)
* [!DNL Analytics](#analytics) (Mise à jour : 21 février 2020)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (liens vers l’aide de la solution)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (liens vers l’aide de la solution)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)

Vous cherchez la page d’accueil de l’aide ? Voir la [documentation d’Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## État du système Adobe {#status}

[!UICONTROL État du système Adobe] fournit des informations détaillées, des mises à jour d’état et des notifications par e-mail relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

**Nouveautés**

* Avec votre Adobe ID, vous pouvez vous abonner à des notifications d’événement en fonction de votre produit, de votre région et de vos préférences d’événement et de langue. Les utilisateurs qui configurent leurs préférences d’abonnement sont avertis des incidents et des événements de maintenance concernant les produits qui les intéressent, et ce dès qu’ils sont ouverts, mis à jour ou fermés. Rendez-vous sur [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nouvelles fonctionnalités et améliorations disponibles dès maintenant**

| Fonction | Description |
| -----------| ---------- |
| Meilleure notification des événements liés au produit | <ul><li>Soyez informé 30 jours avant la prochaine maintenance du service. Cette fonctionnalité vous donne plus de temps pour évaluer l’impact potentiel sur vos activités, ce qui vous permet de mettre en œuvre un plan de gestion à l’avance si nécessaire.</li><li>Les notifications avancées sont disponibles sur les surfaces Web/mobile/tablette et par courrier électronique.</li></ul> |
| Personnalisez votre expérience en fonction de votre langue souhaitée | <ul><li>Choisissez une langue souhaitée pour les notifications électroniques. La fonction d’abonnement automatique est désormais disponible en 19 langues.</li></ul> |
| Amélioration de l’expérience utilisateur pour les abonnements et les notifications | <ul><li>Indiquez vos préférences de région et d’événement en un seul clic pour tous les produits auxquels vous souhaitez vous abonner.</li><li>Soyez averti lorsque les problèmes _potentiels_ deviennent des problèmes _mineurs_ ou _majeurs_.</li><li>La page du navigateur est automatiquement actualisée lorsque l’état d’un produit ou d’un événement est mis à jour.</li></ul> |

## Interface d’Experience Cloud et services principaux {#ecloud}

Mise à jour de la version : **26 février 2016**

Nouvelles fonctionnalités et correctifs pour l’interface d’Experience Cloud, notamment pour l’administration et les services principaux (attributs du client, audiences, déclencheurs, cookies, etc.).

| Fonction | Description |
| -----------| ---------- |
| Outil d’administration - Affichage des détails utilisateur | Les administrateurs peuvent afficher une liste triable et filtrable de tous les utilisateurs d’Experience Cloud et de leurs détails dans le nouvel outil d’administration. Les détails de l’utilisateur incluent l’accès au produit d’un utilisateur, ses rôles et les informations de dernier accès. Voir l’aide de [l’outil d’administration Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) pour en savoir plus. |

### Domaine de produit unifié

Adobe met à jour l’en-tête de domaine et d’interface afin d’unifier et d’améliorer votre expérience dans toutes les applications Experience Cloud. Ces améliorations sont conçues pour fluidifier votre utilisation de manière simple, mais importante. Ces améliorations ne modifieront pas vos processus actuels.

Les mises à jour comprennent les éléments suivants :

* Nouvelles URL de solution : `experience.adobe.com/<application name>` :
   * À terme, tous les produits adopteront ce modèle d’URL. Recherchez de nouvelles URL pour qu’elles prennent effet tout au long du mois.
   * Navigateurs pris en charge : [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] et [!DNL Opera] (versions les plus récentes). **Remarque** : bien que l’interface d’Experience Cloud prenne en charge ces navigateurs, les solutions individuelles peuvent ne pas tous les prendre en charge. (Par exemple, [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) ne prend pas en charge [!DNL Opera] et [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) ne prend pas en charge [!DNL Safari].)
   * ([!DNL Safari] uniquement) Le changement de domaine peut entraîner des problèmes de cookies dans [!DNL Safari]. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité de [!DNL Safari], vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Experience Cloud de fonctionner sur ce nouveau domaine.
* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide des produits : [!UICONTROL Experience League] est intégré dans le produit afin qu’une recherche d’aide comprenne également les résultats des forums de la communauté et du contenu vidéo. Cette modification simplifie l’accès à davantage de contenu et vous permet de tirer le meilleur parti d’Experience Cloud. De plus, vous pouvez cliquer sur **[!UICONTROL Aide]** > **[!UICONTROL Commentaires]** pour signaler des problèmes ou partager vos idées avec Adobe.
* Notifications améliorées : le menu déroulant [!UICONTROL Notifications] comporte désormais deux onglets, l’un pour vos propres notifications de produit et l’autre pour les annonces de produits globales.

**Remarque :** la page [!UICONTROL Flux] sera abandonnée en janvier 2020. Vous trouverez un avis d’obsolescence dans le produit.

Pour consulter la documentation du produit, voir [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notes de mise à jour d’Experience Platform, d’Experience Platform Launch, d’Identity Service et des bulletins de sécurité.

* [Notes de mise à jour d’Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/security.html) (Tous les produits Adobe)

### Experience Platform Launch {#launch}

Pour consulter les notes de mise à jour et la documentation du produit, voir [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## Mobile Services et SDK mobiles {#mobile}

Contenu mobile.

## [!DNL Analytics] {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm) (Mis à jour le 21 février 2020)

Pour consulter la documentation du produit, voir [Accueil de l’aide Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

* **Plusieurs suites de rapports dans Analysis Workspace**: Vous pouvez désormais importer des données de plusieurs suites de rapports dans un seul projet Analysis Workspace pour les afficher côte à côte. À compter du 12 mars 2020, la fonctionnalité sera déployée sur plusieurs semaines pour tous les clients. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Optimisation** de l’audience d’Experience Cloud : Cette fonctionnalité vous permet de publier des segments dans Experience Cloud dans les 8 heures (au lieu du temps de traitement de 48 heures précédent). [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)

#### Correctifs

* Correction d’un problème dans les rapports et analyses qui empêchait les clients de télécharger des rapports .xls.(AN-206541, AN-204008)
* Le déploiement d’un nouvel interpréteur de commandes a résolu plusieurs problèmes client liés au changement d’organisation d’Experience Cloud.(AN-200844, AN-186920)

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Fin de vie du paramètre &quot;Niveau de conversion&quot; | 3 mars 2020 | Le paramètre Niveau [de](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) conversion inopérant dans Outils d’administration > Report Suites > Paramètres du compte général est supprimé de l’interface utilisateur le 12 mars 2020. |
| Version électronique de l’archive du tableau de bord | 3 mars 2020 | Le paramètre &quot;Afficher l’archive&quot; sous Gérer les tableaux de bord dans les rapports et analyses ne sera plus disponible à compter du 12 mars 2020. |
| Nouveau domaine Adobe Analytics | 18 décembre 2019 | Le 16 janvier 2020, Adobe Analytics a commencé passer à un nouveau domaine : `https://experience.adobe.com/analytics.`<br>**Remarque :** cette modification s’applique à tous les utilisateurs accédant à Analytics avec leur Adobe ID ou Enterprise ID.<ul><li>Ce changement de domaine peut créer des problèmes de cookies lors du chargement d’Analytics dans Safari. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité de Safari, vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Analytics de fonctionner sur ce nouveau domaine Adobe Experience Cloud. Vous pouvez utiliser d’autres navigateurs sans problème, car cette particularité affecte uniquement les utilisateurs de Safari.</li><li>Le changement de domaine peut entraîner l’arrêt du fonctionnement d’[!UICONTROL Activity Map] pour certains clients [dans des cas spécifiques](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vie : API héritées d’Analytics | 9 janvier 2020 | En novembre 2020, les services d’API hérités d’Analytics suivants arriveront en fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner. <ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Nous avons mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Abandon de l’option **[!UICONTROL Afficher l’archive]** | 30 octobre 2019 | Annonce de l’abandon en janvier 2020 de l’option **[!UICONTROL Afficher l’archive]** dans le Gestionnaire de tableaux de bord (**[!UICONTROL Composants > Tableaux de bord]**). |
| Abandon de l’option **[!UICONTROL Exiger des restrictions d’identification par IP]** | 30 octobre 2019 | Annonce de l’abandon en janvier 2020 de la liste blanche des identifications par IP (**[!UICONTROL Exiger des restrictions d’identification par IP]**) dans le menu **[!UICONTROL Admin > Paramètres de la société > Sécurité]**. |
| Fin de la prise en charge de TLS 1.1 | 3 octobre 2019 | D’ici le 31 mars 2020, Adobe Analytics supprimera la prise en charge de TLS 1.1. Ce changement s’inscrit dans le cadre des efforts que nous déployons pour respecter les meilleures normes de sécurité et promouvoir la sécurité des données de nos clients. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | Pour les clients basés à Londres et à Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Modification à venir concernant le champ `createDate` pour les utilisateurs d’Analytics | 30 août 2019 | En octobre ou novembre 2019, le champ `createDate` pour les utilisateurs d’Analytics a été mis à jour de l’heure normale du Pacifique des États-Unis vers une valeur de date et d’heure correctement formatée avec les informations sur le fuseau horaire.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Voir [Notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). La version 2.19.0 a été publiée le 21 février 2020.

## Audience Manager {#aam}

Correctifs et fonctionnalités ajoutées à Audience Manager.

### Nouvelles fonctionnalités, améliorations et correctifs dans Audience Manager {#aam-features}

| Fonction | Description |
|----|----|
|  |  |
|  |  |

### Correctifs et améliorations {#aam-fixes-and-improvements}

Correctifs pour AAM.

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Ressources supplémentaires

* [AEM en tant que Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [Formation et assistance pour AEM 6.5 – Accueil](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Page d’accueil Formation et assistance AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Page d’accueil Formation et assistance AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Page d’accueil Formation et assistance AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notes de mise à jour de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Ressources supplémentaires

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/support/campaign/standard.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)  – [Calendrier des versions](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Mise à jour du 10 février 2020 pour la version du 8 février

## [!DNL Magento] {#magento}

Pour les notes de mise à jour de Magento, veuillez consulter :

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] est une solution complète pour la gestion des pistes et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Date de publication : 21 février 2020

* **Microsoft Dynamics _Modification de propriétaire dans Microsoft_ Action de processus** : Modifiez un prospect ou un propriétaire de contact directement à partir de Marketo Engage.
* **Améliorations des appels d’API :**
   * API de gestion des utilisateurs
   * API de schéma d’objet personnalisé
   * API de règles de redirection de page d’entrée
* **Mise en cache des descripteurs de formulaire** : Améliorations apportées aux pages d’entrée et aux formulaires.

Pour plus d’informations, voir les Notes de mise à jour de [!DNL Marketo] de [février 2020](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720).

### Fonctionnalités à venir

Les fonctionnalités suivantes seront publiées tout au long du trimestre :

| Fonction | Description |
|------|---------|
| [!DNL Bizible] | <ul><li>Nouvelle segmentation basée sur un compte</li><li>Enregistrement des filtres spécifiques au tableau de bord</li><li>Exportation de tableaux de bord Bizible au format PDF</li></ul> |
| Connect de ventes | Composition des mises à jour/améliorations de Windows et du Centre de commandes |

### Annonces

**** Centre de succès Marketo Engage : Lancement en février 2020. Le centre de succès est un centre d’aide intégré qui vous permet de rechercher des documents produit et la communauté, de lancer des guides pratiques, d’accéder au contenu d’adoption, etc. Remarque : Cette fonctionnalité sera lancée en version bêta en ANZ et sera déployée en Amérique du Nord plus tard dans le trimestre.

### Dépréciations

* **Paramètre de l’API de ressource &quot;_method&quot; :** Après septembre 2020, les points de fin d’API d’actif n’accepteront plus &quot;_method&quot; pour transmettre les paramètres de requête dans un corps POST afin de contourner les limitations de longueur d’URI.
* **Dépréciation de la prise en charge d’Internet Explorer :** A compter de la version du 31 juillet 2020, l’interface utilisateur de Marketo Engage ne sera plus prise en charge dans Internet Explorer.

Pour obtenir des notes de mise à jour cumulatives et historiques, reportez-vous à la page [Notes de mise à jour de Marketo](https://docs.marketo.com/x/CgA6Ag).
---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: b0f2fe07102a20e343f69b1c156f48ca4f284966

---


# Accès anticipé - Notes de mise à jour d’Adobe Experience Cloud - Janvier 2020

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!IMPORTANT]
>Cette page contient du contenu de version préliminaire et peut être modifiée avant la publication prévue de chaque produit.

>[!NOTE]
>Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) (mises à jour produit prioritaires d’Adobe) pour être averti par e-mail de la publication des prochaines versions. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : 16 janvier 2020**

* [État du système Adobe](#status)
* [Interface Experience Cloud et services principaux](#ecloud)
* [Experience Platform](#platform)
* [Services mobiles et SDK mobiles](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (liens vers l’aide de la solution)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (liens vers l’aide de la solution)
* [!DNL Advertising Cloud](#adcloud)

Vous cherchez la page d’accueil de l’aide ? Voir la [documentation d’Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Adobe System Status {#status}

[!UICONTROL Adobe System Status] fournit des informations détaillées, des mises à jour d’état et des notifications par courrier électronique au sujet des produits et services Adobe Cloud et des événements de panne, de panne et de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

**Nouveautés**

* Avec votre Adobe ID, vous pouvez vous abonner à des notifications d’événement en fonction de vos préférences de produit, de région et d’événement. Les utilisateurs qui configurent leurs préférences d’abonnement sont avertis uniquement des incidents de produit et des événements de maintenance pertinents dès qu’ils sont ouverts, mis à jour ou fermés. Commencez sur [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nouvelles fonctionnalités et améliorations disponibles aujourd’hui**

| Fonction | Description |
| -----------| ---------- |
| S’abonner à des notifications par courrier électronique proactives | <ul><li>Prise en charge d’Experience Cloud, de Creative Cloud, de Document Cloud, d’Adobe Experience Platform et des services Adobe</li><li>Compatible avec les paramètres de région et les préférences de type d’événement</li></ul> |
| Gestion des préférences de notification | <ul><li>Modifiez et enregistrez vos préférences de notification à tout moment</li><li>Désabonnez-vous des notifications à tout moment</li></ul> |
| Recevez des courriers électroniques personnalisés et plus rapides | <ul><li>Des notifications d’événement sont envoyées dès que des événements sont ouverts, mis à jour ou fermés.</li><li>Recevez uniquement les notifications d’événement correspondant à vos préférences</li><li>Recevez des notifications localisées en fonction de la langue configurée dans vos préférences de compte</li></ul> |
| Recevez des notifications personnalisées intégrées au produit | <ul><li>Les événements correspondant à vos préférences de notification et aux droits des produits apparaissent dans le panneau Annonces.</li></ul> |

## Experience Cloud interface and core services {#ecloud}

Nouvelles fonctionnalités et correctifs de l’interface d’Experience Cloud, y compris l’administration et les services principaux (attributs du client, audiences, triggers, cookies, etc.).

### Domaine de produit unifié

Adobe met à jour l’en-tête de domaine et d’interface afin d’unifier et d’améliorer votre expérience dans toutes les applications Experience Cloud. Ces améliorations sont conçues pour simplifier votre expérience de manière modeste mais importante. Ces améliorations ne modifieront pas vos processus actuels.

Les mises à jour incluent :

* Nouvelles URL de solution : `experience.adobe.com/<application name>.` Tous les produits adopteront finalement ce modèle d’URL. Recherchez de nouvelles URL pour qu’elles prennent effet tout au long du mois.
* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide sur les produits : [!UICONTROL Experience League] est intégrée dans le produit afin qu’une recherche d’aide comprenne également les résultats des forums de la communauté et du contenu vidéo. Cette modification simplifie l’accès à davantage de contenu et vous permet de tirer le meilleur parti d’Experience Cloud. De plus, cliquez sur **[!UICONTROL Aide]**>**[!UICONTROL  Commentaires]** pour signaler des problèmes ou partager vos idées avec Adobe.
* Notifications améliorées : Le menu déroulant [!UICONTROL Notifications] comporte désormais deux onglets, l’un pour vos propres notifications de produit et l’autre pour les annonces de produits globales.

**** Remarque : La page [!UICONTROL Flux] est obsolète en janvier 2020. Vous trouverez un avis d’obsolescence dans le produit.

Pour consulter la documentation du produit, voir [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Cookies Experience Cloud

Adobe est en train d’ajuster le `same-site` paramètre des cookies afin de préparer les modifications que Chrome apportera dans Chrome 80 (à paraître en février 2020).

Vous n’avez pas besoin d’apporter des modifications, sauf si vous utilisez un CNAME pour la collecte de données propriétaires, mais que vous utilisez ce CNAME sur plusieurs domaines (domaines tiers conviviaux) et que vous n’utilisez pas le service d’identification des visiteurs Experience Cloud. Avec la version 80 de Chrome, Chrome attribue automatiquement aux cookies d’identification des visiteurs d’Analytics une valeur MêmeSite `Lax,` qui empêche leur utilisation sur vos autres domaines. Si vous souhaitez continuer à utiliser votre CNAME sur l’ensemble de vos domaines, vous devez contacter le service à la clientèle d’Adobe et lui demander de modifier la valeur MêmeSite pour votre CNAME en `None.`

Notez qu’Adobe vous recommande d’utiliser un CNAME distinct pour chacun de vos domaines, que vous utilisiez ou non le service d’ID Experience Cloud.

[Plus…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Notes de mise à jour d’Experience Platform, d’Experience Platform Launch, d’Identity Service et des bulletins de sécurité.

* [Notes de mise à jour d’Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/security.html)   (Tous les produits Adobe)

### Experience Platform Launch {#launch}

Pour consulter les notes de mise à jour et la documentation du produit, voir [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## Mobile Services and Mobile SDKs {#mobile}

16 janvier 2020 : Version 4.18.0

* Acquisition : ajout d’une nouvelle API `Analytics.processGooglePlayInstallReferrerUrl(final String url)`, afin de prendre en charge [!DNL Google Play] l’installation des API de référents.

Pour plus d’informations sur l’installation des API de référents, voir [Toujours utiliser InstallBroadcast ? Passez à l’API de référent de lecture d’ici le 1er mars 2020](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html).

## [!DNL Analytics] {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)  

Pour consulter la documentation du produit, voir [Accueil de l’aide Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- | 
| Espace de travail d’analyse - Générateur de tableau à structure libre | Le Générateur de tableau étant activé, vous pouvez faire glisser et déposer de nombreuses dimensions, ventilations, mesures et segments afin de créer des tableaux qui répondent à des questions plus complexes. Les données ne seront pas mises à jour immédiatement. Au lieu de cela, des mises à jour se produisent après avoir cliqué sur **[!UICONTROL Créer]**, ce qui vous permet de gagner du temps une fois que vous connaissez la table que vous souhaitez construire. En outre, cette fonctionnalité offre :<ul><li>**Aperçu**: Vous pouvez prévisualiser le format d’un tableau avant de passer du temps à générer des données réelles.</li><li>**Paramètres** de rangée et de ventilation flexibles : Vous pouvez définir les niveaux de rangée et de ventilation pour chaque ligne de dimension. Auparavant, Workspace imposait des valeurs par défaut qui ne pouvaient pas être modifiées avant le renvoi des données.</li><li>**Ventilation par position**: Vous pouvez définir des lignes de dimension pour toujours _les ventiler par position_ et non _par élément_ spécifique (valeur par défaut).</li><li>**Ordre manuel des rangées** statiques : Vous pouvez trier manuellement les rangées statiques afin que les rangées du tableau s’affichent exactement comme vous en avez besoin. Auparavant, les lignes statiques pouvaient être triées uniquement par colonne de mesure ou par ordre alphabétique.</li></ul>La documentation associée sera publiée lorsque cette fonctionnalité sera disponible plus tard en janvier. |
| Nouvelle dimension d’état  identifié pour Analytics sur plusieurs périphériques (CDA) | Nous ajoutons une nouvelle dimension appelée État  identifié aux suites de rapports virtuelles CDA. La dimension a deux valeurs possibles : _Identifié_ et _Non identifié_. _Identifié_ signifie que la personne a été identifiée par le graphique de l’appareil. _Non identifié_ signifie que la personne n’a pas été identifiée par le graphique de l’appareil.<br>Cela signifie que les utilisateurs de CDA peuvent désormais créer des mesures calculées, telles que la couverture [!UICONTROL graphique du]périphérique, qui décrit le nombre de personnes dans la suite de rapports virtuelle qui sont connues par le graphique du périphérique. Cette mesure est utile pour résoudre les problèmes de taux de compression CDA. Si peu de personnes sont identifiées, le niveau de couture sera faible. |
| Prise en charge de VRS dans l’API de l’entrepôt de données | Les suites de rapports virtuelles seront désormais disponibles pour une utilisation via l’API Data Warehouse. Auparavant, elles n’étaient disponibles que par l’interface utilisateur de l’entrepôt de données. Lors de l&#39;utilisation de l&#39;API Entrepôt de données, vous pouvez désormais afficher et interroger des suites de rapports virtuelles, mais uniquement si les segments appliqués à une suite de rapports virtuelle sont compatibles avec l&#39;Entrepôt de données. |
| API Privacy Service : CCPA | Le California Consumer Privacy Act (CCPA) protège la vie privée et les consommateurs pour les personnes résidant en Californie, États-Unis. Cette loi est entrée en vigueur le 1er janvier 2020.<br><br/>Le CCPA offre aux Californiens de nouveaux droits sur leurs données personnelles, comme le droit d’y accéder et de les supprimer, mais aussi de savoir si leurs données sont vendues ou divulguées (et, le cas échéant, à qui) et de refuser la vente de leurs données.<br><br/>Le service de protection des données personnelles prend en charge les demandes de désabonnement de la vente de données personnelles.<br><br/>Le Service de la protection de la vie privée était auparavant le Service RMMD et conserve toutes les fonctionnalités antérieures, maintenant étendues pour appuyer l’ACCP.<br/><br/>[CCPA dans Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Présentation de Privacy Service](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### Correctifs

* Correction d’un problème en raison duquel les notifications d’alerte n’étaient pas envoyées aux numéros de téléphone en Égypte. (AN-197079)
* Correction de plusieurs problèmes avec le [!DNL DFA Data Connector]. (AN-193281, AN-193075, AN-193484, AN-193737)
* [!UICONTROL Rapports et analyses]: Correction d’un problème en raison duquel le rapport Entonnoir de conversion de produit était coupé et affichait des nombres non clairs. (AN-186901)
* Correction d’un problème qui empêchait les utilisateurs de basculer entre des suites de rapports dans des projets Workspace basées sur des suites de rapports avec la nouvelle architecture des classifications. (AN-199076)
* Correction d’un problème qui empêchait le fonctionnement correct de la fonction [!UICONTROL Cumulative] dans les mesures  calculées. (AN-184257)

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout   ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Nouveau domaine Adobe Analytics | 18 décembre 2019 | Le 16 janvier 2020, Adobe Analytics commencera à passer à un nouveau domaine - `https://experience.adobe.com/analytics.`<br>**Remarque **: Cette modification s’applique à tous les utilisateurs accédant à Analytics avec leur Adobe ID ou Enterprise ID.<ul><li>Le changement de domaine peut entraîner des problèmes de cookies lors du chargement d’Analytics dans Safari. Unchecking _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. Vous pouvez utiliser d’autres navigateurs sans problème, car cela affecte uniquement les utilisateurs de Safari.</li><li>Le changement de domaine peut entraîner l’arrêt du fonctionnement de [!UICONTROL Carte] d’activités pour certains clients [dans des cas](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)spécifiques.</li></ul> |
| Fin de vie - API héritées d’Analytics | 9 janvier 2020 | En novembre 2020, les services Analytics Legacy API suivants arriveront en fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner. <ul><li>1.3 API Analytics</li><li>1.4 API SOAP Analytics</li><li>Authentification OAuth héritée (OAuth et JWT)</li></ul>Nous avons fourni une FAQ [EOL API](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) héritée pour répondre à vos questions et vous donner des conseils sur la façon de procéder. Les intégrations d’API qui utilisent ces services peuvent migrer vers les API [REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 1.4 Analytics ou vers les API [Analytics](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)2.0. Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Abandon de l’option **[!UICONTROL Afficher l’archive]** | 30 octobre 2019 | Annonce de l’abandon en janvier 2020 de l’option **[!UICONTROL Afficher l’archive]** dans le Gestionnaire de tableaux de bord (**[!UICONTROL  Composants > Tableaux de bord]**). |
| Abandon de l’option **[!UICONTROL Exiger des restrictions d’identification par IP]** | 30 octobre 2019 | Annonce de l’abandon en janvier 2020 de la liste blanche des identifications par IP (**[!UICONTROL Exiger des restrictions d’identification par IP]**) dans le menu **[!UICONTROL  Admin > Paramètres de la société > Sécurité]**. |
| Fin de la prise en charge de TLS 1.1 | 3 octobre 2019 | D’ici le 31 mars 2020, Adobe Analytics supprimera la prise en charge de TLS 1.1. Ce changement s’inscrit dans le cadre des efforts que nous déployons pour respecter les meilleures normes de sécurité et promouvoir la sécurité des données de nos clients. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | Pour les clients basés à Londres et à Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Modification à venir concernant le champ `createDate` pour les utilisateurs d’Analytics | 30 août 2019 | In October or November 2019, the `createDate` field for Analytics users was updated from US Pacific Time to a correctly formatted date and time value with time zone information.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Voir [Notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Correctifs et fonctionnalités ajoutés à Audience Manager.

### Nouvelles fonctionnalités, améliorations et correctifs dans Audience Manager {#aam-features}

| Fonction | Description |
| -----------| ---------- |
| [Loi sur la protection des renseignements personnels des consommateurs de Californie (ACCP) - Soutien et révision de la documentation sur la protection des renseignements personnels](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | La [California Consumer Privacy Act (CCPA)](https://www.caprivacy.org/about), qui est entrée en vigueur le 1er janvier 2020, accorde aux résidents de Californie de nouveaux droits concernant leurs renseignements personnels et impose des responsabilités en matière de protection des données à certaines entités qui font des affaires en Californie. <br><br> Audience Manager vous aide à respecter vos obligations en vertu des règles de confidentialité, par le biais d’outils de confidentialité tels que [Adobe Experience Platform Privacy Service](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) pour l’accès aux données et la suppression des requêtes. <br><br> Nous avons mis à jour le processus actuel de gestion [des](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests) exclusions afin d’inclure l’exclusion de tout ID déclaré (par exemple, ID CRM). Dans le cas d’une exclusion par ID déclaré, l’ID déclaré et le dernier périphérique lié seront exclus de la collecte de données d’Audience Manager. Les demandes d’exclusion envoient désormais également des demandes de non-segmentation aux partenaires [de](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation) destination qui prennent en charge cette fonctionnalité, à la fois par lot et en temps réel. <br><br> De plus, nous avons remanié notre documentation sur la sécurité [des](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html)données, la confidentialité [des](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html)données et la gouvernance [des](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html) données afin de vous permettre de trouver plus facilement les informations requises pour se conformer aux réglementations susmentionnées. |

### Correctifs et améliorations {#aam-fixes-and-improvements}

* Correction d’un problème dans le flux de travail [!UICONTROL Créer une destination] en raison duquel, lors de la sélection de plateformes ****intégrées comme[!UICONTROL catégorie][!UICONTROL , la section Informations de base disparaissait et le flux de travail était impossible à terminer.](AAM-52397, AAM-52414)
* Correction d’un bogue en raison duquel la page [!UICONTROL Créer/modifier] des destinations ne se chargeait pas dans les navigateurs Apple Safari et Mozilla Firefox. (AAM-51784)

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Maintenance du produit

* **AEM 6.5.3.0** AEM 6.5, Service Pack 3.0 (version 6.5.3.0 publiée le 12 décembre 2019) est une mise à jour importante qui comprend les correctifs client clés publiés depuis la disponibilité générale d’AEM 6.5, avril 2019.
   * [Notes de mise à jour](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4, Service Pack 7.0 (6.4.7.0, publié le 12 décembre 2019) est une mise à jour importante qui inclut les correctifs client clés publiés depuis la disponibilité générale d’AEM 6.4, avril 2018.
   * [Notes de mise à jour](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 7 (6.3.3.7 publié le 12 décembre 2019) est une mise à jour importante qui comprend les correctifs client clés publiés depuis la disponibilité générale d’AEM 6.3, avril 2017.
   * [Notes de mise à jour](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Desktop App 2.0.1.1**

   AEM Desktop App 2.0.1.1 fournit une mise à jour pour la connexion unique avec Okta et permet de spécifier l’emplacement des fichiers temporaires dans les Préférences. La prise en charge d’AEM 6.3.x est obsolète pour l’application de bureau 2.x avec cette version.
   * [Notes de mise à jour](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1 met fin à la prise en charge d’AEM 6.3.x**

   La prise en charge d’AEM 6.3.x est obsolète dans Adobe Asset Link depuis avril 2019. Adobe Asset Link 1.1 supprime la prise en charge d’AEM 6.3.x à compter du 13 janvier 2020.
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### Versions de produit

* **Service de conversion automatisée de formulaires**

   Le service de conversion automatisée des formulaires, qui permet de convertir automatiquement des formulaires PDF en formulaires HTML prêts pour les périphériques mobiles, est devenu disponible pour la consommation générale le 12 décembre 2019.

   * [Introduction](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [Configuration du service](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [Conversion de formulaires PDF en formulaires adaptatifs](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### Auto-assistance

* **Prévisualisation de fichiers 3D**

   AEM 6.5 prend en charge le téléchargement, la diffusion et l’aperçu interactif des ressources 3D dans le cadre du processus de création. La visionneuse 3D interactive est disponible à partir de la page des détails des ressources dans AEM. Le lecteur de contenu comprend, entre autres, une collection de commandes de caméra interactives qui vous permettent d’effectuer un zoom ou un panoramique sur la ressource 3D.
Voir [Prévisualisation de fichiers](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html)3D.

* **Composants Core**

   Core Components 2.8.0, with numerous fixes, is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **Archétype de projet AEM**

   Le module [ui.frontend](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html) de l’archétype [de projet](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) AEM est un outil utile et flexible qui facilite le développement frontal de votre projet AEM.

### Ressources supplémentaires

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

### Campaign Classic 19.2

| Fonction | Description |
| ------------- | ----------- |
| California Consumer Privacy Act (CCPA) | L&#39;ACCP est la nouvelle loi sur la protection des renseignements personnels de l&#39;État de Californie qui harmonise et modernise les exigences en matière de protection des données qui entreront en vigueur le 1er janvier 2020. L’ACCP s’applique aux clients d’Adobe Campaign qui détiennent des données pour les sujets de données résidant en Californie. <br> Outre les fonctionnalités de confidentialité déjà disponibles (notamment la gestion du consentement, les paramètres de rétention des données et les rôles utilisateur), Adobe Campaign vous aide à mieux vous préparer à l’application CCPA : <ul><li>__ Droit d&#39;accès _et_ droit de suppression : nous tirons parti des capacités qui ont été ajoutées au RMPC. [En savoir plus](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>Vous pouvez déterminer si un consommateur a choisi de ne pas vendre de renseignements personnels. Pour ce faire, vous devez étendre le tableau [!UICONTROL Profils] et ajouter un champ **[!UICONTROL d’exclusion pour l’ACCP]**.[En savoir plus](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> Reportez-vous à la vidéo [pratique](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html). |
| Surveillance en direct du flux de travail | Vous pouvez désormais surveiller l’état d’exécution de tous les processus de votre instance à l’aide de vues prédéfinies. <br> Pour plus d’informations, voir [Filtrage des processus en fonction de leur état](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status). |
| Contenu interactif avec AMP | Adobe Campaign vous permet de tester le nouveau format interactif [AMP pour le courrier électronique](https://amp.dev/about/email/) , qui permet aux spécialistes du marketing d’inclure des composants AMP dans les messages afin d’améliorer l’expérience du courrier électronique grâce à un contenu riche, dynamique et interactif, directement exploitable dans le message lui-même. <br> Cette fonctionnalité est publiée en version bêta publique. <br> Pour plus d&#39;informations, reportez-vous à la documentation [](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html) détaillée et à la vidéo [du](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html)didacticiel. |
| Messagerie SMS sécurisée (TLS) | Les SMS sécurisés sont désormais pris en charge via le connecteur Extended Generic SMPP. Cela permet une connexion chiffrée au fournisseur. <br> **Avertissement**: cette fonctionnalité nécessite un certificat à jour sur tous les serveurs. Les certificats non valides, révoqués ou expirés génèrent des erreurs affectant les capacités d&#39;envoi SMS globales. <br>Pour plus d’informations, consultez la [documentation détaillée](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |

Voir les [Notes de mise à jour d’Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) pour les correctifs et améliorations.

### Campaign Standard 19.4

| Fonction | Description |
| ------------- | ----------- |
| California Consumer Privacy Act (CCPA) | L&#39;ACCP est la nouvelle loi sur la protection des renseignements personnels de l&#39;État de Californie qui harmonise et modernise les exigences en matière de protection des données qui entreront en vigueur le 1er janvier 2020. L’ACCP s’applique aux clients d’Adobe Campaign qui détiennent des données pour les sujets de données résidant en Californie. <br> Outre les fonctionnalités de confidentialité déjà disponibles dans Adobe Campaign (notamment la gestion du consentement, les paramètres de rétention des données et les rôles utilisateur), nous profitons de l’occasion pour inclure des fonctionnalités supplémentaires afin de faciliter votre préparation à l’ACCP : <ul><li> Droit d&#39;accès et droit de suppression : nous tirons parti des capacités qui ont été ajoutées au RMPC. [En savoir plus](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> Lors de la création d’une demande de protection de la vie privée, le type de réglementation (RDPC ou ACCP) a été ajouté au service principal de protection de la vie privée. Cette méthode est celle que vous devez utiliser pour toutes les requêtes d’accès et de suppression. L’utilisation de l’API et de l’interface Campaign pour l’accès et la suppression des requêtes est obsolète. Consultez l’article [Fonctions](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html)obsolètes et supprimées. </li><li> Un champ d’exclusion **de l’** ACCP a été ajouté à la ressource Profils pour permettre aux utilisateurs d’Adobe Campaign de déterminer si un client a choisi de ne pas vendre ses informations personnelles. [En savoir plus](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> Reportez-vous à la vidéo [pratique](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html). |
| Intégration de Microsoft Dynamics 365 (GA) | L’intégration entre Adobe Campaign Standard et Microsoft Dynamics 365 est désormais disponible. Vous pourrez transférer vos enregistrements de contacts et d&#39;entités personnalisées de Dynamics 365 vers Campaign et récupérer les données d&#39;événement de courriel de Campaign vers Dynamics 365 pour un meilleur alignement ventes/marketing. <br> Reportez-vous à la documentation [](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html) détaillée pour configurer cette intégration et voir la vidéo [](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html)pratique. |

See [Adobe Campaign Standard Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) for fixes and improvements.

### Panneau de configuration d’Adobe Campaign

Nous avons ajouté de nouvelles fonctionnalités permettant aux administrateurs de déléguer des sous-domaines et de renouveler les certificats SSL à partir du Panneau de configuration.

Pour plus d’informations, reportez-vous aux pages suivantes :

* Configuration d’un nouveau sous-domaine - [En savoir plus](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* Renouvellement du certificat SSL d’un sous-domaine - [En savoir plus](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>Ces fonctionnalités seront disponibles en version bêta d&#39;ici la fin janvier et feront l&#39;objet de fréquentes mises à jour et modifications sans préavis.

### Ressources supplémentaires

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/support/campaign/standard.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)  – [Calendrier des versions](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panneau de configuration Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - Notes de [mise à jour](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Mise à jour du 11 janvier 2020, version

| Affichage | Fonction |
|------|---------|
| Suivi des conversions | Tous les cookies Advertising Cloud ont été mis à jour pour répondre aux nouvelles exigences de contrôle des cookies pour Google Chrome 80, qui sera publié le 4 février. Les modifications ont été implémentées à partir des serveurs Adobe à l’aide des cookies existants, sans aucun effet sur les mesures des visiteurs. Aucune mise à jour de l’annonceur n’est requise. |
| Statistiques > Alertes bêta, Recherche > Campagnes | (Fonction bêta pour les comptes de recherche uniquement) Une nouvelle version bêta des alertes vous permet de créer des modèles d&#39;alerte afin d&#39;identifier quand une campagne de recherche, un groupe publicitaire, un mot-clé ou une publicité répond à des conditions spécifiques — comme les mesures de performances — pendant une période spécifiée, puis générez une alerte. Les alertes sont disponibles pour un seul annonceur. |
| Rapports | Les données relatives aux publicités avec liste de produits sont désormais incluses dans les rapports Classification des étiquettes, Valeur des étiquettes, Règle sur l’offre et Contrainte. |

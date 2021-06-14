---
title: Dernières notes de mise à jour
description: Découvrez les dernières notes de mise à jour, les nouvelles fonctionnalités et la nouvelle documentation pour les produits et services Experience Cloud. Trouvez de nouvelles aides et des tutoriels sur Experience Cloud, Creative Cloud abonnement Entreprise et Document Cloud.
doc-type: release notes
last-update: June 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 823476f3b4553a0bd9aae8670652bec1259cd84f
workflow-type: tm+mt
source-wordcount: '4914'
ht-degree: 52%

---

# Notes de mise à jour d’Adobe Experience Cloud - Juin 2021

![Bannière](assets/experience-cloud-banner-3.png)

Les applications et les services Experience Cloud sont mis à jour chaque mois. Cette page est votre destination de référence lorsque vous recherchez les dernières mises à jour, la documentation et les tutoriels pour [!DNL Experience Cloud] et [!DNL Experience Platform]. Vous trouverez également de nouvelles documentations pour [!DNL Creative Cloud for Enterprise] et [!DNL Document Cloud].

>[!NOTE]
>
>Abonnez-vous à la [mise à jour produit prioritaire d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) pour recevoir chaque mois des notifications par email concernant les mises à jour de cette page. Cette page est tenue à jour tout au long du mois. Par conséquent, veuillez consulter régulièrement les mises à jour des produits Adobe Enterprise et de la documentation Experience League.

Dernière mise à jour : **11 juin 2021**

* [Composants de lʼinterface centrale dʼExperience Cloud](#ecloud)
* [Statut du système Adobe](#status)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [[!DNL Analytics]](#analytics) et  [Customer Journey Analytics](#cust-journey)
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Campaign]](#ac)
* [[!DNL Advertising]](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [Document Cloud](#doc-cloud)
* [Creative Cloud abonnement Entreprise](#creative-cloud)

Besoin d’aide ? Consultez [Adobe Experience League](https://experienceleague.adobe.com/?lang=fr#home) pour trouver de la documentation technique et sur les produits, des cours préparés par Adobe, des tutoriels vidéo, des réponses rapides, des informations provenant de la communauté et des formations dispensées par un instructeur.

## ![](/assets/ec_appicon_24.png) Icône Composants de l’interface utilisateur centrale d’Experience Cloud {#ecloud}

Les composants de l’interface centrale d’Experience Cloud incluent des mises à jour auxquelles l’accès se fait à partir de l’en-tête du produit unifié, telles que l’aide autonome, la recherche et les préférences du compte utilisateur. Vous trouverez ici des mises à jour sur les personnes, les lieux (emplacement) et la gestion des produits.

| Fonctionnalité | Date | Description |
| ------- | ------- | ------- |
| Prise en charge de l’authentification unique pour les Federated ID Adobes | 17 juin 2021 | Si vous utilisez des Federated ID, vous pouvez vous connecter à Experience Cloud sans avoir à saisir d’adresse électronique ou de mot de passe. Pour utiliser cette fonctionnalité, ajoutez **#/sso:@domain** à l’URL de l’Experience Cloud. <br><br>Supposons, par exemple, que vous possédiez la commande domain  **adobecustomer.**  et que vous souhaitiez vous connecter à Adobe Analytics. L’URL serait : **https://experience.adobe.com/#/sso:@adobecustomer.com/analytics**. |
| Experience League Search | 1 juin 2021 | La recherche de documentation Experience League a été améliorée. Accédez à [Experience League](https://experienceleague.adobe.com/docs/?lang=en) et utilisez le champ **[!UICONTROL Rechercher]** pour localiser les tutoriels, la documentation, les cours, etc. |

{style=&quot;table-layout:auto&quot;}

**Autres ressources d’aide**

* Aide à l’administration pour les [composants de l’interface centrale](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) et la gestion des utilisateurs
* Aide et notes de mise à jour pour [Places - Location Service](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Aide sur [Personnes - Attributs du client et bibliothèque d’audiences](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en).

## ![Icône](/assets/adobe.png) Statut du système Adobe {#status}

[!UICONTROL Statut du système Adobe] fournit des informations détaillées, des mises à jour de statut et des notifications par email relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

Les mises à jour les plus récentes et les informations sur la dernière version concernant le statut du système Adobe se trouvent sur le lien suivant [Statut du système Adobe - 21 mai 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=fr).

## ![Icône](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Inclut des informations de mise à jour et une nouvelle documentation pour les Experience Platform et les Experience Platform Launch.

* **26 mai 2021 :** [Notes de mise à jour de l’Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=fr)
* **17 mai 2021 :** [Notes de mise à jour de la collecte de données Experience Platform](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=fr)  (anciennement, Experience Platform Launch)

### Tutoriels et cours sur Experience Platform {#tutorials-platform}

Nouveaux tutoriels, vidéos ou cours publiés pour Experience Platform et ses services.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Juin 2021 | [Préparation des données](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/prepare-data.html) | Vidéo | Découvrez comment nettoyer, préparer et combiner les données de plusieurs jeux de données pour créer un jeu de données à l’aide des fonctions Create Table AS (CTAS) et Spark SQL pour la création de rapports et l’intégration à des tableaux de bord. |
| Juin 2021 | [Copie de schémas entre des environnements de test](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/copy-schemas-between-sandboxes.html) | Vidéo | Découvrez comment copier un schéma d’un environnement de test vers un autre dans Adobe Experience Platform à l’aide de l’[!UICONTROL API de schéma d’exportation/importation]. Créez et testez vos schémas dans les environnements de test de développement, puis copiez-les en production. |
| Juin 2021 | [mettre à jour les schémas,](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/update-schemas.html) | Vidéo | Découvrez les éléments de base à connaître lors de la mise à jour des schémas existants dans Adobe Experience Platform. |
| Juin 2021 | [Blocs de création de schéma](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schema-building-blocks.html) | Vidéo | Découvrez les éléments de blocs de création clés des schémas du modèle de données d’expérience (XDM), notamment les champs, les types de données, les groupes de champs de schéma, les classes et le comportement. |
| Juin 2021 | [Création de classes](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-classes.html) | Vidéo | Découvrez comment créer des classes dans Adobe Experience Platform pour les utiliser dans des schémas de modèle de données d’expérience (XDM). |
| Juin 2021 | [Configurer les relations entre les schémas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/configure-relationships-between-schemas.html) | Vidéo | Découvrez comment configurer une relation entre deux schémas dans Adobe Experience Platform. Les relations vous permettent d’utiliser un jeu de données comme table de recherche pour un autre. |
| Juin 2021 | [Création de types de données](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-data-types.html) | Vidéo | Découvrez comment créer vos propres types de données dans Adobe Experience Platform à utiliser dans les schémas de modèle de données d’expérience (XDM). |
| Juin 2021 | [Convertir votre modèle de données en modèle de données d’expérience](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/convert-your-data-model-to-xdm.html) | Vidéo | Découvrez comment les architectes de données peuvent prendre leur modèle de données transactionnelles existant et le convertir en modèle de données d’expérience. Cette vidéo montre la différence entre les approches de modélisation à l’aide de diagrammes de relation d’entité. |
| Juin 2021 | [Planification de votre modèle de données](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/plan-your-data-model.html) | Vidéo | Découvrez ce que vous devez faire avant de commencer à créer vos schémas dans Adobe Experience Platform. documenter vos cas d’utilisation professionnels, comprendre votre licence Platform, connaître les barrières de sécurité du produit et identifier les données à ingérer avant de finaliser votre modèle de données. |
| Juin 2021 | [Tableau](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/psql-client-tableau.html) | Vidéo | Découvrez comment vous connecter à [!UICONTROL Query Service] à partir de diverses applications clientes de bureau qui prennent en charge le protocole `PostgreSQL` et comment utiliser les outils et les pilotes `PostgreSQL` pour connecter et écrire des requêtes. |
| Juin 2021 | [Fonctions définies par l’Adobe](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/adobe-defined-functions.html) | Vidéo | Découvrez comment utiliser des fonctions définies par l’Adobe dans Adobe Experience Platform [!UICONTROL Query Service] pour exécuter des tâches commerciales courantes sur les données d’événement d’expérience. |
| Juin 2021 | [Exploration des données](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/explore-data.html) | Vidéo | Découvrez comment valider les données ingérées, prévisualiser les données et explorer les propriétés statistiques et analytiques des données à l’aide des fonctions SQL. |
| Juin 2021 | [Présentation de Query Service](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/understanding-query-service.html) | Vidéo | Découvrez Query Service dans Adobe Experience Platform et comment il permet de comprendre le comportement des clients et de générer des informations pertinentes. |
| Juin 2021 | [Présentation de l’interface utilisateur de Query Service](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-ui.html) | Vidéo | Découvrez comment écrire et exécuter des requêtes, afficher des requêtes précédemment exécutées et accéder à des requêtes enregistrées par d’autres utilisateurs au sein de votre organisation IMS dans Adobe Experience Platform Query Service. |
| Juin 2021 | [Query API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-api.html) | Vidéo | Découvrez comment écrire et exécuter des requêtes, créer des requêtes de planification et créer un modèle de requête à l’aide de l’[!UICONTROL API Query Service] Adobe Experience Platform. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Utilisez Experience Platform pour orchestrer le parcours d’un client à l’échelle sur les canaux d’expérience, en anticipant intelligemment les besoins de chaque individu en temps réel.

* Mise à jour : juin 2021 - [Notes de mise à jour du Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=fr)

**Ressources supplémentaires pour Journey Orchestration**

[Documentation](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) - [Tutoriels vidéos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=fr)

## ![Icône](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] est un service applicatif intégré à Adobe Experience Platform. Utilisez [!UICONTROL Offer Decisioning] pour offrir à vos clients la meilleure offre et la meilleure expérience possible à tous les points de contact au bon moment.

* Mise à jour en avril 2021 - [Notes de mise à jour de l’Offer decisioning](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=fr#new)

**Plus de ressources pour Offer Decisioning**

[Documentation](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new) - [Tutoriels vidéos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=fr)

## ![Icône](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Date de publication : **17 juin 2021**

* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features)
* [Nouvelles fonctionnalités dans Customer Journey Analytics](#cust-journey)
* [Correctifs dans Adobe Analytics](#aa-fixes)
* [Avis importants pour les administrateurs d’Analytics](#aa-notices)
* [Cours et tutoriels pour Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

| Fonctionnalité | [Disponibilité générale](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=fr) - Date cible | Description |
| ----------- | ---------- | ------- |
| S.O. | S.O. |

{style=&quot;table-layout:auto&quot;}

### Nouvelles fonctionnalités dans Customer Journey Analytics {#cust-journey}

| Fonctionnalité | [Disponibilité générale](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) - Date cible | Description |
| ----------- | ---------- | ----- |
| S.O. | S.O. |

{style=&quot;table-layout:auto&quot;}

### Correctifs dans Adobe Analytics {#aa-fixes}

* Correction d’un problème en raison duquel une devise incorrecte s’affichait dans le rapport Temps réel du chiffre d’affaires. (AN-254649)
* Mise à jour de la documentation sur le [respect de la casse en eVar dans les rapports](https://experienceleague.adobe.com/docs/analytics/components/dimensions/evar.html). (AN-246438)
* Mise à jour de la documentation afin de mieux expliquer [l’ implémentation des flux de données](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/create-feed.html) et [ici](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/df-faq.html#BucketOwnerFullControl). (AN-219485)
* Correction de problèmes en raison desquels certaines données n’étaient pas envoyées dans le rapport du Data Warehouse (AN-259951) ; AN-259712; AN-260107; AN-259953)

#### Correctifs supplémentaires dans Adobe Analytics ou CJA

AN-246344; AN-250035; AN-250354; AN-252482; AN-254661; AN-254965; AN-255424; AN-256515; AN-257232; AN-257572; AN-257893; AN-258393; AN-259203; AN-259513; AN-259614; AN-259665; AN-259931; AN-260074; AN-260085; AN-260147; AN-260190; AN-260198; AN-260290; AN-260306 (CJA); AN-260508; AN-260625; AN-260793; AN-260861; AN-260938; AN-260945; AN-261149; AN-261317

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| ----------- | ---------- | ---------- |
| Les agents utilisateur du navigateur reflètent des versions de système dʼexploitation incorrectes pour macOS. | 19 mai 2021 | Actuellement, tous les navigateurs principaux signalent de manière incorrecte les utilisateurs de macOS X 11 et versions ultérieures comme utilisant macOS 10, tel quʼil est enregistré dans la chaîne de lʼagent utilisateur du navigateur. Ce problème a une incidence sur la création de rapports dʼAdobe Analytics, car ce dernier utilise lʼagent utilisateur pour déterminer les informations sur les appareils, telles que le système dʼexploitation. Cette inexactitude semble avoir été mise en place afin d’éviter des problèmes de compatibilité pour certains sites Web. Voir ce [ticket Bugzilla](https://bugs.webkit.org/show_bug.cgi?id=213622&amp;utm_source=convertkit&amp;utm_medium=email&amp;utm_campaign=User+Agent+strings%2C+new+BigQuery+features%2C+custom+Google+Tag+Manager+loader...+%E2%80%93+Simmer+Newsletter+%2311%20-%205873454) pour référence. Il n’est pas clair quand ou si ce problème sera corrigé.<br>Certains navigateurs ont dʼabord enregistré macOS 11 correctement, il se peut donc quʼil y ait un certain trafic correspondant à cette valeur. Toutefois, en raison de la création de rapports inexacte, le filtrage pour le système dʼexploitation macOS 11 nʼest pas utile.<br>Ce problème revêt un caractère important, car à partir de Safari sur macOS 11, Apple a mis à jour les limites dʼexpiration des cookies ITP pour sʼappliquer aux implémentations CNAME (voir [la publication de blog WebKit](https://webkit.org/blog/11338/cname-cloaking-and-bounce-tracking-defense/)).<br>Avant cette mise à jour, ces limites sʼappliquaient uniquement aux cookies côté client définis via JavaScript. Cette inexactitude rend difficile lʼévaluation du volume de trafic utilisant macOS 11 et est donc impactée par le changement ITP. Pour en savoir plus sur les cookies et Adobe Analytics, cliquez [ici](https://experienceleague.adobe.com/docs/analytics/technotes/cookies/cookies.html?lang=fr#cookies). |
| Fin de vie de trois services d’API Analytics | 19 mai 2021 | Le 18 août 2021, les services d’API hérités d’Analytics suivants ont atteint leur date de fin de vie et ont été fermés. Les intégrations actuelles créées à l’aide de ces services ont cessé de fonctionner ce jour-là.<ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Adobe a mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte dʼintégration [Adobe I/O](https://console.adobe.io/home?mv=email#) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Mises à jour des zones géographiques ISO 2021 | 13 mai 2021 | Adobe a effectué des mises à jour des zones géographiques ISO 2021 le 21 mai 2021. Attendez-vous à voir des mises à jour mineures après cette version. |
| Fin de vie des sources de données à traitement complet | 12 avril 2021 | Le 31 juillet 2021, Adobe prévoit dʼabandonner les sources de données à traitement complet. À partir du 25 mars 2021, il ne sera plus possible de créer de nouvelles importations de ce type. Utilisez lʼ[API dʼinsertion de données en masse](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) pour importer ce type de données. |
| Mise à jour de la connexion à [!UICONTROL Report Builder] | 9 avril 2021 | Le 14 janvier 2021, les mises à jour de connexion à [!UICONTROL Report Builder] ont supprimé les dépendances aux technologies héritées et aligné le processus de connexion avec Experience Cloud. Experience Cloud utilise votre Enterprise ID (email et mot de passe). Pour garantir un accès ininterrompu à [!UICONTROL Report Builder], mettez à jour le complément externe [!UICONTROL Report Builder] vers la version 5.6.47 ou une version ultérieure d’ici le 22 juillet 2021. Les versions 5.6.47 et ultérieures de Report Builder prennent uniquement en charge la connexion à Experience Cloud et ne prennent pas en charge lʼauthentification unique (SSO). |
| Modifications des adresses IP de Data Warehouse et du flux de données | 6 avril 2021 | À compter du 17 juin, les flux de données et le système de diffusion de Data Warehouse seront déplacés dans lescentres de données d’Adobe. Par conséquent, cela peut provoquer un changement d’adresses IP externes visibles de votre côté. Adobe vous recommande de confirmer que tous les blocs CIDR IP du centre de données d’où proviennent vos rapports et vos flux sont présents dans les pare-feux, et ce, pour chaque système de destination sous votre contrôle. [Voici une liste complète des plages dʼadresses IP à placer dans les listes autorisées de votre pare-feu](https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html?lang=fr#data-collection-and-ftp-ip-address-blocks). |
| Avis de modifications prochaines du menu Analytics | 24 mars 2021 | Le 22 avril 2021, Adobe a mis à jour les menus déroulants **[!UICONTROL Composants]**, **[!UICONTROL Outils]** et **[!UICONTROL Administrateur]** dans le but d’en améliorer les performances. Toutes ces pages restent disponibles sous les liens **[!UICONTROL Tous les composants]**, **[!UICONTROL Tous les outils]** et **[!UICONTROL Tous les administrateurs]**. Elles seront supprimées du menu déroulant. Voici les éléments de menu qui seront supprimés du menu déroulant et placés sur leur page de liens respective :<br><br> [!UICONTROL Composants]<ul><li>[!UICONTROL Signets]</li><li>[!UICONTROL Tableaux de bord]</li><li>[!UICONTROL Cibles]</li><li>[!UICONTROL Événements du calendrier]</li><li>[!UICONTROL Rapports planifiés]</li><li>[!UICONTROL Paramètres des rapports]</li></ul>Outils de <ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search&amp;Promote]</li></ul>[!UICONTROL Administration]<ul><li>[!UICONTROL Gestion des utilisateurs]</li><li>[!UICONTROL Importateur de classifications]</li><li>[!UICONTROL Créateur de règles de classification]</li><li>[!UICONTROL Sources de données]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL Paramètres de l’entreprise]</li><li>[!UICONTROL Journaux]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL Gestionnaire de code]</li><li>[!UICONTROL Exclure par adresse IP]</li><li>[!UICONTROL Gestion du trafic]</li></ul> |
| Traitement Same-as-SiteCatalyst VISTA ACTIVÉ | 17 mars 2021 | Le 17 juin 2021, toutes les suites de rapports seront mises à jour pour que le [!UICONTROL Traitement Same-as-SiteCatalyst VISTA] soit ACTIVÉ. Cette modification a un impact sur les rapports Data Warehouse en traitant les données en fonction des règles de traitement. Pour toute question ou clarification, contactez l’assistance clientèle. |
| Options de la landing page Reports &amp; Analytics | 19 février 2021 | Le 25 mars 2021, les options permettant de configurer de nouveaux tableaux de bord Reports &amp; Analytics ou dʼautres contenus tels que votre page de destination Adobe Analytics ont été supprimées. Si votre page de destination personnalisée a été précédemment définie en tant que page Reports &amp; Analytics, celle-ci continue à fonctionner jusquʼà ce que vous modifiez la page de destination dans les [!UICONTROL Préférences utilisateur]. |
| Fin de vie des Data Connectors Adobe | 13 juillet 2020 | Les [!UICONTROL Data Connectors] Adobe sont alimentés par une technologie héritée qui n’est plus viable ni prise en charge. Une nouvelle norme est disponible dans le [Programme Partenaires Adobe Exchange](https://partners.adobe.com/exchangeprogram/experiencecloud). Vous pouvez utiliser cette norme pour prolonger l’offre et la prise en charge de toute intégration. La date de fin de vie officielle est fixée au 1er août 2021. [En savoir plus...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=fr) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Pour connaître les dernières mises à jour des versions d’AppMeasurement, reportez-vous aux [notes de mise à jour d’AppMeasurement pour JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=fr).

### Nouveaux cours et tutoriels pour Analytics {#tutorials-analytics}

Nouveaux cours, tutoriels et articles dans [!DNL Analytics] et [!UICONTROL Customer Journey Analytics].

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Juin 2021 | [Prise en main de Customer Journey Analytics pour les administrateurs](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Cours | Découvrez comment configurer, configurer et administrer Customer Journey Analytics. Découvrez quelques concepts de base pour vous donner une base, puis passez à d’autres étapes de configuration. Le cours est ensuite plafonné avec certaines recommandations sur la migration des mesures calculées et des segments d’Adobe Analytics vers Customer Journey Analytics. |
| Juin 2021 | [Configuration des rapports de recherche interne au site](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/configure-internal-site-search-reports.html?lang=en) | Vidéo | Créez et configurez des tableaux à structure libre dans Analysis Workspace afin d’analyser la fonctionnalité de recherche interne de votre site. |
| Juin 2021 | [Mise en correspondance de variables SDK Web dans Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/map-web-sdk-variables-into-adobe-analytics.html?lang=en) | Vidéo | Découvrez comment mapper des variables d’analyse du SDK Web à Adobe Analytics à l’aide de règles de traitement. |
| Juin 2021 | [Mise en œuvre de variables de recherche interne à lʼaide du SDK Web](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-web-sdk.html?lang=en) | Vidéo | Découvrez comment utiliser le SDK Web pour implémenter des variables Adobe Analytics pour un cas d’utilisation du suivi des termes de recherche interne. Voir le flux de données de la page vers Experience Edge, puis vers Adobe Analytics. |
| Juin 2021 | [Mise en œuvre de variables de recherche interne à lʼaide dʼAppMeasurement](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-appmeasurement.html?lang=en) | Vidéo | Dans cette vidéo, découvrez les étapes de la mise en oeuvre de variables de recherche de site interne pour Adobe Analytics à l’aide de la collecte/du lancement de données Experience Platform, y compris le terme de recherche, le nombre de résultats, etc. |
| Juin 2021 | [Définition des besoins de votre entreprise en matière de recherche interne au site](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/defining-your-internal-site-search-business-requirements.html?lang=en) | Vidéo | Lorsque vous décidez de suivre la recherche interne sur votre site, il est important de commencer par déterminer les aspects de la recherche dont vous souhaitez effectuer le suivi et les mesures à prendre dans l’analyse des résultats. Cette vidéo décrit les besoins de l’entreprise. |

{style=&quot;table-layout:auto&quot;}

### Ressources d’aide à propos d’Analytics

* [Documentation et tutoriels du produit Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=fr)

## ![Icône](/assets/audience-manager.png) Audience Manager {#aam}

Correctifs et améliorations d’Audience Manager.

### Correctifs et améliorations {#aam-fixes-and-improvements}

* Amélioration apportée au [rapport Utilisation de l’activité](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/activity-usage-reporting.html?lang=en) qui permet désormais d’examiner les données datant de plus d’un an. (AAM-58268)
* Adobe fournit aux clients Audience Manager des clés d’accès utilisateur pour les compartiments Amazon S3 d’Audience Manager. Pour des raisons de sécurité, les clés sont désormais automatiquement désactivées après 100 jours d’inactivité. Pour plus d’informations, reportez-vous à la question située au bas de la page dans la [FAQ sur la collecte de données et l’intégration de produits](https://experienceleague.adobe.com/docs/audience-manager/user-guide/faqs/faq-data-collection.html?lang=en).

## ![Icône](/assets/aem.png) Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour  Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

>[!NOTE]
>
>Adobe recommande de consulter la page des [mises à jour et feuilles de route Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=fr) afin de se tenir au courant des informations de mise à jour.

### Mises à jour des produits Experience Manager

* **Experience Manager 6.5.9.0**

   Experience Manager 6.5, Service Pack 9.0 (6.5.9.0 publiée le 27 mai 2021) est une mise à jour importante qui inclut de nouvelles fonctionnalités, des améliorations importantes demandées par les clients, une amélioration des performances, de la stabilité et de la sécurité, publiées depuis la disponibilité générale d’AEM 6.5, avril 2019.

   * [Notes de mise à jour](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=fr)
   * [Livrables de la mise à jour d’AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=en)

### Versions de produits Experience Manager

* **Experience Manager as a Cloud Service**

   Nouvelles fonctionnalités dans Experience Manager as a Cloud Service:

   * **Adobe Experience Manager as a Cloud Service Foundation**

      * [Canal de version préliminaire](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/prerelease.html?lang=en) : Prévisualisez les fonctionnalités à venir un mois avant qu’elles ne soient mises en production !
      * [Obsolescence](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/deprecated-apis.html?lang=en) des API : Liste des dernières API obsolètes.
      * [Module externe Maven Experience Manager as a Cloud Service SDK Build Analyzer](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=en) : Mettez à jour vos projets Maven vers la dernière version, qui inclut une vérification d’API Java™ obsolète et d’autres améliorations.
   * **Experience Manager Sites as a Cloud Service**

      Vous pouvez désormais vérifier le contenu d’un nouveau [niveau d’aperçu](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/previewing-content.html?lang=en) pour simuler l’aspect final de l’expérience comme vous le feriez sur le niveau Publication. Cette nouvelle fonctionnalité est activée par l’assistant de publication gérée de sites Experience Manager, qui vous permet de choisir une destination de publication entre [!UICONTROL Publier] ou [!UICONTROL Aperçu]. Les expériences sur [!UICONTROL Aperçu] sont ensuite accessibles via une URL dédiée. Après la validation sur [!UICONTROL Aperçu], vous pouvez publier le contenu de [!UICONTROL Auteur] vers [!UICONTROL Publier] comme vous le faites habituellement. L’activation du service [!UICONTROL Aperçu] dans les environnements Experience Manager as a Cloud Service se déploie progressivement au cours des prochaines semaines.

   * **Experience Manager Assets as a Cloud Service**

      Nouvelles fonctionnalités du canal de version préliminaire :

      * Les schémas de métadonnées peuvent être appliqués directement aux propriétés du dossier.
      * L’outil [!UICONTROL Asset Bulk Ingestor] permet d’ajouter des métadonnées lors d’une ingestion en masse.
      * Une amélioration de l’expérience utilisateur affiche le nombre de ressources présentes dans un dossier. Pour plus de 1 000 ressources dans un dossier, Experience Manager Assets affiche plus de 1 000 ressources.

      Nouvelles fonctionnalités de [!UICONTROL Dynamic Media] :

      * Le rapport de pixels d’appareil d’imagerie dynamique (RPD) et l’optimisation de la bande passante du réseau vous permettent de fournir des images de meilleure qualité de manière efficace, sur les appareils avec des affichages haute résolution et une bande passante réseau limitée. Voir [FAQ sur l’imagerie dynamique](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/dynamicmedia/imaging-faq.html?lang=en).



### **Communauté Experience Manager**

* [Un guichet unique pour tous les blogs Experience Manager](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

* [Instructions relatives à l’envoi d’une nouvelle idée de Experience Manager](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/guidelines-for-submitting-a-new-experience-manager-aem-idea/td-p/382376)

* [Adobe Summit 2021 s&#39;emballe avec Dan Levy](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-sneaks-with-dan-levy/td-p/405865) : Une fois par an, chaque employé d’Adobe, qu’il s’agisse d’ingénieurs et de spécialistes des données, de concepteurs d’expérience utilisateur ou de chefs de produits, a la possibilité de partager des idées innovantes afin d’élaborer la manière dont les marques interagissent avec leurs clients. Rejoignez-nous pour Adobe Sneaks, où nous partageons les sept premiers projets, exploitant les dernières technologies dans des domaines comme l&#39;IA et les applications à faible code.

### Informations de mise à jour d’Experience Manager

Toutes les notes de mise à jour d’Experience Manager sont conservées dans les pages suivantes :

* [Informations de mise à jour d’Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [Notes de mise à jour de Cloud Manager d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=fr)
* [Notes de mise à jour du service de conversion automatisée de formulaires](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Notes de mise à jour du Service Pack 6.5 d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Notes de mise à jour du pack de correctifs cumulatifs 6.4 d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=fr)
* [Notes de mise à jour de l’appli de bureau Experience Manager ](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Notes de mise à jour d’Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=fr)
* [Notes de mise à jour de Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=fr)

### Nouveaux cours et tutoriels sur Experience Manager {#tutorials-aem}

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Juin 2021 | [Mise en oeuvre des méthodes de l’interface](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/implement-interface.html?lang=en) | Article | Découvrez comment mettre en oeuvre les méthodes d’interface pour créer des fichiers PDF à l’aide de l’API REST Document Cloud. |
| Juin 2021 | [Création d’une interface de service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-interface.html) | Article | Définissez les méthodes de l’interface que vous souhaitez afficher. |
| Juin 2021 | [Création d’une configuration OSGi personnalisée](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-doc-cloud-configuration.html?lang=en) | Article | Découvrez la configuration OSGi personnalisée afin de pouvoir capturer les détails du projet d’Adobe I/O. |
| Juin 2021 | [Création de Content Analyzer](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/get-content-analyzer.html?lang=en) | Article | Découvrez comment créer la partie JSON contenant les informations sur les paramètres d’entrée de l’appel REST Create PDF. |
| Juin 2021 | [Créer une étape de processus personnalisée](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/custom-process-step.html?lang=en) | Article | Affichez le code complet de l’étape de processus personnalisée qui convertit et remplace les fichiers natifs par les fichiers PDF convertis. Cette étape personnalisée recherche toutes les pièces jointes sous le nom du dossier, fourni comme argument de processus dans le workflow. Cette étape de processus personnalisée utilise les méthodes de la balise `DocumentCloudSDKService` personnalisée pour créer des fichiers PDF. |
| Juin 2021 | [Requêtes persistantes GraphQL](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/graphql-persisted-queries.html?lang=en) | Vidéo | Découvrez comment activer, créer, mettre à jour et exécuter des requêtes persistantes dans Experience Manager. |
| Juin 2021 | [Création de votre premier servlet dans AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-servlet.html?lang=en) | Article | Créez votre première servlet Sling afin de pouvoir fusionner des données avec un modèle de formulaire. |
| Juin 2021 | [Création de votre premier service OSGi avec des formulaires de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-osgi-service.html?lang=en) | Article | Créez votre premier service OSGi avec AEM Forms afin de pouvoir générer un fichier PDF en fusionnant les données avec un modèle. |

{style=&quot;table-layout:auto&quot;}

### Autres ressources dʼaide pour Experience Manager

* [Guides relatifs à Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.3](https://helpx.adobe.com/fr/support/experience-manager/6-3.html)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=fr#previous-updates)
* [Versions plus anciennes de la documentation pour Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Guide de l’utilisateur de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=fr)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=fr)
* [Documentation Experience Manager : mises à jour récentes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=fr#aem-as-a-cloud-service)

## ![Icône](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Dernières mises à jour du produit

Pour en savoir plus sur les dernières fonctionnalités, améliorations et correctifs disponibles :

* **Nouvelle version d’Adobe Campaign v8**  avec des améliorations importantes en termes d’infrastructure, de sécurité, de délivrabilité et de surveillance. En utilisant [!DNL Snowflake], une technologie de base de données cloud, Adobe Campaign améliore considérablement son échelle et sa vitesse, avec la possibilité de gérer un nombre plus important de profils clients, ainsi que des taux de diffusion et des transactions beaucoup plus élevés par heure. Pour en savoir plus, consultez la [documentation de Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html).

* **Version** de Adobe Campaign Classic v7 21.1.3 : Pour en savoir plus, consultez les  [Notes de mise à jour de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html).

* **Adobe Campaign Standard version 21.2** : Pour en savoir plus, consultez les Notes de mise à jour du  [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html).

### Nouveaux [!UICONTROL cours et tutoriels Campaign] {#tutorials-campaign}

| Publication | Nom | Solution | Description |
| -----------| ---------- | ---------- | ---------- |
| Juin 2021 | [Intégrer Campaign Standard à Analytics pour optimiser le marketing par e-mail](https://experienceleague.adobe.com/?lang=fr#dashboard/learning) | Campaign Standard | (Cours) Découvrez comment intégrer Campaign Standard à Adobe Analytics et optimiser vos stratégies de marketing par e-mail à l’aide de données en temps réel. Ce cours explique comment créer un rapport Campaign Standard dans Adobe Analytics. Ensuite, découvrez comment utiliser Experience Cloud Triggers et Platform Launch pour configurer les messages marketing et transactionnels en fonction de l’activité du clien |
| Juin 2021 | [Tutoriels sur Adobe Campaign V8](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html) | Campaign V8 | Ce guide de l&#39;utilisateur contient des vidéos et des tutoriels sur les nombreuses fonctionnalités d&#39;Adobe Campaign V8. |
| Juin 2021 | [Création et conception de diffusions Email](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/content-creation/email/create-and-design-email-deliveries.html) | Campaign V8 | (Vidéo) Découvrez le processus de création d’une diffusion email et comment concevoir et personnaliser le contenu d’un email. |
| Juin 2021 | [Conception d’emails pour la délivrabilité](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/email/design-emails-for-deliverability.html) | Campaign V8 | (Vidéo) Découvrez comment appliquer les bonnes pratiques de délivrabilité à vos diffusions email. |
| Juin 2021 | [Gestion de la fatigue à l’aide de règles de typologie](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/typology-rules-for-fatigue-management.html) | Campaign V8 | (Vidéo) Découvrez comment implémenter la gestion de la fatigue en appliquant des règles de typologie. |
| Juin 2021 | [Configuration de la gestion de la fatigue à l’aide de filtres](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/fatigue-management-using-filters.html) | Campaign Standard | (Vidéo) Découvrez comment implémenter la gestion de la fatigue dans Adobe Campaign à l’aide de filtres. |

{style=&quot;table-layout:auto&quot;}

### Ressources d’aide pour Campaign

* Adobe Campaign Standard : [Centre d’aide](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=fr) - [Calendrier des versions](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=fr)
* Adobe Campaign Classic : [Centre d’aide](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=en) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=fr)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - Tutoriels vidéo pour [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=fr) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=fr)

## ![Icône](/assets/advertising-cloud.png) Advertising {#adcloud}

Notes de mise à jour dʼ[!DNL Adobe Advertising].

* [Nouvelles fonctionnalités dans Advertising DSP](#adcloud-dsp)
* [Nouvelles fonctionnalités dans Advertising Search](#adcloud-search)

### Nouvelles fonctionnalités d’[!DNL Advertising DSP] {#adcloud-dsp}

Dernière mise à jour : **10 juin 2021 pour la version du 16 juin**

| Fonctionnalité | Description |
| -----------| ---------- |
| Gestion de campagne | (Version du 16 juin) Les prévisions sont disponibles pour les placements d’affichage standard avec plages et budgets de niveau placement. |

{style=&quot;table-layout:auto&quot;}

### Nouvelles fonctionnalités d’[!DNL Advertising Search] {#adcloud-search}

Dernière mise à jour : **19 mai 2021, pour la version du 18 mai**

| Fonctionnalité | Description |
| -----------| ---------- |
| [!UICONTROL Centre de notifications Beta] | Le [!UICONTROL Centre de notifications Beta] est accessible à tous les utilisateurs. Utilisez-le pour vous abonner aux notifications Web et par e-mail concernant les erreurs d’authentification du compte, les alertes personnalisées déclenchées et l’achèvement des [!UICONTROL statistiques publicitaires] que vous générez.<br>Vous pouvez afficher vos notifications depuis :<ul><li>Le panneau [!UICONTROL Notifications] qui s’ouvre à partir du lien Notifications situé en haut à droite de n’importe quelle page.</li><li>Le [!UICONTROL Centre de notifications] à [!UICONTROL Statistiques et rapports > Centre de notifications Beta].</li></ul><br><b>Remarque :</b> en raison des améliorations apportées au stockage des notifications, toutes les notifications existantes ont été effacées. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/magento.png) [!DNL Magento] {#magento}

Voir les [notes de mise à jour](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) de Magento Commerce et d’Open Source pour obtenir les informations les plus récentes.

## ![Icône](/assets/target.png)[!DNL Target] {#target}

Voir les [[!DNL Target] notes de mise à jour](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=fr) pour consulter les informations les plus récentes.

## ![Icône](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] est une application complète pour la gestion des leads et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en s’engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Voir [!DNL Marketo Engage] [calendrier des versions](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) pour consulter les informations les plus récentes sur le calendrier des versions et les notes de mise à jour.

## ![Icône](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] est une application de gestion du travail unifiée qui permet de partager des idées, de créer du contenu, de gérer des processus complexes et de faire de leur mieux.

Consultez la page [[!DNL Workfront] versions](https://one.workfront.com/s/product-releases) pour obtenir un récapitulatif des dernières informations relatives à tous les produits.

## ![Icône](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Document Cloud.

### Cours et tutoriels de Document Cloud {#tutorials-doc-cloud}

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Juin 2021 | [Adobe Acrobat pour Google Drive](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/acrobatandgoogle.html) | Vidéo | Accédez aux outils PDF peu coûteux et aux processus de signature électronique directement dans l’application Google Drive. |

{style=&quot;table-layout:auto&quot;}

Pour obtenir de l’aide sur Document Cloud, voir :

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=fr)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=fr)
* [Formation et assistance pour Document Cloud](https://helpx.adobe.com/fr/support/document-cloud.html)

## ![Icône](/assets/creative-cloud-24.png) Creative Cloud abonnement Entreprise {#creative-cloud}

| Publication | Nom | Type | Description |
| ----------| --------- | --------- | --------- |
| Juin 2021 | [Essayez le Fresco sur l’iPad (et l’iPhone).](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html) | Vidéo | Découvrez un tout nouveau monde de dessin et de peinture numériques avec Adobe Fresco dans cet atelier pratique de 15 minutes. Apprenez rapidement à utiliser des calques et des masques de détourage pour intégrer de la peinture et des textures à une forme de base. |
| Juin 2021 | [Décodage de la soupe alpha des formats graphiques](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html) | Vidéo | Les fichiers PG, PNG, SVG, GIF et EPS sont généralement utilisés dans la conception, certains pour des pages web, d’autres pour des présentations, des publications et des projets créatifs. Mais... qu&#39;est-ce qu&#39;ils veulent dire, et que devrais-tu choisir ? Découvrez cet atelier pratique de 15 minutes. |

{style=&quot;table-layout:auto&quot;}

Voir [les tutoriels Creative Cloud for Enterprise](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=fr) pour consulter les derniers tutoriels.

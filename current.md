---
title: Dernières notes de mise à jour
description: Découvrez les dernières notes de mise à jour, les nouvelles fonctionnalités et la nouvelle documentation des produits et services  [!DNL Experience Cloud] . Recherchez de nouvelles aide et des tutoriels sur  [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: bee65444e8ef1c12779c991fa9e199d93b8028f0
workflow-type: tm+mt
source-wordcount: '5361'
ht-degree: 39%

---

# Notes de mise à jour d’Adobe Experience Cloud - Octobre 2021

![Bannière](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud]Les applications et les services sont mis à jour chaque mois. Cette page est votre destination de référence lorsque vous recherchez les dernières mises à jour, la documentation et les tutoriels pour [!DNL Experience Cloud] et [!DNL Experience Platform]. Vous trouverez également de nouvelles documentations pour [!DNL Creative Cloud for enterprise] et [!DNL Document Cloud].

>[!NOTE]
>
>Abonnez-vous à la [mise à jour produit prioritaire d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) pour recevoir chaque mois des notifications par email concernant les mises à jour de cette page. Cette page est tenue à jour tout au long du mois. Par conséquent, veuillez consulter régulièrement les mises à jour des produits Adobe Enterprise et de la documentation Experience League.

Dernière mise à jour : **4 octobre 2021**

* [[!DNL Experience League] Événements en direct](#events)
* [[!DNL Experience Cloud Central Interface Components] &amp; Administration](#ecloud)
* [[!UICONTROL Statut du système] Adobe](#status)
* [[!DNL Adobe Analytics]](#analytics) et [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

Besoin d’aide ? Consultez [Adobe Experience League](https://experienceleague.adobe.com/?lang=fr#home) pour trouver de la documentation technique et sur les produits, des cours préparés par Adobe, des tutoriels vidéo, des réponses rapides, des informations provenant de la communauté et des formations dispensées par un instructeur.

## ![Icône](/assets/experience-league.png) [!DNL Experience League] Événements en direct {#events}

[!DNL Experience League] Les événements en direct sont des discussions avec des experts d’Adobe et des invités spéciaux qui sont essentiels pour vous apporter la technologie d’Adobe. Consultez le planning suivant et rejoignez-nous en direct ou regardez les événements enregistrés précédemment.

| Date de l’événement | Heure | Nom de l’événement | Type | Description |
| -----------| ---------- | ---------- | ---------- |---------- |
| 21 octobre 2021 | 12 heures (EST) | [Qui a cliqué là-dessus ? Création de rapports avancés sur les clics sur les liens avec Adobe Analytics](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) | Événement vidéo en direct | La création de rapports sur l’interaction de l’utilisateur avec votre propriété web ou mobile est un élément essentiel pour comprendre le parcours de votre client. Avec Adobe Analytics, vous pouvez comprendre qui, quoi, pourquoi et où de chaque clic dans votre application. Découvrez les conseils des experts d’Adobe Analytics sur l’utilisation des classifications de Activity Map et de l’attribution personnalisée pour mieux comprendre l’engagement des utilisateurs. |
| 23 septembre 2021 | À la demande | [Conseils d’experts pour que vos campagnes de vacances se démarquent](https://www.youtube.com/watch?v=bsU1lAv0xes) | Événement vidéo en direct | Comme il n’est jamais trop tôt pour commencer vos achats de vacances, il n’est jamais trop tôt non plus pour commencer à planifier une campagne marketing à succès pour les vacances. Avec Adobe Campaign, vous pouvez concevoir, planifier et exécuter des campagnes qui réalisent tous les vœux de vacances de votre entreprise.<br>Mais connaissez-vous tous les conseils pour exécuter des campagnes qui se terminent l&#39;année par un big ? Rejoignez Sandra pour une discussion en direct avec trois experts d&#39;Adobe qui ont des tonnes d&#39;expertise collective dans ce domaine. |
| 26 août 2021 | À la demande | [Rendez votre prochain segment ciblé plus smart que jamais](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=fr) | Enregistrement d’événement | Le succès de chaque bonne campagne marketing dépend du ciblage précis de votre audience. Avec le nouveau [!UICONTROL créateur de segments] d’Adobe Experience Platform, vous pouvez créer votre prochain segment d’audience à l’aide des données de profil et du comportement temporel des utilisateurs sur l’ensemble des canaux. Il n’existe pas meilleur moyen de s’assurer que vos messages parviennent aux personnes qui ont le plus besoin de les entendre. |
| 29 juillet 2021 | À la demande | [Mes trois meilleurs conseils de mise en œuvre d’Adobe Analytics](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=fr) | Enregistrement d’événement | Vous l’avez vu sur scène au cours de l’Adobe Summit. Vous l’avez entendu partager des conseils d’expert à Adobe Insider Tours. Vous avez peut-être même eu l’honneur de travailler avec lui sur votre propre mise en œuvre d’Adobe Analytics. Eric Matisoff apporte ses trois conseils préférés de mise en œuvre d’Adobe Analytics à cette discussion exclusive en direct sur Experience League. |

{style=&quot;table-layout:auto&quot;}

Pour visionner d’autres vidéos, rendez-vous sur la [chaîne YouTube d’Adobe Experience League](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw).

## ![Icône](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] et Administration {#ecloud}

| Fonctionnalité | Description |
| ------- | ------- |
| Recherche unifiée | La recherche unifiée continue à ajouter des types d’objets à l’index de recherche. Dans cette mise à jour, la recherche globale effectue désormais des recherches dans le contenu Experience League et les types d’objets Journey Optimizer suivants : <ul><li>Jeux de données</li><li>Destinations </li><li>Requêtes</li><li>Schémas</li><li>Segments</li><li>Sources</li><li>Offres</li><li>Composants</li><li>Messages</li><li>Parcours</li></ul> |
| Consentement des données d’utilisation du produit | Lors d’une première connexion, vous êtes invité à envoyer des préférences sur la manière dont Adobe peut vous fournir du contenu personnalisé utile, tel que des tutoriels, des guides, des conseils rapides, des recommandations, des vidéos d’apprentissage, etc., en fonction des données d’utilisation de vos produits Experience Cloud. Cette requête inclut également une mise à jour de vos préférences pour la collecte et l’utilisation de ces données à l’adresse <https://experience.adobe.com/preferences>. |
| Navigation Experience Cloud [!UICONTROL Triggers] | [Experience Cloud ](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) Triggersis disponible pour la navigation directe à partir du sélecteur d’applications dans l’en-tête des utilisateurs configurés. |
| **Remarque :** Mise à jour planifiée de la navigation dans l’interface | En novembre 2021, la fonction de navigation _[!UICONTROL Aller à Launch / Collecte de données]_ sera supprimée de <https://experience.adobe.com/implement>. |

{style=&quot;table-layout:auto&quot;}

**Plus de ressources d’aide sur [!DNL Experience Cloud Central UI Components] et Administration**

* Aide dʼadministration pour les [Composants de lʼinterface centrale](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=fr) et la gestion des utilisateurs
* Aide et notes de mise à jour pour le [service Places - Emplacement](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=fr)
* Aide sur [Personnes - Attributs du client et Bibliothèque dʼaudiences](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Icône](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] fournit des informations détaillées, des mises à jour de statut et des notifications par e-mail relatives aux produits Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

(Recherchez les informations de mise à jour les plus récentes pour [!DNL Adobe System Status] dans les Notes de mise à jour du [21 mai 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=fr).)

## ![Icône](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Date de publication : **7 octobre 2021**

* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features)
* [Nouvelles fonctionnalités dans Customer Journey Analytics](#cust-journey)
* [Correctifs dans Adobe Analytics](#aa-fixes)
* [Avis importants pour les administrateurs d’Analytics](#aa-notices)
* [Cours et tutoriels pour Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

| Fonctionnalité | Description | [Disponibilité générale](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=fr) - Date cible |
| ----------- | ---------- | ------- |
| Visualisations pour les tableaux de bord Analytics | Les [!UICONTROL tableaux de bord] d’Analytics présentent trois nouvelles visualisations pour permettre aux cadres et aux décideurs de mieux comprendre leurs données en un coup d’oeil. Les nouveaux graphiques à barres [!UICONTROL Doughnut], [!UICONTROL Line] et [!UICONTROL Horizontal] facilitent tous l’affichage des données pour des éléments de dimension individuels, sans avoir à ouvrir une vue de détails. (Lien vers la documentation à suivre) | 7 octobre 2021 |
| [!UICONTROL Temps passé sur la lecture du média] | Adobe de la lecture de médias en flux continu [!UICONTROL Durée de la visite] fournit des informations précieuses sur l’engagement des visiteurs et permet aux organisations multimédias d’obtenir des informations plus approfondies et plus granulaires avec un engagement de l’utilisateur minute par minute grâce à une analyse avancée de la durée de la visite avec des fonctionnalités de partage de journée. Vous pouvez observer le temps passé à visionner vos diffusions multimédia à un moment donné. Vous pouvez fractionner la durée de lecture selon différentes granularités, y compris de nouvelles granularités de 5, 15 et 30 minutes. [En savoir plus](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 18 octobre 2021 |
| [!UICONTROL Créateur de segments] rapide | Permet aux utilisateurs professionnels d’appliquer rapidement des segments de base dans un workflow de projet simplifié intégré. Il n’est pas nécessaire d’accéder au [!UICONTROL créateur de segments]. [En savoir plus](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 21 octobre 2021 |
| Améliorations de la recherche de rail de gauche dans Analysis Workspace | La recherche sur le rail de gauche (1) établit la priorité des correspondances exactes au-dessus des correspondances larges, en plus de continuer à tenir compte de la récence et de la pertinence des composants. 2) Il met en évidence les caractères correspondants afin de rendre les résultats de la recherche plus compréhensibles. 3) Il est plus facile de trouver des classifications liées à une dimension. 4) Enfin, il prend en charge la recherche par caractères génériques (`*`) pour trouver plus facilement des composants spécifiques dont vous avez besoin. Remarque : La recherche par caractères génériques ne fonctionne pas encore au niveau de l’élément de dimension. | 21 octobre 2021 |
| Thème sombre Analysis Workspace | Le thème sombre est disponible en tant qu’option d’affichage. | 21 octobre 2021 |

{style=&quot;table-layout:auto&quot;}

### Nouvelles fonctionnalités dans Customer Journey Analytics {#cust-journey}

| Fonctionnalité | Description | [Disponibilité générale](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - Date cible |
| ----------- | ---------- | ----- |
| Prise en charge des Reports Builder | Report Builder est un module complémentaire Microsoft® [!DNL Excel] qui vous permet de créer, modifier et actualiser facilement des rapports personnalisés à l’aide de données de Customer Journey Analytics. Avec Report Builder et Excel, vous pouvez utiliser l’interface utilisateur simple mais flexible de glisser-déposer pour créer facilement des requêtes de données complexes. Avec Report Builder pour Customer Journey Analytics, vous pouvez :<ul><li>Référencez les cellules de feuille de calcul existantes pour obtenir l’ordre de ligne, la période ou le filtre idéal.</li><li>Créer des dates personnalisées à l’aide de calendriers, de références de cellule ou de maths de date</li><li>Concevez vos tableaux et visualisations à l’aide d’outils de formatage familiers d’Excel.</li><li>Disponible sur macOS, Microsoft 365 pour le Web et Microsoft Windows</li></ul> | 7 octobre 2021 |
| Visualisations pour les tableaux de bord Analytics | Les [!UICONTROL tableaux de bord] d’Analytics présentent trois nouvelles visualisations pour offrir aux cadres et aux décideurs une compréhension encore plus rapide de leurs données. Les nouveaux graphiques à barres horizontales, en anneau et en courbes facilitent l’affichage des données pour les éléments de dimension individuels, sans avoir à ouvrir une vue de détails. (Lien vers la documentation à suivre) | 7 octobre 2021 |
| Journaux d’audit du Customer Journey Analytics (API uniquement) | Les journaux d’audit jouent un rôle important dans la conformité aux normes de sécurité et dans le contrôle des données et des actions des utilisateurs. | 7 octobre 2021 |
| Quick [!UICONTROL Filter Builder] | Permet aux utilisateurs professionnels d’appliquer rapidement des segments de base dans un workflow de projet simplifié intégré. Il n’est pas nécessaire d’accéder au [!UICONTROL Créateur de filtres]. [En savoir plus](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 21 octobre 2021 |
| Améliorations de la recherche de rail de gauche dans Analysis Workspace | La recherche sur le rail de gauche (1) établit la priorité des correspondances exactes au-dessus des correspondances larges, en plus de continuer à tenir compte de la récence et de la pertinence des composants. 2) Il met en évidence les caractères correspondants afin de rendre les résultats de la recherche plus compréhensibles. 3) Il est plus facile de trouver des classifications liées à une dimension. 4) Enfin, il prend en charge la recherche par caractères génériques (`*`) pour trouver plus facilement des composants spécifiques dont vous avez besoin. Remarque : La recherche par caractères génériques ne fonctionne pas encore au niveau de l’élément de dimension. | 21 octobre 2021 |
| Thème sombre Analysis Workspace | Le thème sombre est disponible en tant qu’option d’affichage. | 21 octobre 2021 |

{style=&quot;table-layout:auto&quot;}

### Correctifs dans Adobe Analytics et CJA {#aa-fixes}

* Correction d’une erreur de rapport planifié dans Customer Journey Analytics. (AN-271721)
* Correction de problèmes liés aux [!UICONTROL composants de recherche] dans [!UICONTROL Workspace] qui n’entraînaient pas de correspondances exactes. (AN-253937 ; AN-271707)

#### Correctifs supplémentaires dans Adobe Analytics

AN-256136; AN-265420; AN-268455; AN-269768; AN-270276; AN-270287; AN-271601; AN-271969; AN-272056; AN-272111; AN-272457

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Remarque | Date d’ajout ou de mise à jour | Description |
| ----------- | ---------- | ---------- |
| Fin de vie de trois services d’API Analytics | 16 septembre 2021 | Le **28 octobre 2021**, les services d’API hérités d’Analytics suivants atteindront leur date de fin de vie et seront fermés. Les intégrations actuelles créées à lʼaide de ces services cessent de fonctionner ce jour-là.<ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Adobe a mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte dʼintégration [Adobe I/O](https://developer.adobe.com/console) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Pour connaître les dernières mises à jour des versions d’AppMeasurement (version 2.22.2), reportez-vous aux [Notes de mise à jour d’AppMeasurement pour JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=fr).

### Cours et tutoriels pour Analytics {#tutorials-analytics}

Nouveaux cours, tutoriels et articles dans [!DNL Analytics] et [!UICONTROL Customer Journey Analytics].

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Octobre 2021 | [Utilisation des visualisations pour raconter vos histoires de données](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | Cours | Qui souhaite parcourir les tableaux les uns après les autres pour extraire des informations des données ? Pas vous ! Dans ce cours, découvrez les notions de base sur les visualisations, notamment comment les ajouter à un projet, y intégrer des données et ce que chaque visualisation peut vous montrer. Découvrez comment configurer les paramètres pour obtenir les données exactes dont vous avez besoin. Obtenez également quelques conseils et des cas d’utilisation pour vous aider à rendre les visualisations pratiques à votre analyse régulière. |

{style=&quot;table-layout:auto&quot;}

### Ressources d’aide à propos d’Analytics

* [Documentation et tutoriels du produit Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=fr)

## ![Icône](/assets/audience-manager.png) Audience Manager {#aam}

Nouvelles fonctionnalités dans Audience Manager - mise à jour **14 septembre 2021** :

| Fonctionnalité | Description |
| ------- | ------- |
| Consentement de la collecte de données des ID mobiles | Ajout de la prise en charge du consentement de la collecte de données d’ID mobiles. Pour bénéficier de cette mise à jour, les clients doivent effectuer la mise à niveau vers le [SDK AEP Mobile iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) ou une version ultérieure. |

## ![Icône](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Inclut des informations de mise à jour et une nouvelle documentation pour Experience Platform et [!UICONTROL SDK mobile].

**29 septembre 2021**

| Fonctionnalité | Description |
| ------- | ------- |
| [[!UICONTROL Zone d’entrée des données]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL Les ] zones d’entrée de données sont un  [!DNL Platform]magasin Blob   Azure Blob mis en service qui permet un stockage sécurisé et temporaire par environnement de test pour importer des fichiers dans Experience Platform. |
| Prise en charge des sources de diffusion pour la [préparation des données](https://www.adobe.com/go/monitor-streaming-dataflows-en) | Les sources en flux continu prennent désormais en charge la préparation des données, ce qui vous permet de fournir un schéma source JSON pour mapper des données source non compatibles avec XDM à un schéma XDM cible. |
| [Informations d’identification non expirées](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | Les informations d’identification non expirées pour les utilisateurs de [!UICONTROL Query Service] permettent des connexions plus permanentes aux clients externes au lieu de renouveler les informations d’identification toutes les 24 heures. |
| [[!UICONTROL SDK de destination]](https://www.adobe.com/go/destination-sdk-overview-en) | Utilisez [!UICONTROL SDK de destination] pour l’intégration à [!DNL Platform] et contribuer au catalogue de destinations en constante augmentation. L’accès à cette fonctionnalité est disponible uniquement pour les clients Activation Experience Platform. |

Voir les [Notes de mise à jour d’Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=fr) pour plus d’informations.

### Tutoriels et cours sur Experience Platform {#tutorials-platform}

Derniers tutoriels, vidéos ou cours publiés pour les Experience Platform et les services.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Octobre 2021 | [[!DNL Platform] Administration](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | Cours | Découvrez les activités d’administration pour Experience Platform, notamment la gestion des autorisations et des environnements de test. |

{style=&quot;table-layout:auto&quot;}

### SDK Adobe Mobile

Voir [Notes de mise à jour et journaux des modifications](https://aep-sdks.gitbook.io/docs/release-notes) pour les SDK Adobe Experience Platform Mobile.

## ![Icône](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

Découvrez les dernières fonctionnalités, améliorations et correctifs dans les [Notes de mise à jour de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=fr).

### Tutoriels et cours Journey Optimizer {#tutorials-ajo}

Derniers tutoriels Journey Optimizer :

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Octobre 2021 | [Configuration et gestion des données  [!DNL Journey Optimizer] pour les ingénieurs de données](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | Cours | Découvrez comment configurer et gérer les données requises pour la gestion des parcours dans Journey Optimizer. |
| Octobre 2021 | [Prise  [!DNL Journey Optimizer] en main pour les administrateurs et les gestionnaires de Parcours](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | Cours | Découvrez tout ce que vous devez savoir pour créer votre premier parcours. |
| Octobre 2021 | [ [!DNL Journey Optimizer] Configuration pour les administrateurs de Parcours](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | Cours | Comprendre l’architecture [!DNL Journey Optimizer] et les points d’intégration. Découvrez comment configurer [!DNL Journey Optimizer]. |

{style=&quot;table-layout:auto&quot;}

### Autres ressources pour [!DNL Journey Optimizer]

[Centre d’aide](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=fr)

## ![Icône](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Utilisez Experience Platform pour orchestrer le parcours dʼun client à lʼéchelle appropriée au sein de différents canaux dʼexpérience, en anticipant intelligemment les besoins de chacun en temps réel.

### Dernières [!DNL Journey Orchestration] versions du produit

Découvrez les dernières fonctionnalités, améliorations et correctifs dans les [[!DNL Journey Orchestration] Notes de mise à jour de ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=fr).

#### Autres ressources pour [!DNL Journey Orchestration]

[Centre d’aide](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=fr)

## ![Icône](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer ] Decisioning est un service intégré à Adobe Experience Platform. Utilisez [!UICONTROL Offer Decisioning] pour offrir à vos clients la meilleure offre et la meilleure expérience possible à tous les points de contact au bon moment.

### Dernières versions des produits Offer Decisioning

Découvrez les dernières fonctionnalités, améliorations et correctifs des [Notes de mise à jour de l’Offer decisioning](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html).

#### Plus de ressources pour [!UICONTROL Offer Decisioning]

[Centre d’aide](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![Icône](/assets/aem.png) Experience Manager {#aem}

Adobe recommande de consulter la page des [mises à jour et feuilles de route Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=fr) afin de se tenir au courant des informations de mise à jour.

### Communauté

* [Adobe Developers Live](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)  | 4-5 octobre 2021, 7:00 PDT

   Adobe Developers Live réunit des développeurs d’Adobe et des créateurs d’expérience aux profils variés et à un objectif unique, afin de créer des expériences de bout en bout incroyables. Cette conférence de deux jours comprend d’importantes mises à jour pour les développeurs, des sessions techniques et des opportunités de mise en réseau communautaire.

   Les équipes produit Adobe de Adobe Experience Cloud, Document Cloud et Creative Cloud présentent les dernières avancées technologiques et les outils de développement qui permettent la conception, la création de contenu, les services de document et la gestion de l’expérience client dans l’ensemble des secteurs d’activité.

   Adobe prévoit 20 sessions Experience Manager. Faites passer le mot !

   * [Liste complète des sessions](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [Enregistrement gratuit - Connexion à l’invitation](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Communauté Adobe Developers Live](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### Nouveaux cours et tutoriels sur Experience Manager {#tutorials-aem}

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Octobre 2021 | [Prise en main de la documentation XML](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | Cours | Découvrez comment créer, organiser, créer et publier du contenu avec la documentation XML pour Adobe Experience Manager. |
| Octobre 2021 | [Gestion des workflows créatifs  [!DNL Workfront] à l’aide d’Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | Cours | Découvrez comment Adobe [!DNL Workfront] et Experience Manager. |
| Octobre 2021 | [Prise en main d’AEM Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | Cours | Découvrez comment AEM Assets Essentials peut rationaliser la gestion des ressources pour votre entreprise. |
| Octobre 2021 | [[!UICONTROL Outil de transfert de contenu]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | Vidéo | Découvrez comment [!UICONTROL l’outil de transfert de contenu] vous aide à migrer le contenu vers AEM en tant que Cloud Service à partir d’AEM 6.3+. |
| Octobre 2021 | [[!UICONTROL Service d’importation en bloc]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | Vidéo | Découvrez comment AEM en tant que Cloud Services [!UICONTROL le service d’importation en bloc] peut être utilisé pour importer des ressources provenant de sources non AEM. |
| Octobre 2021 | [Communications (Output Service)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | Vidéo | Découvrez comment AEM Forms as a Cloud Service prend en charge le cas d’utilisation de la communication. |
| Octobre 2021 | [Inscription numérique](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | Vidéo | Découvrez comment AEM Forms as a Cloud Service prend en charge le cas d’utilisation de l’inscription numérique. |
| Octobre 2021 | [Utilisation des outils  [!UICONTROL Cloud Acceleration ] Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | Vidéo | Présentation détaillée de l’utilisation des outils [!UICONTROL Cloud Acceleration Manager]. |
| Octobre 2021 | [Navigation dans  [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | Vidéo | Explorez l’expérience de navigation de [!UICONTROL Cloud Acceleration Manager] pour Experience Manager en tant que Cloud Service. |
| Octobre 2021 | [Outil de migration des workflows de ressources](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | Vidéo | Découvrez comment l’outil [!UICONTROL Migration des workflows de ressources] vous aide à migrer vos workflows AEM Assets existants vers AEM en tant que Cloud Service. |
| Octobre 2021 | [[!UICONTROL Index Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | Vidéo | Découvrez comment le [!UICONTROL convertisseur d’index] convertit automatiquement les définitions d’index d’AEM existantes pour être AEM comme Cloud Service compatible. |
| Octobre 2021 | [[!UICONTROL Convertisseur du Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | Vidéo | Découvrez comment le [!UICONTROL convertisseur du Dispatcher] met automatiquement à jour les configurations existantes AEM Dispatcher pour être AEM comme Cloud Service compatible. |
| Octobre 2021 | [[!UICONTROL Modernizer du référentiel de code]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | Vidéo | Découvrez comment [!UICONTROL Core Repository Modernizer] met automatiquement à jour les projets AEM Maven existants pour qu’ils soient AEM comme Cloud Service compatibles. |
| Octobre 2021 | [[!UICONTROL Outils de refactorisation du code]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | Vidéo | Découvrez comment les [!UICONTROL outils de refactorisation du code ] de l’AEM permettent d’automatiser la conversion des projets AEM existants pour qu’ils soient, en tant que Cloud Service, entièrement compatibles. |
| Octobre 2021 | [[!UICONTROL Outil de transfert de contenu]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | Vidéo | Découvrez comment l’[!UICONTROL outil de transfert de contenu] vous permet de déplacer efficacement le contenu d’AEM 6.5 vers AEM en tant que Cloud Service. |
| Octobre 2021 | [Phases de mise en oeuvre de  [!UICONTROL Cloud Accelerated Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | Vidéo | Passez en revue et comprenez les principales phases de mise en oeuvre ou passez à AEM en tant que Cloud Service à l’aide de [!UICONTROL Cloud Acceleration Manager]. |
| Octobre 2021 | [Readiness et  [!UICONTROL Best Practice Analyzer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | Vidéo | Découvrez comment l’[!UICONTROL analyseur des bonnes pratiques] peut vous aider à vous préparer à passer d’AEM on-premise ou d’Adobe Managed Services à Experience Manager en tant que Cloud Service. |
| Octobre 2021 | [Présentation de Cloud Accelerated Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | Vidéo | Découvrez comment [!UICONTROL Cloud Acceleration Manager] peut vous aider à passer rapidement et facilement en Experience Manager en tant que Cloud Service. |
| Octobre 2021 | [AEM Forms as a Cloud Service - Passage à AEM CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | Vidéo | Découvrez les cas d’utilisation et les fonctionnalités pris en charge par AEM Forms as a Cloud Service. |
| Octobre 2021 | [Dépannage d’AEM en tant que Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | Vidéo | Découvrez comment résoudre les problèmes et déboguer le SDK AEM, AEM en tant que Cloud Service et le processus de création et de déploiement. |
| Octobre 2021 | [AEM Microservices  [!UICONTROL Assets]  - Passage à AEM en tant que Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | Vidéo | Découvrez comment les microservices d’asset compute d’AEM Assets as a Cloud Service vous permettent de générer automatiquement et efficacement n’importe quel rendu pour vos ressources, en remplaçant ce rôle de workflow d’AEM traditionnel. |
| Octobre 2021 | [Recherche et indexation](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | Vidéo | Découvrez les index de recherche AEM as a Cloud Service, comment convertir AEM 6 définitions d’index pour qu’elles soient compatibles avec les Cloud Service et comment déployer des index vers as a Cloud Service. |
| Octobre 2021 | [[!UICONTROL  Dispatcher  ]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | Vidéo | Découvrez l’AEM [!UICONTROL Dispatcher] pour AEM en tant que Cloud Service, en vous concentrant sur les modifications notables de [!UICONTROL Dispatcher] pour la version 6 d’Adobe, l’outil de conversion [!UICONTROL Dispatcher] et comment utiliser le SDK des outils de Dispatcher. |
| Octobre 2021 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | Vidéo | Découvrez Cloud Manager pour AEM en tant que Cloud Service et ses différences avec Cloud Manager pour AEM sur Adobe Manage Services (AMS). |
| Octobre 2021 | [Intégration à AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | Vidéo | Découvrez l’intégration à AEM en tant que Cloud Service à partir de la phase de contrat jusqu’à la configuration des environnements à l’aide de [!UICONTROL Cloud Manager]. |
| Octobre 2021 | [Modernisation du référentiel](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | Vidéo | Découvrez la modernisation du référentiel, le contenu modifiable et non modifiable, la structure du package et l’outil d’interface de ligne de commande de l’outil de modernisation du référentiel. |
| Octobre 2021 | [[!UICONTROL Outils de modernisation d’AEM]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | Vidéo | Découvrez comment AEM [!UICONTROL les outils de modernisation] sont utilisés pour mettre à niveau un projet et un contenu d’AEM existant afin d’être  en tant que Cloud Service compatible. |
| Octobre 2021 | [Outils de modernisation d’AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | Vidéo | Découvrez comment penser différemment aux implémentations d’AEM en tant que Cloud Service. |
| Octobre 2021 | [Analyseur des bonnes pratiques et Cloud Accelerated Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | Vidéo | Découvrez comment BPA (Best Practice Analyzer) et CAM (Cloud Acceleration Manager) fournissent un guide personnalisé pour la migration vers AEM en tant que Cloud Service. |
| Octobre 2021 | [Maintenance de l’historique des versions](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | Vidéo | Découvrez comment Adobe Workfront et Experience Manager [!UICONTROL Assets Essentials] vous aident à gérer des versions de documents [!DNL Workfront] et de ressources Assets Essentials. |
| Octobre 2021 | [Envoi de documents et liaison de ressources](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | Vidéo | Découvrez comment envoyer des documents Workfront à Assets Essentials et lier des ressources Assets Essentials à Workfront. |
| Octobre 2021 | [Configuration de l’intégration](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | Vidéo | Découvrez comment configurer l’intégration d’Adobe Workfront et d’Assets Essentials. |
| Octobre 2021 | [Qu’est-ce qu’une signature numérique ?](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Vidéo | Découvrez les signatures numériques basées sur des certificats, qui respectent les réglementations juridiques les plus strictes du monde entier et fournissent le plus haut niveau d’assurance de l’identité d’un signataire. |
| Octobre 2021 | [Créateur de segments dans Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | Vidéo | Divisez et segmentez vos données avec la segmentation dans Adobe Analytics. Cette vidéo vous guide tout au long du [!UICONTROL créateur de segments] et vous donne un aperçu de base. |
| Octobre 2021 | [Mappage des métadonnées](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | Vidéo | Découvrez comment configurer le mappage des métadonnées entre les champs Workfront et les propriétés Assets Essentials, et comment configurer Assets Essentials pour afficher les valeurs mappées. |

{style=&quot;table-layout:auto&quot;}

### Informations de mise à jour d’Experience Manager {#aem-links}

Les notes de mise à jour et les autres liens dʼinformation sur les mises à jour pour Experience Manager sont ici :

* [[!DNL Experience Manager as a Cloud Service]  Notes de mise à jour](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=fr)
* [[!DNL Experience Manager as a Cloud Service] Informations sur la version](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=fr)
* [[!DNL Experience Manager Cloud Manager]  Notes de mise à jour](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=fr)
* [Notes de mise à jour du service de conversion automatisée de formulaires](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=fr)
* [Notes de mise à jour du Service Pack 6.5 d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=fr)
* [Notes de mise à jour du pack de correctifs cumulatifs 6.4 d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=fr)
* [[!DNL Experience Manager Assets Dynamic Media]  Notes de mise à jour](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=fr)
* [[!DNL Experience Manager Brand Portal]  Notes de mise à jour](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=fr)
* [Notes de mise à jour de l’appli de bureau Experience Manager ](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=fr)
* [[!DNL Experience Manager Dispatcher]  Notes de mise à jour](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=fr)
* [Notes de mise à jour d’Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=fr)
* [Notes de mise à jour de Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=fr)

### Autres ressources dʼaide pour Experience Manager

* [[!DNL Experience Manager as a Cloud Service] Guides](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=fr#previous-updates)
* [Versions plus anciennes de la documentation pour Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager]  Guide de l’utilisateur](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=fr)
* [[!DNL Dynamic Media Classic] Accueil de l’aide](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=fr)
* [Documentation Experience Manager : mises à jour récentes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=fr#aem-as-a-cloud-service)

## ![Icône](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Dernières mises à jour d’Adobe Campaign

Pour en savoir plus sur les dernières fonctionnalités, améliorations et correctifs disponibles :

* [Notes de mise à jour de Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=fr)
* [Notes de mise à jour de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=fr)
* [Notes de mise à jour de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=fr)

### Nouveaux cours et tutoriels sur [!UICONTROL Campaign] {#tutorials-campaign}

Derniers tutoriels et cours pour Adobe Campaign.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Octobre 2021 | [Création de campagnes avancées avec Adobe Campaign V8 pour les utilisateurs professionnels](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | Cours | Découvrez comment configurer et exécuter des campagnes marketing avancées à l’aide d’Adobe Campaign V8. Découvrez les prérequis, créez et configurez des campagnes avancées, des diffusions et gérez les abonnements. |
| Octobre 2021 | [Utilisation des API SOAP dans les workflows - Introduction](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | Tutoriel | Découvrez comment utiliser les API Adobe Campaign Soap et créer un workflow de diffusion avancé basé sur les données reçues via l’API. |
| Octobre 2021 | [Créer des événements](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/create-events.html?lang=en) | Tutoriel | Découvrez comment configurer un événement, spécifier le point de terminaison de diffusion en continu et la charge utile d’un événement. |
| Octobre 2021 | [Configuration des sources de données](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/configure-data-sources.html?lang=en) | Tutoriel | Découvrez ce qu’est une source de données et comment configurer des sources de données Experience Platform et externes. |
| Octobre 2021 | [Cas d’utilisation - messages d’éclatement](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html?lang=en) | Tutoriel | Comprenez les cas d’utilisation applicables pour les messages en rafale. Découvrez comment configurer un parcours pour les messages en rafale et les bonnes pratiques à appliquer. |

{style=&quot;table-layout:auto&quot;}

### Ressources d’aide pour Campaign

* Adobe Campaign v8 : [Centre dʼaide](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=fr) - [Guides de mise en œuvre](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=fr)
* Adobe Campaign Standard : [Documentation de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Tutoriels viéo](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=fr) - [Calendrier des versions](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=fr)
* Adobe Campaign Classic : [Documentation de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=fr)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=fr) - Tutoriels vidéo pour [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=fr)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=fr)

## ![Icône](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notes de mise à jour dʼ[!DNL Adobe Advertising Cloud].

* [Nouveautés de la version  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Nouveautés de la version  [!DNL Advertising Cloud Search]](#adcloud-search)

### Nouveautés de la version [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Dernière mise à jour : **28 septembre 2021**

| Fonctionnalité | Description |
| ------- | ----------- |
| Vues de la gestion des campagnes | Une colonne &quot;[!UICONTROL Date de création]&quot; est désormais disponible dans les jeux de colonnes personnalisés pour les vues [!UICONTROL Campagnes], [!UICONTROL Packages], [!UICONTROL Emplacements] et [!UICONTROL Publicités]. Vous pouvez également filtrer les vues [!UICONTROL Emplacements] et [!UICONTROL Publicités] par [!UICONTROL Date de création]. |
| Offres garanties par programmation | (Version du 8 septembre) Vous pouvez désormais modifier l’[!UICONTROL offre maxi] pour l’emplacement par défaut d’une offre garantie par programmation (PG). Cependant, comme les offres PG ont toujours un CPM fixe, seuls les clients internationaux doivent modifier l’[!UICONTROL offre max] pour prendre en compte les frais de change de devise. |
|  | (Version du 8 septembre) Les utilisateurs disposant de l’autorisation &quot;[!DNL FreeWheel Programmatic Guaranteed]&quot; peuvent désormais envoyer une publicité à [!DNL FreeWheel Programmatic Creative API] à partir de la vue [!UICONTROL Publicités] ou de la vue [!UICONTROL Emplacements]. Vous pouvez toujours envoyer une publicité à partir de la vue [!UICONTROL Offres]. |

{style=&quot;table-layout:auto&quot;}

### Nouveautés de la version [!DNL Advertising Cloud Search] {#adcloud-search}

Dernière mise à jour : **28 septembre 2021**

| Fonctionnalité | Description |
| ------- | ----------- |
| Informations publicitaires | D’autres informations sont disponibles en mode bêta. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

Voir les liens suivants pour consulter les notes de mise à jour dʼAdobe Commerce :

* [Adobe Commerce et Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite pour Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![Icône](/assets/target.png) [!DNL Target] {#target}

Dernière mise à jour : **3 août 2021**

Voir les [[!DNL Target] notes de mise à jour](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=fr) pour consulter les informations les plus récentes.

## ![Icône](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] est une application complète pour la gestion des leads et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en s’engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Voir le [calendrier des versions](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=fr) de [!DNL Marketo Engage] pour consulter les informations les plus récentes sur le calendrier des versions et les notes de mise à jour.

## ![Icône](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] est une application de gestion du travail unifiée qui permet de partager des idées, créer du contenu, gérer des processus complexes et donner le meilleur de soi-même.

Consultez la page [[!DNL Workfront] versions](https://one.workfront.com/s/product-releases) pour obtenir un récapitulatif des dernières informations relatives à lʼensemble des produits.

## ![Icône](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Document Cloud.

### Cours et tutoriels sur Document Cloud {#tutorials-doc-cloud}

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Octobre 2021 | [Qu’est-ce qu’une signature numérique ?](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Vidéo | Découvrez comment utiliser des ID numériques du monde entier avec Adobe Sign. |
| Octobre 2021 | [Prise en main d’Adobe Sign pour les nouveaux expéditeurs](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | Vidéo | Si vous découvrez comment utiliser Adobe Sign, ce tutoriel est un bon point de départ. Ce tutoriel complet se concentre sur tous les concepts de base pour vous aider à maîtriser rapidement Adobe Sign. |
| Octobre 2021 | [Chargement des commentaires PDF dans InDesign](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | Vidéo | Dans ce tutoriel vidéo de 60 secondes, découvrez comment charger à nouveau des commentaires PDF dans InDesign après une révision partagée Acrobat. Ce workflow numérique vous permet d’effectuer des révisions en un temps record. |
| Octobre 2021 | [Obtention d’un ID numérique à partir de  [!DNL Intesi Group]  (qualifié)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | Vidéo | Découvrez comment obtenir un certificat de signature numérique qualifié auprès du groupe [!DNL Intesi]. Une fois enregistré et votre identité vérifiée, [!DNL Intesi] le groupe vous émet un ID numérique utilisé pour appliquer une signature cloud Adobe Sign. |
| Octobre 2021 | [Signature à l’aide de [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | Vidéo | Découvrez comment utiliser votre ID numérique de groupe Intesi pour authentifier votre identité et autoriser une signature numérique distante (signature cloud) sur un document. |
| Octobre 2021 | [Obtention d’un ID numérique à partir de  [!DNL Intesi Group]  (avancé)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | Vidéo | Découvrez comment obtenir un certificat de signature numérique avancé auprès d’Intesi Group. Une fois enregistré et votre identité vérifiée, le groupe Intesi vous émet un ID numérique utilisé pour appliquer une signature cloud Adobe Sign. |
| Octobre 2021 | [Signature à l’aide de [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | Vidéo | Découvrez comment utiliser votre [!DNL Digidentity] ID numérique pour authentifier votre identité et autoriser une signature numérique distante (signature cloud) sur un document. |
| Octobre 2021 | [Obtention d’un ID numérique depuis [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | Vidéo | Découvrez comment obtenir un certificat de signature numérique à partir de [!DNL Digidentity]. Une fois enregistré et votre identité vérifiée, [!DNL Digidentity] vous émet un ID numérique utilisé pour appliquer une signature cloud Adobe Sign. |
| Octobre 2021 | [Détecter les différences entre deux fichiers PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | Vidéo | Ne commettez jamais d’erreur en utilisant la mauvaise version d’un fichier. Détectez rapidement et précisément les différences entre deux fichiers PDF afin d’améliorer les processus de révision des documents. |
| Octobre 2021 | [Création de contenu PDF lors de la navigation avec Microsoft® Edge](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | Vidéo | Découvrez comment archiver instantanément des pages web au format PDF avec l’extension Adobe Acrobat pour Microsoft® Edge. Cet outil Windows est inestimable pour les projets de recherche et l’affichage hors ligne d’informations sur le Web. |
| Octobre 2021 | [Conversion de courriers électroniques et de pièces jointes au format PDF dans Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | Vidéo | Découvrez comment archiver des emails et des pièces jointes au format PDF dans Outlook pour vos projets. Découvrez comment fournir des informations de manière plus professionnelle et plus sécurisée en convertissant automatiquement les pièces jointes en PDF. Cet outil est uniquement disponible pour Windows. |

{style=&quot;table-layout:auto&quot;}

Pour obtenir de l’aide sur Document Cloud, voir :

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=fr)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=fr)
* [Formation et support Adobe Document Cloud](https://helpx.adobe.com/fr/support/document-cloud.html)

## ![Icône](/assets/creative-cloud-24.png) Creative Cloud abonnement Entreprise {#creative-cloud}

Voir [Creative Cloud pour les tutoriels d’entreprise](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=fr) pour consulter les derniers tutoriels.

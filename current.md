---
title: Dernières notes de mise à jour
description: Découvrez les dernières notes de mise à jour, les nouvelles fonctionnalités et la nouvelle documentation pour les produits et services [!DNL Experience Cloud] . Trouvez de nouvelles ressources dʼaide et des tutoriels sur [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] et [!DNL Document Cloud].
doc-type: release notes
last-update: January 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 26f5bbbc8e6a35b8f8246c9a96b7a3dabc361f85
workflow-type: tm+mt
source-wordcount: '6416'
ht-degree: 42%

---

# Notes de mise à jour d’Adobe Experience Cloud - Janvier 2022

![Bannière](assets/experience-cloud-banner-3.png)

Découvrez les dernières mises à jour de la version [Produits Adobe Experience Cloud](https://business.adobe.com/products/adobe-experience-cloud-products.html). Découvrez la documentation d’aide autonome, des tutoriels et des cours les plus récents sur Experience League.

>[!NOTE]
>
>Pour recevoir une notification par courriel mensuelle des mises à jour de cette page, abonnez-vous à la fonction [Mise à jour produit prioritaire des Adobes](https://www.adobe.com/subscription/priority-product-update.html). Revenez fréquemment pour rester au courant de ce qui se passe sur Experience League.

**Janvier 2022**

Dernière mise à jour : **14 janvier 2022**

* [[!DNL Experience League] Événements](#events)
* [[!DNL Experience Cloud Central Interface Components] &amp; Administration](#ecloud)
* [[!UICONTROL Statut du système] Adobe](#status)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)

Besoin d’aide ? Visite [Adobe Experience League](https://experienceleague.adobe.com/?lang=fr#home) pour obtenir de la documentation technique et sur les produits, des cours organisés par l’Adobe, des tutoriels vidéo, des réponses rapides, des informations de la communauté et des formations dirigées par un instructeur.

## ![Icône](/assets/experience-league.png) [!DNL Experience League] Événements {#events}

Les événements Experience League sont un excellent endroit pour obtenir des réponses d’experts en produits Adobe. Vous trouverez ci-dessous les événements disponibles :

* [Experience League Live](#exl-live) : événements vidéo en direct et à la demande sur YouTube
* [Saut de café et questions-réponses de la communauté](#coffee): Conversations avec les responsables de produits dans les communautés Experience League
* [Adobe Developer’s Live](#dev-live) : événements vidéo à la demande disponibles sur Experience League

Les planifications et les événements sont les suivants :

### Experience League LIVE{#exl-live}

[Experience League LIVE est une émission produite par l’équipe d’Experience League et diffusée en direct.](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=fr) C’est l’occasion de communiquer avec des experts Adobes en produits. Découvrez des conseils pratiques, des astuces et des stratégies que vous pouvez appliquer aux applications Adobe Experience Cloud.

| Date de l’événement | Heure | Nom de l’événement | Format | Description |
| -----------| ---------- | ---------- | ---------- |---------- |
| 25 janvier 2022 | 9 heures (PST) | [Analyse de votre entreprise à l’échelle des sources de données](https://www.youtube.com/watch?v=L2EWCOHeyXI) | Événement vidéo en direct | Utilisez Customer Journey Analytics pour regrouper toutes vos données au même endroit. |
| 3 février 2022 | 18 h (heure de Paris) | [Présentation de toutes les nouvelles démonstrations de référence dans AEM](https://www.youtube.com/watch?v=FEREXV826NQ) | Événement vidéo en direct | Découvrez le moyen le plus rapide de configurer, de démontrer et d’explorer les fonctionnalités d’AEM as a Cloud Service. |

{style=&quot;table-layout:auto&quot;}

Les épisodes précédents sont disponibles à l’adresse [Experience League Live](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en).

### Pauses café questions-réponses de la communauté{#coffee}

Passez une heure avec un invité spécial et envoyez vos questions dans les communautés Experience League. Obtenez les réponses aux questions des experts du produit chez Adobe !

| Nom de l’événement | Date | Applications | Format | Description |
| -----------| ---------- | ---------- | ---------- |---------- |
| Customer Journey Analytics et l’avenir d’Analytics | 18 janvier 2022 @ 8h00 PST | Adobe Analytics, Customer Journey Analytics, Experience Platform | Forum Q&amp;R | Posez vos questions dans la communauté Analytics pour Trevor Paulsen, Gestionnaire de produits de groupe, Adobe Analytics.<br>[Détails et enregistrement](https://analyticscommunityqacoffeebrea.splashthat.com/?utm_source=community-thread&amp;utm_campaign=coffee_talk_AA&amp;utm_content=220118) |
| Intégration d’Adobe Target avec Journey Optimizer, l’interface d’Adobe Target et les rubriques générales de Target | 19 janvier 2022 à 9h00 PST | Adobe Target, Journey Optimizer | Forum Q&amp;R | Passez une heure avec Jon Tehero et posez vos questions dans la communauté Adobe Target.<br>[Détails et enregistrement](https://communitycoffeebreakadobetarge.splashthat.com/?utm_source=email&amp;utm_campaign=coffee_talk_AT&amp;utm_content=210119) |

{style=&quot;table-layout:auto&quot;}

### Adobe Developer&#39;s Live{#dev-live}

| Événement | Date et heure | Type | Description |
| -----------| ---------- | ---------- |---------- |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=fr) | À la demande | Vidéo | [!DNL Developers Live] présente les dernières avancées technologiques et les outils les plus récents pour les développeurs. Ils rendent possible la conception, les workflows de création de contenu, les services de document et la gestion de lʼexpérience client dans tous les secteurs dʼactivité. Affichez le discours liminaire, découvrez les API dʼAnalytics, la couche de données client, les projets open source Adobe I/O et bien plus encore. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] et Administration {#ecloud}

Aucune mise à jour au cours du dernier mois.

**Plus de ressources d’aide sur [!DNL Experience Cloud Central UI Components] et Administration**

* Aide dʼadministration pour les [Composants de lʼinterface centrale](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=fr) et la gestion des utilisateurs
* Aide et notes de mise à jour pour le [service Places - Emplacement](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=fr)
* Aide sur [Personnes - Attributs du client et Bibliothèque dʼaudiences](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=fr)

## ![Icône](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] fournit des informations détaillées, des mises à jour de statut et des notifications par e-mail relatives aux produits Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/fr).

Lisez le [dernières notes de mise à jour](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=fr) pour [!DNL Adobe System Status].

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Mise à jour des informations et de la nouvelle documentation pour l’Experience Platform et [!UICONTROL SDK Mobile]:

* Prochaine version planifiée : **26 janvier 2022**
* Dernière version : **17 novembre 2021**

Voir [Notes de mise à jour des Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=fr) pour rester à jour.

### Nouveaux tutoriels et cours pour les Experience Platform {#tutorials-platform}

Nouveaux tutoriels, vidéos ou cours publiés pour Experience Platform.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Janvier 2022 | [Configuration de Customer AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-customer-ai.html?lang=fr) | Vidéo | Découvrez comment créer une instance de Customer AI pour prédire le comportement du client. |
| Janvier 2022 | [Configuration d’Attribution AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-attribution-ai.html?lang=fr) | Vidéo | Découvrez comment créer une instance d’Attribution AI pour comprendre l’impact de vos canaux et campagnes marketing. |

{style=&quot;table-layout:auto&quot;}

### SDK Adobe Mobile

Voir [Notes de mise à jour et journaux des modifications](https://aep-sdks.gitbook.io/docs/release-notes) pour les SDK Adobe Experience Platform Mobile.

## ![Icône](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Date de publication : **19 janvier 2022**

* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features)
* [Nouvelles fonctionnalités dans Customer Journey Analytics](#cust-journey)
* [Correctifs dans Adobe Analytics](#aa-fixes)
* [Avis importants pour les administrateurs d’Analytics](#aa-notices)
* [Cours et tutoriels pour Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

| Fonctionnalité | Description | Date ciblée |
| ----------- | ---------- | ------- |
| S.O. |  | Voir [Disponibilité générale](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=fr) |

{style=&quot;table-layout:auto&quot;}

### Nouvelles fonctionnalités dans Customer Journey Analytics {#cust-journey}

| Fonctionnalité | Description | Date ciblée |
| ----------- | ---------- | ----- |
| [!UICONTROL Persistance] options de liaison des dimensions et des mesures de liaison | Lors de la création ou de la modification d’une vue de données, vous pouvez lier la persistance d’une dimension à une autre dimension ou mesure. Ce concept est connu sous le nom de _merchandising_ dans Reports &amp; Analytics et est désormais pris en charge dans CJA. [En savoir plus](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html#binding-dimension) | 19 janvier 2022 |
| [!UICONTROL Première connaissance] et [!UICONTROL Dernier connu] modèles d&#39;attribution | Ces deux nouveaux modèles d’attribution prennent la première ou la dernière valeur observée pour une dimension dans une portée de persistance spécifiée (session, personne ou période personnalisée avec recherche arrière). Ils appliquent ensuite le modèle d’attribution à tous les événements de la portée spécifiée. [En savoir plus](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html#allocation-settings) | 19 janvier 2022 |
| [!UICONTROL PersonID] et [!UICONTROL Espace de noms PersonID] comme dimensions | Expose la variable `personID` (ou `customerID`, ou l’identifiant que vous utilisez pour fusionner des jeux de données dans une connexion) en tant que dimension dans les vues de données. Cette amélioration facilite l’inclusion de la variable `personID` comme dimension dans votre vue de données en l’extrayant de la connexion. [En savoir plus](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-reference.html?lang=en#optional-standard-components) | 19 janvier 2022 |

{style=&quot;table-layout:auto&quot;}

Voir [Disponibilité générale](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=fr) pour obtenir des informations sur la version.

### Correctifs dans Adobe Analytics et Customer Journey Analytics {#aa-fixes}

* Correction d’un problème Analysis Workspace en raison duquel l’ID d’audience manquait dans les éléments de dimension. (AN-262038 ; AN-279315)
* Correction d’un problème qui empêchait les utilisateurs de charger un enregistrement [!DNL Target] dans Workspace. (AN-277461) AN-275825; AN-266397)
* Correction d’un problème en raison duquel les fonctionnalités non activées étaient visibles dans l’interface utilisateur. (AN-262006)
* Correction d’un problème qui se produisait lors de la modification de la date à l’aide du champ de date dans Workspace. Cela générait le [!UICONTROL Heure de fin] passant de 23 h 59 à 12 h 00. (AN-277269 ; AN-277481)
* Correction d’un problème en raison duquel l’interface utilisateur Segment était rompue lors de l’ajout de nouveaux segments dans un segment déjà chargé. (AN-260827)
* Correction d’un problème en raison duquel les utilisateurs ne pouvaient pas accéder aux projets Workspace partagés. (AN-267529)
* Ajout d’un message d’erreur qui s’affiche lorsqu’une période variable comporte une date de début ultérieure à la date de fin. (AN-270488)
* Correction de divers problèmes de flux de données. (AN-275876) AN-270512; AN-277284; AN-277290; AN-274893; AN-274606; AN-269651)
* Correction d’un problème en raison duquel les périodes dans les graphiques ignoraient les filtres de date dans les tableaux. (AN-263999)
* Correction d’un problème en raison duquel les rapports planifiés étaient envoyés plus tôt en raison de l’heure d’été. (AN-276410 ; AN-276305)
* Correction d’un problème lié au téléchargement du projet vers . `.csv` échec du fichier dans Workspace. (AN-275834)

#### Correctifs supplémentaires dans Adobe Analytics et CJA

AN-253294; AN-254976; AN-255377; AN-255561; AN-258550; AN-259336; AN-263935; AN-265094; AN-269441; AN-269486; AN-269855; AN-271166; AN-271588; AN-272088; AN-272249; AN-272859; AN-272873; AN-272885; AN-273229; AN-273913; AN-274237; AN-274472; AN-274491; AN-274619; AN-274766; AN-275248; AN-275259; AN-275271; AN-275315; AN-275388; AN-275418; AN-275597; AN-275643; AN-275650; AN-275651; AN-275675; AN-275682; AN-275704; AN-275711; AN-275796; AN-275834; AN-275923; AN-275941; AN-276044; AN-276125; AN-276157; AN-276397; AN-276597; AN-276789; AN-276834; AN-276861; AN-276870; AN-276963; AN-276975; AN-277000; AN-277044; AN-277093; AN-277200; AN-277215; AN-277271; AN-277281; AN-277362; AN-277419; AN-277492; AN-277498; AN-277533; AN-277619; AN-277675; AN-277681; AN-277767; AN-277805; AN-277810; AN-277818; AN-277875; AN-277933; AN-277988; AN-278105; AN-278115; AN-278122; AN-278192; AN-278407; AN-278437; AN-278559; AN-278604; AN-278610; AN-278709; AN-278835; AN-278849; AN-278881; AN-279067; AN-279103; AN-279111; AN-279219; AN-279237; AN-279312

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Remarque | Date d’ajout ou de mise à jour | Description |
| ----------- | ---------- | ---------- |
| Expiration de l’extension liste autorisée EOL pour les intégrations héritées d’Analytics OAuth/JWT | 14 janvier 2022 | Le 25 mai 2022, le [API Analytics 1.3, API SOAP 1.4 et API OAuth/JWT héritées d’Analytics](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md) Extension de liste autorisée proposée aux clients utilisant l’ancienne version [!DNL Analytics] Informations d’identification OAuth/JWT supplémentaires pour migrer leurs intégrations client vers [Informations d’identification Adobe IMS](https://developer.adobe.com/console) expire. Cette expiration affecte (mais ne se limite pas à) [!DNL Adobe Analytics Livestream] et [!DNL Adobe Campaign] clients qui n’ont pas terminé leurs migrations IMS requises. Clients qui utilisent actuellement des [!DNL Analytics] Les informations d’identification OAuth/JWT via l’extension de liste autorisée et qui ne terminent pas leur migration vers les informations d’identification IMS d’ici au 25 mai 2022 perdront l’accès aux services Adobe. Les clients Livestream peuvent se référer à ces [instructions](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/live-stream-api/getting_started.md) lors de la migration de leurs applications clientes vers les informations d’identification IMS. [!DNL Campaign] les clients peuvent contacter leur équipe de compte d’Adobe au sujet de la mise à niveau vers la dernière version de [!DNL Campaign]. |
| Fin de vie de Reports &amp; Analytics | 4 janvier 2022 | À compter du **31 décembre 2023**, Adobe prévoit dʼabandonner Reports &amp; Analytics et ses rapports et fonctionnalités associés. Les rapports, les visualisations et la technologie sous-jacente qui optimisent Reports &amp; Analytics ne répondent plus aux normes technologiques d’Adobe. La plupart des fonctions de Reports &amp; Analytics sont disponibles dans [Analysis Workspace](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/home.html?lang=fr). Depuis la publication d’Analysis Workspace en 2015, les fonctionnalités de Reports &amp; Analytics ont migré vers Analysis Workspace, de telle sorte quʼun seuil de parité en matière de workflow a été atteint. [Cet avis](https://spark.adobe.com/page/6WnF8JK6IRDhf/) décrit le processus de fin de vie. |
| Mise à niveau des services SFTP (Secure File Transfer Protocol) | 13 janvier 2022 | Activé **2 mai 2022**, Adobe Analytics mettra à niveau ses services SFTP (Secure File Transfer Protocol) afin de fournir une sécurité améliorée pour les transferts de fichiers. Avec cette modification, certaines configurations de client SFTP ne seront plus prises en charge. Nous ajouterons également quelques options de connexion disponibles par **1 mars 2022**. Cela aura uniquement un impact sur les données envoyées à ou récupérées à partir d’Adobe Analytics par SFTP. Le protocole FTP ne sera pas affecté. Pour éviter les interruptions de service, veillez à ce que vos clients SFTP (code, outils, services) soient conformes aux modifications détaillées. [here](https://experienceleague.adobe.com/docs/analytics/export/ftp-and-sftp/secure-file-transfer-protocol/sftp-upgrade.html). |
| _Global + Chine_ Type RDC | 22 novembre 2021 | _Global + Chine_ est un nouveau type de collecte de données régionale (RDC) qui simplifie le routage du trafic pour les clients globaux à l’aide de la variable [!UICONTROL Package de module complémentaire d’optimisation des performances en Chine]. Auparavant, vous deviez déterminer si les données devaient être acheminées vers le point d’entrée de collecte Chine ou l’un des points d’entrée de collecte globale. Maintenant, vous pouvez choisir ce *type* de collecte de données régionale afin de permettre à Adobe de déterminer le point d’entrée de collecte optimal en fonction de la géolocalisation de l’utilisateur. |
| Fin de vie du traitement complet dans les sources de données | 18 octobre 2021 | Le **31 janvier 2022**, Adobe arrêtera le traitement complet, qui permet aux utilisateurs d’ingérer des données d’accès hors ligne dans Analytics. Cette fonctionnalité est disponible via l’[API Bulk Data Insertion](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md). [En savoir plus](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=fr ) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Pour connaître les dernières mises à jour des versions d’AppMeasurement (version 2.22.4), reportez-vous aux [Notes de mise à jour d’AppMeasurement pour JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=fr).

### Nouveaux tutoriels et cours Analytics {#tutorials-analytics}

Nouveaux tutoriels, vidéos ou cours publiés pour Adobe Analytics.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Janvier 2022 | [Le module Fondamentaux dʼAnalytics pour les utilisateurs professionnels a été supprimé.](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/retire-fundamentals-for-business-users-course.html) | Vidéo | Découvrez pourquoi le cours d’origine a été retiré et les conseils de l’Adobe sur les nouveaux cours de remplacement. |
| Janvier 2022 | [Panneau Temps de lecture de médias](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/media-analytics/measuring-media-analytics/media-playback-time-spent-panel.html?lang=en) | Vidéo | Découvrez comment le panneau Temps passé sur la lecture multimédia permet aux utilisateurs de médias de comprendre leur audience en fonction de la durée de visionnage au cours de la journée par rapport à une granularité donnée. |
| Janvier 2022 | [Stratégies De Segmentation Client Et Bonnes Pratiques Dans Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/customer-segmentation-strategies.html?lang=en) | Vidéo | Rejoignez les initiés d’Analytics pour un jeudi d’Analytics axé sur les concepts de base de la segmentation des clients, les stratégies et les bonnes pratiques. |
| Janvier 2022 | [Configuration de la détection de référencement payant](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-paid-search-detection.html#) | Vidéo | Découvrez comment parcourir la configuration de la section Détection de recherche payante dans le Admin Console Adobe Analytics, y compris quelques recommandations. |
| Janvier 2022 | [Configuration des variables de liste](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-list-variables.html?lang=en) | Vidéo | Découvrez comment et pourquoi configurer et utiliser des variables de liste dans Adobe Analytics. Les variables de liste vous permettent de placer plusieurs valeurs dans un eVar. |
| Janvier 2022 | [Configuration des variables de trafic (props)](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-traffic-variables-props.html?lang=en) | Vidéo | En savoir plus sur la configuration des variables de trafic, également appelées _props_, dans le Admin Console Analytics. |
| Janvier 2022 | [Manipulation des données entrantes à l’aide de règles de traitement](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/manipulating-incoming-data-with-processing-rules.html?lang=en) | Vidéo | Découvrez les règles de traitement dans Adobe Analytics et leur utilisation. Obtenez quelques conseils, exemples et même un avertissement sur l’utilisation des règles de traitement. |
| Janvier 2022 | [Utilisation de segments en tant que dimensions dans Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/applying-segments/using-segments-as-dimensions-in-analysis-workspace.html?lang=fr) | Vidéo mise à jour | Découvrez comment comparer et visualiser des segments en les utilisant comme dimension dans Analysis Workspace. |
| Janvier 2022 | [Gestion et partage de segments dans Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-management-and-sharing.html?lang=en) | Vidéo mise à jour | Dans cette vidéo mise à jour, découvrez quelques conseils sur le partage et la gestion de vos segments. |
| Janvier 2022 | [Utilisation de segments pour limiter les données dans Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/applying-segments/using-segments-to-limit-data-in-analysis-workspace.html?lang=en) | Vidéo mise à jour | Découvrez comment limiter les utilisateurs d’un projet dans Analysis Workspace à un (ou à des segments) spécifique lorsqu’ils utilisent l’outil. |
| Janvier 2022 | [Comparaison de segments dans Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-comparison-in-analysis-workspace.html?lang=en) | Vidéo mise à jour | Découvrez comment Segment IQ, composant d’Analysis Workspace dans Adobe Analytics, simplifie l’analyse en examinant deux segments Analytics sur l’ensemble de vos dimensions et mesures afin de découvrir automatiquement leurs différences les plus importantes sur le plan statistique. |

{style=&quot;table-layout:auto&quot;}

### Ressources d’aide à propos d’Analytics

* [Documentation et tutoriels du produit Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=fr)

## ![Icône](/assets/audience-manager.png) Audience Manager {#aam}

Correctifs et améliorations d’Audience Manager.

* Correction d’un problème en raison duquel tous les appels API renvoyaient une erreur `Undocumented` lors de l’exécution via l’interface Swagger. (AAM-59190)
* Correction d’un problème en raison duquel des rôles utilisateur incorrects étaient affectés à des partenaires dans certaines situations. (AAM-59451)
* Correction dʼun problème en raison duquel lʼAPI nécessitait des en-têtes dʼauthentification sensibles à la casse. (AAM-58528)

## ![Icône](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe recommande de consulter la page des [mises à jour et feuilles de route Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=fr) afin de se tenir au courant des informations de mise à jour.

### Versions de produits Experience Manager

* **Experience Manager as a Cloud Service**

   Regardez la [Vidéo de présentation de la version de décembre 2021](https://video.tv.adobe.com/v/339278) pour un résumé des fonctionnalités ajoutées dans la version 2021.11.0 (novembre 2021).

   * [](https://video.tv.adobe.com/v/338253)Présentation de la version dʼoctobre 2021 : vidéo des nouvelles fonctionnalités.
   * [](https://video.tv.adobe.com/v/337381)Présentation de la version de septembre 2021 : vidéo des nouvelles fonctionnalités.

   * **Experience Manager Assets as a Cloud Service**

      _Nouvelle fonctionnalité_

      * Dynamic Media [!UICONTROL Recadrage intelligent d’image] et [!UICONTROL Échantillon] est désormais alimenté par les derniers services Sensei, qui génèrent des cultures améliorées et des échantillons. En outre, une amélioration a été lancée afin de générer un contenu de recadrage différent pour les mêmes proportions mais avec des résolutions différentes. En outre, les modifications manuelles sont conservées lors du retraitement si la largeur et la hauteur du profil d’image ne sont pas modifiées.

      _Nouvelles fonctionnalités du canal de version préliminaire de Experience Manager Assets_

      * Dynamic Media : vous pouvez désormais utiliser l’interface Dynamic Media de Experience Manager pour configurer [!UICONTROL Paramètres généraux] et [!UICONTROL Configuration de la publication] au lieu d’avoir à passer par l’application de bureau Dynamic Media Classic.
      * Dynamic Media prend désormais en charge l’ingestion, la prévisualisation, la lecture et la publication pour les vidéos MXF. Les annotations et les vidéos Shoppable pour les vidéos MXF ne sont pas encore prises en charge.
      * Après la configuration d’une connexion entre les déploiements DAM distant et Sites, les ressources sur DAM distant sont disponibles sur le déploiement Sites. Vous pouvez désormais effectuer les opérations suivantes : [mettre à jour, supprimer, renommer et déplacer des opérations](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=en) sur des ressources ou des dossiers DAM distants. Les mises à jour, avec un certain délai, sont disponibles automatiquement sur le déploiement Sites .
   * **Experience Manager Forms as a Cloud Service**

      _Nouvelle fonctionnalité_

      * **Externalisation des données de workflow Experience Manager pour un traitement sécurisé**: Vous pouvez stocker des données de processus Experience Manager en cours de traitement (Experience Manager). [!UICONTROL Variables de workflow] données) qui contient des éléments SPD (données personnelles sensibles) dans un référentiel géré par le client pour un traitement sécurisé. Les éléments de données et les variables de workflow ne sont pas stockés dans le référentiel de Experience Manager et sont récupérés à la demande à partir d’un référentiel géré par le client lors du traitement du workflow.

      _Nouvelles fonctionnalités du canal de version préliminaire de Experience Manager Forms_

      * **AEM Forms as a Cloud Service - Communications**: [API de communication](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=en) vous aide à combiner un modèle et des données XML pour générer des documents d’impression dans différents formats. Avec le service , vous pouvez générer des documents en mode synchrone et par lots. Les API vous permettent de créer des applications pour effectuer les opérations suivantes :
         * Générer des documents en renseignant les fichiers de modèle (PDF et XDP) avec des données XML
         * Générer des formulaires de sortie dans divers formats, y compris les flux dʼimpression PDF non interactifs.
      * **Polices personnalisées pour les documents Document d’enregistrement et de PDF créés avec les API de communication**: Vous pouvez désormais utiliser des polices approuvées par la marque dans les documents PDF générés à l’aide des API de communication pour vous conformer aux exigences de votre organisation.
      * **Portail Forms**: Vous pouvez utiliser [Portail Forms](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/configure-forms-portal.html?lang=en) pour répertorier vos formulaires adaptatifs publiés sur une page Experience Manager Sites. Cela permet à un visiteur du site de découvrir tous les formulaires disponibles. De plus, le visiteur peut utiliser [!UICONTROL Portail Forms] pour enregistrer et accéder au brouillon d’un formulaire adaptatif et consulter la version PDF d’un formulaire adaptatif envoyé.
   * **Cloud Manager**

      _Nouvelles fonctionnalités_

      * Les utilisateurs peuvent désormais utiliser de nouveaux pipelines front-end pour déployer le code front-end exclusivement de manière accélérée. Voir [Pipelines front-end de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/cicd-pipelines/introduction-ci-cd-pipelines.html?lang=en#front-end) pour en savoir plus.

         >[!IMPORTANT]
         >
         >Vous devez disposer d’une version de Experience Manager `2021.10.5933.20211012T154732Z` ou version ultérieure pour utiliser la nouvelle [!UICONTROL Pipelines front-end].

      * La durée du pipeline de qualité du code est réduite en exécutant l’analyse du code de manière plus efficace sans avoir à créer une image de Experience Manager entière. Cette modification se déploie progressivement au cours des prochaines semaines suivant la publication de la version.
      * L’identifiant de validation Git s’affiche désormais dans les détails d’exécution du pipeline, ce qui facilite le suivi du code qui a été créé.
      * [!UICONTROL Création de programme] est désormais disponible par le biais de l’API publiquement exposée.
      * [!UICONTROL Création d’environnement] est désormais disponible via l’API publiquement exposée.
      * L’en-tête de réponse `x-request-id` est désormais visible dans le laboratoire de l’API sur [www.adobe.io](https://www.adobe.io/). Cet en-tête est utile pour signaler des problèmes à l’assistance clientèle à des fins de dépannage.
      * Une nouvelle [!UICONTROL Activité] est disponible, où les activités telles que le pipeline et les exécutions de code peuvent être affichées avec les détails associés. Au fil du temps, les activités répertoriées dans cette page s’étendent au-delà des détails fournis.
      * Une nouvelle [!UICONTROL Pipelines] page avec une fenêtre contextuelle d’état pour une vue facile du résumé des détails est désormais disponible. Vous pouvez afficher [!UICONTROL Pipeline] s’exécute avec les détails associés.
      * Le [!UICONTROL Modifier le pipeline] L’API prend désormais en charge la modification de l’environnement utilisé dans les phases de déploiement.
      * Une optimisation dans la variable [!DNL OakPal] le processus d’analyse est désormais disponible pour les modules volumineux.
      * Le fichier CSV de problème de qualité contient désormais l’horodatage de chaque problème de qualité.





### Nouveaux cours et tutoriels sur Experience Manager {#tutorials-aem}

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publication | Nom | Type | Description | Application |
| -----------| ---------- | ---------- | ---------- | ----- |
| Janvier 2022 | [Extension d’Adobe Experience Manager as a Cloud Service à l’aide d’Adobe Developer App Builder](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/configuring-and-extending/app-builder/extending-aem-with-app-builder.html?lang=en) | Vidéo (plusieurs) | Le nouveau développeur d’applications Adobe fournit une structure d’extensibilité permettant aux développeurs d’étendre facilement AEM fonctionnalités as a Cloud Service. | AEM as a Cloud Service |
| Janvier 2022 | [Configuration rapide AEM sans affichage pour AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/quick-setup/cloud-service.html) | Vidéo | Regardez la configuration rapide AEM sans affichage . Il vous permet de disposer d’AEM sans affichage grâce au contenu de l’exemple de projet de site WKND et d’un exemple d’application React (un SPA) qui consomme le contenu via les API GraphQL sans affichage. | AEM as a Cloud Service |
| Janvier 2022 | [Mise en réseau avancée](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/advanced-networking.html?lang=en) | Vidéo (plusieurs) | Découvrez comment AEM as a Cloud Service propose trois options pour gérer la connectivité avec les services externes : Sortie de port flexible, adresse IP de sortie dédiée et réseau privé virtuel. Un programme et des environnements Cloud Manager dans AEM as a Cloud Service ne peuvent utiliser qu’un seul type de configuration réseau avancée à la fois. | AEM as a Cloud Service |
| Janvier 2022 | [Enrichir les données de produit avec le contenu AEM associé](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/enrich-product-associated-content.html?lang=en) | Vidéo | Découvrez comment les professionnels du marketing peuvent enrichir les données de produit avec du contenu associé à partir d’Adobe Experience Manager. Contenu, comme des ressources, [!UICONTROL Fragments d’expérience], et [!UICONTROL Fragments de contenu] dans AEM peut être associé à des produits commerciaux. | AEM as a Cloud Service |
| Janvier 2022 | [Service Email](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/examples/email-service.html?lang=en) | Vidéo | Envoyez des e-mails à partir d’AEM as a Cloud Service en configurant AEM’s `DefaultMailService` pour utiliser les ports de sortie réseau avancés. | AEM as a Cloud Service |
| Janvier 2022 | [Notions de base sur les connecteurs améliorés Workfront](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html?lang=en) | Vidéo | Découvrez les principes de base du connecteur amélioré Adobe Workfront et Experience Manager Assets. En savoir plus [Dossiers de projets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/project-folders.html?lang=en). | Service AEM Assets et Workfront |
| Janvier 2022 | [Prise en main d’AEM Sites - Création rapide d’un site](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html?lang=en) | Vidéo (plusieurs) | Découvrez comment utiliser une approche à code faible pour créer votre premier site dans Adobe Experience Manager avec la création rapide de site et un modèle de site prédéfini. | AEM Sites |
| Janvier 2022 | [Connexions HTTP/HTTPS sur les ports non standard pour une sortie de port flexible](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/examples/http-on-non-standard-ports-flexible-port-egress.html?lang=en) | Vidéo (plusieurs) | Découvrez comment les connexions HTTP/HTTPS sur les ports non standard (et non 80/443) doivent être traitées par proxy hors d’AEM as a Cloud Service. | AEM as a Cloud Service |
| Janvier 2022 | [Ajouter des icônes pour indiquer les onglets principal et terminé](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/ui-tips-and-tricks/active-complete.html?lang=en) | Vidéo | Découvrez comment afficher des icônes pour indiquer l’état de l’onglet lorsque vous disposez d’un formulaire adaptatif avec navigation par onglets gauche. | AEM Forms |
| Janvier 2022 | [Configuration d’Adobe Asset Link](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/adobe-asset-link/setup.html?lang=en) | Vidéo | Apportez un impact rapide à votre entreprise en facilitant la collaboration des équipes créatives et marketing sur les ressources dans le processus de création de contenu. | AEM Assets |
| Janvier 2022 | [Prise en main d’AEM Commerce as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/getting-started.html?lang=en) | Vidéo | Découvrez comment les professionnels du marketing peuvent enrichir les données de produit avec du contenu associé à partir d’Adobe Experience Manager. Le contenu, comme les ressources, les fragments d’expérience et les fragments de contenu dans AEM peuvent être associés à des produits commerciaux. | AEM as a Cloud Service |
| Janvier 2022 | [Prise en main d’AEM Sites - Création rapide d’un site](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html) | Vidéo | Découvrez comment utiliser une approche à code faible pour créer votre premier site dans Adobe Experience Manager avec la création rapide de site et un modèle de site prédéfini. | AEM Sites |
| Janvier 2022 | [Enrichir les données de produit avec le contenu AEM associé](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/enrich-product-associated-content.html) | Vidéo | Découvrez comment les professionnels du marketing peuvent enrichir les données de produit avec du contenu associé à partir d’Adobe Experience Manager. Le contenu, comme les ressources, les fragments d’expérience et les fragments de contenu dans AEM peuvent être associés à des produits commerciaux. | AEM as a Cloud Service |

{style=&quot;table-layout:auto&quot;}

### Informations de mise à jour d’Experience Manager

Toutes les notes de mise à jour d’Experience Manager sont conservées dans les pages suivantes :

* [Informations de mise à jour d’Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=en)
* [Notes de mise à jour de Cloud Manager d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=fr)
* [Notes de mise à jour du service de conversion automatisée de formulaires](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=fr)
* [Notes de mise à jour du Service Pack 6.5 d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
* [Notes de mise à jour du pack de correctifs cumulatifs 6.4 d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=fr)
* [Notes de mise à jour de l’appli de bureau Experience Manager ](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=fr)
* [Notes de mise à jour d’Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=fr)
* [Notes de mise à jour de Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=fr)

### Autres ressources dʼaide pour Experience Manager

* [Guides relatifs à Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=en)
* [Guide de l’utilisateur de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=fr#previous-updates)
* [Versions plus anciennes de la documentation pour Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=fr)
* [Documentation Experience Manager : mises à jour récentes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=fr#aem-as-a-cloud-service)

## Documentation XML pour Adobe Experience Manager {#xml-doc}

La documentation XML pour Adobe Experience Manager est une application déployée sur AEM. Il s’agit d’une puissante solution de gestion de contenu de composant (CCMS) de niveau entreprise qui permet la prise en charge native de DITA dans Adobe Experience Manager, ce qui permet à AEM de gérer la création et la diffusion de contenu basé sur DITA. En savoir plus sur [XML Documentation pour AEM](https://www.adobe.com/products/xml-documentation-for-experience-manager/features.html).

### Nouveaux tutoriels pour la documentation XML pour Adobe Experience Manager {#tutorials-xml-doc}

Nouveaux tutoriels, vidéos ou cours publiés pour la documentation XML pour Adobe Experience Manager.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Janvier 2022 | [Versions de documentation XML](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/tutorials/release-info/latest-release-info.html?lang=en) | Vidéo | Découvrez la documentation XML pour Adobe Experience Manager, une solution de gestion de contenu (CCMS) performante et de qualité professionnelle. Il active la prise en charge native de DITA dans Adobe Experience Manager, ce qui permet à AEM de gérer la création et la diffusion de contenu basé sur DITA. |
| Janvier 2022 | [Génération de sortie avec documentation XML pour AEM](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/output-generation/overview.html?lang=en) | Vidéos et articles | Découvrez le tableau de bord des cartes, les rapports, la publication avec des conditions et des lignes de base, etc. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/magento.png) [!DNL Adobe Commerce] {#magento}

Voir les liens suivants pour consulter les notes de mise à jour dʼAdobe Commerce :

* [Adobe Commerce et Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite pour Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Nouveaux tutoriels Adobe Commerce {#tutorials-commerce}

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Janvier 2022 | [Business Intelligence](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/getting-started/business-intelligence/1-overview.html) | Vidéo (plusieurs) | Commencez par la présentation et découvrez-en plus sur Business Intelligence, une solution complète qui a été optimisée pour tous les marchands Adobe Commerce et Magento Open Sources. |
| Janvier 2022 | [Utilisateurs, rôles et autorisations](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/users-roles-permissions.html) | Vidéo | Découvrez comment créer un compte d’utilisateur distinct pour chaque utilisateur et attribuer un accès restreint en fonction de ses besoins professionnels. |
| Janvier 2022 | [Authentification à deux facteurs](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/two-factor-authentication.html) | Vidéo | Découvrez comment l’authentification à deux facteurs (2FA) empêche tout accès non autorisé à vos données. Adobe Commerce et Magento Open Source prennent en charge les méthodes d’authentification à deux facteurs de plusieurs fournisseurs. |
| Janvier 2022 | [Ajout de sites web, de magasins et d’affichages de magasin](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/add-websites-stores-views.html) | Vidéo | Découvrez comment chaque installation d’Adobe Commerce et de Magento Open Source prend en charge une hiérarchie de sites web, de magasins et de vues de magasin. Créez et développez cette hiérarchie en fonction des besoins de votre entreprise. |
| Janvier 2022 | [Modification de l’URL d’un magasin](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/change-store-url.html) | Vidéo | Découvrez comment modifier l’URL de base de votre magasin. (Le contenu de la vidéo reflète la version 2.1.0.) |
| Janvier 2022 | [Configuration d’une carte du site du magasin](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/site-map-setup.html) | Vidéo | Découvrez comment ajouter facilement un plan de site à votre boutique Commerce. |
| Janvier 2022 | [Règles de prix promotionnelles](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/promotions-price-rules.html) | Vidéo | Découvrez comment configurer les relations entre les produits et utiliser les règles de prix pour déclencher des remises selon diverses conditions. |
| Janvier 2022 | [Création d’une page](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/frontend-development/create-new-page.html) | Vidéo | Découvrez comment créer une page qui renvoie JSON avec un paramètre. |
| Janvier 2022 | [Ajout d’un module JavaScript](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/frontend-development/add-javascript-module.html) | Vidéo | Découvrez le développement d’un module JS simple qui fournit le message &quot;Hello World&quot;. |
| Janvier 2022 | [Aperçu du créateur de pages](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/page-builder-overview.html) | Vidéo | Découvrez comment le Créateur de pages facilite la création de pages riches en contenu avec des dispositions personnalisées qui améliorent votre narration visuelle et favorisent l’engagement et la fidélité des clients. |
| Janvier 2022 | [Ajouter une table à une base de données](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/add-new-db-table.html?lang=en) | Vidéo | Découvrez le mécanisme spécial dans Commerce qui vous permet de créer des tables de base de données, de modifier les tables existantes et d’y ajouter des données, telles que les données de configuration, qui doivent être ajoutées lorsqu’un module est installé. |
| Janvier 2022 | [Création d’un module](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/create-module.html) | Vidéo | Module est un élément structurel de Commerce : l’ensemble du système repose sur des modules. En règle générale, la première étape de la création d’une personnalisation est la création d’un module. |
| Janvier 2022 | [Création d’un attribut de produit](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/add-product-attribute.html) | Vidéo | Découvrez comment ajouter un attribut de produit, l’une des opérations les plus populaires dans Commerce. Les attributs sont un moyen puissant de résoudre de nombreuses tâches pratiques liées à un produit. |
| Janvier 2022 | [Exemple d’injection de dépendance](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/dependency-injection.html) | Vidéo | Découvrez l’injection de dépendance, un modèle de conception qui permet à un objet A de déclarer ses dépendances à un objet externe B qui fournit ces dépendances. Les dépendances déclarées par A sont généralement des interfaces de classe et les dépendances fournies par B sont des implémentations concrètes pour ces interfaces. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/target.png) [!DNL Adobe Target] {#target}

Dernière mise à jour : **10 janvier 2022**

Voir [Notes de mise à jour de Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=fr) pour obtenir les informations les plus récentes.

## ![Icône](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Dernières mises à jour d’Adobe Campaign

Pour en savoir plus sur les dernières fonctionnalités, améliorations et correctifs disponibles :

* [Version de Campaign v7.2](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=fr)

### Nouveau [!DNL Campaign] tutoriels et cours {#tutorials-campaign}

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Campaign.

| Publication | Nom | Type | Description | Version   |
| ------| ----- | -----| ------ | --- |
| Janvier 2022 | [Déploiement d&#39;un modèle de diffusion e-mail ad hoc](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/using-delivery-templates/deploy-ad-hoc-email-delivery-template.html?lang=en) | Vidéo | Découvrez comment déployer un modèle de diffusion email ad hoc et explique la différence entre une diffusion email et un workflow de diffusion. | Campaign v8 |
| Janvier 2022 | [Définition des propriétés du modèle de diffusion](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/using-delivery-templates/set-delivery-template-properties.html?lang=en) | Vidéo | Découvrez comment définir les propriétés du modèle de diffusion et obtenez des détails sur chaque propriété. | Campaign v8 |
| Janvier 2022 | [Configuration des validations pour les campagnes](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.html?lang=en) | Vidéo | Découvrez comment configurer les validations et les validants au niveau de la campagne. | Campaign v8 |
| Janvier 2022 | [Création d’un processus de validation dans un workflow](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.html?lang=en) | Vidéo | Découvrez comment créer un processus de validation dans un workflow pour permettre la révision et la validation de la logique de sélection du ciblage avant le lancement de la diffusion. | Campaign v8 |
| Janvier 2022 | [Configuration des validations pour les diffusions](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.html?lang=en) | Vidéo | Découvrez comment configurer les validations et les validants au niveau de la diffusion. | Campaign v8 |
| Janvier 2022 | [Mécanisme d’évaluation des API avec FFDA](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/api-staging-mechanism.html?lang=en) | Vidéo | Découvrez comment fonctionne le mécanisme d’évaluation de l’API avec FDA complet. Découvrez pourquoi l’évaluation est utilisée, les principes principaux de l’évaluation dans Adobe Campaign et comment activer le mécanisme d’évaluation pour une table personnalisée. | Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### Ressources d’aide pour Campaign

* Adobe Campaign v8 : [Documentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=fr) - [Guides d’implémentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=fr)
* Adobe Campaign Standard : [Documentation de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=fr) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=fr) - [Calendrier des versions](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=fr)
* Adobe Campaign Classic : [Documentation de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=fr)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=fr) - Tutoriels vidéo pour [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=fr)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=fr)

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

 Journey Optimizer vous permet de gérer des campagnes omnicanales planifiées et des moments de contact individuel pour des millions de clients à partir dʼune seule application. Lʼensemble du parcours est optimisé grâce à une prise de décision et des informations intelligentes.

### Dernières versions de produit pour Journey Optimizer

Découvrez les dernières fonctionnalités, améliorations et correctifs dans les [Notes de mise à jour de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=fr).

### Ressources supplémentaires pour [!DNL Journey Optimizer]

* [Documentation Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vidéos pratiques](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=fr)
* [Documentation de la gestion des décisions](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vidéos pratiques](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=fr)

## ![Icône](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Utilisez Experience Platform pour orchestrer le parcours dʼun client à lʼéchelle appropriée au sein de différents canaux dʼexpérience, en anticipant intelligemment les besoins de chacun en temps réel.

### Dernières mises à jour du produit [!DNL Journey Orchestration]

Découvrez les dernières fonctionnalités, améliorations et correctifs dans les Notes de mise à jour de [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=fr).

#### Ressources supplémentaires pour [!DNL Journey Orchestration]

* [Documentation de Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Vidéos pratiques](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=fr)

## ![Icône](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] est une application complète pour la gestion des leads et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en s’engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Voir le [calendrier des versions](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=fr) de [!DNL Marketo Engage] pour consulter les informations les plus récentes sur le calendrier des versions et les notes de mise à jour.

## ![Icône](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] est une application de gestion du travail unifiée qui permet de partager des idées, créer du contenu, gérer des processus complexes et donner le meilleur de soi-même.

Consultez la page [[!DNL Workfront] versions](https://one.workfront.com/s/product-releases) pour obtenir un récapitulatif des dernières informations relatives à lʼensemble des produits.

## ![Icône](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Notes de mise à jour dʼ[!DNL Adobe Advertising Cloud].

* [Nouvelles fonctionnalités dans  [!DNL Advertising Cloud]](#adcloud-all)
* [Nouveautés de la version  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Nouveautés de la version  [!DNL Advertising Cloud Search]](#adcloud-search)
* [Nouveau [!DNL Advertising Cloud] tutoriels](#tutorials-ad-cloud)

### Nouvelles fonctionnalités dans [!DNL Advertising Cloud] {#adcloud-all}

Dernière mise à jour : **27 octobre 2021**

| Fonctionnalité | Description |
| ------- | ----------- |
| Analytics pour Advertising Cloud | Si votre entreprise souhaite ne plus utiliser l’Adobe Analytics hérité `visitorAPI.js` à la bibliothèque Adobe Experience Platform (`alloy.js`) pour la collecte de données, vous devez apporter quelques modifications pour activer le regroupement des identifiants. Voir [En utilisant la variable [!DNL Last Event Service] Bibliothèque JavaScript avec Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=fr). |

{style=&quot;table-layout:auto&quot;}

### Nouveautés de la version [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Dernière mise à jour : **27 octobre 2021**

| Fonctionnalité | Description |
| ------- | ----------- |
| Rapports personnalisés | Vous pouvez désormais créer et gérer des emplacements [!DNL Amazon S3] et différents types d’emplacements de distribution FTP, appelés *[!DNL report destinations]*, pour vos rapports personnalisés. Une fois la configuration des destinations de rapports effectuée, vous pouvez configurer chaque nouveau rapport personnalisé afin de le diffuser vers un ou plusieurs emplacements d’un seul type de destination, ou vers des destinataires d’e-mails. Les mises à jour de vos identifiants [!DNL Amazon S3] et FTP n’interrompront pas la diffusion des rapports.<br><br>Vos rapports existants sont toujours envoyés aux destinataires d’e-mails spécifiés. Pour configurer une diffusion vers une autre destination de rapport, créez un rapport avec la nouvelle destination. |
| Vues de [!UICONTROL Packages], d’[!UICONTROL Emplacements] et de [!UICONTROL Publicités] | Lorsque vous affichez des données pour un seul jour, les graphiques de tendance incluent désormais des données horaires. Placez le curseur sur n’importe quel point pour afficher les données de cette heure. |
| [!UICONTROL Emplacements] | L’emplacement [!UICONTROL Inspecteur] inclut désormais un onglet [!UICONTROL Inventaire], qui affiche toutes les offres et les mesures associées pour l’emplacement. Utilisez les informations pour effectuer des ajustements rapides ou résoudre les problèmes sans générer de rapport personnalisé. |
| [!UICONTROL Publicités] | (Utilisateurs autorisés à inclure des numéros d’horloge Clearcast dans leurs publicités) DSP n’affiche plus d’erreur si vous utilisez un numéro d’horloge joint à une autre publicité. **Remarque :** La bonne pratique consiste à utiliser un numéro d’horloge unique pour chaque publicité vidéo. Dans le cas contraire, l’éditeur n’approuve pas toutes les publicités. |
| [!UICONTROL ID d’offres] | Les paramètres des [!UICONTROL ID d’offres] et autres emplacements de l’interface utilisateur reflètent la nouvelle valorisation de marque du SSP [!DNL Magnite] :<br><ul><li>Le SSP [!DNL Tremor] ([!DNL Telaria]) est maintenant [!DNL Magnite CTV].</li><li>Dans les semaines à venir, [!DNL Rubicon] changera en [!DNL Magnite DV+]où [!DNL DV+] désigne l’affichage, la vidéo et d’autres formats tels que l’audio.</li></ul> |
| [!DNL Freewheel] offres garanties par programmation | Vous pouvez maintenant trouver l’état des publicités pour [!DNL Freewheel] offres garanties par programmation par le [!UICONTROL Publicités] vue. Auparavant, vous pouviez uniquement vérifier le statut à partir de la vue [!UICONTROL Offres]. |

{style=&quot;table-layout:auto&quot;}

### Nouveautés de la version [!DNL Advertising Cloud Search] {#adcloud-search}

Dernière mise à jour : **7 octobre 2021**

| Fonctionnalité | Description |
| ------- | ----------- |
| [!UICONTROL Rapports], [!UICONTROL Centre de notifications] | (Version du 9 octobre) Toutes les notifications par e-mail des rapports, envoyées par Advertising Cloud Search lorsqu’un rapport personnalisé ou planifié est terminé ou a échoué, sont désormais gérées par le [!UICONTROL Centre de notifications]. Les notifications par e-mail et les notifications web sont activées par défaut pour les rapports, mais vous pouvez éventuellement modifier les paramètres de notification. Avec cette modification :<ul><li>Les destinataires dʼe-mails sont limités aux utilisateurs enregistrés et authentifiés dʼAdvertising Cloud Search qui ont accès au compte de lʼannonceur. Cette fonctionnalité garantit quʼaucune donnée confidentielle nʼest envoyée à des utilisateurs non autorisés.</li><li>Le format et le contenu de l’e-mail utilisent le modèle du [!UICONTROL Centre de notifications], qui inclut des détails supplémentaires sur le rapport et des liens de téléchargement direct pour tous les formats de rapport.</li><li>Les notifications de rapport sont un nouveau type de notification, avec ses propres préférences, dans le [!UICONTROL Centre de notifications].</li></ul>Si vous utilisez une automatisation pour extraire des rapports des notifications par e-mail, vous devrez peut-être mettre à jour la logique de filtrage pour assurer la continuité du processus. |
| Informations publicitaires | Des informations supplémentaires sont disponibles dans le mode Beta. |

{style=&quot;table-layout:auto&quot;}

### Nouveaux tutoriels Advertising Cloud {#tutorials-ad-cloud}

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Janvier 2022 | [Tutoriels sur Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/intro.html?lang=en) | Vidéos | Cinq nouveaux tutoriels vidéo sur Advertising Cloud DSP sont disponibles. |

## ![Icône](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Document Cloud.

### Nouveaux cours et tutoriels sur les Documents Cloud {#tutorials-doc-cloud}

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Campaign.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Janvier 2022 | [Amélioration de votre PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/enhance.html?lang=en) | Vidéo | Dans ce tutoriel pratique, apprenez à transformer votre PDF en ajoutant des améliorations graphiques et une numérotation automatique. |
| Janvier 2022 | [Utilisation plus intelligente d’Acrobat DC et Microsoft® 365](https://experienceleague.adobe.com/?recommended=Acrobat-U-1-2021.microsoft365) | Cours | Découvrez des outils PDF puissants à l’intérieur de [!DNL Microsoft® 365] et [!DNL Acrobat DC] pour remplacer des workflows de document obsolètes et rompus. Découvrez comment automatiser les processus de documentation manuels afin d’éviter les retards et les erreurs, d’améliorer la sécurité et la productivité et de proposer des expériences client et employé exceptionnelles, le tout dans les outils Microsoft® et Acrobat que vous utilisez déjà. |

{style=&quot;table-layout:auto&quot;}

Pour obtenir de l’aide sur Document Cloud, voir :

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=fr)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=fr)
* [Formation et support Adobe Document Cloud](https://helpx.adobe.com/fr/support/document-cloud.html)

## ![Icône](/assets/creative-cloud-24.png) Adobe Creative Cloud for enterprise {#creative-cloud}

Pour consulter les derniers tutoriels, voir les [tutoriels Creative Cloud abonnement Enterprise](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=fr).

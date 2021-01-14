---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Notes de mise à jour d’Adobe Experience Cloud
doc-type: release notes
last-update: January 2021
author: mfrei
translation-type: tm+mt
source-git-commit: 026ae3842b9683ac8c55658964969d5deca75340
workflow-type: tm+mt
source-wordcount: '6618'
ht-degree: 41%

---


# Notes de mise à jour de Adobe Experience Cloud - Janvier 2021

![Bannière](/assets/experience-cloud-banner-3.png)

Cette page décrit les nouvelles fonctionnalités, les correctifs et des informations importantes pour [!DNL Adobe Experience Cloud]. Elle met également en évidence la nouvelle documentation, les formations et les tutoriels vidéo qui vous permettent de tirer le meilleur parti d’Experience Cloud.

>[!NOTE]
>
>Abonnez-vous à la [mise à jour de produit prioritaire de l&#39;Adobe ](https://www.adobe.com/subscription/priority-product-update.html) mensuelle pour recevoir des notifications par courrier électronique sur les mises à jour de cette page. Cette page est tenue à jour tout au long du mois. Veuillez donc consulter régulièrement les mises à jour des produits Adobe Enterprise et de la documentation Experience League.

Dernière mise à jour : **14 janvier 2021**

* [État](#status)  du système d&#39;Adobe (non mis à jour)
* [Services d’Experience Cloud et administration](#ecloud)
* [Experience Platform](#platform)  (Mis à jour le 14  **janvier 2021**)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) et [Customer Journey Analytics](#cust-journey) (Mise à jour : **12 janvier 2021**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)  (Mis à jour le 12  **janvier 2021**)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo) (Mise à jour :  **11 janvier 2021**)
* [Document Cloud](#doc-cloud)

Besoin d’aide ? Consultez [Adobe Experience League](https://experienceleague.adobe.com/?lang=fr-FR#home) pour trouver de la documentation technique et sur les produits, des cours préparés par Adobe, des tutoriels vidéo, des réponses rapides, des informations provenant de la communauté et des formations dispensées par un instructeur. Le contenu a été déplacé de `docs.adobe.com` vers cet emplacement. Mettez à jour les signets en conséquence.

## ![Icône](/assets/adobe.png) Statut du système Adobe {#status}

[!UICONTROL Statut du système Adobe] fournit des informations détaillées, des mises à jour de statut et des notifications par email relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

Aucune mise à jour ce mois-ci.

Voir [Statut d’Adobe - 21 mai 2020](https://docs.adobe.com/content/help/fr-FR/release-notes/experience-cloud/previous/2020/05212020.html#status) pour obtenir les dernières informations de mise à jour.

## ![Icône](/assets/ec_appicon_24.png) Services d’Experience Cloud et administration {#ecloud}

[La documentation sur les services et ](https://docs.adobe.com/content/help/fr-FR/core-services/interface/experience-cloud.html) l’administration des Experience Cloud comprend les attributs du client, la bibliothèque d’Audiences ( Peopleservice), l’Activation, la gestion des utilisateurs et des produits et les cookies Experience Cloud.

Aucune mise à jour ce mois-ci.

**Voir également**

* [Notes de mise à jour cumulées pour les ](https://docs.adobe.com/content/help/fr-FR/core-services/interface/release-notes/release-notes.html) services Experience Cloud pour les informations les plus récentes.
* [Notes ](https://experienceleague.adobe.com/docs/id-service/using/release-notes/release-notes.html) de mise à jour de l’identifiant Experience Cloud

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Inclut les informations de mise à jour pour Experience Platform et Experience Platform Launch.

| Fonction | Date de publication | Description |
| ------- | ------| ------- |
| Amélioration de l&#39;interaction de prise en charge des produits pour les Experience Platform | 15 janvier 2021 | Vous pouvez maintenant poser une question ou signaler un problème à un Experience Platform sans quitter votre interface Experience Platform. Accédez à **[!UICONTROL Aide]** > **[!UICONTROL Assistance]** > **[!UICONTROL Créez un ticket d&#39;assistance]**, puis entrez votre question et envoyez votre dossier directement au Service clientèle. Vous recevrez une notification par courrier électronique avec un ID de dossier et l’équipe d’assistance clientèle vous contactera par ticket pour répondre à vos besoins. |

Dernière mise à jour : **9 décembre 2020**

Voir [Notes de mise à jour des Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=en) pour connaître les mises à jour les plus récentes concernant :

* [!UICONTROL Flux de données]
* [!UICONTROL Data Science Workspace]
* [!UICONTROL Sources]

### Experience Platform Launch

Date de publication : **13 janvier 2021**

**[!UICONTROL Lancement côté] serveur :** envoi de données de niveau événement à AEP Edge Network, puis utilisation de Lancement côté serveur pour transformer, enrichir et envoyer ces données à un point de terminaison non-Adobe à l’aide des serveurs de l’Adobe et non du client, avec une faible latence. [Plus…](https://experienceleague.adobe.com/docs/launch/using/server-side-info/server-side-overview.html?lang=en#server-side-info)

**Voir également**

* [](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html) Notes de mise à jour de l’Experience Platform Launch pour plus d’informations sur l’Experience Platform Launch.
* [Notes de mise à jour sur l’](https://experienceleague.adobe.com/docs/launch/using/extensions-ref/adobe-extension/id-service-extension/experience-cloud-id-release-notes.html) extension du service d’identification des Experience Cloud

### Adobe Mobile

Mise à jour du **14 janvier 2021**

iOS version 4.21.1

* Général - Correction d’un problème en raison duquel des exceptions SQLite pouvaient survenir lors de l’arrêt de l’application.

iOS version 4.21.0

* Général - Le SDK est maintenant distribué à l&#39;aide de [!DNL XCFrameworks] pour prendre en charge le matériel avec la nouvelle architecture Apple M1 tout en maintenant la prise en charge de l&#39;architecture Intel existante.

* IMPORTANT : La mise à niveau vers AdobeMobile [!DNL XCFrameworks] requiert Xcode 12.0 ou version ultérieure.
* IMPORTANT : Si vous utilisez [!DNL Cocoapods], la mise à niveau vers AdobeMobile [!DNL XCFrameworks] nécessite [!DNL Cocoapods] 1.10.0 ou une version ultérieure.

### Tutoriels et cours sur Experience Platform et ses services

Nouveaux tutoriels, vidéos ou cours publiés pour Experience Platform et ses services.

Mise à jour : **6 janvier 2021**

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 23 décembre 2020 | [Présentation des schémas d’Union](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/union-schemas-overview.html) | Vidéo | Découvrez les schémas d’union utilisés par le Profil client en temps réel de Adobe Experience Platform. |
| 22 décembre 2020 | [Création de segments à plusieurs entités](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-multi-entity-segments.html) | Vidéo | Découvrez comment créer des segments à plusieurs entités dans le créateur de segments de Adobe Experience Platform. |
| 21 décembre 2020 | [Créer des activités d’offre](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-offer-activities.html) | Vidéo | Découvrez comment créer des activités d&#39;offre dans [!UICONTROL Offer Decisioning]. Une activité d’offre combine vos emplacements et vos collections en une seule entité, de sorte qu’une décision puisse être prise pour fournir l’offre la plus pertinente au client. |
| 21 décembre 2020 | [Créer des collections](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-collections.html) | Vidéo | Découvrez comment créer des collections dans [!UICONTROL Offer Decisioning]. Les collections sont utilisées pour gérer les offres dans des groupes logiques et sont nécessaires pour créer des activités Offer Decisioning. |
| 21 décembre 2020 | [Fourniture d&#39;offres avec l&#39;API Décisions](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/deliver-offers-with-the-decisions-api.html) | Vidéo | Découvrez comment fournir des offres [!UICONTROL Offer Decisioning] avec l&#39;API Décisions. |
| 15 décembre 2020 | [Créer des offres personnalisées](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-personalized-offers.html) | Vidéo | Découvrez comment créer des offres personnalisées dans [!UICONTROL Offer Decisioning]. |
| 15 décembre 2020 | [Créer des offres de secours](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-fallback-offers.html) | Vidéo | Découvrez comment créer des offres de secours dans [!UICONTROL Offer Decisioning]. |
| 14 décembre 2020 (Mise à jour) | [Présentation de Real-time Customer Profile](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/understanding-the-real-time-customer-profile.html) | Vidéo | Cette vidéo explique comment Adobe Experience Platform assemble et met à jour des Profils client en temps réel et comment vous pouvez accéder à ces profils et les utiliser. |
| 10 décembre 2020 | [Créer des balises](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-tags.html) | Vidéo | Découvrez comment créer des balises dans [!UICONTROL Offer Decisioning]. Les balises sont des composants facultatifs des blocs de construction des offres. Ils peuvent être utilisés pour organiser les offres et les regrouper dans des collections dynamiques. |
| 9 décembre 2020 | [Création de règles en Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-rules.html) | Vidéo | Découvrez comment créer des règles dans [!UICONTROL Offer Decisioning]. Les règles sont créées à l’aide des événements et des attributs dans le [!UICONTROL Profil client en temps réel] de la plateforme et constituent les contraintes d’éligibilité des offres. |
| 9 décembre 2020 | [Créer des emplacements](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-placements.html) | Vidéo | Découvrez comment créer des emplacements en Offer Decisioning. Un emplacement est la combinaison du type de contenu et du canal, par exemple une image dans un courrier électronique ou du code HTML sur un site Web. |
| 29 octobre 2020 (Mise à jour) | [Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/demo-of-offer-decisioning.html?lang=fr-FR) | Vidéo | Découvrez comment les marques peuvent utiliser le nouveau service [!UICONTROL Offer Decisioning] d’Adobe pour définir et gérer leurs offres, exploiter les données client en temps réel et offrir les expériences adéquates que leurs clients attendent. |
| 26 octobre 2020 (Mise à jour) | [Introduction à Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/introduction-to-offer-decisioning.html) | Vidéo | Cette vidéo offre un aperçu d’[!UICONTROL Offer Decisioning], un service d’applications qui complète Adobe Experience Platform. La vidéo traite des problématiques métier qu’[!UICONTROL Offer Decisioning] permet de résoudre, des principales fonctionnalités de ce service, de l’architecture de base et des principaux cas pratiques. |
| 26 octobre 2020 (Mise à jour) | [Envoi de données à l’aide du connecteur source CRM Salesforce](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | Vidéo | Le connecteur de source de gestion de la relation client Salesforce vous permet d’assimiler facilement par lots des données de la gestion de la relation client Salesforce dans le Profil client en temps réel de Adobe Experience Platform et le lac de données d’expérience, de manière transparente et évolutive. |
| 13 octobre 2020 (Mise à jour) | [Envoi de données à l’aide du connecteur source CRM Salesforce](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | Vidéo | Le connecteur de source de gestion de la relation client Salesforce vous permet d’assimiler facilement par lots des données de la gestion de la relation client Salesforce dans le Profil client en temps réel de Adobe Experience Platform et le lac de données d’expérience, de manière transparente et évolutive. |
| 23 octobre 2020 (Mise à jour) | [Intégrer les données dans le Profil client en temps réel](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html) | Vidéo | Le Profil client en temps réel permet la personnalisation croisée des canaux à l’échelle de chaque phase du parcours client. |
| 13 octobre 2020 (Mise à jour) | [Configuration d’Attribution AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-attribution-ai.html) | Vidéo | Découvrez comment créer une instance d’Attribution AI pour comprendre l’impact de vos canaux et campagnes marketing. |
| 13 octobre 2020 (Mise à jour) | [Configuration de Customer AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-customer-ai.html) | Vidéo | Découvrez comment créer une instance de Customer AI pour prédire le comportement du client. |

## ![Icône](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Utilisez Adobe Experience Platform pour orchestrer le parcours d’un client à l’échelle de tous les canaux d’expérience, en anticipant intelligemment les besoins de chacun en temps réel.

### Nouvelles versions de produits

* Version de novembre - [En savoir plus](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html#november-release)
* Version d’octobre - [En savoir plus](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html#october-release)

### Ressources supplémentaires pour Journey Orchestration

[Documentation](https://docs.adobe.com/content/help/fr-FR/journeys/using/journey-orchestration-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html) - [Tutoriels vidéos](https://docs.adobe.com/content/help/fr-FR/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Icône](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Date de publication : **14 janvier 2021**

* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features)
* [Nouvelles fonctionnalités dans Customer Journey Analytics](#cust-journey)
* [Correctifs dans Adobe Analytics](#aa-fixes)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)
* [Report Builder](#arb)

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.html) - Date cible | Description |
| ----------- | ---------- | ------- |
| Analysis Workspace - URL des images | 14 janvier 2021 | Vous pouvez ajouter des images à des projets [!UICONTROL Workspace] en référençant une URL d’image publique. [En savoir plus](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/visualizations/text.html?lang=en#analysis-workspace) |
| Analysis Workspace - Gestionnaire des sources et des paramètres combinés | 14 janvier 2021 | Le gestionnaire de source de données (point) et le gestionnaire de paramètres (engrenage) pour les visualisations ont été combinés dans une seule boîte de dialogue, afin que vous puissiez facilement gérer votre source et vos paramètres à partir du même emplacement. |
| Analysis Workspace - Sélection de composants | 4 février 2021 | Le composant de zone de dépôt/liste déroulante trouvé dans [!UICONTROL Quick Insights] a été ajouté à toutes les zones de dépôt dans [!UICONTROL Workspace]. Cette amélioration vous permet de choisir parmi une liste déroulante de composants compatibles ou de continuer à utiliser l’espace comme zone de dépôt. |

### Nouvelles fonctionnalités dans Customer Journey Analytics {#cust-journey}

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Date cible | Description |
| ----------- | ---------- | ----- |
| Dimensions [!UICONTROL Appareil] et [!UICONTROL Géographie] | 30 octobre 2020 | Ces dimensions sont désormais disponibles par défaut dans le cadre du projet de prise en charge [Recherche globale](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-usecases/global-lookups.html?lang=en#use-global-lookups-with-adobe-data-connector-datasets) de l’Adobe Analytics [!UICONTROL Source Connector]. Cet ajout très demandé augmente la [parité entre Adobe Analytics et CJA](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-overview/cja-aa.html?lang=en#cja-overview). |
| QI parcours : [!UICONTROL Analyses entre Canaux] | 11 janvier 2021 | QI parcours : [!UICONTROL Analyses de plusieurs Canaux] vous permet de recréer un jeu de données de événement Adobe Analytics (ou autre) dans le lac de données Experience Platform d’un espace de nommage d’ID à un autre. En règle générale, cela signifie recréer le jeu de données d’événement d’un identifiant basé sur un cookie vers un identifiant basé sur une personne. De cette façon, le jeu de données recyclé peut être combiné avec d&#39;autres données personnelles dans une connexion CJA, ce qui permet l&#39;analyse entre les périphériques et entre les canaux dans Analysis Workspace. [En savoir plus](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/cca/overview.html?lang=fr-FR#cja-connections) |
| Analysis Workspace - URL des images | 14 janvier 2021 | Vous pouvez ajouter des images à des projets Workspace en référençant une URL d’image publique. |
| Analysis Workspace - Gestionnaire des sources et des paramètres combinés | 14 janvier 2021 | Le gestionnaire de source de données (point) et le gestionnaire de paramètres (engrenage) pour les visualisations ont été combinés dans une seule boîte de dialogue, afin que vous puissiez facilement gérer votre source et vos paramètres à partir du même emplacement. |
| Analysis Workspace - Sélection de composants | 4 février 2021 | Le composant de zone de dépôt/liste déroulante trouvé dans [!UICONTROL Quick Insights] a été ajouté à toutes les zones de dépôt dans [!UICONTROL Workspace]. Cette amélioration vous permet de choisir parmi une liste déroulante de composants compatibles ou de continuer à utiliser l’espace comme zone de dépôt. |

### Correctifs dans Adobe Analytics {#aa-fixes}

* Correction de problèmes de mise en forme, de téléchargement et d’envoi de rapports CSV téléchargés dans Workspace. (AN-224844)
AN-240295)
* Correction d’un problème en raison duquel aucune donnée pour les attributs mobiles n’apparaissait dans Livestream même si la suite de rapports Analytics contenait des données. (AN-241169)
* Correction d’un problème en raison duquel le rapport Temps réel ne présentait aucune donnée. (AN-242477)
* Dans les rapports et analyses, correction d’un problème en raison duquel aucune donnée ne s’affichait lors de l’utilisation du filtre _contient_. (AN-237354)
* Correction d’un problème en raison duquel les segments supprimés d’Adobe Analytics continuaient à être utilisés dans le connecteur de données Campaign. (AN-236713)
* Correction de problèmes en raison desquels les rapports planifiés se retrouvaient bloqués dans la file d’attente des rapports. (AN-242599, AN-242554, AN-242900, AN-243329)
* Correction de problèmes liés aux rapports de cible partagés dans les rapports et analyses. (AN-234638)
* Correction d’un problème en raison duquel les graphiques à barres n’affichaient pas les données dans Workspace. (AN-232127)
* Correction de problèmes en raison desquels les clients ne pouvaient pas se connecter à Adobe Analytics. (AN-241882 AN-238802)
* Mise à jour du rapport Mobile Device (Périphérique mobile) afin d’inclure le Samsung Galaxy Z Fold2 5G. (AN-238246)
* Correction de problèmes d’erreurs dans les rapports planifiés dans Workspace. (AN-236707, AN-243449)
* Correction d’un problème en raison duquel les fichiers de source de données n’étaient pas sélectionnés par FTP. (AN-240347)
* Correction d’un problème qui provoquait une erreur lors de la tentative d’accès à [!UICONTROL Advertising Analytics]. (AN-241478)
* Correction d’un problème en raison duquel les fichiers n’étaient pas sélectionnés dans le FTP de classification. (AN-242490)
* Correction d’une erreur de rendu de l’interface utilisateur dans Workspace. (AN-243123)
* Correction d’un problème de Data Warehouse en raison duquel les fichiers ne pouvaient pas être reçus du serveur SFTP. (AN-244679)
* Correction d’un problème qui empêchait le lien [!UICONTROL Télécharger le rapport] de fonctionner, sous [!UICONTROL Admin] > [!UICONTROL Journaux] > [!UICONTROL Journaux d’utilisation et d’accès]. (AN-238058)

#### Correctifs Adobe Analytics supplémentaires

AN-204659 ; AN-221726; AN-230949 ; AN-231984; AN-232835;  AN-233989; AN-235593 ; AN-235989; AN-236823; AN-236840; AN-237168; AN-237262; AN-237265; AN-237633 ; AN-237740; AN-238523; AN-238870; AN-238941; AN-239414; AN-239649; AN-239652; AN-239676; AN-239703; AN-240184; AN-240219; AN-240412; AN-240530; AN-240609 ; AN-240625; AN-240664; AN-240682; AN-240715; AN-241052; AN-241077 ; AN-241112; AN-241149; AN-241578; AN-241714; AN-242157; AN-242485; AN-242535; AN-242573; AN-242608; AN-242728; AN-242818; AN-242820; AN-242963; AN-242978; AN-243013; AN-243054; AN-243105; AN-243172; AN-243181; AN-243255; AN-243326; AN-243418; AN-243449; AN-243463; AN-243507 ; AN-243518; AN-243519; AN-243598 ; AN-243805; AN-243814; AN-243910; AN-243929; AN-244009 ; AN-244012; AN-244105; AN-244121; AN-244137; AN-244188; AN-244225; AN-244305; AN-244357; AN-244363; AN-244419; AN-244607 ; AN-244695 ; AN-244713; AN-244828; AN-244843; AN-244876; AN-244877 ; AN-245388 ; AN-245470

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| ----------- | ---------- | ---------- |
| Mise à jour [!UICONTROL Report Builder] requise | 8 janvier 2021 | Au 30 avril 2021, tous les utilisateurs [!UICONTROL Report Builder] doivent mettre à jour le module [!UICONTROL Report Builder] vers la version 5.6.47 ou ultérieure. Cette version comprend une mise à jour critique du processus de connexion. Les utilisateurs qui ne mettent pas à jour la version 5.6.47 ou ultérieure ne pourront plus se connecter après le 30 avril 2021. [!UICONTROL Les versions 5.6.47 et ultérieures de Report ] Builder prennent en charge la connexion des Experience Cloud uniquement et ne prennent pas en charge les connexions héritées telles que la connexion unique au SiteCatalyst ou la connexion standard. Pour plus d&#39;informations, voir [Connexion au Report Builder](https://experienceleague.adobe.com/docs/analytics/analyze/report-builder/report-builder-setup/login.html?lang=en#section_6D54B8ADAE7F416BB83F5082B3771CFA). |
| Fin de vie de trois services d’API Analytics | 6 janvier 2021 | Le 30 avril 2021, les services d’API hérités d’Analytics suivants sont prévus pour atteindre la date de fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner ce jour-là.<ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Nous avons fourni une [FAQ EOL sur l&#39;API héritée](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour vous aider à répondre à vos questions et vous fournir des conseils sur la façon de procéder. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [1.4 API REST Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) et/ou les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Ajout de l’en-tête HSTS à toutes les requêtes HTTPS entrantes | 29 septembre 2020 | Le 29 septembre 2020, nous avons commencé à ajouter l’en-tête HSTS à toutes les requêtes entrantes qui utilisent des connexions HTTPS. Cela indique au navigateur/client d’effectuer toutes les requêtes à venir dans HTTPS, ce qui est considéré comme une bonne pratique de sécurité. À ce stade, nous n’appliquerons pas cette règle pour les requêtes entrantes utilisant HTTP. |
| Changement du paramètre de cookie [!UICONTROL Service d’identification des Experience Cloud] | 22 septembre 2020 | Une mise à jour des paramètres de confidentialité pour Chrome version 80 a eu un impact sur la capacité d’Adobe Analytics à suivre certains utilisateurs qui consultaient des pages AMP sur Google. Plus précisément, elle empêche le suivi inter-domaines des utilisateurs qui consultent des pages AMP hébergées par Google. Cela pourrait entraîner une augmentation du nombre de visiteurs uniques. Ce correctif permet aux utilisateurs de résoudre ce problème en modifiant les paramètres de leurs cookies ECID.<br>Actuellement, Analytics définit les cookies ECID (service Experience Cloud ID) avec le paramètre `SameSite = Lax` qui, avant la version 80 de Chrome, permettait le suivi inter-domaines. Ce n’est plus le cas. Cette modification permet aux utilisateurs de mettre à jour le paramètre SameSite pour les cookies ECID vers `None`.<br>Veuillez noter que cela permet le partage du cookie Analytics dans d’autres situations, mais les cookies Analytics ne contiennent aucune information sensible. En outre, lors du choix de ce paramètre, les cookies doivent être définis sur `Secure` afin que les données puissent être uniquement transmises par des connexions HTTPS. Si vous souhaitez apporter cette modification, demandez à un utilisateur pris en charge d’ouvrir un ticket auprès de l’assistance clientèle. |
| Migration de `omniture.com` vers un domaine `adobe.com` | 21 août 2020 | Le 13 août 2020, Adobe Analytics a migré son architecture frontale de `omniture.com|http://omniture.com/` vers le domaine `adobe.com|http://adobe.com/`. Cette modification devrait atténuer les problèmes de cookies tiers qui se sont posés après le changement initial du domaine de produit unifié en date du 28 mai 2020. Suite à cette mise à jour, le navigateur peut inviter les utilisateurs à approuver le nouveau domaine `.adobe.com|http://an.adobe.com/` ou `experience.adobe.com|http://experience.adobe.com/`. |
| Mise à jour de la compatibilité d’Ad Hoc Analysis avec Java 8 | 21 août 2020 | Ad Hoc Analysis n’est pas actuellement compatible avec les versions 1.8.0_261+ de Java 8. Pour vous assurer que votre accès à cet outil n’est pas interrompu avant la [date de fin de vie](https://spark.adobe.com/page/S9Bhp66VJ2fEn/), nous vous recommandons de conserver une version de Java 8 antérieure à la version 1.8.0_261. |
| Fin de vie des Data Connectors Adobe | 13 juillet 2020 | Les [!UICONTROL Data Connectors] Adobe sont alimentés par une technologie héritée qui n’est plus viable ni prise en charge. Nous disposons d’un nouveau standard dans le [Programme de partenariat Adobe Exchange](https://partners.adobe.com/exchangeprogram/experiencecloud) qui devrait être adopté pour toutes les intégrations qui souhaitent continuer à être proposées et prises en charge. La date officielle de fin de vie n’a pas encore été fixée, mais elle devrait avoir lieu dans les 12 à 18 prochains mois (mi-2021 à fin 2021). [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics/import/dataconnectors/data-connectors-eol.html) |
| Fin de vie d’Ad Hoc Analysis | 6 août 2018 | Adobe a annoncé la prochaine fin de vie d’Ad Hoc Analysis en date du 1er mars 2021. Pour obtenir de plus amples informations, voir le site [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### AppMeasurement {#appm}

Pour connaître les dernières mises à jour des versions d’AppMeasurement, reportez-vous aux [notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/fr-FR/analytics/implementation/appmeasurement-updates.html).

### Report Builder  {#arb}

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Date cible | Description |
| ----------- | ---------- | ----- |
| Mise à jour de connexion à Analytics [!UICONTROL Report Builder] | 14 janvier 2021 | Les améliorations apportées au processus de connexion [!UICONTROL Report Builder] suppriment les dépendances des technologies héritées et alignent le processus de connexion avec Adobe Experience Cloud. La connexion Experience Cloud vous permet d&#39;utiliser votre Adobe ID ou votre Enterprise ID (connexion unique) pour vous connecter à Adobe Experience Cloud. Au 30 avril 2021, tous les utilisateurs [!UICONTROL Report Builder] doivent mettre à jour le module [!UICONTROL Report Builder] vers la version 5.6.47 ou ultérieure. [!UICONTROL Les versions 5.6.47 et ultérieures du ] créateur de rapports prennent en charge la connexion des Experience Cloud uniquement et ne prennent pas en charge les connexions héritées, telles que la connexion unique au SiteCatalyst ou la connexion standard. Pour plus d&#39;informations, voir [Connexion au Report Builder](https://experienceleague.adobe.com/docs/analytics/analyze/report-builder/report-builder-setup/login.html?lang=en#section_6D54B8ADAE7F416BB83F5082B3771CFA). |

### Ressources d’aide à propos d’Analytics

* [Documentation et Tutorials du produit Adobe Analytics](https://experienceleague.corp.adobe.com/docs/analytics.html)

## ![Icône](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nouveaux correctifs, fonctionnalités, documentation et tutoriels pour Audience Manager.

<!-- ### Fixes and Improvements {#aam-fixes-and-improvements}

* Fixed an issue in the Predictive Audience feature where some users were unable to delete any of their models, even if no segments were mapped to the models. (AAM-55881)
* Fixed an issue where some users were unable to delete traits or segments which had been used as baseline for deleted predictive audience models. (AAM-56476)
* We continued making accessibility improvements across the interface. (AAM-53215) -->

### Cours et tutoriels sur Audience Manager {#tutorials-aam}

Nouveaux tutoriels, vidéos et cours publiés pour Audience Manager.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 15 décembre 2020 | [Définition des autorisations avec un Contrôle d&#39;accès basé sur les rôles](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/user-management/setting-permissions-with-role-based-access-control.html?lang=en#setup-and-admin) | Vidéo | Découvrez comment gérer les autorisations au niveau du groupe, en contrôlant qui peut voir et utiliser les ressources, y compris les caractéristiques, les segments, les destinations et les modèles. Configurez les groupes d’autorisations et ajoutez-y des utilisateurs. |

## ![Icône](/assets/aem.png) Adobe Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

>[!NOTE]
>
>Adobe recommande de consulter fréquemment les [mises à jour et les feuilles de route Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) afin de se tenir au courant des informations de mise à jour.

### Mises à jour de produit

* **aem 6.5.7.0**
AEM 6.5, Service Pack 7 (6.5.7.0 publié le 26 novembre 2020) est une mise à jour importante qui comprend de nouvelles fonctionnalités, des améliorations clés apportées à la clientèle, des performances améliorées, la stabilité et la sécurité, publiée depuis la publication générale de l’ 6.5 d’avril 2019.
   * [Notes de mise à jour](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en#service-pack)
   * [Livrables de la mise à jour d’AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **aem 6.4.8.3**
AEM 6.4, Service Pack 8, Cumulative Fix Pack 3 (6.4.8.3 publié le 26 novembre 2020) est une mise à jour importante qui comprend plusieurs correctifs internes et clients depuis la disponibilité générale d&#39; 6.4, Service Pack 8 (6.4.8.0), Mars 2020.
   * [Notes de mise à jour](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
   * [Livrables de la mise à jour d’AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

### Versions de produit

* **AEM as a Cloud Service**

   Nouveautés dans AEM as a Cloud Service

   * **Adobe Experience Manager Sites as a Cloud Service**
      * [API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html) HTTP de fragment de contenu : Ajoutez la possibilité d’ajouter/de mettre à jour et de supprimer des variations de  [!UICONTROL fragments de ] contenu à l’aide de l’API HTTP.
   * **Adobe Experience Manager Assets as a Cloud Service**

      * L’intégration à Adobe InDesign Server est désormais disponible pour le Experience Manager en tant que [!UICONTROL Cloud Service]. Il permet l’automatisation du traitement des fichiers Adobe InDesign à l’aide de scripts Adobe InDesign Server et permet aux utilisateurs d’utiliser l’interface utilisateur des modèles de ressources pour créer des brochures ou des publicités. Seul l’InDesign Server hébergé par Adobe Managed Services est pris en charge pour le Experience Manager en tant que [!UICONTROL Cloud Service].
      * Le Experience Manager est amélioré pour suivre et afficher les références de ressources lorsqu&#39;une ressource est utilisée dans un déploiement de sites Experience Manager distants à l&#39;aide de la fonctionnalité [!UICONTROL Ressources connectées]. Un nouvel onglet [!UICONTROL Références] de la page [!UICONTROL Propriétés] du fichier liste désormais les références locales et distantes du fichier. Les références permettent aux utilisateurs de DAM de suivre l&#39;utilisation des ressources dans les pages [!UICONTROL Sites] et dans les ressources composées dans [!UICONTROL Ressources].
Voir [configuration et utilisation des ressources connectées](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/use-assets-across-connected-assets-instances.html).
      * [!UICONTROL Les ] fonctionnalités de médias dynamiques sont désormais accessibles au moyen des composants principaux basés sur   les images de Site. Les auteurs peuvent configurer rapidement les composants pour qu’ils utilisent [!UICONTROL les paramètres d’image prédéfinis], [!UICONTROL Recadrage dynamique] et [!UICONTROL les modificateurs d’image] lors de la création de pages Web.
Voir [Core Components 2.13.0 release](https://github.com/adobe/aem-core-wcm-components/releases/tag/core.wcm.components.reactor-2.13.0).
      * L’application de bureau Experience Manager permet aux utilisateurs de télécharger des fichiers et des dossiers en faisant glisser les fichiers depuis l’Explorateur Windows ou l’Outil de recherche Mac sur l’interface de l’application de bureau.
Voir [ajout de ressources à l’aide de l’application de bureau](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/using.html?lang=en#upload-and-add-new-assets-to-aem).
   * **Adobe Experience Manager Commerce as a Cloud Service**

      * Site de référence de CIF Venia - 2020.12.01 qui comprend la dernière version de CIF Core Components v1.6.0.
Voir [CIF Venia Reference Site](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2020.12.01).
      * Composants principaux CIF version 1.6.0.
Voir [Composants principaux du FIC](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.6.0).
   * **Cloud Manager**

      * Gestion en libre-service des [certificats SSL](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/manage-ssl-certificates/introduction.html) et [noms de domaine personnalisés](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/custom-domain-names/introduction.html).
      * Gestion en libre-service des [Listes autorisées IP](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/ip-allow-lists/introduction.html).
      * La page des détails des Environnements mise à jour permet désormais aux utilisateurs de gérer les [!UICONTROL noms de domaine personnalisés] et [!UICONTROL Listes autorisées IP] sur leurs environnements.
   * **Outils de refactorisation du code**

      * Nouvelle version du module externe AIO-CLI publiée. La dernière version de ce module inclut des correctifs pour AEM Dispatcher Converter et Repository Modernizer et prend également en charge un nouvel utilitaire - Index Converter.
Voir [Expérience unifiée](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/refactoring-tools/unified-experience.html#benefits) pour en savoir plus sur ce module externe.
      * Index Converter est un utilitaire qui permet de transformer les définitions d’index OAK personnalisées d’un client en AEM en définitions d’index OAK compatibles avec les Cloud Service.
Voir [Convertisseur d’index](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/index-converter).
      * Nouvelle fonctionnalité ajoutée à [Repository Modernizer](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/repository-modernizer) qui crée un package distinct `ui.config` qui contient toutes les configurations OSGi.





Voir les [notes de mise à jour d’AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html).

### Auto-assistance

**[!DNL Experience Manager as a Cloud Service]**

Les nouvelles mises à jour de la documentation de la fonction sont disponibles dans les liens ci-dessus. Les autres mises à jour de la documentation sont les suivantes :

* **Analyseur des meilleures pratiques**

   * [!UICONTROL Cloud Readiness ] Analyzer (BPA) est désormais l’analyseur [!UICONTROL  des ] meilleures pratiques. BPA fournit une évaluation des meilleures pratiques de votre mise en oeuvre AEM actuelle et aide à évaluer la volonté de passer d’une instance AEM existante à l’AEM en tant que [!UICONTROL Cloud Service].

* **Foundation**

   * Workflows - La prise en charge de la recherche des instances de flux de travail a été ajoutée en fonction de [!UICONTROL Titre du flux de travail], [!UICONTROL Modèle de flux de travail], [!UICONTROL État], [!UICONTROL Initiateur], [!UICONTROL Chemin de charge] et [!UICONTROL Date de Début&lt;a].
Voir [Instances de flux de travaux de recherche](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/administering/workflows-administering.html#administering).
   * Synchronisation des données utilisateur au niveau de la publication : les données utilisateur, y compris les attributs de profil et les appartenances de groupe, peuvent être conservées au niveau de la publication.
Voir la [documentation relative à l&#39;abonnement, à la connexion et au Profil utilisateur](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/personalization/user-and-group-sync-for-publish-tier.html#authoring).

### [!DNL Experience Manager] Formulaires

La documentation relative aux fonctionnalités suivantes incluses dans la version 6.5.7.0 est disponible:

* Les validations côté serveur et la conversion PDF vers formulaire adaptatif s’effectuent plus rapidement après l’installation du Service Pack.

* Vous pouvez maintenant annuler toutes les modifications de redimensionnement et appliquer la mise en page par défaut à chaque composant en mode Mise en page d’un formulaire adaptatif. Voir [Utiliser le mode de mise en page pour redimensionner les composants](https://experienceleague.adobe.com/docs/experience-manager-65/forms/adaptive-forms-basic-authoring/resize-using-layout-mode.html?lang=en).

* [!DNL Experience Manager Forms] modèle de données de formulaire lors de l’intégration avec les services Web RESTful en tant que source de données comprend désormais des configurations de client HTTP pour la gestion des connexions. Voir [Configurer les sources de données](https://experienceleague.adobe.com/docs/experience-manager-65/forms/form-data-model/configure-data-sources.html?lang=en#configure-relational-database).

### Communauté

**Dernier contenu Adobe Experience Manager sur Experience League pour janvier 2021**  - Visionnez une liste  [complète de vidéos, d&#39;articles, de didacticiels et de cours ici](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/td-p/392549).

### Nouveaux cours et tutoriels sur Experience Manager

Mise à jour : **10 janvier 2021**

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 7 décembre 2020 | [Modélisation avancée des données à l’aide des références de fragments](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/fragment-references.html) | Article | Commencez avec Adobe Experience Manager (AEM) et GraphQL. Découvrez comment utiliser la fonction [!UICONTROL Référence du fragment] pour la modélisation avancée des données et pour créer une relation entre deux [!UICONTROL Fragments de contenu] différents. Découvrez comment modifier une requête GraphQL pour inclure un champ à partir d’un modèle référencé. |
| 7 décembre 2020 | [Requête AEM à l’aide de GraphQL à partir d’une application externe](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/explore-graphql-api.html) | Article | Commencez avec Adobe Experience Manager (AEM) et GraphQL. Explorez AEM API GraphQLs un exemple d&#39;application WKND GraphQL React. Découvrez comment cette application externe effectue des appels GraphQL pour AEM renforcer son expérience. Apprenez à gérer les erreurs de base. |
| 7 décembre 2020 | [Explorez les API GraphQL](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/explore-graphql-api.html) | Article | Commencez avec Adobe Experience Manager (AEM) et GraphQL. Explorez AEM API GraphQL à l&#39;aide de l&#39;IDE intégré GrapiQL. Découvrez comment AEM génère automatiquement un schéma GraphQL basé sur un modèle de fragment de contenu. Testez la construction de requêtes de base en utilisant la syntaxe GraphQL. |
| Décembre 2020 | [Création de fragments de contenu](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/author-content-fragments.html) | Article | Commencez avec Adobe Experience Manager (AEM) et GraphQL. Créez et modifiez un fragment de contenu en fonction d’un [!UICONTROL modèle de fragment de contenu]. Découvrez comment créer des variantes de [!UICONTROL Fragments de contenu]. |
| 7 décembre 2020 | [Définition de modèles de fragments de contenu](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/content-fragment-models.html) | Article | Commencez avec Adobe Experience Manager (AEM) et GraphQL. Découvrez comment modéliser du contenu et créer un schéma avec des modèles de fragments de contenu dans AEM. Examinez les modèles existants et créez un nouveau modèle. Découvrez les différents types de données qui peuvent être utilisés pour définir un schéma. |
| 9 décembre 2020 | [Compatibilité des API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/developer-reference-material-apis.html) | Article | Créez un article simple qui communique clairement les API AEM (npm, Java, HTTP) qui peuvent être utilisées pour diverses opérations [!UICONTROL Assets]. |
| 2 décembre 2020 | [Téléchargement de fragments de contenu](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-feature-video-use.html?lang=fr-FR) | Vidéo | Présentation des fonctionnalités de téléchargement des fragments de contenu. |
| 7 décembre 2020 | [Fonctionnalités éditoriales des fragments de contenu](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-feature-video-use.html) | Vidéo | Présentation vidéo des fonctionnalités avancées de l’éditeur [!UICONTROL Fragment de contenu]. Découvrez comment utiliser les annotations et la comparaison de versions avec [!UICONTROL Fragments de contenu]. |
| 4 décembre 2020 | [EXTRACTION de données OCR avec ou sans code à barres provenant de documents émis par l’administration](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/ocr-data-extraction.html?lang=en#some-useful-integrations) | Article | Remplissez le formulaire adaptatif en extrayant les données des documents émis par le gouvernement, comme un permis de conduire ou un passeport. |
| 14 décembre 2020 | [aem sans en-tête avec présentation de GraphQL](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/overview.html) | Vidéo | Présentation de l’API GraphQL implémentée dans Adobe Experience Manager ou AEM. L&#39;API GraphQL d&#39;AEM est principalement conçue pour fournir des données [!UICONTROL Fragment de contenu] aux applications en aval dans le cadre d&#39;un déploiement sans tête. |
| 16 décembre 2020 | [Composant principal Dynamic Media](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/dynamic-media-core-components.html) | Vidéo | Le composant Image, qui fait partie des composants principaux Experience Manager, prend en charge Dynamic Media de manière intégrée. Découvrez comment le composant Image permet à un auteur de contenu d’utiliser des fonctionnalités de Dynamic Media telles que les paramètres d’image prédéfinis, les options de recadrage dynamique et les modificateurs d’image sur une page AEM Sites. |

### Informations de mise à jour d’Experience Manager

Toutes les notes de mise à jour d’Experience Manager sont conservées dans les pages suivantes :

* [Mises à jour et feuille de route d’Experience Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-release-information/aem-release-updates/home.html)
* [Informations de mise à jour d’AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/release-notes/home.html)
* [Notes de mise à jour d’AEM Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Notes de mise à jour du service de conversion automatisée de formulaires](https://docs.adobe.com/content/help/fr-FR/aem-forms-automated-conversion-service/using/release-notes.html)
* [Notes de mise à jour d’AEM 6.5 Service Pack](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/release-notes/service-pack/sp-release-notes.html).
* [Notes de mise à jour d’AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/fr-FR/experience-manager-64/release-notes/cfp-release-notes.html)
* [Notes de mise à jour de Dynamic Media AEM Assets](https://docs.adobe.com/content/help/fr-FR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notes de mise à jour d’AEM Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [Notes de mise à jour de l’application de bureau AEM](https://docs.adobe.com/content/help/fr-FR/experience-manager-desktop-app/using/release-notes.html)
* [Notes de mise à jour d’AEM Dispatcher](https://docs.adobe.com/content/help/fr-FR/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Notes de mise à jour de Livefyre](https://docs.adobe.com/content/help/fr-FR/livefyre/using/release-notes/c-rn.html)

### Ressources d’aide supplémentaires pour AEM

* [Guides sur AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/landing/home.html)
* [Page d’accueil Formation et assistance AEM 6.5](https://helpx.adobe.com/fr/support/experience-manager/6-5.html)
* [Page d’accueil Formation et assistance AEM 6.4](https://helpx.adobe.com/fr/support/experience-manager/6-4.html)
* [Page d’accueil Formation et assistance AEM 6.3](https://helpx.adobe.com/fr/support/experience-manager/6-3.html)
* [Page d’accueil Formation et assistance AEM 6.2](https://helpx.adobe.com/fr/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/fr/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/fr-FR/dynamic-media-classic/using/home.html)

## ![Icône](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Nouvelles versions de produits

Informations de mise à jour pour Campaign Classic, Campaign Standard et le panneau de contrôle.

#### Campaign Classic

[Bulletin](https://helpx.adobe.com/security/products/campaign/apsb21-04.html)  de réponse aux incidents (mis à jour :  **12 janvier 2021**)

* Version 20.3.3 - [En savoir plus](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html#release-notes)
* Version 20.3.1 - [En savoir plus](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html#release-notes)
* Version 20.2.4 - [En savoir plus](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--20-2.html#release-20-2-4-build-9187)
* Version 20.1.4 - [En savoir plus](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--20-1.html#release-20-1-4-build-9126)
* Version 19.2.4 - [En savoir plus](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--19-2.html#release-19-2-4-build-9082)
* Version 19.1.8 - [En savoir plus](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-8-build-9039)

#### Campaign Classic Gold Standard

* Version Gold Standard 11 - [En savoir plus](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/gs-release/gold-standard.html?lang=en#gs-11)

### Ressources d’aide

* Adobe Campaign Standard : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/campaign-standard-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/overview.html) - [Calendrier des versions](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-planning.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/campaign-classic-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/tutorials/overview.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/documentation-updates.html)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/control-panel/using/release-notes.html) - Tutoriels vidéo pour [Campaign Standard](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

#### Nouveaux cours et tutoriels sur Campaign

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publication | Nom | Solution | Description |
| -----------| ---------- | ---------- | ---------- |
| 23 décembre 2020 | [Configuration du contenu dynamique](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/configuring-dynamic-content.html#sending-messages) | Campaign Classic | (Vidéo) Comprenez les différents types de contenu dynamique et découvrez comment créer et appliquer des blocs de personnalisation et des instructions conditionnelles à une diffusion. |
| 9 décembre 2020 | [Panneau de configuration - Gestion des enregistrements Google TXT](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/subdomains-and-certificates/google-txt-record-management.html#subdomains-and-certificates) | Campaign Standard | (Vidéo) Découvrez comment ajouter des enregistrements de vérification de site Google TXT à tous les sous-domaines utilisés pour envoyer des courriers électroniques aux adresses GMAIL avec [!UICONTROL Panneau de Contrôle Campaign]. |

## ![Icône](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notes de mise à jour d’Adobe Advertising Cloud.

* [Nouvelles fonctionnalités dans Advertising Cloud DSP](#adcloud-dsp)
* [Nouvelles fonctionnalités dans Advertising Cloud Search](#adcloud-search)

### Nouvelles fonctionnalités d’[!DNL Advertising Cloud DSP] {#adcloud-dsp}

Dernière mise à jour : **28 octobre 2020**

| Fonctionnalité | Description |
| -----------| ---------- |
| Nouveau Aide | (Version du 28 octobre) L’aide héritée a été remplacée par des pages mises à jour, disponibles à partir du lien ‘Aide’ dans le menu principal DSP et également disponibles à tout moment depuis [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=fr-FR](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=fr-FR) |
| Campagnes | (Version du 28 octobre) Les précédentes vues bêta des campagnes sont désormais les vues par défaut des campagnes, ce qui permet d’obtenir des informations plus rapides, de simplifier les workflows et de personnaliser les vues. |
| Inventaire privé | (Version du 15 octobre) Tous les utilisateurs peuvent désormais configurer et modifier les détails de l’ID de la transaction en utilisant un nouveau formulaire d’ID de transaction, qui est une version simplifiée de l’ancien formulaire [!UICONTROL Smart Ad Serving]. Pour configurer les détails de l’ID de la nouvelle transaction, accédez à **[!UICONTROL Inventaire > Transactions]**, cliquez sur **[!UICONTROL Créer]**, puis sur **[!UICONTROL ID de transaction bêta]**. |
| Prévisions de placement | (Version du 15 octobre) Pour les placements avec une fréquence de placement, la section [!UICONTROL Prévision] des paramètres de placement inclut une nouvelle section [!UICONTROL Maximums estimés], qui indique la capacité supplémentaire disponible avec la configuration de ciblage actuelle. |

### Nouvelles fonctionnalités d’[!DNL Advertising Cloud Search] {#adcloud-search}

Dernière mise à jour : **17 octobre 2020**

| Fonctionnalité | Description |
| -----------| ---------- |
| [!UICONTROL Rechercher dans les campagnes] | Dans la vue [!UICONTROL Comptes], la colonne [!UICONTROL Accès] vous informe désormais lorsqu’[!DNL Advertising Cloud Search] ne parvient pas à se connecter à un compte de moteur de recherche activé. Pour connaître la cause de l’erreur, placez le curseur sur l’icône d’avertissement. |
| [!UICONTROL Alertes personnalisées] | L’ancienne version [!UICONTROL bêta des alertes] s’appelle désormais [!UICONTROL Alertes personnalisées]. |
| [!UICONTROL Alertes personnalisées] | Dans les alertes personnalisées, le workflow d’identification de l’augmentation ou de la diminution des mesures pour la période spécifiée par rapport aux mesures de la période précédente a été simplifié et déplacé vers l’onglet [!UICONTROL Filtres]. |

### Tutoriels et cours Ad Cloud

Mise à jour : **2 décembre 2020**

| Publication | Nom | Solution | Description |
| ----------- | ----------- | ---------- | ---------- |
| 14 novembre 2020 | [Créer des tableaux de bord Advertising Cloud avec Adobe Analytics](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-dashboards-a4adc.html?lang=fr-FR) | Vidéo | Techniques de création d’un tableau de bord Advertising Cloud pour la surveillance des campagnes en direct. |
| 14 novembre 2020 | [Créer des rapports d’entrée sur le site Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-site-entry-a4adc.html?lang=fr-FR#analytics) | Vidéo | Création d’un rapport d’entrée sur le site Advertising Cloud pour surveiller le jour de la semaine, l’heure de la journée, le navigateur et l’influence géographique. |
| 14 novembre 2020 | [Créer des mesures personnalisées Analytics avec des données Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-custom-metrics-a4adc.html?lang=fr-FR#analytics) | Vidéo | Mesures personnalisées utiles à créer lors de l’utilisation de données Advertising Cloud dans Adobe Analytics. |
| 14 novembre 2020 | [Créer des segments Analytics pour l’activation et le reporting](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-segments-a4adc.html?lang=fr-FR#analytics) | Vidéo | Utiliser des dimensions Advertising Cloud pour créer des segments pour des rapports et des analyses plus propres. |
| 14 novembre 2020 | [Présentation de Predictive Audiences](https://experienceleague.corp.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html?lang=fr-FR#build-and-manage-audiences) | Vidéo | Dans cette vidéo, nous discuterons de Predictive Audiences d’Audience Manager, nous présenterons des détails sur leur fonctionnement et nous montrerons les cas d’utilisation. |
| 14 novembre 2020 | [Créer des profils Analytics pour l’activation et le reporting Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-profiles-a4adc.html?lang=fr-FR#analytics) | Vidéo | Utilisation d’Adobe Analytics pour créer des pools de reciblage de site robustes pour le remarketing Advertising Cloud. |
| 14 novembre 2020 | [Reporting avec les canaux marketing Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-reporting-a4adc.html?lang=fr-FR#analytics) | Vidéo | Fonctionnement des données d’entrée de vue publicitaire et de clic publicitaire Advertising Cloud avec les canaux marketing Adobe Analytics. |
| 14 novembre 2020 | [Créer une analyse Campaign de prélancement avec Adobe Analytics](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-pre-launch-a4adc.html?lang=fr-FR) | Vidéo | Comment utiliser Adobe Analytics pour établir les bases du lancement d’une campagne paid media Advertising Cloud. |

## ![Icône](/assets/magento.png) [!DNL Magento] {#magento}

Pour les notes de mise à jour de Magento, veuillez consulter :

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![Icône](/assets/target.png)[!DNL Target] {#target}

Voir les [[!DNL Target] notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html) pour consulter les informations les plus récentes.

## ![Icône](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] est une application complète pour la gestion des pistes et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en s’engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Voir les [notes de mise à jour](https://docs.marketo.com/display/public/DOCS/Jan+%2721) [!DNL Marketo] pour consulter les informations les plus récentes.

### Fonctionnalités à venir

Les fonctionnalités suivantes seront publiées tout au long du trimestre :

| Fonctionnalité | Description |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Nouvelle segmentation basée sur un compte</li><li>Enregistrement des filtres spécifiques au tableau de bord</li><li>Exportation de tableaux de bord Bizible au format PDF</li></ul> |
| Connect de ventes | Composition des mises à jour/améliorations des fenêtres et du Centre de commandes |

### Dépréciations

* **Paramètre de l’API de ressource &quot;_method&quot; :** après septembre 2020, les points de fin d’API d’actif n’accepteront plus `_method` pour transmettre les paramètres de requête dans un corps POST afin de contourner les limitations de longueur d’URI.
* **Dépréciation de la prise en charge d’Internet Explorer :** à compter de la version du 31 juillet 2020, l’interface utilisateur de Marketo Engage ne sera plus prise en charge dans Internet Explorer.

Pour obtenir des notes de mise à jour cumulatives et historiques, reportez-vous à la page [Notes de mise à jour de Marketo](https://docs.marketo.com/display/public/DOCS/Release+Notes).

## ![Icône](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Informations sur les mises à jour et ressources d’aide pour Adobe Document Cloud.

### Didacticiels Acrobat

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 29 décembre 2020 | [Organisation des pages](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/organize.html) | Article | Utilisez [!UICONTROL Organiser les pages] dans le Document Cloud Acrobat pour ajouter, remplacer, extraire, faire pivoter, supprimer et déplacer des pages dans votre PDF. |
| 29 décembre 2020 | [Création de formulaires à remplir](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/create-fillable-forms.html) | Article | Convertissez un document ou un formulaire papier numérisé créé dans un InDesign, Microsoft Word ou Excel ou une autre application en formulaire PDF à remplir. |
| 29 décembre 2020 | [Analyse et OCR](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/scan-and-ocr.html) | Article | Convertissez des analyses ou des images de documents en fichiers PDF modifiables et indexables, puis ajustez la qualité du fichier obtenu. |
| 28 décembre 2020 | [Préparation de fichiers PDF accessibles](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility.html) | Article | Créez des fichiers PDF universellement accessibles. |
| 28 décembre 2020 | [Utilisation des données de formulaire](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/formdata.html) | Article | Si vous disposez d’un jeu de formulaires remplis et devez compiler les données, vous pouvez utiliser Acrobat DC pour fusionner les réponses dans une seule feuille de calcul. |
| 28 décembre 2020 | [Réduction de la taille des fichiers et optimisation](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/reduce.html) | Article | Réduisez les fichiers volumineux et optimisez vos fichiers PDF sans compromettre la qualité du partage, de la publication ou de l’archivage. |
| 21 décembre 2020 | [Rendre les bulletins PDF plus accessibles](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/by-industry/gov/pdfs/making-pdf-ballots-accessible.html) | Webinaire | Découvrez les principaux secteurs d’accessibilité des fichiers PDF nécessaires pour permettre aux utilisateurs de technologies d’assistance, tels que les lecteurs d’écran, de lire et de remplir leurs bulletins de vote. |
| 21 décembre 2020 | [Redact &amp; Sanitize](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/redact.html) | Article | Utilisez l’outil Redact pour supprimer en permanence des informations privées ou sensibles de votre PDF et Sanitifier le document. |
| 18 décembre 2020 | [Action Wizard](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/action.html) | Article | Créez une action pour appliquer automatiquement un ensemble de commandes à un ou plusieurs fichiers. |
| 15 décembre 2020 | [Configuration de l&#39;expiration des caractéristiques avec le paramètre de durée de vie (TTL)](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/configuring-trait-expiration-with-the-time-to-live-ttl-setting.html?lang=en#build-and-manage-audiences) | Vidéo | Découvrez comment travailler avec [!UICONTROL Temps de vie], qui est une expiration de l&#39;adhésion à la caractéristique si vous ne vous réqualifiez pas dans le délai spécifié. |
| 4 décembre 2020 | [Utilisation de l’API Outils Adobe PDF pour OCR des fichiers PDF](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/ocr.html) | Article | Découvrez comment utiliser [!UICONTROL la reconnaissance optique des caractères] pour déverrouiller les fichiers PDF numérisés afin d’extraire du texte et de créer des fichiers indexables. |
| 4 décembre 2020 | [Prise en main de l’API et de Java des outils Adobe PDF Tools](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/gettingstartedjava.html) | Article | Les développeurs peuvent commencer en quelques minutes avec les exemples de fichiers prêts à être lancés pour accéder à tous les services Web disponibles. Ce didacticiel décrit toutes les étapes à suivre pour début d’exécution des exemples à l’aide du PDF Tools Java SDK. |
| 4 décembre 2020 | [Prise en main de l’API Outils Adobe PDF et de .Net](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/gettingstartednet.html) | Article | Les développeurs peuvent commencer en quelques minutes avec les exemples de fichiers prêts à être lancés pour accéder à tous les services Web disponibles. Ce didacticiel décrit toutes les étapes à suivre pour début d’exécution des exemples à l’aide du PDF Tools .Net SDK. |
| 4 décembre 2020 | [Utilisation de l’API Outils PDF pour l’Export PDF vers Word, PowerPoint et d’autres outils](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/exportpdf.html) | Article | Convertissez des fichiers PDF en MS Word pour modifier le contenu, les approbations et les envoyer ultérieurement pour des signatures afin de créer des workflows de contrat personnalisés. Vous pouvez également exporter du contenu PDF au format MS Excel pour effectuer des calculs de facture et de finances ou effectuer des analyses de données. |
| 4 décembre 2020 | [Créez un fichier PDF à partir d’un fichier HTML ou MS Office en quelques minutes avec l’API Outils PDF et Node.js.](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/createpdffromhtml.html) | Article | Découvrez comment numériser des workflows de document avec la nouvelle API Adobe PDF Tools. Cette API permet aux développeurs de choisir librement entre plusieurs services de manipulation PDF performants pour répondre aux besoins de workflows d’entreprise complexes. |

### Nouveaux cours et tutoriels d’Adobe Sign

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Document Cloud.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 22 décembre 2020 | [Protection de paie](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/expand/recipes/gov/usecasegovpaycheck.html) | Démonstration | Découvrez comment utiliser Adobe Sign pour convertir le Programme de protection des paiements en formulaire interactif en ligne. |

Pour obtenir de l’aide sur Document Cloud, voir :

* [Hub d’apprentissage Adobe Acrobat](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=fr-FR)
* [Hub d’apprentissage Adobe Sign](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=fr-FR)
* [Formation et assistance pour Document Cloud](https://helpx.adobe.com/fr/support/document-cloud.html)

---
title: Notes de mise à jour pour les Experience Cloud et les Experience Platform
description: Découvrez les dernières notes de mise à jour, les nouvelles fonctionnalités et la nouvelle documentation pour Experience Cloud et Experience Platform. Trouvez de nouvelles aides et des tutoriels sur Creative Cloud abonnement Entreprise et Document Cloud.
doc-type: release notes
last-update: February 2021
author: mfrei
translation-type: tm+mt
source-git-commit: c7220fd5298c74ac555ba9d1799194d794b81271
workflow-type: tm+mt
source-wordcount: '6403'
ht-degree: 32%

---


# Notes de mise à jour de Adobe Experience Cloud - Février 2021

![Bannière](/assets/experience-cloud-banner-3.png)

Les solutions et services Experience Cloud sont mis à jour chaque mois. Cette page est votre emplacement central pour rechercher les dernières mises à jour de version, la documentation et les didacticiels pour [!DNL Experience Cloud] et l&#39;Experience Platform. Vous trouverez également de nouvelles informations sur [!DNL Creative Cloud for Enterprise] et [!DNL Document Cloud].

>[!IMPORTANT]
>
>Cette page contient le contenu de la pré-version et peut être modifiée avant les dates de publication.

>[!NOTE]
>
>Abonnez-vous à la [mise à jour produit prioritaire d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) pour recevoir chaque mois des notifications par email concernant les mises à jour de cette page. Cette page est tenue à jour tout au long du mois. Veuillez donc vérifier régulièrement si des mises à jour sont apportées au produit Adobe Enterprise et à la documentation Experience League.

Dernière mise à jour : **12 février 2021**

* [Statut du système Adobe](#status)
* [Services d’Experience Cloud et administration](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [](#analytics) **AnalyticsMis à jour le 19 février 2021**
* [Customer Journey Analytics](#cust-journey)`
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Entreprise](#creative-cloud)

Besoin d’aide ? Consultez [Adobe Experience League](https://experienceleague.adobe.com/?lang=fr#home) pour trouver de la documentation technique et sur les produits, des cours préparés par Adobe, des tutoriels vidéo, des réponses rapides, des informations provenant de la communauté et des formations dispensées par un instructeur.

## ![Icône](/assets/adobe.png) Statut du système Adobe {#status}

[!UICONTROL Statut du système Adobe] fournit des informations détaillées, des mises à jour de statut et des notifications par email relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

Aucune mise à jour ce mois-ci.

Voir [Statut d’Adobe - 21 mai 2020](https://docs.adobe.com/content/help/fr-FR/release-notes/experience-cloud/previous/2020/05212020.html#status) pour obtenir les dernières informations de mise à jour.

## ![Icône](/assets/ec_appicon_24.png) Services d’Experience Cloud et administration {#ecloud}

La documentation sur les [services et administration d’Experience Cloud](https://docs.adobe.com/content/help/fr-FR/core-services/interface/experience-cloud.html) comprend les attributs du client, la bibliothèque d’audiences (le service [!UICONTROL Personnes]), l’activation, la gestion des utilisateurs et des produits, ainsi que les cookies Experience Cloud.

**4 février 2021**

* **Mise à jour de la connexion :** une mise à jour de l’Experience Cloud supprime l’écran initial de connexion de l’Experience Cloud. À compter du 4 février, vous serez directement renvoyé vers l’écran de connexion d’Adobe depuis `https://experience.adobe.com/login`.

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Inclut les informations de mise à jour pour Experience Platform et Experience Platform Launch.

* [Notes de mise à jour d’Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=fr). (27 janvier 2021)
* [Notes de mise à jour d’Experience Platform Launch](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=fr). (13 janvier 2021)

### Didacticiels et cours Experience Platform

Nouveaux tutoriels, vidéos ou cours publiés pour Experience Platform et ses services.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 10 février 2021 | [Configuration de la destination Blob Azure](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=en#destinations) | Vidéo | Découvrez comment suivre les étapes requises pour configurer et configurer la destination de l&#39;Enregistrement Blob Azure dans la plateforme de données client en temps réel (CDP en temps réel). |
| 4 février 2021 | [Graphiques d&#39;identité de vue](https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/view-identity-graphs.html) | Vidéo | Comment utiliser la fonctionnalité de visionneuse de graphiques d’identité pour rechercher, explorer et filtrer des graphiques d’identité à des fins de validation et de débogage. |
| 3 février 2021 | [Présentation de l&#39;assimilation des données par lot](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/batch-ingestion-overview.html) | Vidéo | Présentation de l’assimilation des données par lot à Adobe Experience Platform. Apprenez à assimiler des données de lot à l’aide de l’API. |
| 3 février 2021 | [Activation des données vers des applications non Adobes](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/activate-data-to-non-adobe-applications.html) | Vidéo | Découvrez comment le CDP en temps réel de l’Adobe vous aide à créer de véritables stratégies de personnalisation avec vos audiences. Découvrez également comment il se plie à vos applications existantes d&#39;éco-système et non-Adobes de Microsoft, Google et Facebook. |
| 21 janvier 2021 | [Intro de cours pour la prise en main des services intelligents pour les marketeurs](https://video.tv.adobe.com/v/330805?quality=12&learn=on) | Vidéo | Une introduction au cours Prise en main des services intelligents pour les marketeurs. |
| 13 janvier 2021 | [Présentation de la prise en main de l’Offer decisioning pour les marketeurs](https://video.tv.adobe.com/v/330520?quality=12&learn=on) | Vidéo | Et introduction au cours Prise en main de l’Offer decisioning pour les spécialistes du marketing. |
| 31 janvier 2021 | [Former, marquer et produire des modèles à l&#39;aide du modèle de créateur de recettes](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/train-score-and-productize-models.html) | Vidéo | Découvrez comment utiliser le modèle mis à jour du créateur de recettes pour créer une recette à l&#39;aide du schéma de vente au détail et des jeux de données. |
| 31 janvier 2021 | [Chargement de données dans les blocs-notes JupyterLab](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/load-data-in-jupyterlab-notebooks.html) | Vidéo | Découvrez JupyterLab dans Data Science Workspace. |
| 12 janvier 2021 | [Créer des stratégies de fusion](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/create-merge-policies.html) | Vidéo | Découvrez comment créer des stratégies de fusion dans Adobe Experience Platform. |

## ![Icône](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Utilisez Adobe Experience Platform pour orchestrer le parcours d’un client à l’échelle des canaux d’expérience, en anticipant intelligemment les besoins de chacun en temps réel.

### Dernières versions du produit

Pour en savoir plus sur les dernières fonctionnalités, améliorations et correctifs des [Notes de mise à jour du Journey Orchestration](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html).

### Nouveaux cours et tutoriels pour Journey Orchestration

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 22 janvier 2021 | [Passage à un autre parcours](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/jumping-to-another-journey.html?lang=fr) | Vidéo | Découvrez comment inviter des individus à passer d’un parcours à un autre. |

### Autres ressources pour le Journey Orchestration

[Documentation](https://docs.adobe.com/content/help/fr-FR/journeys/using/journey-orchestration-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [Tutoriels vidéos](https://docs.adobe.com/content/help/fr-FR/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Icône](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Date de mise à jour : **18 février 2021**

* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features)
* [Nouvelles fonctionnalités dans Customer Journey Analytics](#cust-journey)
* [Correctifs dans Adobe Analytics](#aa-fixes)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices) **Mis à jour le 19 février 2021**
* [Cours et tutoriels pour Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.html) - Date cible | Description |
| ----------- | ---------- | ------- |
| Analysis Workspace - Sélection de composants | 4 février 2021 | Le composant de zone de dépôt/liste déroulante qui se trouve dans [!UICONTROL Quick Insights] a été ajouté à toutes les zones de dépôt dans [!UICONTROL Workspace]. Cette amélioration vous permet de choisir parmi des composants compatibles dans une liste déroulante ou de continuer à utiliser l’espace comme zone de dépôt. |
| Sélection de la langue des tableaux de bord Analytics | 14 janvier 2021 | Accédez à **[!UICONTROL Paramètres]** > **[!UICONTROL Préférences]** > **[!UICONTROL Langue]** pour sélectionner une langue dans le tableau de bord Analytics. |

### Nouvelles fonctionnalités dans Customer Journey Analytics {#cust-journey}

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Date cible | Description |
| ----------- | ---------- | ----- |
| Analysis Workspace - Sélection de composants | 4 février 2021 | Le composant de zone de dépôt/liste déroulante qui se trouve dans [!UICONTROL Quick Insights] a été ajouté à toutes les zones de dépôt dans [!UICONTROL Workspace]. Cette amélioration vous permet de choisir parmi des composants compatibles dans une liste déroulante ou de continuer à utiliser l’espace comme zone de dépôt. |
| API CJA | 18 février 2021 | Les API CJA sont désormais disponibles. Ces API vous permettent de modifier par programmation des composants et de récupérer des rapports. Pour plus d’informations, consultez la [documentation de l’API CJA](https://adobe.io/cja-apis/docs). |

### Correctifs dans Adobe Analytics {#aa-fixes}

* Correction d’un problème en raison duquel le délai d’expiration de la passerelle de l’API Adobe Analytics 2.0 augmentait à 300 secondes (5 minutes). (AN-232335)
* Correction de problèmes de performances avec Workspace, API 2.0 et Adobe Report Builder rapports (AN-245644, AN-244504, AN-243060).
* Correction d’un problème qui provoquait une erreur lorsque vous cliquiez sur **Ajouter** dans Analytics [!UICONTROL Flux de données]. (AN-243171)
* Correction de problèmes en raison desquels les classifications ne classaient pas les données. (AN-243823, AN-247049, AN-244114)
* Correction d’un problème lié aux projets planifiés : les clients ne pouvaient voir que les projets qu’ils possédaient, mais pas tous les projets planifiés (AN-246955)
* Correction d’un problème du panneau A4T dans [!UICONTROL Workspace] en raison duquel les projets ne s’ouvraient pas. (AN-246881)
* Correction d’un problème en raison duquel [!UICONTROL Workspace] renvoyait une erreur liée à A4T [!UICONTROL Mesures calculées]. (AN-247082)
* Correction d’un problème en raison duquel les demandes d’API de Data Warehouse ne renvoyaient aucune donnée. (AN-236931)
* Correction d’un problème en raison duquel l’accès à une suite de rapports virtuelle n’était possible qu’en conjonction avec l’accès à la suite de rapports parente. (AN-247042)
* Correction d’un problème qui provoquait une erreur lors de la conversion de projets de [!UICONTROL Ad Hoc Analysis] en [!UICONTROL Workspace]. (AN-221215)
* Correction d’un problème en raison duquel un nombre incorrect de projets filtrés s’affichait dans le [!UICONTROL Gestionnaire de projets de l’espace de travail]. (AN-244934)

#### Correctifs Adobe Analytics supplémentaires

AN-224987; AN-229009 ; AN-239750; AN-239765; AN-241620; AN-242996 ; AN-243577 ; AN-243774; AN-244509 ; AN-244746; AN-244763; AN-244868; AN-244960; AN-245016; AN-245097 ; AN-245727; AN-246141; AN-246283; AN-246340; AN-246532; AN-246669; AN-246744 ; 246763 ; AN-246892; AN-246898 ; AN-246961; AN-247643; AN-247048; AN-247134; AN-247758; AN-247774; AN-248179; AN-248226; AN-248297 ; AN-248300; AN-248303; AN-248376; AN-248495 ; AN-248647

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| ----------- | ---------- | ---------- |
| Options du landing page Rapports et analyses | 19 février 2021 | Le 25 mars 2021, les options permettant de définir de nouveaux tableaux de bord de rapports et analyses ou d’autres contenus comme votre landing page Adobe Analytics seront supprimées. Si vous avez précédemment défini une page Rapports et analyses comme landing page personnalisé, elle continuera à fonctionner jusqu’à ce que votre landing page soit modifié dans [!UICONTROL Préférences utilisateur]. Depuis le 25 mars 2021, vous ne pouvez plus définir de nouveaux landings page personnalisés Rapports et analyses. |
| Fin de vie d’Ad Hoc Analysis | Janvier 2021 | [!UICONTROL Les analyses ad hoc ] atteignent leur date de fin de vie le 1er mars 2021. Pour obtenir de plus amples informations, voir le site [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |
| Fin de vie de trois services d’API Analytics | 6 janvier 2021 | Le 30 avril 2021, les services d’API hérités d’Analytics suivants atteindront leur date de fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner ce jour-là.<ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Nous avons mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Fin de vie des Data Connectors Adobe | 13 juillet 2020 | Les [!UICONTROL Data Connectors] Adobe sont alimentés par une technologie héritée qui n’est plus viable ni prise en charge. Une nouvelle norme est disponible dans le [Programme partenaire Exchange Adobe](https://partners.adobe.com/exchangeprogram/experiencecloud). Vous pouvez utiliser cette norme pour que toute intégration continue à être proposée et prise en charge. La date officielle de fin de vie est le 1er août 2021. [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics/import/dataconnectors/data-connectors-eol.html) |
| Ajout de l’en-tête HSTS à toutes les requêtes HTTPS entrantes | 29 septembre 2020 | Le 29 septembre 2020, l&#39;Adobe a commencé à ajouter l&#39;en-tête HSTS à toutes les demandes entrantes qui utilisent HTTPS. Cet en-tête indique au navigateur ou au client d’effectuer toutes les requêtes futures dans HTTPS, ce qui est considéré comme une bonne pratique de sécurité. À ce stade, l’Adobe ne l’applique pas aux requêtes entrantes utilisant HTTP. |
| Modification du paramètre de cookie du [!UICONTROL service Experience Cloud ID] | 22 septembre 2020 | Une mise à jour des paramètres de confidentialité pour Chrome version 80 a eu un impact sur la capacité d’Adobe Analytics à suivre certains utilisateurs qui consultaient des pages AMP sur Google. Plus précisément, elle empêche le suivi inter-domaines des utilisateurs qui consultent des pages AMP hébergées par Google. Cela pourrait entraîner une augmentation du nombre de visiteurs uniques. Ce correctif permet aux utilisateurs de résoudre ce problème en modifiant les paramètres de leurs cookies ECID.<br>Actuellement, Analytics définit les cookies [!UICONTROL ECID] (service Experience Cloud ID) avec le paramètre `SameSite = Lax` qui, avant la version 80 de Chrome, permettait le suivi inter-domaines. Ce n’est plus le cas. Cette modification permet aux utilisateurs de mettre à jour le paramètre SameSite pour les cookies ECID vers `None`.<br>Cette modification permet le partage du cookie Analytics dans d’autres situations, mais les cookies Analytics ne contiennent pas d’informations sensibles. En outre, lors du choix de ce paramètre, les cookies doivent être définis sur `Secure` afin que les données puissent être uniquement transmises par des connexions HTTPS. Si vous souhaitez apporter cette modification, un utilisateur ayant souscrit un contrat dédié peut ouvrir un ticket auprès du service d’assistance clientèle. |

### AppMeasurement {#appm}

Pour connaître les dernières mises à jour des versions d’AppMeasurement, reportez-vous aux [notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/fr-FR/analytics/implementation/appmeasurement-updates.html).

### Cours et tutoriels pour Analytics {#tutorials-analytics}

Nouveaux cours, tutoriels et articles dans [!DNL Analytics] et [!UICONTROL Customer Journey Analytics].

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 8 février 2021 | [Ajouter des tendances aux visualisations de ligne](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/adding-trendlines-to-line-visualizations.html?lang=en) | Vidéo | Dans Paramètres de visualisation, vous pouvez choisir d’ajouter une régression ou de déplacer une courbe de tendance moyenne vers votre série de lignes. Cette fonction permet de représenter un modèle plus clair dans les données. |
| 8 février 2021 | [Ajouter des modules externes d’implémentation dans le Platform launch](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/implementation/via-adobe-launch/adding-implementation-plug-ins-in-launch.html?lang=en#implementation) | Vidéo | Les modules externes d’implémentation sont des éléments de code JavaScript que vous pouvez ajouter à votre mise en oeuvre Analytics pour effectuer le suivi de données personnalisées supplémentaires. Dans cette vidéo, découvrez comment et où ajouter le code dans le Platform launch. |
| 6 janvier 2021 | [Panneau Observateurs simultanés de médias dans Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/media-concurrent-viewers-panel-in-analysis-workspace.html?lang=en#analysis-workspace) | Vidéo | Déterminer où s’est produit le pic de concurrence ou où des abandons ont eu lieu. Bénéficiez d&#39;un aperçu précieux de la qualité du contenu et de l&#39;engagement des visiteurs, ainsi que d&#39;une aide pour le dépannage ou la planification du volume et de l&#39;échelle. |

### Ressources d’aide à propos d’Analytics

* [Documentation et tutoriels du produit Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=fr)

## ![Icône](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nouvelles fonctionnalités, correctifs, documentation et didacticiels en Audience Manager.

| Fonctionnalité | Date d’ajout ou de mise à jour | Description |
|----|----|----|
| [Migration des utilisateurs Audiences Manager vers le Admin Console](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/admin-console-migration.html) | 1 février 2021 | La gestion des comptes d’utilisateurs de l’Audience Manager se déplace vers le Adobe Admin Console, pour une expérience plus rationnelle dans l’ensemble de vos solutions d’Adobe. <br>Suivez les étapes décrites dans cet article pour faciliter la migration des utilisateurs. Tous les administrateurs d’Audiences Manager doivent début de migrer leurs comptes d’utilisateurs vers Adobe Admin Console dès que possible. |

### Correctifs et améliorations {#aam-fixes-and-improvements}

* Correction d’un problème dans le rapport [État de l’intégration](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html). Dans ce problème, il y avait une incohérence entre les enregistrements du rapport et ceux du fichier téléchargés par un partenaire d’intégration. (AAM-57415)
* Correction d’un problème de clonage de **[!UICONTROL Modèle]** dans la fonction **[!UICONTROL Audiences prédictives]**. (AAM-56775)
* Correction d’un problème de duplication des caractéristiques et des segments en raison duquel une caractéristique ou un segment incorrect était dupliqué. (AAM-57351)
* Correction d’un problème en raison duquel la case à cocher **[!UICONTROL Sélectionner tout]** dans **[!UICONTROL Modèles > Exclure les caractéristiques]** ne pouvait pas être cliquée pour les utilisateurs. (AAM-57366)
* Correction d’un problème dans **[!UICONTROL Créateur de segments]** en raison duquel la case à cocher **[!UICONTROL Sélectionner tout]** ne sélectionnait pas toutes les caractéristiques. (AAM-55640)

### Cours et tutoriels sur Audience Manager {#tutorials-aam}

Nouveaux tutoriels, vidéos et cours publiés pour Audience Manager.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 5 février 2021 | [Procédure d’importation de données basées sur des fichiers](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/steps-for-ingesting-file-based-data.html?lang=en#integrating-offline-data) | Vidéo | Découvrez les étapes à prendre en compte lorsque vous embarquez des données hors ligne dans l’Audience Manager, y compris les exigences en matière de nom de fichier pour le fichier de données. |
| 5 février 2021 | [Formatage et insertion de données basées sur des fichiers](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/formatting-and-ingesting-file-based-data.html?lang=en#integrating-offline-data) | Vidéo | Lors de l’importation de vos données propriétaires en Audience Manager afin de mieux comprendre et de mieux cible votre client, certaines exigences de mise en forme s’appliquent aux données. Découvrez quelques-unes des options principales et où obtenir plus d&#39;informations. |
| 5 février 2021 | [Création d’une source de données sur plusieurs périphériques et authentification](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/data-sources/creating-a-cross-device-data-source-and-authenticating.html?lang=en#setup-and-admin) | Vidéo | Découvrez comment créer une source de données sur plusieurs périphériques pour stocker les ID et les données de gestion de la relation client lors de l’importation de vos données de gestion de la relation client propriétaires en Audience Manager. Cette vidéo vous explique comment procéder et comment configurer la méthode `setCustomerIDs()` en Experience Platform Launch pour les connexions. |
| 3 février 2021 | [Introduction au cours - Création et gestion de l&#39;Activation des données dans l&#39;Audience Manager](https://video.tv.adobe.com/v/331001) | Vidéo | Les segments d&#39;Audience ne valent rien, à moins que vous ne fassions quelque chose avec eux. Ce cours vous explique comment utiliser les audiences pour personnaliser l’expérience utilisateur. Cette vidéo d&#39;introduction vous guide sur votre chemin. |
| 28 janvier 2021 | [Création et gestion des caractéristiques](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.3) | Cours | Découvrez les avantages et les inconvénients de la création et de l&#39;organisation des caractéristiques à partir du [!UICONTROL créateur de caractéristiques] produit jusqu&#39;à l&#39;outil [!UICONTROL Gestion en bloc]. Apprenez également à utiliser l&#39;outil [!UICONTROL Data Explorer] pour découvrir des signaux importants qui entrent en Audience Manager et créer des caractéristiques pour eux. |
| 22 janvier 2021 | [Utilisation des rapports d’Audience Optimization pour comprendre les performances des médias](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/using-audience-optimization-reports-to-understand-media-performance.html?lang=en#reports) | Vidéo | Découvrez comment utiliser les rapports sur les Audiences Optimization pour améliorer vos campagnes, savoir où investir vos investissements marketing et où arrêter d&#39;investir. Découvrez également comment déterminer le plafonnement optimal de la fréquence et trouver d&#39;autres éléments positifs dans ces rapports. |
| 15 janvier 2021 | [Comprendre les Audiences connexes avec les rapports de chevauchement](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/understand-related-audiences-with-overlap-reports.html?lang=en#reports) | Vidéo | Les rapports de chevauchement vous permettent de déterminer comment les audiences de caractéristiques et de segments se chevauchent (même visiteur dans plusieurs caractéristiques ou segments), de sorte que vous sachiez où vous pouvez agir avec vos données pour augmenter la conversion ou vous concentrer sur l’extension de la portée. |
| 12 janvier 2021 | [Utilisation des étiquettes d’exportation de données pour contrôler le flux de données](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/data-activation/destinations-basics/using-data-export-labels-to-control-data-flow.html?lang=en#data-activation) | Vidéo | Les étiquettes d’exportation de données vous offrent un mécanisme en Audience Manager pour contrôler le flux de différents types de données/sources, afin que vous puissiez respecter vos exigences en matière de confidentialité. Découvrez comment et où définir les contrôles d’exportation de données et les étiquettes d’exportation de données, pour travailler en tandem à cette fin. |
| 22 janvier 2021 | [Importer des segments d’Adobe Analytics dans l’Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/import-aa-segments-into-aam.html?lang=en#build-and-manage-audiences) | Vidéo | Outre le transfert de données en temps réel d’Adobe Analytics vers l’Audience Manager, vous pouvez également importer des segments qui incluent des données post-traitées d’Analytics vers l’Audience Manager via l’Experience Cloud. |

## ![Icône](/assets/aem.png) Adobe Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour dans le Experience Manager. Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

>[!NOTE]
>
>L’Adobe recommande de consulter la [page Experience Manager release updates and roadmap](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=fr) afin de rester informé de la mise à jour.

### Versions de produit

* **Experience Manager as a Cloud Service**

   Nouvelles fonctionnalités du Experience Manager en tant que Cloud Service

   * ** Experience Manager Assets as a Cloud Service**

      * **Service de Gestion de contenu sans en-tête**

         * [API GraphQL pour la Diffusion](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-api-content-fragments.html) de fragments de contenu : Possibilité de requête de fragments de contenu à l’aide de la syntaxe GraphQL et de schémas basés sur des modèles de fragments de contenu, pour une sortie au format JSON.
         * [Prise en charge de l’authentification pour les demandes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-authentication-content-fragments.html) d’API GraphQL : Capacité à authentifier les demandes d’API GraphQL avec des jetons d&#39;accès pour les API côté serveur.
         * [Le composant](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html) RemotePage : Prise en charge Ajoutée de l’affichage et de la modification des SPA externes dans AEM utilisation.
         * [Modification d&#39;un SPA externe dans AEM](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html) : Possibilité Ajoutée de télécharger une application autonome d’une seule page sur une instance AEM, d’ajouter des sections de contenu modifiables et d’activer la création.
         * Amélioration de la sortie JSON à partir de l’API GraphQL, notamment la possibilité de générer du texte enrichi au format JSON et dans les paramètres régionaux.
         * Prise en charge de l’imbrication de modèles de fragments de contenu pour permettre la création de structures de fragments de contenu imbriquées, par le biais de types de données de référence de fragments de contenu dédiés ou de références de fragments de contenu insérées dans des champs de texte multilignes.
         * D’autres règles de validation sont disponibles dans les types de données du modèle Fragment de contenu, notamment &quot;unique&quot;, &quot;obligatoire&quot; et &quot;traduisible&quot;.
         * Possibilité de baliser les modèles de fragments de contenu et d’autoriser la création de fragments de contenu dans un dossier avec des stratégies par balises ou chemins d’accès.
         * Améliorations de la convivialité de l’éditeur de fragments de contenu, notamment l’action de publication et l’affichage du modèle sur lequel un fragment est basé.
         * Possibilité de prévisualisation de la sortie JSON directement dans l’éditeur de fragments de contenu.
      * **Applications Web progressives (PWA)**

         * [Une version d&#39;application Web progressive (PWA) d&#39;un ](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/enable-pwa.html?lang=en) site peut désormais être activée au niveau du projet via une configuration simple.
   * ** Experience Manager Assets as a Cloud Service**

      * Experience Manager en tant que Cloud Service étend la fonctionnalité Balises actives pour prendre en charge l’identification des mots-clés et des entités dans les ressources textuelles. Le texte est identifié, indexé et mis à disposition en tant que métadonnées pour améliorer l&#39;expérience de recherche sans avoir besoin d&#39;aucune configuration. Voir [Balises dynamiques](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/manage/smart-tags.html).
      * Le format de fichier MXF est désormais pris en charge. Voir [formats de fichier pris en charge](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/file-format-support.html#video-formats).
   * ** Experience Manager Commerce as a Cloud Service**

      * **Nouveautés?**

         * Gestion de l&#39;expérience des produits : Nouvel onglet Propriétés Commerce pour les ressources et les fragments d’expérience. Cet onglet vous permet de lier des produits/catégories aux ressources et aux fragments d’expérience. L’onglet affiche également des données en temps réel pour les produits/catégories liés et un lien permettant d’afficher des détails dans la console du produit.
         * Site de référence de CIF Venia - 2021.02.02 qui comprend la dernière version des composants principaux de CIF version 1.7.0. Pour plus d&#39;informations, consultez [Site de référence de CIF Venia](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.02).
         * Publication des composants principaux CIF version 1.7.0. Reportez-vous à [Composants principaux CIF](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.7.0) pour plus de détails.
      * **Analyseurs de build de SDK**

         Le Experience Manager en tant que module externe d’expert de build du SDK Cloud Service détecte des problèmes dans un projet d’expert, y compris les dépendances manquantes. Il permet aux développeurs de trouver des problèmes lors du développement local, bien avant le déploiement sur les environnements Cloud avec Cloud Manager.

         Deux nouveaux analyseurs ont été ajoutés pour cette version :

         * analyseur repointeur
         * bundle-nativecode

         Pour plus d&#39;informations, consultez la documentation [ici](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html#developing).
   * **Outils de transition vers le cloud**

      * **Nouveautés de l’outil de transfert de contenu**

         * Nouvelle fonctionnalité et interface utilisateur ajoutées à l’outil de transfert de contenu - Outil de mappage des utilisateurs. Cette fonctionnalité mappe automatiquement les utilisateurs et les groupes existants à leurs identifiants système Identity Management Adobe dans le cadre de l’activité de migration de contenu.
Voir [Utilisation de l’outil de mappage utilisateur](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-user-mapping-tool.html).
         * L’outil de transfert de contenu migre désormais tous les groupes et utilisateurs référencés dans le jeu de migration, y compris les enfants.
         * Les utilisateurs sont autorisés à sélectionner certains chemins sous `/etc` lors de la création de jeux de migration.







### **Communauté**

* **Développeurs d&#39;Adobes en direct 2021 | liste de session complète**

   Par requête populaire, [ici](https://adobe.ly/3cldljt) est une liste agrégée de toutes les sessions de Experience Manager qui se déroulent sur Adobe Developers Live. Tous les enregistrements et questions-réponses de chaque session sont affichés sur leurs fils contextuels respectifs.

* **Liste du contenu Adobe Experience Manager le plus récent sur Experience League | Janvier 2021**

   Source officielle du contenu technique Digital Experience produit par Adobe. Voir la liste complète [ici](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156).

### Informations de mise à jour d’Experience Manager

Toutes les notes de mise à jour d’Experience Manager sont conservées dans les pages suivantes :

* [Mises à jour et feuille de route d’Experience Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-release-information/aem-release-updates/home.html)
* [Experience Manager en tant qu’informations de mise à jour Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/release-notes/home.html)
* [Notes de mise à jour de Experience Manager Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Notes de mise à jour du service de conversion automatisée de formulaires](https://docs.adobe.com/content/help/fr-FR/aem-forms-automated-conversion-service/using/release-notes.html)
* [Notes de mise à jour de Experience Manager 6.5 Service Pack](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Notes de mise à jour cumulées du pack de correctifs Experience Manager 6.4](https://docs.adobe.com/content/help/fr-FR/experience-manager-64/release-notes/cfp-release-notes.html)
* [Notes de mise à jour de Experience Manager Assets Dynamic Media](https://docs.adobe.com/content/help/fr-FR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notes de mise à jour du portail des marques Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=fr)
* [Notes de mise à jour de l’appli de bureau  Experience Manager ](https://docs.adobe.com/content/help/fr-FR/experience-manager-desktop-app/using/release-notes.html)
* [Notes de mise à jour du répartiteur Experience Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Notes de mise à jour de Livefyre](https://docs.adobe.com/content/help/fr-FR/livefyre/using/release-notes/c-rn.html)

### Cours et didacticiels pour Experience Manager

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 11 février 2021 | [Authentification à AEM en tant que Cloud Service à partir d’une application externe](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | Cours | Découvrez comment une application externe peut utiliser les [!UICONTROL Jetons d&#39;accès de développement local] et [!UICONTROL informations d’identification du service] pour s’authentifier par programmation auprès du Experience Manager en tant que Cloud Service via HTTP. |
| 11 février 2021 | [Relation et dissociation des actifs](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html) | Vidéo | Découvrez comment établir et gérer des relations entre les ressources en Experience Manager. |
| 8 février 2021 | [AEM Sites - Didacticiel WKND](https://docs.adobe.com/content/help/en/experience-manager-learn/getting-started-wknd-tutorial-develop/overview.html) | Tutoriel | Bienvenue dans un didacticiel en plusieurs parties conçu pour les développeurs qui découvrent le Experience Manager. Ce tutoriel présente la mise en oeuvre d&#39;un site Experience Manager pour une marque de style de vie fictif WKND. |
| 1 février 2021 | [Création de votre premier lot OSGi](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/create-your-first-osgi-bundle.html?lang=en) | Article | Découvrez comment créer votre premier lot OSGi à l’aide de maven et eclipse. |
| 1 février 2021 | [Publier des ressources](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/publish.html) | Vidéo | Découvrez comment publier des ressources et leurs rendus de l’auteur Experience Manager vers AEM Publish. |
| 4 février 2021 | [Développement local](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/local-development-environment.html) | Vidéo | Découvrez comment télécharger et configurer un environnement de développement local à l’aide du Experience Manager en tant que SDK Cloud Service. |
| 4 février 2021 | [Structure du projet](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/project-structure.html) | Vidéo | Explorez les meilleures pratiques pour structurer un projet Maven Experience Manager pour AEM en tant que Cloud Service. |
| 4 février 2021 | [Migrer les configurations du répartiteur](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/dispatcher-configuration.html) | Vidéo | Présentation des différences dans les configurations du répartiteur, ainsi que des conseils et astuces pour migrer le répartiteur d’Adobe Managed Services (AMS) vers le Experience Manager en tant que Cloud Service. |
| 2 février 2021 | [Présentation du SDK AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/aem-sdk.html) | Vidéo | Utilisation et configuration du SDK pour Experience Manager en tant que Cloud Service. |
| 2 février 2021 | [Qu’est-ce que AEM Cloud Service ?](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/what-is-aem-as-a-cloud-service.html) | Vidéo | Explorez ce qu&#39;est un Experience Manager en tant que Cloud Service, et comment il diffère d&#39;une autre version de Adobe Experience Manager. |
| 2 février 2021 | [Rôle de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/cloud-manager.html) | Vidéo | Explorez l&#39;objectif de [!UICONTROL Cloud Manager] et comment il fonctionne avec le Experience Manager en tant que Cloud Service. |
| 2 février 2021 | [Évolution de l&#39;AEM en tant que Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/evolution.html) | Vidéo | Explorez l’historique des Experience Manager et les différences entre Experience Manager sur site, AEM Adobe Managed Services et Experience Manager en tant que Cloud Service. |
| 2 février 2021 | [Architecture d’AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/architecture.html) | Vidéo | Explorez l&#39;architecture sous-jacente et d&#39;importants éléments de Experience Manager en tant que Cloud Service. Découvrez Cloud Manager et ses API en profondeur. |
| 2 février 2021 | [Utilisation des API de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/cloud-manager-apis.html) | Vidéo | Découvrez comment les API de Cloud Manager peuvent être utilisées pour étendre et intégrer des applications à d’autres systèmes. |
| 2 février 2021 | [Analyser les résultats des tests](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/analyze-test-results.html) | Vidéo | Explorer les erreurs de compilation dans votre code et déterminer si ce code suit les meilleures pratiques pour le Experience Manager en tant que Cloud Service |
| 2 février 2021 | [Configuration des tuyaux](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/configure-pipelines.html) | Vidéo | Explorez les différents types de pipelines dans Cloud Manager et comment les configurer pour un projet réussi. |
| 2 février 2021 | [Gérer les configurations du répartiteur](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/dispatcher-configurations.html) | Vidéo | Utilisez les meilleures pratiques et les exemples pour découvrir comment le répartiteur fonctionne avec le Experience Manager en tant que Cloud Service et Cloud Manager. |
| 2 février 2021 | [Intégrations permanentes et Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/continuous-integration.html) | Vidéo | Découvrez les meilleures pratiques et l’intégration continue à l’aide d’Adobe Cloud Manager. |
| 2 février 2021 | [Fusion de projets AEM à déployer à l’aide de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/merge-projects.html) | Vidéo | Découvrez comment plusieurs projets peuvent être fusionnés en un seul projet pour être déployés en tant que Cloud Service dans Experience Manager à l’aide de Cloud Manager. |
| 2 février 2021 | [Déploiement de projets Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/deploy-code.html) | Vidéo | Intégrez le référentiel git de cloud manager à un référentiel git externe et déployez un projet sur Experience Manager en tant que Cloud Service. |
| 2 février 2021 | [Publication de contenu](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/content-publishing.html) | Vidéo | Découvrez comment fonctionne la publication de contenu en Experience Manager en tant que Cloud Service, y compris les concepts de diffusion de contenu et de pipeline d’Adobes. |
| 2 février 2021 | [Authentification basée sur un jeton - Informations d&#39;identification du service](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/service-credentials.html?lang=en#authentication) | Vidéo | Découvrez l’authentification par jeton pour les intégrations avec le Experience Manager en tant que Cloud Service. |
| 2 février 2021 | [Signature de plusieurs Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/introduction.html?lang=en#sign-multiple-documents) | Tutoriel | Que vous demandiez une hypothèque ou que vous ouvriez un nouveau compte bancaire, vous devez remplir et signer plusieurs formulaires. L’intégration entre le Experience Manager Forms et Adobe Sign facilite le remplissage et la signature de plusieurs formulaires. |
| 28 janvier 2021 | [Authentification basée sur un jeton - Jeton d&#39;accès de développement local](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/local-development-access-token.html?lang=en#authentication) | Vidéo | Découvrez comment la Console développeur des Experience Manager permet aux développeurs de générer eux-mêmes des jetons d&#39;accès temporaires qui peuvent être utilisés pour accéder par programmation aux Experience Manager. |
| 28 janvier 2021 | [Authentification basée sur un jeton à AEM en tant que Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | Vidéo | Découvrez comment une application externe peut s’authentifier par programmation et interagir avec le Experience Manager en tant que Cloud Service sur HTTP à l’aide de jetons d&#39;accès. |
| 24 janvier 2021 | [Créer le formulaire principal pour déclencher le processus](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/create-initial-form.html) | Article | Le formulaire initial (Formulaire de refinancement) est utilisé pour signer plusieurs formulaires en déclenchant le flux de travail [!UICONTROL Signer plusieurs Forms AEM]. |
| 8 janvier 2021 | [Exécution du pipeline de production de CD/CI de Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | Vidéo | La configuration du pipeline de production CI/CD définit le déclencheur qui initie le pipeline, les paramètres contrôlant le déploiement de production et les paramètres de test de performances. |
| 8 janvier 2021 | [Activité d’Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/activity.html) | Vidéo | Cloud Manager fournit une vue consolidée dans l’activité d’un Programme, répertoriant toutes les exécutions de pipeline CI/CD, tant en production qu’en non-production. Cette fonctionnalité permet aux utilisateurs de vue des pipelines en cours et de passer en revue les déploiements précédents. |
| 8 janvier 2021 | [Pipelines de non-production Adobe Cloud Manager pour CI/CD](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-non-production-pipeline.html) | Vidéo | Les pipelines de CI/CD hors production sont divisés en deux catégories, des pipelines de qualité de code et des pipelines de déploiement. La qualité du code canalise tout le code d’une branche Git pour générer et être évaluée par rapport à l’analyse de la qualité du code de Cloud Manager. |
| 8 janvier 2021 | [Configuration du pipeline de production de CD/CI d&#39;Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | Vidéo | La configuration du pipeline de production CI/CD définit le déclencheur qui initie le pipeline, les paramètres contrôlant le déploiement de production et les paramètres de test de performances. |
| 8 janvier 2021 | [Environnements d’Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/environments.html) | Vidéo | Les Environnements de Cloud Manager sont composés de services Experience Manager Author, Experience Manager Publish et Dispatcher. Différents environnements prennent en charge des rôles et peuvent être engagés à l&#39;aide de différents pipelines CI/CD. Les environnements de Cloud Manager comportent généralement un environnement de production, un environnement d’étape et un environnement de développement. |
| 8 janvier 2021 | [Présentation graphique sans en-tête de QL](https://internal.adobedemo.com/content/demo-hub/en/demos/internal/aem-headless-graphql.html) | Démonstration | Les API de qualité de Experience Manager exposent le contenu des fragments de contenu Experience Manager aux applications en aval. Les API GraphQL peuvent être utilisées dans des cas d’utilisation à la fois inactifs et hybrides. |
| 8 janvier 2021 | [Programmes d’Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/programs.html) | Vidéo | Les Programmes de Cloud Manager représentent des ensembles d’environnements Experience Manager prenant en charge des ensembles logiques d’initiatives commerciales, correspondant généralement à un contrat de niveau de service (SLA) acheté. |
| 8 janvier 2021 | [Authentification basée sur un jeton](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | Vidéo | Les Programmes de Cloud Manager représentent des ensembles d’environnements Experience Manager prenant en charge des ensembles logiques d’initiatives commerciales, correspondant généralement à un contrat de niveau de service (SLA) acheté. |
| 8 janvier 2021 | [Importation en masse](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html) | Vidéo | L&#39;outil d&#39;importation en bloc en Experience Manager en tant que Cloud Service permet aux administrateurs d&#39;importer en bloc des actifs à partir de l&#39;enregistrement de cloud (Azure Blob Enregistrement ou Amazon S3) de manière sécurisée et efficace. |

### Autres ressources d’aide pour le Experience Manager

* [Experience Manager en tant que guides Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/landing/home.html)
* [Experience Manager 6.5 Accueil - Formation et support](https://helpx.adobe.com/fr/support/experience-manager/6-5.html)
* [Experience Manager 6.4 Accueil - Formation et support](https://helpx.adobe.com/fr/support/experience-manager/6-4.html)
* [Experience Manager 6.3 Accueil - Formation et support](https://helpx.adobe.com/fr/support/experience-manager/6-3.html)
* [Experience Manager 6.2 Accueil Formation et support](https://helpx.adobe.com/fr/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Versions plus anciennes de la documentation du Experience Manager](https://helpx.adobe.com/fr/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/fr-FR/dynamic-media-classic/using/home.html)

## ![Icône](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Dernières versions du produit

Pour en savoir plus sur les dernières fonctionnalités, améliorations et correctifs disponibles :

* [Notes de mise à jour de Campaign Standard](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html)
* [Notes de mise à jour de Campaign Classic](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.html)

### Nouveaux cours et tutoriels sur Campaign

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publication | Nom | Solution | Description |
| -----------| ---------- | ---------- | ---------- |
| 5 février 2021 | [Prise en main de Adobe Campaign Classic pour les utilisateurs professionnels](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.classic) | Campaign Classic | Après avoir suivi ce cours, vous comprendrez les concepts de Adobe Campaign Classic et saurez comment créer votre première campagne marketing. |
| 1 février 2021 | [Introduction aux canaux multiples et aux canaux croisés](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/introduction-to-cross-and-multi-channel-campaigns.html) | Campaign Classic | Comprendre la différence entre les campagnes à plusieurs canaux et les campagnes à plusieurs canaux et connaître les cas d’utilisation des campagnes à plusieurs canaux et à plusieurs canaux. |
| 1 février 2021 | [Créer une Diffusion SMS](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/sms-channel/create-a-sms-delivery.html) | Campaign Classic | Découvrez comment créer une diffusion SMS. |
| 1 février 2021 | [Créer des campagnes entre canaux](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/cross-channel-campaigns.html) | Campaign Classic | Découvrez comment créer et exécuter une campagne sur plusieurs canaux. |
| 29 janvier 2021 | [Utiliser des Populations témoins](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/use-control-groups.html) | Campaign Classic | Comprenez le concept des Populations témoins et apprenez à utiliser une Population témoin pour votre diffusion. |
| 28 janvier 2021 | [Envoyer et valider des BAT](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/send-and-validate-proofs.html) | Campaign Classic | Découvrez comment envoyer et valider un BAT. |
| 28 janvier 2021 | [Créer des courriers électroniques pour la livraison](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/design-emails-for-deliverability.html) | Campaign Classic | Découvrez comment appliquer les meilleures pratiques en matière de délivrabilité. |
| 28 janvier 2021 | [Création et conception de diffusions de messagerie](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/create-and-design-email-deliveries.html) | Campaign Classic | Comprenez le processus de création d’une diffusion de messagerie et apprenez à concevoir et à personnaliser du contenu de messagerie. |
| 27 janvier 2021 | [Créer des campagnes déclenchées par un événement](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/getting-started/create-event-triggered-campaigns.html) | Campaign Classic | Découvrez comment créer une campagne déclenchée par un événement et comprendre ses utilisations. |

### Ressources d’aide

* Adobe Campaign Standard : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/campaign-standard-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/overview.html) - [Calendrier des versions](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-planning.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/campaign-classic-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/tutorials/overview.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/documentation-updates.html)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/control-panel/using/release-notes.html) - Tutoriels vidéo pour [Campaign Standard](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icône](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notes de mise à jour d’Adobe Advertising Cloud.

* [Nouvelles fonctionnalités dans Advertising Cloud DSP](#adcloud-dsp)
* [Nouvelles fonctionnalités dans Advertising Cloud Search](#adcloud-search)

### Nouvelles fonctionnalités d’[!DNL Advertising Cloud DSP] {#adcloud-dsp}

Dernière mise à jour : **28 octobre 2020**

| Fonctionnalité | Description |
| -----------| ---------- |
| Nouveau Aide | (Version du 28 octobre) L’aide héritée a été remplacée par des pages mises à jour, disponibles à partir du lien « Aide » dans le menu principal DSP et également disponibles à tout moment depuis [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=fr](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=fr-FR) |
| Campagnes | (Version du 28 octobre) Les précédentes vues bêta des campagnes sont désormais les vues par défaut des campagnes, ce qui permet d’obtenir des informations plus rapides, de simplifier les workflows et de personnaliser les vues. |
| Inventaire privé | (Version du 15 octobre) Tous les utilisateurs peuvent désormais configurer et modifier les détails de l’ID de la transaction en utilisant un nouveau formulaire d’ID de transaction, qui est une version simplifiée de l’ancien formulaire [!UICONTROL Smart Ad Serving]. Pour configurer les détails de l’ID de la nouvelle transaction, accédez à **[!UICONTROL Inventaire > Transactions]**, cliquez sur **[!UICONTROL Créer]**, puis sur **[!UICONTROL ID de transaction bêta]**. |
| Prévisions de placement | (Version du 15 octobre) Pour les placements avec une fréquence de placement, la section [!UICONTROL Prévision] des paramètres de placement inclut une nouvelle section [!UICONTROL Maximums estimés], qui indique la capacité supplémentaire disponible avec la configuration de ciblage actuelle. |

### Nouvelles fonctionnalités d’[!DNL Advertising Cloud Search] {#adcloud-search}

Dernière mise à jour : **23 février 2021, pour la version du 20 février**

| Fonctionnalité | Description |
| -----------| ---------- |
| Toutes | Outils > &quot;Adwords Conversion Tags&quot; est désormais &quot;Google Publics Conversion Tags&quot;.&quot; |
| Toutes | En avril, les fonctionnalités et vues suivantes seront abandonnées :<br><ul><li>Optimisation > Cartes de Portfolio</li><li>Optimisation > Règles sur l&#39;offre</li><li>Statistiques et rapports > Tableau de bord</li><li>Campagnes :  Prise en charge en attente et programmée des modifications en masse</li></ul> |

### Tutoriels et cours Advertising Cloud

Mise à jour : **23 février 2021**

| Tutoriel | Description |
| -----------| ---------- |
| [Présentation de l’espace de travail et du Rapports](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-analysis-workspace-a4adc.html) | Découvrez comment utiliser vos données Advertising Cloud pour créer des rapports visuels dans Adobe Analytics Analysis Workspace. |

## ![Icône](/assets/magento.png) [!DNL Magento] {#magento}

Voir les [notes de mise à jour de Magento Commerce et d’Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) pour obtenir les informations les plus récentes.

## ![Icône](/assets/target.png)[!DNL Target] {#target}

Voir les [[!DNL Target] notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html) pour consulter les informations les plus récentes.

## ![Icône](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] est une application complète destinée à la gestion des pistes et aux spécialistes du marketing B2B qui cherchent à transformer les expériences client en s&#39;engageant à toutes les étapes de parcours d&#39;achat complexes.

### Mises à jour de Core Marketo Engage

Voir les [notes de mise à jour](https://docs.marketo.com/display/public/DOCS/Release+Notes) [!DNL Marketo Engage] pour consulter les informations les plus récentes.

### Fonctionnalités à venir

Les fonctionnalités suivantes seront publiées tout au long du trimestre :

| Fonctionnalité | Description |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Nouvelle segmentation basée sur un compte</li><li>Enregistrement des filtres spécifiques au tableau de bord</li><li>Exportation de tableaux de bord Bizible au format PDF</li></ul> |
| Connect de ventes | Composition des mises à jour/améliorations des fenêtres et du Centre de commandes |

### Dépréciations

* **Paramètre de l’API de ressource &quot;_method&quot; :** après septembre 2020, les points de fin d’API d’actif n’accepteront plus `_method` pour transmettre les paramètres de requête dans un corps POST afin de contourner les limitations de longueur d’URI.
* **Dépréciation de la prise en charge d’Internet Explorer :** à compter de la version du 31 juillet 2020, l’interface utilisateur de Marketo Engage ne sera plus prise en charge dans Internet Explorer.

## ![Icône](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Document Cloud.

### Tutoriels Acrobat

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 8 février 2021 | [Entrée de présentation Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html) | Centre d&#39;apprentissage | Bienvenue dans le centre d&#39;apprentissage Adobe Acrobat. Vous y trouverez un large éventail d&#39;expériences d&#39;apprentissage axées sur l&#39;Adobe Acrobat. Nos didacticiels, webinars et exemples d’utilisation sont conçus pour permettre aux utilisateurs débutants et avancés d’être rapidement informés sur Adobe Acrobat. |

### Didacticiels Adobe Sign

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 8 février 2021 | [Présentation de l&#39;entrée - Prise en charge de la ressource](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html) | Centre d&#39;apprentissage | Bienvenue dans le centre d&#39;apprentissage Adobe Sign. Vous y trouverez un large éventail d’expériences d’apprentissage axées sur l’Adobe Sign. Nos didacticiels, webinars et exemples d’utilisation sont conçus pour permettre aux débutants et aux administrateurs de se familiariser rapidement avec Adobe Sign. |

Pour obtenir de l’aide sur Document Cloud, voir :

* [Hub d’apprentissage Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=fr)
* [Hub d’apprentissage Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=fr)
* [Formation et assistance pour Document Cloud](https://helpx.adobe.com/fr/support/document-cloud.html)

## ![](/assets/creative-cloud-24.png) IconCreative Cloud Enterprise  {#creative-cloud}

Nouveaux didacticiels pour Creative Cloud Enterprise.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 3 février 2021 | [Création de paragraphes avec Photoshop](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/cinemagraphps.html?lang=en#cceoverview) | Vidéo | Découvrez comment créer une photo vivante en combinant des vidéos d&#39;Adobe Stock avec des techniques de masquage intelligentes à Photoshop. |
| 3 février 2021 | [Création de composites uniques avec Adobe Stock et Photoshop pour iPad](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/compositepsipad.html?lang=en) | Vidéo | Apprenez à utiliser l&#39;une de vos applications de Creative Cloud préférées d&#39;une toute nouvelle façon, avec une interface tactile repensée. |
| 3 février 2021 | [Personnaliser et marquer un modèle 3D avec Dimension et Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/3ddimensionstock.html?lang=en) | Vidéo | Personnalisez et marquez un modèle 3D en Dimension en utilisant des matériaux, des propriétés environnementales, de l&#39;éclairage et de la photographie, afin de créer des images photo-réalistes pour tout projet de conception. |
| 2 février 2021 | [Comprendre les composants dans Adobe XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/xdoverview/components.html) | Vidéo | Découvrez comment utiliser les composants pour vous offrir une flexibilité sans précédent pour appliquer à la fois la vitesse et la cohérence à votre flux de travaux de conception. |
| 2 février 2021 | [Conseils et techniques pour la maîtrise de l&#39;éclairage 3D dans CGI](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/mastering3dlighting.html?lang=en) | Article | Découvrez l&#39;éclairage 3D et comment créer des conditions lumineuses différentes qui peuvent modifier complètement une scène générée par ordinateur et la façon dont les objets y sont présentés. |
| 2 février 2021 | [Création d&#39;une photographie virtuelle photoréaliste à l&#39;aide du rendu 3D et de la composition](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/photorealistic.html?lang=en#3doverview) | Article | Apprenez à créer une photographie virtuelle photoréaliste avec le rendu et la composition 3D. |
| 29 janvier 2021 | [Guides de référence rapide du CCE](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/overview-ref.html) | Guides de référence rapides | Accédez à des guides de référence rapides qui vous aideront à découvrir les nouvelles fonctionnalités du Creative Cloud. |

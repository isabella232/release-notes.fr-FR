---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Notes de mise à jour d’Adobe Experience Cloud
doc-type: release notes
last-update: July 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 3947290a3d13ab4cef1d6d9ec639fa70a250c36a
workflow-type: tm+mt
source-wordcount: '4377'
ht-degree: 99%

---


# Notes de mise à jour d’Adobe Experience Cloud - juillet 2020

![Bannière](/assets/experience-cloud-banner-3.png)

Cette page décrit les nouvelles fonctionnalités, les correctifs et des informations importantes pour [!DNL Adobe Experience Cloud]. Elle met également en évidence la nouvelle documentation, les formations et les tutoriels vidéo qui vous permettent de tirer le meilleur parti d’Experience Cloud.

>[!NOTE]
>
>Inscrivez-vous aux [Mises à jour produit prioritaires d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) afin de recevoir une notification par courrier électronique concernant les prochaines mises à jour.

**Date de publication : 16 juillet 2020**

Les dates de publication du produit peuvent varier. Consultez régulièrement les mises à jour.

Dernière mise à jour : **14 juillet 2020**

* [Statut du système Adobe](#status)
* [Interface d’Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) et [Customer Journey Analytics](#cust-journey)  (Mise à jour le 14 juillet 2020)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/fr/primetime/user-guide.html) (liens vers la page d’aide de Primetime)

Besoin d’aide ? Consultez [Adobe Experience League](https://experienceleague.adobe.com/#home) pour trouver de la documentation technique et sur les produits, des cours préparés par Adobe, des tutoriels vidéo, des réponses rapides, des informations provenant de la communauté et des formations dispensées par un instructeur.

## ![Icône](/assets/adobe.png) Statut du système Adobe {#status}

[!UICONTROL Statut du système Adobe] fournit des informations détaillées, des mises à jour de statut et des notifications par email relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

Publié le : **21 mai 2020**

**Nouveautés**

* Avec votre Adobe ID, vous pouvez vous abonner à des notifications d’événement avec plus de granularité et associées au niveau de l’offre de produit et des modules complémentaires. Pour vous aider à configurer votre abonnement plus rapidement, le processus d’auto-abonnement recommande désormais une sélection de produits et d’offres en fonction de vos droits sur les produits. Cela devrait réduire le nombre d’emails que vous recevez et fournir des notifications plus pertinentes dans votre boîte de réception. Rendez-vous sur [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nouvelles fonctionnalités et améliorations disponibles dès maintenant**

| Fonctionnalité | Description |
| -----------| ---------- |
| Amélioration de l’expérience utilisateur pour les abonnements et les notifications | <ul><li>Les emplacements régionaux [!DNL Marketo Engage] sont désormais filtrés en fonction de la liste des offres de produits sélectionnées.</li><li>Les notifications par email [!DNL Marketo Engage] sont pertinentes pour la région, l’emplacement et les préférences d’environnement de l’utilisateur.</li></ul> |
| Confirmation d’abonnement à l’événement | <ul><li>Vous pouvez désormais obtenir une confirmation par email lorsque vous vous abonnez à des mises à jour d’événement unique en cours.</li></ul> |
| Améliorations de la convivialité de la navigation globale | <ul><li>Expérience de l’utilisateur cohérente avec `Adobe.com` dans le menu de navigation de niveau supérieur.</li></ul> |

## ![Icône](/assets/ec_appicon_24.png) Interface d’Experience Cloud {#ecloud}

Mises à jour générales de l’interface d’Experience Cloud.

**Menu de l’interface mis à jour**

Dans Experience Cloud, la version du **16 juillet 2020** met à jour le menu déroulant Sélecteur d’applications. Il a été rationalisé afin que les logos des solutions soient supprimés et que le menu affiche uniquement les applications et services auxquels vous avez accès.

Consultez la [documentation du produit](https://docs.adobe.com/content/help/fr-FR/core-services/interface/experience-cloud.html) de l’interface d’Experience Cloud pour obtenir un exemple.

**Domaine de produit unifié**

Adobe a mis à jour l’en-tête de domaine et d’interface afin d’unifier et d’améliorer votre expérience dans toutes les applications Experience Cloud. Ces améliorations sont conçues pour fluidifier votre utilisation de manière simple, mais importante. Ces améliorations ne modifient pas vos processus actuels.

Les mises à jour comprennent les éléments suivants :

* Nouvelles URL d’application : `experience.adobe.com/<application name>` :
   * À terme, tous les produits adopteront ce modèle d’URL. Recherchez de nouvelles URL pour qu’elles prennent effet tout au long du mois.
   * Navigateurs pris en charge : [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] et [!DNL Opera] (versions les plus récentes). **Remarque** : bien que l’interface d’Experience Cloud soit compatible avec ces navigateurs, les applications individuelles peuvent ne pas tous les prendre en charge. (Par exemple, [Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/admin/sys-reqs.html) ne prend pas en charge [!DNL Opera] et [Target](https://docs.adobe.com/help/fr-FR/target/using/implement-target/before-implement/supported-browsers.html) ne prend pas en charge [!DNL Safari].)
   * ([!DNL Safari] uniquement) Le changement de domaine peut entraîner des problèmes de cookies dans [!DNL Safari]. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité de [!DNL Safari], vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Experience Cloud de fonctionner sur ce nouveau domaine.
* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide des produits : [!UICONTROL Experience League] est intégré dans le produit afin qu’une recherche d’aide comprenne également les résultats des forums de la communauté et du contenu vidéo. Cette modification simplifie l’accès à davantage de contenu et vous permet de tirer le meilleur parti d’Experience Cloud. De plus, vous pouvez cliquer sur **[!UICONTROL Aide]** > **[!UICONTROL Commentaires]** pour signaler des problèmes ou partager vos idées avec Adobe.

Les applications suivantes utilisent le nouveau domaine experience.adobe.com :

| Application ou service | Domaine |
| -----------| ---------- |
| Page d’accueil Experience Cloud | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Gestion des parcours | `experience.adobe.com/journeys` |
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Panneau de contrôle d’Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Distribution logicielle | `experience.adobe.com/downloads` |
| Outil d’administration (bêta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Panorama et collections]**, un filtre hérité dans le sélecteur de [!UICONTROL ressources Experience Cloud], est en cours de désactivation.

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Notes de mise à jour d’[!DNL Experience Platform] et des services d’application, y compris des services [!UICONTROL Offres], [!UICONTROL Personnes], [!UICONTROL Places], et [!UICONTROL Mobile Services] d’[!DNL Experience Platform Launch,], et des bulletins de sécurité.

Dernière date de publication : **10 juin 2020**

Voir les [notes de mise à jour Experience Platform](https://docs.adobe.com/content/help/fr-FR/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) pour obtenir les informations les plus récentes sur Experience Platform.

## ![Icône](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Grâce à Adobe Experience Platform, orchestrez des parcours clients individuels à l’échelle sur des canaux d’expérience en anticipant de manière intelligente les besoins de chaque individu en temps réel, quel que soit l’endroit où leur parcours les mène.

### Ressources supplémentaires pour Journey Orchestration

[Documentation](https://docs.adobe.com/content/help/fr-FR/journeys/using/journey-orchestration-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html) - [Tutoriels vidéos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Icône](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Date de publication : **16 juillet 2020**

* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features)
* [Nouvelles fonctionnalités dans Customer Journey Analytics](#cust-journey)
* [Nouvelles fonctionnalités de Media Analytics](#media-aa)
* [Correctifs dans Adobe Analytics](#aa-fixes)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)  (Mise à jour le 13 juillet 2020)
* [Nouveaux cours et tutoriels d’Adobe Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.html) - Date cible | Description |
| -----------| ---------- |-------|
| ADC : Accrochage basé sur les champs | 27 juillet 2020 | Nouvelle méthode d’Analytics sur plusieurs périphériques qui vous permet d’utiliser une variable personnalisée pour identifier les visiteurs. |
| Workspace : nouveaux paramètres prédéfinis de période | 16 juillet 2020 | Quatre nouvelles périodes ont été ajoutées (_cette semaine/ce mois/ce trimestre/cette année_, à l’exception d’aujourd’hui) afin que les utilisateurs puissent choisir parmi des périodes ne comprenant pas de données de journée partielle pour la journée en cours. |
| API Data Repair – version bêta publique | 14 juillet 2020 | L’[!UICONTROL API Data Repair] vous offre un mécanisme de suppression ou de modification de certaines données Adobe Analytics existantes. Les demandes de [!UICONTROL réparation de données] sont effectuées en envoyant une définition de travail à l’[!UICONTROL API Data Repair], qui inclut la suite de rapports, la période, les variables et les actions à appliquer aux données. Lors du lancement de la version bêta publique, l’[!UICONTROL API Data Repair] prend en charge la suppression des données d’[!UICONTROL Activity Map]. D’autres fonctionnalités seront déployées ultérieurement. Contactez l’Assistance clientèle pour rejoindre la version bêta publique de l’API Data Repair. [En savoir plus...](https://github.com/AdobeDocs/analytics-2.0-apis/blob/master/data-repair.md) |

### Nouvelles fonctionnalités dans Customer Journey Analytics {#cust-journey}

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.html) - Date cible | Description |
| -----------| ---------- |-----|
| Aucune nouvelle fonctionnalité ce mois-ci |  |  |

### Nouvelles fonctionnalités de [!UICONTROL Media Analytics] {#media-aa}

Date de publication : **16 juillet 2020**

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.html) - Date cible | Description |
| -----------| ---------- | ---------- |
| [Appareils et plateformes pris en charge](https://docs.adobe.com/content/help/fr-FR/media-analytics/using/supported-devices.html) | 18 juin 2020 | L’extension Media Launch avec SDK AEP prend désormais en charge les appareils OTT suivants :<ul><li>Apple TV (tvOS)</li><li>Fire TV (Système d’exploitation Fire)</li><li>Android TV</li></ul> |  | [Appareils et plateformes pris en charge](https://docs.adobe.com/content/help/fr-FR/media-analytics/using/supported-devices.html) | 18 juin 2020 | L’extension Media Launch avec SDK AEP prend désormais en charge les appareils OTT suivants :<ul><li>Apple TV (tvOS)</li><li>Fire TV (Système d’exploitation Fire)</li><li>Android TV</li></ul> |
| [Suivi de l’état du lecteur](https://docs.adobe.com/content/help/fr-FR/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 mai 2020 | Les clients [!UICONTROL Media Analytics] peuvent capturer l’interaction de la visionneuse au cours de la lecture à l’aide d’un jeu standard de variables de solution pour le mode Plein écran, le sous-titrage, le mode silencieux, l’incrustation dans l’image et le mode In-Focus. Vous pouvez également créer des états de lecteur personnalisés. Des comptes rendus des performances sur les variables de suivi de l’état du lecteur sont désormais disponibles dans [!UICONTROL Analysis Workspace]. Cette fonctionnalité nécessite l’une des configurations suivantes : <ul><li>SDK Media [!DNL JavaScript] 3.0 ou version ultérieure</li><li>Utilisation avec le SDK [!DNL Adobe Experience Platform] (AEP) :</li><li>[!UICONTROL Extension Media Analytics] (pour le web) : [!UICONTROL Adobe Media Analytics] (SDK 3.x) pour Audio et Video v1.0 ou version ultérieure</li><li>[!UICONTROL Extension Media Analytics] (pour mobile) : [!UICONTROL Adobe Media Analytics pour Audio] et Vidéo v2.0 ou version ultérieure</li><li>[!UICONTROL Collection Médias]</li></ul> |

### Correctifs dans Adobe Analytics {#aa-fixes}

* Correction d’un problème qui survenait après le passage à une suite de rapports avec une autre devise. Le graphique en courbes [!UICONTROL Workspace] ne reflétait pas la bonne devise. (AN-216655)
* Correction de problèmes liés aux visualisations illisibles dans les fichiers PDF téléchargés. (AN-217949)
* Correction d’un problème qui provoquait une erreur lors de l’ajout d’une variable de hiérarchie à une suite de rapports. (AN-211974)
* Correction d’un problème survenant lors de la modification d’un flux de données associé à une suite de rapports dont le fuseau horaire était différent de celui de la suite de rapports [!UICONTROL Reports &amp; Analytics] sélectionnée. (AN-222474)
* Correction d’un problème de dysfonctionnement du [!UICONTROL Créateur de règles de classification]. (AN-219662)
* Correction de plusieurs problèmes liés aux classifications et aux règles de classification. (AN-223492, AN-220654, AN-219662, AN-223260)
* Correction d’un problème concernant le renvoi, par le même segment, de données différentes dans une suite de rapports virtuelle par rapport à la suite de rapports parente. (AN-201074)
* Correction d’un problème qui empêchait le téléchargement des paramètres de la suite de rapports. (AN-223690)
* Correction d’un problème dans les [!UICONTROL Alertes intelligentes] qui empêchait le fonctionnement du lien du courrier électronique _Opt-out de ce planning_. (AN-223875)
* Correction d’un problème lié à l’affichage d’une devise incorrecte pour une suite de rapports virtuelle. (AN-224781)
* Correction d’un problème lié à des erreurs de _composants manquants_ dans les suites de rapports virtuelles. (AN-224782)
* Correction d’un problème en raison duquel la ventilation d’une classification d’une dimension par une autre pouvait renvoyer des résultats vides lorsqu’elle était utilisée avec une mesure calculée avec une affectation de participation définie. (AN-214089)

#### Correctifs Adobe Analytics supplémentaires

AN-222672, AN-222813, AN-222892, AN-223272, AN-223432, AN-224062, AN-224108, AN-224163, AN-224339, AN-224456, AN-224449, AN-224552, AN-224553, AN-224786

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout  ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Fin de vie des connecteurs de données Adobe | 13 juillet 2020 | Les connecteurs de données Adobe sont alimentés par une technologie héritée qui n’est plus viable ni prise en charge. Nous disposons d’un nouveau standard dans le [Programme de partenariat Adobe Exchange](https://partners.adobe.com/exchangeprogram/experiencecloud) qui devrait être adopté pour toutes les intégrations qui souhaitent continuer à être proposées et prises en charge. La date officielle de fin de vie n’a pas encore été fixée, mais elle devrait avoir lieu dans les 12 à 18 prochains mois (mi-2021 à fin 2021). [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics/import/dataconnectors/data-connectors-eol.html) |
| Mappage d’une suite de rapports à l’organisation IMS | Juillet 2020 | L’outil de mappage des suites de rapports sera abandonné en novembre 2020. Cette fonctionnalité optimise les intégrations telles que la publication de segments Advertising Analytics et Experience Cloud dans Adobe Analytics. Une suite de rapports doit être mappée à une organisation IMS pour activer ces services et d’autres services. Les nouvelles suites de rapports sont automatiquement mappées lors de leur création. Cependant, les anciennes suites de rapports doivent être mappées manuellement à une organisation IMS. Consultez [Mappage des suites de rapports à une organisation](https://docs.adobe.com/content/help/fr-FR/core-services/interface/about-core-services/report-suite-mapping.html) dans le guide d’utilisation des services principaux pour vous assurer que toutes les suites de rapports appartiennent à une organisation IMS. |
| Migration vers un domaine de produit unifié | Date d’entrée en vigueur : 28 mai 2020 | La migration vers un domaine de produit unifié pour Adobe Analytics, débutée en janvier 2020, s’est terminée le 28 mai 2020. Tandis qu’Adobe Analytics s’emploie à supprimer toutes les références de domaine `omniture.com` de son architecture, il est important de créer une liste autorisée `omniture.com` comme cookie tiers. Nous vous informerons via les notes de mise à jour dès que la migration complète de l’architecture sera terminée (bientôt). L’étape de liste d’autorisation ne sera ainsi plus nécessaire. Vous trouverez [ici](https://helpx.adobe.com/fr/analytics/kb/adobe-ip-addresses.html) une liste complète de domaines et d’adresses IP recommandés que vous devriez inclure dans votre liste d’autorisation.<br>Si votre entreprise bloque les cookies tiers, contactez l’assistance clientèle pour récupérer l’accès à votre compte Adobe Analytics. |
| Nouvelle page d’entrée par défaut d’Adobe Analytics | Date d’entrée en vigueur : 18 juin 2020 | Le 18 juin 2020, la page d’entrée par défaut d’Adobe Analytics passera de [!UICONTROL Rapports] à [!UICONTROL Workspace]. Cette modification se produira pour tous les utilisateurs n’ayant pas défini de page d’entrée personnalisée auparavant. |
| Liste d’autorisation des technologies tierces | 12 mars 2020 (date de mise en vigueur) | Adobe Analytics a commencé à utiliser des technologies tierces pour la gestion du déploiement de fonctionnalités et la prise en charge intégrée. Les URL suivantes doivent être ajoutées aux listes d’autorisation de pare-feu réseau nécessaires pour garantir un accès complet aux fonctionnalités :<ul><li>Gainsight : https://esp.aptrinsic.com</li><li>LaunchDarkly : https://app.launchdarkly.com</li></ul> |
| Amélioration de la redondance pour la disponibilité d’[!UICONTROL Analysis Workspace] | 21 mai 2020 | Afin d’assurer la disponibilité d’[!UICONTROL Analysis Workspace], nous ajoutons un réseau CDN secondaire (réseau de diffusion de contenu) pour une redondance améliorée. Les URL suivantes doivent être ajoutées aux listes d’autorisation de pare-feu réseau nécessaires :<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Modification du mode de calcul des [!UICONTROL entrées/sorties] dans [!UICONTROL Workspace] | 7 avril 2020 | Dans [!UICONTROL Analysis Workspace], depuis mars 2020, nous avons modifié la manière dont la valeur _Aucun_ interagit avec les [!UICONTROL entrées/sorties]. Comme vous pouvez désormais activer et désactiver l’option _Aucun_ dans [!UICONTROL Analysis Workspace], nous appliquons l’option _Aucun_ après l’entrée ou la sortie, alors que (pour les eVars) elle était appliquée avant l’entrée ou la sortie. Supposons, par exemple, que le premier accès d’une visite n’ait aucune valeur pour eVars, contrairement au second accès. Dans [!UICONTROL Reports &amp; Analytics], le premier accès s’affichera comme _Non spécifié_ pour l’entrée, mais dans [!UICONTROL Analysis Workspace], il affichera la valeur pour le second accès. |
| Abandon de l’**[!UICONTROL archive de tableau de bord]** | 27 mars 2020 | Le paramètre **[!UICONTROL Afficher l’archive]** sous **[!UICONTROL Gérer les tableaux de bord]** dans [!UICONTROL Reports &amp; Analytics] ne sera plus disponible à compter du mois d’octobre 2020. |
| Fin de vie des API héritées d’Analytics | 9 janvier 2020 | En novembre 2020, les services d’API hérités d’Analytics suivants arriveront en fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner. <ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Nous avons mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | Pour les clients basés à Londres et à Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fin de vie d’Ad Hoc Analysis | 6 août 2018 | Adobe a annoncé la prochaine fin de vie d’Ad Hoc Analysis. La date de fin de vie sera communiquée dès que possible. Pour obtenir de plus amples informations, voir le site [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### AppMeasurement

Pour connaître les dernières mises à jour des versions d’AppMeasurement, reportez-vous aux [notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/fr-FR/analytics/implementation/appmeasurement-updates.html).

#### Ressources d’aide à propos d’Analytics

* [Tutoriels Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentation produit Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/landing/home.html)

## ![Icône](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nouveaux correctifs, fonctionnalités, documentation et tutoriels pour Audience Manager.

Date de publication : **16 juillet 2020**

### Nouvelles fonctionnalités et correctifs dans Adobe Audience Manager

* Correction d’un problème en raison duquel les clients ne pouvaient pas mapper certains segments aux destinations Amazon. (AAM-54373)
* Correction d’un problème en raison duquel l’écran du navigateur se figeait lorsque les clients ouvraient un segment dans un nouvel onglet. (AAM-55213)
* Correction d’un problème dans le [rapport État de l’intégration](https://docs.adobe.com/help/fr-FR/audience-manager/user-guide/reporting/onboarding-status-report.html), en raison duquel les clients constataient une différence entre la date qui apparaissait lorsqu’ils cliquaient sur une barre du graphique et la date du tableau. (AAM-55235)
* Correction d’un bogue dans la section Administration, en raison duquel l’interface utilisateur affichait une icône d’erreur au lieu d’un message de confirmation lorsque les clients tentaient de supprimer des utilisateurs. (AAM-55186)
* Correction d’un problème avec l’API Swagger, en raison duquel l’en-tête `x-api-key` n’était pas ajouté à la demande de curl. (AAM-55392)
* Amélioration de l’ordre de tri par défaut des segments mappés aux destinations dans l’affichage des destinations. Les segments mappés sont maintenant triés par date de début du mappage de segments, puis par identifiant de segment. (AAM-38494)
* Plusieurs améliorations de l’accessibilité de l’interface. (AAM-48956, AAM-49012, AAM-49364, AAM-49363, AAM-49374, AAM-49579, AAM-55037).

## ![Icône](/assets/aem.png) Adobe Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Mises à jour de produit

* **Dynamic Media Classic**

   Les utilisateurs de Dynamic Media Classic ont désormais accès à une nouvelle expérience d’application de bureau qui ne repose plus sur la technologie Adobe Flash dans le navigateur. La nouvelle application est désormais disponible pour Windows et macOS.

   Voir [Application de bureau Dynamic Media Classic d’Adobe – Maintenant disponible.](https://docs.adobe.com/content/help/fr-FR/dynamic-media-classic/using/new-ui-2020.html)

* **Ajout de la prise en charge des ressources 3D à Dynamic Media**

   Dynamic Media dans AEM 6.5 et AEM as a Cloud Service vous permet désormais de charger, gérer, afficher et diffuser des ressources 3D sous forme d’expériences immersives.

   * Dans AEM as a Cloud Service, consultez [Utilisation de ressources 3D dans Dynamic Media.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/assets-3d.html)
   * Dans AEM 6.5, consultez [Utilisation de ressources 3D dans Dynamic Media.](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/assets/dynamic/assets-3d.html)

### Auto-assistance

* **Mises à jour de la documentation d’AEM 6.5.5 Forms**

   * Nouvelles fonctionnalités et améliorations de la version 6.5.5 :

      * [Personnalisez les colonnes de la boîte de réception d’Adobe Experience Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/authoring/essentials/inbox.html#inbox-admin-control).
      * [Enregistrez les communications interactives en tant que brouillon.](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#save-as-draft)
      * Prise en charge du serveur d’applications Oracle WebLogic pour les installations de [serveur unique](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-single-server.pdf) et de [cluster](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-cluster.pdf).
      * [Améliorations de l’accessibilité.](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#accessibility-improvements)
      * [Authentification par certificat X-509 pour les services web SOAP dans le modèle de données de formulaire.](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Prise en charge d’Oracle RAC.](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#other-improvements)
      * [Amélioration de la journalisation des erreurs dans les rapports de transaction.](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)
   * Nouvelles fonctionnalités et améliorations de la version 6.4.8.1 :
      * [Authentification par certificat X-509 pour les services web SOAP dans le modèle de données de formulaire.](https://docs.adobe.com/content/help/fr-FR/experience-manager-64/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Amélioration de la journalisation des erreurs dans les rapports de transaction.](https://docs.adobe.com/content/help/fr-FR/experience-manager-64/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)

### **Communauté**

* **Discussions de la communauté AEM**

   Vous pouvez maintenant consulter toutes les annonces AEM ainsi que les références intéressantes aux blogueurs internes et externes dans un seul et même endroit. Consultez la [section Discussions](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions) de la communauté AEM.

### Nouveaux cours et tutoriels sur Experience Manager

Nouveaux tutoriels, vidéos ou cours publiés le mois dernier.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 25 juin 2020 | [Prise en main des formulaires adaptatifs](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/creating-your-first-adaptive-form/adaptive-forms-getting-started-tutorial-use.html) | Vidéo | Ces tutoriels décrivent les étapes de création d’un formulaire adaptatif à plusieurs onglets. Découvrez comment utiliser des tableaux, une disposition en accordéon et un éditeur de règles pour créer des règles de fonctionnement. |
| 25 juin 2020 | [Création d’un processus d’examen dans AEM Forms](https://video.tv.adobe.com/v/35821/quality=9?captions=fre_fr) | Vidéo | Découvrez comment créer un processus pour examiner les données envoyées à partir d’un formulaire actif. |
| 23 juin 2020 | [Profils de traitement](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/processing-profiles.html) | Vidéo | Les profils de traitement définissent les rendus à créer pour les ressources dans AEM as a Cloud Service. |
| 23 juin 2020 | [Bonnes pratiques de Dynamic Media Classic](https://docs.adobe.com/content/help/en/experience-manager-learn/dynamic-media-classic-tutorial/overview.html) | Article | Les utilisateurs actuels et les nouveaux utilisateurs peuvent en savoir plus sur Dynamic Media Classic, ses principales capacités et le processus de _création_, d’_auteur_ et de _diffusion_. |
| 23 juin 2020 | [Débogage de la version et des déploiements d’AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/build-and-deployment.html) | Article | Découvrez comment déboguer la version et les déploiements d’AEM as a Cloud Service. |
| 16 juin 2020 | [Débogage d’AEM as a Cloud Service à l’aide de journaux](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/logs.html) | Article | Découvrez comment utiliser les journaux pour déboguer AEM as a Cloud Service. Les journaux se trouvent en première ligne du débogage des applications AEM, mais dépendent d’une journalisation adéquate dans l’application AEM déployée. |
| 10 juin 2020 | [Utilisation de Dynamic Media 3D avec AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/dynamic-media/dynamic-media-3d-feature-video.html) | Vidéo | La prise en charge d’Adobe Experience Manager par Dynamic Media 3D vous permet de personnaliser et de diffuser facilement des expériences interactives optimisées en 3D à grande échelle. |
| 5 juin 2020 | [Projet de l’éditeur d’application d’une seule page](https://docs.adobe.com/content/help/en/experience-manager-learn/spa-react-tutorial/create-project.html) | Article | Découvrez comment utiliser l’archétype du projet Adobe Experience Manager (AEM) pour générer un projet Maven à plusieurs modules comme point de départ pour une application React intégrée à l’éditeur d’application d’une seule page AEM. |
| 3 juin 2020 | [Tutoriel de gestion des envois de formulaires HTML5](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/html5-forms/handle-mobile-form-submission.html) | Article | Découvrez comment accéder aux données envoyées dans le gestionnaire d’envoi personnalisé. |

### Informations de mise à jour d’Experience Manager

Toutes les notes de mise à jour d’Experience Manager sont conservées dans les pages suivantes :

* [Informations de mise à jour d’AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/release-notes/home.html)
* [Notes de mise à jour d’AEM Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Notes de mise à jour du service de conversion automatisée de formulaires](https://docs.adobe.com/content/help/fr-FR/aem-forms-automated-conversion-service/using/release-notes.html)
* [Notes de mise à jour d’AEM 6.5 Service Pack](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/release-notes/service-pack/sp-release-notes.html).
* [Notes de mise à jour d’AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/fr-FR/experience-manager-64/release-notes/cfp-release-notes.html)
* [Notes de mise à jour de Dynamic Media AEM Assets](https://docs.adobe.com/content/help/fr-FR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notes de mise à jour d’AEM Brand Portal](https://docs.adobe.com/content/help/fr-FR/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Notes de mise à jour de l’application de bureau AEM](https://docs.adobe.com/content/help/fr-FR/experience-manager-desktop-app/using/release-notes.html)
* [Notes de mise à jour d’AEM Dispatcher](https://docs.adobe.com/content/help/fr-FR/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Notes de mise à jour d’Adobe Primetime](https://docs.adobe.com/content/help/fr-FR/primetime/release-notes/home.translate.html)
* [Notes de mise à jour de Livefyre](https://docs.adobe.com/content/help/fr-FR/livefyre/using/release-notes/c-rn.html)

### Ressources d’aide supplémentaires pour AEM

* [Guides d’utilisation d’AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/landing/home.html)
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

* Nouvelle version stable Gold Standard. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

#### Panneau de contrôle de Campaign

* Audit de la délivrabilité des sous-domaines. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)

* Gestion des clés GPG. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/control-panel/using/instances-settings/gpg-keys-management.html)

### Nouveaux cours et tutoriels sur Campaign

Nouveaux tutoriels, vidéos ou cours publiés le mois dernier.

| Publication | Nom | Solution | Description |
| ----------- | ----------- | ---------- | ---------- |  
| 26 juin 2020 | [Explorer l’interface utilisateur d’Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/exploring-the-adobe-campaign-classic-user-interface.html) | Campaign Classic | Cette vidéo décrit l’interface utilisateur principale d’Adobe Campaign Classic et vous explique comment accéder à la fonctionnalité principale. |
| 8 juillet 2020 | [Installation et configuration du client Adobe Campaign](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/install-and-setup-the-adobe-campaign-client.html) | Campaign Classic | Apprenez à télécharger et installer la console du client Adobe Campaign, à créer et gérer vos connexions à plusieurs environnements et à vérifier l’accès à la console du client Adobe Campaign. |
| 19 juin 2020 | [Présentation d’Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/introduction-to-adobe-campaign-classic.html) | Campaign Classic | Découvrez la place d’Adobe Campaign Classic dans le portefeuille d’Adobe Digital Experience, ainsi que les principales fonctionnalités et capacités. |
| 12 juin 2020 | [Déploiement d’un modèle de diffusion de courrier électronique ad hoc](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/deploying-ad-hoc-email-delivery-template.html) | Campaign Classic | Découvrez comment déployer un modèle de courrier électronique ad hoc. |
| 12 juin 2020 | [Configuration d’un modèle de diffusion](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/configuring-a-delivery-template.html) | Campaign Classic | Découvrez comment configurer un modèle de courrier électronique. |
| 12 juin 2020 | [Définition des propriétés du modèle de diffusion](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/setting-delivery-template-properties.html) | Campaign Classic | Découvrez comment définir les propriétés du modèle de courrier électronique. |
| 12 juin 2020 | [Gestion des clés GPG](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management-overview.html) | Campaign Classic/Panneau de contrôle | Découvrez comment générer et installer une paire de clés GPG publique/privée pour le chiffrement des données et comment importer et installer une clé publique pour le déchiffrement des données. |
| 26 juin 2020 | [Prise en main de l’interface utilisateur dans Adobe Campaign Standard](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/getting-started/getting-started-with-the-ui.html) | Campaign Standard | Cette vidéo présente l’interface utilisateur d’Adobe Campaign Standard et explique comment accéder aux fonctionnalités clés et de base. |
| 26 juin 2020 | [Gestion des clés GPG](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/gpg-key-management-overview.html) | Campaign Standard/Panneau de contrôle | Découvrez comment générer et installer une paire de clés GPG publique/privée pour le chiffrement des données et comment importer et installer une clé publique pour le déchiffrement des données. |

### Ressources d’aide

* Adobe Campaign Standard : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/campaign-standard-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/overview.html) - [Calendrier des versions](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-planning.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/campaign-classic-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/documentation-updates.html)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/control-panel/using/release-notes.html) - Tutoriels vidéo pour [Campaign Standard](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icône](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notes de mise à jour d’Adobe Advertising Cloud.

### Nouvelles fonctionnalités dans [!UICONTROL Advertising Cloud Search] {#adcloud-search}

Mises à jour le **8 juillet 2020** pour la publication du 11 juillet.

| Fonctionnalité | Description |
| -----------| ---------- |
| [!UICONTROL Alertes bêta] | Vous pouvez maintenant ouvrir une vue en lecture seule et filtrée contenant les données de n’importe quelle alerte, puis ouvrir une vue filtrée des entités dans la vue de gestion de campagne concernée, à partir de laquelle vous pouvez modifier les enregistrements d’entité. |
| [!UICONTROL Portfolios] | La dépréciation des mesures basées sur la position dans les contraintes et les paramètres de portfolio a été reportée au 8 août. |

## ![Icône](/assets/magento.png) [!DNL Magento] {#magento}

Pour les notes de mise à jour de Magento, veuillez consulter :

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icône](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] est une application complète pour la gestion des pistes et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en s’engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Voir les [notes de mise à jour](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) [!DNL Marketo] pour consulter les informations les plus récentes.

### Fonctionnalités à venir

Les fonctionnalités suivantes seront publiées tout au long du trimestre :

| Fonctionnalité | Description |
|------|---------|
| [!DNL Bizible] | <ul><li>Nouvelle segmentation basée sur un compte</li><li>Enregistrement des filtres spécifiques au tableau de bord</li><li>Exportation de tableaux de bord Bizible au format PDF</li></ul> |
| Connect de ventes | Composition des mises à jour/améliorations de Windows et du Centre de commandes |

### Annonces

**Centre de succès Marketo Engage :** lancement en février 2020. Le centre de succès est un centre d’aide intégré qui vous permet à vous et à la communauté de rechercher des documents produit, de lancer des guides pratiques, d’accéder au contenu d’adoption, etc. Remarque : cette fonctionnalité sera lancée en version bêta en ANZ et sera déployée en Amérique du Nord plus tard dans le trimestre.

### Dépréciations

* **Paramètre de l’API de ressource &quot;_method&quot; :** après septembre 2020, les points de fin d’API d’actif n’accepteront plus `_method` pour transmettre les paramètres de requête dans un corps POST afin de contourner les limitations de longueur d’URI.
* **Dépréciation de la prise en charge d’Internet Explorer :** à compter de la version du 31 juillet 2020, l’interface utilisateur de Marketo Engage ne sera plus prise en charge dans Internet Explorer.

Pour obtenir des notes de mise à jour cumulatives et historiques, reportez-vous à la page [Notes de mise à jour de Marketo](https://docs.marketo.com/x/CgA6Ag).

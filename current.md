---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: dd357da4e362c01ab350891b1082020c90eb77fe
workflow-type: tm+mt
source-wordcount: '6522'
ht-degree: 36%

---


# Accès anticipé - Notes de mise à jour de Adobe Experience Cloud - juin 2020

![Bannière](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. Il met également en évidence la documentation, les cours de formation et les didacticiels vidéo qui vous aideront à tirer le meilleur parti d’Experience Cloud.

>[!IMPORTANT]
>
>Cette page contient une version anticipée du contenu et peut être modifiée avant la version définitive qui sera publiée.

>[!NOTE]
>
>Inscrivez-vous aux [Mises à jour produit prioritaires d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) afin de recevoir une notification par courrier électronique concernant les prochaines mises à jour.

**Date de publication : 18 juin 2020**

Les dates de publication des produits peuvent varier. Consultez fréquemment les mises à jour.

Dernière mise à jour : **12 juin 2020**

* [Statut du système Adobe](#status)
* [Interface d’Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Orchestration du parcours](#journey-orch)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/fr/primetime/user-guide.html) (liens vers la page d’aide de Primetime)

Besoin d’aide ? Visitez [Adobe Experience League](https://experienceleague.adobe.com/#home) pour trouver de la documentation sur les produits et les techniques, des cours organisés par Adobe, des didacticiels vidéo, des réponses rapides, des informations sur la communauté et une formation dirigée par un instructeur.

## ![Icône](/assets/adobe.png) Statut du système Adobe {#status}

[!UICONTROL Statut du système Adobe] fournit des informations détaillées, des mises à jour de statut et des notifications par email relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

Publié : **21 mai 2020**

**Nouveautés**

* Avec votre Adobe ID, vous pouvez vous abonner à des notifications d’événement avec plus de granularité et associées au niveau de l’offre de produit et des modules complémentaires. Pour vous aider à configurer votre abonnement plus rapidement, le processus d’auto-abonnement recommande désormais une sélection de produits et d’offres en fonction de vos droits sur les produits. Cela devrait réduire le nombre d’emails que vous recevez et fournir des notifications plus pertinentes dans votre boîte de réception. Rendez-vous sur [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nouvelles fonctionnalités et améliorations disponibles dès maintenant**

| Fonction | Description |
| -----------| ---------- |
| Amélioration de l’expérience utilisateur pour les abonnements et les notifications | <ul><li>Les emplacements régionaux [!DNL Marketo Engage] sont désormais filtrés en fonction de la liste des offres de produits sélectionnées.</li><li>Les notifications par email [!DNL Marketo Engage] sont pertinentes pour la région, l’emplacement et les préférences d’environnement de l’utilisateur.</li></ul> |
| Confirmation d’abonnement à l’événement | <ul><li>Vous pouvez désormais obtenir une confirmation par email lorsque vous vous abonnez à des mises à jour d’événement unique en cours.</li></ul> |
| Améliorations de la convivialité de la navigation globale | <ul><li>Expérience de l’utilisateur cohérente avec `Adobe.com` dans le menu de navigation de niveau supérieur.</li></ul> |

## ![Icône](/assets/ec_appicon_24.png) Interface d’Experience Cloud {#ecloud}

Mises à jour générales de l’interface d’Experience Cloud.

**Domaine de produit unifié**

Adobe a mis à jour l’en-tête de domaine et d’interface afin d’unifier et d’améliorer votre expérience dans toutes les applications Experience Cloud. Ces améliorations sont conçues pour fluidifier votre utilisation de manière simple, mais importante. Ces améliorations ne modifient pas vos processus actuels.

Les mises à jour comprennent les éléments suivants :

* Nouvelles URL d’application : `experience.adobe.com/<application name>` :
   * À terme, tous les produits adopteront ce modèle d’URL. Recherchez de nouvelles URL pour qu’elles prennent effet tout au long du mois.
   * Navigateurs pris en charge : [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] et [!DNL Opera] (versions les plus récentes). **Remarque :** Bien que l’interface d’Experience Cloud prenne en charge ces navigateurs, il est possible que les applications individuelles ne prennent pas en charge chaque navigateur. (Par exemple, [Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/admin/sys-reqs.html) ne prend pas en charge [!DNL Opera] et [Target](https://docs.adobe.com/help/fr-FR/target/using/implement-target/before-implement/supported-browsers.html) ne prend pas en charge [!DNL Safari].)
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
| Admin Tool (Outil d’administration) (bêta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Panorama et collections]**, un filtre hérité dans le sélecteur de [!UICONTROL ressources Experience Cloud], est en cours de désactivation.

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.

Date de publication : **10 juin 2020**

[!DNL Adobe Experience Platform] comprend les nouvelles fonctionnalités suivantes :

* **Espace de travail des sciences de données :** Le [!DNL JupyterLab Launcher] logiciel inclut désormais un [!DNL Python] ordinateur portable pour l&#39;apprentissage automatique en temps réel (Alpha).
* **Segmentation :** Un champ de date Anniversaire pour les fonctions de date a été ajouté, ce qui permet aux utilisateurs d’évaluer les dates sans année.
* **Sources :** Nouveaux connecteurs source pour [!DNL Apache HDFS] et [!DNL Couchbase].

Pour plus d’informations sur ces fonctionnalités, voir Notes [de mise à jour de la plateforme](https://docs.adobe.com/content/help/fr-FR/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)d’expérience.

### Informations supplémentaires sur la mise à jour d’Experience Platform

* [Notes de mise à jour d’Experience Platform Launch](https://docs.adobe.com/content/help/fr-FR/launch/using/intro/release-notes/current.html)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/fr/security.html) (Tous les produits Adobe)

### Nouveaux cours et didacticiels de la plateforme d’expérience {#tutorials-plat}

| Contenu | Type de contenu | Description |
| -----------| ---------- | ---------- |
| [Présentation d’Adobe Experience Platform](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | Cours | Découvrez comment Adobe Experience Platform vous aide à offrir une expérience adaptée en transformant vos données en profils clients en temps réel robustes et en informations basées sur l’IA que vous pouvez activer dans chaque canal. Ce cours d’introduction vous donne un aperçu des fonctionnalités de la plateforme d’expérience, des cas d’utilisation, des relations avec Adobe Experience Cloud, de l’architecture de base, de l’interface et des rôles de projet. |
| [Présentation du SDK Web et du réseau Edge](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | Didacticiel vidéo | Présentation d’Adobe Experience Platform SDK et d’Edge Network. Experience Platform Web SDK est une bibliothèque JavaScript côté client qui permet aux clients d’utiliser une seule bibliothèque JavaScript, un seul type de balise, un seul flux de données, une seule et même destination côté serveur pour envoyer des données à toutes les applications Adobe et à des destinations tierces. |
| [Démo du SDK Web et du réseau Edge](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | Didacticiel vidéo | Regardez le SDK Web d’Adobe Experience Platform et Edge Network en action, avec un seul appel à Adobe pour envoyer des données à Experience Platform, Analytics, Audience Manager et Cible. |
| [Démonstration de la plateforme de données client en temps réel](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | Didacticiel vidéo | Découvrez comment le CDP en temps réel est utilisé pour collecter des données provenant de plusieurs sources. Vous pouvez fusionner ces données dans un profil client en temps réel unique et activer ces données pour créer des expériences client personnalisées. |

## ![Icône](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Grâce à Adobe Experience Platform, orchestrez des parcours clients individuels à l’échelle sur des canaux d’expérience en anticipant de manière intelligente les besoins de chaque individu en temps réel, quel que soit l’endroit où leur parcours les mène.

### Dernière version

La version du 2e trimestre a été publiée. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html)

### Nouveaux cours et didacticiels sur l&#39;orchestration du voyage {#jo-tutorials}

| Contenu | Type de contenu | Description |
| -----------| ---------- | ---------- |
| [Prise en main de l’orchestration du parcours pour les administrateurs](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | Cours | Découvrez comment configurer et utiliser l&#39;orchestration de parcours. Ce cours couvre les concepts clés et les étapes de configuration nécessaires pour permettre l&#39;orchestration d&#39;un voyage. Apprenez à créer, publier et comment signaler et analyser vos voyages orchestrés. |
| [Prise en main de Journey Orchestration pour les utilisateurs professionnels](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | Cours | Découvrez comment configurer et utiliser l&#39;orchestration de parcours. Ce cours porte sur les concepts clés. Vous apprendrez à créer, publier, créer des rapports et analyser vos voyages orchestrés. |

### Ressources supplémentaires pour l’orchestration du parcours

[Documentation](https://docs.adobe.com/content/help/fr-FR/journeys/using/journey-orchestration-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html) - [Tutoriels vidéos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Icône](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Updated **June 10, 2020**

* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features)
* [Nouvelles fonctionnalités dans Customer Journey Analytics](#cust-journey)
* [Nouvelles fonctionnalités de Media Analytics](#media-aa)
* [Correctifs dans Adobe Analytics](#aa-fixes)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [Nouveaux cours et didacticiels Adobe Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

| Fonction | [Disponibilité](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.translate.html)générale - Date de Cible | Description |
| -----------| ---------- |-------|
| QI de l’attribution : [!UICONTROL Attribution algorithmique] | 18 juin 2020 | Le modèle d’attribution  algorithmique d’ [!UICONTROL Analysis Workspace] utilise des techniques statistiques pour déterminer de manière dynamique l’allocation optimale du crédit pour la mesure sélectionnée. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| QI de l’attribution : Fenêtres de recherche personnalisées | 18 juin 2020 | Vous pouvez désormais configurer n’importe quel modèle d’attribution dans le QI  d’attribution pour inclure des points de contact de 90 jours avant la période de rapports. Cela permet généralement d’accroître la précision d’attribution pour les événements qui surviennent au début de la période du rapports en tenant compte des interactions qui se sont produites au cours du ou des mois précédents. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Rôles de projet pour les projets [!UICONTROL Workspace] partagés | 18 juin 2020 | Lors du partage d’un projet [!UICONTROL Workspace] , vous pouvez désormais placer des destinataires dans l’un des trois rôles de projet, en fonction de l’expérience de projet que vous souhaitez qu’ils possèdent : Edition, Duplicata et Vue. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Projets [!UICONTROL Workspace] à Vue seule | 18 juin 2020 | [!UICONTROL Les projets Workspace] peuvent être partagés avec les utilisateurs, car la Vue __Can est la seule. Lorsqu’un destinataire de Vue ouvre le projet partagé, il bénéficie d’une expérience de projet plus restrictive, sans rail gauche et avec des interactions limitées.[En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Possibilité de co-modifier des projets [!UICONTROL Workspace] | 18 juin 2020 | Les Destinataires ajoutés au rôle _[!UICONTROL Possibilité de modification]_peuvent enregistrer sur un projet qui leur a été partagé. Cela s’applique aussi bien aux administrateurs qu’aux non-administrateurs.[En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Panneau vierge mis à jour dans [!UICONTROL Workspace] | 18 juin 2020 | Le panneau vierge de [!UICONTROL Workspace] comprend désormais des panneaux et des visualisations, ce qui vous permet de choisir plus facilement le processus d’analyse le plus performant pour vous. |
| Domaines propriétaires disponibles dans la collecte de données régionale pour la Chine | 18 juin 2020 | Permet aux clients disposant d’un `.cn` domaine de demander un domaine propriétaire à utiliser à l’intérieur de la Chine continentale. (Documentation disponible avec l’achat du SKU d’optimisation des performances de la Chine.) |
| Panneau Aperçu rapide dans [!UICONTROL Workspace] | 25 juin 2020 | Quick Insights fournit des conseils aux non-analystes et aux nouveaux utilisateurs d’ [!UICONTROL Analysis Workspace] pour savoir comment répondre rapidement et facilement aux questions de l’entreprise. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| [!UICONTROL Panneau Analyses pour la Cible] dans [!UICONTROL Workspace] | 25 juin 2020 | Le panneau [!UICONTROL Analytics pour la Cible] (A4T) vous permet d’analyser vos activités et expériences Adobe Target dans [!UICONTROL Analysis Workspace]. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Nouvelles fonctionnalités dans Customer Journey Analytics {#cust-journey}

| Fonction | [Disponibilité](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.translate.html)générale - Date de Cible | Description |
| -----------| ---------- |-----|
| QI de l’attribution : [!UICONTROL Attribution algorithmique] | 18 juin 2020 | Le modèle d’attribution  algorithmique d’ [!UICONTROL Analysis Workspace] utilise des techniques statistiques pour déterminer de manière dynamique l’allocation optimale du crédit pour la mesure sélectionnée. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| QI de l’attribution : Fenêtres de recherche personnalisées | 18 juin 2020 | Vous pouvez désormais configurer n’importe quel modèle d’attribution dans le QI  d’attribution pour inclure des points de contact de 90 jours avant la période de rapports. Cela permet généralement d’accroître la précision d’attribution pour les événements qui surviennent au début de la période du rapports en tenant compte des interactions qui se sont produites au cours du ou des mois précédents. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Prise en charge de la détection des [!UICONTROL anomalies] | 18 juin 2020 | [!UICONTROL La détection] des anomalies fournit une méthode statistique pour déterminer comment une mesure donnée a changé par rapport aux données précédentes. [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Rôles de projet pour les projets [!UICONTROL Workspace] partagés | 18 juin 2020 | Lors du partage d’un projet [!UICONTROL Workspace] , vous pouvez désormais placer des destinataires dans l’un des trois rôles de projet, en fonction de l’expérience de projet que vous souhaitez qu’ils possèdent : Edition, Duplicata et Vue. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Projets [!UICONTROL Workspace] à Vue seule | 18 juin 2020 | [!UICONTROL Les projets Workspace] peuvent être partagés avec les utilisateurs, car la Vue __Can est la seule. Lorsqu’un destinataire de Vue ouvre le projet partagé, il bénéficie d’une expérience de projet plus restrictive, sans rail gauche et avec des interactions limitées.[En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Possibilité de co-modifier des projets [!UICONTROL Workspace] | 18 juin 2020 | Les Destinataires ajoutés au rôle _[!UICONTROL Possibilité de modification]_peuvent enregistrer sur un projet qui leur a été partagé.[En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Panneau Aperçu rapide dans [!UICONTROL Workspace] | 25 juin 2020 | Quick Insights fournit des conseils aux non-analystes et aux nouveaux utilisateurs d’ [!UICONTROL Analysis Workspace] pour savoir comment répondre rapidement et facilement aux questions de l’entreprise. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |

### Nouvelles fonctionnalités de [!UICONTROL Media Analytics] {#media-aa}

Date de mise à jour : **29 mai 2020**

**Suivi de l’état du lecteur :** les clients [!UICONTROL Media Analytics] peuvent capturer l’interaction de la visionneuse au cours de la lecture à l’aide d’un jeu standard de variables de solution pour le mode Plein écran, le sous-titrage, le mode silencieux, l’incrustation dans l’image et le mode In-Focus. Vous pouvez également créer des états de lecteur personnalisés. Des comptes rendus des performances sur les variables de suivi de l’état du lecteur sont désormais disponibles dans [!UICONTROL Analysis Workspace]. Cette fonctionnalité nécessite l’une des configurations suivantes :

* SDK Media [!DNL JavaScript] 3.0 ou version ultérieure
* Utilisation avec le SDK [!DNL Adobe Experience Platform] (AEP) :
   * [!UICONTROL Extension Media Analytics] (pour le Web) : [!UICONTROL Adobe Media Analytics] (SDK 3.x) pour Audio et Video v1.0 ou version ultérieure
   * [!UICONTROL Extension Media Analytics] (pour mobile) : [!UICONTROL Adobe Media Analytics pour Audio] et Vidéo v2.0 ou version ultérieure
* [!UICONTROL Collection Médias]

Voir [À propos du suivi de l’état du lecteur](https://docs.adobe.com/content/help/fr-FR/media-analytics/using/player-state-tracking/player-state-overview.html).

### Correctifs dans Adobe Analytics {#aa-fixes}

* Correction d’un problème en raison duquel les segments avec des recherches sur plusieurs octets pour certaines suites de rapports ne correspondaient à rien. Ils correspondent désormais aux chaînes correctes. (AN-220043)
* Correction d’un problème en raison duquel le filtre  d’éléments dans les [!UICONTROL rapports et analyses] ne fonctionnait pas. (AN-206132)
* Correction du temps de réponse lent dans l’interface Projets  planifiés. (AN-214837)
* Correction d’un problème en raison duquel l’API de Rapports Analytics 2.0 renvoyait une erreur de plage de dates. (AN-215087)
* Fixed a case in which the instance/visit/visitor wasn&#39;t being counted in the denominator for the [!UICONTROL Time Spent] metrics. Cela se produit lorsqu’un accès sans valeur pour la dimension (par exemple, Nom de page) suit la même seconde. (AN-211074)
* Correction d’un problème en raison duquel les utilisateurs ne pouvaient pas accéder aux projets [!UICONTROL Workspace] partagés avec eux. (AN-217561)
* Correction d’un problème en raison duquel les clés n’étaient pas classées par Créateur [!UICONTROL de règles de]classification. (AN-221538)
* Correction d’un problème en raison duquel l’utilisation [!UICONTROL des appels] serveur ne rapports aucune donnée d’utilisation. (AN-210452)
* Correction de problèmes en raison desquels les données manquaient dans Audience Manager pour les segments Adobe Analytics publiés. (AN-220208, AN-220659)
* Correction d’un problème en raison duquel les rapports affichaient des données mais des journaux de flux  de données disaient &quot;Aucune donnée d’entrepôt de données&quot;. (AN-220784, AN-220858)
* Correction de problèmes qui empêchaient le lancement des analyses  ad hoc à partir du `experiencecloud.com` domaine. (AN-219680, AN-221629)
* Correction de problèmes liés à l&#39;utilisation de la touche d&#39;accès rapide &quot;Ctrl (ou Commande) + C&quot;. (AN-221101, AN-221537)
* Correction d’un problème de la page d’activation de Carte [!UICONTROL d’] activités. (AN-222029, AN-221242)
* Correction d’un problème en raison duquel il n’était pas possible d’ajouter un point de contact au milieu d’une visualisation [!UICONTROL Abandon] . (AN-221648)

#### Correctifs Adobe Analytics supplémentaires

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788 ; AN-220866 ; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000 ; AN-222505 ; AN-222559

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Migration vers un domaine de produit unifié | Date d’entrée en vigueur : 28 mai 2020 | La migration vers un domaine de produit unifié pour Adobe Analytics, débutée en janvier 2020, s’est terminée le 28 mai 2020. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist (formerly, allowlist) `omniture.com` as a third-party cookie. Une fois la migration complète de l&#39;architecture terminée (bientôt), nous vous en informerons par le biais des notes de mise à jour et cette étape d&#39;autorisation ne sera plus nécessaire. [Voici](https://helpx.adobe.com/fr/analytics/kb/adobe-ip-addresses.html) une liste complète des adresses et domaines IP recommandés que vous devez autoriser.<br>Si votre entreprise bloque les cookies tiers, contactez l’assistance clientèle pour récupérer l’accès à votre compte Adobe Analytics. |
| Nouvelle page d’entrée par défaut d’Adobe Analytics | Date d’entrée en vigueur : 18 juin 2020 | Le 18 juin 2020, la page d’entrée par défaut d’Adobe Analytics passera de [!UICONTROL Rapports] à [!UICONTROL Workspace]. Cette modification se produira pour tous les utilisateurs n’ayant pas défini de page d’entrée personnalisée auparavant. |
| Liste des technologies tierces autorisées | 12 mars 2020 (date de mise en vigueur) | Adobe Analytics a commencé à utiliser des technologies tierces pour la gestion du déploiement de fonctionnalités et la prise en charge intégrée. Les URL suivantes doivent être ajoutées à toutes les listes de pare-feu réseau nécessaires pour garantir un accès complet aux fonctionnalités :<ul><li>Gainsight : https://esp.aptrinsic.com</li><li>LaunchDarkly : https://app.launchdarkly.com</li></ul> |
| Improved redundancy for [!UICONTROL Analysis Workspace] availability | 21 mai 2020 | In order to ensure availability of [!UICONTROL Analysis Workspace], we are adding a secondary CDN (Content Delivery Network) for improved redundancy. Les URL suivantes doivent être ajoutées à toute liste d&#39;autorisations de pare-feu réseau nécessaire :<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Modification du mode de calcul des [!UICONTROL entrées/sorties] dans [!UICONTROL Workspace] | 7 avril 2020 | Dans [!UICONTROL Analysis Workspace], depuis mars 2020, nous avons modifié la manière dont la valeur _Aucun_ interagit avec les [!UICONTROL entrées/sorties]. Comme vous pouvez désormais activer et désactiver l’option _Aucun_ dans [!UICONTROL Analysis Workspace], nous appliquons l’option _Aucun_ après l’entrée ou la sortie, alors que (pour les eVars) elle était appliquée avant l’entrée ou la sortie. Supposons, par exemple, que le premier accès d’une visite n’ait aucune valeur pour eVars, contrairement au second accès. Dans [!UICONTROL Reports &amp; Analytics], le premier accès s’affichera comme _Non spécifié_ pour l’entrée, mais dans [!UICONTROL Analysis Workspace], il affichera la valeur pour le second accès. |
| Abandon de l’**[!UICONTROL archive de tableau de bord]** | 27 mars 2020 | Le paramètre **[!UICONTROL Afficher l’archive]** sous **[!UICONTROL Gérer les tableaux de bord]** dans [!UICONTROL Reports &amp; Analytics] ne sera plus disponible à compter du mois d’octobre 2020. |
| Fin de vie : API héritées d’Analytics | 9 janvier 2020 | En novembre 2020, les services d’API hérités d’Analytics suivants arriveront en fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner. <ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Nous avons mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | Pour les clients basés à Londres et à Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fin de vie d’Ad Hoc Analysis | 6 août 2018 | Adobe a annoncé la prochaine fin de vie d’Ad Hoc Analysis. La date de fin de vie sera communiquée dès que possible. Pour obtenir de plus amples informations, voir le site [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### Nouveaux cours et didacticiels Analytics {#tutorials-analytics}

Nouveaux cours, vidéos de didacticiels et articles dans Analytics et les analyses de parcours client.

| Contenu | Type de contenu | Description |
| -----------| ---------- | ---------- | 
| [Prise en main des analyses de parcours client pour les utilisateurs](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | Cours | Dans ce cours, vous apprendrez à utiliser la fonction d’analyse du parcours client (CJA) pour analyser les données provenant de nombreuses sources de données différentes. Vous découvrirez les différences entre Adobe Analytics et Customer Journey Analytics, ainsi que la manière dont les données sont traitées dans la CJA. Après avoir suivi ce cours, vous devriez être en mesure de créer et de personnaliser des visualisations sur plusieurs canaux pour mieux comprendre vos clients. |
| [Prise en main des analyses de parcours client pour les administrateurs](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Cours | Découvrez comment configurer et utiliser [!UICONTROL Journey Orchestration]. Ce cours couvre les concepts clés et les étapes de configuration nécessaires pour permettre l&#39;orchestration d&#39;un voyage. Vous apprendrez comment créer, publier et comment rapporter et analyser vos trajets orchestrés. |
| [Prise en main des analyses de parcours client pour les ingénieurs de données](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | Cours | Ce cours vous permettra d’en savoir plus sur les données qui entrent dans l’analyse du parcours du client et sur l’impact de ces données sur les rapports de l’analyste. Ce cours s’appuie sur vos connaissances générales d’Adobe Experience Platform. |
| [Prise en main des analyses de parcours client pour les administrateurs](https://video.tv.adobe.com/v/34349?captions=fre_fr) | Didacticiel vidéo | Une vidéo d’introduction à Customer Journey Analytics for Administrators. |
| [Mise en oeuvre d’Analytics guidée](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | Cours | Dans ce cours, vous apprendrez à commencer à mettre en oeuvre Adobe Analytics, à comprendre les concepts d’Analytics, à créer un plan et à mettre en oeuvre Adobe Analytics à l’aide du lancement de la plate-forme d’expérience. |
| [Principes fondamentaux d’Adobe Analytics pour les dirigeants](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | Cours | Dans ce cours, découvrez les fondamentaux d’Analytics et comment Analysis Workspace peut modifier votre activité. Découvrez comment découvrir des informations avec Adobe Sensei, écouter les témoignages des clients et regarder les faits saillants du sommet 2019 de l&#39;industrie. |
| [Prise en main d’Analysis Workspace](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | Cours | Découvrez comment commencer à utiliser Analysis Workspace. Créez votre premier projet, découvrez comment définir des plages de dates, appliquer des segments et partager et collaborer sur des projets. |
| [Générateur de cartes de performance Adobe Analytics tableaux de bord](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | Didacticiel vidéo | Dans cette vidéo, découvrez comment créer et partager des [!UICONTROL cartes de performance] dans [!UICONTROL Analysis Workspace] à afficher sur les tableaux de bord Adobe Analytics (application mobile). |
| [Expérience in-app des tableaux de bord Analytics Adobe](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | Didacticiel vidéo | Dans cette vidéo, découvrez comment utiliser les tableaux de bord Adobe Analytics (application mobile) pour accéder aux cartes [!UICONTROL de performance] de vue créées par vous ou partagées avec vous. |

#### Ressources d’aide à propos d’Analytics

* [Tutoriels Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentation produit Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/landing/home.html)

## ![Icône](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nouveaux correctifs, fonctionnalités, documentation et tutoriels dans Audience Manager.

Updated **June 10, 2020**

### Mises à jour de l’interface utilisateur

Audience Manager publie des mises à jour sur la barre de domaine et d’en-tête afin d’améliorer votre expérience et de réaliser l’union avec d’autres applications Experience Cloud.

* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide à l’utilisateur, y compris les articles présentés et les vidéos contextuelles dans le menu Aide.
* Capacité à fournir des commentaires sur la plateforme d’expérience et les tickets d’assistance aux fichiers.
* Nouveau modèle d’URL plus simple. Mettez à jour vos signets vers la nouvelle URL : `experience.adobe.com/audience-manager`.

Ces mises à jour ne sont disponibles que pour les utilisateurs qui se connectent à l’aide d’un Adobe ID. Pour vous connecter à un Adobe ID, voir [Gestion des utilisateurs et des produits Experience Cloud](https://docs.adobe.com/content/help/fr-FR/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Nouvelles fonctionnalités et correctifs dans Adobe Audience Manager

| Fonction | Description |
| -----------| ---------- |  
| [Module Audience Manager pour IAB TCF v2.0 ](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.translate.html) | En maintenant l’accent mis par Adobe sur la confidentialité par conception, nous mettons à niveau le module externe Audience Manager pour IAB TCF vers la version 2.0 de l’IAB Transparency &amp; Consent Framework (TCF), à compter du 10 juin 2020. Les clients qui ont mis en oeuvre le module externe Audience Manager pour IAB TCF doivent effectuer la mise à niveau vers la version 2.0 d’ici le 15 août 2020, afin de continuer à utiliser cette fonctionnalité. Après le 15 août 2020, la version 1.1 sera abandonnée et ne sera plus prise en charge. |

**Correctifs**

* Mise à jour des Conditions générales  d’Audience Marketplace afin de refléter les exigences légales dans des zones géographiques spécifiques. (AAM-54518)
* Correction d’un problème en raison duquel l’accès à la page [!UICONTROL Caractéristiques] à partir des signets générait une erreur 404. (AAM-54768)
* Correction d’un problème en raison duquel l’API de mise à jour de destination expirait lors de la récupération des modèles algorithmiques. (AAM-54342)
* Les utilisateurs peuvent désormais voir un indicateur de précision de la classification de modèle pour les personnes intelligentes. (AAM-54847)
* Correction d’un problème en raison duquel l’activation de la touche Entrée après l’ajout d’une expression de caractéristiques supprimait l’expression au lieu de l’enregistrer. (AAM-54210)
* Correction d’un problème en raison duquel les appels à la méthode GET de l’API [!UICONTROL Traits] échouaient pour les utilisateurs qui n’avaient pas l’autorisation VUE_MODELS. (AAM-53104)
* Correction d’un problème en raison duquel les utilisateurs ne pouvaient pas supprimer les modèles  algorithmiques qui contenaient des caractéristiques [!UICONTROL de]dossier. (AAM-50192)
* Les expressions à longue caractéristique s’enroulent désormais sur plusieurs lignes. (AAM-54972)
* Correction d’un problème en raison duquel les utilisateurs disposant d’autorisations en lecture seule pouvaient voir le bouton [!UICONTROL Créer nouveau] dans les pages des modèles algorithmiques. (AAM-54889)
* Correction d’un problème en raison duquel l’indicateur de chargement des rapports [!UICONTROL Général] et [!UICONTROL Tendance] continuait à tourner une fois le téléchargement CSV terminé. (AAM-54571)
* Correction d’un problème en raison duquel les utilisateurs ne pouvaient pas ajouter de caractéristiques en bloc aux segments dans le créateur [!UICONTROL de]segments. (AAM-55033)
* Plusieurs améliorations de l’accessibilité de l’interface. (AAM-47269, AAM-48966, AAM-48976, AAM-49369, AAM-49023, AAM-49042).

### Nouveaux cours et didacticiels d’Audience Manager {#tutorials-aam}

| Contenu | Type de contenu | Description |
| -----------| ---------- | ---------- |  
| [Présentation d’Audience Manager](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | Cours | Ce cours vous apprend les bases d’Audience Manager et les problèmes que vous pouvez résoudre en l’utilisant. Découvrez les cas d’utilisation courants et les termes et concepts clés d’Audience Manager. |
| [Présentation de l’identité dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | Didacticiel vidéo | Découvrez comment Adobe Audience Manager gère l’identité, notamment la fusion de profils et de profils internes, ainsi que la synchronisation d’identifiants avec les partenaires. |
| [Présentation et configuration de la destination basée sur les personnes LinkedIn](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | Cours | Cette vidéo vous guide tout au long des concepts et étapes de création d’une destination basée sur les personnes vers LinkedIn. Il s’appuie sur les vidéos et la documentation supplémentaires concernant les destinations basées sur les personnes. |
| [Création de caractéristiques basées sur des règles](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | Didacticiel vidéo | Découvrez comment utiliser le créateur [!UICONTROL de] caractéristiques dans l’interface d’Audience Manager pour créer une caractéristique basée sur des règles, ce qui vous permet de capturer l’activité en temps réel dans les profils d’Audience Manager. |
| [Activation du module Audience Manager pour IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | Didacticiel vidéo | Découvrez comment activer le module Audience Manager pour le TCF IAB. L’activation de ce module externe est facile si vous utilisez Adobe Experience Platform Launch. |
| [Démo du module externe Audience Manager pour IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | Didacticiel vidéo | Dans cette vidéo, découvrez comment les cookies et les balises du service d’ID Experience Cloud et des solutions sont affectés par les sélections de choix des utilisateurs IAB. |

## ![Icône](/assets/aem.png) Adobe Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Mises à jour de produit

* **AEM 6.5.5.0**

   AEM 6.5, Service Pack 5 (6.5.5.0 publié le 4 juin 2020) est une mise à jour importante qui comprend de nouvelles fonctionnalités, des améliorations clés demandées par les clients, ainsi que des performances, une stabilité et des améliorations de sécurité, publiées depuis la version générale d’AEM 6.5 en avril 2019.

   * [Notes de mise à jour](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [Livrables de la mise à jour d’AEM Forms](https://helpx.adobe.com/fr/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4, Service Pack 8, Cumulative Fix Pack (6.4.8.1 publié le 4 juin 2020) est une mise à jour importante qui comprend plusieurs correctifs internes et clients depuis la disponibilité générale d’AEM 6.4, Service Pack 8 (6.4.8.0) en mars 2020.

   * [Notes de mise à jour](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
   * [Livrables de la mise à jour d’AEM Forms](https://helpx.adobe.com/fr/aem-forms/kb/aem-forms-releases.html)

### Auto-assistance

* **AEM en tant que Cloud Service**

   Nouveautés d’AEM as a Cloud Service ?

   Les points forts sont les suivants :

   * Cadre d’intégration commerciale des sites AEM.
   * Amélioration des balises actives et nouveauté de la formation guidée par l’interface utilisateur.
   * Prise en charge de Adobe Asset Link pour Adobe Xd.
   * Prise en charge 3D d’AEM Assets Dynamic Media.
   * Les nouvelles améliorations du libre-service réduisent les dépendances avec Adobe pour les opérations de sandbox.
      * La prise en charge améliorée du sandbox en libre-service dans Cloud Manager permet aux utilisateurs autorisés de supprimer tous les environnements d’un sandbox et de recevoir des crédits.
      * Les environnements sandbox d’auto-hibernation &quot;hibernent&quot; automatiquement les sandbox après une période d’inactivité. Les clients peuvent activement déclencher la &quot;dé-hibernation&quot;.
   * Outils de Transition pour la prise en charge de l’accélération du cloud
   Dans le but de réduire le temps et les coûts de transition sur site au service Cloud, deux outils de transition ont été lancés ce mois-ci. Ces outils sont conçus pour automatiser certaines des tâches clés au cours du processus de transition, réduisant ainsi l&#39;effort global. .

   1. [L’utilisation de l’outil](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) de transfert de contenu (disponible sur SD) rationalise l’activité de transfert de contenu et la rend évolutive. Avec une interface utilisateur conviviale, l’outil est en libre-service pour les clients et partenaires existants (on-prem/AMS) qui passent à AEM en tant que service Cloud.
   1. [Outil de conversion](https://github.com/adobe/aem-cloud-service-dispatcher-converter) du répartiteur AMS (Open Source) pour automatiser la conversion des configurations du répartiteur AMS en configurations du répartiteur de services Cloud.
   [Notes de mise à jour d’AEM as a Cloud Service 2020.6.0](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   Outil de Transition :

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **Composants principaux**

   La version 2.9.0 des composants principaux intègre la couche [de données du client](https://github.com/adobe/adobe-client-data-layer) Adobe et un nouveau composant de barre de progression. Il est désormais disponible avec la documentation [de](https://docs.adobe.com/content/help/fr-FR/experience-manager-core-components/using/introduction.html) création et les détails du [développeur et le téléchargement de projet disponible sur GitHub](https://github.com/adobe/aem-core-wcm-components).

* **Transition vers AEM as a Cloud Service**

   [Le déplacement vers AEM en tant que service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/moving/home.html) Cloud décrit le parcours de transition recommandé pour un client AEM existant qui se rend au service Cloud. L&#39;objectif de cette documentation est de fournir aux clients des informations, des conseils et des bonnes pratiques pour les aider à se préparer à cette transition et à rendre ce voyage structuré et prévisible.

   L’un des outils de Transition Cloud - Outil de transfert de contenu a été publié. [L’outil](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) de transfert de contenu est développé par Adobe et peut être utilisé pour déplacer du contenu existant d’une instance AEM source (sur site ou AMS) vers l’instance de service AEM Cloud cible.

   L’un des outils de refactorisation de code - AEM Dispatcher Converter a été publié. [AEM Dispatcher Converter](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) est un outil permettant de convertir des configurations AEM Dispatcher existantes en AEM en configurations de Répartiteur de services cloud. Il est disponible.

* **Accessibilité et directives WCAG 2.1**

   Mises à jour concernant les lignes directrices de WCAG 2.1 :

   * [Adobe Experience Manager as a Cloud Service et directives d’accessibilité web](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [Guide rapide relatif à WCAG 2.1](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [Création d’un contenu accessible (conformité WCAG 2.1)](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **Newsletters AEM**

   La newsletter AEM par Experience League est conçue pour vous aider à maîtriser AEM afin que vous puissiez début à tirer immédiatement parti de la valeur d’AEM. Voici la dernière newsletter :

   * [ Volume 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html) : Experience Manager est désormais disponible en tant que service cloud.
   * [Abonnez-vous](https://adobeeventsonline.com/AEM/2017/NL/Optin/) à la newsletter Experience Insider.
   * Voir les archives de la newsletter dans la section [Ressources AEM](https://helpx.adobe.com/fr/support/experience-manager/6-5.html) de la page de formation et d’assistance d’Adobe Experience Manager 6.5.

### **Communauté**

* **Discussion de la communauté AEM**

   Vous pouvez maintenant consulter toutes les annonces AEM et les références intéressantes aux blogueurs internes et externes dans un seul et même endroit. Consultez la section [Discussion de la communauté AEM.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### Nouveaux cours et didacticiels Experience Manager

| Contenu | Type de contenu | Description |
| -----------| ---------- | ---------- |
| [Prise en main d’Adobe Asset Link pour les utilisateurs professionnels](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | Cours | Dans ce cours, apprenez à utiliser les fonctionnalités et fonctionnalités d’Adobe Asset Link pour alimenter votre conception créative avec du contenu stocké dans les ressources Adobe Experience Manager. Le cours couvre tous les aspects, du lancement d’un lien d’élément adobe à l’utilisation des ressources de base en passant par les options de recherche et de navigation, en passant par la collaboration efficace avec d’autres utilisateurs. |
| [Prise en main d’AEM Assets pour les utilisateurs professionnels](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | Cours | Découvrez comment commencer à utiliser AEM Assets pour les utilisateurs professionnels. Explorez les bases des ressources AEM, les fonctions de collaboration, la recherche, l’organisation des ressources et le téléchargement des ressources et de leurs rendus. |
| [Prise en main des sites AEM pour les utilisateurs professionnels](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | Cours | Découvrez comment utiliser les principales fonctionnalités et fonctionnalités des sites AEM pour gérer les pages Web de votre entreprise. Le cours couvre tout, de la présentation des sites AEM aux concepts de base de la création, aux fonctions de création avancées et aux fonctionnalités de gestion des pages. |
| [Structure de projet AEM](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | Article | Décrit les modifications requises pour les projets Adobe Experience Manager Maven afin qu’ils soient compatibles avec AEM Cloud Service. |
| [Modèles Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | Didacticiel vidéo | Découvrez comment déboguer AEM en tant que démarrage rapide local du SDK de service Cloud à l’aide de la console Web Sling Models. |
| [Composants de la console Web AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | Didacticiel vidéo | Découvrez comment déboguer AEM en tant que démarrage rapide local du SDK de service Cloud à l’aide de la console Web Composants. |
| [Débogage du démarrage rapide local du SDK AEM à l’aide des journaux](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Didacticiel vidéo | Découvrez comment déboguer AEM en tant que démarrage rapide local du SDK de service Cloud à l’aide de la console Web des lots. |
| [Débogage à distance d’AEM en tant que démarrage rapide local du SDK de service cloud](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | Didacticiel vidéo | Découvrez le débogage Java à distance de votre IDE, ce qui vous permet de parcourir l’exécution du code en direct dans AEM pour comprendre le flux d’exécution exact. |
| [Configuration intelligente des balises](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | Didacticiel vidéo | Cette section contient des instructions détaillées pour intégrer Adobe Experience Manager (AEM) à Smart Content Service à l’aide des E/S Adobe. |
| [Génération par lot de documents](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | Article | Découvrez comment utiliser l’API de traitement par lots pour produire plusieurs communications interactives à partir d’un modèle. |
| [Création d’un document d’impression dans AEM Forms](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | Article | Découvrez les étapes nécessaires pour créer une communication interactive pour le canal d&#39;impression. |
| [Accès au lien de ressource Adobe](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | Didacticiel vidéo | Découvrez comment accéder au contenu stocké dans Adobe Experience Manager Assets (AEM Assets) sans quitter les applications de bureau Creative Cloud que vous connaissez le mieux. |
| [Présentation du panneau Lien de ressource](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | Didacticiel vidéo | Adobe Asset Link permet aux utilisateurs créatifs de parcourir, rechercher, extraire et archiver des fichiers stockés dans AEM Assets à l’aide du panneau intégré dans InDesign, Photoshop et Illustrator. Découvrez l’interface utilisateur du panneau Adobe Asset Link et ses fonctionnalités. |
| [Recherche de ressources](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | Didacticiel vidéo | Les utilisateurs créatifs peuvent rechercher des ressources stockées dans AEM Assets à l’aide de mots-clés ou effectuer une recherche à un emplacement spécifique. |
| [Versions des fichiers et commentaires](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | Didacticiel vidéo | A l’aide du panneau Lien d’actif Adobe, vous pouvez accéder aux détails des fichiers des ressources AEM Assets, tels que les miniatures, les métadonnées de base et les versions depuis le panneau. |
| [Arrivée](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | Didacticiel vidéo | Adobe Asset vous permet d’extraire les ressources AEM directement à partir de l’application créative sur laquelle vous travaillez et de commencer immédiatement à apporter des modifications. |
| [Pour le rendu Emplacement uniquement pour les ressources AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | Didacticiel vidéo | Découvrez comment créer et utiliser un rendu FPO (For Placement Only) pour les ressources AEM. |
| [Copie d’emplacement](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | Didacticiel vidéo | Découvrez comment utiliser les ressources d’AEM Assets à l’aide de l’opération Importer une copie. |
| [Téléchargement et téléchargement](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | Didacticiel vidéo | Découvrez comment télécharger et télécharger des fichiers depuis et vers AEM Assets à l’aide du panneau Lien d’actif. |
| [Fichiers et collections](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | Didacticiel vidéo | Découvrez comment accéder rapidement et facilement aux fichiers et collections AEM Assets à partir du panneau Lien d’actif. |
| [Télécharger](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | Didacticiel vidéo | Découvrez comment télécharger des ressources et leurs rendus sur votre ordinateur local pour les utiliser et les partager. |

### Ressources supplémentaires

* [AEM en tant que Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/landing/home.html)
* [Page d’accueil Formation et assistance AEM 6.5](https://helpx.adobe.com/fr/support/experience-manager/6-5.html)
* [Page d’accueil Formation et assistance AEM 6.4](https://helpx.adobe.com/fr/support/experience-manager/6-4.html)
* [Page d’accueil Formation et assistance AEM 6.3](https://helpx.adobe.com/fr/support/experience-manager/6-3.html)
* [Page d’accueil Formation et assistance AEM 6.2](https://helpx.adobe.com/fr/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/fr/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/fr-FR/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notes de mise à jour de Livefyre](https://docs.adobe.com/content/help/fr-FR/livefyre/using/release-notes/c-rn.html)

## ![Icône](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Campaign Standard

#### Nouveaux cours et didacticiels sur Campaign Standard

| Contenu | Type de contenu | Description |
| -----------| ---------- | ---------- |  
| [Prise en main d’Adobe Campaign Standard pour les utilisateurs professionnels](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Cours | Découvrez comment naviguer dans l’interface, travailler avec des diffusions et créer et gérer des données de destinataire. |

### Campaign Classic

#### Dernière version

[Adobe Campaign Classic version 20.2](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.html)

#### Didacticiels Campaign Classic

| Contenu | Type de contenu | Description |
| -----------| ---------- | ---------- |  
| [Installation et configuration du client Adobe Campaign](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/install-and-setup-the-adobe-campaign-client.html) | Didacticiel vidéo | Découvrez comment télécharger et installer la console Client Adobe Campaign, créer et gérer vos connexions à plusieurs environnements et vérifier l’accès à la console Client Adobe Campaign. |

### Panneau de contrôle de Campaign

| Fonction | Description |
| -----------| ---------- |  
| Surveillance active des Profils | Le Panneau de configuration vous permet de surveiller l’utilisation des profils actifs pour chacune de vos instances Campaign. Cette fonctionnalité est en version bêta et est disponible pour les clients hébergés sur AWS depuis Campaign Standard 10368 build et Campaign Classic 8931 build. [En savoir plus](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html) |

### Ressources d’aide pour Campaign

* Adobe Campaign Standard : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/campaign-standard-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/overview.html) - [Calendrier des versions](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-planning.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/campaign-classic-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/documentation-updates.html)
* Panneau de configuration Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html) - Notes [de](https://docs.adobe.com/content/help/fr-FR/control-panel/using/release-notes.html) mise à jour - Comment télécharger des vidéos pour [Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icône](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [Nouvelles fonctionnalités dans Advertising Cloud DSP](#adcloud-dsp)
* [Nouvelles fonctionnalités dans Advertising Cloud Search](#adcloud-search)

### Nouvelles fonctionnalités dans Advertising Cloud DSP {#adcloud-dsp}

| Fonction | Description |
| -----------| ---------- |
| [!UICONTROL Accueil Campaign] | (Version du 3 juin) De nouvelles mesures d’espacement au niveau de la campagne basées sur le budget de la campagne fourni et le temps écoulé sont disponibles. |
| Prévisions de positionnement | (Version du 3 juin) Pour les emplacements CTV et vidéo avec optimisation au niveau de l’emplacement, les paramètres d’emplacement incluent désormais la prévision de plusieurs longueurs d’annonce (15 s et 30 s). Ils comprennent également des prévisions pour les stocks de VAST et de VPAID. |
| Optimisation CPA/RSDP | (Version du 20 mai) Les gestionnaires de Campaign n&#39;ont plus besoin de limiter les nouveaux placements dans les paquets pour éviter une surallocation du budget. Les emplacements reçoivent désormais une allocation budgétaire dynamique basée sur leurs performances CPM ou CPA/RSDP. |

### Nouvelles fonctionnalités dans [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Fonction | Description |
| -----------| ---------- |
| [!UICONTROL Campagnes] | Microsoft Advertising (anciennement Bing Ads) abandonne les mesures de position moyenne après le 30 septembre 2020. En prévision de cette situation, à compter du 11 juillet, les contraintes fondées sur la position seront ignorées et les conditions fondées sur la position dans tout type de contrainte seront également ignorées. |
| [!UICONTROL Informations publicitaires] | (Version du 13 juin) Les informations suivantes ont été supprimées :<br/><br/><ul><li>Performances des Cibles d&#39;Audience (la version la plus récente)</li><li>Performances historiques (nouvelle version)</li><li>Type de correspondance (nouvelle version)</li><li>Audit des paramètres (la version la plus récente)</li><li>Prépublication de portefeuille (héritée)</li></ul><br/>Les informations restantes sont des versions héritées et le libellé _hérité_ a été supprimé des noms. En outre, les modes Live/Edition ont été supprimés. |

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

| Fonction | Description |
|------|---------|
| [!DNL Bizible] | <ul><li>Nouvelle segmentation basée sur un compte</li><li>Enregistrement des filtres spécifiques au tableau de bord</li><li>Exportation de tableaux de bord Bizible au format PDF</li></ul> |
| Connect de ventes | Composition des mises à jour/améliorations de Windows et du Centre de commandes |

### Annonces

**Centre de succès Marketo Engage :** lancement en février 2020. Le centre de succès est un centre d’aide intégré qui vous permet à vous et à la communauté de rechercher des documents produit, de lancer des guides pratiques, d’accéder au contenu d’adoption, etc. Remarque : cette fonctionnalité sera lancée en version bêta en ANZ et sera déployée en Amérique du Nord plus tard dans le trimestre.

### Dépréciations

* **Paramètre de l’API de ressource &quot;_method&quot; :** après septembre 2020, les points de fin d’API d’actif n’accepteront plus `_method` pour transmettre les paramètres de requête dans un corps POST afin de contourner les limitations de longueur d’URI.
* **Dépréciation de la prise en charge d’Internet Explorer :** à compter de la version du 31 juillet 2020, l’interface utilisateur de Marketo Engage ne sera plus prise en charge dans Internet Explorer.

Pour obtenir des notes de mise à jour cumulatives et historiques, reportez-vous à la page [Notes de mise à jour de Marketo](https://docs.marketo.com/x/CgA6Ag).

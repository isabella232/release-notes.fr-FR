---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: be2f2b5ad468ad63bfcb2fdd67d063203ac08654
workflow-type: tm+mt
source-wordcount: '5030'
ht-degree: 79%

---


# Notes de mise à jour d’Adobe Experience Cloud - Mai 2020

![Bannière](/assets/experience-cloud-banner-3.png)

Cette page fournit de nouvelles fonctionnalités, des correctifs et des avis importants dans [!DNL Adobe Experience Cloud]. Les dates de publication de la solution peuvent varier. Consultez régulièrement les dernières mises à jour.

>[!NOTE]
>
>Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) pour être averti par e-mail de la publication des prochaines versions.

**Date de publication : mai 2020**

Dernière mise à jour : **4 juin 2020**

* [Statut du système Adobe](#status)
* [Interface d’Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**Mise à jour le 4 juin 2020**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html) (liens vers la page d’aide de Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/fr/primetime/user-guide.html) (liens vers la page d’aide de Primetime)

Besoin d’aide ? Visitez [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) pour trouver des cours organisés par Adobe, de la documentation technique, des réponses rapides, des informations de la communauté et des formations dirigées par un instructeur.

## ![Icône](/assets/adobe.png) Statut du système Adobe {#status}

[!UICONTROL Statut du système Adobe] fournit des informations détaillées, des mises à jour de statut et des notifications par email relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

Date de mise à jour : **21 mai 2020**

**Nouveautés**

* Avec votre Adobe ID, vous pouvez vous abonner à des notifications d’événement avec plus de granularité et associées au niveau de l’offre de produit et des modules complémentaires. Pour vous aider à configurer votre abonnement plus rapidement, le processus d’auto-abonnement recommande désormais une sélection de produits et d’offres en fonction de vos droits sur les produits. Cela devrait réduire le nombre d’emails que vous recevez et fournir des notifications plus pertinentes dans votre boîte de réception. Rendez-vous sur [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nouvelles fonctionnalités et améliorations disponibles dès maintenant**

| Fonction | Description |
| -----------| ---------- |
| Amélioration de l’expérience utilisateur pour les abonnements et les notifications | <ul><li>Les emplacements régionaux [!DNL Marketo Engage] sont désormais filtrés en fonction de la liste des offres de produits sélectionnées.</li><li>Les notifications par email [!DNL Marketo Engage] sont pertinentes pour la région, l’emplacement et les préférences d’environnement de l’utilisateur.</li></ul> |
| Confirmation d’abonnement à l’événement | <ul><li>Vous pouvez désormais obtenir une confirmation par email lorsque vous vous abonnez à des mises à jour d’événement unique en cours.</li></ul> |
| Améliorations de la convivialité de la navigation globale | <ul><li>Expérience de l’utilisateur cohérente avec `Adobe.com` dans le menu de navigation de niveau supérieur.</li></ul> |

## ![Icône](/assets/ec_appicon_24.png) Interface d’Experience Cloud {#ecloud}

Mises à jour générales de l’interface d’Experience Cloud.

**Domaine de produit unifié**

Adobe a mis à jour l’en-tête de domaine et d’interface afin d’unifier et d’améliorer votre expérience dans toutes les applications Experience Cloud. Ces améliorations sont conçues pour fluidifier votre utilisation de manière simple, mais importante. Ces améliorations ne modifient pas vos processus actuels.

Les mises à jour comprennent les éléments suivants :

* Nouvelles URL d’application : `experience.adobe.com/<application name>` :
   * À terme, tous les produits adopteront ce modèle d’URL. Recherchez de nouvelles URL pour qu’elles prennent effet tout au long du mois.
   * Navigateurs pris en charge : [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] et [!DNL Opera] (versions les plus récentes). **Remarque** : bien que l’interface d’Experience Cloud prenne en charge ces navigateurs, les applications individuelles peuvent ne pas tous les prendre en charge. (Par exemple, [Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/admin/sys-reqs.html) ne prend pas en charge [!DNL Opera] et [Target](https://docs.adobe.com/help/fr-FR/target/using/implement-target/before-implement/supported-browsers.html) ne prend pas en charge [!DNL Safari].)
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
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Panneau de contrôle d’Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Distribution logicielle | `experience.adobe.com/downloads` |
| Admin Tool (Outil d’administration) (bêta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Panorama et collections]**, un filtre hérité dans le sélecteur de [!UICONTROL ressources Experience Cloud], est en cours de désactivation.

## ![Icône](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notes de mise à jour d’[!DNL Experience Platform,] y compris d’[!DNL Experience Platform Launch,] de [!UICONTROL Journey Orchestration], des services [!UICONTROL Offres], [!UICONTROL Personnes], [!UICONTROL Places], et [!UICONTROL Mobile Services], et des bulletins de sécurité.

### Améliorations de l’interface

Mise à jour : **15 mai 2020**

[!DNL Adobe Experience Platform] publie des mises à jour sur la barre de domaine et d’en-tête afin d’améliorer votre expérience et de réaliser l’union avec d’autres applications Experience Cloud. Les mises à jour comprennent les éléments suivants :

* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide à l’utilisateur, y compris les articles présentés et la documentation contextuelle dans le menu Aide.
* Capacité à fournir des commentaires sur Experience Platform et les tickets d’assistance pour les fichiers.

Voir les [Notes de mise à jour d’Experience Platform](https://docs.adobe.com/content/help/fr-FR/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) pour plus d’informations.

### Attributs du client - nouvelle documentation

Mise à jour : **15 mai 2020**

* [Prise en charge des attributs du client pour le CCPA](https://docs.adobe.com/content/help/fr-FR/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Prise en charge des attributs du client pour le RGPD](https://docs.adobe.com/content/help/fr-FR/core-services/interface/customer-attributes/gdpr.html) (Règlement général sur la protection des données)

### Journey Orchestration {#journey}

Grâce à Adobe Experience Platform, orchestrez des parcours clients individuels à l’échelle sur des canaux d’expérience en anticipant de manière intelligente les besoins de chaque individu en temps réel, quel que soit l’endroit où leur parcours les mène.

* [Documentation](https://docs.adobe.com/content/help/fr-FR/journeys/using/journey-orchestration-home.html)
* [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html)
* [Tutoriels vidéo](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Informations supplémentaires sur la mise à jour d’Experience Platform

* [Notes de mise à jour d’Experience Platform Launch](https://docs.adobe.com/content/help/fr-FR/launch/using/intro/release-notes/current.html)
* [Notes de mise à jour d’Experience Platform](https://docs.adobe.com/content/help/fr-FR/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/fr/security.html) (Tous les produits Adobe)

## ![Icône](/assets/analytics.png) [!DNL Analytics] {#analytics}

Updated **June, 2020**

* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features)
* [Nouvelles fonctionnalités dans Customer Journey Analytics](#cust-journey)
* [Nouvelles fonctionnalités de Media Analytics](#media-aa)
* [Correctifs Adobe Analytics](#aa-fixes)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)
* [Nouveaux tutoriels Analytics](#tutorials-analytics)

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

| Fonction | [Disponibilité](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.translate.html)générale - Date de Cible | Description |
| -----------| ---------- |-------|
| QI de l’attribution : Attribution algorithmique | 18 juin 2020 | Le modèle d’attribution  algorithmique d’Analyse Workspace utilise des techniques statistiques pour déterminer de manière dynamique l’allocation optimale du crédit pour la mesure sélectionnée. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| QI de l’attribution : Fenêtres de recherche personnalisées | 18 juin 2020 | Vous pouvez désormais configurer n’importe quel modèle d’attribution dans le QI  d’attribution afin d’inclure les points de contact entre 90 jours avant la période de rapports. Cela permet généralement d’accroître la précision d’attribution pour les événements qui surviennent au début de la période du rapports en tenant compte des interactions qui se sont produites au cours du ou des mois précédents. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Rôles de projet pour les projets Workspace partagés | 18 juin 2020 | Lors du partage d’un projet Workspace, vous pouvez désormais placer des destinataires dans l’un des trois rôles de projet, en fonction de l’expérience de projet que vous souhaitez qu’ils possèdent : Edition, Duplicata et Vue. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Projets Workspace à Vue seule | 18 juin 2020 | Les projets Workspace peuvent uniquement être partagés avec les utilisateurs sous la forme &quot;Can vue&quot;. Lorsqu’un destinataire de Vue ouvre le projet partagé, il bénéficie d’une expérience de projet plus restrictive, sans rail gauche et avec des interactions limitées. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Possibilité de co-modifier des projets Workspace | 18 juin 2020 | Les Destinataires ajoutés au rôle &quot;Peut modifier&quot; peuvent enregistrer sur un projet qui leur a été partagé. Cela s’applique aussi bien aux administrateurs qu’aux non-administrateurs. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Panneau vierge mis à jour dans Workspace | 18 juin 2020 | Le panneau vierge de Workspace inclut désormais des panneaux et des visualisations, ce qui vous permet de choisir plus facilement le processus d’analyse qui fonctionne le mieux pour vous. |
| Domaines propriétaires disponibles dans la collecte de données régionale pour la Chine | 18 juin 2020 | Permet aux clients disposant d’un `.cn` domaine de demander un domaine propriétaire à utiliser à l’intérieur de la Chine continentale. (Documentation disponible avec l’achat du SKU &quot;China Performance Optimization&quot; (Optimisation des performances de la Chine).) |
| Panneau Aperçu rapide dans Workspace | 25 juin 2020 | Quick Insights fournit des conseils aux non-analystes et aux nouveaux utilisateurs d’Analyse Workspace pour savoir comment répondre rapidement et facilement aux questions de l’entreprise. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Panneau Analyses pour la Cible dans Workspace | 25 juin 2020 | Le panneau Analyses de Cible (A4T) vous permet d’analyser vos activités et expériences de Cible Adobe dans l’espace de travail des Analyses. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Nouvelles fonctionnalités dans Customer Journey Analytics {#cust-journey}

| Fonction | [Disponibilité](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.translate.html)générale - Date de Cible | Description |
| -----------| ---------- |-----|
| Prise en charge de la détection des anomalies | 18 juin 2020 | La détection des anomalies fournit une méthode statistique pour déterminer comment une mesure donnée a changé par rapport aux données précédentes. [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Rôles de projet pour les projets Workspace partagés | 18 juin 2020 | Lors du partage d’un projet Workspace, vous pouvez désormais placer des destinataires dans l’un des trois rôles de projet, en fonction de l’expérience de projet que vous souhaitez qu’ils possèdent : Edition, Duplicata et Vue. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Projets Workspace à Vue seule | 18 juin 2020 | Les projets Workspace peuvent uniquement être partagés avec les utilisateurs sous la forme &quot;Can vue&quot;. Lorsqu’un destinataire de Vue ouvre le projet partagé, il bénéficie d’une expérience de projet plus restrictive, sans rail gauche et avec des interactions limitées. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Possibilité de co-modifier des projets Workspace | 18 juin 2020 | Les Destinataires ajoutés au rôle &quot;Peut modifier&quot; peuvent enregistrer sur un projet qui leur a été partagé. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |

### Nouvelles fonctionnalités de [!UICONTROL Media Analytics] {#media-aa}

Date de mise à jour : **29 mai 2020**

**Suivi de l’état du lecteur :** les clients [!UICONTROL Media Analytics] peuvent capturer l’interaction de la visionneuse au cours de la lecture à l’aide d’un jeu standard de variables de solution pour le mode Plein écran, le sous-titrage, le mode silencieux, l’incrustation dans l’image et le mode In-Focus. Vous pouvez également créer des états de lecteur personnalisés. Des comptes rendus des performances sur les variables de suivi de l’état du lecteur sont désormais disponibles dans [!UICONTROL Analysis Workspace]. Cette fonctionnalité nécessite l’une des configurations suivantes :

* SDK Media [!DNL JavaScript] 3.0 ou version ultérieure
* Utilisation avec le SDK [!DNL Adobe Experience Platform] (AEP) :
   * [!UICONTROL Extension Media Analytics] (pour le Web) : [!UICONTROL Adobe Media Analytics] (SDK 3.x) pour Audio et Video v1.0 ou version ultérieure
   * [!UICONTROL Extension Media Analytics] (pour mobile) : [!UICONTROL Adobe Media Analytics pour Audio] et Vidéo v2.0 ou version ultérieure
* [!UICONTROL Collection Médias]

Voir [À propos du suivi de l’état du lecteur](https://docs.adobe.com/content/help/fr-FR/media-analytics/using/player-state-tracking/player-state-overview.html).

### Adobe Analytics Fixes {#aa-fixes}

* Correction d’un problème en raison duquel les segments avec des recherches sur plusieurs octets pour certaines suites de rapports ne correspondaient à rien. Ils correspondent désormais aux chaînes correctes. AN-220043
* Correction d’un problème en raison duquel le filtre d’éléments dans les rapports et analyses ne fonctionnait pas. AN-206132
* Correction du temps de réponse lent dans l’interface des projets planifiés. AN-214837
* Correction d’un problème en raison duquel l’API de Rapports Analytics 2.0 renvoyait une erreur de plage de dates. AN-215087
* Correction d’un cas où l’instance/visite/visiteur n’était pas comptabilisée dans le dénominateur pour les mesures Durée de la visite. Cela se produit lorsqu’un accès sans valeur pour la dimension (par exemple, Nom de page) suit la même seconde. AN-211074
* Correction d’un problème en raison duquel les utilisateurs ne pouvaient pas accéder aux projets Workspace partagés avec eux. AN-217561
* Correction d’un problème en raison duquel les clés n’étaient pas classifiées par le Créateur de règles de classification. AN-221538
* Correction d’un problème en raison duquel l’utilisation des appels serveur ne rapports aucune donnée d’utilisation. AN-210452
* Correction de problèmes en raison desquels les données manquaient dans AAM pour les segments Adobe Analytics publiés. AN-220208, AN-220659
* Correction d’un problème en raison duquel les rapports affichaient des données mais des journaux de flux de données indiquant &quot;Aucune donnée d’entrepôt de données&quot;. AN-220784, AN-220858
* Correction de problèmes qui empêchaient le lancement d’une Analyse ad hoc à partir du `experiencecloud.com` domaine. AN-219680, AN-221629
* Correction de problèmes liés à l&#39;utilisation de la touche d&#39;accès rapide &quot;Ctrl (ou Commande) + C&quot;. AN-221101, AN-221537
* Correction d’un problème de la page d’activation de la carte d’Activités. AN-222029, AN-221242
* Correction d’un problème en raison duquel il n’était pas possible d’ajouter un point de contact au milieu d’une visualisation Abandons. AN-221648

#### Correctifs Adobe Analytics supplémentaires

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788 ; AN-220866 ; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000 ; AN-222505 ; AN-222559

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Migration vers un domaine de produit unifié | Date d’entrée en vigueur : 28 mai 2020 | La migration vers un domaine de produit unifié pour Adobe Analytics, débutée en janvier 2020, s’est terminée le 28 mai 2020. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. Nous vous informerons via les notes de mise à jour dès que la migration complète de l’architecture sera terminée (bientôt). L’étape de liste blanche ne sera ainsi plus nécessaire. [Voici](https://helpx.adobe.com/fr/analytics/kb/adobe-ip-addresses.html) une liste complète des adresses et domaines IP recommandés que vous devez autoriser.<br>Si votre entreprise bloque les cookies tiers, contactez l’assistance clientèle pour récupérer l’accès à votre compte Adobe Analytics. |
Si votre entreprise bloque les cookies tiers, contactez l’assistance clientèle pour récupérer l’accès à votre compte Adobe Analytics.
|Nouveau landing page par défaut Adobe Analytics|Date d&#39;entrée en vigueur : 18 juin 2020|Le 18 juin 2020, le landing page par défaut d’Adobe Analytics passera de Rapports à Workspace. Cette modification se produira pour tous les utilisateurs n’ayant pas défini de page d’entrée personnalisée auparavant.|
|Autorisation de technologie tierce|12 mars 2020 (date d&#39;entrée en vigueur)|Adobe Analytics a commencé à exploiter les technologies tierces pour la gestion du déploiement de fonctionnalités et la prise en charge des produits. Les URL suivantes doivent être ajoutées à toutes les listes de pare-feu réseau nécessaires pour garantir un accès complet aux fonctionnalités :<ul><li>Gainsight : https://esp.aptrinsic.com</li><li>LaunchDarkly : https://app.launchdarkly.com</li></ul>|
|Amélioration de la redondance pour la disponibilité de l&#39;espace de travail d&#39;Analyse|21 mai 2020|Afin de garantir la disponibilité de l&#39;espace de travail d&#39;Analyse, nous ajoutons un CDN secondaire (Content Diffusion Network) pour une redondance améliorée. Les URL suivantes doivent être ajoutées aux whitelistes de pare-feu réseau nécessaires :<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul>|
|Modification du mode de calcul des [!UICONTROL entrées/sorties] dans [!UICONTROL Workspace]|7 avril 2020|Dans [!UICONTROL Analyse Workspace], en mars 2020, nous avons modifié la manière dont la valeur _Aucun interagit avec Entries/Sorties._ Comme vous pouvez désormais activer et désactiver l’option _Aucun_ dans [!UICONTROL Analysis Workspace], nous appliquons l’option _Aucun_ après l’entrée ou la sortie, alors que (pour les eVars) elle était appliquée avant l’entrée ou la sortie. Supposons, par exemple, que le premier accès d’une visite n’ait aucune valeur pour eVars, contrairement au second accès. Dans [!UICONTROL Reports &amp; Analytics], le premier accès s’affichera comme _Non spécifié_ pour l’entrée, mais dans [!UICONTROL Analysis Workspace], il affichera la valeur pour le second accès.|
|EOL of **[!UICONTROL Dashboard Archive]**|March 27, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports &amp; Analytics] will no longer be available as of October, 2020.|
|Fin de vie - API héritées d’Analytics|9 janvier 2020|En novembre 2020, les services d’API hérités d’Analytics suivants atteindront leur fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner. <ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Nous avons mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0.|
|Fin du service de courtage FTP de San Jose pour Londres et Singapour|Juillet 2020|Pour les clients à Londres et Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|Fin de vie de l&#39;Analyse ad hoc|6 août 2018|Adobe a annoncé son intention de mettre fin à l&#39;Analyse ad hoc. La date de fin de vie sera communiquée dès que possible. Pour obtenir de plus amples informations, voir le site [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/).|

### [!DNL AppMeasurement] {#appm}

Voir [Notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/fr-FR/analytics/implementation/appmeasurement-updates.html). La version 2.20.0 a été publiée le 5 mars 2020.

### Nouveaux tutoriels Analytics {#tutorials-analytics}

| Contenu | Description |
| -----------| ---------- |
| [Modèle de tutoriel de formation dans Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | Le tutoriel de formation à [!UICONTROL Analysis Workspace] vous guide tout au long de la terminologie et des étapes courantes pour la création de votre premier projet dans [!UICONTROL Workspace]. |
| [Ajout de comparaisons mensuelles et annuelles antérieures aux tendances](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Découvrez comment appliquer des plages de dates personnalisées pour créer des comparaisons de tendances mensuelles et annuelles pour n’importe quelle mesure dans [!UICONTROL Analysis Workspace]. |
| [Extension du mode sombre pour Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Activez l’extension Chrome Dark Reader pour rendre Analysis Workspace sombre. |
| [Extension Color EyeDropper pour la définition de palettes personnalisées](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Découvrez comment utiliser l’extension Chrome ColorPick EyeDropper pour trouver facilement les valeurs hexadécimales dont vous avez besoin pour une palette de couleurs personnalisée dans vos projets [!UICONTROL Workspace]. |

#### Ressources d’aide à propos d’Analytics

* [Tutoriels Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentation produit Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/landing/home.html)

## ![Icône](/assets/audience-manager.png) Audience Manager {#aam}

Nouveaux correctifs, fonctionnalités, documentation et tutoriels dans Audience Manager.

### Mises à jour de l’interface utilisateur

Audience Manager publie des mises à jour sur la barre de domaine et d’en-tête afin d’améliorer votre expérience et de réaliser l’union avec d’autres applications Experience Cloud.

* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide à l’utilisateur, y compris les articles présentés et les vidéos contextuelles dans le menu Aide.
* Capacité à fournir des commentaires sur Experience Platform et les tickets d’assistance pour les fichiers.
* Nouveau modèle d’URL plus simple. Mettez à jour vos signets vers la nouvelle URL : `experience.adobe.com/audience-manager`.

Ces mises à jour ne sont disponibles que pour les utilisateurs qui se connectent à l’aide d’un Adobe ID. Pour vous connecter à un Adobe ID, voir [Gestion des utilisateurs et des produits Experience Cloud](https://docs.adobe.com/content/help/fr-FR/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Nouvelles fonctionnalités et correctifs dans Adobe Audience Manager

| Fonction | Description |
| -----------| ---------- |  
| [Outils de gestion en bloc (BAAAM)](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | Nous avons téléchargé une nouvelle feuille de calcul des outils de gestion en bloc qui : <br><br><ul><li>Permet de lister des sous-dossiers dans votre hiérarchie de caractéristiques (AAM-51528).</li><li>Récupère des mesures lorsqu’elles sont demandées pour les caractéristiques associées aux identifiants CRM (identifiants inter-périphériques) (AAM-52135)</li><li>Correction d’un problème de codage de langue pour les caractères coréens (AAM-AAM-54006).</li></ul> |

**Correctifs**

* Correction d’un problème en raison duquel les rapports de tendance expiraient pour les dossiers présentant un grand nombre de caractéristiques. (AAM-54457)
* Correction d’un problème en raison duquel les clients ne pouvaient pas voir le [!UICONTROL créateur d’Expressions] dans le processus de création/modification de caractéristiques. (AAM-54255)
* Correction d’un problème en raison duquel les messages d’erreur dans l’interface ne s’affichaient que pour une courte période, disparaissaient avant que les clients aient la possibilité de les lire. Cela se produisait par exemple lors de la tentative de suppression d’un segment qui était mis en correspondance avec une destination. (AAM-54031)
* Correction d’un problème en raison duquel les clients qui n’utilisaient plus [!UICONTROL Audience Marketplace] recevaient des e-mails de facturation mensuelle. (AAM-54602)
* Correction d’un problème en raison duquel les clients qui cliquaient sur certaines caractéristiques à partir d’autres emplacements de l’interface utilisateur voyaient des liens rompus au lieu des caractéristiques. (AAM-54768)
* Correction d’un problème en raison duquel, en mode de modification de l’expression de caractéristiques, la pression sur ENTRÉE actualisait la page et l’expression de caractéristiques était perdue. (AAM-54210)
* Plusieurs améliorations de l’accessibilité de l’interface. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Nouveaux tutoriels Audience Manager {#tutorials-aam}

| Contenu | Description |
| -----------| ---------- |  
| [Présentation des termes et concepts de base dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | Cette vidéo présente quelques-uns des termes et concepts de base qui vous permettent de commencer dans Audience Manager, notamment les signaux, les caractéristiques, les segments, etc. |
| [Présentation du flux de données dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | Cette vidéo vous aide à comprendre Adobe Audience Manager en décrivant le flux de données dans, via et hors de l’application. |
| [Audience Manager - Présentation d’un DMP](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Découvrez les principaux défis liés à la personnalisation sur plusieurs canaux et comment Adobe Audience Manager facilite les parcours clients. Identifiez également les types de données qui peuvent être intégrés dans Audience Manager et identifiez les partenaires d’éco-système ad-tech intégrés à Audience Manager. |
| [Cas d’utilisation d’Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | Dans cette vidéo, nous identifions quatre cas d’utilisation courants d’Audience Manager et décrivons les bonnes pratiques qui y sont associées. |
| [Présentation des mesures sur plusieurs périphériques dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | Dans cette vidéo, nous abordons la différence entre les profils des périphériques et les profils entre périphériques et montrons où les nombres de l’interface utilisateur correspondent à ces différents types de profils. |
| [Présentation des Audiences prédictives dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | Dans cette vidéo, nous discutons des Audiences prédictives d’Audience Manager, nous présentons des détails sur leur fonctionnement et nous montrons les cas d’utilisation. |
| [Configuration et création de rapports sur les Audiences prédictives dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | Dans cette vidéo, nous examinons la configuration des Audiences prédictives dans l’interface d’Audience Manager. Nous voyons aussi les rapports qui montrent les résultats du modèle. |

## ![Icône](/assets/aem.png) Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Mises à jour de produit

* **AEM en tant que Cloud Service**

   * Améliorations et correctifs du traitement des ressources. La boîte de dialogue de retraitement des ressources permet à l’utilisateur de mieux contrôler, de sélectionner un profil de traitement spécifique et de déterminer si le processus de post-traitement doit être déclenché.
   * Améliorations des performances d’assimilation des fichiers de médias dynamiques.

### Auto-assistance

* **Service de conversion automatique des formulaires - version AFC-2020.03.1**

   Une nouvelle option est disponible lorsque vous installez le dernier connecteur :

   **[!UICONTROL Détection automatique de sections logiques]** : Vous pouvez utiliser l’option [!UICONTROL Détection automatique de sections logiques] pour abandonner les panneaux au niveau de la page (panneaux basés sur le numéro de page) et créer uniquement des panneaux logiques. Il regroupe également les champs qui n’appartiennent à aucune section avec les sections logiques précédentes et les champs d’une section logique répartis sur deux pages adjacentes en une seule section logique. Par exemple, si certains champs d’une section logique se trouvent à la fin de la première page et d’autres au début de la deuxième page, tous ces champs sont regroupés en une seule section logique.

* **Formats d’image non pris en charge dans Dynamic Media**

   Informations sur les sous-types de formats de fichiers image pixellisés qui ne sont pas pris en charge dans [!UICONTROL Dynamic Media].

   Voir [Formats d’image pixellisée non pris en charge dans Dynamic Media](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **Fragments de contenu**

   Informations sur [la prise en charge des fragments de contenu dans l’API HTTP AEM Assets](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html), ainsi que sur la [personnalisation et l’extension des fragments de contenu](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html) et la [configuration des fragments de contenu en vue de la configuration des composants pour le rendu](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **Communauté AEM Experience League**

   Connectez-vous à la [communauté AEM Experience League](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community) : Posez des questions à vos collègues apprenants et aux experts d’AEM, parcourez les fils d’actualité et partagez vos conseils et votre expertise !

* **Newsletters AEM**

   La newsletter AEM par [!UICONTROL Experience League] est conçue pour vous aider à maîtriser AEM afin que vous puissiez début à tirer immédiatement parti de la valeur d’AEM. Voici la dernière newsletter :

   * [ Volume 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html) : Experience Manager est désormais disponible en tant que service cloud.
   * [Abonnez-vous](https://adobeeventsonline.com/AEM/2017/NL/Optin/) à la newsletter Experience Insider.
   * Voir les archives de la newsletter dans la section [Ressources AEM](https://helpx.adobe.com/fr/support/experience-manager/6-5.html) de la page de formation et d’assistance d’Adobe Experience Manager 6.5.

### Nouveaux tutoriels Experience Manager

| Contenu | Description |
| -----------| ---------- |  
| [Configuration de l’exécution locale d’AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Il est possible d’exécuter localement Adobe Experience Manager (AEM) à l’aide du SDK d’[!UICONTROL AEM en tant que Cloud Service] [!UICONTROL Quickstart Jar]. Cela permet aux développeurs de déployer et de tester du code personnalisé, des configurations et du contenu avant de le soumettre à un contrôle de sources et de le déployer dans un environnement [!UICONTROL AEM en tant que Cloud Service]. |
| [Prise en main d’AEM Assets](https://video.tv.adobe.com/v/33624?captions=fre_fr) | Une vidéo d’introduction sur la prise en main d’AEM Assets pour les utilisateurs professionnels. |
| [schémas de dossiers de métadonnées](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Les schémas de dossiers de métadonnées permettent aux utilisateurs de gérer et de revoir les métadonnées associées aux dossiers de fichiers eux-mêmes, plutôt que directement sur les fichiers. |
| [Balisage](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | Les balises constituent un outil intégral de gestion des ressources dans la hiérarchie de dossiers des ressources. La création d’une taxonomie de balisage est essentielle pour permettre aux utilisateurs de découvrir et d’organiser des ressources dans AEM. |
| [Profils de métadonnées](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Les profils de métadonnées permettent l’application automatique des métadonnées par défaut aux ressources au sein des dossiers de ressources. Cela permet de réduire le fardeau de la gestion des métadonnées pour les utilisateurs d’AEM et d’accroître la cohérence des métadonnées. |
| [Schémas de métadonnées](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Les schémas de métadonnées définissent l’interface qui expose les métadonnées de fichier dans AEM. Cette vidéo explore la combinaison des approches utilisées pour appliquer des ressources. |

### Ressources supplémentaires

* [Notes de mise à jour d’AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [Documentation d’AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/landing/home.html)
* [Page d’accueil Formation et assistance AEM 6.5](https://helpx.adobe.com/fr/support/experience-manager/6-5.html)
* [Page d’accueil Formation et assistance AEM 6.4](https://helpx.adobe.com/fr/support/experience-manager/6-4.html)
* [Page d’accueil Formation et assistance AEM 6.3](https://helpx.adobe.com/fr/support/experience-manager/6-3.html)
* [Page d’accueil Formation et assistance AEM 6.2](https://helpx.adobe.com/fr/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Notes de mise à jour d’AEM Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/fr/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/fr-FR/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media](https://docs.adobe.com/content/help/fr-FR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notes de mise à jour de Livefyre](https://docs.adobe.com/content/help/fr-FR/livefyre/using/release-notes/c-rn.html)

## ![Icône](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Campaign Standard

* [Version Adobe Campaign Standard 20.3](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Panneau de contrôle de Campaign

| Fonction | Description |
| -----------| ---------- |  
| Gestion des clés GPG | Installez et/ou générez des clés GPG sur une instance marketing, afin de chiffrer les données envoyées à partir de Campaign et de déchiffrer les données entrantes. |
| Gestion des certificats pour les sous-domaines CNAME | Le Panneau de configuration vous permet désormais de renouveler les certificats SSL de vos sous-domaines qui ont été délégués avec la méthode CNAME. |

### Nouveaux tutoriels Campaign

* Nouveaux tutoriels Campaign Standard

| Contenu | Description |
| -----------| ---------- |  
| [Panneau de configuration - Gestion des enregistrements Google TXT](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Grâce au Panneau de contrôle de Campaign, apprenez à ajouter des enregistrements de vérification de site TXT Google aux sous-domaines utilisés pour envoyer des emails aux adresses GMAIL. |
| [Configuration et exécution d’un processus avec l’activité d’API externe](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Découvrez comment appeler un point de terminaison d’API REST externe à l’aide de l’activité d’API externe. |
| [Prise en main des notifications Push pour Android-Tutoriel](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | Ce tutoriel explique les étapes nécessaires à la configuration des notifications Push avec Campaign Standard et Android App. |

* Nouveaux tutoriels Campaign Classic

| Contenu | Description |
| -----------| ---------- |  
| [Gestion de données importante sur Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Découvrez comment tirer parti du connecteur Snowflake dans Adobe Campaign Classic. |
| [Panneau de configuration - Gestion des enregistrements Google TXT](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Grâce au Panneau de contrôle de Campaign, apprenez à ajouter des enregistrements de vérification de site TXT Google aux sous-domaines utilisés pour envoyer des emails aux adresses GMAIL. |

### Ressources d’aide pour Campaign

* Adobe Campaign Standard : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/campaign-standard-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/overview.html) - [Calendrier des versions](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-planning.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/campaign-classic-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/documentation-updates.html)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/control-panel/using/release-notes.html)

## ![Icône](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Nouvelles fonctionnalités dans Advertising Cloud DSP](#adcloud-dsp)
* [Nouvelles fonctionnalités dans Advertising Cloud Search](#adcloud-search)

### Nouvelles fonctionnalités dans Advertising Cloud DSP {#adcloud-dsp}

| Fonction | Description |
| -----------| ---------- |
| [!UICONTROL Campagnes Classic] et [!UICONTROL Campagnes bêta] | Les paramètres de mesure IAS pour la fraude et la sécurité de la marque, que vous pouvez éventuellement configurer pour chaque campagne, incluent désormais des options de mesure sur les inventaires VAST et VPAID. |
| [!UICONTROL Campagnes bêta] | Les visualisations des données et les temps de chargement des pages ont été améliorés. |
|  | Sur toutes les pages, vous pouvez désormais télécharger des rapports Excel basés sur les filtres et vues en cours. |
|  | (Dans la version du 22 mai) Les nouvelles mesures comprennent les mesures Temps passé, Diffusion d’intervalle en cours, OTS spécifiques à la date. |
| [!UICONTROL Blacklistes] | Le système de prévision utilise désormais automatiquement la blackliste au niveau de l’annonceur ou du compte. Les utilisateurs n’ont plus besoin de coller la blackliste dans les paramètres de placement. |
| [!UICONTROL Offres d’inventaire] | (Bêta fermée) Un nouveau formulaire simplifié vous permet de configurer, de modifier et de résoudre rapidement les problèmes liés aux offres des plateformes côté offre (SSP) qui ne sont pas disponibles dans la boîte de réception Deal ID. |
|  | Lorsque vous acceptez un ensemble d’offres garanties par la programmation dans la boîte de réception Deal ID, vous êtes désormais averti que vous devez créer un emplacement par défaut pour chacun des Deal ID. |

### Nouvelles fonctionnalités dans [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Fonction | Description |
| -----------| ---------- |
| [!UICONTROL Campagnes] | (Comptes Google Ads ; service bêta) À compter de la fin mai, Advertising Cloud Search pourra synchroniser les données de vos campagnes d’affichage Google Gmail et de vos campagnes Google Smart Shopping avec les conversions Google pour le suivi et les rapports. Le service vous permet également de modifier les paramètres des campagnes et des groupes publicitaires pour vos campagnes existantes à partir des vues Campagnes et Groupes publicitaires. Le service sera facultatif. Une fois le service généralement disponible, des frais supplémentaires s’appliqueront.<br>Pour plus d’informations sur le service, y compris le programme bêta et la portée future, contactez votre gestionnaire de compte Adobe. |

## ![Icône](/assets/magento.png) [!DNL Magento] {#magento}

Pour les notes de mise à jour de Magento, veuillez consulter :

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icône](/assets/marketo.png) [!DNL Marketo] {#marketo}

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

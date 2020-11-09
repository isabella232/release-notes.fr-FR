---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Notes de mise à jour d’Adobe Experience Cloud
doc-type: release notes
last-update: November 2020
author: mfrei
translation-type: ht
source-git-commit: 27e6ef1fb123fd8a5d136f86c5df492ea6e79733
workflow-type: ht
source-wordcount: '8040'
ht-degree: 100%

---


# Notes de mise à jour d’Adobe Experience Cloud - Novembre 2020

![Bannière](/assets/experience-cloud-banner-3.png)

Cette page décrit les nouvelles fonctionnalités, les correctifs et des informations importantes pour [!DNL Adobe Experience Cloud]. Elle met également en évidence la nouvelle documentation, les formations et les tutoriels vidéo qui vous permettent de tirer le meilleur parti d’Experience Cloud.

>[!IMPORTANT]
>
>Cette page peut contenir du contenu de version préliminaire pour certains produits et peut être modifiée avant les dates de mises à jour. Consultez régulièrement les mises à jour.

>[!NOTE]
>
>Inscrivez-vous aux [Mises à jour produit prioritaires d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) afin de recevoir une notification par courrier électronique concernant les prochaines mises à jour.

Dernière mise à jour : **2 novembre 2020**

* [Statut du système Adobe](#status)
* [Services d’Experience Cloud et administration](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) et [Customer Journey Analytics](#cust-journey)   (Mise à jour **2 novembre 2020**)
* [Audience Manager](#aam)
* [Experience Manager](#aem) (Mise à jour : **28 octobre 2020**)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)  (Mise à jour : **28 octobre 2020**)
* [[!DNL Target]](#target) (Mise à jour : **2 novembre 2020**)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Primetime]](https://docs.adobe.com/content/help/fr-FR/primetime/release-notes/home.html)
* [Document Cloud](#doc-cloud)

Besoin d’aide ? Consultez [Adobe Experience League](https://experienceleague.adobe.com/#home) pour trouver de la documentation technique et sur les produits, des cours préparés par Adobe, des tutoriels vidéo, des réponses rapides, des informations provenant de la communauté et des formations dispensées par un instructeur.

>[!NOTE]
>
>La documentation Experience Cloud se déplace vers Experience League. En octobre, toutes les notes de mise à jour, articles, vidéos et tutoriels passeront de leur emplacement actuel à `docs.adobe.com` dans Experience League. Ce déplacement permet de s’assurer que tous les contenus d’apprentissage, d’auto-assistance, d’activation et de communauté sont diffusés à partir d’un seul emplacement. Lorsque ce changement se produira, aucune action ne sera nécessaire, car tous les liens seront redirigés vers Experience League. Nous mettrons à jour les notes de mise à jour au début du découpage.

## ![Icône](/assets/adobe.png) Statut du système Adobe {#status}

[!UICONTROL Statut du système Adobe] fournit des informations détaillées, des mises à jour de statut et des notifications par email relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

Pas de mise à jour effectuée.

Voir [Statut d’Adobe - 21 mai 2020](https://docs.adobe.com/content/help/fr-FR/release-notes/experience-cloud/previous/2020/05212020.html#status) pour obtenir les dernières informations de mise à jour.

## ![Icône](/assets/ec_appicon_24.png) Services d’Experience Cloud et administration {#ecloud}

Anciennement appelée _Services principaux d’Experience Cloud_, la documentation sur les [services et l’administration d’Experience Cloud](https://docs.adobe.com/content/help/fr-FR/core-services/interface/experience-cloud.html) comprend les attributs du client, l’activation de la bibliothèque d’audiences ([!UICONTROL personnes] services), la gestion des utilisateurs et des produits, ainsi que les cookies Experience Cloud.

Pas de mise à jour effectuée.

Pour obtenir des informations sur les dernières mises à jour, reportez-vous à [Notes de mise à jour cumulatives pour les services Experience Cloud](https://docs.adobe.com/content/help/fr-FR/core-services/interface/release-notes/release-notes.html).

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Inclut les informations de mise à jour pour Experience Platform et Experience Platform Launch,

Publication : **14 octobre 2020**

Voir les [notes de mise à jour Experience Platform](https://docs.adobe.com/content/help/fr-FR/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md), pour plus d’informations sur les mises à jour apportées aux éléments suivants :

* Préparation de données
* Profil client en temps réel
* Segmentation Service
* Sources

### Experience Platform Launch

Voir les [notes de mise à jour Experience Platform Launch](https://docs.adobe.com/content/help/fr-FR/launch/using/intro/release-notes/current.html), pour plus d’informations sur Platform Launch.

### Tutoriels et cours sur Experience Platform et ses services

Nouveaux tutoriels, vidéos ou cours publiés pour Experience Platform et ses services.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 26 octobre 2020 | [Introduction à Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/introduction-to-offer-decisioning.html?lang=fr-FR) | Vidéo | Cette vidéo offre un aperçu d’[!UICONTROL Offer Decisioning], un service d’applications qui complète Adobe Experience Platform. La vidéo traite des problématiques métier qu’[!UICONTROL Offer Decisioning] permet de résoudre, des principales fonctionnalités de ce service, de l’architecture de base et des principaux cas pratiques. |
| 29 octobre 2020 | [Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/demo-of-offer-decisioning.html?lang=fr-FR) | Vidéo | Découvrez comment les marques peuvent utiliser le nouveau service [!UICONTROL Offer Decisioning] d’Adobe pour définir et gérer leurs offres, exploiter les données client en temps réel et offrir les expériences adéquates que leurs clients attendent. |
| 14 septembre 2020 | [Valeur commerciale d’Attribution AI](https://docs.adobe.com/content/help/fr-FR/platform-learn/tutorials/intelligent-services/business-value-of-attribution-ai.html) | Vidéo | Dans le cadre d’[!UICONTROL Intelligent Services], [!UICONTROL Attribution AI] est un service d’attribution algorithmique à plusieurs canaux qui calcule l’influence et l’impact incrémentiel des interactions des clients par rapport à des résultats spécifiés. Grâce à [!UICONTROL Attribution AI], les professionnels du marketing peuvent mesurer et optimiser les dépenses publicitaires et marketing en comprenant l’impact de chaque interaction client sur chaque phase du parcours des clients. |
| 14 septembre 2020 | [Valeur commerciale de Customer AI](https://docs.adobe.com/content/help/fr-FR/platform-learn/tutorials/intelligent-services/business-value-of-customer-ai.html) | Vidéo | Cette vidéo montre comment [!UICONTROL Customer AI] enrichit les profils clients avec des propensions basées sur l’IA et renforce la segmentation et le ciblage des clients. |
| 14 septembre 2020 | [Valeur commerciale de Platform et de Magento](https://docs.adobe.com/content/help/fr-FR/platform-learn/tutorials/experience-cloud/business-value-of-platform-and-magento.html) | Vidéo | Cette vidéo montre comment utiliser Adobe Experience Platform avec [!DNL Magento] Commerce pour créer une vue unique de clients et personnaliser intelligemment les expériences sur un storefront numérique et entre canaux. |

## ![Icône](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Grâce à Adobe Experience Platform, orchestrez des parcours clients individuels à l’échelle sur des canaux d’expérience en anticipant de manière intelligente les besoins de chaque individu en temps réel, quel que soit l’endroit où leur parcours les mène.

### Ressources supplémentaires pour Journey Orchestration

[Documentation](https://docs.adobe.com/content/help/fr-FR/journeys/using/journey-orchestration-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html) - [Tutoriels vidéos](https://docs.adobe.com/content/help/fr-FR/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Icône](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Date de publication : **29 octobre 2020**

* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features)
* [Nouvelles fonctionnalités dans Customer Journey Analytics](#cust-journey)  (Mise à jour 2 novembre 2020)
* [Nouvelles fonctionnalités de Media Analytics](#media-aa)
* [Correctifs dans Adobe Analytics](#aa-fixes)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [Cours et tutoriels pour Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.html) - Date cible | Description |
| ----------- | ---------- | ------- |
| Documentation Adobe Analytics | Novembre 2020 | La documentation Adobe Analytics se déplace vers Experience League. Au cours du mois d’octobre, tous les articles, vidéos, notes de mise à jour et tutoriels passeront de leur emplacement actuel à `docs.adobe.com` dans `experienceleague.adobe.com`. Ce déplacement permet de s’assurer que tous les contenus d’apprentissage, d’auto-assistance, d’activation et de communauté sont diffusés à partir d’un seul emplacement. Lorsque ce changement se produira, aucune action ne sera nécessaire, car tous les liens seront redirigés vers Experience League. Nous mettrons à jour les notes de mise à jour au début du découpage. |
| Visualisation [!UICONTROL Ligne] dans [!UICONTROL Workspace] : option de tendance de moyenne glissante | 8 octobre 2020 | La moyenne glissante a été ajoutée aux paramètres de tendance de visualisation [!UICONTROL Ligne]. Connue également sous le nom de moyenne mobile, une moyenne glissante utilise un nombre spécifique de points de données (déterminé par une sélection de [!UICONTROL périodes]), calcule leur moyenne et utilise cette moyenne comme point dans la ligne. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/analysis-workspace/visualizations/line.html) |
| API de [!UICONTROL réparation des données] | 8 octobre 2020 | L’API de [!UICONTROL réparation des données] est un outil permettant de supprimer des données des suites de rapports Analytics. La version d’octobre offre la possibilité de supprimer des variables eVar, prop et [!UICONTROL Activity Map] spécifiées pour une période spécifiée. D’autres fonctionnalités seront activées à l’avenir. L’utilisation de l’API de [!UICONTROL réparation des données] supprime définitivement les données Adobe Analytics existantes. Nous recommandons une approche prudente pour exécuter la réparation afin de réduire les risques de suppression accidentelle. Un contrat est nécessaire pour l’accès à l’API de [!UICONTROL réparation de données]. Contactez votre équipe de compte pour plus d’informations. [En savoir plus](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/data-repair.md) |
| [!UICONTROL Workspace] : page d’aide sur les performances | 22 octobre 2020 | La page d’aide sur les performances [!UICONTROL Analysis Workspace] présente les différents facteurs qui influent sur les performances du projet et fournit des liens vers des conseils relatifs à l’optimisation. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/analysis-workspace/workspace-faq/optimizing-performance.html) |
| Améliorations apportées à l’interface utilisateur des [!UICONTROL tableaux de bord] Analytics | 23 octobre 2020 | Lors de la création d’une fiche d’évaluation mobile dans [!UICONTROL Workspace], la mise en forme de cette fiche d’évaluation correspond désormais à l’application. |

### Nouvelles fonctionnalités dans Customer Journey Analytics {#cust-journey}

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.html) - Date cible | Description |
| ----------- | ---------- | ----- |
| Customer Journey Analytics   documentation | Novembre 2020 | La documentation Customer Journey Analytics se déplace vers Experience League. Au cours du mois d’octobre, tous les articles, vidéos, notes de mise à jour et tutoriels passeront de leur emplacement actuel à `docs.adobe.com` dans `experienceleague.adobe.com`. Ce déplacement permet de s’assurer que tous les contenus d’apprentissage, d’auto-assistance, d’activation et de communauté sont diffusés à partir d’un seul emplacement. Lorsque ce changement se produira, aucune action ne sera nécessaire, car tous les liens seront redirigés vers Experience League. Nous mettrons à jour les notes de mise à jour au début du découpage. |
| Visualisation [!UICONTROL Ligne] : option de tendance de moyenne glissante | 8 octobre 2020 | La moyenne glissante a été ajoutée aux paramètres de tendance de visualisation Ligne. Une moyenne glissante calcule la moyenne pour une période antérieure spécifiée et l’utilise comme point de données de tendance, puis passe à la période suivante. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/analysis-workspace/visualizations/line.html) |
| Suppression de la limitation de renvoi | 19 octobre 2020 | Afin de fournir une expérience améliorée du CJA, nous avons supprimé la limite de renvoi (importation de données historiques). Auparavant, vous pouviez renvoyer un maximum de 2,5 milliards de lignes et au-delà, vous étiez tenu de demander l’aide du service d’ingénierie. Désormais, vous pouvez renvoyer les données vous-même, sans aucune restriction. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/analytics-platform/using/cja-connections/create-connection.html#enable-connection) |
| Page d’aide sur les performances Analysis Workspace | 22 octobre 2020 | La page d’aide sur les performances Analysis Workspace présente les différents facteurs qui influent sur les performances du projet et fournit des liens vers des conseils relatifs à l’optimisation. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/analysis-workspace/workspace-faq/optimizing-performance.html) |
| Journey IQ : analyse cross-canal | 30 octobre 2020 | Journey IQ : l’analyse cross-canal permet aux clients de recréer un jeu de données d’événement Adobe Analytics (ou autre) dans le lac de données Adobe Experience Platform d’un espace de noms d’identité à un autre. En règle générale, cela signifie recréer le jeu de données d’événement d’un identifiant basé sur un cookie vers un identifiant basé sur une personne. De cette façon, le jeu de données recréé peut être combiné avec d’autres données personnelles dans une connexion CJA, ce qui permet une analyse entre dispositifs/cross-canal dans Analysis Workspace. |
| Mesures et dimensions [!UICONTROL Durée de la visite] | 30 octobre 2020 | Les mesures et dimensions [!UICONTROL Durée de la visite] vous permettent de déterminer le temps que les clients passent dans divers aspects du parcours du client, ce qui vous permet de bénéficier d’une vue plus complète sur l’engagement et les goulets d’étranglement entre les canaux. |
| Dimensions [!UICONTROL Appareil] et [!UICONTROL Géographie] | 30 octobre 2020 | Les dimensions [!UICONTROL Appareil] et [!UICONTROL Géographie] sont désormais disponibles par défaut dans le cadre du projet « Prise en charge de la recherche globale » dans le [connecteur source Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html). Cet ajout très demandé augmente la [parité entre Adobe Analytics et CJA](https://docs.adobe.com/content/help/fr-FR/analytics-platform/using/cja-overview/cja-aa.html). |

### Nouvelles fonctionnalités de [!UICONTROL Media Analytics] {#media-aa}

| Fonctionnalité | [Disponibilité générale](https://docs.adobe.com/content/help/fr-FR/analytics/landing/an-releases.html) - Date cible | Description |
| ----------- | ---------- | ---------- |
| Panneau [!UICONTROL Observateur simultané de médias] dans [!UICONTROL Workspace] | 17 septembre 2020 | Le panneau [!UICONTROL Observateurs simultanés de médias] vous permet de déterminer où s’est produit le pic d’accès simultané ou où des abandons ont eu lieu. Il fournit des informations importantes sur la qualité du contenu et l’engagement des observateurs et aide à la résolution des problèmes ou à la planification du volume/de l’échelle. [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/media-analytics/using/media-reports/media-workspace-panels/media-concurrent-viewers.html) |

### Correctifs dans Adobe Analytics {#aa-fixes}

* Correction d’un problème de ventilations impliquant des classifications qui ne fonctionnaient pas si la mesure avait un modèle d’attribution. S’appliquait à une situation où la suite de rapports était migrée vers la dernière architecture des classifications. (AN-230364)
* Correction d’un problème en raison duquel l’interface utilisateur des segments ne fonctionnait plus après avoir collé les valeurs dans un conteneur. (AN-233998)
* Correction d’un problème en raison duquel l’historique des tâches [!UICONTROL Flux de données] manquait certaines données horaires. (AN-231776)
* Correction d’un problème survenant lors de la copie de mesures calculées qui générait le message d’erreur « Vous n’êtes pas autorisé à accéder à cette mesure ». (AN-238070)
* Correction d’un problème en raison duquel il était impossible de définir un alignement correct sur la visualisation [!UICONTROL Texte] dans [!UICONTROL Workspace]. (AN-238188)

#### Correctifs Adobe Analytics supplémentaires

AN-224702 ; AN-232791 ; AN-233982 ; AN-234384 ; AN-235608 ; AN-236538 ; AN-236598 ; AN-236738 ; AN-237434 ; AN-237672 ; AN-237850 ; AN-237943 ; AN-238081 ; AN-238508 ; AN-238527 ; AN-238536 ; AN-238619

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout   ou de mise à jour | Description |
| ----------- | ---------- | ---------- |
| Ajout de l’en-tête HSTS à toutes les requêtes HTTPS entrantes | 29 septembre 2020 | Le 29 septembre 2020, nous avons commencé à ajouter l’en-tête HSTS à toutes les requêtes entrantes qui utilisent des connexions HTTPS. Cela indique au navigateur/client d’effectuer toutes les requêtes à venir dans HTTPS, ce qui est considéré comme une bonne pratique de sécurité. À ce stade, nous n’appliquerons pas cette règle pour les requêtes entrantes utilisant HTTP. |
| Modification du paramètre de cookie du service Experience Cloud ID | 22 septembre 2020 | Une mise à jour des paramètres de confidentialité pour Chrome version 80 a eu un impact sur la capacité d’Adobe Analytics à suivre certains utilisateurs qui consultaient des pages AMP sur Google. Plus précisément, elle empêche le suivi inter-domaines des utilisateurs qui consultent des pages AMP hébergées par Google. Cela pourrait entraîner une augmentation du nombre de visiteurs uniques. Ce correctif permet aux utilisateurs de résoudre ce problème en modifiant les paramètres de leurs cookies ECID.<br>Actuellement, Analytics définit les cookies ECID (service Experience Cloud ID) avec le paramètre `SameSite = Lax` qui, avant la version 80 de Chrome, permettait le suivi inter-domaines. Ce n’est plus le cas. Cette modification permet aux utilisateurs de mettre à jour le paramètre SameSite pour les cookies ECID vers `None`.<br>Veuillez noter que cela permet le partage du cookie Analytics dans d’autres situations, mais les cookies Analytics ne contiennent aucune information sensible. En outre, lors du choix de ce paramètre, les cookies doivent être définis sur `Secure` afin que les données puissent être uniquement transmises par des connexions HTTPS. Si vous souhaitez apporter cette modification, demandez à un utilisateur pris en charge d’ouvrir un ticket auprès de l’assistance clientèle. |
| Migration de `omniture.com` vers un domaine `adobe.com` | 21 août 2020 | Le 13 août 2020, Adobe Analytics a migré son architecture frontale de `omniture.com|http://omniture.com/` vers le domaine `adobe.com|http://adobe.com/`. Cette modification devrait atténuer les problèmes de cookies tiers qui se sont posés après le changement initial du domaine de produit unifié en date du 28 mai 2020. Suite à cette mise à jour, le navigateur peut inviter les utilisateurs à approuver le nouveau domaine `.adobe.com|http://an.adobe.com/` ou `experience.adobe.com|http://experience.adobe.com/`. |
| Mise à jour de la compatibilité d’Ad Hoc Analysis avec Java 8 | 21 août 2020 | Ad Hoc Analysis n’est pas actuellement compatible avec les versions 1.8.0_261+ de Java 8. Pour vous assurer que votre accès à cet outil n’est pas interrompu avant la [date de fin de vie](https://spark.adobe.com/page/S9Bhp66VJ2fEn/), nous vous recommandons de conserver une version de Java 8 antérieure à la version 1.8.0_261. |
| Fin de vie des Data Connectors Adobe | 13 juillet 2020 | Les [!UICONTROL Data Connectors] Adobe sont alimentés par une technologie héritée qui n’est plus viable ni prise en charge. Nous disposons d’un nouveau standard dans le [Programme de partenariat Adobe Exchange](https://partners.adobe.com/exchangeprogram/experiencecloud) qui devrait être adopté pour toutes les intégrations qui souhaitent continuer à être proposées et prises en charge. La date officielle de fin de vie n’a pas encore été fixée, mais elle devrait avoir lieu dans les 12 à 18 prochains mois (mi-2021 à fin 2021). [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics/import/dataconnectors/data-connectors-eol.html) |
| Fin de vie d’Ad Hoc Analysis | 6 août 2018 | Adobe a annoncé la prochaine fin de vie d’Ad Hoc Analysis en date du 1er mars 2021. Pour obtenir de plus amples informations, voir le site [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### AppMeasurement {#appm}

Pour connaître les dernières mises à jour des versions d’AppMeasurement, reportez-vous aux [notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/fr-FR/analytics/implementation/appmeasurement-updates.html).

### Cours et tutoriels pour Analytics {#tutorials-analytics}

Nouveaux cours, tutoriels et articles dans [!DNL Analytics] et [!UICONTROL Customer Journey Analytics].

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 8 octobre 2020 | [Tableaux à structure libre, fondation d’Analysis](https://video.tv.adobe.com/v/41766?captions=fre_fr) | Vidéo | Apprenez ce que vous devez savoir et ce que vous apprendrez lorsque vous débuterez ce parcours de formation. |
| 5 octobre 2020 | [Utilisation des mesures de participation dans Analysis Workspace](https://docs.adobe.com/content/help/fr-FR/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/using-participation-metrics-in-analysis-workspace.html) | Vidéo | Utilisez cette astuce simple pour obtenir n’importe quelle mesure de participation dans [!UICONTROL Analysis Workspace] à tout moment. |
| 5 octobre 2020 | [Création automatique de tables à structure libre dans Analysis Workspace](https://docs.adobe.com/content/help/fr-FR/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/auto-build-freeform-tables-in-analysis-workspace.html) | Vidéo | Déposez les composants directement dans un projet vierge, un panneau ou un tableau à structure libre et un tableau est automatiquement créé pour vous dans un format recommandé. |
| 5 octobre 2020 | [Utilisation de mesures dans une table à structure libre](https://docs.adobe.com/content/help/fr-FR/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/working-with-metrics-in-a-freeform-table.html) | Vidéo | Découvrez les différentes manières d’utiliser les mesures dans une [!UICONTROL table à structure libre] dans [!UICONTROL Analysis Workspace]. |
| 21 septembre 2020 | [Journey AI - Optimisation prédictive du temps d’envoi](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/communication-channels/email/journey-ai/predictive-send-time-optimization.html) | Vidéo | Identifiez les workflows nécessaires pour synchroniser les données entre Adobe Campaign et le modèle Journey IA. Découvrez comment afficher les scores de temps d’envoi au niveau du profil individuel et comment exécuter des diffusions Email à l’aide d’une formule de temps d’envoi. |

### Ressources d’aide à propos d’Analytics

* [Tutoriels Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/analytics-learn/tutorials/overview.html)
* [Documentation produit Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/landing/home.html)

## ![Icône](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nouveaux correctifs, fonctionnalités, documentation et tutoriels pour Audience Manager.

Date de publication : **8 octobre 2020**

### Nouvelles fonctionnalités, améliorations et correctifs dans Audience Manager {#aam-features}

| Fonctionnalité | Date d’ajout   ou de mise à jour | Description |
|----|----|----|
| [Audiences prédictives](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences.html) | 21 octobre 2020 | <ul><li>**Clonage des modèles d’audiences prédictives** : vous pouvez désormais cloner des modèles existants et modifier leur configuration en fonction de vos besoins. Pour plus d’informations, consultez [Clonage et modification des modèles d’audience prédictives](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences-start.html#clone-predictive-audiences).</li><li>**Classification par lot des audiences prédictives** : outre la classification des visiteurs selon des personnalités distinctes en temps réel, les audiences prédictives prennent désormais en charge la classification par lot, ce qui vous permet de classer les utilisateurs intégrés et de les activer dans les destinations par lot.</li></ul> |
| [Rapports de chevauchement](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/reporting/interactive-and-overlap-reports/dynamic-reports.html) | 23 octobre 2020 | Nous avons mis à jour la méthodologie que nous utilisons pour calculer les rapports de chevauchement ([Caractéristique à caractéristique](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/reporting/interactive-and-overlap-reports/trait-trait-overlap-report.html), [Segment à caractéristique](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/reporting/interactive-and-overlap-reports/segment-trait-overlap-report.html), [Segment à segment](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/reporting/interactive-and-overlap-reports/segment-segment-overlap-report.html)). Le calcul des rapports de chevauchement est désormais basé sur les uniques de rapports et sur les signatures MinHash (plutôt que sur l’[échantillonnage de données 1/54](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/reporting/report-sampling.html#data-sampling-ratio)). |

### Correctifs et améliorations {#aam-fixes-and-improvements}

* Correction d’un problème de la fonction d’Audience prédictive en raison duquel certains utilisateurs ne pouvaient supprimer aucun de leurs modèles, même si aucun segment n’était mappé aux modèles. (AAM-55881)
* Correction d’un problème en raison duquel certains utilisateurs ne pouvaient pas supprimer de caractéristiques ou de segments qui avaient été utilisés comme référence pour les modèles d’audience prédictive supprimés. (AAM-56476)
* Nous avons continué à améliorer l’accessibilité dans l’interface. (AAM-53215)

### Cours et tutoriels sur Audience Manager {#tutorials-aam}

Nouveaux tutoriels, vidéos et cours publiés pour Audience Manager.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 28 octobre 2020 | [Présentation des nombres dans le graphique des caractéristiques](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/understanding-numbers-in-the-trait-graph.html?lang=en#build-and-manage-audiences) | Vidéo | Obtenez des conseils les nombres indiqués pour les caractéristiques dans l’écran d’informations sur les caractéristiques. |
| 23 octobre 2020 | [Planification de la création de caractéristiques à partir des données Analytics](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/planning-trait-creation-from-analytics-data.html?lang=en#build-and-manage-audiences) | Vidéo | Découvrez des conseils et astuces pour vous aider lorsque vous envisagez d’utiliser des données Adobe Analytics dans vos caractéristiques dans Audience Manager. |
| 23 octobre 2020 | [Choix d’une source de données lors de la création de caractéristiques](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/choosing-a-data-source-when-creating-traits.html?lang=en#build-and-manage-audiences) | Vidéo | Le champ Source de données est l’un des champs importants à remplir lors de la création des caractéristiques. Obtenez des conseils sur le choix de la source de données appropriée pour les caractéristiques basées sur les règles et intégrées. |
| 14 septembre 2020 | [Utilisation de l’affichage du code pour créer et modifier des caractéristiques](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-code-view-to-create-and-edit-traits.html?lang=en#build-and-manage-audiences) | Vidéo | Découvrez comment utiliser l’affichage du code lors de la création de nouvelles caractéristiques ou de la modification de caractéristiques existantes. L’affichage du code est une alternative au Générateur d’expression lors de la définition de l’expression de caractéristiques. |
| 10 octobre 2020 | [Présentation des audiences prédictives](https://docs.adobe.com/content/help/fr-FR/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | Vidéo | Dans cette vidéo, nous discuterons des audiences prédictives d’Audience Manager, nous présenterons des détails sur leur fonctionnement et nous montrerons les cas d’utilisation. |

## ![Icône](/assets/aem.png) Adobe Experience Manager {#aem}

AEM n’a pas été mis à jour ce mois-ci. Le contenu suivant provient du mois dernier (à l’exception des nouveaux cours et didacticiels).

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

>[!NOTE]
>
>Adobe recommande de consulter fréquemment les [mises à jour et les feuilles de route Experience Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-release-information/aem-release-updates/home.html) afin de se tenir au courant des informations de mise à jour.

### Versions de produit

* **AEM as a Cloud Service**

   Nouveautés dans AEM as a Cloud Service

   * **Adobe Experience Manager Sites as a Cloud Service**
      * Le SDK JavaScript de l’éditeur d’applications d’une seule page (SPA) est [désormais en open source](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/implementing/headless/spa/reference-materials.html).
   * **Adobe Experience Manager Assets as a Cloud Service**

      * Les fichiers image de filigrane sont pris en charge pour les rendus générés avec les microservices Asset. Ils peuvent être configurés en tant que Profils de traitement et utilisent un fichier PNG en tant que filigrane. Voir [Ajouter un filigrane à vos fichiers](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/assets/manage/watermark-assets.html).
      * Améliorations apportées à Dynamic Media :
         * Publication sélective : il est désormais possible pour une équipe marketing d’accéder aux images de recadrage intelligent [!UICONTROL Dynamic Media] et aux rendus dynamiques synchronisés sur Dynamic Media afin de pouvoir créer des supports promotionnels, sans avoir à publier ces ressources dans Dynamic Media pour une diffusion globale. La publication de contenu Experience Manager et [!UICONTROL Dynamic Media] est découplée et peut se produire séparément pour y parvenir. Voir [Publication sélective](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/assets/dynamicmedia/selective-publishing.html).
         * Réinitialisation du mot de passe : les administrateurs peuvent désormais réinitialiser le mot de passe Cloud Service de [!UICONTROL Dynamic Media] reçu lors de la mise en service. La réinitialisation peut être effectuée dans l’interface utilisateur Experience Manager, sans avoir à utiliser l’application de bureau [!UICONTROL Dynamic Media] Classic. Voir [Modification du mot de passe dans Dynamic Media](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#change-dm-password).
      * Pour en savoir plus sur les améliorations suivantes, voir [Nouveautés de Brand Portal](https://docs.adobe.com/content/help/fr-FR/experience-manager-brand-portal/using/introduction/whats-new.html).
         * Prévisualisation PDF améliorée avec l’intégration du SDK Adobe Document Cloud View.
         * Fonction de téléchargement en un clic.
         * Nouvelles configurations d’administration pour l’expérience de téléchargement.
   * **Adobe Experience Manager Commerce as a Cloud Service**

      * Composants principaux CIF version 1.3.0. Voir [Composants principaux CIF](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.3.0) pour en savoir plus.
      * La fonctionnalité de prévisualisation avec produit/catégorie pour les modèles de produit et de catégorie est désormais disponible. Elle permet aux utilisateurs professionnels/marketeurs dans AEM d’afficher des modèles de produit/catégorie avec des données réelles.
      * Page de propriétés ajoutée aux produits et catégories pour permettre aux utilisateurs professionnels d’accéder aux détails associés au SKU/ID de catégorie du produit.
      * Fonctionnalité de tri ajoutée à la console de produits pour permettre le tri des produits/catégories par nom ou par attribut de prix.
      * La fonctionnalité de recherche de produits a été ajoutée à [!UICONTROL Product Console].
   * **Cloud Manager**

      * [!UICONTROL L’audit du contenu] a été renommé [!UICONTROL Audit Expérience].
      * Le processus de création a été divisé en trois commandes Maven distinctes.
      * Si le clonage du référentiel git échoue, il sera tenté à nouveau jusqu’à trois fois.
   * **Cloud Readiness Analyzer**

      * Le Cloud Readiness Analyzer (CRA) dispose d’une console d’état de démarrage qui affiche un bouton **[!UICONTROL Générer un rapport]** explicite sur lequel l’utilisateur peut cliquer pour exécuter le CRA.
      * L’interface utilisateur du CRA affiche la progression pendant son exécution. Elle affiche les éléments analysés et les résultats trouvés pendant l’exécution.
      * Le rapport du CRA présente un résumé et le nombre de résultats sous forme de tableau organisé selon le type de résultats et le niveau d’importance. En cliquant sur le numéro de ce résultat, vous accédez automatiquement à l’emplacement de ce résultat dans le rapport.
   * **Outil de transfert de contenu**

      * L’outil de transfert de contenu (CTT) prend en charge le magasin de données Azure Blob Store.
      * L’interface utilisateur du CTT dispose d’une fonctionnalité de rechargement automatique qui recharge la page d’aperçu toutes les 30 secondes.
      * Bouton ajouté à l’interface utilisateur CTT pour récupérer facilement le jeton d’accès.
      * Ajout d’un message de validation descriptif pour l’*URL* et le *nom du jeu de migrations*.
   * **Outils de refactorisation du code**

      * Le plug-in AIO-CLI prend en charge Repository Modernizer et permet aux utilisateurs d’exécuter l’outil à l’aide du plug-in. Voir la [ressource Git : aio-cli-plugin-aem-cloud-service-migration](https://github.com/adobe/aio-cli-plugin-aem-cloud-service-migration) pour plus d’informations.
      * L’utilitaire Repository Modernizer peut être utilisé pour restructurer des packages de projets existants en packages compatibles avec la structure de projet définie pour AEM as a Cloud Service. Voir la [ressource Git : Repository Modernizer](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/repository-modernizer) pour plus d’informations.







Voir les [notes de mise à jour d’AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html).

### Auto-assistance

**[!DNL Experience Manager] Sites**

La documentation de l’Éditeur de texte enrichi est mise à jour afin de répertorier tous [les protocoles pris en charge pour les liens dans RTE](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/administering/operations/configure-rich-text-editor-plug-ins.html#linkstyles).

**[!DNL Experience Manager] Assets**

* Du nouveau contenu d’aide sur l’[accessibilité d’AEM Assets](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/assets/accessibility.html) à tous les utilisateurs est disponible.

* **[Le paramètre Viewmode](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/assets/using/search-assets.html#assetpicker)** est ajouté au sélecteur de ressources pour ouvrir le sélecteur de ressources en mode de recherche. Pour ouvrir le sélecteur de ressources en mode de recherche et l’utiliser avec `assettype` et `mimetype`, l’utilisateur doit ajouter un suffixe au paramètre `viewmode=search` dans l’URL `https://[aem-server]:[port]/aem/assetpicker.html`. Par exemple : `https://[aem-server]:[port]/aem/assetpicker.html?viewmode=search&assettype=images`.

* Les groupes d’utilisateurs associés du dossier privé sont supprimés lors de la [suppression du dossier privé](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/assets/managing/private-folder.html#delete-private-folder) et les groupes d’utilisateurs redondants, inutilisés et générés automatiquement existants peuvent être supprimés du référentiel à l’aide d’une méthode propre dans JMX.

* Le problème de connexion à l’application de bureau avec [Service Pack 6.5.5.0](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/release-notes/service-pack/previous-hotfixes-featurepacks.html#assets-6550) a été corrigé avec l’application de bureau version 2.0.3.2.

* Si les utilisateurs ont modifié [Apache Jackrabbit Oak TokenConfiguration](https://helpx.adobe.com/fr/experience-manager/kb/How-to-set-token-session-expiration-AEM.html) afin de définir la configuration du délai d’expiration sur une valeur inférieure au temps nécessaire au téléchargement d’une ressource, l’utilisateur peut alors rencontrer un problème de délai d’expiration de session. Par conséquent, les utilisateurs doivent modifier `chunkUploadMinFileSize` et `chunksize`, de sorte que chaque requête de bloc actualise la session. Pour plus d’informations, voir [Chargement de ressources](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/assets/managing/managing-assets-touch-ui.html#uploading-assets).

* Les ressources peuvent également être [déplacées dans des dossiers frères à l’aide de l’opération de glisser-déposer](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/assets/managing/managing-assets-touch-ui.html#moving-or-renaming-assets), à l’exception de l’opération [!UICONTROL Déplacer (m)] qui ouvre l’assistant [!UICONTROL Déplacer les ressources].

* Pour Assets Insights, utilisez [Adobe Launch](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/assets/advanced/asset-insights-launch-tutorial.html). [L’intégration à DTM](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/assets/managing/touch-ui-using-dtm-for-asset-insights.html) est appelée ‘méthode obsolète’ dans la documentation.

Mise à jour : **28/10/2020**

* **Améliorations de Brand Portal** : les nouvelles fonctionnalités suivantes, entre autres, sont disponibles dans [!DNL Brand Portal] :

   * [Expérience de téléchargement améliorée](https://docs.adobe.com/content/help/fr-FR/experience-manager-brand-portal/using/download/brand-portal-download-assets.html) pour des téléchargements rapides et simplifiés. D’autres configurations de téléchargement peuvent être configurées par les administrateurs pour offrir une expérience qui répond aux besoins des utilisateurs et des entreprises.
   * La navigation en un clic vers [!UICONTROL Fichiers], [Collections](https://docs.adobe.com/content/help/fr-FR/experience-manager-brand-portal/using/share/brand-portal-share-collection.html) et [!UICONTROL Liens partagés] est désormais possible à partir de n’importe quelle page.
   * Désormais, les utilisateurs peuvent [sélectionner et télécharger des rendus spécifiques](https://docs.adobe.com/content/help/fr-FR/experience-manager-brand-portal/using/download/brand-portal-download-assets.html#download-assets-from-asset-details-page). La nouvelle option de téléchargement de rendu est disponible dans le panneau [!UICONTROL Rendus] de la page Détails des actifs.
   * Un délai de 15 minutes pour les sessions d’utilisateurs invités garantit une meilleure expérience à tous les utilisateurs simultanés.

### [!DNL Experience Manager] Formulaires

La documentation relative aux fonctionnalités suivantes incluses dans la version 6.5.6.0 est disponible. Vous pouvez maintenant :

* Exécuter l’action de préremplissage de données du formulaire adaptatif au niveau du client. [Le préremplissage au niveau du client](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/forms/adaptive-forms-advanced-authoring/prepopulate-adaptive-form-fields.html) réduit considérablement le temps nécessaire à la fusion des données et au rendu d’un formulaire adaptatif.
* Utiliser l’[authentification mutuelle basée sur des certificats pour les services Web RESTful et SOAP](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/forms/form-data-model/configure-data-sources.html#mutual-authentication) dans un modèle de données de formulaire.
* Inclure les [paramètres régionaux en tant que sélecteur d’URL](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/forms/manage-administer-aem-forms/supporting-new-language-localization.html). L’utilisation d’un sélecteur d’URL permet de [mettre en cache les formulaires adaptatifs traduits](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/forms/install-aem-forms/configure-aem-forms/configure-adaptive-forms-cache.html) sur un dispatcher.
* Joindre [plusieurs fichiers au composant Pièce jointe](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/forms/getting-started/introduction-forms-authoring.html) des formulaires adaptatifs.

La documentation relative aux fonctionnalités suivantes, publiées pour le service de conversion automatisée pour Forms, est disponible. Vous pouvez maintenant :

* Utiliser des [PDF forms activés pour Adobe Sign](https://git.corp.adobe.com/AdobeDocs/aem-forms-automated-conversion-service.en/blob/master/help/frequently-asked-questions.md) avec le service. Si le PDF form source contient des balises de texte Adobe Sign, le service conserve toutes les informations associées à Adobe Sign pendant la conversion et associe les informations du signataire présentes dans le PDF source aux champs de formulaire adaptatif correspondants.

* Le service prend désormais en charge la [conversion de PDF forms en couleur en formulaires adaptatifs](https://docs.adobe.com/content/help/fr-FR/aem-forms-automated-conversion-service/using/release-notes.html).

### Mise à jour et documentation sur les feuilles de route [!DNL Adobe Experience Manager]

Publication d’une solution de documentation à guichet unique pour la feuille de route de la version Adobe Experience Manager, les mises à jour de version et les informations sur les modules complémentaires. Elle permet d’accéder plus facilement à de nombreux articles pertinents disponibles dans différents espaces AEM qui sont désormais centralisés. Elle comprend les articles importants suivants :

* [Feuille de route des versions d’AEM](https://docs.adobe.com/content/help/fr-FR/experience-manager-release-information/aem-release-updates/update-releases-roadmap.html) : répertorie les prochaines versions d’AEM as a Cloud Service et la version d’AEM avec Managed Services et On-Premise prise en charge.
* [Mises à jour des versions d’AEM](https://docs.adobe.com/content/help/fr-FR/experience-manager-release-information/aem-release-updates/aem-releases-updates.html) : répertorie les versions les plus récentes d’AEM as a Cloud Service et les versions d’AEM avec Managed Services et On-Premise prises en charge et vous dirige vers la documentation de ces versions.
* [Mises à jour d’Aem Forms](https://docs.adobe.com/content/help/fr-FR/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html) : répertorie les liens du package Distribution logicielle de tous les packages de modules complémentaires Forms publiés.

En outre, le référentiel comprend d’autres articles importants, tels que les [définitions des véhicules des mises à jour d’AEM](https://docs.adobe.com/content/help/fr-FR/experience-manager-release-information/aem-release-updates/update-release-vehicle-definitions.html) et les [dernières mises à jour de la documentation d’AEM](https://docs.adobe.com/content/help/fr-FR/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html).

### [!DNL Adobe Experience Manager] application de bureau 

* Les utilisateurs qui se connectent à l’application de bureau après s’être déconnectés ou qui se connectent pour la première fois doivent fournir l’URL de leur serveur [!DNL Experience Manager] au format `https://[aem-server-url]:[port]/`, puis sélectionner l’option [!UICONTROL Connexion], afin d’éviter l’erreur « L’application a rencontré une erreur inconnue ». Pour plus d’informations, voir [Utilisation de l’application de bureau Adobe Experience Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-desktop-app/using/using.html).

### Communauté

* **Annonce d’un nouveau processus d’envoi de demandes de fonctionnalités Experience Manager**

   Souhaitez-vous qu’une nouvelle fonctionnalité soit ajoutée à la feuille de route Experience Manager ? Adobe est heureux d’annoncer *FeatureBit* - un projet visant à améliorer la façon dont les clients et les partenaires demandent des améliorations de fonctionnalités (appelées RFE) à l’équipe produit Experience Manager. Pour en savoir plus, consultez la [communauté AEM Experience League](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/announcing-the-new-process-to-submit-experience-manager-feature/td-p/380425).

* **Le contenu AEM le plus récent sur Experience League**

   Il s’agit de la source officielle de contenu technique relatif à l’expérience digitale produit par Adobe. Voir la liste complète [ici](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156).

### Nouveaux cours et tutoriels sur Experience Manager

Mise à jour : **21 octobre 2020**

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 2 novembre 2020 | [Charger et déclencher un appel Target](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/target/load-and-fire-target.html) | Vidéo | Découvrez comment charger, transférer des paramètres à la demande de page et déclencher un appel Target à partir de la page de votre site à l’aide d’une règle Launch. Les informations de la page sont récupérées et transmises en tant que paramètres à l’aide de la couche de données client Adobe qui vous permet de collecter et de stocker des données sur l’expérience des visiteurs sur une page web, puis d’accéder facilement à ces données. |
| 28 octobre 2020 | [Balises intelligentes de vidéo](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/assets/metadata/video-smart-tags.html) | Vidéo | Les ressources d’Experience Manager utilisent Adobe Sensei pour baliser intelligemment les ressources vidéo avec des mots-clés qui décrivent les éléments clés de la vidéo, ce qui permet aux utilisateurs d’AEM de les trouver facilement avec une recherche par mots-clés. |
| 27 octobre 2020 | [Présentation d’AEM Document Security Extension for Microsoft Office](https://docs.adobe.com/content/help/fr-FR/experience-manager-document-security/using/document-security-extension-microsoft-office.html) | Article | Adobe Experience Manager Document Security Extension for Microsoft Office garantit que seules les personnes autorisées peuvent utiliser des fichiers Word, Excel et PowerPoint contenant votre propriété intellectuelle. En utilisant Document Security Extension for Microsoft Office, vous pouvez appliquer des paramètres de confidentialité prédéfinis à vos fichiers. |
| 7 octobre 2020 | [Mesures des pages de vue dans Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/analytics/create-analytics-workspace.html) | Article | Découvrez comment mapper les données capturées d’un site Adobe Experience Manager aux mesures et aux dimensions dans les suites de rapports Adobe Analytics. |
| 8 octobre 2020 | [Personnalisation des expériences de pages web complètes](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/target/personalization-web-page.html) | Vidéo | Découvrez comment créer une activité pour rediriger les pages de votre site hébergées sur AEM vers une nouvelle page à l’aide d’Adobe Target. |
| 8 octobre 2020 | [Personnalisation à l’aide du compositeur d’expérience visuelle](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/target/personalization-using-vec.html) | Vidéo | Découvrez comment créer une activité Target de test A/B à l’aide du compositeur d’expérience visuelle (VEC). |
| 14 septembre 2020 | [Créer une activité Target à l’aide d’offres de fragments d’expérience](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/target/create-target-activity.html) | Vidéo | Découvrez comment créer et tester une activité Adobe Target à l’aide d’offres de fragments d’expérience AEM. |
| 8 octobre 2020 | [Exporter le fragment d’expérience vers Adobe Target](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/target/export-experience-fragment-target.html) | Vidéo | Découvrez comment exporter un fragment d’expérience AEM en tant qu’offres Adobe Target. |
| 5 octobre 2020 | [Insérer une ligne dans la base de données à l’aide de la variable de modèle de données de formulaire](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/forms/variables-aem-workflow/form-data-model.html) | Vidéo | Les variables de type modèle de données de formulaire sont généralement utilisées pour insérer des lignes dans la source de données sous-jacente du modèle de données de formulaire. Cette vidéo explique les étapes nécessaires pour insérer une ligne dans la base de données à l’aide du processus AEM. |
| 28 septembre 2020 | [Authentification à deux facteurs à l’aide de SMS](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/forms/some-useful-integrations/two-factor-authentication.html) | Article | Effectuez la vérification OTP à l’aide d’un SMS dans vos formulaires adaptatifs. |
| 28 septembre 2020 | [Cours sur Asset Compute](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.asset.compute) | Cours | Ce cours explique comment étendre les microservices Asset Compute d’AEM as a Cloud Service! Vous devez désormais être en mesure de configurer, de développer, de tester, de déboguer et de déployer des objets Worker Asset Compute personnalisés pour une utilisation par votre service Auteur d’AEM as a Cloud Service. |
| 23 septembre 2020 | [Suivi des composants cliqués avec Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/analytics/track-clicked-component.html) | Article | Utilisez la couche de données client Adobe basée sur les événements pour collecter des données sur une page et sur les interactions utilisateur sur un site d’Adobe Experience Manager. Découvrez comment utiliser des règles dans Experience Platform Launch pour écouter ces événements et envoyer des données à une suite de rapports Adobe Analytics. |
| 25 septembre 2020 | [Intégrer les objets Worker Asset Compute aux profils de traitement AEM](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/deploy/processing-profiles.html) | Vidéo | AEM as a Cloud Service s’intègre aux objets Worker Asset Compute déployés sur Adobe I/O Runtime via les profils de traitement AEM Assets. Les profils de traitement sont configurés dans le service Auteur pour traiter des ressources spécifiques à l’aide d’objets Worker personnalisés et pour stocker les fichiers générés par les objets Worker en tant que rendus de ressources. |
| 25 septembre 2020 | [Déploiement sur Adobe I/O Runtime- Didacticiel](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/deploy/runtime.html) | Vidéo | Les projets Asset Compute, et les objets Worker qu’ils contiennent, doivent être déployés sur Adobe I/O Runtime pour être utilisés par AEM as a Cloud Service. |
| 25 septembre 2020 | [Débogage d’un objet Worker Asset Compute](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/asset-compute/test-debug/debug.html) | Article | Les objets Worker Asset Compute peuvent être débogués de plusieurs manières : des simples instructions du log de débogage au code VS joint en tant que débogueur distant, en passant par l’extraction des logs pour les activations dans Adobe I/O Runtime lancée depuis AEM as a Cloud Service. |
| 25 septembre 2020 | [Utilisation de l’outil de développement Asset Compute](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/develop/development-tool.html) | Article | L’outil de développement Asset Compute est un outil Web local qui permet aux développeurs de configurer et d’exécuter localement les objets Worker Asset Compute, en dehors du contexte du SDK AEM par rapport aux ressources Asset Compute dans Adobe I/O Runtime. |
| 27 septembre 2020 | [Développement d’un objet Worker Asset Compute](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/develop/worker.html) | Article | Les objets Worker Asset Compute sont au cœur d’une application Asset Compute, car ils fournissent des fonctionnalités personnalisées qui exécutent ou orchestrent, le travail effectué sur une ressource pour créer un rendu. |
| 25 septembre 2020 | [Configuration du fichier manifest.yml](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/develop/manifest.html) | Article | Le fichier manifest.yml du projet Asset Compute décrit tous les objets Worker de cette application à déployer. |
| 14 septembre 2020 | [Configuration des variables d’environnement](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/develop/environment-variables.html) | Vidéo | Les variables d’environnement sont conservées dans le fichier ‘.env’ pour le développement local et sont utilisées pour fournir des informations d’identification Adobe I/O et des informations d’identification de l’espace de stockage requises pour le développement local. |
| 14 septembre 2020 | [Création d’un projet Asset Compute](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/develop/project.html) | Article | Les applications Asset Compute sont des projets Node.js, générés à l’aide de l’interface de ligne de commande Adobe I/O CLI, qui adhèrent à une certaine structure leur permettant d’être déployés dans Adobe I/O Runtime et intégrés à AEM as a Cloud Service. |
| 14 septembre 2020 | [Configuration des variables d’environnement](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/develop/environment-variables.html) | Article | Les variables d’environnement sont conservées dans le fichier ‘.env’ pour le développement local et sont utilisées pour fournir des informations d’identification Adobe I/O et des informations d’identification de l’espace de stockage requises pour le développement local. |
| 14 septembre 2020 | [Création d’un projet Asset Compute](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/develop/project.html) | Vidéo | Les applications Asset Compute sont des projets Node.js, générés à l’aide de l’interface de ligne de commande Adobe I/O CLI, qui adhèrent à une certaine structure leur permettant d’être déployés dans Adobe I/O Runtime et intégrés à AEM as a Cloud Service. |
| 14 septembre 2020 | [Configuration d’Adobe I/O Project Firefly](https://docs.adobe.com/content/help/fr-FRexperience-manager-learn/cloud-service/asset-compute/set-up/firefly.html) | Tutoriel | Les applications Asset Compute sont des applications Adobe Project Firefly spécialement définies et, en tant que telles, nécessitent l’accès à Adobe Project Firefly dans Adobe Developer Console pour les configurer et les déployer. |
| 25 septembre 2020 | [Configuration d’un environnement de développement local](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/set-up/development-environment.html) | Article | Développer des objets Worker Asset Compute, qui sont des applications JavaScript Node.js, nécessite des outils de développement spécifiques qui diffèrent du développement AEM traditionnel, allant de Node.js et de divers modules npm à Docker Desktop et Microsoft Visual Studio Code. |
| 25 septembre 2020 | [Configuration des comptes et des services](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/set-up/accounts-and-services.html) | Article | Développer des objets Worker Asset Compute nécessite l’accès à des comptes et à des services, y compris AEM as a Cloud Service, Adobe Project Firefly et l’espace de stockage fourni par Microsoft ou Amazon. |
| 30 septembre 2020 | [Exploration de la couche de données client Adobe](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/adobe-client-data-layer/data-layer-overview.html) | Article | Explorez les fonctionnalités de la couche de données client Adobe basée sur les événements et de son intégration avec les composants principaux AEM Sites. Découvrez comment écouter les événements, obtenir l’état actuel et modifier la couche de données. |
| 30 septembre 2020 | [Présentation de la couche de données client Adobe](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/adobe-client-data-layer/data-layer-overview.html) | Vidéo | Découvrez comment la couche de données client Adobe orientée événement expose les données des composants principaux AEM Sites. Grâce à la couche de données client Adobe, les solutions de gestion des balises telles que Experience Platform Launch peuvent transmettre des données de site web à des applications telles qu’Analytics et Target. |
| 8 octobre 2020 | [Ajout de l’extension Target à la propriété Launch](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/target/add-target-launch-extension.html) | Vidéo | Découvrez comment charger, transférer des paramètres à la demande de page et déclencher un appel Target à partir de la page de votre site à l’aide d’une règle Launch. Les informations de la page sont récupérées et transmises en tant que paramètres à l’aide de la couche de données client Adobe qui vous permet de collecter et de stocker des données sur l’expérience des visiteurs sur une page web, puis d’accéder facilement à ces données. |
| 7 octobre 2020 | [Création d’un compte Cloud Service Adobe Target](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/target/setup-aem-target-cloud-service.html) | Vidéo | Découvrez comment intégrer Adobe Experience Manager en tant que Cloud Service à Adobe Target en utilisant l’authentification Cloud Service et Adobe IMS. |
| 2 octobre 2020 | [Présentation d’AEM et d’Adobe Target](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/sites/integrations/target/overview.html) | Vidéo | AEM et Target sont deux solutions puissantes avec des fonctionnalités qui semblent se chevaucher. Les clients ont parfois du mal à comprendre comment et quand utiliser ces produits conjointement pour offrir une expérience personnalisée. Afin d’offrir une expérience optimisée à chaque utilisateur final, différentes équipes de votre entreprise doivent travailler en étroite collaboration et définir qui fait quoi. |
| 2 octobre 2020 | [Intégration d’AEM Forms et Adobe Sign](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.2.forms) | Cours | Associés, Adobe Sign et AEM Forms vous permettent d’automatiser des transactions complexes et d’inclure des signatures électroniques sécurisées et légales dans le cadre d’une expérience digitale transparente. |
| 6 octobre 2020 | [Création d’un document interactif pour le canal d’impression](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.5.forms) | Cours | Interactive Communications centralise et gère la création, l’assemblage et la diffusion de correspondances sécurisées, personnalisées et interactives telles que la correspondance commerciale, les documents, les relevés, les avis de prestations sociales, les emails marketing, les factures et les kits de bienvenue. Ce cours présentera la création de divers composants qui constituent un document de communication interactif. |
| 10 octobre 2020 | [Prise en main d’AEM SPA Editor pour les développeurs](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.spaeditor) | Cours | Découvrez comment créer des applications à page unique (SPA) très performantes qui peuvent être créées dans AEM avec AEM SPA Editor. Ce cours couvre les principales tâches de développement de la création d’un nouveau projet SPA Editor à la création de composants personnalisés. Des cours équivalents sont fournis pour les frameworks Angular et React ; la plupart des développeurs devraient choisir un seul framework à utiliser. |
| 7 octobre 2020 | [Extensibilité des Asset Compute](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/asset-compute/overview.html) | Article | Tutoriel qui décrit la création d’un objet Worker de microservices de ressources personnalisé pour AEM as a Cloud Service. |
| 6 octobre 2020 | [Création de votre premier formulaire adaptatif](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.4.forms) | Cours | AEM Forms vous permet de créer des formulaires attrayants, réactifs, dynamiques et adaptatifs. Le cours débute avec la création d’un modèle de formulaire adaptatif personnalisé et vous guide tout au long du processus de création d’un formulaire adaptatif à l’aide des différents composants du formulaire. |
| 21 octobre 2020 | [Outils du Dispatcher local](https://docs.adobe.com/content/help/fr-FR/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Article | AEM Dispatcher est un module de serveur Web Apache HTTP qui fournit une couche de sécurité et de performances entre le réseau CDN et le niveau Publication dans AEM. Découvrez comment configurer le Dispatcher dans le cadre d’un environnement de développement local. |
| 14 octobre 2020 | [Prise en main d’AEM Sites pour les développeurs](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.2.guided) | Cours | Ce cours met à jour un [cours existant](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2019.2.guided) sur Experience League. |
| 7 octobre 2020 | [Structure de projet AEM](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | Vidéo | Cet article décrit les modifications requises pour que les projets Maven Adobe Experience Manager soient compatibles avec AEM as a Cloud Service, en veillant à ce qu’ils respectent la division entre contenu modifiable et non modifiable, à ce que les dépendances soient établies pour créer des déploiements déterministes non conflictuels et à ce qu’ils soient mis en package dans une structure déployable. |

### Informations de mise à jour d’Experience Manager

Toutes les notes de mise à jour d’Experience Manager sont conservées dans les pages suivantes :

* [Mises à jour et feuille de route d’Experience Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-release-information/aem-release-updates/home.html)
* [Informations de mise à jour d’AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/release-notes/home.html)
* [Notes de mise à jour d’AEM Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Notes de mise à jour du service de conversion automatisée de formulaires](https://docs.adobe.com/content/help/fr-FR/aem-forms-automated-conversion-service/using/release-notes.html)
* [Notes de mise à jour d’AEM 6.5 Service Pack](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/release-notes/service-pack/sp-release-notes.html).
* [Notes de mise à jour d’AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/fr-FR/experience-manager-64/release-notes/cfp-release-notes.html)
* [Notes de mise à jour de Dynamic Media AEM Assets](https://docs.adobe.com/content/help/fr-FR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notes de mise à jour d’AEM Brand Portal](https://docs.adobe.com/content/help/fr-FR/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Notes de mise à jour de l’application de bureau AEM](https://docs.adobe.com/content/help/fr-FR/experience-manager-desktop-app/using/release-notes.html)
* [Notes de mise à jour d’AEM Dispatcher](https://docs.adobe.com/content/help/fr-FR/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Notes de mise à jour d’Adobe Primetime](https://docs.adobe.com/content/help/fr-FR/primetime/release-notes/home.html)
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

#### Panneau de contrôle

* Configuration de sous-domaines à l’aide de CNAME - [En savoir plus](https://docs.adobe.com/content/help/fr-FR/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html#use-cnames)

* Améliorations de la surveillance des bases de données - [En savoir plus](https://docs.adobe.com/content/help/fr-FR/control-panel/using/performance-monitoring/database-monitoring.html)

### Nouveaux cours et tutoriels sur Campaign

Nouveaux tutoriels, vidéos ou cours publiés le mois dernier.

| Publication | Nom | Solution | Description |
| ----------- | ----------- | ---------- | ---------- |
| 2 novembre 2020 | [Panneau de contrôle - Générer une clé SSH - Vidéo sur les fonctionnalités](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/control-panel/sftp-management/generate-ssh-key.html) | Campaign Classic | Découvrez comment générer une clé SSH à l’aide d’un terminal et comment stocker la version publique de la clé dans le panneau de contrôle. |
| 2 novembre 2020 | [Panneau de contrôle - Connexion à un serveur SFTP - Vidéo sur les fonctionnalités](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/control-panel/sftp-management/connect-to-sftp-server.html) | Campaign Classic | Découvrez comment se connecter à un serveur SFTP à l’aide d’une application SFTP cliente, avec les clés que vous avez stockées dans le panneau de contrôle. |
| 20 octobre 2020 | [Panneau de contrôle - Prise en main du panneau de contrôle - Article](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/control-panel/getting-started-with-the-control-panel.html) | Campaign Classic | Cet article explique comment accéder au panneau de contrôle et présente les conditions préalables requises pour pouvoir l’utiliser. |
| 20 octobre 2020 | [Panneau de contrôle - Prise en main du panneau de contrôle - Article](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/control-panel/getting-started-with-the-control-panel.html) | Campaign Standard | Cet article explique comment accéder au panneau de contrôle et présente les conditions préalables requises pour pouvoir l’utiliser. |
| 19 octobre 2020 | [Panneau de contrôle- Ajout d’une plage d’adresses IP à la liste autorisée](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/control-panel/sftp-management/adding-ip-range-to-allow-list.html) | Campaign Classic | Découvrez comment ajouter une plage d’adresses IP à la liste autorisée du panneau de contrôle. |
| 19 octobre 2020 | [Panneau de contrôle- Ajout d’une plage d’adresses IP à la liste autorisée](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/control-panel/sftp-management/adding-ip-range-to-allow-list.html) | Campaign Standard | Découvrez comment ajouter une plage d’adresses IP à la liste autorisée du panneau de contrôle. |
| 16 octobre 2020 | [Panneau de contrôle - Délégation de sous-domaines à l’aide de CNAME (bêta) - Vidéo sur les fonctionnalités](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/control-panel/subdomains-and-certificates/delegating-subdomains-using-cname.html) | Campaign Classic | Découvrez comment configurer et envoyer un sous-domaine à l’aide de CNAME dans le panneau de contrôle. |
| 16 octobre 2020 | [Panneau de contrôle - Délégation de sous-domaines à l’aide de CNAME (bêta) - Vidéo sur les fonctionnalités](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/control-panel/subdomains-and-certificates/delegating-subdomains-using-cname.html) | Campaign Standard | Découvrez comment configurer et envoyer un sous-domaine à l’aide de CNAME dans le panneau de contrôle. |

### Ressources d’aide

* Adobe Campaign Standard : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/campaign-standard-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/overview.html) - [Calendrier des versions](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-planning.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic : [Centre d’aide](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/campaign-classic-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.html) - [Tutoriels vidéo](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/tutorials/overview.html) - [Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/documentation-updates.html)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/control-panel/using/release-notes.html) - Tutoriels vidéo pour [Campaign Standard](https://docs.adobe.com/content/help/fr-FR/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/fr-FR/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icône](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notes de mise à jour d’Adobe Advertising Cloud.

* [Nouvelles fonctionnalités dans Advertising Cloud DSP](#adcloud-dsp)
* [Nouvelles fonctionnalités dans Advertising Cloud Search](#adcloud-search)

### Nouvelles fonctionnalités d’[!DNL Advertising Cloud DSP] {#adcloud-dsp}

Mise à jour : 28 octobre 2020

| Fonctionnalité | Description |
| -----------| ---------- |
| Nouveau  Aide | (Version du 28 octobre) L’aide héritée a été remplacée par des pages mises à jour, disponibles à partir du lien ‘Aide’ dans le menu principal DSP et également disponibles à tout moment depuis [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html) |
| Campagnes | (Version du 28 octobre) Les précédentes vues bêta des campagnes sont désormais les vues par défaut des campagnes, ce qui permet d’obtenir des informations plus rapides, de simplifier les workflows et de personnaliser les vues. |
| Inventaire privé | (Version du 15 octobre) Tous les utilisateurs peuvent désormais configurer et modifier les détails de l’ID de la transaction en utilisant un nouveau formulaire d’ID de transaction, qui est une version simplifiée de l’ancien formulaire [!UICONTROL Smart Ad Serving]. Pour configurer les détails de l’ID de la nouvelle transaction, accédez à **[!UICONTROL Inventaire > Transactions]**, cliquez sur **[!UICONTROL Créer]**, puis sur **[!UICONTROL ID de transaction bêta]**. |
| Prévisions de placement | (Version du 15 octobre) Pour les placements avec une fréquence de placement, la section [!UICONTROL Prévision] des paramètres de placement inclut une nouvelle section [!UICONTROL Maximums estimés], qui indique la capacité supplémentaire disponible avec la configuration de ciblage actuelle. |

### Nouvelles fonctionnalités d’[!DNL Advertising Cloud Search] {#adcloud-search}

Date de publication : **17 octobre 2020**

| Fonctionnalité | Description |
| -----------| ---------- |
| Rechercher dans les campagnes | Dans la vue [!UICONTROL Comptes], la colonne [!UICONTROL Accès] vous informe désormais lorsqu’[!DNL Advertising Cloud Search] ne parvient pas à se connecter à un compte de moteur de recherche activé. Pour connaître la cause de l’erreur, placez le curseur sur l’icône d’avertissement. |
| [!UICONTROL Alertes personnalisées] | L’ancienne version [!UICONTROL bêta des alertes] s’appelle désormais [!UICONTROL Alertes personnalisées]. |
|  | Dans les alertes personnalisées, le workflow d’identification de l’augmentation ou de la diminution des mesures pour la période spécifiée par rapport aux mesures de la période précédente a été simplifié et déplacé vers l’onglet [!UICONTROL Filtres]. |

## ![Icône](/assets/magento.png) [!DNL Magento] {#magento}

Pour les notes de mise à jour de Magento, veuillez consulter :

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![Icône](/assets/target.png)[!DNL Target] {#target}

Voir les [[!DNL Target] notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html) pour consulter les informations les plus récentes.

### Nouveaux cours et tutoriels d’Adobe Target

Mise à jour : **2 novembre 2020**

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 11 octobre 2020 | [Modèle de déploiement de la personnalisation hybride](https://docs.adobe.com/content/help/fr-FR/target-learn/tutorials/implementation/hybrid-deployment.html) | Vidéo | Adobe Target offre un modèle de déploiement hybride unique de la personnalisation, mélange des implémentations côté client et côté serveur. Ce modèle hybride permet aux utilisateurs non spécialistes de créer une expérience ou une activité de personnalisation à l’aide du compositeur d’expérience visuelle WYSIWYG et de bénéficier d’une exécution, d’une diffusion et d’un rendu de l’expérience par le serveur pour une diffusion extrêmement performante. |

## ![Icône](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] est une application complète pour la gestion des pistes et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en s’engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Voir les [notes de mise à jour](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+July+%2720) [!DNL Marketo] pour consulter les informations les plus récentes.

### Fonctionnalités à venir

Les fonctionnalités suivantes seront publiées tout au long du trimestre :

| Fonctionnalité | Description |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Nouvelle segmentation basée sur un compte</li><li>Enregistrement des filtres spécifiques au tableau de bord</li><li>Exportation de tableaux de bord Bizible au format PDF</li></ul> |
| Connect de ventes | Composition des mises à jour/améliorations des fenêtres et du Centre de commandes. |

### Dépréciations

* **Paramètre de l’API de ressource &quot;_method&quot; :** après septembre 2020, les points de fin d’API d’actif n’accepteront plus `_method` pour transmettre les paramètres de requête dans un corps POST afin de contourner les limitations de longueur d’URI.
* **Dépréciation de la prise en charge d’Internet Explorer :** à compter de la version du 31 juillet 2020, l’interface utilisateur de Marketo Engage ne sera plus prise en charge dans Internet Explorer.

Pour obtenir des notes de mise à jour cumulatives et historiques, reportez-vous à la page [Notes de mise à jour de Marketo](https://docs.marketo.com/x/CgA6Ag).

## ![Icône](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Informations sur les mises à jour et ressources d’aide pour Adobe Document Cloud.

### Nouveaux cours et tutoriels d’Adobe Sign

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Document Cloud.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 29 septembre 2020 | [Présentation rapide d’Adobe Sign](https://docs.adobe.com/content/help/fr-FR/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/quick-tour.html) | Vidéo | Dans cette vidéo, nous allons vous présenter rapidement Adobe Sign en commençant par l’écran d’accueil. |

Pour obtenir de l’aide sur Document Cloud, voir :

* [Hub d’apprentissage Adobe Acrobat](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=en)
* [Hub d’apprentissage Adobe Sign](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=en)
* [Formation et assistance pour Document Cloud](https://helpx.adobe.com/fr/support/document-cloud.html)

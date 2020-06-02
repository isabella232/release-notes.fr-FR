---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 02f473e0c7908d44aa0444ce99f4540d9e79b254
workflow-type: tm+mt
source-wordcount: '5368'
ht-degree: 86%

---


# Notes de mise à jour d’Adobe Experience Cloud - Mai 2020

![Bannière](/assets/experience-cloud-banner-3.png)

Cette page fournit de nouvelles fonctionnalités, des correctifs et des avis importants dans [!DNL Adobe Experience Cloud]. Les dates de publication de la solution peuvent varier. Consultez régulièrement les dernières mises à jour.

>[!NOTE]
>
>Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) pour être averti par e-mail de la publication des prochaines versions.

**Date de publication : mai 2020**

Dernière mise à jour : **2 juin 2020**

* [État du système Adobe](#status)
* [Interface d’Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**Mise à jour le 2 juin 2020**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html) (liens vers la page d’aide de Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/fr/primetime/user-guide.html) (liens vers la page d’aide de Primetime)

Besoin d’aide ? Visitez [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) pour trouver des cours organisés par Adobe, de la documentation technique, des réponses rapides, des informations de la communauté et des formations dirigées par un instructeur.

## ![Icône](/assets/adobe.png) État du système Adobe {#status}

[!UICONTROL État du système Adobe] fournit des informations détaillées, des mises à jour d’état et des notifications par e-mail relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

Date de mise à jour : **21 mai 2020**

**Nouveautés**

* Avec votre Adobe ID, vous pouvez vous abonner à des notifications d’événement avec plus de granularité et associées au niveau de l’offre de produit et des modules complémentaires. Pour vous aider à configurer votre abonnement plus rapidement, le processus d’auto-abonnement recommande désormais une sélection de produits et d’offres en fonction de vos droits sur les produits. Cela devrait réduire le nombre d’emails que vous recevez et fournir des notifications plus pertinentes dans votre boîte de réception. Rendez-vous sur [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nouvelles fonctionnalités et améliorations disponibles dès maintenant**

| Fonction | Description |
| -----------| ---------- |
| Amélioration de l’expérience utilisateur pour les abonnements et les notifications | <ul><li>Les emplacements régionaux [!DNL Marketo Engage] sont désormais filtrés en fonction de la liste des offres de produits sélectionnées.</li><li>[!DNL Marketo Engage] les notifications par courrier électronique sont pertinentes pour la région, l’emplacement et les préférences d’environnement de l’utilisateur.</li></ul> |
| Confirmation d’abonnement à l’événement | <ul><li>Vous pouvez désormais obtenir une confirmation par e-mail lorsque vous vous abonnez à des mises à jour à un événement unique en cours.</li></ul> |
| Améliorations de la convivialité de la navigation globale | <ul><li>Expérience de l’utilisateur cohérente avec `Adobe.com` dans le menu de navigation de niveau supérieur.</li></ul> |

## ![Icône](/assets/ec_appicon_24.png) Interface d’Experience Cloud {#ecloud}

Mises à jour générales de l’interface d’Experience Cloud.

**Domaine de produit unifié**

Adobe a mis à jour l’en-tête de domaine et d’interface afin d’unifier et d’améliorer votre expérience dans toutes les applications Experience Cloud. Ces améliorations sont conçues pour fluidifier votre utilisation de manière simple, mais importante. Ces améliorations ne modifient pas vos processus actuels.

Les mises à jour comprennent les éléments suivants :

* Nouvelles URL d’application : `experience.adobe.com/<application name>` :
   * À terme, tous les produits adopteront ce modèle d’URL. Recherchez de nouvelles URL pour qu’elles prennent effet tout au long du mois.
   * Navigateurs pris en charge : [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] et [!DNL Opera] (versions les plus récentes). **Remarque** : bien que l’interface d’Experience Cloud prenne en charge ces navigateurs, les applications individuelles peuvent ne pas tous les prendre en charge. (Par exemple, [Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/admin/sys-reqs.html) ne prend pas en charge [!DNL Opera] et [Target](https://docs.adobe.com/help/fr-FR/target/using/implement-target/before-implement/supported-browsers.html) ne prend pas en charge [!DNL Safari].)
   * ([!DNL Safari] uniquement) Le changement de domaine peut entraîner des problèmes de cookies dans [!DNL Safari]. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité de [!DNL Safari], vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Experience Cloud de fonctionner sur ce nouveau domaine.
* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide des produits : [!UICONTROL Experience League] est intégré dans le produit afin qu’une recherche d’aide comprenne également les résultats des forums de la communauté et du contenu vidéo. Cette modification simplifie l’accès à davantage de contenu et vous permet de tirer le meilleur parti d’Experience Cloud. De plus, vous pouvez cliquer sur **[!UICONTROL Aide]** > **[!UICONTROL Commentaires]** pour signaler des problèmes ou partager vos idées avec Adobe.

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
| Panneau de configuration d’Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Distribution logicielle | `experience.adobe.com/downloads` |
| Admin Tool (Outil d’administration) (bêta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Le panorama et les collections]**, un filtre hérité dans le sélecteur de ressources  Marketing Cloud, est en cours de désaffectation.

## ![Icône](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notes de mise à jour d’[!DNL Experience Platform,] y compris d’[!DNL Experience Platform Launch,] de [!UICONTROL Journey Orchestration], des services [!UICONTROL Offres], [!UICONTROL Personnes], [!UICONTROL Places], et [!UICONTROL Mobile Services], et des bulletins de sécurité.

### Améliorations de l’interface

Mise à jour : **15 mai 2020**

[!DNL Adobe Experience Platform] publie des mises à jour sur la barre de domaine et d’en-tête afin d’améliorer votre expérience et de réaliser l’union avec d’autres applications Experience Cloud. Les mises à jour comprennent les éléments suivants :

* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide à l’utilisateur, y compris les articles présentés et la documentation contextuelle dans le menu Aide.
* Capacité à fournir des commentaires sur Experience Platform et les tickets d’assistance pour les fichiers.

Voir les [Notes de mise à jour d’Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) pour plus d’informations.

### Attributs du client - nouvelle documentation

Mise à jour : **15 mai 2020**

* [Prise en charge des attributs du client pour le CCPA](https://docs.adobe.com/content/help/fr-FR/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Prise en charge des attributs du client pour le RGPD](https://docs.adobe.com/content/help/fr-FR/core-services/interface/customer-attributes/gdpr.translate.html) (Règlement général sur la protection des données)

### Orchestration du parcours {#journey}

Grâce à Adobe Experience Platform, orchestrez des parcours clients individuels à l’échelle sur des canaux d’expérience en anticipant de manière intelligente les besoins de chaque individu en temps réel, quel que soit l’endroit où leur parcours les mène.

* [Documentation](https://docs.adobe.com/content/help/fr-FR/journeys/using/journey-orchestration-home.html)
* [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html)
* [Vidéos pratiques](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Informations supplémentaires sur la mise à jour d’Experience Platform

* [Notes de mise à jour d’Experience Platform Launch](https://docs.adobe.com/content/help/fr-FR/launch/using/intro/release-notes/current.html)
* [Notes de mise à jour d’Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/fr/security.html) (Tous les produits Adobe)

## ![Icône](/assets/analytics.png) [!DNL Analytics] {#analytics}

Updated **May 29, 2020**

* [Nouvelles fonctionnalités dans Customer Journey Analytics](#cust-journey)
* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features) (**Updated June 2, 2020**)
* [Nouvelles fonctionnalités de Media Analytics](#media-aa) (**Mis à jour le 29 mai 2020**)
* [Avis importants à l’intention des administrateurs](#aa-notices) d’Analytics (**Mis à jour le 1er juin 2020**)
* [Correctifs](#aa-fixes) d’Adobe Analytics (**Mis à jour le 21 mai 2020**)
* [AppMeasurement](#appm)
* [Nouveaux tutoriels Analytics](#tutorials-analytics)

### Nouvelles fonctionnalités dans Customer Journey Analytics {#cust-journey}

| Fonction | Description |
| -----------| ---------- |
| [!UICONTROL Customer Journey Analytics] : Disponibilité globale | rend [!UICONTROL Customer Journey Analytics] disponible pour les clients des zones EMEA et APAC. |
| [!UICONTROL Customer Journey Analytics] : Prise en charge des [!UICONTROL sandbox Adobe Experience Platform] | Permet de sélectionner des [!UICONTROL sandbox Adobe Experience Platform] spécifiques à partir desquelles créer des connexions CJA. [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics-platform/using/cja-connections/create-connection.translate.html) |

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

<!--First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| Fonction | Date de disponibilité générale | Description |
| -----------| ------------ | ---------- |
| API d&#39;insertion de données en masse | 31 mai 2020 | Permet d’assimiler facilement et indépendamment des lots de données Analytics. Utile pour les données côté serveur et hors ligne. [En savoir plus...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) |
| Prise en charge d’Analytics pour [!UICONTROL Adobe Experience Platform Edge Network] | 31 mai 2020 | Permet d’utiliser une balise unique pour envoyer des données à plusieurs solutions Adobe, telles qu’Adobe Analytics, Adobe Target, Adobe Audience Manager, Adobe Experience Platform Data Lake, Unified Profile et Experience Cloud ID Service. [En savoir plus...](https://docs.adobe.com/content/help/en/experience-platform/edge/solutions/analytics/analytics-overview.html) |
| [!UICONTROL Tableaux de bord Adobe Analytics] | 31 mai 2020 | Les [!UICONTROL tableaux de bord Adobe Analytics] constituent une application mobile qui permet aux utilisateurs, à tout moment et en tout lieu, d’accéder aux informations d’Adobe Analytics. Cette application est destinée aux cadres qui recherchent un accès en ligne à des mesures clés. Elle permet d’accéder à des cartes de performance interactives et organisées et sera disponible pour les systèmes d’exploitation iOS et Android. [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/mobapp/home.translate.html) |
| [!UICONTROL Espace de travail]: Créer automatiquement les tables [à structure libre] du 21 mai 2020 ! UICONTROL depuis un état vide | Précédemment, vous ne pouviez pas déplacer des composants directement dans un projet ou un panneau vierge, vous deviez d’abord ajouter un [!UICONTROL Tableau à structure libre]. Vous pouvez désormais déplacer des composants directement dans un projet ou un panneau vierge, ce qui entraînera alors la création pour vous d’un [!UICONTROL Tableau à structure libre] au format recommandé. De plus, des améliorations ont été apportées à la manière dont les types de composants mixtes (par exemple, les dimensions et les mesures) sont traités lorsqu’ils sont déplacés simultanément dans un Tableau à structure libre. |
| [!UICONTROL Package] Adobe Analytics ajouté à la page Niveau [!UICONTROL d’accès aux] fonctionnalités | 21 mai 2020 | Vous pouvez désormais vue à quel module  Adobe Analytics (SKU) votre société a droit dans **[!UICONTROL Admin]** > Paramètres **[!UICONTROL de]** Société > Niveau d’accès aux **[!UICONTROL fonctionnalités.]** |
| Améliorations de l’accessibilité | 21 mai 2020 | L’équipe Adobe Analytics a apporté plusieurs améliorations d’accessibilité à Analyse Workspace, notamment une amélioration de la navigation au clavier, du contraste de couleur et de la prise en charge des lecteurs d’écran. |

#### New features in [!UICONTROL Media Analytics] {#media-aa}

Date de mise à jour : **29 mai 2020**

**Suivi de l&#39;état du lecteur :** [!UICONTROL Les clients Media Analytics] peuvent capturer l’interaction de la visionneuse au cours de la lecture à l’aide d’un ensemble standard de variables de solution pour le mode Plein écran, le sous-titrage, le mode silencieux, l’image dans l’image et la mise au point. Vous pouvez également créer des états de lecteur personnalisés. Les variables de suivi d’état du lecteur sont désormais disponibles pour le rapports dans [!UICONTROL Analyse Workspace]. Cette fonctionnalité nécessite l’une des fonctionnalités suivantes :

* Media [!DNL JavaScript] SDK 3.0 ou version ultérieure
* Utilisation avec le SDK [!DNL Adobe Experience Platform] (AEP) :
   * [!UICONTROL Media Analytics Extension] (pour le Web) : [!UICONTROL Adobe Media Analytics] (SDK 3.x) pour Audio et Video v1.0 ou version ultérieure
   * [!UICONTROL Extension] Media Analytics (pour mobile) : [!UICONTROL Adobe Media Analytics pour l’audio] et la vidéo v2.0 ou ultérieure
* [!UICONTROL Collection multimédia]

Voir [A propos du suivi](https://docs.adobe.com/content/help/en/media-analytics/using/player-state-tracking/player-state-overview.html)d’état du lecteur.

#### Correctifs Adobe Analytics {#aa-fixes}

* Adobe a modifié la mesure [!UICONTROL Durée de la visite] pour ne jamais inclure &quot;Non spécifié&quot; dans le calcul. Cela signifie que, que l’interface utilisateur dise d’inclure &quot;Non spécifié&quot;, nous faisons une exception spéciale pour toujours exclure &quot;Non spécifié&quot; dans le calcul de la [!UICONTROL durée de la visite] . Par conséquent, même si vous avez configuré un rapport contenant la mesure [!UICONTROL Durée de la visite] pour inclure &quot;Non spécifié&quot;, il renvoie toujours 0 temps passé pour l’élément de ligne &quot;Non spécifié&quot;. Notez que cela peut modifier le rapports historique dans les rapports et analyses ainsi que l’API de Rapports v1.4. (AN-197958)
* Correction d’un problème en raison duquel l’instance, la visite ou le Visiteur n’était pas comptabilisé dans le dénominateur pour les mesures [!UICONTROL Durée de la visite] .  Cela se produit lorsqu’un accès sans valeur pour la dimension (par exemple, [!UICONTROL Nom]de page) est suivi dans la même seconde. (AN-211074)
* Correction d’un problème entraînant l’absence de données de segment [!DNL Analytics] dans Audience Manager. (AN-206221)
* Correction d’un problème concernant le traitement des [!UICONTROL sources de données] qui affichait les mauvaises dates. (AN-213604)
* Correction d’un problème empêchant le chargement correct des fichiers de classification vers le FTP. (AN-214102)
* Correction d’un problème empêchant le renvoi d’une réponse complète avec la méthode d’API `Segments.Get`. (AN-206210)
* Correction d’un problème qui entraînait la conversion des éléments de ligne d’un tableau en caractères spéciaux lors d’un téléchargement au format PDF [!DNL Workspace]. (AN-196153)
* Correction du mauvais fonctionnement de l’appel d’API Adobe Analytics 1.4 `visattrcustomeridcustomerattributes`. (AN-186873)
* Correction d’un problème qui entraînait l’apparition de données dans les rapports qui n’apparaissaient pas dans le [!UICONTROL Flux de données]. (AN-211923)
* Correction d’un problème qui empêchait la copie des autorisations [!UICONTROL Profil de produit]. (AN-211113)
* Correction d’un problème qui empêchait les utilisateurs possédant des Federated ID de se connecter au [!UICONTROL Report Builder]. (AN-207750)
* Correction d’un problème d’affichage des données [!UICONTROL AdWords] dans [!UICONTROL Advertising Analytics]. (AN-213249)
* Correction d’un problème qui empêchait l’affichage des données de classification dans la vue de tendance. (AN-212761)
* Correction d’un problème qui provoquait un nombre de segments publié incorrect dans le [!UICONTROL Gestionnaire de segments]. (AN-213374)
* Correction d’un problème lié à l’option **[!UICONTROL Afficher la tendance à la hausse en tant que...]** dans l’[!UICONTROL éditeur de mesures] calculées : elle ne fonctionnait pas lors de l’application de filtres. (AN-214223)
* Correction de plusieurs problèmes liés à l’importation et à l’exportation de [!UICONTROL classifications]. (AN-213488, AN-215309, AN-216345, AN-215307, AN-216671)
* Correction de plusieurs problèmes avec le [!UICONTROL Créateur de règles de classification]. (AN-213826, AN-213550, AN-213095)
* Correction de problèmes liés au traitement des [!UICONTROL sources de données]. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911, AN-217551, AN-217947, AN-219018, AN-214691, AN-218401)
* Correction de problèmes de connectivité FTP. (AN-115525)
* Correction de plusieurs problèmes de [!DNL Analytics] [!UICONTROL flux de données]. (AN-176769, AN-160480, AN-211923, AN-204286, AN-212977, AN-214528, AN-215080, AN-217784, AN-219093, AN-218817, AN-217798, AN-218267, AN-218382)
* Correction de problèmes liés aux requêtes [!UICONTROL Data Warehouse]. (AN-181836)
* Correction de problèmes dans les projets [!UICONTROL Workspace] téléchargés au format PDF, en raison desquels les valeurs étaient converties en caractères spéciaux. (AN-196153)
* Correction d’un problème qui empêchait la copie des autorisations [!UICONTROL Profil de produit] dans [!UICONTROL Admin Console]. (AN-211113)
* Correction d’un problème en raison duquel les formats de temps dans les mesures calculées étaient rompus pour les valeurs négatives. (AN-210900)
* Correction d’un problème qui empêchait les utilisateurs de modifier le [!UICONTROL modèle d’ attribution] sur les mesures de lignes statiques. (AN-207872)
* Correction d’un problème en raison duquel le créateur de [!UICONTROL rapports planifiés] restait bloqué dans un état de file d’attente. (AN-215317)
* Correction du [!UICONTROL connecteur de données ExactTarget]. (AN-210794)
* Correction de problèmes de latence dans l’[!UICONTROL API d’importation en masse]. (AN-210165)
* Correction d’un problème en raison duquel les utilisateurs ne pouvaient pas se connecter à [!UICONTROL Report Builder] avec un Federated ID. (AN-207750)
* Correction d’un problème dans [!UICONTROL Advertising Analytics] qui empêchait l’affichage des données [!DNL Google AdWords]. (AN-213249)
* Correction d’un problème qui empêchait l’affichage des événements [!UICONTROL Workspace] [!UICONTROL Project Viewed] dans les journaux. (AN-214134)
* Correction d’un problème qui se produisait lors de la modification de la plage de dates dans [!UICONTROL Workspace] et de la sélection de l’option **[!UICONTROL Appliquer à tous les panneaux]**. La date n’a pas été modifiée dans certains panneaux. (AN-214944)
* Correction d’un problème en raison duquel il n’était pas possible de créer ou de modifier des alertes. (AN-215920)
* Correction d’un problème en raison duquel toutes les plages de dates dynamiques de [!UICONTROL Workspace] affichaient des dates incorrectes en raison du premier jour de la semaine passant sporadiquement d’un lundi à un dimanche. (AN-218835)

#### Correctifs Adobe Analytics supplémentaires

AN-101871, AN-115525 ; AN-123869 ; AN-152580 ; AN-160480 ; AN-178128 ; AN-186907 ; AN-199299 ; AN-201342 ; AN-201397 ; AN-204286 ; AN-204518 ; AN-206045 ; AN-206948 ; AN-208607 ; AN-209486 ; AN-210743 ; AN-211550 ; AN-211539 ; AN-211826 ; AN-211943 ; AN-212130 ; AN-212151 ; AN-212653 ; AN-212673 ; AN-212709 ; AN-212833 ; AN-212961 ; AN-212977 ; AN-213095 ; AN-213422 ; AN-213450 ; AN-213490 ; AN-213752 ; AN-213827 ; AN-214094 ; AN-214153 ; AN-214214 ; AN-214234 ; AN-214253 ;  AN-214255 ; AN-214343 ; AN-214355 ; AN-214401 ; AN-214427 ; AN-214528 ; AN-214642 ; AN-214691 ; AN-214772 ; AN-214793 ; AN-214924 ; AN-215017 ; AN-215080 ; AN-215212 ; AN-215312 ; AN-215377 ; AN-215402 ; AN-215545 ; AN-215905 ; AN-215963 ; AN-216447 ; AN-216676 ; AN-216880 ; AN-216999 ; AN-217245 ; AN-218450 ; AN-218899 ; AN-219487 ; AN-219677

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Migration vers un domaine de produit unifié | Date d&#39;entrée en vigueur : 28 mai 2020 | La migration vers un domaine de produits unifié pour Adobe Analytics, qui a commencé en janvier 2020, s’est terminée le 28 mai 2020. Adobe Analytics tente de supprimer toutes les références de `omniture.com` domaine de son architecture, mais il est important de créer une liste blanche `omniture.com` en tant que cookie tiers. Une fois la migration complète de l&#39;architecture terminée, nous vous en informerons par le biais des notes de mise à jour et cette étape de liste blanche ne sera plus nécessaire. [Voici](https://helpx.adobe.com/analytics/kb/adobe-ip-addresses.html) une liste complète des adresses et domaines IP recommandés que vous devez mettre en liste blanche.<br>Si votre entreprise bloque les cookies tiers, contactez le service d’assistance clientèle pour regagner votre accès à Adobe Analytics. |
| Nouveau landing page par défaut Adobe Analytics | Date d&#39;entrée en vigueur : 18 juin 2020 | Le 18 juin 2020, le landing page par défaut pour Adobe Analytics passera de [!UICONTROL Rapports] à [!UICONTROL Espace de travail]. Cette modification se produira pour tous les utilisateurs qui n’ont pas défini de landing page personnalisé auparavant. |
| Liste blanche des technologies tierces | (Date d&#39;entrée en vigueur : 12 mars 2020 | Adobe Analytics a commencé à tirer parti des technologies tierces pour la gestion du déploiement de fonctionnalités et la prise en charge des produits. Les URL suivantes doivent être ajoutées aux listes blanches de pare-feu réseau nécessaires pour garantir un accès complet aux fonctionnalités :<ul><li>Gainsight : https://esp.aptrinsic.com</li><li>LaunchDarkly : https://app.launchdarkly.com</li></ul> |
| Amélioration de la redondance pour la disponibilité de l’espace de travail d’Analyse | 21 mai 2020 | Afin d’assurer la disponibilité d’Analyse Workspace, nous ajoutons un CDN secondaire (Content Diffusion Network) pour une redondance améliorée. Les URL suivantes doivent être ajoutées aux listes blanches de pare-feu réseau nécessaires :<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Modification du mode de calcul des [!UICONTROL entrées/sorties] dans [!UICONTROL Workspace] | 7 avril 2020 | Dans [!UICONTROL Analysis Workspace], depuis mars 2020, nous avons modifié la manière dont la valeur _Aucun_ interagit avec les [!UICONTROL entrées/sorties]. Comme vous pouvez désormais activer et désactiver l’option _Aucun_ dans [!UICONTROL Analysis Workspace], nous appliquons l’option _Aucun_ après l’entrée ou la sortie, alors que (pour les eVars) elle était appliquée avant l’entrée ou la sortie. Supposons, par exemple, que le premier accès d’une visite n’ait aucune valeur pour eVars, contrairement au second accès. Dans [!UICONTROL Reports &amp; Analytics], le premier accès s’affichera comme _Non spécifié_ pour l’entrée, mais dans [!UICONTROL Analysis Workspace], il affichera la valeur pour le second accès. |
| Abandon du paramètre **[!UICONTROL Niveau de conversion]** | 3 mars 2020 | Le paramètre [Niveau de conversion](https://docs.adobe.com/content/help/fr-FR/analytics/admin/admin-tools/general-acct-settings-admin.html) qui ne fonctionnait pas dans **[!UICONTROL Outils d’administration]** > **[!UICONTROL Suite de rapports]** > **[!UICONTROL Paramètres du compte général]** sera supprimé de l’interface le 12 mars 2020. |
| Abandon de l’**[!UICONTROL archive de tableau de bord]** | 27 mars 2020 | Le paramètre **[!UICONTROL Afficher l’archive]** sous **[!UICONTROL Gérer les tableaux de bord]** dans [!UICONTROL Reports &amp; Analytics] ne sera plus disponible à compter du mois d’octobre 2020. |
| Fin de la prise en charge de TLS 1.1 | 3 octobre 2019 | D’ici le 31 mars 2020, Adobe Analytics supprimera la prise en charge de TLS 1.1. Ce changement s’inscrit dans le cadre des efforts que nous déployons pour respecter les meilleures normes de sécurité et promouvoir la sécurité des données de nos clients. |
| Nouveau domaine Adobe Analytics | 18 décembre 2019 | Le 16 janvier 2020, Adobe Analytics a commencé à passer à un nouveau domaine : `https://experience.adobe.com/analytics.`<br>**Remarque :** cette modification s’applique à tous les utilisateurs accédant à Analytics avec leur Adobe ID ou Enterprise ID.<ul><li>Ce changement de domaine peut créer des problèmes de cookies lors du chargement d’Analytics dans Safari. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité [!DNL Safari], vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Analytics de fonctionner sur ce nouveau domaine Adobe Experience Cloud. Vous pouvez utiliser d’autres navigateurs sans problème, car cette particularité affecte uniquement les utilisateurs de [!DNL Safari].</li><li>Le changement de domaine peut entraîner l’arrêt du fonctionnement d’[!UICONTROL Activity Map] pour certains clients [dans des cas spécifiques](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vie : API héritées d’Analytics | 9 janvier 2020 | En novembre 2020, les services d’API hérités d’Analytics suivants arriveront en fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner. <ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Nous avons mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | Pour les clients basés à Londres et à Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fin de vie d’Ad Hoc Analysis | 6 août 2018 | Adobe a annoncé la prochaine fin de vie d’Ad Hoc Analysis. La date de fin de vie sera communiquée dès que possible. Pour obtenir de plus amples informations, voir le site [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

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

   **[!UICONTROL Détection automatique de sections logiques]** Vous pouvez utiliser l’option [!UICONTROL Détection automatique de sections logiques] pour abandonner les panneaux au niveau de la page (panneaux basés sur le numéro de page) et créer uniquement des panneaux logiques. Il regroupe également les champs qui n’appartiennent à aucune section avec les sections logiques précédentes et les champs d’une section logique répartis sur deux pages adjacentes en une seule section logique. Par exemple, si certains champs d’une section logique se trouvent à la fin de la première page et d’autres au début de la deuxième page, tous ces champs sont regroupés en une seule section logique.

* **Formats d’image non pris en charge dans Dynamic Media**

   Informations sur les sous-types de formats de fichiers image pixellisés qui ne sont pas pris en charge dans [!UICONTROL Dynamic Media].

   Voir [Formats d’image pixellisée non pris en charge dans Dynamic Media](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/assets/administer/assets-formats.translate.html#unsupported-image-formats-dynamic-media).

* **Fragments de contenu**

   Informations sur [la prise en charge des fragments de contenu dans l’API HTTP AEM Assets](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.translate.html), ainsi que sur la [personnalisation et l’extension des fragments de contenu](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html) et la [configuration des fragments de contenu en vue de la configuration des composants pour le rendu](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

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

* [Notes de mise à jour d’AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.translate.html)
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

* [Adobe Campaign Standard version 20.3](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.translate.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/previous-releases/release--19-1.translate.html#release-19-1-4-build-9032)

### Panneau de contrôle Campaign

| Fonction | Description |
| -----------| ---------- |  
| Gestion des clés GPG | Installez et/ou générez des clés GPG sur une instance marketing, afin de chiffrer les données envoyées à partir de Campaign et de déchiffrer les données entrantes. |
| Gestion des certificats pour les sous-domaines CNAME | Le Panneau de configuration vous permet désormais de renouveler les certificats SSL de vos sous-domaines qui ont été délégués avec la méthode CNAME. |

### Didacticiels sur les nouvelles campagnes

* Nouveaux tutoriels Campaign Standard

| Contenu | Description |
| -----------| ---------- |  
| [Panneau de configuration - Gestion des enregistrements Google TXT](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Grâce au Panneau de contrôle de Campaign, apprenez à ajouter des enregistrements de vérification de site TXT Google aux sous-domaines utilisés pour envoyer des emails aux adresses GMAIL. |
| [Configuration et exécution d’un processus avec l’activité d’API externe](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Découvrez comment appeler un point de terminaison d’API REST externe à l’aide de l’activité d’API externe. |
| [Prise en main des notifications Push pour Android-Tutoriel](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | Ce didacticiel explique les étapes nécessaires à la configuration des notifications Push avec Campaign Standard et l&#39;application Android. |

* Nouveaux tutoriels Campaign Classic

| Contenu | Description |
| -----------| ---------- |  
| [Gestion de données importante sur Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Découvrez comment tirer parti du connecteur Snowflake dans Adobe Campaign Classic. |
| [Panneau de configuration - Gestion des enregistrements Google TXT](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Grâce au Panneau de contrôle de Campaign, apprenez à ajouter des enregistrements de vérification de site TXT Google aux sous-domaines utilisés pour envoyer des emails aux adresses GMAIL. |

### Ressources d’aide Campaign

* Adobe Campaign Standard : [Centre](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/campaign-standard-home.html) d’aide - Notes [de](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html) mise à jour - Vidéos [pratiques - Planification](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) des [](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.html) versions - Dernières mises à jour de la documentation[](https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic : [Centre](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/campaign-classic-home.html) d’aide - Notes [de](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.html) mise à jour - Vidéos [pratiques -](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)[Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/documentation-updates.html)
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
| [!UICONTROL Listes noires] | Le système de prévision utilise désormais automatiquement la liste noire au niveau de l’annonceur ou du compte. Les utilisateurs n’ont plus besoin de coller la liste noire dans les paramètres de placement. |
| [!UICONTROL Offres d’inventaire] | (Bêta fermée) Un nouveau formulaire simplifié vous permet de configurer, de modifier et de résoudre rapidement les problèmes liés aux offres des plateformes côté offre (SSP) qui ne sont pas disponibles dans la boîte de réception Deal ID. |
|  | Lorsque vous acceptez un ensemble d’offres garanties par la programmation dans la boîte de réception Deal ID, vous êtes désormais averti que vous devez créer un emplacement par défaut pour chacun des Deal ID. |

### Nouvelles fonctionnalités dans [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Fonction | Description |
| -----------| ---------- |
| [!UICONTROL Campagnes] | (Comptes Google Ads ; service bêta) À compter de la fin mai, Advertising Cloud Search pourra synchroniser les données de vos campagnes d’affichage Google Gmail et de vos campagnes Google Smart Shopping avec les conversions Google pour le suivi et le rapports. Le service vous permet également de modifier les paramètres des campagnes et des groupes publicitaires pour vos campagnes existantes à partir des vues Campagnes et Groupes publicitaires. Le service sera facultatif. Une fois le service généralement disponible, des frais supplémentaires s’appliqueront.<br>Pour plus d’informations sur le service, y compris le programme bêta et la portée future, contactez votre gestionnaire de compte Adobe. |

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

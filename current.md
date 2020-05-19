---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 99e67d659f3da76d0613629dfc7e7d853a9e1349
workflow-type: tm+mt
source-wordcount: '4798'
ht-degree: 39%

---


# Accès anticipé - Notes de mise à jour d’Adobe Experience Cloud - mai 2020

![Bannière](/assets/experience-cloud-banner-3.png)

Cette page fournit de nouvelles fonctionnalités, des correctifs et des avis importants dans [!DNL Adobe Experience Cloud]. Les dates de publication de la solution peuvent varier. Consultez régulièrement les dernières mises à jour.

>[!IMPORTANT]
>
>Cette page contient le contenu de la version préliminaire et peut être modifiée avant le 21 mai 2020. Les nouvelles informations publiées par la suite seront notées avec la date d&#39;ajout.

>[!NOTE]
>
>Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) (mises à jour produit prioritaires d’Adobe) pour être averti par e-mail de la publication des prochaines versions.

**Date de publication : mai 2020**

Dernière mise à jour : **19 mai 2020**

* [État du système Adobe](#status)
* [Interface d’Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html) (liens vers la page d’aide de Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/fr/primetime/user-guide.html) (liens vers la page d’aide de Primetime)

Besoin d&#39;aide ? Visitez [[ !DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) pour trouver des cours organisés par Adobe, de la documentation technique, des réponses rapides, des informations sur la communauté et des formations dirigées par un instructeur.

## ![Icône](/assets/adobe.png) État du système Adobe {#status}

[!UICONTROL État du système Adobe] fournit des informations détaillées, des mises à jour d’état et des notifications par e-mail relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

Date de mise à jour : **21 mai 2020**

**Nouveautés**

* Avec votre Adobe ID, vous pouvez vous abonner à des notifications d’événement avec plus de granularité et associées au niveau de l’offre de produit et des modules complémentaires. Pour vous aider à configurer votre abonnement plus rapidement, le processus d’auto-abonnement recommande désormais une sélection de produits et d’offres en fonction de vos droits sur les produits. Cela devrait réduire le nombre de courriers électroniques que vous recevez et fournir des notifications plus pertinentes dans votre boîte de réception. Rendez-vous sur [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nouvelles fonctionnalités et améliorations disponibles dès maintenant**

| Fonction | Description |
| -----------| ---------- |
| Amélioration de l’expérience utilisateur pour les abonnements et les notifications | <ul><li>[!DNL Marketo Engage] les emplacements régionaux sont désormais filtrés en fonction de la liste des offres de produits sélectionnées.</li><li>[!DNL Marketo Engage] les notifications par courrier électronique sont pertinentes pour la région, l’emplacement et les préférences d’environnement de l’utilisateur.</li></ul> |
| Confirmation d&#39;abonnement Événement | <ul><li>Vous pouvez désormais obtenir une confirmation par courrier électronique lorsque vous vous abonnez à des mises à jour en événement unique en cours.</li></ul> |
| Améliorations de la convivialité de la navigation globale | <ul><li>Expérience cohérente de l’utilisateur avec `Adobe.com` le menu de navigation de niveau supérieur.</li></ul> |

## ![Icône](/assets/ec_appicon_24.png) Interface d’Experience Cloud {#ecloud}

Mises à jour générales de l’interface d’Experience Cloud.

**Domaine de produit unifié**

Adobe a mis à jour l’en-tête de domaine et d’interface afin d’unifier et d’améliorer votre expérience dans toutes les applications Experience Cloud. Ces améliorations sont conçues pour fluidifier votre utilisation de manière simple, mais importante. Ces améliorations ne modifient pas vos workflows actuels.

Les mises à jour comprennent les éléments suivants :

* Nouvelles URL d’application : `experience.adobe.com/<application name>` :
   * À terme, tous les produits adopteront ce modèle d’URL. Recherchez de nouvelles URL pour qu’elles prennent effet tout au long du mois.
   * Navigateurs pris en charge : [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] et [!DNL Opera] (versions les plus récentes). **Remarque** : bien que l’interface d’Experience Cloud prenne en charge ces navigateurs, les applications individuelles peuvent ne pas tous les prendre en charge. (Par exemple, [Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/admin/sys-reqs.html) ne prend pas en charge [!DNL Opera] et [Target](https://docs.adobe.com/help/fr-FR/target/using/implement-target/before-implement/supported-browsers.html) ne prend pas en charge [!DNL Safari].)
   * ([!DNL Safari] uniquement) Le changement de domaine peut entraîner des problèmes de cookies dans [!DNL Safari]. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité de [!DNL Safari], vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Experience Cloud de fonctionner sur ce nouveau domaine.
* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide des produits : [!UICONTROL Experience League] est intégré dans le produit afin qu’une recherche d’aide comprenne également les résultats des forums de la communauté et du contenu vidéo. Cette modification simplifie l’accès à davantage de contenu et vous permet de tirer le meilleur parti d’Experience Cloud. De plus, vous pouvez cliquer sur **[!UICONTROL Aide]** > **[!UICONTROL Commentaires]** pour signaler des problèmes ou partager vos idées avec Adobe.

Les applications suivantes utilisent le nouveau domaine experience.adobe.com :

| Application ou service | Domaine |
| -----------| ---------- |
| page d&#39;accueil Experience Cloud | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Gestion du parcours | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Panneau de configuration d’Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Distribution logicielle | `experience.adobe.com/downloads` |
| Outil d’administration (bêta) | `experience.adobe.com/admin` |

## ![Icône](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notes de mise à jour d’[!DNL Experience Platform,] y compris d’[!DNL Experience Platform Launch,] de [!UICONTROL Journey Orchestration], des services [!UICONTROL Offres], [!UICONTROL Personnes], [!UICONTROL Places], et [!UICONTROL Mobile Services], et des bulletins de sécurité.

### Améliorations de l’interface

Updated: **May 15, 2020**

[!DNL Adobe Experience Platform] publie des mises à jour sur la barre de domaine et d’en-tête afin d’améliorer votre expérience et de vous unir à d’autres applications Experience Cloud. Les mises à jour comprennent les éléments suivants :

* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide à l’utilisateur, y compris les articles présentés et la documentation contextuelle dans le menu Aide.
* Capacité à fournir des commentaires sur la plateforme d’expérience et les tickets d’assistance pour les fichiers.

See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) for more information.

### Attributs du client - nouvelle documentation

Updated: **May 15, 2020**

* [Prise en charge des attributs du client pour l’ACCP](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Prise en charge des attributs du client pour GDPR](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/gdpr.html) (règlement général sur la protection des données)

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

* [Nouvelles fonctionnalités de l’analyse du parcours des clients](#cust-journey)
* [Nouvelles fonctionnalités d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)
* [Nouveaux tutoriels Analytics](#tutorials-analytics)

### Nouvelles fonctionnalités de l’analyse du parcours des clients {#cust-journey}

| Fonction | Description |
| -----------| ---------- |
| [!UICONTROL Analyse]du parcours du client : Disponibilité globale | rend les analyses [!UICONTROL de parcours] client disponibles pour les clients de la zone EMEA et de l’APAC. |
| [!UICONTROL Analyse]du parcours du client : Prise en charge des sandbox [!UICONTROL Adobe Experience Platform] | Permet de sélectionner des sandbox [!UICONTROL spécifiques à] Adobe Experience Platform pour créer des connexions CJA à partir de. [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics-platform/using/cja-connections/create-connection.translate.html) |

### Nouvelles fonctionnalités d’Adobe Analytics {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| Fonction | Description |
| -----------| ---------- |
| Prise en charge d’Analytics pour [!UICONTROL Adobe Experience Platform Edge Network] | Permet d’utiliser une balise unique pour envoyer des données à plusieurs solutions Adobe, telles qu’Adobe Analytics, Adobe Cible, Adobe Audience Manager, Adobe Experience Platform Data Lake, Unified Profil et Experience Cloud ID Service. [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/experience-platform/edge/home.html) |
| [!UICONTROL tableaux de bord Adobe Analytics] | [!UICONTROL Adobe Analytics tableaux de bord] est une application mobile qui permet aux utilisateurs, à tout moment et en tout lieu, d’accéder aux informations d’Adobe Analytics. Cette application est destinée aux cadres qui recherchent un accès en ligne à des mesures clés. Il permet d’accéder à des cartes de performance interactives et organisées et sera disponible pour les systèmes d’exploitation iOS et Android. [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace][!UICONTROL  : crée automatiquement des tableaux à structure libre à partir d’un état vide] | Previously, you could not drop components directly into a blank project or blank panel; you had to add a [!UICONTROL Freeform Table] first. You can now drop components directly into a blank project or panel, and a [!UICONTROL Freeform Table] is automatically built for you in a recommended format. En outre, des améliorations ont été apportées à la façon dont les types de composants mixtes (tels que les dimensions et les mesures) sont traités lorsqu’ils sont déposés ensemble dans un tableau à structure libre vierge. |
| [!UICONTROL Package] Adobe Analytics ajouté à la page Niveau [!UICONTROL d’accès aux] fonctionnalités | Vous pouvez désormais vue à quel module  Adobe Analytics (SKU) votre société a droit dans **[!UICONTROL Admin]** > Paramètres **[!UICONTROL de]** Société > Niveau d’accès aux **[!UICONTROL fonctionnalités.]** |

#### Correctifs d’Adobe Analytics

* Fixed an issue that caused missing [!DNL Analytics] segment data in Audience Manager. (AN-206221)
* Correction d’un problème concernant le traitement des [!UICONTROL sources de données] qui affichait les mauvaises dates. (AN-213604)
* Correction d’un problème empêchant le chargement correct des fichiers de classification vers le FTP. (AN-214102)
* Correction d’un problème empêchant le renvoi d’une réponse complète avec la méthode d’API `Segments.Get`. (AN-206210)
* Correction d’un problème qui entraînait la conversion des éléments de ligne d’un tableau en caractères spéciaux lors d’un téléchargement au format PDF [!DNL Workspace]. (AN-196153)
* Correction du mauvais fonctionnement de l’appel d’API Adobe Analytics 1.4 `visattrcustomeridcustomerattributes`. (AN-186873)
* Correction d’un problème qui entraînait l’apparition de données dans les rapports qui n’apparaissaient pas dans le [!UICONTROL Flux de données]. (AN-211923)
* Correction d’un problème qui empêchait la copie des autorisations [!UICONTROL Profil de produit]. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to [!UICONTROL Report Builder]. (AN-207750)
* Correction d’un problème d’affichage des données [!UICONTROL AdWords] dans [!UICONTROL Advertising Analytics]. (AN-213249)
* Correction d’un problème qui empêchait l’affichage des données de classification dans la vue de tendance. (AN-212761)
* Correction d’un problème qui provoquait un nombre de segments publié incorrect dans le [!UICONTROL Gestionnaire de segments]. (AN-213374)
* Correction d’un problème lié à l’option **[!UICONTROL Afficher la tendance à la hausse en tant que...]** dans l’éditeur [!UICONTROL de mesures] calculées : elle ne fonctionnait pas lors de l’application de filtres. (AN-214223)
* Correction de plusieurs problèmes liés à l’importation et à l’exportation de [!UICONTROL classifications] . (AN-213488, AN-215309, AN-216345, AN-215307, AN-216671)
* Correction de plusieurs problèmes avec le Créateur [!UICONTROL de règles de]classification. (AN-213826, AN-213550, AN-213095)
* Correction de problèmes liés au traitement des sources [!UICONTROL de] données. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911, AN-21751, (AN-217947, AN-219018, AN-214691, AN-218401)
* Correction de problèmes de connectivité FTP. (AN-115525)
* Correction de plusieurs problèmes de flux [!DNL Analytics] de  données. (AN-176769, AN-160480, AN-211923, AN-204286, AN-212977, AN-214528, AN-215080, (AN-217784, AN-219093, AN-218817, AN-217798, AN-218267, AN-218382)
* Correction de problèmes liés aux demandes [!UICONTROL Data Warehouse] . (AN-181836)
* Correction de problèmes dans les projets [!UICONTROL Workspace] téléchargés au format PDF, en raison desquels les valeurs étaient converties en caractères spéciaux. (AN-196153)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions in [!UICONTROL Admin Console]. (AN-211113)
* Correction d’un problème en raison duquel les formats de temps dans les mesures calculées étaient rompus pour les valeurs négatives. (AN-210900)
* Correction d’un problème qui empêchait les utilisateurs de modifier le modèle [!UICONTROL d’] attribution sur les mesures de lignes statiques. (AN-207872)
* Correction d’un problème en raison duquel le créateur de rapports  planifiés restait bloqué dans un état de file d’attente. (AN-215317)
* Correction du connecteur [!UICONTROL de données]ExactTarget. (AN-210794)
* Correction de problèmes de latence dans l&#39;API [!UICONTROL d&#39;importation en]masse. (AN-210165)
* Correction d’un problème en raison duquel les utilisateurs ne pouvaient pas se connecter au créateur [!UICONTROL de] rapports avec un ID fédéré. (AN-207750)
* Correction d’un problème dans les analyses [!UICONTROL de] publicité qui empêchait [!DNL Google AdWords] l’affichage des données. (AN-213249)
* Correction d’un problème qui empêchait l’affichage des événements [!UICONTROL Workspace] [!UICONTROL Project Viewed] dans les journaux. (AN-214134)
* Correction d’un problème qui se produisait lors de la modification de la plage de dates dans [!UICONTROL Workspace] et de la sélection de l’option **[!UICONTROL Appliquer à tous les panneaux]**. La date n’a pas été modifiée dans certains panneaux. (AN-214944)
* Correction d’un problème en raison duquel il n’était pas possible de créer ou de modifier des alertes. (AN-215920)
* Correction d’un problème en raison duquel toutes les plages de dates dynamiques de [!UICONTROL Workspace] affichaient des dates incorrectes en raison du premier jour de la semaine passant sporadiquement d’un lundi à un dimanche. (AN-218835)

#### Autres correctifs d’Adobe Analytics

AN-101871, AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299 ; AN-201342; AN-201397 ; AN-204286; AN-204518; AN-206045 ; AN-206948 ; AN-208607 ; AN-209486 ; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709 ; AN-212833 ; AN-212961; AN-212977 ; AN-213095 ; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094 ; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017 ; AN-215080; AN-215212; AN-215312; AN-215377 ; AN-215402; AN-215545; AN-215905 ; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999 ; AN-217245; AN-218450; AN-218899 ; AN-219487; AN-219677

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Modification du mode de calcul des [!UICONTROL entrées/sorties] dans [!UICONTROL Workspace] | 7 avril 2020 | Dans [!UICONTROL Analysis Workspace], depuis mars 2020, nous avons modifié la manière dont la valeur _Aucun_ interagit avec les [!UICONTROL entrées/sorties]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. Supposons, par exemple, que le premier accès d’une visite ne comporte aucune valeur pour les eVars, contrairement au second accès. In [!UICONTROL Reports &amp; Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
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
| [Modèle de didacticiel de formation dans Analyse Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | Le didacticiel de formation à l’espace de travail  d’Analyse vous guide tout au long de la terminologie et des étapes courantes pour la création de votre premier projet dans [!UICONTROL Workspace]. |
| [Ajout de comparaisons mensuelles et annuelles antérieures aux tendances](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Découvrez comment appliquer des plages de dates personnalisées pour créer des comparaisons de tendances mensuelles et annuelles pour n’importe quelle mesure dans [!UICONTROL Analyse Workspace]. |
| [Extension de mode sombre pour l’espace de travail d’Analyse](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Activez l’extension Dark Reader Chrome pour rendre l’espace de travail d’Analyse sombre. |
| [Extension de la pipette couleur pour la définition de palettes personnalisées](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Découvrez comment utiliser l’extension Chrome ColorPick EyeDropper pour trouver facilement les valeurs hexadécimales dont vous avez besoin pour une palette de couleurs personnalisée dans vos projets [!UICONTROL Workspace] . |

#### Ressources d’aide à propos d’Analytics

* [Didacticiels Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentation du produit Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/landing/home.html)

## ![Icône](/assets/audience-manager.png) Audience Manager {#aam}

Nouvelles fonctionnalités, correctifs, documentation et didacticiels dans Audience Manager.

### Mises à jour de l’interface utilisateur

Audience Manager met à jour la barre de domaine et d’en-tête afin d’améliorer votre expérience et de vous unir à d’autres applications Experience Cloud.

* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide à l’utilisateur, y compris les articles présentés et les vidéos contextuelles dans le menu Aide.
* Capacité à fournir des commentaires sur la plateforme d’expérience et les tickets d’assistance pour les fichiers.
* Nouveau modèle d’URL plus simple. Mettez à jour vos signets vers la nouvelle URL : `experience.adobe.com/audience-manager`.

Ces mises à jour ne sont disponibles que pour les utilisateurs qui se connectent à l’aide d’un Adobe ID. Pour vous connecter à un ID Adobe, voir [Gestion des utilisateurs et des produits](https://docs.adobe.com/content/help/fr-FR/core-services/interface/manage-users-and-products/admin-getting-started.html)Experience Cloud.

### Nouvelles fonctionnalités et correctifs dans Adobe Audience Manager

| Fonction | Description |
| -----------| ---------- |  
| [Outils de gestion en masse (BAAAM)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | Nous avons téléchargé une nouvelle feuille de calcul d&#39;outils de gestion en masse qui : <br><br><ul><li>Permet de liste des sous-dossiers dans votre hiérarchie de caractéristiques (AAM-51528).</li><li>Récupère des mesures lorsqu’elles sont demandées pour les caractéristiques associées aux identifiants de gestion de la relation client (identifiants inter-périphériques) (AAM-52135)</li><li>Correction d’un problème de codage de langue pour les caractères coréens (AAM-AAM-54006).</li></ul> |

**Correctifs**

* Correction d’un problème en raison duquel les rapports de tendance étaient temporisés pour les dossiers présentant un grand nombre de caractéristiques. (AAM-54457)
* Correction d’un problème en raison duquel les clients ne pouvaient pas voir le créateur [!UICONTROL d’] Expressions dans le processus de création/modification de caractéristiques. (AAM-54255)
* Correction d’un problème en raison duquel les messages d’erreur dans l’interface ne s’affichaient que pour une courte période, disparaissaient avant que les clients aient la possibilité de les lire. Cela se produisait par exemple lors de la tentative de suppression d’un segment qui était mappé à une destination. (AAM-54031)
* Correction d’un problème en raison duquel les clients qui n’utilisaient plus [!UICONTROL Audience Marketplace] recevaient des courriels de facturation mensuelle. (AAM-54602)
* Correction d’un problème en raison duquel les clients qui cliquaient sur certaines caractéristiques à partir d’autres emplacements de l’interface utilisateur voyaient des liens rompus au lieu des caractéristiques. (AAM-54768)
* Correction d’un problème en raison duquel, en mode de modification de l’expression de caractéristiques, la pression sur ENTRÉE actualisait la page et l’expression de caractéristiques était perdue. (AAM-54210)
* Plusieurs améliorations de l’accessibilité de l’interface. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Nouveaux didacticiels Audience Manager {#tutorials-aam}

| Contenu | Description |
| -----------| ---------- |  
| [Présentation des termes et concepts de base dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | Cette vidéo présente quelques-uns des termes et concepts de base qui vous permettent de commencer dans Audience Manager, notamment les signaux, les caractéristiques, les segments, etc. |
| [Présentation du flux de données dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | Cette vidéo vous aide à comprendre Adobe Audience Manager en décrivant le flux de données dans, via et hors de l’application. |
| [Gestionnaire d&#39;Audiences - Présentation d&#39;un DMP](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Découvrez les principaux défis liés à la personnalisation sur plusieurs canaux et comment Adobe Audience Manager facilite le voyage des clients. Identifiez également les types de données qui peuvent être intégrés dans Audience Manager et identifiez les partenaires d&#39;éco-système ad-tech intégrés à Audience Manager. |
| [Cas d’utilisation d’Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | Dans cette vidéo, nous identifions quatre cas d’utilisation courants du gestionnaire d’Audiences et décrivons les meilleures pratiques qui y sont associées. |
| [Présentation des mesures sur plusieurs périphériques dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | Dans cette vidéo, nous abordons la différence entre les profils des périphériques et les profils entre périphériques et montrons où les nombres de l’interface utilisateur correspondent à ces différents types de profils. |
| [Présentation des Audiences prédictives dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | Dans cette vidéo, nous discutons des Audiences prédictives du gestionnaire des Audiences, nous présentons des détails sur leur fonctionnement et nous montrons les cas d&#39;utilisation. |
| [Configuration et création de rapports sur les Audiences prédictives dans Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | Dans cette vidéo, nous examinons la configuration des Audiences prédictives dans l’interface d’Audience Manager. Nous voyons aussi les rapports qui montrent les résultats du modèle. |

## ![Icône](/assets/aem.png) Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Mises à jour de produit

* **AEM en tant que Cloud Service**

   * Améliorations et correctifs du traitement des ressources. La boîte de dialogue de retraitement des ressources permet à l’utilisateur de mieux contrôler, de sélectionner un profil de traitement spécifique et de déterminer si le processus de post-traitement doit être déclenché.
   * Améliorations des performances d’assimilation des fichiers de médias dynamiques.

### Auto-assistance

* **Service de conversion automatisé des formulaires - version AFC-2020.03.1**

   Une nouvelle option est disponible lorsque vous installez le dernier connecteur :

   **[!UICONTROL Détection automatique des sections]** logiques : vous pouvez utiliser l’option de détection [!UICONTROL automatique des sections] logiques pour faire tomber les panneaux de niveau page (panneaux basés sur le numéro de page) et créer uniquement des panneaux logiques. Il regroupe également les champs qui n’appartiennent à aucune section avec les sections logiques et les champs précédents d’une section logique qui est répartie sur deux pages adjacentes en une seule section logique. Par exemple, si certains champs d’une section logique se trouvent à la fin de la page un et d’autres dans le début de la page deux, tous ces champs sont regroupés en une seule section logique.

* **Formats d’image non pris en charge dans Contenu multimédia dynamique**

   Informations sur les sous-types de formats de fichiers image pixellisés qui ne sont pas pris en charge dans [!UICONTROL Contenu multimédia]dynamique.

   Voir Formats d’image pixellisée [non pris en charge dans Contenu multimédia](https://docs.adobe.com/content/help/en/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media)dynamique.

* **Fragments de contenu**

   Informations sur la prise en charge des fragments de [contenu dans l’API](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)HTTP AEM Assets, ainsi que sur la [personnalisation et l’extension des fragments](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)de contenu et la configuration des fragments de [contenu en vue de la configuration des composants pour le rendu](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **Communauté AEM Experience League**

   Connectez-vous à la communauté [](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community)AEM Experience League : Posez des questions à vos collègues apprenants et aux experts d’AEM, parcourez les fils d’actualité et partagez vos conseils et votre expertise !

* **Lettres d’actualité AEM**

   Le bulletin d’informations AEM d’ [!UICONTROL Experience League] est conçu pour vous aider à maîtriser AEM afin que vous puissiez début à tirer immédiatement parti de la valeur d’AEM. Voici la dernière newsletter :

   * [Volume 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): Experience Manager est désormais disponible en tant que service cloud.
   * [Abonnez-vous](https://adobeeventsonline.com/AEM/2017/NL/Optin/) au bulletin d’information d’Experience Insider.
   * Archives du bulletin d’informations de Vue dans la section des ressources [](https://helpx.adobe.com/fr/support/experience-manager/6-5.html) AEM de la page de formation et d’assistance d’Adobe Experience Manager 6.5.

### Nouveaux tutoriels Experience Manager

| Contenu | Description |
| -----------| ---------- |  
| [Configuration de l’exécution locale d’AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. This allows developers to deploy to, and test custom code, configuration, and content prior to committing it to source control, and deploying it to a [!UICONTROL AEM as a Cloud Service] environment. |
| [Prise en main des ressources AEM](https://video.tv.adobe.com/v/33624?captions=fre_fr) | Une vidéo d’introduction sur la prise en main d’AEM Assets pour les utilisateurs professionnels. |
| [schémas de dossiers de métadonnées](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Les schémas de dossiers de métadonnées permettent aux utilisateurs de gérer et de revoir les métadonnées associées aux dossiers de fichiers eux-mêmes, plutôt que directement sur les fichiers. |
| [Balisage](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | Les balises constituent un outil intégral de gestion des ressources dans la hiérarchie de dossiers des ressources. La création d’une taxonomie de balisage est essentielle pour permettre aux utilisateurs de découvrir et d’organiser des ressources dans AEM. |
| [Profils de métadonnées](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Les profils de métadonnées permettent l’application automatique des métadonnées par défaut aux fichiers des dossiers de fichiers. Cela permet de réduire le fardeau de la gestion des métadonnées pour les utilisateurs d’AEM et d’accroître la cohérence des métadonnées. |
| [Schémas de métadonnées](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Les schémas de métadonnées définissent l’interface qui expose les métadonnées de fichier dans AEM. Cette vidéo explore la combinaison des approches utilisées pour appliquer des ressources. |

### Ressources supplémentaires

* [Notes de mise à jour d’AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [Documentation d’AEM as a Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/landing/home.html)
* [Page d’accueil Formation et assistance AEM 6.5](https://helpx.adobe.com/fr/support/experience-manager/6-5.html)
* [Page d’accueil Formation et assistance AEM 6.4](https://helpx.adobe.com/fr/support/experience-manager/6-4.html)
* [Page d’accueil Formation et assistance AEM 6.3](https://helpx.adobe.com/fr/support/experience-manager/6-3.html)
* [Page d’accueil Formation et assistance AEM 6.2](https://helpx.adobe.com/fr/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Notes de mise à jour d’AEM Cloud Manager](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/fr/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/fr-FR/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media](https://docs.adobe.com/content/help/fr-FR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notes de mise à jour de Livefyre](https://docs.adobe.com/content/help/fr-FR/livefyre/using/release-notes/c-rn.html)

## ![Icône](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Campaign Standard

* [Adobe Campaign Standard version 20.3](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Panneau de configuration Campaign

| Fonction | Description |
| -----------| ---------- |  
| Gestion des clés GPG | Installez et/ou générez des clés GPG sur une instance marketing, afin de chiffrer les données envoyées à partir de Campaign et de déchiffrer les données entrantes. |
| Gestion des certificats pour les sous-domaines CNAME | Le Panneau de configuration vous permet désormais de renouveler les certificats SSL de vos sous-domaines qui ont été délégués avec la méthode CNAME. |

### Didacticiels sur les nouvelles campagnes

* Nouveaux tutoriels Campaign Standard

| Contenu | Description |
| -----------| ---------- |  
| [Panneau de configuration - Gestion des enregistrements Google TXT](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Découvrez comment ajouter des enregistrements de vérification de site Google TXT à tous les sous-domaines utilisés pour envoyer des courriers électroniques aux adresses GMAIL à l’aide du Panneau de configuration Campaign. |
| [Configuration et exécution d’un processus avec l’activité d’API externe](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Découvrez comment appeler un point de terminaison de l’API REST externe à l’aide de l’activité API externe. |
| [Prise en main des notifications Push pour Android-Tutoriel](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | Ce didacticiel explique les étapes nécessaires à la configuration des notifications Push avec Campaign Standard et l&#39;application Android. |

* Nouveaux didacticiels Campaign Classic

| Contenu | Description |
| -----------| ---------- |  
| [Grand data Management sur Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Découvrez comment tirer parti du connecteur Snowflake dans Adobe Campaign Classic. |
| [Panneau de configuration - Gestion des enregistrements Google TXT](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Découvrez comment ajouter des enregistrements de vérification de site Google TXT à tous les sous-domaines utilisés pour envoyer des courriers électroniques aux adresses GMAIL à l’aide du Panneau de configuration Campaign. |

### Ressources d’aide Campaign

* Adobe Campaign Standard : [Centre](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/campaign-standard-home.html) d’aide - Notes [de](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html) mise à jour - Vidéos [pratiques - Planification](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) des [](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.html) versions - Dernières mises à jour de la documentation[](https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic : [Centre](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/campaign-classic-home.html) d’aide - Notes [de](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/latest-release.html) mise à jour - Vidéos [pratiques -](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)[Dernières mises à jour de la documentation](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/documentation-updates.html)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/control-panel/using/release-notes.html)

## ![Icône](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Nouvelles fonctionnalités du DSP Advertising Cloud](#adcloud-dsp)
* [Nouvelles fonctionnalités de la recherche dans Advertising Cloud](#adcloud-search)

### Nouvelles fonctionnalités du DSP Advertising Cloud {#adcloud-dsp}

| Fonction | Description |
| -----------| ---------- |
| [!UICONTROL Campagnes classiques] et [!UICONTROL Campagnes bêta] | Les paramètres de mesure IAS pour la fraude et la sécurité de la marque, que vous pouvez éventuellement configurer pour chaque campagne, incluent désormais des options de mesure sur les stocks VAST et VPAID. |
| [!UICONTROL Campagnes bêta] | Les visualisations des données et les temps de chargement des pages ont été améliorés. |
|  | Sur toutes les pages, vous pouvez désormais télécharger des rapports Excel basés sur les filtres et vues en cours. |
|  | (Dans la version du 22 mai) Les nouvelles mesures comprennent les mesures Temps passé, Diffusion d’intervalle en cours,  d’heures spécifiques à la date. |
| [!UICONTROL les blacklistes,] | Le système de prévision utilise désormais automatiquement la liste noire au niveau de l’annonceur ou du compte. Les utilisateurs n’ont plus besoin de coller la liste noire dans les paramètres d’emplacement. |
| [!UICONTROL Offres de stock] | (Bêta fermé) Un nouveau formulaire simplifié vous permet de configurer, de modifier et de résoudre rapidement les problèmes liés aux plateformes côté offre (SSP) qui ne sont pas disponibles dans la boîte de réception ID d&#39;opération. |
|  | Lorsque vous acceptez un ensemble d&#39;offres garanties par la programmation dans la boîte de réception des ID d&#39;opération, vous êtes désormais averti que vous devez créer un emplacement par défaut pour chacun des ID d&#39;opération. |

### Nouvelles fonctionnalités de la recherche dans [!UICONTROL Advertising Cloud] {#adcloud-search}

| Fonction | Description |
| -----------| ---------- |
| [!UICONTROL Campagnes] | (Comptes Google Publicités ; service bêta) À compter de la fin mai, Advertising Cloud Search pourra synchroniser les données de vos campagnes d’affichage Google Gmail et de vos campagnes Google Smart Shopping avec les conversions Google pour le suivi et le rapports. Le service vous permet également de modifier les paramètres des campagnes et des groupes publicitaires pour vos campagnes existantes à partir des vues Campagnes et Groupes publicitaires. Le service sera facultatif. Une fois que le service est généralement disponible, des frais supplémentaires s&#39;appliquent.<br>Pour plus d’informations sur le service, y compris le programme bêta et la portée future, contactez votre gestionnaire de compte Adobe. |

## ![Icône](/assets/magento.png) [!DNL Magento] {#magento}

Pour les notes de mise à jour de Magento, veuillez consulter :

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icône](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] est une application complète pour la gestion des pistes et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en s’engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Voir les notes [!DNL Marketo] de [](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) mise à jour pour consulter les informations les plus récentes.

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

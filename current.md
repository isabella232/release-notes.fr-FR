---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 80852c2797ad1a26b6c4a806fa2cf3ef59f84707

---


# Accès anticipé - Notes de mise à jour d’Adobe Experience Cloud - avril 2020

![Bannière](/assets/experience-cloud-banner-3.png)

Nouvelles fonctionnalités et correctifs d’[!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>
>Cette page comporte du contenu publié avant la date de publication et peut faire l’objet de modifications avant la publication planifiée.

>[!NOTE]
>
>Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) pour être averti par e-mail de la publication des prochaines versions. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : 2020 avril **

(Les dates de publication des solutions spécifiques peuvent varier.)

* [État du système Adobe](#status)
* [Interface d’Experience Cloud et services principaux](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html) (liens vers la page d’aide de la solution)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/fr/primetime/user-guide.html) (liens vers la page d’aide de la solution)

Vous cherchez la page d’accueil de l’aide ? Voir la [documentation d’Adobe Experience Cloud](https://docs.adobe.com/content/help/fr-FR/experience-cloud/user-guides/home.html).

## ![Icône](/assets/adobe.png) État du système Adobe {#status}

[!UICONTROL État du système Adobe] fournit des informations détaillées, des mises à jour d’état et des notifications par e-mail relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

**Nouveautés**

* Avec votre Adobe ID, vous pouvez vous abonner à des notifications d’événement avec plus de granularité et associées au niveau de l’offre de produit et des modules complémentaires. De plus, dans notre dernière version, le processus de  d’auto- recommande maintenant une sélection de produits et de services en fonction de vos droits sur les produits. Cela devrait simplifier le processus de  du  en réduisant le nombre de décisions ou de clics requis pour créer votre de  et, plus important encore, fournir des notifications plus pertinentes dans votre boîte de réception. Rendez-vous sur [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nouvelles fonctionnalités et améliorations disponibles dès maintenant**

| Fonction | Description |
| -----------| ---------- |
|  personnalisé  en fonction des droits | <ul><li> présélectionnée  recommandations de en fonction des droits DX de l’utilisateur.</li><li>Les   recommandées sont mises en surbrillance en haut de l’de produit pour une visualisation rapide.</li><li>Les notifications électroniques reçues sont pertinentes pour les droits de l’utilisateur sur les produits.</li></ul> |
| Gestion plus facile des  de  | <ul><li>**[!UICONTROL Gérer]** a une nouvelle expérience utilisateur pour gérer à la fois les produits et les dede l’ de l’.</li><li>Nouvelle option permettant de  et de modifier les produits et les  lede produits séparément.</li><li>L&#39;option **[!UICONTROL Supprimer]** vous permet de vous désabonner d&#39;un produit ou d&#39;un  .</li><li>L’option **[!UICONTROL Désabonner tout]** en un clic est disponible pour le produit  .</li><li>La prise en charge de l&#39;UX est disponible pour les surfaces Web/Mobile/Tablette et les  en 19 langues.</li></ul> |

## ![Icône](/assets/ec_appicon_24.png) Interface d’Experience Cloud et services principaux {#ecloud}

Nouvelles fonctionnalités et correctifs de l’interface d’Experience Cloud, y compris l’administration et les services principaux (attributs du client,  de , déclencheurs, cookies, etc.) :

* La page [!UICONTROL Flux] Experience Cloud était obsolète. (EXC-8505)
* La page de connexion à Experience Cloud a été mise à jour pour refléter les nouveaux éléments de marque. (EXC-10747)

Pour consulter la documentation du produit, consultez l’aide [Experience Cloud](https://docs.adobe.com/content/help/fr-FR/core-services/interface/experience-cloud.html).

### Domaine de produit unifié

Adobe met à jour l’en-tête de domaine et d’interface afin d’unifier et d’améliorer votre expérience dans toutes les applications Experience Cloud. Ces améliorations sont conçues pour fluidifier votre utilisation de manière simple, mais importante. Ces améliorations ne modifieront pas vos processus actuels.

Les mises à jour comprennent les éléments suivants :

* Nouvelles URL de solution : `experience.adobe.com/<application name>` :
   * À terme, tous les produits adopteront ce modèle d’URL. Recherchez de nouvelles URL pour qu’elles prennent effet tout au long du mois.
   * Navigateurs pris en charge : [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] et [!DNL Opera] (versions les plus récentes). **Remarque** : bien que l’interface d’Experience Cloud prenne en charge ces navigateurs, les solutions individuelles peuvent ne pas tous les prendre en charge. (Par exemple, [Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/admin/sys-reqs.html) ne prend pas en charge [!DNL Opera] et [Target](https://docs.adobe.com/help/fr-FR/target/using/implement-target/before-implement/supported-browsers.html) ne prend pas en charge [!DNL Safari].)
   * ([!DNL Safari] uniquement) Le changement de domaine peut entraîner des problèmes de cookies dans [!DNL Safari]. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité de [!DNL Safari], vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Experience Cloud de fonctionner sur ce nouveau domaine.
* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide des produits : [!UICONTROL Experience League] est intégré dans le produit afin qu’une recherche d’aide comprenne également les résultats des forums de la communauté et du contenu vidéo. Cette modification simplifie l’accès à davantage de contenu et vous permet de tirer le meilleur parti d’Experience Cloud. De plus, vous pouvez cliquer sur **[!UICONTROL Aide]** > **[!UICONTROL Commentaires]** pour signaler des problèmes ou partager vos idées avec Adobe.

## ![Icône](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notes de mise à jour d’[!UICONTROL Experience Platform], d’[!UICONTROL Experience Platform Launch], d’[!UICONTROL Identity Service], de Journey Orchestration, de Mobile Services et des bulletins de sécurité.

### Orchestration du parcours {#journey}

Grâce à Adobe Experience Platform, orchestrez des parcours clients individuels à l’échelle sur des canaux d’expérience en anticipant de manière intelligente les besoins de chaque individu en temps réel, quel que soit l’endroit où leur parcours les mène.

* [Documentation](https://docs.adobe.com/content/help/fr-FR/journeys/using/journey-orchestration-home.html)
* [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html)
* [Vidéos pratiques](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services et SDK mobiles {#mobile}

Android 4.18.2 (3 avril 2020) :

* Messagerie in-app : Pour des raisons de sécurité, [!UICONTROL WebViews] créé par le SDK définit désormais la propriété `setAllowFileAccess` sur _false_.

iOS 4.19.2 (24 mars 2020) :

* Général : Correction de certaines fuites dans [!DNL Target] le code.

Unity 4.19.0 (10 mars 2020):

* Mise à jour [!UICONTROL du module externe] Unity pour utiliser les versions 4.19.0 d’iOS et 4.18.0 ou [!DNL Android].
* Nouvelle méthode d’acquisition exposée pour [!DNL Android] permettre le traitement d’une URL fournie par les API de  [!DNL Google Play] .

### Informations supplémentaires sur la version de la plateforme d’expérience

* [Notes](https://docs.adobe.com/content/help/fr-FR/launch/using/intro/release-notes/current.html)de mise à jour sur le lancement de la plateforme d’expérience.
* [Notes de mise à jour de la plateforme d’expérience](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/fr/security.html)    (Tous les produits Adobe)

## ![Icône](/assets/analytics.png) [!DNL Analytics] {#analytics}

Date de publication : **16 avril 2020**

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices) (Mise à jour le 7 avril 2020)
* [AppMeasurement](#appm)
* [Nouveaux didacticiels Analytics](#tutorials-analytics)

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- |
| [!UICONTROL Analyse]du parcours du client : Renvoi [!UICONTROL automatisé de jeux de données] | Cette nouvelle option vous permet d’importer toutes les données d’historique pour une connexion dans [!UICONTROL Customer Journey Analytics]. (Documentation à suivre) |
| Prise en charge d’Analytics pour [!UICONTROL Experience Edge] | Vous pouvez désormais transférer des données qui ont été envoyées à [!UICONTROL Experience Edge] vers Analytics. |
| [!UICONTROL Espace de travail]: Générer automatiquement des tableaux à structure libre à partir d’un état vide | Auparavant, vous ne pouviez pas déposer les composants directement dans un projet vierge ou un panneau vierge ; il fallait d&#39;abord ajouter un tableau à structure libre. Vous pouvez désormais déposer les composants directement dans un projet ou un panneau vierge. Un tableau à structure libre sera automatiquement créé pour vous dans un format recommandé. En outre, des améliorations ont été apportées à la façon dont les types de composants mixtes (par exemple, dimensions et mesures) sont traités lorsqu’ils sont déposés dans un tableau à structure libre vierge. |

#### Correctifs d’Analytics

* Correction d’un problème en raison duquel il manquait des données de segment Analytics dans  Gestionnaire de  de. (AN-206221)
* Correction d’un problème en raison duquel le traitement des sources [!UICONTROL de] données présentait des dates incorrectes. (AN-213604)
* Correction d’un problème en raison duquel les fichiers de classification n’étaient pas correctement téléchargés sur FTP. (AN-214102)
* Correction d’un problème en raison duquel la méthode API `Segments.Get` ne renvoyait pas de réponse complète. (AN-206210)
* Correction d’un problème en raison duquel les éléments de tableau étaient convertis en caractères spéciaux dans le téléchargement [!DNL Workspace] PDF. (AN-196153)
* Correction d’un problème en raison duquel l’appel de l’API Adobe Analytics 1.4 `visattrcustomeridcustomerattributes` ne fonctionnait pas correctement. (AN-186873)
* Correction d’un problème en raison duquel les données s’affichaient dans les rapports mais manquaient dans le flux de [!UICONTROL données]. (AN-211923)
* Correction d’un problème en raison duquel il était impossible de copier les [!UICONTROL de] de produits. (AN-211113)
* Correction d’un problème en raison duquel les utilisateurs avec des ID fédérés ne pouvaient pas se connecter au créateur de rapports. (AN-207750)
* Correction d’un problème en raison duquel les données [!UICONTROL AdWords] ne s’affichaient pas dans [!UICONTROL les analyses]de publicité. (AN-213249)
* Correction d’un problème en raison duquel les données de classification ne s’affichaient pas dans le  de tendances. (AN-212761)
* Correction d’un problème en raison duquel le nombre de segments publiés était incorrect dans le Gestionnaire de [!UICONTROL segments]. (AN-213374)

#### Correctifs Analytics supplémentaires

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout    ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Modification du mode de calcul des [!UICONTROL entrées/sorties] dans [!UICONTROL Workspace] | 7 avril 2020 | Dans [!UICONTROL Workspace], depuis mars 2020, nous avons modifié la manière dont la valeur _Aucun_ interagit avec [!UICONTROL les entrées/sorties]. Comme vous pouvez désormais activer et désactiver _les_ Nones dans [!UICONTROL Workspace], nous appliquons la valeur _Aucun_ après l’entrée ou la sortie, alors que (pour les eVars) elle était appliquée avant. Supposons, par exemple, que le premier accès d’une visite ne comporte aucune valeur pour les eVars, contrairement au second accès. Dans les [!UICONTROL rapports et analyses] , il s’affichera comme _Non spécifié_ pour l’entrée, mais dans [!UICONTROL l’espace de travail] , il s’affichera comme la valeur du second accès. |
| Abandon du paramètre **[!UICONTROL Niveau de conversion]** | 3 mars 2020 | The non-functioning [Conversion Level](https://docs.adobe.com/content/help/fr-FR/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020. |
| Abandon de l’**[!UICONTROL archive de tableau de bord]** | 27 mars 2020 | Le paramètre **[!UICONTROL Afficher l’archive]** sous **[!UICONTROL Gérer les tableaux de bord]** dans [!UICONTROL Reports &amp; Analytics] ne sera plus disponible à compter du mois d’octobre 2020. |
| Fin de la prise en charge de TLS 1.1 | 3 octobre 2019 | D’ici le 31 mars 2020, Adobe Analytics supprimera la prise en charge de TLS 1.1. Ce changement s’inscrit dans le cadre des efforts que nous déployons pour respecter les meilleures normes de sécurité et promouvoir la sécurité des données de nos clients. |
| Nouveau domaine Adobe Analytics | 18 décembre 2019 | Le 16 janvier 2020, Adobe Analytics a commencé à passer à un nouveau domaine : `https://experience.adobe.com/analytics.`<br>**Remarque :** cette modification s’applique à tous les utilisateurs accédant à Analytics avec leur Adobe ID ou Enterprise ID.<ul><li>Ce changement de domaine peut créer des problèmes de cookies lors du chargement d’Analytics dans Safari. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité [!DNL Safari], vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Analytics de fonctionner sur ce nouveau domaine Adobe Experience Cloud. Vous pouvez utiliser d’autres navigateurs sans problème, car cette particularité affecte uniquement les utilisateurs de [!DNL Safari].</li><li>Le changement de domaine peut entraîner l’arrêt du fonctionnement d’[!UICONTROL Activity Map] pour certains clients [dans des cas spécifiques](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vie : API héritées d’Analytics | 9 janvier 2020 | En novembre 2020, les services d’API hérités d’Analytics suivants arriveront en fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner. <ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Nous avons mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | Pour les clients basés à Londres et à Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fin de vie d’Ad Hoc Analysis | 6 août 2018 | Adobe a annoncé la prochaine fin de vie d’Ad Hoc Analysis. La date de fin de vie sera communiquée dès que possible. Pour obtenir de plus amples informations, voir le site [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Voir [Notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/fr-FR/analytics/implementation/appmeasurement-updates.html). La version 2.20.0 a été publiée le 5 mars 2020.

### Nouveaux didacticiels Analytics {#tutorials-analytics}

| Contenu | Description |
| -----------| ---------- |
| [Adobe Labs ( de technologie) avec Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe Labs (Technology) vous permet d’interagir avec les nouvelles technologies, de découvrir des informations précieuses et d’influencer le développement et les priorités futurs des [!DNL Analytics] fonctionnalités. |
| [Amélioration de la publication   Experience Cloud](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Des améliorations ont été apportées à [!UICONTROL Experience Cloud  publication]par le. Vous pouvez désormais publier   (segments) et les rendre disponibles six fois plus rapidement. Cela réduit le temps de latence actuel de 48 heures à environ 8 heures, voire plus rapidement, en fonction du trafic et de la taille du segment. |
| [Plusieurs suites de rapports dans   espace de travail](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | Plusieurs suites de rapports peuvent être analysées dans un seul projet [!UICONTROL Workspace] en sélectionnant des suites de rapports au niveau du panneau. Cela vous permet d’exécuter des panneaux côte à côte  des sur différents ensembles de données. |

Voir la page d’accueil [de l’aide d’](https://docs.adobe.com/content/help/fr-FR/analytics/landing/home.html) Adobe Analytics pour consulter la documentation du produit.

## ![Icône](/assets/audience-manager.png) Audience Manager {#aam}

Nouvelles fonctionnalités et correctifs dans Adobe Audience Manager:

| Fonction | Description |
| -----------| ---------- |  
| [Principaux problèmes du service clientèle](../support-issues/support-issues-overview.md) | Nous avons ajouté une nouvelle section à notre portail de documentation, qui contient des réponses aux questions les plus fréquentes de notre équipe d’assistance clientèle. |

* Correction d’un problème en raison duquel les boutons [!UICONTROL Test]  et Modèle [!UICONTROL d’allocation de] et Test [!UICONTROL et] du laboratoirede de ne fonctionnaient pas. (AAM-53388)
* Correction d’un problème qui entraînait l’affichage du [!UICONTROL adressable au taux] de [!UICONTROL correspondance et au] segment sur 0 lorsqu’une destination était configurée pour exporter des UUID. Le taux [!UICONTROL de] correspondance et le  de segment adressable aux  s’affichent désormais sous la forme 100 %. (AAM-51615)
* Correction d’un problème en raison duquel les noms de caractéristiques contenant des caractères spéciaux étaient codés deux fois au format HTML. (AAM-54001)
* Correction d’un problème qui empêchait certains utilisateurs de passer à d’autres solutions Adobe Experience Cloud à partir de l’interface [!DNL Audience Manager] utilisateur. (AAM-52917)
* Correction d’un problème qui empêchait certains utilisateurs de créer une source de données SHA256 pour les destinations basées sur les personnes. (AAM-53525)
* Plusieurs améliorations de l’accessibilité dans l’interface. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-49360)

## ![Icône](/assets/aem.png) Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Auto-assistance

* **Newsletter AEM**

   Consultez la dernière newsletter [d’](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)Adobe Experience Manager.

* **AEM as a Cloud Service - Configuration du service Dynamic Media Cloud**

   Une nouvelle option est disponible lorsque vous configurez le service Dynamic Media Cloud :

   **Publication** sélective : lorsque vous sélectionnez cette option, cela signifie que les ressources sont publiées automatiquement pour les  sécurisées uniquement et peuvent être publiées explicitement dans AEM sans publication dans DMS7 pour les  de dans le domaine public.

   See [Configuring Dynamic Media Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services).

* **Contenu multimédia dynamique - Imagerie dynamique**

   L’ensemble de la rubrique d’aide d’Smart Imaging a été mis à jour avec de nouvelles informations, y compris des exemples de ressources d’image qui illustrent l’optimisation de Smart Imaging ajoutée.

   Voir [Smart Imaging](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Configuration de Contenu multimédia dynamique - Mode Scene7**

   Une nouvelle option Synchroniser tout le contenu est désormais disponible sur la page Configuration des médias dynamiques disponible dans **[!UICONTROL Outils > Services]** Cloud.

   Voir [Création d’une configuration](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services)de média dynamique.

* **AEM Assets Brand Portal prend en charge les ressources AEM en tant que service Cloud**

   Vous pouvez désormais publier des ressources à partir d’AEM Assets en tant que service Cloud vers AEM Assets Brand Portal.

   Voir [Configuration des ressources AEM avec le portail](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) de marque et [Publication des ressources sur le portail](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html)de marque.

* **Adobe Asset Link 2.0 version**

   Adobe Asset Link 2.0 prend en charge l’utilisation de plusieurs AEM   et prend en charge AEM en tant que service Cloud. AEM prend en charge les besoins des spécialistes du marketing pour configurer l’exécution automatique du processus de traitement des ressources lorsque des ressources sont transférées vers un dossier à l’aide d’Adobe Asset Link.

   See [Adobe Asset Link](https://helpx.adobe.com/fr/enterprise/using/adobe-asset-link.html).

### Nouveaux didacticiels Experience Manager

| Contenu | Description |
| -----------| ---------- |  
| [Configuration des outils du répartiteur local](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Découvrez comment faciliter la configuration, la validation et la simulation du [!UICONTROL répartiteur] localement. |
| [Configuration des outils de développement pour les projets AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | Le développement d’Adobe Experience Manager (AEM) nécessite un ensemble minimal d’outils de développement à installer et à configurer sur l’ordinateur du développeur. Ces outils prennent en charge le développement et la création de projets AEM. |
| [Configuration de l’exécution locale d’AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) peut être exécuté localement à l’aide d’AEM en tant que Jar QuickStart du SDK de service Cloud. Cela permet aux développeurs de déployer et de tester du code, une configuration et du contenu personnalisés avant de l’affecter au contrôle de code source, et de le déployer dans AEM en tant que  de service Cloud. |
| [Navigation](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | Explorez les principes de base de la navigation dans AEM Assets. |
| [Versions](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | Découvrez comment AEM crée et gère les versions des ressources. |
| [Intégration d’AEM - [!DNL Magento] à l’aide de [!UICONTROL Commerce Integration Framework]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | Cette vidéo vous guide tout au long de la configuration de l’intégration entre AEM et [!DNL Magento]AEM. |
| [Présentation de la pile d’architecture AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | L’archétype du projet CIF crée un projet CIF Adobe Experience Manager (AEM) minimal comme point de départ pour les projets clients utilisant les composants principaux CIF. |
| [Présentation d’OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Présentation d’OSGi, une architecture modulaire dynamique pour les applications Java qui constitue la base d’Adobe Experience Manager. |
| [Présentation du référentiel de contenu Java (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Cette section présente le référentiel de contenu Java (JCR) utilisé par Adobe Experience Manager. |
| [Présentation de Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Présentation d’une structure Web RESTful open source [!DNL Sling], qui fait partie de la pile technologique sous-jacente d’Adobe Experience Manager. |
| [Présentation du niveau Auteur et Publication](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Présentation des niveaux [!UICONTROL Auteur] et [!UICONTROL Publication] dans le cadre de l’architecture d’Adobe Experience Manager. |
| [Présentation du répartiteur](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | Présentation des fonctionnalités et fonctionnalités du répartiteur dans le cadre de l’architecture AEM. |
| [Introduction à l&#39;élaboration des composantes](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Présentation du développement de composants avec les sites Adobe Experience Manager. Comprend une introduction aux [!UICONTROL boîtes de dialogue], aux modèles Sling, aux scripts HTML et aux bibliothèques côté [!UICONTROL client.] |
| [Archétype de projet AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | Le projet AEM contient l’ensemble du code et des configurations pour une implémentation. The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. |
| [Présentation des composants principaux](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | Les composants [!UICONTROL principaux d’AEM] sont des composants d’ensemble standard à utiliser avec Adobe Experience Manager. |
| [Utilisation du fichier JAR de démarrage rapide d’AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | Découvrez comment installer et exécuter une instance locale d’Adobe Experience Manager en quelques minutes avec le fichier jar [!UICONTROL de démarrage rapide]AEM. |

### Ressources d’aide supplémentaires

* [AEM en tant que Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/landing/home.html)
* [Page d’accueil Formation et assistance AEM 6.5](https://helpx.adobe.com/fr/support/experience-manager/6-5.html)
* [Page d’accueil Formation et assistance AEM 6.4](https://helpx.adobe.com/fr/support/experience-manager/6-4.html)
* [Page d’accueil Formation et assistance AEM 6.3](https://helpx.adobe.com/fr/support/experience-manager/6-3.html)
* [Page d’accueil Formation et assistance AEM 6.2](https://helpx.adobe.com/fr/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://helpx.adobe.com/fr/experience-manager/cloud-manager/user-guide.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/fr/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/fr-FR/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notes de mise à jour de Livefyre](https://docs.adobe.com/content/help/fr-FR/livefyre/using/release-notes/c-rn.html)

## ![Icône](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html)

### Nouveaux didacticiels de Campaign Standard {#tutorials-acs}

| Contenu | Description |
| -----------| ---------- |  
| [Substitution de  - Test des courriers électroniques à l&#39;aide de ciblés](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | Testez vos messages électroniques à l&#39;aide de la fonction de substitution de . |

### Autres ressources d’aide Campaign

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/fr/support/campaign/standard.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)    – [Calendrier des versions](https://helpx.adobe.com/fr/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/fr/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/fr-FR/RN.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![Icône](/assets/magento.png) [!DNL Magento] {#magento}

Pour les notes de mise à jour de Magento, veuillez consulter :

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icône](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] est une solution complète pour la gestion des pistes et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Pour plus d’informations, consultez les notes [!DNL Marketo] de [](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) mise à jour.

### Fonctionnalités à venir

Les fonctionnalités suivantes seront publiées tout au long du trimestre :

| Fonction | Description |
|------|---------|
| [!DNL Bizible] | <ul><li>Nouvelle segmentation basée sur un compte</li><li>Enregistrement des filtres spécifiques au tableau de bord</li><li>Exportation de tableaux de bord Bizible au format PDF</li></ul> |
| Connect de ventes | Composition des mises à jour/améliorations de Windows et du Centre de commandes |

### Annonces

**Centre de succès Marketo Engage :** lancement en février 2020. Le centre de succès est un centre d’aide intégré qui vous permet de rechercher des documents produit et la communauté, de lancer des guides pratiques, d’accéder au contenu d’adoption, etc. Remarque : cette fonctionnalité sera lancée en version bêta en ANZ et sera déployée en Amérique du Nord plus tard dans le trimestre.

### Dépréciations

* **Paramètre de l’API de ressource &quot;_method&quot; :** Après septembre 2020, les points de fin d’API de ressources n’accepteront plus `_method` de transmettre des paramètres de  dans un corps POST pour contourner les limitations de longueur d’URI.
* **Dépréciation de la prise en charge d’Internet Explorer :** a compter de la version du 31 juillet 2020, l’interface utilisateur de Marketo Engage ne sera plus prise en charge dans Internet Explorer.

Pour obtenir des notes de mise à jour cumulatives et historiques, reportez-vous à la page [Notes de mise à jour de Marketo](https://docs.marketo.com/x/CgA6Ag).

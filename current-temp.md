---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: ht
source-git-commit: 46ec8789a918fa57533130ccb4b66dce651cb7fc

---


# Notes de mise à jour d’Adobe Experience Cloud    - Mars 2020

![Bannière](/assets/experience-cloud-banner-3.png)

Nouvelles fonctionnalités et correctifs d’[!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>Cette page comporte du contenu publié avant la date de publication et peut faire l’objet de modifications avant la publication planifiée.

>[!NOTE]
>Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) pour être averti par e-mail de la publication des prochaines versions. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : mars 2020**

Dernière mise à jour : 11 mars 2020

* [État du système Adobe](#status)
* [Interface d’Experience Cloud et services principaux](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) - Date de lancement : **12 mars 2020** (mise à jour : 27 mars 2020)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html) (liens vers l’aide de la solution)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/fr/primetime/user-guide.html) (liens vers l’aide de la solution)
* [Nouvelle documentation et nouveaux tutoriels](#selfhelp)

Vous cherchez la page d’accueil de l’aide ? Voir la [documentation d’Adobe Experience Cloud](https://docs.adobe.com/content/help/fr-FR/experience-cloud/user-guides/home.html).

(Les dates de lancements de chaque produit peuvent varier.)

## ![Icône](/assets/adobe.png) État du système Adobe {#status}

[!UICONTROL État du système Adobe] fournit des informations détaillées, des mises à jour d’état et des notifications par e-mail relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

**Nouveautés**

* Avec votre Adobe ID, vous pouvez vous abonner à des notifications d’événement avec plus de granularité et associées au niveau de l’offre de produit et des modules complémentaires. Recherchez cette nouvelle fonctionnalité dans les produits Experience Cloud, où le processus d’abonnement automatique affiche des sous-offres pour des produits et services auxquels vous pourriez vouloir vous abonner. Cette amélioration devrait réduire considérablement le volume de notifications que vous recevez et rendre les notifications plus pertinentes par rapport aux produits et fonctionnalités que vous utilisez.  Rendez-vous sur [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nouvelles fonctionnalités et améliorations disponibles dès maintenant**

| Fonction | Description |
| -----------| ---------- |
| Abonnement automatique personnalisé par sous-offres de produits | <ul><li>Abonnement automatique par offre de produits ou modules complémentaires pour produits Experience Cloud.</li><li>Les notifications d’événement reçues sont pertinentes par rapport à vos préférences en matière de produit et d’offre de produit.</li></ul> |
| Expérience personnalisée orientée sur les préférences de l’utilisateur | <ul><li>Les préférences de fuseau horaire basées sur le paramètre du navigateur sont utilisées dans les notifications par courrier électronique.</li><li>Confirmation par courrier électronique envoyée lors de l’abonnement/du désabonnement avec toutes les préférences sélectionnées.</li></ul> |
| Meilleure diffusion des messages d’événement | <ul><li>Historique des événements trié selon les mises à jour chronologiques des événements.</li><li>Date et heure de la résolution de l’événement ajoutée aux publications fermées majeures/mineures.</li></ul> |

## ![Icône](/assets/ec_appicon_24.png) Interface d’Experience Cloud et services principaux {#ecloud}

Nouvelles fonctionnalités et correctifs pour l’interface d’Experience Cloud, notamment pour l’administration et les services principaux (attributs du client, audiences, déclencheurs, cookies, etc.).

| Fonction | Date de publication | Description |
| ----|----|---- |
| Outil d’administration - Affichage des détails utilisateur | 26 février 2020 | Les administrateurs peuvent afficher une liste triable et filtrable de tous les utilisateurs d’Experience Cloud et de leurs détails dans le nouvel outil d’administration. Les détails de l’utilisateur incluent l’accès au produit d’un utilisateur, ses rôles et les informations de dernier accès. Voir l’aide de [l’outil d’administration Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) pour en savoir plus. |

### Domaine de produit unifié

Adobe met à jour l’en-tête de domaine et d’interface afin d’unifier et d’améliorer votre expérience dans toutes les applications Experience Cloud. Ces améliorations sont conçues pour fluidifier votre utilisation de manière simple, mais importante. Ces améliorations ne modifieront pas vos processus actuels.

Les mises à jour comprennent les éléments suivants :

* Nouvelles URL de solution : `experience.adobe.com/<application name>` :
   * À terme, tous les produits adopteront ce modèle d’URL. Recherchez de nouvelles URL pour qu’elles prennent effet tout au long du mois.
   * Navigateurs pris en charge : [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] et [!DNL Opera] (versions les plus récentes). **Remarque** : bien que l’interface d’Experience Cloud prenne en charge ces navigateurs, les solutions individuelles peuvent ne pas tous les prendre en charge. (Par exemple, [Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/admin/sys-reqs.html) ne prend pas en charge [!DNL Opera] et [Target](https://docs.adobe.com/help/fr-FR/target/using/implement-target/before-implement/supported-browsers.html) ne prend pas en charge [!DNL Safari].)
   * ([!DNL Safari] uniquement) Le changement de domaine peut entraîner des problèmes de cookies dans [!DNL Safari]. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité de [!DNL Safari], vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Experience Cloud de fonctionner sur ce nouveau domaine.
* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide des produits : [!UICONTROL Experience League] est intégré dans le produit afin qu’une recherche d’aide comprenne également les résultats des forums de la communauté et du contenu vidéo. Cette modification simplifie l’accès à davantage de contenu et vous permet de tirer le meilleur parti d’Experience Cloud. De plus, vous pouvez cliquer sur **[!UICONTROL Aide]** > **[!UICONTROL Commentaires]** pour signaler des problèmes ou partager vos idées avec Adobe.
* Notifications améliorées : le menu déroulant [!UICONTROL Notifications] comporte désormais deux onglets, l’un pour vos propres notifications de produit et l’autre pour les annonces de produits globales.

**Remarque :** la page [!UICONTROL Flux] a été abandonnée en janvier 2020. Vous trouverez un avis d’obsolescence dans le produit.

Pour consulter la documentation du produit, consultez l’aide [Experience Cloud](https://docs.adobe.com/content/help/fr-FR/core-services/interface/experience-cloud.html).

## ![Icône](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notes de mise à jour d’[!UICONTROL Experience Platform], d’[!UICONTROL Experience Platform Launch], d’[!UICONTROL Identity Service], de Journey Orchestration, de Mobile Services et des bulletins de sécurité.

* [Notes de mise à jour d’Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Orchestration du parcours](#journey)
* [Mobile Services et SDK mobiles](#mobile)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/fr/security.html)    (Tous les produits Adobe)

### Experience Platform Launch {#launch}

Pour consulter les notes de mise à jour et la documentation du produit, voir [Experience Platform Launch](https://docs.adobe.com/content/help/fr-FR/launch/using/intro/release-notes/current.html).

### Orchestration du parcours {#journey}

Grâce à Adobe Experience Platform, orchestrez des parcours clients individuels à l’échelle sur des canaux d’expérience en anticipant de manière intelligente les besoins de chaque individu en temps réel, quel que soit l’endroit où leur parcours les mène.

La version pour le premier trimestre a été publiée. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

#### Ressources supplémentaires    pour Journey Orchestration

[Documentation](https://docs.adobe.com/content/help/fr-FR/journeys/using/journey-orchestration-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/journeys/using/release-notes/release-notes.html) - [Tutoriels vidéos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services et SDK mobiles {#mobile}

**iOS v4.19.1**

* Général - Résolution d’un blocage potentiel lorsque des énumérations [!UICONTROL Swift] sont incluses dans les données contextuelles des appels de suivi.
* [!DNL Target] – L’ID de [!DNL Target] session sera désormais ajouté comme paramètre de données contextuelles `a.target.sessionId` dans l’accès [!UICONTROL Analytics-for-Target] interne envoyé à Adobe Analytics.

**Android v4.18.1**

* [!DNL Target] – L’ID de [!DNL Target] session sera désormais ajouté comme paramètre de données contextuelles « a.target.sessionId » dans l’accès [!UICONTROL Analytics-for-Target] interne envoyé à Adobe Analytics.

## ![Icône](/assets/analytics_cloud_appicon_24.png) [!DNL Analytics] {#analytics}

Date de la version : **12 mars 2020**

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices) (mise à jour : 27 mars 2020)
* [AppMeasurement](#appm)

Pour consulter la documentation du produit, voir [Accueil de l’aide Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/landing/home.html).

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

* **Plusieurs suites de rapports dans [!UICONTROL Analysis Workspace ]** : vous pouvez désormais importer les données de plusieurs suites de rapports dans un seul projet [!UICONTROL Analysis Workspace] pour les afficher côte à côte. [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Audience Optimization d’Experience Cloud** : cette fonctionnalité vous permet de publier des segments dans Experience Cloud dans les 8 heures (au lieu des 48 heures de traitement nécessaires précédemment). [En savoir plus...](https://docs.adobe.com/content/help/fr-FR/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace - modèle de tutoriel de formation** : ce nouveau modèle standard vous guide à travers la terminologie courante et les étapes nécessaires à la création de votre première analyse dans Workspace. Il est disponible sous forme de modèle standard dans le modal [!UICONTROL Nouveau projet] et remplace l’exemple de projet qui existe aujourd’hui pour les nouveaux utilisateurs qui n’ont pas d’autres projets dans leur liste.

#### Correctifs

* Correction d’un problème dans [!UICONTROL Reports &amp; Analytics] qui empêchait le téléchargement des rapports `.xls`. Ce problème affectait des clients utilisant des devises différentes du dollar américain et de l’euro. (AN-206541, AN-204008)
* Le déploiement d’un nouveau conteneur a résolu plusieurs problèmes client liés au changement d’organisation dans Experience Cloud. (AN-200844, AN-186920)
* Correction d’un problème lié au fait que l’exécution d’une ventilation sur l’élément de ligne _Non spécifié_ (ou sur certains autres éléments de ligne de rapport) sans inclure _Non spécifié (Aucun)_ dans les filtres de recherche de la ventilation ne renvoyait aucun résultat dans la ventilation.
* Correction d’un problème qui se produisait lors de l’utilisation d’une dimension classifiée : la mesure entrée ou sortie ne correspondait pas au nombre total d’éléments de ligne dans la ventilation.
* Correction d’un problème qui empêchait les modèles première touche et dernière touche dans Attribution IQ de calculer le crédit correctement pour certains éléments de ligne sur certaines dimensions prêtes à l’emploi.
* Correction d’un problème lié au renvoi de résultats incorrects lors de la ventilation d’une dimension de date par une autre dimension de date.
* Correction d’un problème qui entraînait parfois le mauvais comptage des mesures entrée et sortie dans une application à « Non spécifié » dans un rapport de dimension classifiée.

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout    ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Abandon du paramètre **[!UICONTROL Niveau de conversion]** | 3 mars 2020 | Le paramètre [Niveau de conversion](https://docs.adobe.com/content/help/fr-FR/analytics/admin/admin-tools/general-acct-settings-admin.html) qui ne fonctionnait pas dans **[!UICONTROL Outils d’administration] > [!UICONTROL Suite de rapports] > [!UICONTROL Paramètres du compte général]** sera supprimé de l’interface utilisateur le 12 mars 2020. |
| Abandon de l’**[!UICONTROL archive de tableau de bord]** | 27 mars 2020 | Le paramètre **[!UICONTROL Afficher l’archive]** sous **[!UICONTROL Gérer les tableaux de bord]** dans [!UICONTROL Reports &amp; Analytics] ne sera plus disponible à compter du mois d’octobre 2020. |
| Fin de la prise en charge de TLS 1.1 | 3 octobre 2019 | D’ici le 31 mars 2020, Adobe Analytics supprimera la prise en charge de TLS 1.1. Ce changement s’inscrit dans le cadre des efforts que nous déployons pour respecter les meilleures normes de sécurité et promouvoir la sécurité des données de nos clients. |
| Nouveau domaine Adobe Analytics | 18 décembre 2019 | Le 16 janvier 2020, Adobe Analytics a commencé passer à un nouveau domaine : `https://experience.adobe.com/analytics.`<br>**Remarque :** cette modification s’applique à tous les utilisateurs accédant à Analytics avec leur Adobe ID ou Enterprise ID.<ul><li>Ce changement de domaine peut créer des problèmes de cookies lors du chargement d’Analytics dans Safari. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité [!DNL Safari], vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Analytics de fonctionner sur ce nouveau domaine Adobe Experience Cloud. Vous pouvez utiliser d’autres navigateurs sans problème, car cette particularité affecte uniquement les utilisateurs de [!DNL Safari].</li><li>Le changement de domaine peut entraîner l’arrêt du fonctionnement d’[!UICONTROL Activity Map] pour certains clients [dans des cas spécifiques](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vie : API héritées d’Analytics | 9 janvier 2020 | En novembre 2020, les services d’API hérités d’Analytics suivants arriveront en fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner. <ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Nous avons mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | Pour les clients basés à Londres et à Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fin de vie d’Ad Hoc Analysis | 6 août 2018 | Adobe a annoncé la prochaine fin de vie d’Ad Hoc Analysis. La date de fin de vie sera communiquée dès que possible. Pour obtenir de plus amples informations, voir le site [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Voir [Notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/fr-FR/analytics/implementation/appmeasurement-updates.html). La version 2.20.0 a été publiée le 5 mars 2020.

## ![Icône](/assets/audience-manager.png) Audience Manager {#aam}

Nouvelles fonctionnalités et mises à jour d’Audience Manager :

| Fonction | Description |
| -----------| ---------- |
| [Feuille de calcul des outils de gestion en bloc](https://docs.adobe.com/help/fr-FR/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | Une nouvelle version de la feuille de calcul est disponible pour vous. Cette version corrige un problème rencontré par certains clients lors de la création de modèles algorithmiques avec le système d’exploitation Windows 64 bits. Téléchargez la dernière version [ici](https://docs.adobe.com/help/fr-FR/audience-manager/user-guide/reference/bulk-management-tools/assets/BAAAM_V2_20200311.xlsm). |

### Correctifs et améliorations {#aam-fixes-and-improvements}

* Correction d’une erreur qui empêchait les clients de mettre à jour le nom d’un segment en raison d’une autorisation RBAC manquante : [!UICONTROL VIEW_ALL_DESTINATIONS]. L’autorisation [!UICONTROL VIEW_ALL_DESTINATIONS] ne devrait pas être requise pour mettre à jour un segment. Pour plus d’informations sur les autorisations RBAC, consultez [Administration (Contrôles RBAC)](https://docs.adobe.com/help/fr-FR/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AAM-52760)
* Correction d’une erreur dans l’[Explorateur de données](https://docs.adobe.com/help/fr-FR/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) qui empêchait certains clients de voir le contenu dans la section d’informations de base et les opérateurs dans le générateur d’expression, lors de la création de caractéristiques en fonction de signaux de l’[!UICONTROL Explorateur de données]. (AAM-53130)
* Correction d’une erreur qui empêchait certains clients de charger l’interface [!UICONTROL Audience Marketplace]. (AAM-52070)
* Correction d’une erreur dans l’[!UICONTROL API de segments] où, en raison de certains segments ne possédant pas de description, l’interface se figeait lorsque les utilisateurs essayaient d’accéder à ces segments, ce qui forçait les utilisateurs à quitter cette page. (AAM-53071)
* Plusieurs améliorations de l’accessibilité de l’interface. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058, AAM-49392)

## ![Icône](/assets/aem.png) Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Mises à jour de produit

* **AEM 6.5.4.0**
AEM 6.5, Service Pack 4.0 (version 6.5.4.0 publiée le 5 mars 2020) est une mise à jour importante qui inclut de nouvelles fonctionnalités, des améliorations client importantes, une amélioration des performances, de la stabilité et de la sécurité, publiées depuis la disponibilité générale d’AEM 6.5, avril 2019.
   * [Nouveautés d’Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/fr-FR/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [Notes de mise à jour](https://helpx.adobe.com/fr/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Livrables de la mise à jour d’AEM Forms](https://helpx.adobe.com/fr/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4 Service Pack 8.0 (6.4.8.0 publié le 5 mars 2020), est une mise à jour importante qui contient des correctifs client clés, publiée depuis la mise à disposition d’AEM 6.4 en avril 2018.
   * [Notes de mise à jour](https://helpx.adobe.com/fr/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/fr/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3 Service Pack 3, Cumulative Fix Pack 8 (6.3.3.8 publié le 5 mars 2019), est une mise à jour importante qui contient des correctifs client clés, publiée depuis la mise à disposition d’AEM 6.3 en avril 2017.
   * [Notes de mise à jour](https://helpx.adobe.com/fr/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/fr/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4, Service Pack 6 (6.4.6 publié le 5 mars 2020) modifie la manière dont AEM Assets est configurée avec [!UICONTROL Brand Portal.] En outre, cette version inclut d’autres améliorations et correctifs de bogues.
   * [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Auto-assistance

* **AEM en tant que Cloud Service - autorisations basées sur les rôles**

   Cloud Manager dispose de rôles préconfigurés avec des autorisations appropriées. Chacun des rôles possède des autorisations spécifiques, des tâches ou des autorisations préconfigurées associées à chaque rôle. La rubrique d’aide [Autorisations basées sur les rôles](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) identifie les fonctionnalités disponibles et les rôles pouvant les exécuter.

* **AEM en tant que Cloud Service – Dispatcher**

   Les sections [Dispatcher et CDN](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) et [Invalidation du cache du répartiteur explicite](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) ont été mises à jour pour rendre de manière plus claire les options disponibles et leur fonctionnement.

* **Configurer des AEM Assets avec Brand Portal**

   AEM Assets est désormais configuré avec [!UICONTROL Brand Portal] via Adobe I/O qui fournit un jeton IMS d’autorisation du client Brand Portal. Précédemment, il était configuré dans l’interface de Classic par le biais de la [!UICONTROL passerelle OAuth héritée.]
Reportez-vous à [Configurer des AEM Assets avec Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **AEM en tant que Cloud Service - Recadrage intelligent dans Dynamic Media**

   Une nouvelle option est disponible dans AEM en tant que Cloud Service lorsque vous travaillez avec le recadrage intelligent dans le composant Dynamic Media :

   **Activer la correspondance du rapport d’aspect** : sélectionnez cette option pour permettre à Dynamic Media de sélectionner un rendu de recadrage intelligent qui correspond mieux au rapport d’aspect de l’image d’origine.
Reportez-vous à [Travailler avec le recadrage intelligent](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop).

### Communauté

* **Webinars de développement de compétences dans AEM**

   * Sites AEM - à compter du 17 mars 2020, apprenez les blocs élémentaires de la création de contenu ainsi que les concepts et les opérations essentiels d’AEM Sites. [Inscrivez-vous maintenant](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register).
   * AEM Assets - à compter du 19 mars 2020, perfectionnez votre expertise en gestion des actifs numériques et découvrez les bases de Brand Portal, de [!UICONTROL Dynamic Media], d’[!UICONTROL Asset Link], etc. [Inscrivez-vous maintenant](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register).

### Ressources supplémentaires

* [AEM en tant que Cloud Service](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-service/landing/home.html)
* [Formation et assistance pour AEM 6.5 – Accueil](https://helpx.adobe.com/fr/support/experience-manager/6-5.html)
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

### Campaign Classic

* [Mise à jour Campaign Classic 19.1.4](https://docs.adobe.com/content/help/fr-FR/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Ressources supplémentaires

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/fr/support/campaign/standard.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)    – [Calendrier des versions](https://helpx.adobe.com/fr/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/fr/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/fr-FR/RN.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/control-panel/using/release-notes.html)

## ![Icône](/assets/advertising_cloud_appicon_24.png) Advertising Cloud {#adcloud}

Mise à jour le 20 mars 2020 pour la version du 21 mars :

| Affichage | Fonction |
|------|---------|
| [!UICONTROL Portfolios] | Pour obtenir des instructions sur la manière de gérer vos portfolios afin de tenir compte des changements de trafic dus au COVID-19, contactez votre gestionnaire de compte. |
| Campagnes Google Ads et Microsoft Ads | Dans les portfolios optimisés avec l’option « Optimiser automatiquement les valeurs d’ajustement d’enchères », Advertising Cloud n’optimise plus automatiquement les paramètres d’ajustement d’enchères pour les campagnes à l’aide de la stratégie d’enchères au coût par clic améliorée (eCPC). Le moteur de recherche optimise tous les ajustements d’enchères au moment de l’enchère. Advertising Cloud optimise toujours les enchères de base et, lorsque l’option « Ajuster automatiquement les limites du budget de la campagne » est activée, le budget de la campagne. |
| [!UICONTROL Alertes bêta] | (Fonction bêta) Vous pouvez désormais créer des modèles d’alerte afin d’identifier le moment où un portfolio répond à des conditions spécifiques, comme des mesures de performances, pendant une période spécifiée, puis générer une alerte. Vous pouvez créer des alertes au niveau du portfolio depuis **[!UICONTROL Insights &amp; Reports]** > **[!UICONTROL Alertes (bêta)]**, mais pas depuis **[!UICONTROL Optimisation]** > **[!UICONTROL Portfolios)]**. **Remarque :** Les alertes créées à partir de la version héritée d’Alertes bêta, qui a été remplacée en janvier, ne sont plus disponibles. |
| [!UICONTROL Admin] > [!UICONTROL Propriétés de transaction] | Une nouvelle colonne « ID de propriété » affiche l’ID de propriété unique pour chaque propriété de transaction. Vous pouvez rechercher n’importe quelle chaîne contenue dans les valeurs de colonne. |

## ![Icône](/assets/magento.png) [!DNL Magento] {#magento}

Pour les notes de mise à jour de Magento, veuillez consulter :

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icône](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] est une solution complète pour la gestion des pistes et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Date de publication : 21 février 2020

* **Microsoft Dynamics _Modification de propriétaire dans Microsoft_ Action de processus** : Modifiez un prospect ou un propriétaire de contact directement à partir de Marketo Engage.
* **Améliorations des appels d’API :**
   * API de gestion des utilisateurs
   * API de schéma d’objet personnalisé
   * API de règles de redirection de page d’entrée
* **Mise en cache des descripteurs de formulaire** : Améliorations apportées aux pages d’entrée et aux formulaires.

Pour plus d’informations, voir les Notes de mise à jour de [!DNL Marketo] de [février 2020](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720).

### Fonctionnalités à venir

Les fonctionnalités suivantes seront publiées tout au long du trimestre :

| Fonction | Description |
|------|---------|
| [!DNL Bizible] | <ul><li>Nouvelle segmentation basée sur un compte</li><li>Enregistrement des filtres spécifiques au tableau de bord</li><li>Exportation de tableaux de bord Bizible au format PDF</li></ul> |
| Connect de ventes | Composition des mises à jour/améliorations de Windows et du Centre de commandes |

### Annonces

**Centre de succès Marketo Engage :** lancement en février 2020. Le centre de succès est un centre d’aide intégré qui vous permet de rechercher des documents produit et la communauté, de lancer des guides pratiques, d’accéder au contenu d’adoption, etc. Remarque : Cette fonctionnalité sera lancée en version bêta en ANZ et sera déployée en Amérique du Nord plus tard dans le trimestre.

### Dépréciations

* **Paramètre de l’API de ressource &quot;_method&quot; :** Après septembre 2020, les points de fin d’API d’actif n’accepteront plus &quot;_method&quot; pour transmettre les paramètres de requête dans un corps POST afin de contourner les limitations de longueur d’URI.
* **Dépréciation de la prise en charge d’Internet Explorer :** A compter de la version du 31 juillet 2020, l’interface utilisateur de Marketo Engage ne sera plus prise en charge dans Internet Explorer.

Pour obtenir des notes de mise à jour cumulatives et historiques, reportez-vous à la page [Notes de mise à jour de Marketo](https://docs.marketo.com/x/CgA6Ag).

## ![Icône](/assets/experience-cloud.png) Nouvelle documentation et nouveaux tutoriels {#selfhelp}

Articles et vidéos d’auto-assistance nouveaux et récents. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| Solution | Contenu | Description |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | Vidéo - [Création de plusieurs pages de catégorie et de produit](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | Découvrez comment créer un projet CIF Adobe Experience Manager (AEM) minimal comme point de départ de projets clients à l’aide des composants principaux de CIF. Appliquez un thème et un style CSS aux composants et inspectez un nouveau projet AEM CIF généré par l’archétype. Découvrez également comment CSS et JavaScript utilisé par les composants principaux de CIF sont organisés. |
| [!UICONTROL AEM Forms] | Article - [Authentification à l’auteur AEM à l’aide d’OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Découvrez comment configurer votre application sur le portail OKTA et sur les paramètres que vous utilisez généralement pour enregistrer une nouvelle application. |
| [!UICONTROL AEM Commerce] | Tutoriel - [Personnaliser les composants principaux CIF](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | Vérifiez plusieurs points d’extension différents fournis par les composants principaux de CIF et AEM en général. Les composants principaux de CIF fournissent un jeu standard de composants Commerce qui peuvent être utilisés pour accélérer un projet qui intègre des solutions Adobe Experience Manager (AEM) et Magento. |
| [!DNL Adobe Campaign] - destinations de l’audience | Vidéo - [Création d’une audience…](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Créez une audience dans Campaign Standard à l’aide du [!UICONTROL créateur de segments d’Adobe Experience Platform]. Vous pouvez accéder à cette fonctionnalité directement dans Adobe Campaign Standard via les modules [!UICONTROL Audiences]. |
| [!DNL Adobe Campaign] - destinations de l’audience | Vidéo - [Activation des audiences Adobe Experience Platform dans un flux de travail marketing](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Découvrez comment activer les [!UICONTROL requêtes d’audience de Data Services] au sein d’un flux de travail à l’aide de l’activité [!UICONTROL Lecture d’audience]. |
| [!DNL Adobe Campaign] | Tutoriel - [Notification Push avec Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | Envoyez des notifications Push personnalisées et segmentées vers les appareils mobiles iOS et Android. Ce tutoriel vous guidera à travers les étapes impliquées dans l’envoi de notifications Push depuis Adobe Campaign et la réception de ces notifications dans votre application Android. |
| [!DNL Adobe Campaign] | Vidéo - [Création d’une notification Push](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Créez une notification Push dans Adobe Campaign Standard. Vous pouvez envoyer des notifications Push personnalisées et segmentées vers les appareils mobiles iOS et Android. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Vérification du statut d’une tâche d’ingestion de données](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | Découvrez comment vérifier le statut d’une tâche d’ingestion de données et si les données ont été ingérées dans Adobe Experience Platform depuis Adobe Campaign Standard. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Modification du mappage des données](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | Découvrez comment vérifier le statut et modifier le mappage des données. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Mappage des événements d’expérience](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Découvrez comment mapper les événements d’expérience dans Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Mappage des ressources personnalisées](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Découvrez comment mapper différents types de données entre Adobe Campaign Standard et Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Compréhension du connecteur de données d’Adobe Experience Platform](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Découvrez comment rendre vos données disponibles sur Adobe Experience Platform en mappant les données XTK (les données ingérées dans Campagne) aux données des modèles de données d’expérience (XDM) sur Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Mappage des données de tableau sources](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Apprenez à mapper vos données sources ou vos profils de test avec Adobe Experience Platform. |
| [!DNL Adobe Campaign]- destinations de l’audience | Vidéo - [Modification de la dimension de ciblage d’une diffusion pour une audience de plateforme](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Découvrez comment modifier la dimension de ciblage d’une diffusion pour une audience de plateforme en dehors du tableau de profil principal dans Adobe Campaign Standard. |
| [!DNL Adobe Campaign] | Vidéo - [Gestion de données importante sur Snowflake](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Tirez profit du connecteur Snowflake dans Adobe Campaign Classic. |
| [!DNL Adobe Campaign] - destinations de l’audience | Article - [Aperçu des destinations d’audience (Beta)](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Découvrez comment tirer profit des données de profil centralisées et consolidées d’Adobe Experience Platform pour vos campagnes marketing dans Adobe Campaign Standard. |
| [!DNL Adobe Target] - SDK Mobile | Tutoriel - [Personnaliser les expériences d’application avec Adobe Target](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Mettez en œuvre Adobe Target dans votre propre application Android. Validez la configuration du SDK Mobile Services et implémentez des requêtes [!DNL Target] telles que la prérécupération de contenu, le blocage des requêtes, etc. |
| Adobe Analytics | Vidéo - [Session extraordinaire de l’Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Regardez des extraits de la session extraordinaire haute technologie du Summit 2019. |
| Adobe Analytics | Vidéo - [Présentation des mesures calculées dans Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Découvrez les principes de base de la création de [!UICONTROL mesures calculées] dans [!UICONTROL Customer Journey Analytics]. |
| Adobe Analytics | Vidéo - [Session extraordinaire de l’Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Regardez des extraits de la session voyage et hospitalité du Summit 2019. |
| Adobe Analytics | Vidéo - [Session extraordinaire de l’Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Regardez des extraits de la session vente au détail du Summit 2019. |
| Adobe Analytics | Vidéo - [Cas d’utilisation client : le groupe Accent investit dans l’expérience client pour stimuler ses ventes](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Découvrez comment le groupe Accent utilise Adobe Experience Cloud pour créer des expériences numériques en toute transparence. |
| Adobe Analytics | Vidéo - [Cas d’utilisation client : ServiceNow obtient les bons insights pour se connecter aux prospects](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Découvrez comment [!DNL ServiceNow] obtient des données exploitables de ses canaux marketing et améliore son retour sur investissement sur le référencement publicitaire payant avec Adobe Advertising Cloud et Adobe Analytics. |
| Adobe Analytics | Vidéo - [Adobe Analytics - Plus que des données : intelligence du client](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | Découvrez un marketing piloté par les données et comment emmener la maturité de vos analyses des données aux insights, puis à l’action. |
| Adobe Analytics | Vidéo - [Adobe Sensei et Adobe Analytics - Version étendue](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Afficher les fonctionnalités clés d’Adobe Analytics avec la technologie Adobe [!DNL Sensei,] y compris [!UICONTROL la détection des anomalies,] [!UICONTROL la contribution de l’analyse,] [!UICONTROL les alertes intelligentes], [!UICONTROL la mise en grappe,] [!UICONTROL Segment IQ] et [!UICONTROL la modélisation de propension]. |
| Adobe Analytics | Vidéo - [Comment Adobe Analysis Workspace peut modifier votre activité](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Découvrez comment vous pouvez réaliser des analyses ad hoc, des analyses flexibles des analyses de cohortes et des analyses d’abandons à l’aide d’[!UICONTROL Analysis Workspace]. Vous pouvez également partager l’environnement de travail d’analyse avec toutes les membres de votre entreprise et sa fonction glisser et déposer permet à chacun d’analyser les données facilement et d’obtenir des insights rapidement. |
| Adobe Analytics | Vidéo - [Cas d’utilisation client : The Home Depot innove dans la gestion de l’expérience client](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Découvrez comment [!DNL Home Depot] utilise les solutions Adobe pour créer de la loyauté envers la marque et de la satisfaction client grâce à une expérience d’achat personnalisée. |
| Adobe Analytics | Présentation - [Compréhension de Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Découvrez comment [!UICONTROL Customer Journey Analytics] d’Adobe, un service d’application conçu sur [!DNL Adobe Experience Platform], apporte [!UICONTROL Analysis Workspace] dans Experience Platform. Cette fonctionnalité permet d’activer l’analyse multicanale sur l’un de vos jeux de données [!DNL Adobe Experience Platform]. |
| Adobe Analytics | Vidéo - [Attribution cross-canal dans Analytics du parcours client](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | Découvrez comment vous pouvez utiliser les visualisations pour afficher l’attribution (donner du crédit) entre les canaux dans [!UICONTROL Customer Journey Analytics]. |
| Adobe Analytics | Article - [Astuces clients pour continuer votre parcours d’apprentissage d’Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Rencontrez trois clients Adobe possédant des conseils et des astuces pour vous concernant la manière dont tirer le meilleur d’Adobe Analytics. |
| Adobe Analytics | Vidéo - [Création de visualisation cross-canal dans Analytics du parcours client](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | Découvrez comment [!UICONTROL Customer Journey Analytics] vous permet de créer des visualisations qui incluent des données depuis plusieurs jeux de données répartis sur plusieurs canaux, y compris la fusion des données par visiteur. |
| Adobe Analytics | Vidéo - [Déplacez vos mesures calculées d’Adobe Analytics vers Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Découvrez des conseils pour recréer vos [!UICONTROLCmesures calculées] Analytics dans [!UICONTROL Customer Journey Analytics]. |

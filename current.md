---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 2282dd7a9b0575021f2262e43f644af4b1dc3f0b

---


# Accès anticipé - Notes de mise à jour d’Adobe Experience Cloud - mars 2020

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!IMPORTANT]
>Cette page contient une version anticipée du contenu et peut être modifiée avant la version définitive qui sera publiée.

>[!NOTE]
>Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) pour être averti par e-mail de la publication des prochaines versions. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : mars 2020**

(Les dates de lancements de chaque produit peuvent varier)

* [État du système Adobe](#status)
* [Interface d’Experience Cloud et services principaux](#ecloud)
* [Experience Platform](#platform)
* [Orchestration du voyage](#journey)
* [Mobile Services et SDK mobiles](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (liens vers l’aide de la solution)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (liens vers l’aide de la solution)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [Nouvelle documentation et nouveaux didacticiels](#selfhelp)

Vous cherchez la page d’accueil de l’aide ? Voir la [documentation d’Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## État du système Adobe {#status}

[!UICONTROL État du système Adobe] fournit des informations détaillées, des mises à jour d’état et des notifications par e-mail relatives aux produits cloud Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/).

**Nouveautés**

* Avec votre Adobe ID, vous pouvez vous abonner aux notifications  avec plus de granularité, jusqu’au niveau de l’offre de produit et du module complémentaire. Recherchez cette nouvelle fonctionnalité dans les produits Experience Cloud, où le processus de  d’auto- affiche des sous-offres pour les produits et services auxquels vous souhaitez vous abonner. Cette amélioration devrait réduire considérablement le volume des notifications que vous recevez et rendre les notifications plus pertinentes pour les produits et fonctionnalités que vous utilisez.  Rendez-vous sur [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nouvelles fonctionnalités et améliorations disponibles dès maintenant**

| Fonction | Description |
| -----------| ---------- |
| personnel personnalisé  par sous-offres de produits | <ul><li> d’auto- par offre de produits ou modules complémentaires pour les produits Experience Cloud.</li><li>Les notifications  reçues sont pertinentes pour vos préférences de produit et d’offre de produit.</li></ul> |
| Expérience personnalisée en fonction des préférences de l’utilisateur | <ul><li>Les préférences de fuseau horaire basées sur le paramètre du navigateur sont utilisées dans les notifications par courrier électronique.</li><li>Confirmation par courrier électronique envoyée lors de l’abonnement/désabonnement avec toutes les préférences sélectionnées.</li></ul> |
| Meilleure  des messages de  | <ul><li>Historique des  triés en fonction des mises à jour  des chronologiques.</li><li>Horodatage de la résolution de  ajoutée aux publications fermées majeures/mineures.</li></ul> |

## Interface d’Experience Cloud et services principaux {#ecloud}

Nouvelles fonctionnalités et correctifs pour l’interface d’Experience Cloud, notamment pour l’administration et les services principaux (attributs du client, audiences, déclencheurs, cookies, etc.).

| Fonction | Date de publication | Description |
| ----|----|---- |
| Outil d’administration - Affichage des détails utilisateur | 26 février 2020 | Les administrateurs peuvent afficher une liste triable et filtrable de tous les utilisateurs d’Experience Cloud et de leurs détails dans le nouvel outil d’administration. Les détails de l’utilisateur incluent l’accès au produit d’un utilisateur, ses rôles et les informations de dernier accès. Voir l’aide de [l’outil d’administration Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) pour en savoir plus. |

### Domaine de produit unifié

Adobe met à jour l’en-tête de domaine et d’interface afin d’unifier et d’améliorer votre expérience dans toutes les applications Experience Cloud. Ces améliorations sont conçues pour fluidifier votre utilisation de manière simple, mais importante. Ces améliorations ne modifieront pas vos processus actuels.

Les mises à jour comprennent les éléments suivants :

* Nouvelles URL de solution : `experience.adobe.com/<application name>` :
   * À terme, tous les produits adopteront ce modèle d’URL. Recherchez de nouvelles URL pour qu’elles prennent effet tout au long du mois.
   * Navigateurs pris en charge : [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] et [!DNL Opera] (versions les plus récentes). **Remarque** : bien que l’interface d’Experience Cloud prenne en charge ces navigateurs, les solutions individuelles peuvent ne pas tous les prendre en charge. (Par exemple, [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) ne prend pas en charge [!DNL Opera] et [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) ne prend pas en charge [!DNL Safari].)
   * ([!DNL Safari] uniquement) Le changement de domaine peut entraîner des problèmes de cookies dans [!DNL Safari]. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité de [!DNL Safari], vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Experience Cloud de fonctionner sur ce nouveau domaine.
* Il est plus facile de basculer entre vos organisations ou vers une autre application.
* Amélioration de l’aide des produits : [!UICONTROL Experience League] est intégré dans le produit afin qu’une recherche d’aide comprenne également les résultats des forums de la communauté et du contenu vidéo. Cette modification simplifie l’accès à davantage de contenu et vous permet de tirer le meilleur parti d’Experience Cloud. De plus, vous pouvez cliquer sur **[!UICONTROL Aide]** > **[!UICONTROL Commentaires]** pour signaler des problèmes ou partager vos idées avec Adobe.
* Notifications améliorées : le menu déroulant [!UICONTROL Notifications] comporte désormais deux onglets, l’un pour vos propres notifications de produit et l’autre pour les annonces de produits globales.

**Remarque :** La page [!UICONTROL Flux] a été abandonnée en janvier 2020. Vous trouverez un avis d’obsolescence dans le produit.

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) help.

## Experience Platform {#platform}

Release notes for the [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] and security bulletins.

* [Notes de mise à jour d’Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/security.html)  (Tous les produits Adobe)

### Experience Platform Launch {#launch}

Pour consulter les notes de mise à jour et la documentation du produit, voir [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## Orchestration du voyage {#journey}

À l’aide d’Adobe Experience Platform, orchestrez les voyages individuels des clients à l’échelle de l’d’expérience en anticipant intelligemment les besoins de chaque individu en temps réel, où que soit son parcours.

La version T1 a été publiée. [En savoir plus](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

### Ressources supplémentaires

[Documentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - Notes [de](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) mise à jour - Vidéos [pratiques](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## Mobile Services et SDK mobiles {#mobile}

**iOS v4.19.1**

* Général - Résolution d’un blocage potentiel lorsque les énumérations [!UICONTROL Swift] sont incluses dans les données contextuelles pour les appels de suivi.
* [!DNL Target] - [!DNL Target] L’ID de session sera désormais ajouté en tant que paramètre de données `a.target.sessionId` contextuelles dans l’accès interne Analytics pour  envoyé à Adobe Analytics.

**Android v4.18.1**

* [!DNL Target] - [!DNL Target] L’ID de session sera désormais ajouté en tant que paramètre de données contextuelles &quot;a..sessionId&quot; dans l’accès interne à l’  Analytics pour envoyé à Adobe Analytics.

## [!DNL Analytics] {#analytics}

Date de la version : **12 mars 2020**

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)

Pour consulter la documentation du produit, voir [Accueil de l’aide Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

* **Plusieurs suites de rapports dans[!UICONTROL Espace de travail ]**de : Vous pouvez désormais importer des données de plusieurs suites de rapports dans un seul projet[!UICONTROL de l’espace de travail]pour dans des panneaux côte à côte.[En savoir plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud   Optimisation**: Cette fonctionnalité vous permet de publier des segments dans Experience Cloud dans les 8 heures (au lieu du temps de traitement de 48 heures précédent). [En savoir plus...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Workspace - Modèle** de didacticiel de formation : Ce nouveau modèle standard vous guide tout au long de la terminologie commune et des étapes nécessaires à la création de votre premier   dans Workspace. Il est disponible sous forme de modèle standard dans le module [!UICONTROL Nouveau projet] et remplace l’exemple de projet existant aujourd’hui pour les nouveaux utilisateurs qui n’ont pas d’autres projets dans leur .

#### Correctifs

* Correction d’un problème dans les [!UICONTROL rapports et analyses] qui empêchait le téléchargement `.xls` des rapports. Ce problème affectait les clients utilisant des devises autres que le dollar américain et l’euro. (AN-206541, AN-204008)
* Le déploiement d’un nouvel interpréteur de commandes a résolu plusieurs problèmes client liés au changement d’organisation d’Experience Cloud.(AN-200844, AN-186920)
* Correction d’un problème en raison duquel l’exécution d’une ventilation sur l’élément de ligne _Non spécifié_ (ou d’autres éléments de ) sans inclure _Non spécifié (Aucun)_ dans le de recherche de la ventilation ne retournait aucun résultat dans la ventilation.
* Correction d’un problème survenant lors de l’utilisation d’une dimension classifiée, les totaux des mesures d’entrée ou de sortie ne correspondaient pas au total de l’élément de ligne sur une ventilation.
* Correction d’un problème en raison duquel les modèles Première touche et Dernière touche dans l’ID d’attribution ne calculaient pas correctement le crédit pour certains éléments de ligne dans certaines dimensions prêtes à l’emploi.
* Correction d’un problème en raison duquel la ventilation d’une dimension de date par une autre dimension de date renvoyait des résultats incorrects.
* Correction d’un problème en raison duquel les mesures d’entrée ou de sortie étaient parfois comptabilisées incorrectement lorsqu’elles étaient appliquées à &quot;Non spécifié&quot; dans un rapport de dimension classifié.

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout  ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| EOL du paramètre Niveau **[!UICONTROL de]** conversion | 3 mars 2020 | Le paramètre Niveau [de](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) conversion non opérationnel dans Outils **[!UICONTROL d’]administration > Suites[!UICONTROL de]rapports > Paramètres du compte[!UICONTROL général sera supprimé de l’interface utilisateur le 12 mars 2020.]** |
| EOL de l&#39;archive **** | 3 mars 2020 | Le paramètre d’archivage **** sous **[!UICONTROL Gérer les]** dans les [!UICONTROL rapports et analyses] ne sera plus disponible à compter du 12 mars 2020. |
| Fin de la prise en charge de TLS 1.1 | 3 octobre 2019 | D’ici le 31 mars 2020, Adobe Analytics supprimera la prise en charge de TLS 1.1. Ce changement s’inscrit dans le cadre des efforts que nous déployons pour respecter les meilleures normes de sécurité et promouvoir la sécurité des données de nos clients. |
| Nouveau domaine Adobe Analytics | 18 décembre 2019 | Le 16 janvier 2020, Adobe Analytics a commencé passer à un nouveau domaine : `https://experience.adobe.com/analytics.`<br>**Remarque :** cette modification s’applique à tous les utilisateurs accédant à Analytics avec leur Adobe ID ou Enterprise ID.<ul><li>Ce changement de domaine peut créer des problèmes de cookies lors du chargement d’Analytics dans Safari. En désactivant la case à cocher _Empêcher le suivi sur plusieurs domaines_ dans les préférences de confidentialité de , vous activez les cookies sur plusieurs domaines (et toutes les expériences sur plusieurs sites) et permettez ainsi à Analytics de fonctionner sur ce nouveau domaine Adobe Experience Cloud. [!DNL Safari] You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>Le changement de domaine peut entraîner l’arrêt du fonctionnement d’[!UICONTROL Activity Map] pour certains clients [dans des cas spécifiques](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vie : API héritées d’Analytics | 9 janvier 2020 | En novembre 2020, les services d’API hérités d’Analytics suivants arriveront en fin de vie et seront fermés. Les intégrations actuelles créées à l’aide de ces services cesseront de fonctionner. <ul><li>API Analytics 1.3</li><li>API Analytics 1.4 SOAP</li><li>Legacy OAuth Authentication (OAuth et JWT)</li></ul>Nous avons mis à disposition une [FAQ sur la fin de vie des API héritées](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) pour répondre à vos questions et vous donner des conseils sur la marche à suivre. Les intégrations d’API qui utilisent ces services peuvent migrer vers les [API Analytics 1.4 REST](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) ou vers les [API Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Les comptes OAuth hérités peuvent migrer vers un compte d’intégration [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, qui peut être utilisé pour accéder aux API Analytics 1.4 et 2.0. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

Voir [Notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). La version 2.20.0 a été publiée le 5 mars 2020.

## Audience Manager {#aam}

Nouvelles fonctionnalités et mises à jour de   Manager :

### Fixes and improvements {#aam-fixes-and-improvements}

* Correction d’un bogue en raison duquel les clients ne pouvaient pas mettre à jour le nom du segment en raison d’un [!UICONTROL d’autorisation RBAC manquant _ALL_DESTINATIONS]. L’autorisation [!UICONTROL _ALL_DESTINATIONS] ne doit pas être requise pour mettre à jour un segment. Pour plus d’informations sur les autorisations RBAC, voir [Administration (Contrôles RBAC)](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AAM-52760)
* Correction d’un bogue dans l’Explorateur [de](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) données en raison duquel certains clients ne voyaient pas le contenu dans la section d’informations de base et les opérateurs du créateur de  de , lors de la création de caractéristiques basées sur des signaux de l’Explorateur [!UICONTROL de] données. (AAM-53130)
* Correction d’un bogue en raison duquel certains clients ne pouvaient pas charger l’interface du [!UICONTROL  Marketplace] . (AAM-52070)
* Correction d’un bogue dans l’API  Segments en raison duquel, en raison de certains segments sans description, l’interface se figeait lorsque les utilisateurs tentaient d’accéder à ces segments et qu’ils devaient quitter cette page. (AAM-53071)
* Plusieurs améliorations d’accessibilité dans l’interface. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058,AAM-49399 (92)

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Mises à jour du produit

* **AEM 6.5.4.0** AEM 6.5, Service Pack 4.0 (version 6.5.4.0 publiée le 5 mars 2020) est une mise à jour importante qui comprend de nouvelles fonctionnalités, des améliorations clés pour les clients, des performances améliorées, la stabilité et la sécurité, publiées depuis la disponibilité générale d’AEM 6.5, avril 2019.
   * [Nouveautés d’Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [Notes de mise à jour](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Livrables de la version d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4, Service Pack 8.0 (version 6.4.8.0 publiée le 5 mars 2020) est une mise à jour importante qui inclut les correctifs client clés publiés depuis la disponibilité générale d’AEM 6.4, avril 2018.
   * [Notes de mise à jour](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 8 (6.3.3.8 publié le 5 mars 2019) est une mise à jour importante qui comprend les correctifs client clés publiés depuis la disponibilité générale d’AEM 6.3, avril 2017.
   * [Notes de mise à jour](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal **

   AEM Assets Brand Portal 6.4, Service Pack 6 (6.4.6 publié le 5 mars 2020) modifie la configuration des AEM Assets avec [!UICONTROL Brand Portal.] En outre, la version comprend d’autres améliorations et correctifs de bogues.
   * [Notes de mise à jour](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Auto-assistance

* **AEM as a Cloud Service - Permissions basées sur les rôles**

   Cloud Manager dispose de rôles préconfigurés avec les autorisations appropriées. Chacun des rôles a des autorisations, des  préconfigurées ou des autorisations spécifiques associées à chaque rôle. La rubrique d’aide Permissions [basées sur les](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) rôles identifie les fonctions disponibles et les rôles qui peuvent les exécuter.

* **AEM as a Cloud Service - Répartiteur**

   Les sections d’invalidation [du](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) répartiteur et du CDN [et du répartiteur](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) explicite ont été mises à jour afin de clarifier les options disponibles et leur fonctionnement.

* **Configuration des ressources AEM avec le portail de marque**

   AEM Assets est maintenant configuré avec [!UICONTROL Brand Portal] via les E/S Adobe, qui achète un jeton IMS pour autorisation du client du portail de marques. Auparavant, il était configuré dans l’interface Classic par le biais de la passerelle OAuth [!UICONTROL héritée.]
Voir [Configuration des ressources AEM avec le portail](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html)de marque.

* **AEM as a Cloud Service - Recadrage intelligent dans Contenu multimédia dynamique**

   Une nouvelle option est disponible dans AEM en tant que service Cloud lorsque vous travaillez avec le recadrage dynamique dans le composant Contenu multimédia dynamique :

   **Activer la correspondance** des proportions : sélectionnez cette option pour permettre à Contenu multimédia dynamique de sélectionner un rendu de recadrage dynamique qui correspond le mieux aux proportions de l’image d’origine.
Voir [Utilisation du recadrage](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop)dynamique.

### Communauté

* **Webinaires AEM Skill Builder**

   * Sites AEM - À compter du 17 mars 2020, découvrez les éléments de base de la création de contenu et les concepts et opérations fondamentaux des sites AEM. [Inscrivez-vous maintenant](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register).
   * Ressources AEM - À compter du 19 mars 2020, apportez votre aide à votre expertise en gestion des ressources numériques et découvrez les bases du portail de marque, des médias [!UICONTROL dynamiques,] des liens [!UICONTROL de ressources,] etc. [Inscrivez-vous maintenant](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register).

### Ressources supplémentaires

* [AEM en tant que Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [Formation et assistance pour AEM 6.5 – Accueil](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Page d’accueil Formation et assistance AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Page d’accueil Formation et assistance AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Page d’accueil Formation et assistance AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notes de mise à jour de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Campaign Classic 

* [Mise à jour Campaign Classic 19.1.4](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Ressources supplémentaires

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/support/campaign/standard.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)  – [Calendrier des versions](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Notes de mise à jour](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Mis à jour le 10 février 2020 pour la version du 8 février :

| Affichage | Fonction |
|------|---------|
| [!UICONTROL Portfolios] | You can now add [!DNL Yahoo!] Japan Display Network (YDN) campaigns to portfolios to optimize the campaign budgets and ad group-level bids. La même enchère s’applique à toutes les publicités d’un groupe. Les données relatives aux campagnes Japan Display Network sont incluses dans le  du portfolio. |
| [!UICONTROL Rechercher] > [!UICONTROL Bulksheet] | Vous pouvez désormais créer, modifier et supprimer des annonces de recherche en responsive design (RSA) Google à l’aide de feuilles d’envoi groupées. Auparavant, la prise en charge n’était assurée que par le biais de l’interface de gestion de campagne standard sous **[!UICONTROL Rechercher]** > **[!UICONTROL Campagnes]**. |
| [!UICONTROL Rechercher] > [!UICONTROL Campagnes, Rapports] | Les statistiques sur la proéminence de Google Ads `Impr. (Abs. Top) %` et `Impr. (Top) %` sont désormais disponibles dans tous les rapports de base et dans les vues de gestion de campagne au niveau de l’entité, à l’exception de celles relatives aux achats de groupes de produits, aux rapports sur le [!UICONTROL taux d’impressions quotidien des campagnes] et sur le [!UICONTROL taux d’impressions quotidien des mots-clés], ainsi que dans les vues des étiquettes et des contraintes. |

## [!DNL Magento] {#magento}

Pour les notes de mise à jour de Magento, veuillez consulter :

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

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

## Nouvelle documentation et nouveaux didacticiels {#selfhelp}

Articles et vidéos d’auto-assistance nouveaux et récents. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| Solution | Contenu | Description |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | Vidéo - [Création de plusieurs pages de et de produit](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | Découvrez comment créer un projet CIF Adobe Experience Manager (AEM) minimal comme point de départ pour les projets clients à l’aide des composants principaux de CIF. Appliquez un style de thème et CSS aux composants et inspectez un nouveau projet CIF AEM, généré par l’archétype. Découvrez également comment les composants principaux de CIF organisent CSS et JavaScript. |
| [!UICONTROL AEM Forms] | Article - [Authentification auprès de l’auteur AEM à l’aide d’OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Découvrez comment configurer votre application sur le portail OKTA et les paramètres que vous utilisez généralement lors de l’enregistrement d’une nouvelle application. |
| [!UICONTROL AEM Commerce] | Didacticiel - [Personnaliser les composants principaux CIF](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | Examinez plusieurs points d’extension différents fournis par CIF Core Components et AEM en général. CIF Core Components fournit un ensemble standard de composants commerciaux qui peuvent être utilisés pour accélérer un projet qui intègre les solutions Adobe Experience Manager (AEM) et Magento. |
| [!DNL Adobe Campaign] -   destinations | Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Créez un   en Campaign Standard à l’aide du créateur [!UICONTROL de segments d’Adobe]Experience Platform. Vous pouvez accéder à cette fonctionnalité directement dans  Adobe Campaign Standard via les [!UICONTROL modules de] . |
| [!DNL Adobe Campaign] -   destinations | Vidéo - [Activation de la plate-forme Adobe Experience Platform   dans un flux de travail marketing](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Découvrez comment activer le [!UICONTROL Data Services ] au sein d’un flux de travail à l’aide du  delecture de. |
| [!DNL Adobe Campaign] | Didacticiel - Notification [Push avec Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | Envoyez des notifications Push personnalisées et segmentées aux périphériques mobiles iOS et Android. Ce didacticiel décrit les étapes nécessaires à l&#39;envoi de notifications Push à partir de  Adobe Campaign et à la réception de ces notifications dans votre application Android. |
| [!DNL Adobe Campaign] | Vidéo - [Création d’une notification Push](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Créez une notification Push dans  Adobe Campaign Standard. Vous pouvez envoyer des notifications Push personnalisées et segmentées aux périphériques mobiles iOS et Android. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Vérification de l’état d’une tâche d’assimilation de données](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | Découvrez comment vérifier l’état d’une tâche d’importation de données et si les données ont été assimilées depuis  Adobe Campaign Standard dans Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Modifier le mappage des données](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | Découvrez comment vérifier l’état et modifier le mappage des données. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - d’expériences [de zone cliquable](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Découvrez comment mapper les  d’expérience dans Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Carte des ressources personnalisées](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Découvrez comment mapper différents types de données entre  Adobe Campaign Standard et Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Comprendre le connecteur de données d’Adobe Experience Platform](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Découvrez comment rendre vos données disponibles sur Adobe Experience Platform en mappant les données XTK (données assimilées dans Campaign) aux données du modèle de données d’expérience (XDM) sur Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connecteur de données AEP | Vidéo - [Mappage des données de table de départ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Apprenez à mapper vos données d’origine/ de test avec Adobe Experience Platform. |
| [!DNL Adobe Campaign]-   destinations | Vidéo - [Changez le  d&#39;un  pour une plate-forme  un](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Découvrez comment modifier le  d’un  pour un de plateforme  en dehors du tableau de principal dans Standard. |
| [!DNL Adobe Campaign] | Vidéo - [Gros  sur Snowflake](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Tirez parti du connecteur Snowflake dans  Adobe Campaign Classic. |
| [!DNL Adobe Campaign] -   destinations | Article - [ Destinations (BETA) - Présentation](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Découvrez comment tirer parti des données de centralisées et consolidées d’Adobe Experience Platform pour vos campagnes marketing dans  Standard. |
| [!DNL Adobe Target] - SDK Mobile | Didacticiel - [Personnaliser les expériences d’application avec les  Adobe](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Mettez en oeuvre les  Adobe dans votre propre application Android. Validez la configuration du SDK Mobile Services et implémentez [!DNL Target] des requêtes telles que la prérécupération de contenu, le blocage de requêtes, etc. |
| Adobe Analytics | Vidéo - Super session [Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Regardez des extraits de la &quot;super session&quot; high-tech au Sommet 2019. |
| Adobe Analytics | Vidéo - [Présentation des mesures calculées dans les analyses de parcours du client](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Découvrez les principes de base de la création de mesures  calculées dans les analyses [!UICONTROL de parcours du]client. |
| Adobe Analytics | Vidéo - Super session [Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) |  des extraits de la session de voyage et d&#39;accueil du Sommet 2019. |
| Adobe Analytics | Vidéo - Super session [Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Reportez-vous aux clips organisés de la session de vente au détail du Sommet 2019. |
| Adobe Analytics | Vidéo - Cas d’utilisation [par le client : Accent Group investit dans l&#39;expérience client pour stimuler les ventes](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Découvrez comment le groupe Accent utilise Adobe Experience Cloud pour créer des expériences numériques homogènes. |
| Adobe Analytics | Vidéo - Cas d’utilisation [par le client : ServiceNow obtient les informations appropriées pour établir une connexion avec le](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Découvrez comment [!DNL ServiceNow] obtenir des données exploitables de ses  marketing et optimiser le retour sur investissement sur la publicité de recherche payante avec Adobe Advertising Cloud et Adobe Analytics. |
| Adobe Analytics | Vidéo - [Adobe Analytics - Plus que des données : intelligence du client](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | Découvrez le marketing axé sur les données et comment faire passer la maturité de vos analyses des données aux informations pour passer à l’action. |
| Adobe Analytics | Vidéo - [Adobe Sensei et Adobe Analytics - Version étendue](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) |  fonctionnalités clés d’Adobe Analytics optimisées par Adobe [!DNL Sensei,] y compris la détection des [!UICONTROL anomalies,] la  de [!UICONTROL contribution ,] les alertes intelligentes,  la mise en grappe,le QI des segments de,le  et la modélisation de la propension de l’. |
| Adobe Analytics | Vidéo - [Comment Adobe   Workspace peut modifier votre activité](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Découvrez comment vous pouvez exécuter des   ad hoc, des de  de données  flexibles, des [!UICONTROL de cohortes et des d’abandons à l’aide de l’espace de travail]dede. Vous pouvez également partager le   de travail de la  de travail avec tout le monde dans votre, et sa fonction glisser-déposer permet à tout le monde d&#39;analyser facilement les données et d&#39;obtenir rapidement des informations. |
| Adobe Analytics | Vidéo - Cas d’utilisation [par le client : Le Home Depot innove avec la gestion de l’expérience client](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Découvrez comment [!DNL Home Depot] utiliser les solutions Adobe pour fidéliser la marque et satisfaire les clients grâce à une expérience d’achat personnalisée et personnalisée. |
| Adobe Analytics | Présentation - [Présentation des analyses de parcours du client](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Découvrez comment Adobe [!UICONTROL Customer Journey Analytics], un service d’application basé sur [!DNL Adobe Experience Platform], introduit [!UICONTROL  Workspace] dans la plateforme d’expérience. Cette fonctionnalité permet d’activer l’ à plusieurs sur l’un de vos jeux de [!DNL Adobe Experience Platform] données. |
| Adobe Analytics | Vidéo - Attribution de  [plusieurs dans CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | Découvrez comment utiliser les visualisations pour montrer l’attribution (attribuer du crédit) entre les  du dans les analyses [!UICONTROL de parcours du]client. |
| Adobe Analytics | Article - Conseils [client pour poursuivre votre parcours d’apprentissage d’Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Rencontrez trois clients Adobe qui disposent de conseils et de astuces pour vous aider à tirer le meilleur parti d’Adobe Analytics. |
| Adobe Analytics | Vidéo - [Créer des visualisations  dans CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | Découvrez comment [!UICONTROL Customer Journey Analytics] vous permet de créer des visualisations qui incluent des données issues de plusieurs ensembles de données sur plusieurs , y compris la fusion des données par. |
| Adobe Analytics | Vidéo - [Déplacez vos mesures calculées d’Adobe Analytics vers les analyses de parcours des clients](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Trouvez des conseils pour recréer vos mesures [!UICONTROLCcalculées Analytics] dans Analytics [!UICONTROL du parcours du]client. |

---
title: Dernières notes de mise à jour
description: Découvrez les dernières notes de mise à jour, les nouvelles fonctionnalités et la nouvelle documentation pour les produits et services  [!DNL Experience Cloud] . Trouvez de nouvelles ressources dʼaide et des tutoriels sur [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] et [!DNL Document Cloud].
doc-type: release notes
last-update: March 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: fe574c18fe36112968b6e58ddb8103239eed9632
workflow-type: tm+mt
source-wordcount: '5696'
ht-degree: 50%

---

# Notes de mise à jour d’Adobe Experience Cloud - Mars 2022

![Bannière](assets/experience-cloud-banner-3.png)

En tant que créateur d’expériences, votre chemin vers la réussite commence avec [Adobe Experience League](https://experienceleague.adobe.com/?lang=fr#home). Vous y trouverez une vaste bibliothèque de documents pratiques, des tutoriels autonomes, des vidéos pratiques et des cours pour tous niveaux et rôles. Bénéficiez également des conseils de la communauté internet de pairs et de lʼassistance fournie par un expert lorsque vous en avez besoin.

Vous êtes prêt à commencer ? [Répondez à un petit quiz de 5 minutes pour réussir](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp) !

>[!NOTE]
>
>Pour recevoir une notification mensuelle par e-mail des mises à jour de cette page, abonnez-vous à la [Mise à jour prioritaire des produits Adobe](https://www.adobe.com/subscription/priority-product-update.html). Consultez régulièrement ce site pour rester au courant de ce qui se passe sur Experience League.

Dernière mise à jour : **21 mars 2022**

* [[!DNL Experience League] events](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - composants et administration de l’interface centrale](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Plans directeurs en matière d’expérience digitale : tutoriels](#blueprints)

Besoin d’aide ? Rendez-vous sur [Adobe Experience League](https://experienceleague.adobe.com/?lang=fr#home) pour trouver de la documentation technique et sur les produits, des cours préparés par Adobe, des tutoriels vidéo, des réponses rapides, des informations provenant de la communauté et des formations dispensées par un instructeur.

## ![Icône](/assets/experience-league.png) [!DNL Experience League] events {#events}

Les événements Experience League sont un excellent endroit pour apprendre, interagir et obtenir des réponses de la part des experts du produit d’Adobe !

| Événement | Type | Description |
| -----------|---------- | ----|
| [Experience League LIVE](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=fr) | Vidéo en direct et à la demande | Une émission en direct en streaming réalisée par l&#39;équipe Experience League. Elle offre l’occasion de communiquer avec des experts en produits Adobe. Découvrez des conseils pratiques, des astuces et des stratégies que vous pouvez appliquer aux applications Adobe Experience Cloud.<br> [Détails et événements passés](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) |
| [AEM Gems](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/aem-gems-build-sites-faster-with-aem-headless-and-app-builder/m-p/440205#M31629) | Webinaire Adobe Live | Bootstrap et déploiement rapides d’applications d’une seule page (SPA) à l’aide d’Adobe [!UICONTROL App Builder] workflows et outils sans compétences Experience Manager traditionnelles telles que Java™ et Sling nécessaires. Avec Experience Manager Headless, les marketeurs et les développeurs peuvent tous avoir l’expertise nécessaire dans leur propre domaine : les développeurs contrôlent la structure globale de l’application, le style et le routage, tandis que les marketeurs déterminent le contenu et son affichage.<br>**Date :** Mercredi 23 mars à [Détails et enregistrement](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/aem-gems-build-sites-faster-with-aem-headless-and-app-builder/m-p/440205#M31629) |
| [Adobe Analytics : Raconter des histoires percutantes avec des données](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b%E2%80%A6%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) | Webinaire Adobe Live | La narration des données est bien faite quand c&#39;est un équilibre entre art et science. Alors, pourquoi la surconcevoir ? Amy Ard, championne d’Adobe Analytics, présente trois parties destinées à guider votre narration de données sans pour autant diminuer la créativité :<ul><li>Identifier l&#39;opportunité ou le problème</li><li>Explication via les données</li><li>Offrir une solution</li></ul>**Date :** Jeudi 31 mars - [Détails et enregistrement](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b...%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) |
| [Experience Makers - Échange de compétences pour Adobe Workfront](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) | Webinaire Adobe Live | Nous sommes ravis d’annoncer la première édition d’Experience Makers - L’échange de compétences pour Adobe Workfront aura lieu le 13 avril. Cet événement d’apprentissage numérique gratuit de 3 heures est entièrement axé sur Workfront et les clients ont la possibilité de poser des questions en direct à des experts et à des pairs qui connaissent le mieux la gestion de travail. Que vous soyez nouveau à Workfront ou expert chevronné, nous avons quelque chose pour tout le monde. <br>**Date :** Mercredi 13 avril - [Détails et enregistrement](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) |
| [Adobe  [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=fr) | Vidéo | [!DNL Developers Live] présente les dernières avancées technologiques et les outils les plus récents pour les développeurs. Ils rendent possible la conception, les workflows de création de contenu, les services de document et la gestion de lʼexpérience client dans tous les secteurs dʼactivité. Affichez le discours liminaire, découvrez les API dʼAnalytics, la couche de données client, les projets open source Adobe I/O et bien plus encore. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] fournit des informations détaillées, des mises à jour de statut et des notifications par e-mail relatives aux produits Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/fr).

Pour obtenir les informations les plus récentes, voir État du système d’Adobe [notes de mise à jour](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=en#status).

## ![Icône](/assets/ec_appicon_24.png) Experience Cloud - composants et administration de l’interface centrale {#ecloud}

Experience Cloud [composants de l’interface utilisateur centrale](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=fr) inclure les fonctionnalités disponibles sur la page d’accueil et l’en-tête du produit persistant ; Ces fonctionnalités incluent les paramètres de profil utilisateur, les préférences et la recherche. Vous trouverez également de l’aide sur la gestion des utilisateurs et des produits, les attributs du client et les audiences Experience Cloud.

| Fonctionnalité | Description |
| ------- |-------|
| Accès _[!UICONTROL Récents]_ dans Experience Platform et Journey Optimizer à l’aide de [!UICONTROL Recherche unifiée] | Vous pouvez accéder aux objets récemment consultés à partir de chaque page de l’Experience Platform et de Journey Optimizer via le [!UICONTROL Recherche unifiée] champ .<br>Voir [Recherche unifiée d’objets et d’entités](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en) pour plus d’informations. |

{style=&quot;table-layout:auto&quot;}

**Plus de ressources d’aide sur Administration et [!DNL Experience Cloud Central UI Components]**

* [Notes de mise à jour](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en) pour les composants de l’interface utilisateur centrale dʼExperience Cloud
* [Gestion des utilisateurs et des produits](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) pour Experience Cloud (administration)
* [Notes de mise à jour](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=fr) du service Places
* Documentation produit pour les fonctionnalités [Personnes : attributs du client et bibliothèque d’audiences](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)
* [Recherche unifiée dʼobjets et dʼentités](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en)

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Dernières informations de mise à jour et nouvelle documentation pour Experience Platform et le [!UICONTROL SDK mobile] :

Date de lancement : **7 mars 2022**

* [Notes de mise à jour d’Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=fr)

### Nouveaux tutoriels et cours sur Experience Platform {#tutorials-platform}

Nouveaux tutoriels, vidéos ou cours publiés pour Experience Platform.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Mars 2022 | [Tutoriel sur la mise en oeuvre de Adobe Experience Cloud dans les applications mobiles](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/overview.html) | Cours | Découvrez comment mettre en oeuvre des applications Adobe Experience Cloud dans votre application mobile à l’aide du SDK Mobile de Adobe Experience Platform. |
| Mars 2022 | [Génération d’identifiants d’appareil propriétaires](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/generate-first-party-device-ids.html) | Vidéo | Découvrez comment générer des identifiants d’appareil propriétaires et comment ils fonctionnent. |
| Mars 2022 | [Configuration des flux de données](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/configure-datastreams.html) | Vidéo | Découvrez comment créer et configurer des flux de données pour les implémentations de SDK Web et Mobile. |

{style=&quot;table-layout:auto&quot;}

### SDK Adobe Mobile

Voir [Notes de mise à jour et journaux des modifications](https://aep-sdks.gitbook.io/docs/release-notes) pour les SDK Adobe Experience Platform Mobile.

## ![Icône](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Date de lancement : **23 mars 2022**

* [Notes de mise à jour](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=fr) dʼAdobe Analytics (**nouvel emplacement**)
* [Documentation et tutoriels du produit](https://experienceleague.adobe.com/docs/analytics.html?lang=fr) Adobe Analytics

### AppMeasurement {#appm}

Version : **2.22.4**

* [Notes de mise à jour d’AppMeasurement pour JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=fr)

### Nouveaux tutoriels et cours sur Analytics {#tutorials-analytics}

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Analytics.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Mars 2022 | [Conseils et astuces pour simplifier et consacrer moins de temps à la formation des utilisateurs](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/simplify-training-users.html?lang=en) | Vidéo et article | Découvrez à quel point une organisation Adobe Analytics bien formée peut être essentielle pour réussir dans votre entreprise. |
| Mars 2022 | [Créer une communauté plus forte](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/empowered-community.html) | Vidéo et article | Découvrez la valeur d’une communauté Analytics dotée de pouvoirs et comment en créer et en prendre en charge une. |
| Mars 2022 | [Créer des règles de traitement des canaux marketing](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/create-marketing-channel-processing-rules.html?lang=en) | Vidéo | Découvrez comment configurer [!UICONTROL Règles de traitement] pour [!UICONTROL Canaux marketing]. |
| Mars 2022 | [Configurer des canaux marketing dans votre suite de rapports](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/set-up-marketing-channels.html) | Vidéo | Dans cette vidéo, découvrez comment configurer les rapports des canaux marketing dans votre suite de rapports Analytics. |
| Mars 2022 | [Transition vers Adobe Analytics à partir de Google Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/transitioning-from-other-platforms/transition-from-google-analytics.html?lang=en) | Vidéo | Un guide complet pour la transition vers [!DNL Adobe Analytics] de [!DNL Google Analytics]. |
| Mars 2022 | [Configurer les variables de hiérarchie](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-hierarchy-variables.html?lang=en) | Vidéo | Découvrez comment et à quel moment configurer des variables de hiérarchie pour votre site. Cette fonctionnalité peut être utilisée pour afficher une vue hiérarchique des pages de votre site et le volume de trafic qui atteint chaque noeud. |
| Mars 2022 | [Traiter et partager dans Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/curation-and-sharing-in-analysis-workspace.html?lang=en) | Vidéo | Découvrez comment travailler avec le traitement et le partage de projets dans Analysis Workspace. |
| Mars 2022 | [Lien direct vers un projet dans Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/direct-link-to-a-project.html?lang=en) | Vidéo | Découvrez comment démocratiser plus efficacement les analyses en créant des liens raccourcis qui amènent vos collègues directement à vos projets Analysis Workspace. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Date de lancement : **23 mars 2022**

* [Notes de mise à jour](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=fr) de Customer Journey Analytics  (**nouvel emplacement**)
* [Documentation et tutoriels du produit](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=fr) Customer Journey Analytics

## ![Icône](/assets/audience-manager.png) Audience Manager {#aam}

Correctifs et améliorations d’Audience Manager:

| Amélioration | Description |
| -----------| ---------- |  
| Validation des sources de données cibles appartenant à d’autres entreprises | Audience Manager a publié une amélioration de la fonction [processus d’intégration des données par lots](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=en). Pour empêcher l’intégration accidentelle de fichiers et de données dans les sources de données cibles détenues par d’autres partenaires, Audience Manager a ajouté une exigence de mappage entre l’ID de partenaire (PID) et les sources de données (DPID) détenues par d’autres partenaires. <ul><li>Voir aussi le __DPID_TARGET_DATA_OWNER_ champ dans [Exigences en matière de nom et de taille de fichier Amazon S3 pour les fichiers de données entrants](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=en#name-elements).</li><li>Les consultants internes à l’Adobe et l’assistance clientèle doivent se lire : [Gestion de l’accès à l’intégration pour les données de deuxième niveau](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=en) pour plus d’informations sur le nouveau mappage, une amélioration est nécessaire et comment demander un nouveau mappage</li><li>Il s’agit de _not_ requis pour demander un mappage pour les relations de partage de données existantes. Le mappage est également _not_ requis lors de l’intégration de données dans des sources de données cibles appartenant à votre PID.</li></ul> |

{style=&quot;table-layout:auto&quot;}

Pour les ressources d’aide autonome, voir [Documentation et tutoriels sur l’Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=fr) sur Experience League.

## ![Icône](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe recommande de consulter la page des [mises à jour et feuilles de route Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=fr) afin de se tenir au courant des informations de mise à jour.

### Mises à jour de produits Experience Manager

* **Experience Manager 6.5, Service Pack 12 (6.5.12.0)**

   Adobe Experience Manager 6.5.12.0 comprend de nouvelles fonctionnalités, des améliorations importantes demandées par les clients, ainsi que des améliorations en termes de performances, de stabilité et de sécurité, publiées depuis la version 6.5 d’avril 2019. Le Service Pack est installé sur Adobe Experience Manager 6.5.

   Voir [Notes de mise à jour](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=fr).

### Versions de produits Experience Manager

* **Experience Manager as a Cloud Service**

   * [Vidéo de présentation de la version de janvier 2022](https://video.tv.adobe.com/v/340120) de nouvelles fonctionnalités.
   * [Vidéo de présentation de la version de décembre 2021](https://video.tv.adobe.com/v/339278) mettant en avant les nouvelles fonctionnalités.
   * [Vidéo de présentation de la version dʼoctobre 2021](https://video.tv.adobe.com/v/338253) mettant en avant les nouvelles fonctionnalités.
   * [Vidéo de présentation de la version de septembre 2021](https://video.tv.adobe.com/v/337381) mettant en avant les nouvelles fonctionnalités.

   * **Experience Manager Assets as a Cloud Service**

      _Nouvelles fonctionnalités d’Experience Manager Assets_

      * Dynamic Media : vous pouvez désormais utiliser l’interface Dynamic Media d’Experience Manager pour configurer les [Paramètres généraux](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html?lang=fr) et la [Configuration de la publication](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html?lang=fr) au lieu d’avoir à passer par l’application de bureau Dynamic Media Classic.
      * Dynamic Media prend désormais en charge l’ingestion, la prévisualisation, la lecture et la publication des vidéos MXF. Les annotations et les vidéos Shoppable pour les vidéos MXF ne sont pas encore prises en charge.
      * Après la configuration d’une connexion entre les déploiements du DAM distant et de Sites, les ressources sur le DAM distant sont disponibles sur le déploiement de Sites. Vous pouvez désormais [mettre à jour, supprimer, renommer et déplacer](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=fr) les ressources ou les dossiers du DAM distant. Les mises à jour sont, avec un peu de retard, disponibles automatiquement au déploiement de Sites.

      _Nouvelles fonctionnalités du canal de version préliminaire d’Experience Manager Assets_

      * Dynamic Media vous offre désormais la possibilité de [configurer un compte d’alias de société](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=fr) dans l’interface utilisateur, ce qui permet de mettre à jour les URL Dynamic Media prêtes à l’emploi et le code incorporé de la visionneuse. Cette action permet de renforcer l’optimisation du moteur de recherche, car les mises à jour apportées à votre environnement commercial, comme le rebranding, sont prises en compte.
      * L’interface utilisateur dʼExperience Manager Assets vous permet désormais dʼeffectuer les actions suivantes :

         * Configuration de la détection des ressources en double dans un référentiel.
         * Configuration de l’ajout de filigranes numériques aux images.
      * Les administrateurs peuvent désormais configurer le service de messagerie pour les téléchargements volumineux. Les utilisateurs peuvent ainsi choisir dʼ[activer les notifications par e-mail pour les téléchargements volumineux](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=fr#enable-email-notifications-for-large-downloads) dans l’interface dʼExperience Manager Assets. Une fois le processus de téléchargement terminé, l’utilisateur reçoit une notification par e-mail avec le lien de téléchargement du dossier zip archivé.
      * La fonctionnalité [Gestion de la publication](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=fr) bénéficie dʼune interface utilisateur améliorée. Les utilisateurs peuvent publier ou dépublier du contenu vers et depuis la destination sélectionnée, ainsi quʼ[Ajouter du contenu](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=fr#add-content) à la liste de publication depuis lʼensemble du référentiel de gestion des ressources numériques. Ils peuvent également [Inclure les paramètres des dossiers](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=fr#include-folder-settings) pour publier le contenu des dossiers sélectionnés et appliquer des filtres, ainsi que [planifier la publication](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=fr#publish-assets-later) à une date ou heure ultérieure.

      _Correctif_

      * Les ressources non traitées, qui nʼont pas de rendu original, sont envoyées à Asset Compute pour être traitées lors de la migration des ressources dʼExperience Manager On-premise vers les services cloud.
   * **Experience Manager Forms as a Cloud Service**

      _Nouveautés de Forms_

      * **Experience Manager Forms as a Cloud Service - Communications** : les [API de communication](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=fr) vous permettent de combiner un modèle et des données XML pour générer des documents dʼimpression dans différents formats. Le service vous permet de générer des documents dans les modes synchrone et par lots. Les API vous permettent de créer des applications pour effectuer les opérations suivantes :

         * Générer des documents en complétant les fichiers modèles avec des données XML.
         * de générer des formulaires dans divers formats, y compris les flux d’impression PDF non interactifs ;
         * de générer des fichiers PDF d’impression à partir de fichiers PDF de formulaire XFA ;
         * de générer des documents PDF, PostScript, PCL et ZPL en blocs en fusionnant plusieurs jeux de données avec les modèles sources.
      * **Polices personnalisées pour les documents de référence et documents PDF créés à l’aide des API de communication** : vous pouvez désormais utiliser des polices approuvées par les marques dans les documents PDF générés à l’aide des API de communication pour vous aligner sur les exigences d’entreprise.

      _Nouveautés du canal de version préliminaire de Forms_

      * [API dʼassemblage](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/) : les API dʼassemblage permettent de combiner, réarranger, augmenter et obtenir des informations sur les documents PDF.
   * **Cloud Manager**

      _Date de publication_

      La date de publication de Cloud Manager dans Experience Manager as a Cloud Service 2022.01.0 est le 20 janvier 2022.
La prochaine version est prévue pour le 31 mars 2022.

      _Nouvelles fonctionnalités_

      * Cloud Manager [évite de reconstruire la base du code lorsqu’il détecte que la même validation Git est utilisée](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=fr#build-artifact-reuse) dans plusieurs exécutions de pipelines de piles pleines.
      * L’accès au journal de l’environnement Experience Manager nécessite désormais le profil de produit **[!UICONTROL Responsable de déploiement]**. Un bouton désactivé est affiché pour les utilisateurs qui ne disposent pas de ce profil.
      * L’interface utilisateur n’autorise pas la configuration du pipeline frontal pour un programme où Sites n’est pas activé en tant que solution.
      * Lors de la génération d’un mot de passe Git, la date d’expiration s’affiche.








### Communauté

* **Webinaire GEMS dʼExperience Manager : _création de site plus rapide à lʼaide dʼExperience Manager Headless et dʼApp Builder_**

   * Avez-vous manqué le discours d&#39;ouverture de l&#39;Adobe Summit 2022 ? Regarder [Rendre l&#39;économie numérique personnelle](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2022-opening-keynote-make-the-digital-economy/td-p/444612).
   * Adobe Summit 2022 | [Liste complète des sessions Experience Manager](https://adobe.ly/3rti6gF).
   * GEM Experience Manager | Webinaire | Mercredi 23 mars 2022
      * Rubrique : *Créer des sites plus rapidement avec Experience Manager Headless et App Builder*
      * [S’inscrire ici](https://adobe.ly/3oCkEsh)
      * [Pour les questions et réponses](https://adobe.ly/3LkSWdm)

### Nouveaux cours et tutoriels sur Experience Manager {#tutorials-aem}

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publication | Nom | Type | Description | Applications |
| -----------| ---------- | ---------- | ---------- | ------|
| Mars 2022 | [Commencer à développer avec AEM sans affichage](https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html?lang=fr) | Cours | Créez AEM landing page sans affichage qui rassemble tout le contenu sur AEM sans affichage sur ExL. | AEM sans tête |
| Mars 2022 | [Créer votre premier site web dans Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.1.aemcs.website) | Cours | Générez rapidement un nouveau site web en Experience Manager à l’aide d’un modèle de site prédéfini. | AEM Sites |
| Mars 2022 | [Extraire le noeud du xml de données envoyées](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/extract-xml-node.html?lang=en) | Vidéo | Découvrez cette étape de processus personnalisée pour créer un document XML en extrayant le noeud d’un autre document XML. Utilisez ce processus lorsque vous souhaitez fusionner les données envoyées avec le modèle XDP pour générer le PDF. | AEM Forms |
| Mars 2022 | [Écrire le document dans le système de fichiers](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/write-payload-document.html?lang=en) | Vidéo | Découvrez comment écrire les documents générés dans le workflow dans le système de fichiers. | AEM Forms |
| Mars 2022 | [Fonctions personnalisées](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/custom-functions-aem-forms.html?lang=en) | Vidéo | AEM Forms 6.5 offre la possibilité de définir des fonctions JavaScript pouvant être utilisées pour définir des règles métier complexes à l’aide de l’éditeur de règles. | AEM Forms |
| Mars 2022 | [Workfront pour les séries d’experts du connecteur amélioré pour Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html?lang=en) | Vidéo | Rejoignez les experts Workfront et Experience Manager Assets d’Adobe dans cette série de vidéos en quatre parties, afin de découvrir et de discuter les entrées et sorties de Workfront pour le connecteur amélioré Experience Manager. | AEM Assets, Workfront |
| Mars 2022 | [Listes déroulantes en cascade](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/geonames-org.html?lang=en) | Vidéo | Tutoriel contenant des exemples de ressources pour créer un formulaire avec une liste déroulante en cascade. | AEM Forms |
| Mars 2022 | [Configuration initiale et configuration](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/setup.html?lang=en) | Vidéo | Découvrez comment configurer et configurer Workfront pour le connecteur amélioré de Experience Manager, en déverrouillant la puissance combinée d’AEM Assets et de Workfront. | AEM Assets, Workfront |
| Mars 2022 | [Mappage de métadonnées et de formulaires personnalisés Workfront](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/custom-forms.html?lang=en) | Vidéo | Découvrez comment configurer Workfront et AEM Assets pour gérer et synchroniser les métadonnées des ressources à l’aide de formulaires personnalisés Workfront et de schémas de métadonnées AEM. | AEM Assets, Workfront |
| Mars 2022 | [AEM Balises, dossiers liés au projet et métadonnées de dossier](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/aem-tags-project-linked-folders-and-folder-metadata.html?lang=en) | Vidéo | Découvrez comment piloter AEM Balises utilisées sur les ressources via les données Workfront, configurer et utiliser des dossiers liés à un projet et des données Workfront pour AEM des schémas de métadonnées de dossier de ressources. | AEM Assets, Workfront |
| Mars 2022 | [Paramètres avancés et workflows](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/advanced-settings-and-workflows.html?lang=en) | Vidéo | Découvrez les paramètres avancés de Workfront pour AEM connecteur amélioré et comment configurer des workflows et des lanceurs avancés dans AEM pour gérer la synchronisation des données entre Adobe et Workfront. | AEM Assets, Workfront |
| Mars 2022 | [Création et configuration d’un compte Dynamics](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/formscs-dynamics-crm/create-dynamics-account.html?lang=en) | Vidéo | Découvrez les étapes d’enregistrement de Microsoft® Dynamics avec Azure Principale Directory. | AEM CS |
| Mars 2022 | [Partage de liens publics](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/link-sharing.html) | Vidéo | Découvrez comment le lien de partage d’Assets Essentials permet aux utilisateurs de partager des ressources avec des parties prenantes internes et externes tout en réduisant le risque de partage de ressources ou d’informations incorrectes. | AEM Assets |

{style=&quot;table-layout:auto&quot;}

### Informations de mise à jour d’Experience Manager

Toutes les notes de mise à jour d’Experience Manager sont conservées dans les pages suivantes :

* [Informations de mise à jour d’Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=fr)
* [Notes de mise à jour de Cloud Manager d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=fr)
* [Notes de mise à jour du service de conversion automatisée de formulaires](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=fr)
* [Notes de mise à jour du Service Pack 6.5 d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
* [Notes de mise à jour du pack de correctifs cumulatifs 6.4 d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=fr)
* [Notes de mise à jour de l’appli de bureau Experience Manager ](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=fr)
* [Notes de mise à jour d’Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=fr)
* [Notes de mise à jour de Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=fr)

### Autres ressources dʼaide pour Experience Manager

* [Guides relatifs à Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=fr)
* [Guide de l’utilisateur de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=fr#previous-updates)
* [Versions plus anciennes de la documentation pour Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=fr)
* [Documentation Experience Manager : mises à jour récentes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=fr#aem-as-a-cloud-service)

## ![Icône](/assets/ec_appicon_24.png) XML Documentation for Adobe Experience Manager {#xml-doc}

XML Documentation for Adobe Experience Manager est une application déployée sur AEM. C’est une puissante solution de gestion de contenu par composant (CCMS) de qualité professionnelle qui permet la prise en charge native de DITA dans Adobe Experience Manager, ce qui permet à AEM de gérer la création et la diffusion de contenu basé sur DITA.

En savoir plus sur [XML Documentation for AEM](https://www.adobe.com/fr/products/xml-documentation-for-experience-manager/features.html).

### Nouveaux tutoriels pour [!DNL XML Documentation for Adobe Experience Manager] {#tutorials-xml-doc}

Nouveaux tutoriels, vidéos ou cours publiés pour [!DNL XML Documentation for Adobe Experience Manager].

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Mars 2022 | [Génération de sortie avec documentation XML](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2022.2.xmldocs&amp;lang=fr) | Cours | Découvrez comment générer une sortie à l’aide de [!DNL XML Documentation for Adobe Experience Manager]. Découvrez les différentes fonctionnalités disponibles pour la génération de sortie, notamment les rapports, les lignes de base, les conditions, le dépannage, la publication en masse et l’activation. |

{style=&quot;table-layout:auto&quot;}

### Ressources supplémentaires

* [XML Documentation for Adobe Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=fr) : tutoriels sur Experience League
* [Formation et assistance pour XML Documentation for Adobe Experience Manager](https://helpx.adobe.com/fr/support/xml-documentation-for-experience-manager.html) : documentation du produit

## ![Icône](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Voir les liens suivants pour consulter les notes de mise à jour dʼAdobe Commerce :

* [Adobe Commerce et Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite pour Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Nouvelles ressources Adobe Commerce {#new-commerce}

Nouvelle documentation et nouveaux tutoriels pour Adobe Commerce sur Experience League.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Mars 2022 | [Guide des services de paiement](https://experienceleague.adobe.com/docs/commerce-merchant-services/payment-services/guide-overview.html) | Guide de  | Guide destiné aux administrateurs d’Adobe Commerce et de Magento Open Source. Il contient des informations détaillées sur l’installation et l’intégration des services de paiement, ainsi que sur la configuration et la gestion des services. Elle requiert une compréhension de base de la configuration et des fonctionnalités de base de Commerce. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/target.png) [!DNL Adobe Target] {#target}

Dernière mise à jour : **21 mars 2022**

* Pour obtenir des informations sur la version préliminaire, consultez la section [Version préliminaire d’Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=fr).
* Pour obtenir des informations à jour, consultez la section [Notes de mise à jour d’Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=fr).

## ![Icône](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Dernières mises à jour d’Adobe Campaign

Pour en savoir plus sur les dernières fonctionnalités, améliorations et correctifs disponibles :

* [Campaign Classic v7.2.2](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=fr)

### Nouveaux tutoriels et cours sur [!DNL Campaign] {#tutorials-campaign}

Nouveaux tutoriels et cours publiés pour Adobe Campaign.

| Publication | Nom | Type | Description | Applications |
| ------| ----- | -----| ------ | --- |
| Mars 2022 | [Intégration à Experience Manager - Présentation](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/overview.html?lang=fr) | Vidéo | Connectez Adobe Campaign à Adobe Experience Manager et gérez les modèles de diffusion d’e-mails, les ressources et les formulaires dans Experience Manager. | AEM, Campaign v8 |
| Mars 2022 | [Configurer Campaign pour l’intégration dʼExperience Manager](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/configure-campaign-for-aem-integration.html?lang=en) | Vidéo | Découvrez comment configurer l’intégration entre Experience Manager et Campaign, y compris les paramètres importants à rechercher et les pièges potentiels à éviter. | AEM, Campaign v8 |
| Mars 2022 | [Approuver et publier une page Experience Manager dans Campaign](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/approve-and-publish-aem-content-to-campaign.html?lang=en) | Vidéo | Découvrez comment créer une newsletter dans Experience Manager et comment l’approuver et la publier dans Campaign. | AEM, Campaign v8 |
| Mars 2022 | [Synchroniser et envoyer une diffusion email Experience Manager dans Campaign](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/synchronize-and-send-an-aem-delivery-in-campaign.html?lang=en) | Vidéo | Découvrez comment tester et envoyer un email à partir d’Adobe Campaign à l’aide d’une newsletter qui a été créée dans Experience Manager. | AEM, Campaign v8 |
| Mars 2022 | [Intégration à Adobe Target](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/connect/target-integration.html) | Vidéo | Découvrez comment personnaliser une diffusion avec du contenu dynamique diffusé à partir d&#39;Adobe Target. | Adobe Target, Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### Ressources d’aide pour Campaign

* Adobe Campaign v8 : [Documentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [Guides d’implémentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=fr)
* Adobe Campaign Standard : [Documentation de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=fr) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=fr) - [Calendrier des versions](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=fr)
* Adobe Campaign Classic : [Documentation de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=fr)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=fr) - Tutoriels vidéo pour [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=fr)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=fr)

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Journey Optimizer vous permet de gérer des campagnes omnicanales planifiées et des moments de contact individuel pour des millions de clients à partir dʼune seule application. Lʼensemble du parcours est optimisé grâce à une prise de décision et des informations intelligentes.

### Dernières versions de produit pour Journey Optimizer

Découvrez les dernières fonctionnalités, améliorations et correctifs dans les [Notes de mise à jour de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=fr).

### Tutoriels et cours pour Journey Optimizer {#tutorials-ajo}

Derniers tutoriels pour Journey Optimizer :

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Mars 2022 | [Utiliser et gérer les expressions enregistrées dans la bibliothèque de personnalisation](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/personalize-content/use-and-manage-saved-expressions-in-personalization-library.html?lang=en) | Vidéo | Découvrez comment utiliser les éléments enregistrés de la bibliothèque de personnalisation dans un message ainsi que comment créer et gérer les éléments de la bibliothèque de personnalisation. |

### Ressources supplémentaires pour [!DNL Journey Optimizer]

* [Documentation Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vidéos pratiques](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=fr)
* [Documentation de la gestion des décisions](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vidéos pratiques](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=fr)

## ![Icône](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Utilisez Experience Platform pour orchestrer le parcours dʼun client à lʼéchelle appropriée au sein de différents canaux dʼexpérience, en anticipant intelligemment les besoins de chacun en temps réel.

### Dernières mises à jour du produit [!DNL Journey Orchestration]

Découvrez les dernières fonctionnalités, améliorations et correctifs dans les Notes de mise à jour de [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=fr).

#### Ressources supplémentaires pour [!DNL Journey Orchestration]

* [Documentation de Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Vidéos pratiques](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=fr)

## ![Icône](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] est une application complète pour la gestion des leads et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en s’engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Voir le [calendrier des versions](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=fr) de [!DNL Marketo Engage] pour consulter les informations les plus récentes sur le calendrier des versions et les notes de mise à jour.

### Nouveaux tutoriels et cours Marketo {#tutorials-marketo}

Nouveaux tutoriels et cours publiés pour Adobe Marketo.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Mars 2022 | [Créer et gérer des boîtes de dialogue personnalisées](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dialogue-management.html?lang=en) | Vidéo | Découvrez comment créer et gérer une _[!UICONTROL Dialogue]_. La conception de conversations ciblées et personnalisées est la clé pour créer une expérience de conversation optimale pour chaque visiteur web. |
| Mars 2022 | [Configuration et installation de votre chatbot](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/setup.html?lang=en) | Vidéo | Un guide pour vous aider à installer le code JavaScript de chatbot sur votre site web ou page d’entrée et à personnaliser son aspect pour qu’il corresponde à votre marque. |
| Mars 2022 | [Permettre aux personnes de réserver des réunions avec votre équipe de vente](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/meeting-booking.html?lang=en) | Vidéo | Utilisation [!UICONTROL Chat dynamique] pour accélérer la connexion aux ventes pour les prospects des comptes cibles. |
| Mars 2022 | [Activez votre intégration Marketo avec [!UICONTROL Chat dynamique]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/marketo-integration.html?lang=en) | Vidéo | [!UICONTROL Chat dynamique] est intégré de manière native à Marketo Engage, ce qui vous permet d’utiliser le contexte des conversations sur les robots pour recibler ou noter vos prospects. |
| Mars 2022 | [Gestion des utilisateurs de [!UICONTROL Chat dynamique]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/user-management.html?lang=en) | Vidéo | Gérez vos [!UICONTROL Chat dynamique] par le biais de Adobe Admin Console. |
| Mars 2022 | [Visite du produit [!UICONTROL Chat dynamique]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/product-tour.html?lang=en) | Vidéo | [!UICONTROL Chat dynamique] est une nouvelle solution de chatbot conçue pour le marketing et les ventes. Il est nativement intégré à Marketo Engage, ce qui vous permet d’utiliser Dynamic Chat comme nouveau canal dans votre marketing cross-canal. Il est simple à utiliser et facile à configurer. |

## ![Icône](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] est une application de gestion du travail unifiée qui permet de partager des idées, créer du contenu, gérer des processus complexes et donner le meilleur de soi-même.

Consultez la page [[!DNL Workfront] versions](https://one.workfront.com/s/product-releases) pour obtenir un récapitulatif des dernières informations relatives à lʼensemble des produits.

## ![Icône](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Notes de mise à jour dʼ[!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [Nouveautés de la version  [!DNL Advertising Cloud Search]](#adcloud-search)
* [Nouveaux tutoriels sur  [!DNL Advertising Cloud] ](#tutorials-ad-cloud)

<!-- 
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

{style="table-layout:auto"}
-->

<!-- 
### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Custom Reports | You can now create and manage [!DNL Amazon S3] and different types of FTP delivery locations, called *[!DNL report destinations]*, for your custom reports. Once you configure report destinations, you can set up each of your new custom reports to be delivered to one or more locations of a single destination type, or to email recipients. Updates to your [!DNL Amazon S3] and FTP credentials won't interrupt report delivery.<br><br>Your existing reports are still sent to the specified email recipients. To configure delivery to a different report destination, create a report with the new destination. |
| [!UICONTROL Packages], [!UICONTROL Placements], and [!UICONTROL Ads] views| When you view data for a single day, the trend charts now include hourly data. Hold the cursor over any point to see the data for that hour. |
| [!UICONTROL Placements] | The placement [!UICONTROL Inspector] now includes an [!UICONTROL Inventory] tab, which shows all deals and their associated metrics for the placement. Use the information to make quick adjustments or troubleshoot issues without generating a custom report. |
| [!UICONTROL Ads] | (Users with permission to include Clearcastclock numbers in their ads) DSP no longer shows an error if you use a clock number that's attached to another ad. **Note:**  The best practice is to use a unique clock number for each video ad. Otherwise, the publisher does not approve all the ads. |
| [!UICONTROL Deal IDs] | The [!UICONTROL Deal ID] settings and other places in the user interface reflect new branding for [!DNL Magnite] SSP:<br><ul><li>The SSP [!DNL Tremor] ([!DNL Telaria]) is now [!DNL Magnite CTV].</li><li>In the coming weeks, [!DNL Rubicon] will change to [!DNL Magnite DV+], where [!DNL DV+] stands for display, video, and other formats such as audio.</li></ul> |
| [!DNL Freewheel] programmatically guaranteed deals | You can now find the status of ads for [!DNL Freewheel] programmatically guaranteed deals from the [!UICONTROL Ads] view. Previously, you could check the status only from the [!UICONTROL Deals] view. |
-->

<!--
{style="table-layout:auto"}
-->

### Nouveautés de la version [!DNL Advertising Cloud Search] {#adcloud-search}

Dernière mise à jour : **14 mars 2022** pour la version du 12 mars

| Fonctionnalité | Description |
| ------- | ----------- |
| [!UICONTROL Portfolios] | Par défaut, l’optimisation hybride est disponible au niveau de la campagne. Vous pouvez désormais activer l’optimisation hybride au niveau du groupe d’annonces, pour laquelle la fonctionnalité d’optimisation est définie. [!DNL Google] Cibles CPA ou ROAS au niveau du groupe publicitaire pour un contrôle plus précis des performances.<br>Pour tout portefeuille, vous devez prévoir une période d’apprentissage avant de le lancer afin de vous assurer qu’il dispose d’une couverture de modèle suffisante. De même, si vous remplacez un portefeuille hybride de l’optimisation au niveau de la campagne par une optimisation au niveau du groupe publicitaire, définissez le portefeuille sur l’état principal pendant environ deux semaines. Cela permet de s’assurer que la fonctionnalité d’optimisation dispose de suffisamment de temps pour en savoir plus sur les groupes publicitaires inclus et générer des cibles.<br>Pour prendre en charge l’optimisation au niveau du groupe d’annonces, les simulations personnalisées peuvent désormais inclure les résultats par groupe d’annonces. Exécutez une simulation personnalisée avec les résultats au niveau du groupe publicitaire avant de lancer un portfolio hybride avec optimisation au niveau du groupe publicitaire. |
| [!UICONTROL Portfolios] <br> [!UICONTROL Campagnes] | (Fonction bêta, [!DNL Microsoft® Advertising] (campagnes) : vous pouvez maintenant configurer les campagnes de recherche pour utiliser la variable [!UICONTROL Maximiser les conversions] stratégie d’offre et éventuellement définir un coût maximum par clic.<br>Si vous participez déjà à la version bêta de l’optimisation hybride pour d’autres stratégies d’enchères automatique, vous avez automatiquement accès à la [!UICONTROL Maximiser les conversions] et vous pouvez inclure des campagnes avec la variable [!UICONTROL Maximiser les conversions] stratégie dans les portefeuilles hybrides. Pour utiliser cette stratégie dans un portfolio hybride, vous devez activer le téléchargement des objectifs Advertising Cloud Search vers [!DNL Microsoft® Ads]. Si vous ne participez pas déjà à la version bêta et souhaitez la rejoindre, contactez votre [!DNL Adobe] gestionnaire de compte. |
| Campagne [!UICONTROL Audiences]<br><br>Campagne [!UICONTROL Feuilles d’envoi groupées] | ([!DNL Microsoft® Advertising] (campagnes) : vous pouvez désormais utiliser n’importe lequel de vos [!DNL Microsoft® Advertising] audiences, à l’exception des audiences dans le marché, comme cibles au niveau de la campagne ou [!UICONTROL adgroup]cibles de niveau -1. Auparavant, vous pouviez les utiliser uniquement comme [!UICONTROL adgroup]cibles de niveau -1. |
| Campagne [!UICONTROL Audiences] | (Fonction bêta, [!DNL Microsoft® Advertising] comptes éligibles [!UICONTROL Correspondance client]) Vous pouvez désormais créer et gérer des audiences de correspondance client en chargeant des fichiers CSV avec des adresses électroniques. Les données doivent être hachées à l’aide de l’algorithme SHA-256. |

{style=&quot;table-layout:auto&quot;}

### Nouveaux tutoriels sur Advertising Cloud {#tutorials-ad-cloud}

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Mars 2022 | [Comment créer un emplacement d’affichage standard](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/placement-create.html) | Vidéo | Découvrez comment créer un emplacement d’affichage standard pour une campagne Advertising Cloud DSP. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nouveaux tutoriels et cours publiés pour Adobe Document Cloud.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Mars 2022 | [Commandes et outils personnalisés](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/custom.html?lang=en) | Vidéo | Découvrez comment améliorer la productivité du workflow de document à l’aide de commandes et d’outils personnalisés. Partagez ensuite vos nouvelles commandes et outils avec vos collègues pour améliorer l’efficacité organisationnelle. |
| Mars 2022 | [Ajout de signets et d’hyperliens](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/bookmarks.html?lang=en) | Vidéo | Découvrez comment ajouter des signets et des hyperliens pour une meilleure navigation et une meilleure interaction avec vos fichiers de PDF. |
| Mars 2022 | [Optimisation des documents numérisés](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizescan.html) | Vidéo | Que votre document vienne d’un appareil photo ou d’un scanner, apprenez à améliorer le résultat dans Acrobat pour une meilleure expérience de visionnage et de recherche de PDF. |
| Mars 2022 | [Convertir Word en PDF, y compris les champs de formulaire](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/wordform.html?lang=en) | Vidéo | Dans ce tutoriel vidéo de 60 secondes, apprenez à convertir des fichiers et des formulaires Word en PDF et à créer automatiquement des champs de formulaire. |
| Mars 2022 | [Champs de formulaire avancés](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/advancedforms.html?lang=en) | Vidéo | Dans ce tutoriel pratique, apprenez à configurer des calculs, à créer un bouton Envoyer par messagerie et à mettre rapidement à jour les pages de formulaire sans recréer tous les champs de formulaire existants. |
| Mars 2022 | [Créer des fichiers de PDF plus efficaces en un clic](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/optimize.html?lang=en) | Vidéo | Dans ce tutoriel vidéo de 60 secondes, apprenez à utiliser l’outil de Optimize PDF pour réduire considérablement la taille de vos fichiers de PDF. |
| Mars 2022 | [Reconnaître le texte dans un fichier de PDF numérisé](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/textrecognition.html?lang=en) | Vidéo | Dans ce tutoriel vidéo de 60 secondes, apprenez à convertir un PDF numérisé afin que vous puissiez rechercher du texte dans le PDF. |
| Mars 2022 | [Laissez Acrobat vous aider à rendre des PDF accessibles](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/accessible.html?lang=en) | Vidéo | Dans ce tutoriel vidéo de 60 secondes, apprenez à vérifier si un PDF est accessible. |
| Mars 2022 | [Export PDF à Word à partir de votre téléphone](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/exportwordphone.html?lang=en) | Vidéo | Dans ce tutoriel vidéo de 60 secondes, découvrez comment convertir un fichier de PDF en document Microsoft® Word entièrement modifiable avec l’application mobile Acrobat. |
| Mars 2022 | [Protect de vos fichiers PDF avec un mot de passe](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/protect.html?lang=en) | Vidéo | Dans ce tutoriel vidéo de 60 secondes, apprenez à protéger un PDF afin qu’un mot de passe soit nécessaire pour ouvrir, soit pour modifier le PDF. |

{style=&quot;table-layout:auto&quot;}

Pour obtenir de l’aide sur Document Cloud, voir :

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=fr)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=fr)
* [Formation et assistance sur Document Cloud](https://helpx.adobe.com/fr/support/document-cloud.html)

## ![Icône](/assets/creative-cloud-24.png) Adobe Creative Cloud abonnement Entreprise {#creative-cloud}

Consultez les [tutoriels Creative Cloud abonnement Enterprise](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=fr) pour obtenir les derniers tutoriels.

## ![Icône](/assets/experience-league.png) Gestion des données client - Voix {#voices}

[Voix de gestion des données clients](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) est votre destination en tant que responsable et spécialiste de la gestion des données client. Cette collection de tutoriels est votre guichet unique pour écouter vos pairs, vous inspirer et découvrir les développements de MarTech. Aucun enregistrement requis, cliquez et regardez.

## ![Icône](/assets/experience-league.png) Plans directeurs d’expérience digitale {#blueprints}

[Les plans directeurs de l’expérience digitale](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=fr) sont des implémentations reproductibles qui vous permettent d’aborder la stratégie et de résoudre rapidement les problèmes établis de l’entreprise. Chaque plan directeur fournit une série d’artefacts expliquant le problème des entreprises à haute valeur ajoutée, les architectures, les étapes d’implémentation, les considérations techniques et les liens vers la documentation pertinente.

| Publication | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Février 2022 | [Parcours clients](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=fr) | Vidéo | Les parcours clients permettent aux marques d’interagir de manière proactive et de communiquer avec leurs clients par le biais de canaux tels que les e-mails, les SMS et les alertes mobiles. |
| Février 2022 | [Plan directeur de Campaign v7](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=fr) | Vidéo | Adobe Campaign v7 est un outil de campagne conçu pour les canaux marketing traditionnels tels que les e-mails et le publipostage direct. Il offre des fonctionnalités ETL et de gestion des données performantes permettant de concevoir et d’organiser une campagne parfaite. |

{style=&quot;table-layout:auto&quot;}

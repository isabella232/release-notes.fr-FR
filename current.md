---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: notes de mise à jour
last-update:  Octobre 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 6efac6a7bd4bac8b9ee42a743761e2ea1fb82e82

---


# Accès anticipé - Notes de mise à jour d’Experience Cloud - octobre 2019

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!IMPORTANT]
>
>Cette page contient une version anticipée du contenu et peut être modifiée avant la version définitive qui sera publiée.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. Vous recevrez une notification trois à cinq jours ouvrables avant la sortie de la mise à jour. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

## Date de publication : 10 octobre 2019

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (liens vers l’aide de la solution)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (liens vers l’aide de la solution)

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Notes de mise à jour d’Experience Platform, d’Experience Platform Launch, d’Identity Service et des bulletins de sécurité.

* [Experience Platform Launch](#launch)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/security.html) (Tous les produits Adobe)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- |  
| API de Privacy Service : CCPA | La Loi sur la protection des renseignements personnels des consommateurs de Californie (ACCP) renforce les droits à la vie privée et la protection des consommateurs pour les résidents de Californie (États-Unis). Cette loi entrera en vigueur le 1er janvier 2020.<br/>L'ACCP accorde de nouveaux droits à la confidentialité des données aux résidents de Californie, comme le droit d'accéder et de supprimer leurs données personnelles, de savoir si leurs données personnelles sont vendues ou divulguées (et à qui) et de refuser la vente de leurs données personnelles.<br/>En prévision de l’ACFPC, le Service de la protection de la vie privée appuiera les demandes d’exclusion de la vente de données à caractère personnel.<br/>Le Service de la protection de la vie privée s’appelait auparavant le Service du RGMD et conserve toutes les fonctionnalités précédentes, maintenant étendues pour prendre en charge l’ACCP.<br/>CCPA dans Analytics : Présentation `[Link to new CCPA page in Analytics]()`<br/>[de Privacy Service](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Rapports de confidentialité : Console d’administration Analytics | L’activation des rapports de confidentialité pour Analytics ajoute un ensemble de variables réservées à une suite de rapports.  Les variables sont conçues pour faciliter la collecte des données de consentement des consommateurs au niveau de l’accès.<br/>Nouvelles dimensions :<br/><ul><li>Exclusion de la gestion du consentement</li><li>Inscription à la gestion du consentement</li><li>Variables de gestion du consentement : `[Link to new Consent Variables page in Analytics]()`</li></ul> |
| Analyses audio et vidéo : Prise en charge de la confidentialité | Deux nouvelles variables ont été ajoutées à l’API Media Collection :<br/><ul><li> analytics.optOutServerSideForwarding</li><li> analytics.optOutShare</li></ul>Il s’agit de variables facultatives qui peuvent être utilisées pour capturer l’état du consentement du consommateur au moment de l’accès.<br/>[Documentation](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/>de l’API de collecte de médiasLes nouvelles variables de données contextuelles Gestion du consentement Analytics ont été ajoutées au formulaire Analyses fédérées. Ces variables peuvent désormais être utilisées pour marquer l’exclusion du partage ou la vente d’accès pour la fédération.<br/>[Télécharger un formulaire fédéré](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| Analysis Workspace: Update to Freeform table totals | Les tableaux à structure libre comprennent désormais deux totaux, un total **** de tableau et un total **** général. The Table total row accounts for [report filters](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) applied. Previously, only segmentation impacted totals. [Learn more](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>In addition, **[!UICONTROL Show Totals]** and **[!UICONTROL Show Grand Total]** options have been added to **[!UICONTROL Column Settings]**.<br/>With this change to Freeform totals, dependent visualizations will be updated (e.g. linked **[!UICONTROL Summary Number]** visualizations), as well as exported CSV and PDF data. |
| Analysis Workspace: Option to remove Unspecified/None | The ability to easily remove ‘Unspecified (None)’ has been added as an option to report filters. |
| Analysis Workspace: Deprecation of purple granularity components | Purple granularity time components (Minute, Hour, Day, Week, Month, Quarter, Year) have been deprecated. The purple time components have always behaved exactly like their orange dimension counterparts, so this change will simplify the experience. **No action needs to taken if you previously used one of the purple time components.**<br/>With this change, the purple Time section has also been renamed to Date Ranges.******** |

#### Correctifs

* Analysis Workspace: Fixed an issue that resulted in incorrect search results when searching for dimension items in the left rail. (AN-185065)
* Fixed issues with being unable to delete or unpublish shared segments in Adobe Audience Manager (AAM). The fix is to not delete the segment if AAM is unresponsive. (AN-185882, AN-185883, AN-184607)
* Fixed a timeout issue with being unable to load segments in Ad Hoc Analysis. (AN-184654)
* Correction d’un problème survenant lorsque la suite de rapports que vous avez utilisée pour la dernière fois était par la suite masquée ou que vous n’aviez plus les autorisations d’accès à cette suite de rapports. Dans ce cas, vous ne pouviez plus vous connecter via Experience Cloud. (AN-181777)
* Correction d’un problème de délai d’expiration dans les segments qui rendait difficile la création d’une suite de rapports virtuelle basée sur un segment. (AN-179684)

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Fin de la prise en charge de TLS 1.1 | 3 octobre 2019 | D’ici le 31 mars 2020, Adobe Analytics supprimera la prise en charge de TLS 1.1. Ce changement s’inscrit dans le cadre des efforts que nous déployons pour maintenir les normes de sécurité les plus élevées et promouvoir la sécurité des données des clients. |
| San Jose FTP Broker se termine pour Londres et Singapour | Juillet 2020 | Pour les clients de Londres et Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/>Pour Londres, utilisez [ftp3.omniture.](ftp://ftp3.omniture.com/)<br/>comPour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/) |
| Mise à jour des totaux de tableau à structure libre d’Analysis Workspace | 12 septembre 2019 | En octobre 2019, les lignes totales du tableau à structure libre commenceront à tenir compte des filtres [de](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) rapport appliqués. À ce jour, les totaux ne prennent en compte que la segmentation. Grâce à cette modification, les visualisations dépendantes sont mises à jour (par exemple, visualisations [!UICONTROL Nombre de résumés]), ainsi que les données CSV et PDF exportées. |
| Modification à venir concernant le champ `createDate` pour les utilisateurs d’Analytics | 30 août 2019 | En octobre ou novembre 2019, le champ `createDate` pour les utilisateurs d’Analytics sera mis à jour de l’heure normale du Pacifique des États-Unis vers une valeur Date/Heure correctement formatée avec les informations sur le fuseau horaire. (AN-183468) |
| Prise en charge des décalages de fuseau horaire historiques | 8 août 2019 | Analytics gère désormais automatiquement les décalages de fuseau horaire pour les accès horodatés. Après cette modification du 8 août, les systèmes qui chargent les données pour un traitement historique n’auront plus besoin d’ajuster les décalages de fuseau horaire avant d’envoyer les données. |
| Limites du créateur de règles de classification | Ajout le 5 juin 2019 | Ces limites ne sont pas nouvelles, mais elles ont été ajoutées à la documentation [ici](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nouvelles limites des opérateurs de segment | Ajout le 31 mai 2019 | À compter du 18 juillet 2019, les opérateurs de segment _contient n’importe lequel_, _ne contient pas n’importe lequel_, _contient tous les_ et _ne contient pas tous les_ seront limités à 100 mots par champ d’entrée. Après cette date, la limite sera appliquée à tous les segments nouveaux et modifiés. Les segments existants qui dépassent la limite continueront à être pris en charge, mais ne pourront pas être modifiés ou enregistrés tant que le champ d’entrée dépasse la limite. Ces limites sont appliquées dans le cadre d’efforts continus visant à améliorer les performances des requêtes. |
| Modifications concernant la prise en charge des **[!UICONTROL classifications activées par date]** et des **[!UICONTROL classifications numériques 2]** | Mise à jour le 28 mai 2019 | La possibilité d’importer des classifications numériques 2 et des classifications activées par date a été supprimée du code base. Cette modification a pris effet lors de la version de maintenance de juillet 2019. S’il y a des colonnes numériques ou des colonnes activées par date dans le fichier d’importation, ces cellules seront ignorées et les autres données de ce fichier seront importées normalement. <br/>Les classifications existantes peuvent toujours être exportées par le biais du workflow de classification standard et sont toujours disponibles dans les rapports. |
| Modification des calculs des _totaux des rapports_ | Mise à jour le 9 juillet 2019 | Le **18 juin 2019**, Adobe Analytics a uniformisé les calculs des _totaux des rapports_ pour toutes les dimensions et mesures. Pour cette raison, les totaux de certains rapports ont été modifiés (notamment les rapports Props ou Attributs du client). Avant cette modification, certains totaux incluaient ou excluaient la ligne _Non spécifié_ dans le total, peu importe si elle apparaissait ou _non_ dans le rapport. <br/>À compter du 18 juin 2019, le poste _Non spécifié_ apparaîtra toujours dans le total du rapport, même s’il n’apparaît pas comme poste sur le rapport. En outre, les segments qui utilisent la logique _existe_ ou _n’existe pas_ peuvent afficher des résultats différents pour certaines dimensions après cette modification, en particulier les dimensions dont _Non spécifié_ possède un nom spécial, comme l’élément de ligne « Tapé/Marqué » pour la dimension Type de référent ou l’élément de ligne « Autre » pour la dimension Type de périphérique. Cette modification concernera Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder et l’API Reporting. |
| Mise à jour des téléchargements CSV d’Analysis Workspace | 10 avril 2019 | À partir du 11 avril 2019, plusieurs modifications seront apportées aux **[!UICONTROL téléchargements CSV]** (et **[!UICONTORL copies dans le Presse-papiers]**) depuis Analysis Workspace pour supprimer le formatage des données exportées.  <ul><li>Le séparateur des milliers ne sera plus inclu. Le séparateur décimal sera toujours inclus et se conformera au format défini sous **[!UICONTROL Composants &gt; Paramètres de rapport &gt; Séparateur des milliers]**. Remarque : Les valeurs numériques qui utilisent une virgule comme séparateur décimal continuent à être placées entre guillemets dans le fichier CSV exporté.</li><li>Aucun symbole de devise ne sera affiché.</li><li>Aucun symbole de pourcentage ne sera affiché. Les pourcentages seront sous forme décimale. Par exemple, 75 % sera représenté comme 0,75.</li><li>La durée sera indiquée en secondes.</li><li>Les tableaux de cohortes affichent uniquement les valeurs brutes. Les pourcentages sont supprimés.</li><li>Si un nombre n’est pas valide, une cellule vide s’affichera.</li></ul> |
| Modification à venir de la commande du débogueur Analysis Workspace | 4 avril 2019 | Le **13 juin 2019**, la commande de la console permettant d’activer le débogueur Analysis Workspace sera remplacée par adobeTools.debug.includeOberonXml. adobe.tools.debug.includeOberonXml cessera de fonctionner après cette date. |
| Numéros de version des navigateurs mobiles | 7 février 2019 | Le niveau de troncation des numéros de version des navigateurs mobiles est modifié depuis le 8 janvier 2019 (de 2 à 1). Depuis lors, seuls les deux premiers niveaux des versions sont affichés (par ex. _Firefox 64.0.2_ apparaît désormais sous la forme _Firefox 64.0_). |
| Fin de vie d’[!DNL Ad Hoc Analysis] | 29 janvier 2019 | Le 6 août 2018, Adobe a annoncé la prochaine fin de vie d’[!DNL Ad Hoc Analysis]. dont la date sera communiquée dès que possible.<br/>Pour plus d’informations, y compris les versions de Java compatibles durant cette période, consultez la section [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Liens d’[!DNL Analytics] rapports courts | 14 janvier 2019 | Tout lien d’[!DNL Analytics] rapport court qui n’aura pas été consulté pendant un an sera nettoyé et supprimé à compter du jeudi 17 janvier 2019, selon un calendrier progressif. |
| Flux de données : colonne post_product_list – modification de taille | 9 janvier 2019 | Le 7 février 2019, Adobe prévoit d’étendre la taille de la colonne post_product_list de 64 Ko à 16 Mo. Cette modification garantit que les valeurs eVar de marchandisage ajoutées à la colonne post_product_list lors du traitement ne causent pas de troncature de valeurs de produits et de revenus. Si certains de vos processus assimilent des valeurs post_product_list, assurez-vous qu’ils peuvent gérer des valeurs allant jusqu’à 16 Mo en longueur ou entraîneront une troncature des valeurs à 16 Ko afin d’éviter les problèmes d’assimilation de données. |
| Modifications de gestion concernant les points de terminaison inactifs [!DNL Analytics Live Stream] | 20 décembre 2018 | À compter du 1er février 2019, les points de terminaison [!DNL Live Stream] n’ayant reçu aucune connexion d’utilisateurs actifs durant 90 jours pourront être désactivés. Vous pouvez contacter l’assistance clientèle pour obtenir des renseignements au sujet de vos points de terminaison [!DNL Live Stream] et, si besoin, demander leur réactivation. De plus, veuillez vous assurer que vos processus client maintiennent une connexion permanente, comme prévu par la configuration du service, et qu’ils sont mis en œuvre pour se reconnecter lorsque la connexion est désactivée ou interrompue. |
| Mise à jour d’Adobe [!DNL Report Builder] en raison de la fin de la prise en charge du protocole TLS 1.0 | 7 septembre 2018 | En raison de la fin de la prise en charge du protocole TLS 1.0, nous avons recommandé aux utilisateurs de [!DNL Report Builder] de télécharger la version v5.6.21 avant février 2019. À compter de cette date, les versions antérieures de [!DNL Report Builder] ne fonctionneront plus. |

### [!DNL AppMeasurement] {#appm}

Voir Notes [de mise à jour](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)AppMeasurement pour JavaScript.

## Audience Manager {#aam}

Nouvelles fonctionnalités, améliorations et correctifs dans Audience Manager.

**Correctifs et améliorations**

* Tous les comptes de clients créés après le 1er juillet 2019 se verront automatiquement attribuer une [!DNL Tableau] licence leur donnant accès à leurs rapports. Si votre compte a été créé avant le 1er juillet 2019 et que vous n’avez toujours pas accès à vos [!DNL Tableau] rapports, contactez le service à la clientèle.
* Nous avons supprimé des abonnements aux caractéristiques d’activité générés de manière incorrecte pour les profils de visiteurs qui n’avaient pas de synchronisation des identifiants avec la source de données de caractéristiques (AAM-45371).
* Nous avons supprimé les ID de périphérique global non valides des sources de données globales. Voir Sources [de données](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html) globales pour savoir à quoi doivent ressembler les ID de périphérique valides acceptés par Audience Manager (AAM-41259).
* Correction d’un bogue en raison duquel la page Segments ne répondait plus lorsque vous tentiez de supprimer un segment protégé (AAM-49881).
* Lors de la modification de destinations pour les audiences personnalisées Twitter, le sélecteur de [!UICONTROL compte] n’est désormais actif que si aucun [!DNL Twitter Ads] compte n’est attribué à la destination (AAM-49975).
* Correction d’un bogue empêchant les utilisateurs de désactiver les flux de données [!UICONTROL Audience Marketplace] lorsque les abonnements sont désactivés (AAM-49640).
* Nous avons apporté plusieurs améliorations à l’accessibilité de l’interface utilisateur d’Audience Manager.

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Maintenance du produit

* **AEM 6.3.3.6**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 6 (6.3.3.6 released September 25, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.3, April 2017.
   * [Notes de mise à jour](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   AEM 6.4, Service Pack 6.0 (6.4.6.0 released September 19, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.4, April 2018.
   * [Notes de mise à jour](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0**
AEM 6.5, Service Pack 2.0 (6.5.2.0 released September 19, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.5, April 2019.
   * [Notes de mise à jour](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Auto-assistance

* **Scene7 : Processus de retraitement des ressources**

   Vous pouvez désormais retraiter des fichiers dans un dossier qui comporte déjà un profil de traitement existant que vous avez modifié ultérieurement.
Voir [Retraitement des fichiers dans un dossier après avoir modifié son profil](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)de traitement.

* **Intégration des visionneuses de médias dynamiques avec Adobe Analytics et Adobe Launch**

   L’extension Visionneuses de médias dynamiques pour Adobe Launch, ainsi que la version 5.13 des visionneuses de médias dynamiques, permettent aux clients de Contenu multimédia dynamique, d’Adobe Analytics et d’Adobe Launch d’utiliser des événements et des données spécifiques aux visionneuses de médias dynamiques dans leur configuration de lancement Adobe.
Voir [Intégration de visionneuses de médias dynamiques avec Adobe Analytics et Adobe Launch](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html).

* **Application de bureau AEM**

   L’application de bureau AEM 2.0 est désormais disponible pour les créatifs, les spécialistes du marketing et les utilisateurs de la ligne d’activité, afin qu’ils puissent travailler avec AEM Assets.
Reportez-vous aux Notes de mise à jour de l’application de bureau [AEM.](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Core Components**
   * Découvrez les fonctionnalités de localisation des composants principaux et comment ils fonctionnent avec les modèles AEM.
      [Voir l'exemple](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html).
   * Composants principaux 2.6.0 introduit un composant Fragment d’expérience. The component is now available along with authoring documentation and developer details and project download available on GitHub.[](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html)[](https://github.com/adobe/aem-core-wcm-components)

* **AEM Assets**
   * Nouvelle documentation pour la fonctionnalité de recherche visuelle/analogique.
See Find similar images.[](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)
   * Connected Assets functionality now uses documents that are available on remote DAM deployment, in addition to images file formats.
See Use Connected Assets to share DAM assets in AEM Sites.[](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html)
   * Fresh content on asset searching and discovery. The Search assets in AEM topic is your one-stop-shop for information on using, configuring, troubleshooting, limitations, and tips.
__
See Search assets in AEM.[](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html)

### Ressources supplémentaires

* [Formation et assistance pour AEM 6.5 – Accueil](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Formation et assistance pour AEM 6.4 – Accueil](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Formation et assistance pour AEM 6.3 – Accueil](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Formation et assistance pour AEM 6.2 – Accueil](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versions plus anciennes de la documentation AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help Home](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media ](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notes de mise à jour de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

<!-- ### Adobe Campaign Classic

* [Campaign Classic 19.1.4 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) – build 9032
* [Campaign Classic 19.1.5 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) – build 9033

### Adobe Campaign [!UICONTROL Control Panel]

Text

### Additional resources -->

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

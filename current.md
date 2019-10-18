---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: notes de mise à jour
last-update: Octobre 2019
author: mfrei
translation-type: ht
source-git-commit: 0371f31dcb1feb368bd8a2937a9f2d9583e208dc

---


# Notes de mise à jour d’Adobe Experience Cloud - Octobre 2019

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!NOTE]
>
>Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) pour être averti par e-mail de la publication des prochaines versions. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

## Date de publication : 10 octobre 2019

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/fr-FR/target/using/release-notes/target-release-notes.html) (liens vers l’aide de la solution)
* [!DNL Primetime](https://helpx.adobe.com/fr/support/primetime.html) (liens vers l’aide de la solution)
* [!DNL Advertising Cloud](#adcloud)

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Notes de mise à jour d’Experience Platform, d’Experience Platform Launch, d’Identity Service et des bulletins de sécurité.

* [Experience Platform Launch](#launch)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/fr/security.html) (Tous les produits Adobe)

### Experience Platform Launch {#launch}

Pour consulter les notes de mise à jour et la documentation du produit, voir [Experience Platform Launch](https://docs.adobe.com/content/help/fr-FR/launch/using/intro/release-notes/current.html).

## [!DNL Analytics] {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)

Pour consulter la documentation du produit, voir [Accueil de l’aide Adobe Analytics](https://docs.adobe.com/content/help/fr-FR/analytics/landing/home.html).

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- |  
| API Privacy Service : CCPA | Le California Consumer Privacy Act (CCPA) protège la vie privée et les consommateurs pour les personnes résidant en Californie, États-Unis. Ce document sera en vigueur à partir du 1er janvier 2020.<br/><br/>Le CCPA offre aux Californiens de nouveaux droits sur leurs données personnelles, comme le droit d’y accéder et de les supprimer, mais aussi de savoir si leurs données sont vendues ou divulguées (et, le cas échéant, à qui) et de refuser la vente de leurs données.<br/><br/>Afin de préparer l’arrivée du CCPA, le Privacy Service recevra les demandes de refus de vente de données personnelles.<br/><br/>Le Privacy Service, nouveau nom du RGPD Service, conserve toutes ses fonctionnalités existantes et les adapte au CCPA.<br/><br/>[CCPA dans Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br/><br/>[Présentation de Privacy Service](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Rapport de confidentialité : Analytics Admin Console | L’activation de la création de rapports de confidentialité pour Analytics ajoute un ensemble de variables réservées à une suite de rapports.  Ces variables sont conçues pour aider à la collecte de données de consentement des consommateurs au niveau de l’accès.<br/><br/>Nouvelles dimensions :<br/><ul><li>Droit d’opposition de gestion du consentement</li><li>Accord préalable de gestion du consentement</li><li>[Variables de gestion du consentement](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| Audio et vidéo Analytics : prise en charge de la confidentialité | Deux nouvelles variables ont été ajoutées à l’API Media Collection :<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>Il s’agit de variables facultatives qui peuvent être utilisées pour enregistrer le statut du consentement du consommateur au moment de l’accès.<br/><br/>[Documentation de l’API Media Collection](https://docs.adobe.com/content/help/fr-FR/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>Les nouvelles variables de données contextuelles de la gestion du consentement dans Analytics ont été ajoutées au formulaire Federated Analytics. Ces variables peuvent désormais être utilisées pour marquer le droit d’opposition du partage des données ou de la vente d’accès à celles-ci pour la fédération.<br/><br/>[Télécharger le formulaire Federated Analytics](https://docs.adobe.com/content/help/fr-FR/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| Analysis Workspace : mise à jour des totaux des tableaux à structure libre | Les tableaux à structure libre comprennent désormais deux totaux, un **[!UICONTROL Total du tableau]** et un **[!UICONTROL Total général]**. La ligne Total du tableau tient compte des [filtres de rapport](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) appliqués. Avant la mise à jour, seule la segmentation affectait les totaux. [En savoir plus](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>De plus, les options **[!UICONTROL Afficher les totaux]** et **[!UICONTROL Afficher le total général]** ont été ajoutées aux **[!UICONTROL Paramètres des colonnes]**.<br/>Grâce à cette modification des totaux pour les tableaux à structure libre, les visualisations dépendantes sont mises à jour (par exemple, les visualisations **[!UICONTROL Nombre de résumés]**), ainsi que les données CSV et PDF exportées. |
| Analysis Workspace : option de suppression pour Non spécifié/Aucun | La possibilité de supprimer facilement « Non spécifié (Aucun) » a été ajoutée en tant qu’option des filtres de rapport. |
| Analysis Workspace : abandon des composants de granularité violets | Les composants temporels de granularité violets (minute, heure, jour, semaine, mois, trimestre, année) ont été abandonnés. Les composants temporels violets se sont toujours comportés exactement comme leurs homologues de dimension orange, ce changement simplifiera donc l’expérience. **Aucune action** n’est nécessaire si vous avez déjà utilisé l’un des composants temporels violets.<br/>Avec cette modification, la section **[!UICONTROL Heure]** violette a également été renommée en **[!UICONTROL Plages de dates]**. |

#### Correctifs

* Analysis Workspace : correction d’un problème qui générait des résultats de recherche incorrects lors de la recherche d’éléments de dimension dans le rail de gauche. (AN-185065)
* Correction de problèmes liés à l’impossibilité de supprimer ou d’annuler la publication de segments partagés dans Adobe Audience Manager (AAM). Le correctif consiste à ne pas supprimer le segment si AAM ne répond pas. (AN-185882, AN-185883, AN-184607)
* Correction d’un problème de délai d’expiration en raison duquel les segments ne pouvaient pas être chargés dans les Ad Hoc Analysis. (AN-184654)
* Correction d’un problème survenant lorsque la suite de rapports que vous avez utilisée pour la dernière fois était désormais masquée ou lorsque vous n’aviez plus les autorisations d’accès à cette suite de rapports. Dans ce cas, vous ne pouviez plus vous connecter via Experience Cloud. (AN-181777)
* Correction d’un problème de délai d’expiration dans les segments qui rendait difficile la création d’une suite de rapports virtuelle basée sur un segment. (AN-179684)
* Correction d’un problème en raison duquel, dans de rares cas, les données étaient tronquées si le codage était incorrect. (AN-186707)
* Les moteurs de recherche Yandex sont maintenant correctement répartis par pays. (AN-181728)

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Fin de la prise en charge de TLS 1.1 | 3 octobre 2019 | D’ici le 31 mars 2020, Adobe Analytics supprimera la prise en charge de TLS 1.1. Ce changement s’inscrit dans le cadre des efforts que nous déployons pour respecter les meilleures normes de sécurité et promouvoir la sécurité des données de nos clients. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | Pour les clients basés à Londres et à Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Mise à jour des totaux de tableau à structure libre d’Analysis Workspace | 12 septembre 2019 | En octobre 2019, les lignes total du tableau à structure libre commenceront à tenir compte des [filtres de rapport](https://docs.adobe.com/content/help/fr-FR/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) appliqués. À ce jour, les totaux ne prennent en compte que la segmentation. Grâce à cette modification, les visualisations dépendantes sont mises à jour (par exemple, visualisations [!UICONTROL Nombre de résumés]), ainsi que les données CSV et PDF exportées. |
| Modification à venir concernant le champ `createDate` pour les utilisateurs d’Analytics | 30 août 2019 | En octobre ou novembre 2019, le champ `createDate` pour les utilisateurs d’Analytics sera mis à jour de l’heure normale du Pacifique des États-Unis vers une valeur Date/Heure correctement formatée avec les informations sur le fuseau horaire. (AN-183468) |
| Prise en charge des décalages de fuseau horaire historiques | 8 août 2019 | Analytics gère désormais automatiquement les décalages de fuseau horaire pour les accès horodatés. Après cette modification du 8 août, les systèmes qui chargent les données pour un traitement historique n’auront plus besoin d’ajuster les décalages de fuseau horaire avant d’envoyer les données. |
| Limites du créateur de règles de classification | Ajout le 5 juin 2019 | Ces limites ne sont pas nouvelles, mais elles ont été ajoutées à la documentation [ici](https://docs.adobe.com/content/help/fr-FR/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
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

Voir [Notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/fr-FR/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Nouvelles fonctionnalités, améliorations et correctifs dans Audience Manager.

**Correctifs et améliorations**

* Tous les comptes clients créés après le 1er juillet 2019 se verront attribuer automatiquement une licence [!DNL Tableau], leur donnant ainsi accès à leurs rapports. Si votre compte a été créé avant le 1er juillet 2019 et que vous n’avez pas encore accès à vos rapports [!DNL Tableau], veuillez contacter l’Assistance clientèle.
* Nous avons corrigé une erreur qui générait des caractéristiques d’activité incorrectes et augmentait artificiellement les taux de correspondance et la taille des audiences. Suite à ce correctif, vous pouvez constater une diminution de la taille des segments créés avec des caractéristiques d’activité générées automatiquement. Ce comportement est normal et attendu (AAM-45371).
* Nous avons supprimé des ID d’appareils mondiaux invalides des sources de données mondiales. Consultez la rubrique [Sources de données globales](https://docs.adobe.com/content/help/fr-FR/audience-manager/user-guide/features/data-sources/global-data-sources.html) pour savoir à quoi doivent ressembler les ID d’appareil valides acceptés par Audience Manager (AAM-41259).
* Correction d’une erreur qui survenait lors d’une tentative de suppression d’un segment protégé suite à laquelle la page des segments ne répondait plus (AAM-49881).
* Lors de la modification des destinations pour les audiences personnalisées sur Twitter, le sélecteur [!UICONTROL Compte] n’est maintenant disponible que si la destination n’a pas déjà un compte [!DNL Twitter Ads] assigné (AAM-49975).
* Correction d’une erreur qui empêchait les utilisateurs de désactiver les flux de données [!UICONTROL Audience Marketplace] lorsque les abonnements étaient désactivés (AAM-49640).
* Nous avons apporté plusieurs améliorations à l’accessibilité de l’interface utilisateur d’Audience Manager.

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Version du produit

* **Cloud Manager 2019.9.0**

   * Cloud Manager 2019.9.0, publié le 12 septembre 2019, met à jour les critères de test de sécurité, ajoute des graphiques de surveillance téléchargeables et corrige certains problèmes de convivialité signalés par les clients.
   * [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Maintenance du produit

* **AEM 6.3.3.6**

   AEM 6.3 Service Pack 3, Cumulative Fix Pack 6 (6.3.3.6 publié le 25 septembre 2019), est une mise à jour importante qui contient des correctifs client clés, publiée depuis la mise à disposition d’AEM 6.3 en avril 2017.
   * [Notes de mise à jour](https://helpx.adobe.com/fr/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/fr/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   AEM 6.4, Service Pack 6,0 (version 6.4.6.0 publiée le jeudi 19 septembre 2019) est une mise à jour importante qui inclut des correctifs clients clés publiés depuis la disponibilité générale d’AEM 6.4, avril 2018.
   * [Notes de mise à jour](https://helpx.adobe.com/fr/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/fr/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0**
AEM 6.5, Service Pack 2.0 (version 6.5.2.0 publiée le 19 septembre 2019) est une mise à jour importante qui inclut des correctifs clients clés publiés depuis la disponibilité générale d’AEM 6.5, avril 2019.
   * [Notes de mise à jour](https://helpx.adobe.com/fr/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versions CFP d’AEM Forms](https://helpx.adobe.com/fr/aem-forms/kb/aem-forms-releases.html)

### Auto-assistance

* **Scene7 : processus de nouveau traitement des ressources**

   Vous pouvez maintenant traiter à nouveau les ressources dans un dossier qui a déjà un profil de traitement que vous avez changé par la suite.
Voir [Traitement des ressources dans un dossier après avoir modifié son profil de traitement](https://helpx.adobe.com/fr/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile).

* **Intégration de Dynamic Media Viewers dans Adobe Analytics et Adobe Launch**

   L’extension Dynamic Media Viewers pour Adobe Launch ainsi que la version 5.13 de Dynamic Media Viewers permettent aux clients de Dynamic Media, Adobe Analytics et Adobe Launch d’utiliser des événements et des données spécifiques pour leur configuration de Dynamic Media Viewers dans Adobe Launch.
Voir [Intégration de Dynamic Media Viewers dans Adobe Analytics et Adobe Launch](https://helpx.adobe.com/fr/experience-manager/6-5/assets/using/launch.html).

* **Application de bureau AEM**

   L’application de bureau AEM 2.0 est désormais disponible pour les utilisateurs créatifs, les spécialistes marketing et les professionnels afin qu’ils puissent travailler avec AEM Assets.
Reportez-vous aux [Notes de mise à jour de l’application de bureau AEM.](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Composants Core**
   * Découvrez les fonctionnalités de localisation des composants Core et comment ils fonctionnent avec les modèles AEM.
      [Voir l’exemple](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html).
   * La version 2.6.0 des composants Core introduit un composant Experience Fragment. Le composant est désormais disponible avec la [documentation de création](https://docs.adobe.com/content/help/fr-FR/experience-manager-core-components/using/introduction.html). [Les détails des développeurs et le téléchargement du projet sont disponibles sur GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM Assets**
   * Nouvelle documentation pour la fonctionnalité de recherche visuelle/analogique.
Voir [Rechercher des images similaires](https://helpx.adobe.com/fr/experience-manager/6-5/assets/using/search-assets.html#visualsearch).
   * La fonctionnalité Ressources connectées utilise désormais les documents disponibles lors du déploiement DAM à distance, en plus des formats de fichiers d’images.
Voir [Utilisation des ressources connectées pour partager des ressources DAM dans AEM Sites](https://helpx.adobe.com/fr/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html).
   * Un nouveau contenu pour la recherche et la découverte de ressources. La rubrique _Rechercher des ressources dans AEM_ constitue votre source unique pour obtenir des informations sur l’utilisation, la configuration, le dépannage, les restrictions et les astuces.
Voir [Recherche de ressources dans AEM](https://helpx.adobe.com/fr/experience-manager/6-5/assets/using/search-assets.html).

### Ressources supplémentaires

* [Formation et assistance pour AEM 6.5 – Accueil](https://helpx.adobe.com/fr/support/experience-manager/6-5.html)
* [Formation et assistance pour AEM 6.4 – Accueil](https://helpx.adobe.com/fr/support/experience-manager/6-4.html)
* [Formation et assistance pour AEM 6.3 – Accueil](https://helpx.adobe.com/fr/support/experience-manager/6-3.html)
* [Formation et assistance pour AEM 6.2 – Accueil](https://helpx.adobe.com/fr/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://helpx.adobe.com/fr/experience-manager/cloud-manager/user-guide.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/fr/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/fr-FR/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notes de mise à jour de Livefyre](https://docs.adobe.com/content/help/fr-FR/livefyre/using/release-notes/c-rn.translate.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Adobe Campaign Classic

* [Mise à jour de Campaign Classic 19.1.4](https://docs.campaign.adobe.com/doc/AC/fr/RN.html#9032) - Nouveau build 9032
* [Mise à jour de Campaign Classic 19.1.6](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-19-1-6-build-9035) - build 9035

### Ressources supplémentaires

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/fr/support/campaign/standard.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/fr-FR/campaign-standard/using/release-notes/release-notes.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Calendrier des versions](https://helpx.adobe.com/fr/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/fr/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/fr/RN.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

Mise à jour pour la version du 12 octobre 2019

| Affichage | Fonction |
|------|---------|
| Rechercher dans les campagnes | Advertising Cloud peut désormais synchroniser et proposer un suivi au niveau des annonces pour les comptes sur Yahoo! Japan Display Network. Si vous fournissez des informations de connexion pour un compte, l’intégralité des campagnes, des groupes publicitaires et des publicités existants dans le compte est disponible en lecture seule dans les vues de gestion de campagnes. Les données sur les clics, les coûts, les conversions et d’autres performances sont disponibles dans les vues de gestion de campagnes et dans les rapports de base et avancés. |
|  | (Publicitaires avec Google Analytics) Advertising Cloud Search permet de synchroniser les mesures de conversion pour un compte, une propriété et une combinaison d’affichage spécifiques de Google Analytics à des fins d’optimisation et de création de rapports. Les pages vues, les sessions, le taux de rebond (calculé en tant que rebonds/sessions) et la durée de la session sont automatiquement inclus. Vous pouvez inclure jusqu’à 16 mesures supplémentaires par source de données. |
|  | (Comptes Google Ads existants pour les publicitaires qui disposent d’une intégration Advertising Cloud-Adobe Analytics) Un nouveau format est disponible pour le code de suivi s_kwcid. Il permet à Advertising Cloud de partager des données sur le compte à l’aide de la fonctionnalité de création de rapports et d’analyse d’Adobe Analytics. Le format le plus récent comprend des paramètres pour l’identifiant de campagne et l’identifiant du groupe publicitaire, qui sont nécessaires pour générer des rapports précis au niveau de la campagne et du groupe publicitaire pour les campagnes Google Drafts and Experiments dans Analytics. Si vos comptes Google existants contiennent des campagnes Google Drafts and Experiments, modifiez les paramètres de suivi de compte pour chaque compte spécifique afin de migrer vers le nouveau s_kwcid. Si vous ne disposez pas de campagne Google Drafts and Experiments, la migration vers le nouveau format est facultative. Remarque : tous les nouveaux comptes Google utilisent automatiquement le nouveau format. |
| Rechercher dans Advanced Campaign Management (ACM) | (Campagnes Google Ads) Vous pouvez à présent configurer des suffixes d’URL finales au niveau de la campagne pour des modèles de publicités textuelles et commerciales Google. |
|  | (Campagnes Google Ads) Les champs facultatifs « Titre 3 » et « Description 2 » sont disponibles pour les publicités textuelles étendues Google. |
| Rapports | Les mesures de partage d’impressions de Bing Ads suivantes, qui ont été interrompues avec la dernière API de Bing Ads, ne sont pas collectées après le 11 octobre : Search IS% Lost to Rank, Search IS% Lost to Bid (Bing), Search IS% Lost to Page Relevance (Bing), and Search IS% Lost to Keyword Relevance (Bing). Les mesures précédemment collectées restent disponibles pour la création de rapports. |
| Intégration d’Adobe Analytics | (Publicitaires avec Adobe Analytics uniquement) Dans Analysis Workspace, la dimension « Périphérique (AMO ID) », qui n’a jamais collecté de données, n’est plus disponible. Pour créer des rapports sur les données Analytics en ligne, utilisez la dimension « Type de périphérique mobile ». Pour générer des rapports sur les mesures de trafic de moteur de recherche (telles que les clics, le coût et les impressions) par type d’appareil, continuez à utiliser la création de rapports dans Advertising Cloud Search. |

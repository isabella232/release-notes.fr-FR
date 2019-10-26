---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: notes de mise à jour
last-update:  Novembre 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 2c6076aa0af7b9a273e31b1f8919e006ff48e6b4

---


# Accès anticipé - Notes de mise à jour d’Adobe Experience Cloud - novembre 2019

> [!IMPORTANT] Cette page contient une version anticipée du contenu et peut être modifiée avant la version définitive qui sera publiée.

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

> [!NOTE] Abonnez-vous à [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) pour être averti par e-mail de la publication des prochaines versions. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : 30 octobre 2019**

* [Interface d’Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (liens vers l’aide de la solution)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (liens vers l’aide de la solution)
* [!DNL Advertising Cloud](#adcloud)

## Interface d’Experience Cloud {#ecloud}

Notes de mise à jour de l’interface d’Experience Cloud et de l’administration des produits.

* La page Flux est obsolète en décembre 2019. Recherchez un avis de désapprobation interne au produit. (MCUI-10039)
* Mise à jour du lien [En savoir plus](https://www.adobe.com/marketing/campaign.html) pour Adobe Campaign à partir du sélecteur d’applications. (MCUI-10034)
* Stabilité et réactivité améliorées de la plateforme principale pour l’interface d’Experience Cloud. (MCUI-6822)
* Correction de vulnérabilités de sécurité dans l’interface utilisateur d’Experience Cloud. (MCUI-9942)
* Correction d’un problème critique dans les attributs du client qui bloquait la validation du schéma pour certains clients. (MCUI-10024, MCUI-6479)
* Amélioration de la bibliothèque d’audiences afin de supprimer les dimensions qui ne sont pas prises en charge pour la création d’audiences en temps réel. (MCUI-10046)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notes de mise à jour d’Experience Platform, d’Experience Platform Launch, d’Identity Service et des bulletins de sécurité.

* [Experience Platform Launch](#launch)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/security.html) (Tous les produits Adobe)

### Experience Platform Launch {#launch}

Pour consulter les notes de mise à jour et la documentation du produit, voir [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## [!DNL Analytics] {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)

Pour consulter la documentation du produit, voir [Accueil de l’aide Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- | 
| Analyse de parcours du client | Le 21 novembre 2019, Adobe mettra à disposition [Customer Journey Analytics](https://www.adobe.com/analytics/customer-journey-analytics.html) en tant que module complémentaire d’Adobe Analytics.<br><br/>Les analyses du parcours client vous permettent d’importer toutes les données de vos clients de n’importe quel canal. en ligne et hors ligne — dans Adobe Experience Platform, puis analysez ces données comme vous le feriez pour vos données numériques existantes à l’aide d’Analysis Workspace aujourd’hui. Les analyses de parcours client vous permettent de contrôler la manière dont vous connectez vos données en ligne et hors ligne dans Analysis Workspace sur n’importe quel ID client commun, ce qui vous permet enfin d’effectuer l’attribution, la segmentation, le flux, les abandons, etc. dans l’ensemble de vos données client dans Adobe Analytics.<br><br/>Les clients Analytics Select, Prime et Ultimate peuvent acheter ce produit complémentaire. Pour plus d’informations, contactez votre équipe de compte Adobe. |
| API Privacy Service : CCPA | Le California Consumer Privacy Act (CCPA) protège la vie privée et les consommateurs pour les personnes résidant en Californie, États-Unis. Ce document sera en vigueur à partir du 1er janvier 2020.<br><br/>Le CCPA offre aux Californiens de nouveaux droits sur leurs données personnelles, comme le droit d’y accéder et de les supprimer, mais aussi de savoir si leurs données sont vendues ou divulguées (et, le cas échéant, à qui) et de refuser la vente de leurs données.<br><br/>Afin de préparer l’arrivée du CCPA, le Privacy Service recevra les demandes de refus de vente de données personnelles.<br><br/>Le Privacy Service, nouveau nom du RGPD Service, conserve toutes ses fonctionnalités existantes et les adapte au CCPA.<br/><br/>[CCPA dans Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Présentation de Privacy Service](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Rapport de confidentialité : Analytics Admin Console | L’activation de la création de rapports de confidentialité pour Analytics ajoute un ensemble de variables réservées à une suite de rapports.  Ces variables sont conçues pour aider à la collecte de données de consentement des consommateurs au niveau de l’accès.<br><br/>Nouvelles dimensions :<br/><ul><li>Droit d’opposition de gestion du consentement</li><li>Accord préalable de gestion du consentement</li><li>[Variables de gestion du consentement](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| Audio et vidéo Analytics : prise en charge de la confidentialité | Deux nouvelles variables ont été ajoutées à l’API Media Collection :<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>Il s’agit de variables facultatives qui peuvent être utilisées pour enregistrer le statut du consentement du consommateur au moment de l’accès.<br/><br/>[Documentation de l’API Media Collection](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>Les nouvelles variables de données contextuelles de la gestion du consentement dans Analytics ont été ajoutées au formulaire Federated Analytics. Ces variables peuvent désormais être utilisées pour marquer le droit d’opposition du partage des données ou de la vente d’accès à celles-ci pour la fédération.<br/><br/>[Télécharger le formulaire Federated Analytics](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### Correctifs

* Correction d’un problème qui générait une erreur lors de la tentative de suppression des plages de dates détenues par "Utilisateur inconnu". (AN-185540)

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| EOL de l’option **[!UICONTROL Afficher l’archive]** | 30 octobre 2019 | Annonce de la date de fin de vie de janvier 2020 pour l’option **[!UICONTROL Afficher l’archive]** dans le Gestionnaire de tableaux de bord (**[!UICONTROL Composants &gt; Tableaux de bord]**). |
| EOL de l’option **[!UICONTROL Mettre en place les restrictions]** d’identification par IP | 30 octobre 2019 | Annonce de la date de fin de vie de janvier 2020 pour la fonctionnalité de liste blanche de connexion IP (**[!UICONTROL Mettre en place les restrictions]** de connexion IP) sous **[!UICONTROL Admin &gt; Paramètres de la société &gt; Sécurité]** . |
| Gestion mise à jour de l’attribut SameSite sur les cookies | 15 octobre 2019 | En août 2019, Adobe a annoncé l’ajout du paramètre de cookie Même site à tous les cookies définis par Analytics. Une mise à jour logique est appliquée lorsque :<ul><li>Tous les cookies tiers qui ne sont pas basés sur Webkit sont dotés de l’attribut MêmeSite défini sur `none`.</li><li>L’attribut MêmeSite n’est pas défini pour tous les autres cookies.</li></ul> |
| Fin de la prise en charge de TLS 1.1 | 3 octobre 2019 | D’ici le 31 mars 2020, Adobe Analytics supprimera la prise en charge de TLS 1.1. Ce changement s’inscrit dans le cadre des efforts que nous déployons pour respecter les meilleures normes de sécurité et promouvoir la sécurité des données de nos clients. |
| Fin du courtage par FTP entre San Jose et Londres, et entre San Jose et Singapour | Juillet 2020 | Pour les clients basés à Londres et à Singapour, nous ne prendrons plus en charge le courtage de données entre Londres ou Singapour et le centre de données de San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Pour Londres, utilisez [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Pour Singapour, utilisez [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Mise à jour des totaux de tableau à structure libre d’Analysis Workspace | 12 septembre 2019 | En octobre 2019, les lignes total du tableau à structure libre commenceront à tenir compte des [filtres de rapport](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) appliqués. À ce jour, les totaux ne prennent en compte que la segmentation. Grâce à cette modification, les visualisations dépendantes sont mises à jour (par exemple, visualisations [!UICONTROL Nombre de résumés]), ainsi que les données CSV et PDF exportées. |
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

Voir [Notes de mise à jour d’AppMeasurement pour JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Nouvelles fonctionnalités, améliorations et correctifs dans Audience Manager.

| Fonction | Description |
|--- |----|
| [Améliorations des règles de fusion de profils](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | Nous avons publié une série d’améliorations pour les règles [!UICONTROL de fusion de]profils : <ul><li>L’évaluation des segments est désormais prise en charge par lot pour 100 périphériques au maximum.</li><li>Nous avons amélioré la précision des rapports pour les populations de caractéristiques et de segments.</li><li>Nous avons amélioré la précision des fichiers de commandes générés à l’aide d’ID inter-périphériques.</li><li>Nous avons mis à jour la documentation avec des cas d’utilisation plus détaillés pour chaque règle. Voir Cas d’utilisation [généraux pour les règles](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html)de fusion de profils, les Cas [d’utilisation de graphiques de périphériques](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html)externes et les Cas [d’utilisation de graphiques de périphériques de lien de](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html)profil.</li></ul> |
| [Outils de gestion en masse](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | Nous avons publié une nouvelle version de la feuille de calcul de gestion en bloc qui fonctionne sur les systèmes d’exploitation MacOS et Microsoft Windows et prend en charge la connexion à Experience Cloud. |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | Nous avons ajouté la prise en charge de [!DNL HTTP Strict-Transport-Security], une stratégie de sécurité Web qui protège contre le détournement de cookies et les attaques de rétrogradation de protocole. |

**Correctifs et améliorations**

* Correction d’un bogue dans Audience Marketplace, en raison duquel l’interface utilisateur renvoyait l’erreur 409 lorsque les clients envoyaient l’utilisation mensuelle du segment. (AAM-50825)
* Nous avons corrigé un bogue dans les signaux dérivés, où pendant une courte période les clients étaient incapables de créer de nouveaux signaux dérivés. (AAM-50968)
* Correction d’un bogue dans Destinations basées sur les personnes, en raison duquel les clients ne pouvaient pas modifier le nom d’une destination. (AAM-51025)
* Correction d’un bogue en raison duquel certains utilisateurs avaient des comptes en double pour se connecter à l’interface utilisateur d’Audience Manager. En raison des autorisations associées aux comptes en double, ces utilisateurs n’ont pas pu accéder à certaines parties de l’interface utilisateur et effectuer des opérations. (AAM-50818)
* Nous avons continué à améliorer l’accessibilité de l’interface utilisateur d’Audience Manager. (AAM-48932, AAM-49043, AAM-49054, AAM-49371, AAM-49375)

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Versions de produit

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5 est une version de fonctionnalités qui vise à permettre aux utilisateurs du portail de marque (agences/équipes externes) de télécharger du contenu sur le portail de marque et de le publier sur AEM Assets, sans avoir à accéder à l’environnement de création. Cette fonctionnalité, appelée [Ressource des ressources dans le portail](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html)des marques, améliore les expériences des clients en fournissant un mécanisme bidirectionnel permettant aux utilisateurs de contribuer et de partager des ressources avec d’autres utilisateurs du portail des marques mondialement distribués.

   Reportez-vous à la page [Nouveautés du portail](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html)de marque AEM Assets.

   See [Release notes](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **Service de conversion automatisée AEM Forms**

   Le service de conversion automatisée des formulaires permet d’accélérer la numérisation et la modernisation des expériences de capture de données grâce à la conversion automatisée des formulaires PDF en formulaires adaptatifs. Ce service, proposé par Adobe Sensei, convertit automatiquement vos formulaires PDF en formulaires adaptatifs compatibles avec les périphériques, réactifs et basés sur HTML5. Tout en exploitant les investissements existants dans les formulaires PDF et XFA, le service applique également les validations, le style et la mise en page appropriés aux champs de formulaire adaptatif pendant la conversion.

   Voir Service [de conversion automatisée](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)Adobe Experience Manager Forms.

* **Cloud Manager 2019.10.0**

   Les Notes de mise à jour générales de Cloud Manager 2019.10.0 sont désormais disponibles. Les notes répertorient également les mises à jour des étapes de déploiement et de la gestion de la version du projet expert.

   Voir les notes [de mise à jour de](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)Cloud Manager 2019.10.0.

### Auto-assistance

* **Carte d’activités**

   En raison de modifications de sécurité dans l’API Adobe Analytics, il n’est plus possible d’utiliser la version de Carte d’activités incluse dans AEM. Voir [Configuration de la connexion à Adobe Analytics](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics).

   Vous devez maintenant utiliser le module [de navigateur de Carte d’](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) activités pour Chrome, Firefox ou Internet Explorer, comme fourni par Adobe Analytics.

* **Guide des meilleures pratiques pour les projets AEM Screens**

   Le nouveau Guide des _meilleures pratiques pour les écrans_ AEM fournit des informations détaillées et des conseils pratiques pour imaginer, concevoir et intégrer des expériences client intentionnelles dans votre implémentation de la signature numérique. Il vous guide également dans la manière de créer un impact positif sur votre entreprise à l’aide des meilleures pratiques, tout en déployant un projet de signalisation numérique dans AEM Screens.

   Reportez-vous au Guide des [meilleures pratiques pour les projets](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html)AEM Screens.

* **Gestion de l’expérience sans tête**

   Les fonctionnalités du Rendu de contenu [distant](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848) utilisé pour le rendu côté serveur des applications d’une seule page sont maintenant documentées.

* **SPA et rendu côté serveur**

   Vous pouvez étendre et personnaliser le service de rendu de contenu distant que vos applications SPA pilotées par AEM utilisent pour le rendu côté serveur afin de répondre à vos besoins.

   Voir [SPA et Rendu](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer)côté serveur.

* **Archétype du projet AEM**

   L’archétype de projet AEM crée un projet Adobe Experience Manager minimal basé sur les meilleures pratiques comme point de départ pour vos propres projets AEM. Les propriétés à fournir lors de l'utilisation de cet archétype vous permettent de spécifier les noms de toutes les parties de ce projet et de contrôler certaines fonctionnalités facultatives.

   Reportez-vous à la page Archétype [du projet](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html)AEM.

* **Mises à jour de la documentation AEM**

   Découvrez les modifications et mises à jour importantes apportées à la documentation d’Adobe Experience Manager au cours des trois derniers mois.

   Voir Documentation [AEM : Mises à jour](https://helpx.adobe.com/experience-manager/documentation-updates.html)récentes de la documentation.

### Ressources supplémentaires

* [Formation et assistance pour AEM 6.5 – Accueil](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Formation et assistance pour AEM 6.4 – Accueil](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Formation et assistance pour AEM 6.3 – Accueil](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Formation et assistance pour AEM 6.2 – Accueil](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notes de mise à jour de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Ressources de documentation

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/support/campaign/standard.html) – [Notes de mise à jour](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Calendrier des versions](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Tutoriels vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

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

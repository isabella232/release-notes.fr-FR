---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: notes de mise à jour
last-update: Août 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 3bd946a9ef7d6d6d2e17cec4385a2dd53a41df97

---


# Notes de mise à jour d’Adobe Experience Cloud

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!NOTE]
>
>Inscrivez-vous aux [Mises à jour produit prioritaires d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) afin de recevoir une notification par courrier électronique concernant les prochaines mises à jour. Vous recevrez une notification trois à cinq jours ouvrables avant la sortie de la mise à jour. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : 8 août 2019**

* [Experience Cloud et Platform Platform](#platform)
* [!DNL Analytics](#analytics) (**Mise à jour le 20 août 2019**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Ad Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (liens vers l'aide de la solution)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (liens vers l'aide de la solution)

## [!DNL Experience Cloud] et [!DNL Experience Platform] {#platform}

Notes de mise à jour relatives à [!UICONTROL Experience Platform], à l’interface d’Experience Cloud, à l’administration des produits, à Experience Platform Launch, au service d’identité et aux bulletins de sécurité.

* [Interface d’Experience Cloud](#core-services)
* [Experience Platform Launch](#launch)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/security.html) (Tous les produits Adobe)

### Interface d’Experience Cloud {#core-services}

* Correction d’un problème critique de connexion à Experience Cloud en raison duquel la session de certains utilisateurs était fermée. (MCUI-6908)
* Mise à jour de la connexion Experience Cloud afin d’améliorer les performances et de réduire la latence. (MCUI-6854, MCUI-6869, MCUI-6883)
* Mise à jour cosmétique de l’interface. (MCUI-6861, MCUI-6911, MCUI-6862)
* Correction d’un problème lié aux [!UICONTROL Triggers] d’Experience Cloud qui entraînait une interprétation incorrecte de la clause _Like_ dans la définition du [!UICONTROL déclencheur]. (MCUI-6611)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)  (**Mise à jour le 20 août 2019**)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- |  
| Prise en charge des paramètres de cookie SameSite | The [SameSite cookie setting](https://web.dev/samesite-cookies-explained) will be added to all cookies set by Analytics. Cette modification permet de se conformer aux modifications de Chrome, qui exigent le champ de cookie SameSite. Par défaut, les cookies Analytics seront définis sur `none`. Si vous avez utilisé exclusivement un domaine propriétaire (par ex. stats.domain.com), vous pouvez demander à l’assistance clientèle d’Adobe de le définir sur `lax` pour les domaines de collecte propriétaires. |
| Workspace : limite des éléments pour le filtre déroulant augmentée de 50 à 200 | La limite des éléments pouvant être placés dans un filtre déroulant a été augmentée de 50 à 200. Cette amélioration prend en charge divers cas d’utilisation, tels que l’ajout à un filtre de tous les pays (195) ou de tous les États et provinces (52). |
| Impressions d’activité et conversions d’activités A4T activées pour Attribution IQ | Nous avons activé deux mesures Analytics pour Target (A4T) pour Attribution IQ : Impressions d’activité et Conversions des activités. Auparavant, dans Analysis Workspace, ces mesures étaient gonflées par rapport aux rapports et analyses. Grâce à cette modification, les utilisateurs peuvent désormais appliquer un modèle d’attribution de « même touche » qui harmonise Analysis Workspace et Reports &amp; Analytics. |

#### Correctifs

* Correction d’un problème d’affichage du texte dans les rapports en temps réel en mode plein écran. (AN-183168)
* (**Mis à jour le 20 août 2019**) La collecte de données rejette désormais les URL de redirection qui contiennent des signes @ pour empêcher les attaquants de rediriger vers des sites malveillants par le biais de domaines placés sur liste blanche.
* (**Mis à jour le 20 août 2019**) La migration des visiteurs est maintenant désactivée pour tous les accès provenant des navigateurs qui ne prennent pas en charge l'attribut Samesite Cookie et si l'accès contient un cookie tiers.
* (**Mis à jour le 20 août 2019**) Correction d'un problème en raison duquel les premiers accès n'avaient pas été envoyés au cookie s_ vi pour un nouveau visiteur.

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Prise en charge des décalages de fuseau horaire historiques | 8 août 2019 | Analytics gère désormais automatiquement les décalages de fuseau horaire pour les accès horodatés. Après cette modification du 8 août, les systèmes qui chargent les données pour un traitement historique n’auront plus besoin d’ajuster les décalages de fuseau horaire avant d’envoyer les données. |
| Limites du créateur de règles de classification | Ajout le 5 juin 2019 | Ces limites ne sont pas nouvelles, mais ont été ajoutées à la documentation [ici](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nouvelles limites des opérateurs de segment | Ajout le 31 mai 2019 | À compter du 18 juillet 2019, les opérateurs de segment _contient n’importe lequel_, _ne contient pas n’importe lequel_, _contient tous les_ et _ne contient pas tous les_ seront limités à 100 mots par champ d’entrée. Après cette date, la limite sera appliquée à tous les segments nouveaux et modifiés. Les segments existants qui dépassent la limite continueront à être pris en charge, mais ne pourront pas être modifiés ou enregistrés tant que le champ d’entrée dépasse la limite. Ces limites sont appliquées dans le cadre d’efforts continus visant à améliorer les performances des requêtes. |
| Modifications à venir concernant la prise en charge des **[!UICONTROL classifications activées par date]** et des **[!UICONTROL classifications numériques 2]** | Mise à jour le 28 mai 2019 | La possibilité d’importer des classifications numériques 2 et des classifications activées par date a été supprimée du code base. Cette modification prendra effet lors de la version de maintenance de juillet 2019. S’il y a des colonnes numériques ou des colonnes activées par date dans le fichier d’importation, ces cellules seront ignorées et les autres données de ce fichier seront importées normalement. <br/>Les classifications existantes peuvent toujours être exportées par le biais du workflow de classification standard et sont toujours disponibles dans les rapports. |
| Modification à venir des calculs des _totaux des rapports_ | Mise à jour le 9 juillet 2019 | Le **18 juin 2019**, Adobe Analytics va uniformiser les calculs des _totaux des rapports_ pour toutes les dimensions et mesures. Pour cette raison, les totaux de certains rapports seront modifiés (notamment les rapports Props ou Attributs du client). Avant cette modification, certains totaux incluaient ou excluaient la ligne _Non spécifié_ dans le total, peu importe si elle apparaissait ou _non_ dans le rapport. <br/>À compter du 18 juin 2019, le poste _Non spécifié_ apparaîtra toujours dans le total du rapport, même s’il n’apparaît pas comme poste sur le rapport. En outre, les segments qui utilisent la logique _existe_ ou _n’existe pas_ peuvent afficher des résultats différents pour certaines dimensions après cette modification, en particulier les dimensions dont _Non spécifié_ possède un nom spécial, comme l’élément de ligne « Tapé/Marqué » pour la dimension Type de référent ou l’élément de ligne « Autre » pour la dimension Type de périphérique. Cette modification concernera Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder et l’API Reporting. |
| Mise à jour des téléchargements CSV depuis [!DNL Analysis Workspace] | 10 avril 2019 | À partir du 11 avril 2019, plusieurs modifications seront apportées aux **[!UICONTROL téléchargements CSV]** (et **[!UICONTORL copies dans le Presse-papiers]**) depuis [!DNL Analysis Workspace] pour supprimer la mise en forme des données exportée.  <ul><li>Le séparateur des milliers ne sera plus inclu. Le séparateur décimal sera toujours inclus et se conformera au format défini sous **[!UICONTROL Composants &gt; Paramètres de rapport &gt; Séparateur des milliers]**. Remarque : Les valeurs numériques qui utilisent une virgule comme séparateur décimal continuent à être placées entre guillemets dans le fichier CSV exporté.</li><li>Aucun symbole de devise ne sera affiché.</li><li>Aucun symbole de pourcentage ne sera affiché. Les pourcentages seront sous forme décimale. Par exemple, 75 % sera représenté comme 0,75.</li><li>La durée sera indiquée en secondes.</li><li>Les tableaux de cohortes affichent uniquement les valeurs brutes. Les pourcentages sont supprimés.</li><li>Si un nombre n’est pas valide, une cellule vide s’affichera.</li></ul> |
| Modification à venir de la commande du débogueur [!DNL Analysis Workspace] | 4 avril 2019 | La commande de la console permettant d’activer le débogueur [!DNL Analysis Workspace] sera remplacée par adobeTools.debug.includeOberonXml le **13 juin 2019**. adobe.tools.debug.includeOberonXml cessera de fonctionner après cette date. |
| Numéros de version des navigateurs mobiles | 7 février 2019 | Le niveau de troncation des numéros de version des navigateurs mobiles est modifié depuis le 8 janvier 2019 (de 2 à 1). Depuis lors, seuls les deux premiers niveaux des versions sont affichés (par ex. _Firefox 64.0.2_ apparaît désormais sous la forme _Firefox 64.0_). |
| Fin de vie d’[!DNL Ad Hoc Analysis] | 29 janvier 2019 | Le 6 août 2018, Adobe a annoncé la prochaine fin de vie d’[!DNL Ad Hoc Analysis]. dont la date sera communiquée dès que possible.<br/>Pour plus d’informations, notamment sur les versions de Java compatibles durant cette période, voir [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Liens d’[!DNL Analytics] rapports courts | 14 janvier 2019 | Tout lien d’[!DNL Analytics] rapport court qui n’aura pas été consulté pendant un an sera nettoyé et supprimé à compter du jeudi 17 janvier 2019, selon un calendrier progressif. |
| Fin de la prise en charge de TLS 1.0 | Mis à jour le 10 janvier 2019 | À compter du 11 février 2019, la création de rapports Adobe Analytics ne prendra plus en charge le chiffrement TLS 1.0 (Transport Layer Security – Sécurité de la couche de transport). Ce changement entre dans le cadre de nos efforts continus pour conserver des normes de sécurité élevées et promouvoir la sécurité des données des clients. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> À compter du 20 février 2019, la collecte de données Adobe Analytics ne prendra plus en charge le protocole TLS 1.0. À la suite de cette modification, Adobe ne collectera plus les [!DNL Analytics] données des utilisateurs finaux disposant d’appareils ou de navigateurs web plus anciens qui ne prennent pas en charge le protocole TLS 1.1 ou version ultérieure. Cette modification ne devrait pas avoir de répercussions importantes sur les données des clients ou le compte rendu des performances. (Si votre site Internet ne prend pas en charge TLS 1.0, vous ne serez pas concerné.) <br/>À compter du 11 avril 2019, l’API de création de rapports d’Adobe Analytics ne prendra plus en charge le chiffrement TLS 1.0. Les clients qui accèdent à l’API doivent vérifier qu’ils ne seront pas affectés. <ul><li>Les clients API utilisant Java 7 avec les paramètres par défaut devront être [modifiés pour prendre en charge TLS 1.2 ](https://www.java.com/en/configure_crypto.html). (Reportez-vous à la section _Modification de la version par défaut du protocole TLS pour les points de terminaison clients : TLS 1.0 à TLS 1.2_.) </li><li>Les clients API utilisant Java 8 ne devraient pas être affectés, étant donné que TLS 1.2 est la configuration par défaut.</li><li> Les clients API utilisant d’autres structures devront contacter leurs fournisseurs pour plus de détails sur la prise en charge de TLS 1.2.</li></ul> |
| Flux de données : colonne post_product_list – modification de taille | 9 janvier 2019 | Le 7 février 2019, Adobe prévoit d’étendre la taille de la colonne post_product_list de 64 Ko à 16 Mo. Cette modification garantit que les valeurs eVar de marchandisage ajoutées à la colonne post_product_list lors du traitement ne causent pas de troncature de valeurs de produits et de revenus. Si certains de vos processus assimilent des valeurs post_product_list, assurez-vous qu’ils peuvent gérer des valeurs allant jusqu’à 16 Mo en longueur ou entraîneront une troncature des valeurs à 16 Ko afin d’éviter les problèmes d’assimilation de données. |
| Modifications de gestion concernant les points de terminaison inactifs [!DNL Analytics Live Stream] | 20 décembre 2018 | À compter du 1er février 2019, les points de terminaison [!DNL Live Stream] n’ayant reçu aucune connexion d’utilisateurs actifs durant 90 jours pourront être désactivés. Vous pouvez contacter l’assistance clientèle pour obtenir des renseignements au sujet de vos points de terminaison [!DNL Live Stream] et, si besoin, demander leur réactivation. De plus, veuillez vous assurer que vos processus client maintiennent une connexion permanente, comme prévu par la configuration du service, et qu’ils sont mis en œuvre pour se reconnecter lorsque la connexion est désactivée ou interrompue. |
| Mise à jour d’Adobe [!DNL Report Builder] en raison de la fin de la prise en charge du protocole TLS 1.0 | 7 septembre 2018 | En raison de la fin de la prise en charge du protocole TLS 1.0, nous avons recommandé aux utilisateurs de [!DNL Report Builder] de télécharger la version v5.6.21 avant février 2019. À compter de cette date, les versions antérieures de [!DNL Report Builder] ne fonctionneront plus. |

### AppMeasurement {#appm}

Version 2.16.0 d’[!UICONTROL Appmeasurement] publiée le 8 août 2019.

| Fonction | Description |
| -----------| ---------- |
| Prise en charge `sendBeacon` des liens de sortie | Mise en œuvre de la prise en charge `sendBeacon` des liens de sortie dans [!UICONTROL AppMeasurement]. Cela permettra d’améliorer le suivi des liens de sortie et entraînera probablement par une augmentation du trafic. |
| Valeurs ECID/fid | Les valeurs ECID/fid sont maintenant mises en cache au premier accès, même si les paramètres OptIn changent. |
| DIL 9.3 | Mise à jour du module Gestion de l’audience vers DIL 9.3 |
| Suivi de la portée de défilement | Bouton exposé dans s.ActivityMap.trackScrollReach permettant d’activer ou de désactiver le suivi de la portée de défilement. |
| Service d’identification des visiteurs 4.4.0 | Mise à niveau d’AppMeasurement pour utiliser le service d’identification des visiteurs 4.4.0. |

#### Correctifs

* Correction d’un bogue de la file d’attente d’AppMeasurement qui survenait avant que la valeur isReadyToTrack ne soit vraie.

Voir [Historique des versions d’AppMeasurement](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html) pour consulter un historique des versions d’AppMeasurement sur les plates-formes suivantes :

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone, XBOX, Silverlight et .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

## Audience Manager {#aam}

**Correctifs et améliorations**

* L’onglet Administration s’affiche désormais uniquement pour les comptes d’utilisateurs disposant de droits d’administrateur (AAM-48557).
* L’API List Users renvoie désormais tous les détails de l’utilisateur (AAM-48662).
* Vous pouvez désormais redimensionner la liste des dossiers de caractéristiques (AAM-48800).
* Diverses optimisations de l’accessibilité de l’interface utilisateur (AAM-48865, AAM-48933).
* Chargement des optimisations pour les pages Administration et Sources de données (AAM-48514).

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Fin de vie du produit

Fin de vie de Digital Publishing Suite Classic (DPSC) le 31 août 2019. Pour plus d'informations, consultez la FAQ de fin de vie classique [de Digital Publishing Suite](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html).

### Ressources supplémentaires

* [Formation et assistance pour AEM 6.5 – Accueil](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Page d’accueil Formation et assistance AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Page d’accueil Formation et assistance AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Page d’accueil Formation et assistance AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Notes de mise à jour de Scene7 Publishing System](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notes de mise à jour de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Adobe Campaign Standard

[Version de Campaign Standard 19.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| Fonction | Description |
| -----------| ---------- |  
| Activité des API externes (version bêta publique) | Pour une personnalisation plus poussée, l’activité des API externes permet d’importer des données provenant de systèmes externes dans un flux de travail via un appel d’API REST. Les points de terminaison REST peuvent correspondre à un système de gestion client, une exécution Adobe I/O ou un point de terminaison REST Adobe Experience Cloud (par exemple, Data Platform, Target, Analytics, Campaign). Cette fonctionnalité est actuellement en version bêta publique. Pour plus d'informations, consultez la documentation [détaillée](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) [et la vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html). |
| Rapport sur le segment de processus | Cette fonctionnalité permet aux spécialistes du marketing de ventiler leurs performances de diffusion par code de segment. Lorsque vous créez un processus et que vous utilisez une activité de segmentation pour affecter des segments à la population de diffusion, ces segments peuvent maintenant accéder à la même diffusion. Cela permet d’afficher les statistiques d’ouverture/clic basées sur plusieurs segments au sein d’une seule diffusion. Pour plus d'informations, consultez la documentation [détaillée](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) [et la vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html). |

### Adobe Campaign Classic

[Mise à jour de Campaign Classic 19.1.3](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - version 9031

### Panneau de configuration d’Adobe Campaign

[Les nouvelles fonctionnalités du Panneau de configuration](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) incluent la possibilité d'ajouter des URL que Campaign Classic se connecte pour les transferts de données/de fichiers.

Notez que le [!UICONTROL panneau de configuration] est disponible pour les clients Adobe Campaign Classic et Adobe Campaign Standard hébergés sur AWS. Aucune mise à niveau n’est requise pour accéder au panneau de configuration.

### Ressources supplémentaires

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

Mise à jour : 9 août 2019, disponible le 10 août

* (Annonceurs disposant du service de suivi de conversion Advertising Cloud) Grâce au module Intelligent Tracking Prevention (ITP) 2.2 d’Apple, qui a été mis à disposition en mai, les cookies de suivi de conversion Advertising Cloud sont automatiquement supprimés des navigateurs Apple Safari après 24 heures. Néanmoins, Advertising Cloud dispose d’une nouvelle solution ITP qui vous permet de suivre les conversions qui se produisent dans Safari pendant plus de 24 heures après le clic d’origine. La solution utilise le stockage local et la technologie iframe. Contactez votre gestionnaire de compte de recherche Advertising Cloud pour obtenir des instructions de mise en œuvre.
* Dans Recherche &gt; Avancé (ACM), vous pouvez à présent configurer des suffixes d’URL finales au niveau de la campagne pour des modèles de publicités textuelles et commerciales Google.
* Les annonceurs disposant de comptes Google Ads qui peuvent bénéficier du ciblage de clients peuvent à présent effectuer les opérations suivantes :
   * Créer une audience par ciblage de clients Google Ads à l’aide d’identifiants utilisateur provenant d’un segment d’audience Adobe. Pour afficher cette fonctionnalité, le compte de l’annonceur doit être configuré de manière à l’autoriser.
   * Créer une audience par ciblage de clients Google Ads en téléchargeant un fichier de données client. Le fichier peut contenir des coordonnées (adresses électroniques, adresses postales ou numéros de téléphone), des identifiants utilisateur ou des identifiants d’appareil mobile. Certains types de coordonnées doivent être hachés à l’aide de l’algorithme SHA-256.
   * Mettez à jour toute audience par ciblage de clients Google, à l’exception des audiences créées à partir d’une audience Adobe. Vous pouvez télécharger des données afin d’ajouter, de supprimer ou de remplacer toutes les données existantes pour l’audience. Toutes les coordonnées doivent être hachées à l’aide de l’algorithme SHA-256.
* Les vues Audiences &gt; Cibles et audiences &gt; Exclusions contiennent une colonne « Type ».

---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: notes de mise à jour
last-update: Août 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 09b88aee612dfb84e3810d1f75da703d3d4c233d

---


# Accès anticipé - Notes de mise à jour d’Adobe Experience Cloud

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!IMPORTANT]
>
>Cette page contient une version anticipée du contenu et peut être modifiée avant la version définitive qui sera publiée.

>[!NOTE]
>
>Inscrivez-vous aux [Mises à jour produit prioritaires d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) afin de recevoir une notification par courrier électronique concernant les prochaines mises à jour. Vous recevrez une notification trois à cinq jours ouvrables avant la sortie de la mise à jour. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : août 2019**

* [Plateforme et administration d'expérience](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (liens vers l'aide de la solution)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (liens vers l'aide de la solution)

## [!UICONTROL Plateforme] et administration d'expérience {#platform}

Notes de mise à jour de [!UICONTROL l'interface Experience Platform], Experience Cloud, administration des produits, lancement de plateforme d'expérience, service d'identité et bulletins de sécurité.

* [Interface d’Experience Cloud](#core-services)
* [Experience Platform Launch](#launch)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/security.html) (Tous les produits Adobe)

### Interface d’Experience Cloud {#core-services}

* Correction d'un problème critique de connexion à Experience Cloud qui entraînait la déconnexion de la session pour certains utilisateurs. (MCUI-6908)
* Mise à jour de la connexion Experience Cloud afin d'améliorer les performances et de réduire la latence. (MCUI -6854, MCUI -6869, MCUI -6883)
* Mise à jour cosmétique de l'interface. (MCUI -6861, MCUI -6911, MCUI -6862)
* Correction d'un problème lié [!UICONTROL aux déclencheurs] Experience Cloud qui entraînait une interprétation incorrecte de _la clause J'aime_ dans la définition [!UICONTROL Trigger] . (MCUI-6611)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d'Adobe Analytics](#aa-features)
* [Avis importants pour les administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- |  
| Prise en charge des paramètres de cookie samesite | Le paramètre de cookie [samesite sera](https://web.dev/samesite-cookies-explained) ajouté à tous les jeux de cookies définis par Analytics. Cette modification vous permet d'être conforme aux modifications chromatiques nécessitant le champ de cookie samesite. Les cookies Analytics seront par défaut activés `none`. Si vous avez utilisé exclusivement un domaine propriétaire (par ex. stats.domain.com), vous pouvez demander à Adobe clientcare de le définir `lax` pour les domaines de collecte propriétaire. |
| Espace de travail : Augmentation de la limite d'élément pour le filtre déroulant de 50 à 200 | Nous avons augmenté la limite des éléments pouvant être placés dans un filtre déroulant de 50 à 200. Cette amélioration prend en charge divers cas d'utilisation, tels que l'ajout de tous les pays (195) à un filtre, ou de tous les États et provinces (52). |
| Attribution IQ activée pour les mesures A 4 T | Nous avons activé deux mesures Analytics pour Target (A 4 T) pour l'IQ Attribution : Impressions d'activité et Conversion des activités. Dans Analysis Workspace, ces mesures ont été gonflées par rapport aux rapports et analyses. Grâce à cette modification, les utilisateurs peuvent désormais appliquer un modèle d'attribution « Même touche », ce qui met l'Espace de travail d'analyse en ligne avec les rapports et analyses. |

#### Correctifs

* Correction d'un problème d'affichage du texte dans les rapports en temps réel en mode plein écran. (AN-183168)

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Limites du créateur de règles de classification | Ajout le 5 juin 2019 | Ces limites ne sont pas nouvelles, mais ont été ajoutées à la documentation [ici](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nouvelles limites des opérateurs de segment | Ajout le 31 mai 2019 | Starting July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. Après cette date, la limite sera appliquée à tous les segments nouveaux et modifiés. Les segments existants qui dépassent la limite continueront à être pris en charge, mais ne pourront pas être modifiés ou enregistrés tant que le champ d’entrée dépasse la limite. Ces limites sont appliquées dans le cadre d’efforts continus visant à améliorer les performances des requêtes. |
| Modifications à venir concernant la prise en charge des **[!UICONTROL classifications activées par date]** et des **[!UICONTROL classifications numériques 2]** | Mise à jour le 28 mai 2019 | La possibilité d’importer des classifications numériques 2 et des classifications activées par date a été supprimée du code base. Cette modification prendra effet lors de la version de maintenance de juillet 2019. S’il y a des colonnes numériques ou des colonnes activées par date dans le fichier d’importation, ces cellules seront ignorées et les autres données de ce fichier seront importées normalement. <br/>Les classifications existantes peuvent toujours être exportées par le biais du workflow de classification standard et sont toujours disponibles dans les rapports. |
| Modification à venir des calculs des _totaux des rapports_ | Mise à jour le 9 juillet 2019 | Le **18 juin 2019**, Adobe Analytics va uniformiser les calculs des _totaux des rapports_ pour toutes les dimensions et mesures. Pour cette raison, les totaux de certains rapports seront modifiés (notamment les rapports Props ou Attributs du client). Avant cette modification, certains totaux incluaient ou excluaient la ligne _Non spécifié_ dans le total, peu importe si elle apparaissait ou non __ dans le rapport. <br/>À compter du 18 juin 2019, le poste _Non spécifié_ apparaîtra toujours dans le total du rapport, même s’il n’apparaît pas comme poste sur le rapport. En outre, les segments qui utilisent la logique _existe_ ou _n’existe pas_ peuvent afficher des résultats différents pour certaines dimensions après cette modification, en particulier les dimensions dont _Non spécifié_ possède un nom spécial, comme l’élément de ligne « Tapé/Marqué » pour la dimension Type de référent ou l’élément de ligne « Autre » pour la dimension Type de périphérique. Cette modification concernera Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder et l’API Reporting. |
| Mise à jour des téléchargements CSV depuis [!DNL Analysis Workspace] | 10 avril 2019 | À partir du 11 avril 2019, plusieurs modifications seront apportées aux **[!UICONTROL téléchargements CSV]** (et **[!UICONTORL copies dans le Presse-papiers]**) depuis [!DNL Analysis Workspace] pour supprimer la mise en forme des données exportée.  <ul><li>Le séparateur des milliers ne sera plus inclu. Le séparateur décimal sera toujours inclus et se conformera au format défini sous **[!UICONTROL Composants &gt; Paramètres de rapport &gt; Séparateur des milliers]**. Remarque : Les valeurs numériques qui utilisent une virgule comme séparateur décimal continuent à être placées entre guillemets dans le fichier CSV exporté.</li><li>Aucun symbole de devise ne sera affiché.</li><li>Aucun symbole de pourcentage ne sera affiché. Les pourcentages seront sous forme décimale. Par exemple, 75 % sera représenté comme 0,75.</li><li>La durée sera indiquée en secondes.</li><li>Les tableaux de cohortes affichent uniquement les valeurs brutes. Les pourcentages sont supprimés.</li><li>Si un nombre n’est pas valide, une cellule vide s’affichera.</li></ul> |
| Modification à venir de la commande du débogueur[!DNL Analysis Workspace] | 4 avril 2019 | La commande de la console permettant d’activer le débogueur [!DNL Analysis Workspace] sera remplacée par adobeTools.debug.includeOberonXml le **13 juin 2019**. adobe.tools.debug.includeOberonXml cessera de fonctionner après cette date. |
| Numéros de version des navigateurs mobiles | 7 février 2019 | Le niveau de troncation des numéros de version des navigateurs mobiles est modifié depuis le 8 janvier 2019 (de 2 à 1). Depuis lors, seuls les deux premiers niveaux des versions sont affichés (par ex. _Firefox 64.0.2_ apparaît désormais sous la forme _Firefox 64.0_). |
| Fin de vie d’ [!DNL Ad Hoc Analysis] | 29 janvier 2019 | Le 6 août 2018, Adobe a annoncé la prochaine fin de vie d’[!DNL Ad Hoc Analysis]. dont la date sera communiquée dès que possible.<br/>Pour plus d’informations, notamment sur les versions de Java compatibles durant cette période, voir [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Liens de [!DNL Analytics] rapports courts | 14 janvier 2019 | Tout lien de [!DNL Analytics] rapport court qui n’aura pas été consulté pendant un an sera nettoyé et supprimé à compter du jeudi 17 janvier 2019, selon un calendrier progressif. |
| Fin de la prise en charge de TLS 1.0 | Mis à jour le 10 janvier 2019 | À compter du 11 février 2019, la création de rapports Adobe Analytics ne prendra plus en charge le chiffrement TLS 1.0 (Transport Layer Security – Sécurité de la couche de transport). Ce changement entre dans le cadre de nos efforts continus pour conserver des normes de sécurité élevées et promouvoir la sécurité des données des clients. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> À compter du 20 février 2019, la collecte de données Adobe Analytics ne prendra plus en charge le protocole TLS 1.0. À la suite de cette modification, Adobe ne collectera plus les [!DNL Analytics] données des utilisateurs finaux disposant d’appareils ou de navigateurs web plus anciens qui ne prennent pas en charge le protocole TLS 1.1 ou version ultérieure. Cette modification ne devrait pas avoir de répercussions importantes sur les données des clients ou le compte rendu des performances. (Si votre site Internet ne prend pas en charge TLS 1.0, vous ne serez pas concerné.) <br/>À compter du 11 avril 2019, l’API de création de rapports d’Adobe Analytics ne prendra plus en charge le chiffrement TLS 1.0. Les clients qui accèdent à l’API doivent vérifier qu’ils ne seront pas affectés. <ul><li>Les clients API utilisant Java 7 avec les paramètres par défaut devront être [modifiés pour prendre en charge TLS 1.2 ](https://www.java.com/en/configure_crypto.html). (Reportez-vous à la section _Modification de la version par défaut du protocole TLS pour les points de terminaison clients : TLS 1.0 à TLS 1.2_.) </li><li>Les clients API utilisant Java 8 ne devraient pas être affectés, étant donné que TLS 1.2 est la configuration par défaut.</li><li> Les clients API utilisant d’autres structures devront contacter leurs fournisseurs pour plus de détails sur la prise en charge de TLS 1.2.</li></ul> |
| Flux de données : colonne post_product_list – modification de taille | 9 janvier 2019 | Le 7 février 2019, Adobe prévoit d’étendre la taille de la colonne post_product_list de 64 Ko à 16 Mo. Cette modification garantit que les valeurs eVar de marchandisage ajoutées à la colonne post_product_list lors du traitement ne causent pas de troncature de valeurs de produits et de revenus. Si certains de vos processus assimilent des valeurs post_product_list, assurez-vous qu’ils peuvent gérer des valeurs allant jusqu’à 16 Mo en longueur ou entraîneront une troncature des valeurs à 16 Ko afin d’éviter les problèmes d’assimilation de données. |
| Modifications de gestion concernant les points de terminaison inactifs[!DNL Analytics Live Stream] | 20 décembre 2018 | À compter du 1er février 2019, les points de terminaison [!DNL Live Stream] n’ayant reçu aucune connexion d’utilisateurs actifs durant 90 jours pourront être désactivés. Vous pouvez contacter l’assistance clientèle pour obtenir des renseignements au sujet de vos points de terminaison [!DNL Live Stream] et, si besoin, demander leur réactivation. De plus, veuillez vous assurer que vos processus client maintiennent une connexion permanente, comme prévu par la configuration du service, et qu’ils sont mis en œuvre pour se reconnecter lorsque la connexion est désactivée ou interrompue. |
| Mise à jour d’Adobe [!DNL Report Builder] en raison de la fin de la prise en charge du protocole TLS 1.0 | 7 septembre 2018 | En raison de la fin de la prise en charge du protocole TLS 1.0, nous avons recommandé aux utilisateurs d’[!DNL Report Builder] de télécharger la version v5.6.21 avant février 2019. À compter de cette date, les versions antérieures d’[!DNL Report Builder] ne fonctionneront plus. |

### AppMeasurement {#appm}

[!UICONTROL Appmeasurement] 2.16.0 est sorti le 8 août 2019.

| Fonction | Description |
| -----------| ---------- |
| `sendBeacon` prise en charge des liens de sortie | Mise en œuvre `sendBeacon` de la prise en charge dans [!UICONTROL appmeasurement] pour les liens de sortie. Cela permettra d'améliorer le suivi des liens de sortie et entraînera probablement une augmentation du trafic. |
| ECID/valeurs fid | Les valeurs ECID/fid sont maintenant mises en cache sur le premier accès, même si les paramètres optin changent. |
| DIL 9.3 | Mise à jour du module Gestion de l'audience vers DIL 9.3 |
| Suivi de la portée de défilement | Bouton exposé dans s. activitymap. trackscrollportée pour activer ou désactiver le suivi de la portée de défilement. |
| Service d'identification des visiteurs 4.4.0 | Mise à niveau d'appmeasurement pour utiliser le service d'identification des visiteurs 4.4.0. |

#### Correctifs

* Correction d'un bogue de la file d'attente appmeasurement qui survenait avant la valeur de isreadytotrack.

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

## Audience Manager {#aam}

**Correctifs et améliorations**

* L'onglet Administration ne s'affiche désormais que pour les comptes utilisateur disposant de droits d'administrateur (AAM -48557).
* L'API Utilisateurs de liste renvoie désormais les détails complets de l'utilisateur (AAM -48662).
* Vous pouvez désormais redimensionner la liste des dossiers de caractéristiques (AAM -48800).
* Optimisations de l'accessibilité de l'interface utilisateur (AAM -48865, AAM -48933).
* Chargement des optimisations pour les pages Administration et Sources de données (AAM -48514).

## [!DNL Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Adobe Campaign Standard 

[Version de Campaign Standard 19.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| Fonction | Description |
| -----------| ---------- |  
| Activité API externe (version bêta publique) | Pour une personnalisation plus poussée, l'activité API externe vous permet d'importer des données provenant de systèmes externes dans un flux de travail via un appel API REST. Les points de fin REST peuvent être un système de gestion client, un endpoint de fin Adobe I/S Runtime ou un endpoint de fin REST Adobe Experience Cloud (par exemple, Platform Platform, Target, Analytics, Campaign). Cette fonctionnalité est actuellement en version bêta publique. Pour plus d'informations, consultez la documentation [détaillée](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) [et la vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html). |
| Rapport sur le segment de processus | Cette fonctionnalité permet aux spécialistes du marketing de ventiler leurs performances de diffusion par code de segment. Lorsque vous créez un flux de travail et que vous utilisez une activité de segmentation pour affecter des segments à la population de diffusion, ces segments peuvent maintenant accéder à la même diffusion. Cela vous permet d'afficher les statistiques d'ouverture/clic basées sur plusieurs segments au sein d'une seule diffusion. Pour plus d'informations, consultez la documentation [détaillée](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) [et la vidéo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html). |

###  Adobe Campaign Classic 

[Mise à jour de Campaign Classic 19.1.3](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - version 9031

### Panneau de configuration Adobe Campaign

[Les nouvelles fonctionnalités du Panneau de configuration](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) incluent la possibilité d'ajouter des URL que Campaign Classic se connecte pour les transferts de données/de fichiers.

Notez que le Panneau [!UICONTROL de configuration] est disponible pour les clients Adobe Campaign Classic et Adobe Campaign Standard hébergés sur AWS. Aucune mise à niveau n'est requise pour accéder au Panneau de configuration.

### Ressources supplémentaires

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Notes de mise à jour de juillet 2019
doc-type: notes de mise à jour
last-update: Juillet 2019
author: mfrei
translation-type: tm+mt
source-git-commit: e8470127c1cd343637d61bc0ac6bdd26339a8e2c

---


# Accès anticipé - Notes de mise à jour d’Adobe Experience Cloud

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!IMPORTANT]
>
>Cette page comporte du contenu publié avant la date de publication et peut faire l’objet de modifications avant la publication planifiée.

>[!NOTE]
>
>Inscrivez-vous aux [Mises à jour produit prioritaires d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) afin de recevoir une notification par courrier électronique concernant les prochaines mises à jour. Vous recevrez une notification trois à cinq jours ouvrables avant la sortie de la mise à jour. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : 18 juillet 2019**

* [Services principaux d’Experience Cloud et administration](#experiencecloud)
* [!DNL Analytics](#analytics)**(Mis à jour le 15 juillet)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## Core services and administration {#experiencecloud}

Notes de mise à jour de l’interface d’Experience Cloud, notamment les services principaux de [!UICONTROL Platform] et l’administration des produits.

* [Service Experience Cloud ID](#ecid)
* [Mobile Services et SDK Mobile](#mobile)
* [Experience Platform Launch](#launch)
* [Bulletins et avis de sécurité](#security)

### Service Experience Cloud ID {#ecid}

**Correctifs et mises à jour**

* `cookieDomain` config update : La bibliothèque attribue automatiquement un domaine de cookie de niveau supérieur lorsque `cookieDomain` dans `initConfig` n'est pas défini. (CORE-29223)
* Fixed an issue for `getVisitorValue` in `localVisitor`. (CORE-31287)
* Fixed an inconsistency of `MCOPTOUT` value in parent visitor versus iframe child visitor from `getVisitorValue` method. (CORE-29719)
* Correction d'un problème de vulnérabilité dans jquery 3.2.1. (CORE-31183)
* Opt-in update: added `optIn.off` to unsubscribe from events.
* Fixed an issue related to `setTimeout` function. (CORE-30623)

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services et SDK Mobile{#mobile}

Ios et Android ont été mis à jour de la manière suivante :

**iOS**

* Adobe Target: All requests now include the client and the `sessionId` in the URL query parameters.
* Adobe Target : Correction d'une fuite de mémoire.
* Visitor ID Service: The `visitorAppendToURL` and `visitorGetUrlVariablesAsync` APIs no longer double-encode their return values. Le double codage provoquait le marquage des valeurs renvoyées par ces API par certaines révisions de sécurité.

**Android**

* Target : Toutes les requêtes incluent désormais le client et le paramètre sessionid dans les paramètres de requête d'URL.
* Messagerie in-app : Correction d'un problème en raison duquel les applications Android étaient bloquées lorsqu'un message était déclenché avec une URL de clic vide.
* Visitor ID Service: The `Visitor.appendToURL` and `Visitor.getUrlVariablesAsync` APIs no longer double-encode their return values. Le double codage provoquait le marquage des valeurs renvoyées par ces API par certaines révisions de sécurité.

Pour consulter la documentation du produit, voir [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html).

Pour en savoir plus sur les SDK  Mobile, voir [SDK Android 4.x pour solutions Experience Cloud](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) et [SDK iOS 4.x pour solutions Experience Cloud](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Security bulletins and advisories {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Nouvelles fonctionnalités et correctifs d'Adobe Analytics](#aa-features) **(Mis à jour le 15 juillet)**
* [Avis importants pour les administrateurs d’Analytics](#aa-notices)

### Nouveautés de la version [!DNL Analytics] {#aa-features}

Pour obtenir la documentation du produit, voir la [page d’accueil de l’aide d’Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

| Composant | Description |
| -----------| ---------- |   
| Analysis Workspace - Améliorations de l'analyse des cohortes | New [Cohort Analysis settings](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/cohort-table/t-cohort.html) have been added: <ul><li>Afficher uniquement le pourcentage</li><li>Arrondi arrondi au entier le plus proche</li><li>Afficher une ligne de pourcentage moyenne</li></ul> |
| Analysis Workspace | In the left rail, users now have the option to _Show items from last 18 months_. Auparavant, la période de recherche était de 6 mois au maximum. Cela facilite la comparaison des pages ou des campagnes à partir de l'année dernière, jusqu'à 18 mois auparavant. |
| Nouveau modèle Analysis Workspace | We added a new template called ["Magento: Marketing &amp; Commerce"](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html) to Analysis Workspace. Il est spécialement conçu pour les clients de commerce électronique Magento, mais tout détaillant peut l'utiliser pour obtenir des informations uniques sur ses activités commerciales. |

#### [!DNL Analysis Workspace] correctifs

* Correction d'un problème en raison duquel les caractères multi-octets s'affichaient à l'envers - vers le bas lors de la ventilation des dimensions. (AN-180112)
* Correction d'un problème lié aux erreurs de visualisation : nous affichons maintenant une barre d'erreur rouge lorsqu'une erreur de visualisation se produisait.(AN-175542)
* Correction d'un problème en raison duquel les noms de dimension s'affichaient comme anglais dans les environnements localisés.(AN-178695)

#### [!DNL Analytics] correctifs

* Correction d'un problème en raison duquel le graphique linéaire dans un rapport d'analyse en temps réel était vide. (AN-181690)
* Correction d'un problème en raison duquel certaines portions de l'historique des flux de données n'étaient pas affichées dans l'interface utilisateur de la Console d'administration. (AN-176219)

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Limites du créateur de règles de classification | Ajout le 5 juin 2019 | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Nouvelles limites des opérateurs de segment | Ajout le 31 mai 2019 | À compter du 18 juillet 2019, les opérateurs de segment « contient n’importe lequel », « ne contient pas n’importe lequel », « contient tous les » et « ne contient pas tous les » seront limités à 100 mots par champ d’entrée. Après cette date, la limite sera appliquée à tous les segments nouveaux et modifiés. Les segments existants qui dépassent la limite continueront à être pris en charge, mais ne pourront pas être modifiés ou enregistrés tant que le champ d’entrée dépasse la limite. Ces limites sont appliquées dans le cadre d’efforts continus visant à améliorer les performances des requêtes. |
| Modifications à venir concernant la prise en charge des **[!UICONTROL classifications activées par date]** et des **[!UICONTROL classifications numériques 2]** | Mise à jour le 28 mai 2019 | La possibilité d’importer des classifications numériques 2 et des classifications activées par date a été supprimée du code base. Cette modification prendra effet lors de la version de maintenance de juillet 2019. S’il y a des colonnes numériques ou des colonnes activées par date dans le fichier d’importation, ces cellules seront ignorées et les autres données de ce fichier seront importées normalement. <br/>Les classifications existantes peuvent toujours être exportées par le biais du workflow de classification standard et sont toujours disponibles dans les rapports. |
| Modification à venir des calculs des _totaux des rapports_. | Mise à jour le 9 juillet 2019 | Le **18 juin 2019**, Adobe Analytics va uniformiser les calculs des _totaux des rapports_ pour toutes les dimensions et mesures. Pour cette raison, les totaux de certains rapports seront modifiés (notamment les rapports Props ou Attributs du client). Avant cette modification, certains totaux incluaient ou excluaient la ligne _Non spécifié_ dans le total, peu importe si elle apparaissait ou non __ dans le rapport. <br/>À compter du 18 juin 2019, le poste _Non spécifié_ apparaîtra toujours dans le total du rapport, même s’il n’apparaît pas comme poste sur le rapport. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the "Typed/Bookmarked" line item for Referrer Type dimension or the "Other" line item for the Device Type dimension. Cette modification concernera Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder et l’API Reporting. |
| Mise à jour des téléchargements CSV depuis [!DNL Analysis Workspace] | 10 avril 2019 | À partir du 11 avril 2019, plusieurs modifications seront apportées aux **[!UICONTROL téléchargements CSV]** (et **[!UICONTORL copies dans le Presse-papiers]**) depuis [!DNL Analysis Workspace] pour supprimer la mise en forme des données exportée.  <ul><li>Le séparateur des milliers ne sera plus inclu. Le séparateur décimal sera toujours inclus et se conformera au format défini sous **[!UICONTROL Composants &gt; Paramètres de rapport &gt; Séparateur des milliers]**. Remarque : Les valeurs numériques qui utilisent une virgule comme séparateur décimal continuent à être placées entre guillemets dans le fichier CSV exporté.</li><li>Aucun symbole de devise ne sera affiché.</li><li>Aucun symbole de pourcentage ne sera affiché. Les pourcentages seront sous forme décimale. Par exemple, 75 % sera représenté comme 0,75.</li><li>La durée sera indiquée en secondes.</li><li>Les tableaux de cohortes affichent uniquement les valeurs brutes. Les pourcentages sont supprimés.</li><li>Si un nombre n’est pas valide, une cellule vide s’affichera.</li></ul> |
| Modification à venir de la commande du débogueur [!DNL Analysis Workspace] | 4 avril 2019 | La commande de la console permettant d’activer le débogueur [!DNL Analysis Workspace] sera remplacée par adobeTools.debug.includeOberonXml le **13 juin 2019**. adobe.tools.debug.includeOberonXml cessera de fonctionner après cette date. |
| Numéros de version des navigateurs mobiles | 7 février 2019 | Le niveau de troncation des numéros de version des navigateurs mobiles est modifié depuis le 8 janvier 2019 (de 2 à 1). Depuis lors, seuls les deux premiers niveaux des versions sont affichés (par ex. _Firefox 64.0.2_ apparaît désormais sous la forme _Firefox 64.0_). |
| Fin de vie d’[!DNL Ad Hoc Analysis] | 29 janvier 2019 | Le 6 août 2018, Adobe a annoncé la prochaine fin de vie d’[!DNL Ad Hoc Analysis]. dont la date sera communiquée dès que possible.<br/>Pour plus d’informations, notamment sur les versions de Java compatibles durant cette période, voir [Découvrir Workspace](https://adobe.ly/discoverworkspace). |
| Short [!DNL Analytics] report links | 14 janvier 2019 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| Fin de la prise en charge de TLS 1.0 | Mis à jour le 10 janvier 2019 | À compter du 11 février 2019, la création de rapports Adobe Analytics ne prendra plus en charge le chiffrement TLS 1.0 (Transport Layer Security – Sécurité de la couche de transport). Ce changement entre dans le cadre de nos efforts continus pour conserver des normes de sécurité élevées et promouvoir la sécurité des données des clients. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/>[!DNL Analytics] À compter du 20 février 2019, la collecte de données Adobe  ne prendra plus en charge le protocole TLS 1.0. À la suite de cette modification, Adobe ne collectera plus les données Analytics des utilisateurs finaux disposant d’appareils ou de navigateurs web plus anciens qui ne prennent pas en charge le protocole TLS 1.1 ou version ultérieure. Cette modification ne devrait pas avoir de répercussions importantes sur les données des clients ou le compte rendu des performances. (Si votre site Internet ne prend pas en charge TLS 1.0, vous ne serez pas concerné.) <br/>À compter du 11 avril 2019, l’API de création de rapports d’Adobe Analytics ne prendra plus en charge le chiffrement TLS 1.0. Les clients qui accèdent à l’API doivent vérifier qu’ils ne seront pas affectés. <ul><li>Les clients API utilisant Java 7 avec les paramètres par défaut devront être [modifiés pour prendre en charge TLS 1.2 ](https://www.java.com/en/configure_crypto.html). (Reportez-vous à la section _Modification de la version par défaut du protocole TLS pour les points de terminaison clients : TLS 1.0 à TLS 1.2_). </li><li>Les clients API utilisant Java 8 ne devraient pas être affectés, étant donné que TLS 1.2 est la configuration par défaut.</li><li> Les clients API utilisant d’autres structures devront contacter leurs fournisseurs pour plus de détails sur la prise en charge de TLS 1.2.</li></ul> |
| Flux de données : colonne post_product_list – modification de taille | 9 janvier 2019 | Le 7 février 2019, Adobe prévoit d’étendre la taille de la colonne post_product_list de 64 Ko à 16 Mo. Cette modification garantit que les valeurs eVar de marchandisage ajoutées à la colonne post_product_list lors du traitement ne causent pas de troncature de valeurs de produits et de revenus. Si certains de vos processus assimilent des valeurs post_product_list, assurez-vous qu’ils peuvent gérer des valeurs allant jusqu’à 16 Mo en longueur ou entraîneront une troncature des valeurs à 16 Ko afin d’éviter les problèmes d’assimilation de données. |
| Modifications de gestion concernant les points de terminaison inactifs [!DNL Analytics Live Stream] | 20 décembre 2018 | À compter du 1er février 2019, les points de terminaison [!DNL Live Stream] n’ayant reçu aucune connexion d’utilisateurs actifs durant 90 jours pourront être désactivés. Vous pouvez contacter l’assistance clientèle pour obtenir des renseignements au sujet de vos points de terminaison [!DNL Live Stream] et, si besoin, demander leur réactivation. De plus, veuillez vous assurer que vos processus client maintiennent une connexion permanente, comme prévu par la configuration du service, et qu’ils sont mis en œuvre pour se reconnecter lorsque la connexion est désactivée ou interrompue. |
| Mise à jour d’Adobe [!DNL Report Builder] en raison de la fin de la prise en charge du protocole TLS 1.0 | 7 septembre 2018 | En raison de la fin de la prise en charge du protocole TLS 1.0, nous avons recommandé aux utilisateurs d’[!DNL Report Builder] de télécharger la version v5.6.21 avant février 2019. À compter de cette date, les versions antérieures d’[!DNL Report Builder] ne fonctionneront plus. |

### AppMeasurement {#appm}

Publication le 15 juillet 2019:

**Appmeasurement pour JavaScript 2.15.0**

* Ajout du suivi de la portée de défilement de Carte d'activités à l'extension de Carte d'activités (AN -172949)
* Ajout de DIL 9.2 à appmeasurement. (AN-182472)

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

### Data Workbench {#aa-dwb}

* Updated the help definition for [log (X, B)](https://marketing.adobe.com/resources/help/en_US/insight/client/c_syntx_mtrc_exp.html) metric syntax documentation. (AN-180527)

Voir les [Notes de mise à jour de Data Workbench ](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/) pour connaître les dernières informations.

## Audience Manager {#aam}

**Correctifs et améliorations**

* On the [!UICONTROL Segments Overview] page, the width of the segment storage folder is now flexible. Cela vous permet de distinguer les segments avec des noms plus longs. (AAM-48400)
* Fixed an issue in [!UICONTROL Algorithmic Models], where moving the **Adjust Reach &amp; Accuracy** slider did not affect the model's reach or accuracy. (AAM-47996)
* Correction d'un problème dans les destinations Analytics, en raison duquel le bouton permettant de télécharger un fichier. csv de segments avec des contrôles d'exportation de données et/ou des stratégies de partage de données tierces était rompu. (AAM-48100)
* Correction d'un problème en raison duquel les clients voyaient des erreurs « Accès refusé » aléatoires lors de la connexion à l'interface utilisateur d'Audience Manager. (AAM-47632)

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Versions de produit

Informations sur les nouvelles fonctionnalités des produits suivants :

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Notes de mise à jour de Cloud Manager 2019.6.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### Documentation XML 3.4

La solution XML Documentation 3.4 est désormais disponible.

***Notes de mise à jour***

* Prise en charge ajoutée pour AEM 6.5.
* L'éditeur change :
   * Aperçu du niveau de carte.
   * Tables - provided an option to copy an `entry` or a `complete` row within a table using copy and paste.
   * Tableaux - permet de sélectionner plusieurs cellules dans une colonne et de les fusionner ou de les fusionner.
   * Tableaux - permet de définir les propriétés de colonne du tableau en mode Création de l'éditeur Web.
   * Tableaux - permet d'ajuster les proportions et la taille des colonnes dans un tableau standard.
   * Tableaux - Sélection de lignes et de colonnes dans la vue Auteur.
   * Tableaux - Styles et propriétés activés (align, valign) dans l'éditeur Web pour l'alignement des cellules de tableau.
   * Correction de bogues dans la vue Balises complètes, y compris les scénarios de copier-coller et de glisser-déposer de contenu.
   * Affichez les titres des rubriques dans les onglets Editeur.
   * Problèmes de performance résolus dans l'éditeur Web.
* Transfert de la ligne de base vers le contenu traduit lors de la traduction.
* Paramètre prédéfini de condition de transfert au cours du processus de traduction.
* Ajout de la capacité d'appliquer des étiquettes à tous les dépendances d'un mappage par rapport à la ligne de base.
* Ajout d'un bouton pour télécharger le mappage avec tous les dépendances sous la forme d'un fichier zip.
* Améliorations de la conversion XHTML vers DITA :
   * Le nom du fichier DITAMAP généré est maintenant identique au nom du fichier ZIP téléchargé.
   * Ajout de la prise en charge des éléments et des attributs HTML supplémentaires.
   * Prise en charge de l'ingestion simultanée du fichier html-zip.
   * The sub-folder hierarchy where the zip is uploaded (*under input path as configured in h2d_io.xml*), is retained for the generated output (*under the configured output path*).
* Fournit des journaux d'audit pour savoir qui a refusé la version et pourquoi.
* Génération de site AEM :
   * Désactivez la regénération pour les sous-zones.
   * Processus de génération de publication activés pour les cas d'utilisation de la regénération.
   * Désactivez l'option de régénération pour une rubrique masquée et rendez l'option disponible pour la rubrique parente où l'attribut chunked est appliqué.
* La recherche DITA fonctionne désormais sur la logique ET dans la recherche de ressources AEM.
* Résultats pour n'afficher pas les fichiers temporaires stockés dans le dossier de sortie de traduction.
* Onglet Ligne de base :
   * Amélioration des performances lors de l'ouverture d'une ligne de base.
   * Choisir des rubriques par date pour travailler sur l'horodatage du client.
* API pour la suppression des étiquettes.

#### Maintenance du produit

**AEM 6.2 SP20-CFP1**

AEM 6.2 Service Pack 1-Cumulative Fix Pack 20 (6.2.1.20), publié le 6 juin 2019, est une mise à jour importante qui inclut les principaux correctifs client publiés depuis la publication d'AEM 6.2 SP 1 décembre 2016.

* [Notes de mise à jour](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

La version 6.3.3.5 d'AEM 6.3.3.5, publiée le 3 juillet 2019, est une mise à jour importante qui comprend des correctifs client clés depuis la publication d'AEM 6.17 avril 2017.

* [Notes de mise à jour](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

AEM 6.4.5.0, publié le 3 juillet 2019, est une mise à jour importante qui comprend des correctifs client clés publiés depuis la publication d'AEM 6.4 en avril 2018.

* [Notes de mise à jour](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

AEM 6.5.1.0, publié le 3 juillet 2019, est une mise à jour importante qui comprend des correctifs client clés publiés depuis la publication d'AEM 6.5 en avril 2019.

* [Notes de mise à jour](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [Versions CFP d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Auto-assistance

**Mise à jour de l'invalidation du cache AEM**

An important AEM patch for the AEM 6.5 clientlibs cache invalidation is available by way of the [AEM 6.5.1.0 update](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html) or this [KB article](https://helpx.adobe.com/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html).

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

Pour les notes de mise à jour, voir :

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

Pour consulter la documentation du produit, voir :

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/support/campaign/standard.html) – [Notes de mise à jour](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) – [Vidéos de présentation](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Vidéos de présentation](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## [!DNL Target] {#target}

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release infomration about Target.

## Magento {#magento}

Pour plus d'informations sur les notes de mise à jour de Magento Commerce et de Magento Open Source, voir :

* [Notes de mise à jour de Magento Open Source 2.3.2](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Notes de mise à jour de Magento Commerce 2.3.2](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)

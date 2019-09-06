---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: notes de mise à jour
last-update: Septembre 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 2cf514449e70523a47b16dceb35d93ec7eff0824

---


# Accès anticipé - Septembre 2019 - Notes de mise à jour d'Experience Cloud

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!IMPORTANT]
>
>Cette page contient le contenu de pré-version et peut faire l'objet de modifications avant la version du 12 septembre 2019.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. Vous recevrez une notification trois à cinq jours ouvrables avant la sortie de la mise à jour. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

## Date de publication : 12 septembre 2019

* [Interface d’Experience Cloud](#ecloud)
* [Plateforme Experience](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (liens vers l'aide de la solution)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (liens vers l'aide de la solution)

## Interface d’Experience Cloud {#ecloud}

Notes de mise à jour de l'interface d'Experience Cloud et de l'administration des produits.

* Correction d'une vulnérabilité de sécurité pour inclure les en-têtes HTTP recommandés. (MCUI-9942)
* Correction d'un problème de permutation entre les sociétés de connexion Analytics. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Plateforme Experience {#platform}

Notes de mise à jour de la plateforme Experience Platform, du lancement de plateforme Experience Platform, du service d'identité et des bulletins de sécurité.

* [Experience Platform Launch](#launch)
* [Mobile Services et SDK Mobile](#mobile)
* [Bulletins et avis de sécurité](https://helpx.adobe.com/security.html) (tous les produits Adobe)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

### Mobile Services et SDK Mobile {#mobile}

Release Date: **September 26th**

**Ios (4.18.8)**

* Correction d'un bogue en raison duquel les données du SDK sont synchronisées avec l'application watchos couplée à chaque appel Analytics.
* Correction d'un bogue en raison duquel la charge utile des clics publicitaires ne pouvait pas être utilisée comme caractéristiques pour les messages in-app.
* Mise à jour des API de cadre de notification utilisateur au lieu de l'API uilocalnotification, qui a été abandonnée depuis ios 10.
* Mise à jour vers wkwebview au lieu d'uiwebview, qui est désormais obsolète pour ios 12.

**Android 4.17.10**

* Ajout de la prise en charge des balises de langue BCP 47.

**Unity**

* Module externe mis à jour vers 4.18.7 pour ios et 4.17.9 pour Android

## [!DNL Analytics] {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics :

* [Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants à l’intention des administrateurs d’Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nouvelles fonctionnalités, améliorations et correctifs d’Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- |  
| **Parcours IQ : Analyses multiterminaux** | En septembre 2019, Adobe Analytics propose un accès anticipé aux clients Analytics Ultimate à une nouvelle fonctionnalité puissante appelée Journey IQ : Analyses inter-périphériques. La fonction Cross-Device Analytics (CDA) transforme Adobe Analytics d'un appareil centré sur un outil d'analyse orienté personne. Grâce à CDA, vous pouvez répondre à des questions telles que : <ul><li>Combien de personnes interagissent avec ma marque ? Combien de dispositifs utilisent-ils ? Comment se chevaucher ?</li><li>À quelle fréquence les utilisateurs commencent-ils une tâche sur un périphérique mobile, puis passent-ils ensuite à un PC de bureau pour terminer la tâche ? Les clics publicitaires de campagne qui atterrissent sur un périphérique conduisent-ils à une conversion autre qu'un autre ?</li><li>Comment ma compréhension de l'efficacité de la campagne change-t-elle si je prends en compte les voyages entre plusieurs périphériques ? Comment ma analyse de l'entonnoir change-t-elle ?</li><li>Quels sont les chemins les plus courants empruntés par les utilisateurs d'un périphérique à l'autre ? Où abandonner ? Où réussissent-ils ?</li><li>En quoi le comportement des utilisateurs ayant plusieurs périphériques diffère-t-il des utilisateurs disposant d'un seul périphérique ?</li></ul><br/>Pour en savoir plus, rendez `adobe.ly/aacda`-vous sur la page. |
| **Architecture des classifications mise à jour** | Depuis septembre, une mise à jour de l'architecture des classifications sera migrée vers les clients sur une période de plusieurs mois. La version de septembre comprend la migration pour un petit nombre d'adopteurs anticipés.<br/>La mise à jour réduit considérablement le temps nécessaire pour que les transferts (y compris la logique de règle) soient importés/assimilés et rendus disponibles pour la création de rapports. |

#### Correctifs

* Correction d'un problème avec [!UICONTROL les services principaux Personnes] et [!UICONTROL les services] principaux qui n'étaient pas accessibles depuis le menu Experience Cloud principal. (AN-184294)
* Correction d'un problème en raison duquel le rail gauche dans [!UICONTROL Analysis Workspace] oscillait entre l'affichage d'une barre de défilement et l'absence de barre de défilement, ce qui provoquait un effet flutateur. (AN-183904)
* Correction de problèmes liés aux rapports d'erreur. Vous allez commencer à afficher des messages d'erreur plus spécifiques plutôt que l'indicateur d'erreur rouge. Plus particulièrement, elle devrait vous aider à comprendre quand la publication est générée par une charge importante, par une erreur ou par la création d'une requête de rapport trop complexe. (AN -184135) [Plus…](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* Correction d'un problème qui empêchait le téléchargement réussi des rapports d'abandons dans `.pdf/.xls/.rtf` les formats. (AN-183165)
* Correction de problèmes de connexion via Experience Cloud et de passage à différentes solutions Experience Cloud ou de basculement vers une autre société de connexion. (AN-183376)
* Correction d'un problème en raison duquel le transfert des ressources des projets planifiés ne fonctionnait pas correctement. Les groupes sont gérés dans [!UICONTROL la console] d'administration, de sorte que nous ne les copions pas entre les utilisateurs lors du transfert des fichiers. (AN-183751)
* Correction d'un problème de suppression des rapports planifiés dont les propriétaires avaient été supprimés. A partir de maintenant, une notification est envoyée à l'administrateur (qui a exécuté l'opération de suppression) lorsque le propriétaire de la planification n'existe plus. (AN-181000)

### Avis importants destinés aux administrateurs d’[!DNL Analytics] {#aa-notices}

| Avis | Date d’ajout ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Mise à jour des totaux de tableau à structure libre d'Analysis Workspace | 12 septembre 2019 | En octobre 2019, les lignes au total du tableau à structure libre commenceront la comptabilisation des filtres [de rapport](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) appliqués. A ce jour, les totaux ne sont comptabilisés que pour la segmentation. Grâce à cette modification, les visualisations dépendantes sont mises à jour (visualisations Synthèse des chiffres, [!UICONTROL par exemple),] ainsi que les données CSV et PDF exportées. |
| Modification à venir concernant `createDate` le champ pour les utilisateurs Analytics | 30 août 2019 | En octobre ou novembre 2019, `createDate` le champ des utilisateurs d'Analytics sera mis à jour de l'heure normale des Etats-Unis vers une valeur Date/Heure correctement formatée avec les informations sur le fuseau horaire. (AN-183468) |
| Prise en charge des décalages de fuseau horaire historiques | 8 août 2019 | Analytics gère désormais automatiquement les décalages de fuseau horaire pour les accès horodatés. Après cette modification du 8 août, les systèmes qui chargent les données pour un traitement historique n’auront plus besoin d’ajuster les décalages de fuseau horaire avant d’envoyer les données. |
| Limites du créateur de règles de classification | Ajout le 5 juin 2019 | Ces limites ne sont pas nouvelles, mais ont été ajoutées à la documentation [ici](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nouvelles limites des opérateurs de segment | Ajout le 31 mai 2019 | À compter du 18 juillet 2019, les opérateurs de segment _contient n’importe lequel_, _ne contient pas n’importe lequel_, _contient tous les_ et _ne contient pas tous les_ seront limités à 100 mots par champ d’entrée. Après cette date, la limite sera appliquée à tous les segments nouveaux et modifiés. Les segments existants qui dépassent la limite continueront à être pris en charge, mais ne pourront pas être modifiés ou enregistrés tant que le champ d’entrée dépasse la limite. Ces limites sont appliquées dans le cadre d’efforts continus visant à améliorer les performances des requêtes. |
| Support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | Mise à jour le 28 mai 2019 | La possibilité d’importer des classifications numériques 2 et des classifications activées par date a été supprimée du code base. Cette modification a pris effet avec la version de maintenance de juillet 2019. S’il y a des colonnes numériques ou des colonnes activées par date dans le fichier d’importation, ces cellules seront ignorées et les autres données de ce fichier seront importées normalement. <br/>Les classifications existantes peuvent toujours être exportées par le biais du workflow de classification standard et sont toujours disponibles dans les rapports. |
| Change to _Report Total_ calculations | Mise à jour le 9 juillet 2019 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. Ceci a entraîné une modification des totaux pour certains rapports (habituellement les rapports Prop ou Attributs du client). Avant cette modification, certains totaux incluaient ou excluaient la ligne _Non spécifié_ dans le total, peu importe si elle apparaissait ou _non_ dans le rapport. <br/>À compter du 18 juin 2019, le poste _Non spécifié_ apparaîtra toujours dans le total du rapport, même s’il n’apparaît pas comme poste sur le rapport. En outre, les segments qui utilisent la logique _existe_ ou _n’existe pas_ peuvent afficher des résultats différents pour certaines dimensions après cette modification, en particulier les dimensions dont _Non spécifié_ possède un nom spécial, comme l’élément de ligne « Tapé/Marqué » pour la dimension Type de référent ou l’élément de ligne « Autre » pour la dimension Type de périphérique. Cette modification concernera Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder et l’API Reporting. |
| Mise à jour des téléchargements CSV d’Analysis Workspace | 10 avril 2019 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from Analysis Workspace to remove formatting from exported data.  <ul><li>Le séparateur des milliers ne sera plus inclu. Le séparateur décimal sera toujours inclus et se conformera au format défini sous **[!UICONTROL Composants &gt; Paramètres de rapport &gt; Séparateur des milliers]**. Remarque : Les valeurs numériques qui utilisent une virgule comme séparateur décimal continuent à être placées entre guillemets dans le fichier CSV exporté.</li><li>Aucun symbole de devise ne sera affiché.</li><li>Aucun symbole de pourcentage ne sera affiché. Les pourcentages seront sous forme décimale. Par exemple, 75 % sera représenté comme 0,75.</li><li>La durée sera indiquée en secondes.</li><li>Les tableaux de cohortes affichent uniquement les valeurs brutes. Les pourcentages sont supprimés.</li><li>Si un nombre n’est pas valide, une cellule vide s’affichera.</li></ul> |
| Modification à venir de la commande du débogueur Analysis Workspace | 4 avril 2019 | Le **13 juin 2019**, la commande de la console permettant d’activer le débogueur Analysis Workspace sera remplacée par adobeTools.debug.includeOberonXml. adobe.tools.debug.includeOberonXml cessera de fonctionner après cette date. |
| Numéros de version des navigateurs mobiles | 7 février 2019 | Le niveau de troncation des numéros de version des navigateurs mobiles est modifié depuis le 8 janvier 2019 (de 2 à 1). Depuis lors, seuls les deux premiers niveaux des versions sont affichés (par ex. _Firefox 64.0.2_ apparaît désormais sous la forme _Firefox 64.0_). |
| Fin de vie d’[!DNL Ad Hoc Analysis] | 29 janvier 2019 | Le 6 août 2018, Adobe a annoncé la prochaine fin de vie d’[!DNL Ad Hoc Analysis]. dont la date sera communiquée dès que possible.<br/>Pour plus d'informations, y compris les versions de Java compatibles durant cette période, consultez [[! DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Liens d’[!DNL Analytics] rapports courts | 14 janvier 2019 | Tout lien d’[!DNL Analytics] rapport court qui n’aura pas été consulté pendant un an sera nettoyé et supprimé à compter du jeudi 17 janvier 2019, selon un calendrier progressif. |
| Flux de données : colonne post_product_list – modification de taille | 9 janvier 2019 | Le 7 février 2019, Adobe prévoit d’étendre la taille de la colonne post_product_list de 64 Ko à 16 Mo. Cette modification garantit que les valeurs eVar de marchandisage ajoutées à la colonne post_product_list lors du traitement ne causent pas de troncature de valeurs de produits et de revenus. Si certains de vos processus assimilent des valeurs post_product_list, assurez-vous qu’ils peuvent gérer des valeurs allant jusqu’à 16 Mo en longueur ou entraîneront une troncature des valeurs à 16 Ko afin d’éviter les problèmes d’assimilation de données. |
| Modifications de gestion concernant les points de terminaison inactifs [!DNL Analytics Live Stream] | 20 décembre 2018 | À compter du 1er février 2019, les points de terminaison [!DNL Live Stream] n’ayant reçu aucune connexion d’utilisateurs actifs durant 90 jours pourront être désactivés. Vous pouvez contacter l’assistance clientèle pour obtenir des renseignements au sujet de vos points de terminaison [!DNL Live Stream] et, si besoin, demander leur réactivation. De plus, veuillez vous assurer que vos processus client maintiennent une connexion permanente, comme prévu par la configuration du service, et qu’ils sont mis en œuvre pour se reconnecter lorsque la connexion est désactivée ou interrompue. |
| Mise à jour d’Adobe [!DNL Report Builder] en raison de la fin de la prise en charge du protocole TLS 1.0 | 7 septembre 2018 |
| Fin de la prise en charge de TLS 1.0 | Mis à jour le 10 janvier 2019 | TLS 1.0 n'est plus pris en charge dans |

### [!DNL AppMeasurement] {#appm}

Reportez-vous à [la page Notes de mise à jour d'appmeasurement pour Javascript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Nouvelles fonctionnalités, améliorations et correctifs dans Audience Manager.

### Nouvelles fonctionnalités et améliorations {#aam-features}

| Fonction | Description |
| -----------| ---------- |  
| **[Destinations basées sur les personnes](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** | [!DNLPDestinations basées sur un serveur d'eople] est un module complémentaire Audience Manager payant qui permet d'activer les segments d'audience propriétaires dans des environnements administrés par personne, tels que Facebook, à l'aide d'identifiants hachés, tels que des adresses électroniques. |
| **[Configuration des audiences personnalisées Twitter en tant que destination basée sur un périphérique en libre-service](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)** | Nous migrons les destinations Twitter vers un modèle de configuration en libre-service. Cet article explique ce que vous devez faire pour que les intégrations Twitter existantes continuent à fonctionner après la migration. |
| **[Exemples de facturation d'Audience Marketplace](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)** | Nous avons ajouté un nouvel exemple, Case 3, où nous détaillons le fonctionnement de la facturation pour les segments avec des cas d'activation et d'utilisation de modélisation. |

**Correctifs et améliorations**

* Nous avons corrigé un bogue en raison duquel les utilisateurs ne pouvaient pas modifier les destinations Adobe Analytics pour mapper les segments manuellement. (AAM-49323)
* Nous avons corrigé un bogue en raison duquel les flux Audience Marketplace en double provenaient d'un seul identifiant de source de données. Il doit exister un mappage 1:1 entre les sources de données et [!DNL Marketplace] les flux. (AAM-48504)
* Nous avons amélioré le processus de création de segments et de caractéristiques. Vous pouvez maintenant filtrer la source de données pour stocker la caractéristique ou le segment, afin d'exclure les sources de données autres que Audience Manager (par exemple, les sources de données d'une suite de rapports d'Adobe Analytics). (AAM-35899)
* Correction d'un problème dans l'API Sources de données, en raison duquel la définition du paramètre `ExcludeReportSuites=true` de requête n'excluait pas les sources de données de la suite de rapports d'Adobe Analytics. (AAM-48545)
* Nous avons apporté plusieurs améliorations à l'accessibilité de l'interface utilisateur d'Audience Manager. (AAM -49024) et (AAM -49031)

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Version du produit

**Cloud Manager 2019.8.0**

La version 2019.8.0 de Cloud Manager corrige divers bogues mineurs, améliore les performances de création et ajoute la prise en charge des packages de contenu créé de manière sélective.

* [Notes de mise à jour de Cloud Manager 2019.8.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Maintenance du produit

**Feuille de maintenance de maintenance AEM**

Consultez la feuille de maintenance de maintenance AEM telle qu'elle est publiée [ici](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html).

### Auto-assistance

**Version bêta d'Asset Link 1.1**

* [A propos de la version bêta d'Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [Configuration d'AEM pour Adobe Asset Link pour la version bêta](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**AEM Desktop App 2.0**

AEM Desktop App 2.0 pour MAC a été publié le 30 août 2019. L'application de bureau AEM 2.0 pour Windows sera publiée début septembre.

Accédez à la documentation et aux téléchargements [ici](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html).

**Balises dynamiques des ressources**

Découvrez comment mettre à jour un certificat une fois qu'il a expiré [ici](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate).

**Guide de l'utilisateur AEM Forms 6.5**

Une nouvelle documentation sur _les directives_ de déploiement réseau est désormais disponible. Voir le [Guide de l’utilisateur de ](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html).

**Service de conversion automatisée de formulaires**

La documentation du service de conversion AEM Forms automatisée est désormais disponible. Voir [Présentation du service de conversion de formulaires automatisés](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html).

### Communauté

**Webinars du créateur de compétences AEM**

* [Sites Adobe Experience Manager](https://forums.adobe.com/thread/2647742)

   | Webinaire | Date |
   | -----------| ---------- |  
   | _Création d'expériences Web_ | 27 août 2019 |
   | _Recherche et navigation dans le contenu_ | 03 septembre 2019 |
   | _Gérer facilement le contenu à modification automatique_ | 10 septembre 2019 |
   | _Expériences fluides_ | 17 septembre 2019 |
   | _Création et gestion multi-lingual, multi-national pour créer une structure de site Web globale_ | 24 septembre 2019 |

* [Ressources Adobe Experience Manager](https://forums.adobe.com/thread/2647743)

   | Webinaire | Date |
   | -----------| ---------- |  
   | _Structure de dossiers et recherche_ | 29 août 2019 |
   | _Métadonnées_ | 05 septembre 2019 |
   | _Brand Portal _ | 12 septembre 2019 |
   | _Contenu multimédia dynamique_ | 19 septembre 2019 |
   | _Lien d'actif_ | 26 septembre 2019 |

* [Adobe Experience Manager Forms](https://forums.adobe.com/thread/2647744)

   | Webinaire | Date |
   | -----------| ---------- |  
   | Forms 101_ | 04 septembre 2019 |
   | _Connect Forms to Databases, Build Workflows et Integrate Forms with E-Signatures_ | 11 septembre 2019 |
   | _Créer des communications interactives prêtes pour l'impression et le web Mobile_ | 25 septembre 2019 |

* [Adobe Experience Manager Cloud Manager](https://forums.adobe.com/thread/2647745)

   | Webinaire | Date |
   | -----------| ---------- |  
   | _Test des bonnes pratiques - Création, surveillance, contrôle et statistiques avec Cloud Manager_ | 18 septembre 2019 |
   | _Configurations de répartiteur avec Cloud Manager_ | 16 octobre 2019 |
   | _Création de processus avec Cloud Manager et outils tiers_ | 13 novembre 2019 |

### Ressources supplémentaires

* [Formation et assistance pour AEM 6.5 – Accueil](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Formation et assistance pour AEM 6.4 – Accueil](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Formation et assistance pour AEM 6.3 – Accueil](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Formation et assistance pour AEM 6.2 – Accueil](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versions plus anciennes de la documentation AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Accueil de l'aide de Media Classic Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notes de mise à jour de Dynamic Media ](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notes de mise à jour de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

### Fin de vie du produit

[!DNL Digital Publishing Suite Classic] (DPSC) fin de vie le 31 août 2019. Pour plus d'informations, voir [[! FAQ de fin de vie DNL Digital Publishing Suite Classic](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html).

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

### Adobe Campaign Classic

* [Mise à jour de Campaign Classic 19.1.4](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) - version 9032
* [Mise à jour de Campaign Classic 19.1.5](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) - version 9033

### Adobe Campaign [!UICONTROL Control Panel]

Nous avons ajouté de nouvelles fonctionnalités permettant aux utilisateurs administrateurs de recevoir des notifications avant que les certificats SSL de leurs domaines arrivent à expiration. Pour plus d’informations, consultez la [documentation détaillée](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html).

En outre, les utilisateurs administrateurs peuvent désormais supprimer les clés SSH ajoutées pour accéder aux serveurs SFTP.

Notez que le [!UICONTROL panneau de configuration] est disponible pour les clients Adobe Campaign Classic et Adobe Campaign Standard hébergés sur AWS. No upgrades are required to access [!UICONTROL Control Panel].

### Ressources supplémentaires

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

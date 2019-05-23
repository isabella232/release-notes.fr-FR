---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: notes de mise à jour
last-update: Mai 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 016a4a630f4f26be8322a008bb214db9dba9a49a

---


# Notes de mise à jour d’Adobe Experience Cloud

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!NOTE]
>>Inscrivez-vous aux [Mises à jour produit prioritaires d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) afin de recevoir une notification par courrier électronique concernant les prochaines mises à jour. Vous recevrez une notification trois à cinq jours ouvrables avant la sortie de la mise à jour. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.


**Date de publication : Mai 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.5.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Notes de mise à jour d&#39;Adobe Experience Platform

Version 1.0, 15 mai 2019

* Voir [Notes de mise à jour sur Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) sur Adobe. io pour connaître les dernières mises à jour apportées à la plateforme Experience Platform.

### Experience Platform Launch

* Voir [Experience Platform Launch](https://docs.adobelaunch.com/) pour obtenir les informations les plus récentes.

### Service Experience Cloud ID

Parution **le 13 mai 2019**

* Prise en charge de Visitor API 4.3.0
* Prise en charge d’ITP 2.1.
* Correction d’un problème concernant la configuration secureCookie.

## Analytics {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics:

* [Nouvelles fonctionnalités et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants pour les administrateurs d’Analytics](#aa-notices)

Pour obtenir la documentation du produit, voir la [page d’accueil de l’aide d’Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Nouvelles fonctionnalités et correctifs d’Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- |  
| **Appmeasurement version 2.14.0** <ul><li>Correction de problèmes liés à la gestion de l&#39;état des paramètres de suivi lorsque plusieurs accès sont en attente. (AN -176931, AN -176629, DTM -12758)</li><li>Appmeasurement mis à jour pour inclure Visitor. js 4.3.0 (AN -180049)</li></ul> |
| **Analysis Workspace :** Nouveau _paramètre de visualisation Inclure les instances_ répétées | Le paramètre de visualisation de flux _Inclure les instances répétées_ vous permet d’inclure ou d’exclure des instances répétées, telles que le rechargement de pages. De plus, toutes les visualisations de flux sont maintenant basées uniquement sur des instances. |
| **Ad - Analyses ad hoc :** Compatibilité avec Java 11 | Ad Hoc Analysis est désormais compatible avec Java 11. Découvrez comment exécuter [Ad - Analyses ad hoc sur Java 11](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html). |
| **Collecte de données :** Nouveau cookie s_ ecid | Ajout d’un cookie de serveur propriétaire, s_ecid, dans lequel la collecte de données stocke l’ECID du visiteur. |

**Correctifs d’Analysis Workspace**

* Correction d’un problème affectant le Durée de consultation de la page. Les rapports Workspace n’utiliseront plus le nom de la page lors du calcul des intervalles de durée, ce qui permet de compter les accès granulaires et par intervalle. (AN-140479)
* Correction des problèmes de performances de visualisation des lignes dans le cadre d’un effort plus vaste visant à améliorer les performances de Workspace. (AN-174878)
* Correction du problème de l’absence de codage UTF-8 dans les fichiers .csv téléchargés. (AN-178393)
* Correction de problèmes de performances ralenties avec le projet Workspace. (AN-177710)
* Correction des problèmes d’affichage de visualisation des lignes avec les petites plages dans la granularité de l’axe Y. (AN-176467)

**Autres correctifs d’Analytics**

* Audience Analytics : correction d’un problème survenant après la modification d’un nom de public dans Audience Manager (AAM) – le nom mis à jour n’était pas reflété dans Audience Analytics. (AN-176237)
* Correction d’un bogue qui empêchait les utilisateurs d’enregistrer les segments Analytics dans AAM. Cela était dû à des dossiers AAM existants avec un mélange de noms majuscules et minuscules. Nous traitons maintenant tous les dossiers comme insensibles à la casse pour qu’ils se synchronisent. (AN-177934)
* Correction d’un problème qui se produisait lorsque les utilisateurs se connectaient à Analytics via Experience Cloud et que leur session expirait. Lors de la reprise de la session, l’utilisateur était redirigé vers une URL défectueuse. (AN-176812)
* Correction d’un problème concernant les décalages de fuseau horaire dans les demandes Data Warehouse. (AN-177585)

### Avis importants pour les administrateurs d’Analytics {#aa-notices}

| Avis | Date d’ajout    ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Modification à venir des calculs des _totaux des rapports_. | 16 avril 2019 | Le **13 juin 2019**, Adobe Analytics va uniformiser les calculs des _totaux des rapports_ pour toutes les dimensions et mesures. Pour cette raison, les totaux de certains rapports seront modifiés (notamment les rapports Props ou Attributs du client). Avant cette modification, certains totaux incluaient ou excluaient la ligne _Non spécifié_ dans le total, peu importe si elle apparaissait ou non__ dans le rapport. <br/>À compter du 13 juin 2019, le poste _Non spécifié_ apparaîtra toujours dans le total du rapport, même s’il n’apparaît pas comme poste sur le rapport. En outre, les segments utilisant la logique _existe_ ou _n’existe pas_ pourront afficher des résultats différents pour certaines dimensions après ce changement. Cette modification concernera Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder et l’API Reporting. |
| Mise à jour des téléchargements CSV d’Analysis Workspace | 10 avril 2019 | À partir du 11 avril 2019, plusieurs modifications seront apportées aux téléchargements CSV (et copies dans le Presse-papiers) depuis Analysis Workspace pour supprimer le formatage des données exportées.  <ul><li>Le séparateur des milliers ne sera plus inclus. Le séparateur décimal sera toujours inclus et se conformera au format défini sous **Composants** &gt; **Paramètres de rapport** &gt; **Séparateur des milliers**. Remarque : Les valeurs numériques qui utilisent une virgule comme séparateur décimal continuent à être placées entre guillemets dans le fichier CSV exporté.</li><li>Aucun symbole de devise ne sera affiché.</li><li>Aucun symbole de pourcentage ne sera affiché. Les pourcentages seront sous forme décimale. Par exemple, 75 % sera représenté comme 0,75.</li><li>La durée sera indiquée en secondes.</li><li>Les tableaux de cohortes affichent uniquement les valeurs brutes. Les pourcentages sont supprimés.</li><li>Si un nombre n’est pas valide, une cellule vide s’affichera.</li></ul> |
| Modification à venir de la commande du débogueur Analysis Workspace | 4 avril 2019 | Le **13 juin 2019**, la commande de la console permettant d’activer le débogueur Analysis Workspace sera remplacée par adobeTools.debug.includeOberonxml. |
| Modifications à venir concernant la prise en charge des classifications activées par date et des classifications numériques | 28 février 2019 | La possibilité d’importer des classifications numériques 2 et des classifications activées par date a été supprimée du code base. Cette modification prendra effet lors de la version de maintenance de juin 2019. S’il y a des colonnes numériques ou des colonnes activées par date dans le fichier d’importation, ces cellules seront ignorées et les autres données de ce fichier seront importées normalement. <br/>Les classifications existantes peuvent toujours être exportées par le biais du workflow de classification standard et sont toujours disponibles dans les rapports. |
| Mise à jour notable de la documentation relative au module externe getPercentPageViewed. | 12 février 2019 | [https://experiencecloud.adobe.com/resources/help/fr_FR/sc/implement/getPercentPageViewed.html](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/getPercentPageViewed.html) |
| Administration &gt; Paramètres du compte général | 7 février 2019 | * Le paramètre _Remplacer le dernier octet de l’adresse IP par 0_ est activé par défaut pour toutes les suites de rapports créées dans le centre de données de Londres après janvier 2019, mais seulement si les paramètres de ces suites de rapports sont copiés à partir d’un modèle répertorié dans Admin Console. Les suites de rapports dont les paramètres sont copiés depuis d’autres suites de rapports héritent de tous les paramètres de la suite de rapports sélectionnée.<br/> * Le paramètre _Obscurcissement d’IP_ n’est plus activé par défaut pour les utilisateurs d’une suite de rapports paramétrée dans la zone EMEA. |
| Numéros de version des navigateurs mobiles | 7 février 2019 | Le niveau de troncation des numéros de version des navigateurs mobiles est modifié depuis le 8 janvier 2019 (de 2 à 1). Depuis lors, seuls les deux premiers niveaux des versions sont affichés (par ex. _Firefox 64.0.2_ apparaît désormais sous la forme _Firefox 64.0_). |
| Fin de vie d’Ad Hoc Analysis | Mis à jour le 29 janvier 2019 | Le 6 août 2018, Adobe a annoncé la prochaine fin de vie d’Ad Hoc Analysis, dont la date sera communiquée dès que possible.<br/>Pour plus d’informations, notamment sur les versions de Java compatibles durant cette période, voir [Découvrir Workspace](https://adobe.ly/discoverworkspace). |
| Liens de rapports Analytics courts | 14 janvier 2019 | Tout lien de rapport Analytics court qui n’aura pas été consulté pendant un an sera supprimé à compter du 17 janvier 2019, selon un calendrier progressif. |
| Fin de la prise en charge de TLS 1.0 | Mis à jour le 10 janvier 2019 | Le 11 février 2019, la création de rapports Adobe Analytics ne prendra plus en charge le chiffrement TLS (Transport Layer Security) 1.0.  Ce changement entre dans le cadre de nos efforts continus pour conserver des normes de sécurité élevées et promouvoir la sécurité des données des clients. Si vous ne parvenez pas à vous connecter à la création de rapports Adobe Analytics après le 11 février 2019, vous devez mettre à niveau votre navigateur vers la [dernière version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/>À compter du 20 février 2019, la collecte de données Adobe Analytics ne prendra plus en charge TLS 1.0. À la suite de cette modification, Adobe ne collectera plus les données Analytics des utilisateurs finaux disposant d’appareils ou de navigateurs Web plus anciens qui ne prennent pas en charge TLS 1.1 ou version supérieure. Cette modification ne devrait pas avoir de répercussions importantes sur les données des clients ou le compte rendu des performances. (Si votre site Internet ne prend pas en charge TLS 1.0, vous ne serez pas concerné.) <br/>À compter du 11 avril 2019, l’API de création de rapports d’Adobe Analytics ne prendra plus en charge le chiffrement TLS 1.0. Les clients qui accèdent à l’API doivent vérifier qu’ils ne seront pas affectés. <ul><li>Les clients API utilisant Java 7 avec les paramètres par défaut devront être [modifiés pour prendre en charge TLS 1.2 ](https://www.java.com/en/configure_crypto.html). (Reportez-vous à la section _Modification de la version par défaut du protocole TLS pour les points de terminaison clients : TLS 1.0 à TLS 1.2_). </li><li>Les clients d’API utilisant Java 8 ne devraient pas être affectés, étant donné que TLS 1.2 est la configuration par défaut.</li><li> Les clients API utilisant d’autres structures devront contacter leurs fournisseurs pour plus de détails sur la prise en charge de TLS 1.2.</li></ul> |
| Mise à jour d’Adobe Report Builder en raison de la fin de la prise en charge du protocole TLS 1.0 | 7 septembre 2018 | En raison de la fin de la prise en charge du protocole TLS 1.0, nous avons recommandé aux utilisateurs d’Adobe Report Builder (ARB) de télécharger ARB 5.6.21 avant le jeudi 7 février 2019. **À compter de cette date, les versions antérieures d’ARB ne fonctionneront plus.** |
| Mise à jour des téléchargements CSV d’Analysis Workspace | 9 janvier 2019 | A compter du 7 février 2019, les téléchargements CSV (et Copier dans le presse-papiers) d’Analysis Workspace n’incluront plus le séparateur des milliers. Remarque : L’interface utilisateur d’Analysis Workspace continuera d’afficher le séparateur des milliers. En outre, le séparateur décimal sera toujours inclus et adhèrera au format défini sous **[!UICONTROL Composants]** &gt; **[!UICONTROL Paramètres de rapport]** &gt; **[!UICONTROL Séparateur des milliers]**. |
| Flux de données : colonne post_product_list – modification de taille | 9 janvier 2019 | Le 7 février 2019, Adobe prévoit d’étendre la taille de la colonne post_product_list de 64 Ko à 16 Mo. Cette modification est censée garantir que les valeurs eVar de marchandisage ajoutées à la colonne post_product_list lors du traitement ne causent pas de troncature de valeurs de produits et de revenus. Si certains de vos processus assimilent des valeurs post_product_list, assurez-vous qu’ils peuvent gérer des valeurs allant jusqu’à 16 Mo en longueur ou entraîneront une troncature des valeurs à 16 Ko afin d’éviter les problèmes d’assimilation de données. |
| Modifications de gestion concernant les points de terminaison inactifs Live Stream d’Analytics | 20 décembre 2018 | À compter du 1er février 2019, les points de terminaison Live Stream n’ayant reçu aucune connexion d’utilisateurs actifs durant 90 jours seront désactivés. Vous pouvez contacter l’assistance clientèle pour obtenir des renseignements au sujet de vos points de terminaison Live Stream et, si besoin, demander leur réactivation. De plus, veuillez vous assurer que vos processus client maintiennent une connexion permanente, comme prévu par la configuration du service, et qu’ils sont mis en œuvre pour se reconnecter lorsque la connexion est désactivée ou interrompue. |
| Migration du serveur FTP de Dallas (ftp2.omniture.com) | 19 octobre 2018 | Le 23 octobre 2018, si vous vous connectez à ftp2.omniture.com par l’intermédiaire du protocole SFTP, vous devrez peut-être réaccepter l’identificateur d’hôte du site SJ1. Ce problème se produira uniquement le 23 octobre. Voir [Mise à niveau des serveurs FTP Adobe](https://marketing.adobe.com/resources/help/en_US/whitepapers/ftp/ftp_upgrade.html). |
| Mise à jour de la dimension Appareil mobile | 16 octobre 2018 | Le 26 septembre, Adobe a mis à jour la recherche d’appareils vers l’API 2.1 de Device Atlas. Pour cette raison, des appareils plus détaillés (ex. Apple iPhone 7, Apple iPhone 8 Plus, etc.) apparaissent dans la dimension Appareil mobile pour certains navigateurs. Ce nouveau niveau de détail sur les appareils ne s’étend pour l’instant pas à tous les appareils ni à tous les types de navigateurs. |
| Fin de la prise en charge d’Internet Explorer 11 | 12 septembre 2018 | Le 13 novembre 2018, Adobe va cesser la prise en charge d’Internet Explorer 11 dans Adobe Analytics. Veuillez utiliser Microsoft Edge ou un autre navigateur pris en charge dès que possible. |
| Fin de vie d’Ad Hoc Analysis | 9 août 2018 | Le 6 août 2018, Adobe a annoncé la prochaine fin de vie d’Ad Hoc Analysis, dont la date sera communiquée dès que possible. Pour obtenir de plus amples informations, voir le site [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). À partir de cette date, nous ne modifierons plus [!UICONTROL Ad Hoc Analysis] pour assurer la prise en charge de Java 9+. Si vous effectuez une mise à niveau vers Java 9+, [!UICONTROL Ad Hoc Analysis] ne fonctionnera plus. Seul Java 8 sera pris en charge. |
| Mise à jour d’Adobe [!UICONTROL Report Builder] en raison de la fin de la prise en charge du protocole TLS 1.0 | 7 septembre 2018 | En raison de la fin de la prise en charge du protocole TLS 1.0, nous avons recommandé aux utilisateurs de [!UICONTROL Report Builder] (ARB) de télécharger ARB 5.6.21 avant février 2019. À compter de cette date, les versions antérieures d’ARB ne fonctionneront plus. |
| Nouvelle aide pour la migration des utilisateurs Analytics | 10 mai 2018 | Nous avons mis à jour l’aide pour la migration des ID utilisateur Analytics avec des informations sur la migration des Enterprise ID et des Federated ID vers Admin Console. Voir [Migration de comptes utilisateurs Analytics pour les Enterprise IDs et les Federated IDs](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/migrate-enterprise.html). |
| Suppression prochaine du rapport Activité du compte | 10 mai 2018 | Le rapport Activité du compte va être remplacé par la fonctionnalité Utilisation de l’appel au serveur dans la version d’été d’Adobe Analytics. Le rapport Activité du compte sera définitivement supprimé le 9 août 2018. Pour afficher un récapitulatif du trafic des suites de rapports après le 9 août 2018, utilisez la fonctionnalité Utilisation de l’appel au serveur. |
| Modifications apportées aux modèles d’attribution linéaire dans les mesures calculées | Effectives le 19 juillet 2018 | Le 19 juillet, Adobe Analytics reverra la manière dont les modèles d’attribution dans les mesures calculées sont évalués. Dans le cadre de cette modification, les mesures calculées qui n’utilisent pas un modèle d’attribution prédéfini seront transférées vers un nouveau modèle d’attribution amélioré. Les modèles d’attribution [!UICONTROL Dernière touche canal marketing] et [!UICONTROL Première touche canal marketing] seront migrés vers les nouveaux modèles d’attribution [!UICONTROL Dernière touche] et [!UICONTROL Première touche]. (Les [!UICONTROL canaux marketing] ne sont pas en train de devenir obsolètes ; ce n’est le cas que pour ces deux modèles d’attribution qui apparaissent dans les mesures calculées.) De plus, nous corrigerons la façon dont l’attribution linéaire est calculée. Si vous utilisez des mesures calculées avec des modèles d’attribution linéaire, les rapports peuvent légèrement changer afin de tenir compte du nouveau modèle d’attribution corrigé. Cette modification des mesures calculées sera reflétée dans [!UICONTROL Analysis Workspace], [!UICONTROL Reports &amp; Analytics], l’[!UICONTROL API de création de rapports], [!UICONTROL Report Builder] et [!UICONTROL Ad Hoc Analysis]. Pour plus d&#39;informations sur cette modification, reportez-vous à [la documentation Mesures](https://marketing.adobe.com/resources/help/en_US/analytics/calcmetrics/m_metric_type_alloc.html) calculées. |
| [!UICONTROL ][!UICONTROL Suppression de la détection des anomalies et de l’analyse des contributions des fonctionnalités de ]Reports &amp; Analytics[!UICONTROL ] | 10 avril 2018 | La détection des anomalies et l’analyse des contributions ont été supprimées de l’ensemble de fonctionnalités Reports &amp; Analytics et sont désormais disponibles uniquement via Analysis Workspace. Les clients Adobe Analytics Select et Foundation ne profitent que d’une détection des anomalies « à granularité journalière » dans Workspace. |
| Adobe a cessé d’émettre des cookies s_vi tiers pour Safari. | 5 avril 2018 | Depuis le 20 mars 2018, Adobe a cessé d’émettre des cookies s_vi tiers pour le navigateur Safari. Cette modification n’affecte pas les clients utilisant des cookies de collecte de données internes. Cette modification supprime également l’inflation des visites et des visiteurs que connaissent certains clients, en raison de l’ITP de Safari. |
| Modification du système principal qui affecte la création de rapports | 11 avril 2018 | Une modification apportée au mécanisme de recherche (système principal) va se répercuter de plusieurs façons sur le reporting. Notez que les modifications suivantes sont entrées en vigueur fin février 2018 :   L’attribution d’un nouveau nom aux pages ne sera plus autorisée. À partir de maintenant, vous devrez utiliser les classifications pour renommer les pages. Jusqu’à la mise à jour du 10 mai 2018, le système continuera à traiter les pages renommées telles qu’elles sont actuellement configurées. Adobe invite ses clients à effectuer la migration vers les classifications avant cette date. Après la version de mai, les changements de noms actuels ne seront plus honorés et pourront être changés, rétroactivement, sans préavis. <br/>La méthodologie de remplacement des URL diffère. Auparavant, Adobe Analytics stockait (généralement) la première URL associée à chaque nom de page, chaque mois. À compter de maintenant, nous stockerons l’URL la plus récente pour chaque nom de page. (Mise à jour le 11 avril 2018) Les rapports de catégorie pour les cumuls et les données en cours dans les Reports &amp; Analytics ne sont plus fournis. La fin de la fourniture des rapports de cumul de catégorie dans l’API de services Web est effective avec la version de maintenance d’Adobe Analytics du 10 mai 2018. Les données de page ou de props d’avant janvier 2007 environ (2006 dans certains cas) ne sont plus prises en charge. Seuls les pages, props et événements de page seront concernés (c.-à-d. les liens personnalisés, les liens de sortie et les liens de téléchargement). Remarque : Cette modification n’a aucune incidence sur la création de rapports dans Analysis Workspace et Data Warehouse. Si vous disposez de données antérieures à ces dates, attendez-vous à ce qui suit : les données ne seront pas combinées correctement dans les limites avant/après 2007. Les recherches ne fonctionneront pas pour les données d’avant janvier 2007 environ. |
| Modifications à venir concernant la prise en charge des classifications activées par date et des classifications numériques | 7 mai 2018 | Dans la version de maintenance du 10 mai 2018, nous allons commencer à limiter les fonctionnalités des classifications numériques et par date. Ces types de classification seront supprimés des interfaces Admin et Importateur de classifications. À partir de cette date, aucune nouvelle classification activée par date et numérique ne pourra être ajoutée. Il sera possible de continuer à gérer les classifications actuelles (les transférer, les supprimer) par l’intermédiaire des processus de classification standard et elles resteront disponibles dans le reporting. |
| Modifications à venir de la prise en charge de l’option Coût et budget des canaux marketing | 28 février 2018 | Dans la version de maintenance d’avril, nous supprimerons l’option Coût et budget des canaux marketing du menu Admin &gt; Canal marketing. Aucune nouvelle donnée de coût et de budget ne pourra être ajoutée. Les données de coût et de budget existantes continueront à être disponibles dans le reporting, mais ne pourront pas être mises à jour. |
| Mettre à jour Report Builder avant de migrer les identifiants utilisateur vers Admin Console | 17 mars 2018 | **Important :** Mettez à jour Report Builder vers la dernière version. À compter d’avril 2018, cette mise à jour est un prérequis à la migration des identifiants utilisateur Analytics vers Admin Console. |
| Gestionnaire de code – Code H hérité | 8 février 2018 | Il n’est plus possible de télécharger du code H JavaScript hérité depuis le gestionnaire de code. |
| Rétention des données : contrôlez et définissez votre politique de rétention des données pour Adobe Analytics | 1 février 2018 | **Contexte :** le RGPD (Règlement général sur la protection des données), qui entre en vigueur le 25 mai 2018, stipule qu’Adobe, en tant qu’entité de traitement des données, doit prendre les mesures adéquates pour aider ses clients à répondre aux demandes d’accès, de suppression et autres d’individus. L’application de politiques de suppression appropriées, sécurisées et opportunes est un aspect essentiel du respect de cette obligation. Par conséquent, Adobe aimerait collaborer avec vous pour mettre en place une politique de rétention des données avant l’entrée en vigueur du RGPD le 25 mai 2018.<br/>**À quoi vous attendre :** à moins que vous n’ayez déjà mis en place une politique de rétention des données Adobe Analytics, Adobe commencera à appliquer la rétention de ces données comme indiqué dans les contrats clients, sauf si d’autres mesures sont prises. La plupart des contrats Adobe Analytics stipulent qu’Adobe doit supprimer les données au bout de 25 mois. Une fois qu’une politique de rétention des données a été mise en place pour votre organisation, elle est appliquée sur une base mensuelle glissante. La rétention des données pour des périodes de plus de 25 mois entraîne des frais supplémentaires. La rétention des données pour de plus courtes périodes peut également être mise en place en contactant l’assistance clientèle. Vous recevrez prochainement un e-mail contenant des informations supplémentaires concernant votre organisation. <br/>La rétention des données affecte toutes les méthodes d’accès aux données Adobe Analytics historiques, notamment, mais sans s’y limiter, Reports &amp; Analytics, Analysis Workspace, Report Builder, et l’API de création de rapports des services Web, Data Warehouse et les flux de données. **Étapes suivantes :** identifiez les parties prenantes de votre organisation chargées de prendre des décisions concernant la rétention des données. Votre organisation est la mieux placée pour déterminer la durée pendant laquelle les données Adobe Analytics doivent être conservées. Contactez votre responsable du succès client Adobe si vous avez des questions concernant la rétention des données pour Adobe Analytics. |
| Association de comptes utilisateur | 26 octobre 2017 | Les utilisateurs Analytics ne doivent plus associer manuellement leurs comptes Experience Cloud et Analytics. Les utilisateurs peuvent contacter leur administrateur Admin Console pour demander l’accès à Analytics. La migration des ID utilisateur Analytics permet aux administrateurs de migrer facilement les comptes utilisateurs de la gestion des utilisateurs Analytics vers Adobe Admin Console. Une fois la migration de vos utilisateurs terminée, ils auront accès aux solutions achetées et aux services principaux disponibles dans Experience Cloud. [En savoir plus sur la migration des ID utilisateur Analytics](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/). |

## Audience Manager {#aam}

| Fonction | Description |
| -----------| ---------- |  
| [Obscurcissement d’adresses IP](https://marketing.adobe.com/resources/help/en_US/aam/ip-obfuscation.html) | Votre entreprise peut souhaiter obscurcir l’adresse IP dans de nombreux pays en raison de la réglementation mondiale en matière de confidentialité. Audience Manager vous permet d’obsurcir les adresses IP des visiteurs de manière globale ou pays par pays. |
| [Intégrations personnalisées des partenaires – Oracle Data Cloud](https://marketing.adobe.com/resources/help/en_US/aam/custom-partner-integrations.html) | Cette page répertorie les intégrations personnalisées entre Audience Manager et les partenaires de données. Audience Manager récupère les données de cookies et d’ID mobile à partir d’Oracle Data Cloud pour Audience Marketplace via des fichiers de données entrants. Les spécifications d’intégration personnalisées décrites sur cette page font uniquement référence aux fichiers de données entrants contenant des ID mobiles (IDFA et ID de périphérique Android). |

**Correctifs, améliorations et obsolescences**

* Nous avons ajouté deux nouvelles colonnes aux rapports généraux sur les destinations. Vous pouvez maintenant voir la Date de début et la Date de fin d’un mappage de segment à une destination. (AAM-44781)

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Versions de produit

**AEM 6.5**

AEM 6.5, disponible à partir du 8 avril 2019, est une version de mise à niveau de la base de code d’AEM 6.4. Nos dernières mises à jour vers AEM 6.5 vous donnent un accès instantané à des améliorations intéressantes qui permettent à votre entreprise de progresser encore plus rapidement.

* [Nouveautés d’Adobe Experience Manager 6.5](https://www.adobe.com/marketing/experience-manager/new.html)
* [Notes de mise à jour d’Adobe Experience Manager 6.5](https://helpx.adobe.com/experience-manager/6-5/release-notes.html)

**Cloud Manager 2019.4.0**

La dernière version de Cloud Manager (2019.4.0 publiée le 18 avril 2019) ajoute une interface utilisateur localisée en français, allemand et japonais. En outre, les étapes de déploiement ont été améliorées.

* [Notes de mise à jour de Cloud Manager 2019.4.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Maintenance du produit

**AEM 6.4.4.0**

AEM 6.4, Service Pack 4 (version 6.4.4.0 publiée le 4 avril 2019) est une mise à jour importante qui inclut des correctifs clients clés publiés depuis la disponibilité générale d’AEM 6.4, avril 2018.

[Notes de mise à jour d’AEM 6.4 Service Pack](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
[Versions d’AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM S3 Connector**

Les instances AEM avec d’anciennes versions de S3 Datastore Connector peuvent devenir indisponibles en raison d’échecs d’accès à S3 après la fin de la prise en charge de Signature version 2 le 24 juin 2019. En tant que client AEM, Adobe vous recommande de vérifier la version de S3 Datastore Connector que vous utilisez. Si nécessaire, effectuez une mise à jour vers une version récente.

Voir [Impact de l’obsolescence d’AWS Signature version 2 sur Amazon S3](https://helpx.adobe.com/experience-manager/kb/the-impact-of-aws-signature-version-2-deprecation-for-amazon-s3.html)

### Auto-assistance

**Moderniser votre base de code AEM Sites**

Découvrez comment tirer parti de la dernière technologie AEM pour moderniser votre base de code AEM Sites. [Modernisation de votre base de code Adobe Experience Manager existante](https://expleague.azureedge.net/labs/L761/index.html)

**Éditeur de texte enrichi AEM – Présentation approfondie**

Découvrez les bonnes pratiques relatives aux configurations riches et à l’utilisation de l’éditeur de texte enrichi dans AEM.

Voir [Présentation approfondie de l’éditeur de texte enrichi AEM](https://helpx.adobe.com/experience-manager/kt/eseminars/gems/AEM-Rich-Text-Editor-RTE-Deep-Dive1.html)

### Ressources supplémentaires  

* [Formation et assistance pour AEM 6.5 – Accueil](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Page d’accueil Formation et assistance AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Page d’accueil Formation et assistance AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Page d’accueil Formation et assistance AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guide de l’utilisateur de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Anciennes versions de la documentation d’AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Notes de mise à jour de Scene7 Publishing System](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notes de mise à jour de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## Campaign {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

* Campaign Classic 18.10.4 - build 8983
* Campaign Classic 18.10.5 - build 8984

Voir les [Notes de mise à jour d’Adobe Campaign Classic](http://docs.campaign.adobe.com/doc/AC/en/RN.html) pour les correctifs et améliorations.

Pour consulter la documentation du produit, voir :

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/support/campaign/standard.html) – [Notes de mise à jour](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) – [Vidéos de présentation](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Vidéos de présentation](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| Fonction | Description |
| -----------| ---------- |  
| Rechercher de recherche | (Pour les annonceurs disposant de comptes Google Ads) Advertising Cloud peut éventuellement télécharger vers Google Ads toutes les données de conversion suivies pour les campagnes Google Ads utilisant le service de suivi des conversions Advertising Cloud. Les téléchargements quotidiens incluent la valeur de conversion définie à l’aide du modèle d’attribution à l’échelle de l’annonceur. Le préfixe « Adobe_ACS_ » est ajouté à toutes les conversions téléchargées (par exemple, « Adobe_ACS_Abonnements » pour la conversion « Abonnements »). <br/> **Remarque :** Les téléchargements n’incluent pas les données de conversion téléchargées vers Advertising Cloud à partir de fichiers de flux. |
| Rechercher dans les campagnes | Le menu **de Recherche** &gt; **Campagnes** &gt; **Campagnes** est maintenant hiérarchique, avec Campagnes sous Comptes ; Groupes publicitaires sous Campagnes ; et Mots-clés (avec sous-submenu), Publicités, Groupes de produits (Affichages en direct uniquement), Emplacements (avec sous-submenu) et Cibles automatiques sous Groupes publicitaires.<br/>Dans les vues En direct, les audiences et les extensions sont au même niveau que les comptes, avec leurs propres sous-submenus. |

## Target Standard/Premium 19.5.1 {#target}

Cette version inclut les fonctionnalités, modifications et améliorations suivantes :

(Les numéros de publication entre parenthèses sont réservés à Adobe.)

### Mises à jour des fonctionnalités

| Fonction/amélioration | Description |
| --- | --- |
| Single Page App Visual Experience Composer (SPA VEC) | Le SPA VEC (compositeur d’expérience visuelle) a été amélioré comme suit afin que vous puissiez travailler plus vite et plus efficacement :<ul><li>Vous pouvez désormais annuler le chargement d’un site web dans le compositeur d’expérience visuelle afin de débloquer la modification d’une activité. Cette amélioration s’avère utile, par exemple, si vous souhaitez modifier légèrement l’activité, revoir ses paramètres ou ajouter un code personnalisé, sans attendre que le site soit chargé. (TGT-33872)</li><li>Vous pouvez effectuer de nombreuses actions avant le chargement de la page dans VEC, ou même si la page ne parvient pas à se charger complètement (par exemple, si un code personnalisé n’est plus fonctionnel). Les actions qu’il n’est pas possible de modifier avant le chargement complet du site sont désactivées dans l’interface utilisateur de Target. (TGT-33851 et TGT-34149)</li></ul> |
| Activités de personnalisation automatisée (PA) et de ciblage automatique | Vous pouvez sélectionner une expérience à utiliser en tant que contrôle lors de la création d’une activité de PA ou de ciblage automatique. Cette fonctionnalité vous permet d’acheminer tout le trafic de contrôle vers une expérience spécifique, en fonction du pourcentage d’allocation de trafic configuré dans l’activité. Vous pouvez ensuite évaluer les performances des livraisons personnalisées par rapport à l’expérience de contrôle. (TGT-26572) |
| Recommandations | Vous pouvez utiliser le bouton de basculement Recommander des articles précédemment achetés lors de la création de la logique Éléments récemment consultés. (TGT-34030) |

### Améliorations, correctifs et modifications

* Les icônes de la barre d’outils s’affichent correctement après l’annulation du chargement d’une page dans le compositeur d’expérience visuelle. Si des actions spécifiques ne peuvent être effectuées qu’après le chargement complet de la page, les icônes de la barre d’outils associée sont désactivées. (TGT-33811)
* Vous pouvez désormais répertorier et naviguer plus facilement dans les dossiers des offres du sélecteur de ressources au lieu de parcourir une hiérarchie de dossiers horizontale. (TGT-33725)

Reportez-vous aux [Notes de mise à jour d’Adobe Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) pour obtenir des informations récentes sur les produits suivants :

* Target Standard et Premium
* Recommendations Classic


## Magento {#magento}

Magento est une plateforme de commerce électronique qui fournit aux marchands en ligne un système de panier souple et un contrôle sur l’aspect, le contenu et les fonctionnalités de leur boutique en ligne. Magento est disponible dans une version open source et dans une version commerce intégrale.

Magento Commerce fait partie d’Adobe Commerce Cloud et offre une solution d’e-commerce avec une puissance d’entreprise, une évolutivité illimitée et une flexibilité open source pour les expériences B2C et B2B

Les notes de mise à jour des éditions open source et de commerce sont disponibles sur la page des [informations de version](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html).

## Primetime {#primetime}

Adobe Primetime est une plateforme télévisée multi-écran grâce à laquelle les entreprises multimédias peuvent créer et rentabiliser des contenus personnalisés et attrayants.

[Notes de mise à jour de Primetime](https://docs.adobe.com/content/help/en/primetime/release-notes/home.html)
[Accueil de l’aide de Primetime](https://helpx.adobe.com/fr/support/primetime.html)

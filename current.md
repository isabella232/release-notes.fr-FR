---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Modèle des notes de mise à jour d’Experience Cloud
doc-type: notes de mise à jour
last-update: Mai 2019
author: mfrei
translation-type: tm+mt
source-git-commit: c8db350233cea9b83993e4723601b01a8e301f87

---


# Notes de mise à jour d’Adobe Experience Cloud

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!NOTE]
>Inscrivez-vous aux [Mises à jour produit prioritaires d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) afin de recevoir une notification par courrier électronique concernant les prochaines mises à jour. Vous recevrez une notification trois à cinq jours ouvrables avant la sortie de la mise à jour. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

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

* Voir [Notes de mise à jour sur Platform Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) sur Adobe. io pour connaître les dernières mises à jour apportées à la plateforme Experience Platform.

### Experience Platform Launch

* Voir [Lancement de plateforme Experience](https://docs.adobelaunch.com/) pour obtenir les informations les plus récentes.

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
| [!DNL AppMeasurement Version 2.14.0] <ul><li>Correction de problèmes liés à la gestion de l&#39;état des paramètres de suivi lorsque plusieurs accès sont en attente. (AN -176931, AN -176629, DTM -12758)</li><li>Appmeasurement mis à jour pour inclure Visitor. js 4.3.0 (AN -180049)</li></ul> |
| [!DNL Analysis Workspace]: Nouveau paramètre de visualisation de flux _Inclure les instances répétées_ | Le paramètre de visualisation de flux _Inclure les instances répétées_ vous permet d’inclure ou d’exclure des instances répétées, telles que le rechargement de pages. De plus, toutes les visualisations de flux sont maintenant basées uniquement sur des instances. |
| [!DNL Ad Hoc Analysis]: Compatibilité avec Java 11 | Ad Hoc Analysis est désormais compatible avec Java 11. Découvrez comment exécuter [Ad - Analyses ad hoc sur Java 11](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html). |
| **Collecte de données :** Nouveau cookie s_ ecid | Ajout d’un cookie de serveur propriétaire, s_ecid, dans lequel la collecte de données stocke l’ECID du visiteur. |

**Correctifs d’Analysis Workspace**

* Correction d’un problème affectant le **[!UICONTROL Durée de consultation de la page]**. [!DNL Analysis Workspace]Les rapports n’utiliseront plus le nom de la page lors du calcul des intervalles de durée, ce qui permet de compter les accès granulaires et par intervalle. **[!UICONTROL ]****[!UICONTROL ]** (AN-140479)
* Correction des problèmes de performance de visualisation en ligne dans le cadre d&#39;un effort plus important pour améliorer [!DNL Analysis Workspace] les performances. (AN-174878)
* Correction du problème de l’absence de codage UTF-8 dans les fichiers .csv téléchargés. (AN-178393)
* Correction de problèmes de lenteur [!DNL Analysis Workspace] des performances du projet. (AN-177710)
* Correction des problèmes d’affichage de visualisation des lignes avec les petites plages dans la granularité de l’axe Y. (AN-176467)

**Autres correctifs d’Analytics**

* [!DNL Audience Analytics]: Correction d&#39;un problème qui survenait après modification du nom d&#39;une audience dans [!DNL Audience Manager (AAM)] : le nom mis à jour n&#39;était pas reflété dans Audience Analytics. (AN-176237)
* Correction d&#39;un problème qui empêchait les utilisateurs d&#39;enregistrer [! Segments DNL Analytics dans [!DNL Audience Manager]. Cela était dû à des dossiers AAM existants avec un mélange de noms majuscules et minuscules. Nous traitons maintenant tous les dossiers comme insensibles à la casse pour qu’ils se synchronisent. (AN-177934)
* Correction d&#39;un problème qui survenait lorsque les utilisateurs connectés [!DNL Analytics] par le biais de la [!DNL Experience Cloud] session puis expirait expiraient. Lors de la reprise de la session, l’utilisateur était redirigé vers une URL défectueuse. (AN-176812)
* Correction d&#39;un problème lié aux décalages fuseaux horaires dans [!DNL Data Warehouse] les requêtes. (AN-177585)

### Avis importants pour les administrateurs d’Analytics {#aa-notices}

| Avis | Date d’ajout    ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Changements à venir de la prise en charge des **[!UICONTROL classifications de date activé]** et **[!UICONTROL numérique 2]** | Mise à jour le 28 mai 2019 | La possibilité d&#39;importer des classifications Numérique 2 et Date-Enabled sera supprimée de la codebase de code. Cette modification prendra effet avec la version de maintenance de juillet 2019. S’il y a des colonnes numériques ou des colonnes activées par date dans le fichier d’importation, ces cellules seront ignorées et les autres données de ce fichier seront importées normalement. <br/>Les classifications existantes peuvent toujours être exportées par le biais du workflow de classification standard et sont toujours disponibles dans les rapports. |
| Modification à venir des calculs des _totaux des rapports_. | Mise à jour le 2 mai 2019 | Le **13 juin 2019**, Adobe Analytics va uniformiser les calculs des _totaux des rapports_ pour toutes les dimensions et mesures. Pour cette raison, les totaux de certains rapports seront modifiés (notamment les rapports Props ou Attributs du client). Avant cette modification, certains totaux incluaient ou excluaient la ligne _Non spécifié_ dans le total, peu importe si elle apparaissait ou non__ dans le rapport. <br/>À compter du 13 juin 2019, le poste _Non spécifié_ apparaîtra toujours dans le total du rapport, même s’il n’apparaît pas comme poste sur le rapport. En outre, les segments utilisant la logique _existe_ ou _n’existe pas_ pourront afficher des résultats différents pour certaines dimensions après ce changement. Cette modification concernera Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder et l’API Reporting. |
| Mise à jour des téléchargements CSV à partir de [!DNL Analysis Workspace] | 10 avril 2019 | Depuis le 11 avril 2019, plusieurs modifications ont été apportées aux **[!UICONTROL téléchargements CSV]** (et **[!UICONTORL Copier dans le Presse-papiers]**) pour [!DNL Analysis Workspace] supprimer la mise en forme des données exportées.  <ul><li>Le séparateur des milliers n&#39;est plus inclus. Le séparateur décimal sera toujours inclus et se conformera au format défini sous **[!UICONTROL Composants &gt; Paramètres de rapport &gt; Séparateur des milliers]**. Remarque : Les valeurs numériques qui utilisent une virgule comme séparateur décimal continuent à être placées entre guillemets dans le fichier CSV exporté.</li><li>Aucun symbole de devise ne sera affiché.</li><li>Aucun symbole de pourcentage ne sera affiché. Les pourcentages seront sous forme décimale. Par exemple, 75 % sera représenté comme 0,75.</li><li>La durée sera indiquée en secondes.</li><li>Les tableaux de cohortes affichent uniquement les valeurs brutes. Les pourcentages sont supprimés.</li><li>Si un nombre n’est pas valide, une cellule vide s’affichera.</li></ul> |
| Modification à venir de la commande [!DNL Analysis Workspace] Débogueur | 4 avril 2019 | La commande Console pour activer [!DNL Analysis Workspace] le débogueur est modifiée à adobetools. debug. includeoberonxml le **13 juin 2019**. adobe.tools.debug.includeOberonXml cessera de fonctionner après cette date. |
| Numéros de version des navigateurs mobiles | 7 février 2019 | Le niveau de troncation des numéros de version des navigateurs mobiles est modifié depuis le 8 janvier 2019 (de 2 à 1). Depuis lors, seuls les deux premiers niveaux des versions sont affichés (par ex. _Firefox 64.0.2_ apparaît désormais sous la forme _Firefox 64.0_). |
| Fin de vie pour [!DNL Ad Hoc Analysis] | 29 janvier 2019 | Le 6 août 2018, Adobe a annoncé l&#39;intention de fin de vie [!DNL Ad Hoc Analysis]. dont la date sera communiquée dès que possible.<br/>Pour plus d’informations, notamment sur les versions de Java compatibles durant cette période, voir [Découvrir Workspace](https://adobe.ly/discoverworkspace). |
| Liens de rapports Analytics courts | 14 janvier 2019 | Tout lien de rapport Analytics court qui n’aura pas été consulté pendant un an sera supprimé à compter du 17 janvier 2019, selon un calendrier progressif. |
| Fin de la prise en charge de TLS 1.0 | Mis à jour le 10 janvier 2019 | À compter du 11 février 2019, la création de rapports Adobe Analytics ne prendra plus en charge le chiffrement TLS 1.0 (Transport Layer Security – Sécurité de la couche de transport). Ce changement entre dans le cadre de nos efforts continus pour conserver des normes de sécurité élevées et promouvoir la sécurité des données des clients. Si vous ne parvenez pas à vous connecter à la création de rapports Adobe Analytics après le 11 février 2019, vous devez mettre à niveau votre navigateur vers la [dernière version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> À compter du 20 février 2019, la collecte de données Adobe Analytics ne prendra plus en charge le protocole TLS 1.0. À la suite de cette modification, Adobe ne collectera plus les données Analytics des utilisateurs finaux disposant d’appareils ou de navigateurs web plus anciens qui ne prennent pas en charge le protocole TLS 1.1 ou version ultérieure. Cette modification ne devrait pas avoir de répercussions importantes sur les données des clients ou le compte rendu des performances. (Si votre site Internet ne prend pas en charge TLS 1.0, vous ne serez pas concerné.) <br/>À compter du 11 avril 2019, l’API de création de rapports d’Adobe Analytics ne prendra plus en charge le chiffrement TLS 1.0. Les clients qui accèdent à l’API doivent vérifier qu’ils ne seront pas affectés. <ul><li>Les clients API utilisant Java 7 avec les paramètres par défaut devront être [modifiés pour prendre en charge TLS 1.2 ](https://www.java.com/en/configure_crypto.html). (Reportez-vous à la section _Modification de la version par défaut du protocole TLS pour les points de terminaison clients : TLS 1.0 à TLS 1.2_). </li><li>Les clients API utilisant Java 8 ne doivent pas être affectés, car le paramètre par défaut est TLS 1.2.</li><li> Les clients API utilisant d’autres structures devront contacter leurs fournisseurs pour plus de détails sur la prise en charge de TLS 1.2.</li></ul> |
| Flux de données : colonne post_product_list – modification de taille | 9 janvier 2019 | Le 7 février 2019, Adobe prévoit d’étendre la taille de la colonne post_product_list de 64 Ko à 16 Mo. Cette modification garantit que les valeurs evar de marchandisage ajoutées à post_ product_ list durant le traitement ne provoquent pas la troncature des valeurs de produit et de chiffre d&#39;affaires. Si certains de vos processus assimilent des valeurs post_product_list, assurez-vous qu’ils peuvent gérer des valeurs allant jusqu’à 16 Mo en longueur ou entraîneront une troncature des valeurs à 16 Ko afin d’éviter les problèmes d’assimilation de données. |
| Modifications de gestion affectant [!DNL Analytics Live Stream] les points de fin inactifs | 20 décembre 2018 | À compter du 1 er février 2019, [!DNL Live Stream] il est possible que les endpoints de fin sans connexion utilisateur active pendant 90 jours soient désactivés. Vous pouvez contacter le service d&#39;assistance clientèle pour examiner les [!DNL Live Stream] points de fin et, le cas échéant, les réactiver. De plus, veuillez vous assurer que vos processus client maintiennent une connexion permanente, comme prévu par la configuration du service, et qu’ils sont mis en œuvre pour se reconnecter lorsque la connexion est désactivée ou interrompue. |
| Mise à jour d’Adobe [!DNL Report Builder] en raison de la fin de la prise en charge du protocole TLS 1.0 | 7 septembre 2018 | En raison de la fin de la prise en charge de TLS 1.0, nous recommandons [!DNL Report Builder] aux utilisateurs de télécharger la version v 5.6.21 avant février 2019. Après cette date, les versions précédentes de [!DNL Report Builder] ne fonctionneront plus. |

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

* Target Standard et Target Premium
* Recommendations Classic


## Magento {#magento}

Magento est une plateforme de commerce électronique qui fournit aux marchands en ligne un système de panier souple et un contrôle sur l’aspect, le contenu et les fonctionnalités de leur boutique en ligne. Magento est disponible dans une version open source et dans une version commerce intégrale.

Magento Commerce fait partie d’Adobe Commerce Cloud et offre une solution d’e-commerce avec une puissance d’entreprise, une évolutivité illimitée et une flexibilité open source pour les expériences B2C et B2B.

Vous trouverez les notes de mise à jour des éditions Open Source et Commerce [sur](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) la page Informations sur la version.

## Primetime {#primetime}

Adobe Primetime est une plateforme télévisée multi-écran grâce à laquelle les entreprises multimédias peuvent créer et rentabiliser des contenus personnalisés et attrayants.

[Notes de mise à jour de Primetime](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Accueil de l’aide de Primetime](http://help.adobe.com/en_US/primetime/)
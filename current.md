---
title: Notes de mise à jour d’Adobe Experience Cloud
description: Notes de mise à jour de juin 2019
doc-type: notes de mise à jour
last-update: Juin 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 1055e2ece605b5c1147f92cfd06cf103860e3d4c

---


# Accès anticipé - Notes de mise à jour d&#39;Adobe Experience Cloud

Nouvelles fonctionnalités et correctifs d’Adobe Experience Cloud.

>[!IMPORTANT]
>Cette page comporte du contenu publié avant la date de publication et peut faire l’objet de modifications avant la publication planifiée.

>[!NOTE]
>Inscrivez-vous aux [Mises à jour produit prioritaires d’Adobe](https://www.adobe.com/subscription/priority-product-update.html) afin de recevoir une notification par courrier électronique concernant les prochaines mises à jour. Vous recevrez une notification trois à cinq jours ouvrables avant la sortie de la mise à jour. Les informations communiquées après la mise à jour seront estampillées avec la date de publication.

**Date de publication : Juin 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Notes de mise à jour d&#39;Adobe Experience Platform

* Voir [Notes de mise à jour sur Platform Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) sur Adobe. io pour connaître les dernières mises à jour apportées à la plateforme Experience Platform.

### Experience Platform Launch

* Voir [Lancement de plateforme Experience](https://docs.adobelaunch.com/) pour obtenir les informations les plus récentes.

## Analytics {#analytics}

Nouvelles fonctionnalités et correctifs d’Adobe Analytics:

* [Nouvelles fonctionnalités et correctifs d’Adobe Analytics](#aa-features)
* [Avis importants pour les administrateurs d’Analytics](#aa-notices)

Pour obtenir la documentation du produit, voir la [page d’accueil de l’aide d’Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Nouvelles fonctionnalités et correctifs d’Adobe Analytics {#aa-features}

| Fonction | Description |
| -----------| ---------- |  
| **Segmentation** | Nouveaux modèles d&#39;attribution pour les dimensions de la segmentation :<ul><li>Répétition (par défaut) : Inclut des instances + valeurs persistantes pour la dimension.</li><li>Instance : Inclut des instances pour la dimension.</li><li>Instance non répétée : Inclut des instances uniques (non répétées) pour la dimension.</li></ul> |
| **Segmentation** | Nouveaux opérateurs de segments : **[!UICONTROL Est égal à N&#39;importe lequel des éléments]** et **[!UICONTROL N&#39;est pas égal à]**. |
| **Débogueur** | Lorsque vous êtes connecté avec votre Adobe ID, vous avez désormais la possibilité de récupérer les accès post-traités dans le débogueur Experience Cloud. Les accès post-traités sont des appels serveur après qu&#39;ils ont été passés par [!UICONTROL les règles de traitement] et les règles VISTA, ce qui vous permet de valider [!UICONTROL les règles] de traitement et vos règles VISTA. **Remarque**: Si vous utilisez A 4 T (supplementaldataid), les données post-traitement peuvent prendre quelques minutes pour revenir. |
| **Analysis Workspace:** | Ajout de nouveaux filtres prêts à l&#39;emploi dans la recherche de rail gauche. Outre ce que vous voyez aujourd&#39;hui (dimensions, mesures, approuvés, etc.), nouveaux filtres tels que Mesures calculées, Attributs du client, evars, Props, Vidéo, etc. ont été ajoutés afin de faciliter la recherche des composants dont vous avez besoin. |
| **Analysis Workspace** | Nous avons ajouté un avertissement à la visualisation Abandons qui s&#39;affichera lorsque vous ajouterez un segment comme touchpoint de contact : certaines combinaisons de conteneur de segments non valides généraient des diagrammes d&#39;abandons non valides, tels que <ul><li>Utilisation d&#39;un segment basé sur les visiteurs comme touchpoint de contact dans une visualisation Abandons du visiteur</li><li>Utilisation d&#39;un segment basé sur les visiteurs comme touchpoint de contact dans une visualisation Abandons de la visite</li><li>Utilisation d&#39;un segment basé sur les visites comme touchpoint de contact dans une visualisation Abandons de la visite</li></ul> <br> [Plus...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/fallout/compare-segments-fallout.html)</br> |

**Correctifs d’Analysis Workspace**

* Correction d&#39;un problème lié aux informations de date japonaise localisées dans [!DNL Analysis Workspace] les visualisations. (AN-180114)
* Correction d&#39;un problème survenant après la copie et le collage d&#39;éléments de dimension. Les recherches suivantes sur l&#39;élément provoquaient une erreur. (AN-177394)
* Correction d&#39;un problème en raison duquel l&#39;option de modification manquait dans les panneaux de segments des tableaux à structure libre. (AN-171703)
* Correction d&#39;un problème en raison **[!UICONTROL duquel la fonction Définir comme page]** d&#39;entrée ne fonctionnait pas lorsqu&#39;elle était partagée avec un grand ensemble de destinataires. (AN-163922)
* Correction d&#39;un problème en raison duquel les chaînes étaient coupées verticalement dans les rapports en temps réel. (AN-175980)

**Autres correctifs d’Analytics**

* Correction d&#39;un problème en raison duquel les utilisateurs administrateurs ne pouvaient pas activer **[!UICONTROL les événements de réussite]**. (AN-176689)
* Correction d&#39;un problème survenant lors de la création d&#39;une alerte avec **[!UICONTROL la mesure Taux]** de sortie. (AN-177476)

### Avis importants pour les administrateurs d’Analytics {#aa-notices}

| Avis | Date d’ajout    ou de mise à jour | Description |
| -----------| ---------- | ---------- |
| Limites du créateur de règles de classification | Ajouté le 5 juin 2019 | Ces limites ne sont pas nouvelles, mais ont été ajoutées à la documentation [ici](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Nouvelles limites d&#39;opérateur de segment | Ajouté le 31 mai 2019 | À compter du 18 juillet 2019, les opérateurs de segment « contient l&#39;un des », « ne contient pas », « contient tous » et « ne contient pas tous » seront limités à 100 mots par champ de saisie. La limite sera appliquée à tous les segments nouveaux et modifiés après cette date. Les segments existants qui dépassent la limite continueront à être pris en charge, mais ne peuvent pas être modifiés ou enregistrés tant que le champ de saisie n&#39;est pas réduit. Ces limites sont appliquées dans le cadre d&#39;efforts continus visant à améliorer les performances de la requête. |
| Changements à venir de la prise en charge des **[!UICONTROL classifications de date activé]** et **[!UICONTROL numérique 2]** | Mise à jour le 28 mai 2019 | La possibilité d’importer des classifications numériques 2 et des classifications activées par date a été supprimée du code base. Cette modification prendra effet avec la version de maintenance de juillet 2019. S’il y a des colonnes numériques ou des colonnes activées par date dans le fichier d’importation, ces cellules seront ignorées et les autres données de ce fichier seront importées normalement. <br/>Les classifications existantes peuvent toujours être exportées par le biais du workflow de classification standard et sont toujours disponibles dans les rapports. |
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

**Correctifs, améliorations et obsolescences**

* Audience Manager comptabilise désormais uniquement les modèles algorithmiques actifs par rapport à la limite d&#39;utilisation.
* Correction d&#39;un problème qui entraînait l&#39;affichage de la portée du modèle algorithmique pour les caractéristiques qui utilisent le modèle correspondant.
* Correction d&#39;un problème en raison duquel le contenu des dossiers de caractéristiques n&#39;était pas affiché, alors les noms des dossiers contenaient des parenthèses et/ou des crochets.
* Correction d&#39;un problème en raison duquel le tri des caractéristiques échouait lors de la sélection d&#39;un seul type de caractéristique.
* Correction d&#39;un problème en raison duquel l&#39;arborescence du dossier de caractéristiques se repliait sur la vue [!UICONTROL Toutes les caractéristiques] chaque fois que vous aviez créé ou mis à jour un nouveau sous-dossier.
* Correction d&#39;un problème en raison duquel l&#39;autorisation VIEW_ DATASOURCES était nécessaire lorsque vous tentiez de supprimer un partenaire.
* Correction d&#39;un problème en raison duquel la zone [!UICONTROL de recherche] de [!UICONTROL la] page Segments était recherchée dans tous les dossiers au lieu de celui sélectionné.
* Correction d&#39;un problème qui empêchait le tri du [!UICONTROL tableau Exclure les caractéristiques] par le biais des commandes d&#39;en-tête lors de la création d&#39;un modèle algorithmique.
* Correction d&#39;un problème qui entraînait le blocage d&#39;Audience Manager lors de l&#39;exécution d&#39;un rapport avec des dates d&#39;intervalle vides.

## Experience Manager {#aem}

Nouvelles fonctionnalités, correctifs et mises à jour Adobe Experience Manager (AEM). Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

### Versions de produit

**Cloud Manager 2019.5.0**

La dernière version de Cloud Manager (2019.5.0) ne contient pas de modifications fonctionnelles significatives, bien qu&#39;elle fournisse quelques correctifs.

* [Notes de mise à jour de Cloud Manager 2019.5.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**Documentation XML pour AEM**

La version 3.3 de la solution de documentation XML est désormais disponible. Reportez-vous aux notes de mise à jour suivantes :

***Fonctionnalités de mappage avancées***
* Ajoutez des références de rubrique à l&#39;aide de la fonction Glisser-déposer depuis la vue du référentiel ou à l&#39;aide de la barre horizontale et du catalogue d&#39;éléments.
* Ajoutez des métadonnées sur une référence de rubrique, un bloc, comme le titre de la navigation, le format, la portée, etc.
* Cliquer sur la référence de rubrique doit ouvrir la rubrique dans l&#39;éditeur (mode d&#39;aperçu s&#39;il n&#39;est pas extrait et désactiver la modification avec le paiement activé).
* Ajouter un chef de rubrique et un groupe de rubriques.
* Ajout de tableaux d&#39;ouvrage avec un point de départ (rubriques, préface, liste de livres, avis, etc.) et Backmatter (Rubriques, Appendices, Glossaire, etc.).
* En mode Création, les liens rompus sont mis en surbrillance, les chemins de navigation sont affichés et la vue complète des balises est disponible.
* Possibilité de définir des attributs de niveau de mappage.
* Possibilité de définir Title/booktitle.
* Prise en charge de Reltables avec la possibilité d&#39;ajouter un en-tête rel, des colonnes, des rubriques glisser/déposer à partir de la carte et du référentiel dans le tableau rel, de définir la liaison, la portée et d&#39;autres paramètres pour les liens, de réorganiser les liens dans la cellule.
* Barre d&#39;outils à insérer avant, insérer après et insérer un élément.
* Mettez en surbrillance si une condition est appliquée sur une rubrique.
* Possibilité de modifier plusieurs zones à la fois (chaque mappage s&#39;ouvre sous la forme d&#39;un onglet dans le même navigateur).
* Dans le panneau de mappage et la vue du référentiel, au survol, affichez le titre complet de la rubrique et le fichier - nom.

***Affichage des balises complètes***

* Insérez de nouvelles balises entre deux éléments.
* Copier et coller des balises.
* Faites glisser des balises à des emplacements autorisés et non autorisés dans un fichier.
* Développez et réduisez les balises.

***Améliorations de la recherche spécifique à DITA***

* Fourniture d&#39;un outil de sérialisation pour réindexer le contenu sélectionné
* Les utilisateurs peuvent utiliser `contains` et `exact match` dans leur recherche. Ils peuvent également effectuer des recherches à l&#39;aide des paramètres suivants. :
   * Métadonnées de la ressource. Par exemple, `file name`ou `title`toute métadonnée personnalisée définie par le client.
   * Nom d&#39;attribut DITA et sa valeur. Par exemple `platform=winOS`.
   * Nom de l&#39;élément DITA et sa valeur. Par exemple `author = Joe Smith`.
   * Nom de l&#39;élément DITA et son attribut appliqué. Par exemple, tableau avec une paire nom/valeur d&#39;attribut product = spacebase qui lui est appliquée.
   * Rubrique DITA et métadonnées de mappage.
   * Type d&#39;informations DITA. Pour l&#39;examen [ple, carte, rubrique, concept, etc.
   * Chemin racine du dossier où se trouve le fichier.
   * Etat du document.
   * État d&#39;extraction.
   * Modification de la plage de dates.
   * Balises CQ.
* Il est possible de créer des requêtes complexes en combinant un ou plusieurs des paramètres de recherche ci-dessus.

***Modifications des fonctionnalités de révision***

* Conseils pour un réviseur :
   * Importez tous les commentaires et incorporez les modifications pour les révisions permanentes avant de procéder à la mise à niveau vers la version 3.3.
   * Assurez-vous que plusieurs onglets ne sont pas ouverts pour l&#39;éditeur.
   * Assurez-vous que la vue Balises complètes n&#39;est pas activée.
   * Ne permutez pas entre le mode Auteur et le mode Source pendant que la révision est en cours.
* Capacité à spécifier la version de mon contenu qui doit être révisée.
* Possibilité de choisir les versions des rubriques sélectionnées en fonction d&#39;une ligne de base, d&#39;une date, d&#39;une étiquette ou d&#39;une version active actuellement - ou de spécifier les versions pour chacune des rubriques lors de la création d&#39;une révision.
* Possibilité d&#39;envoyer la même rubrique/mappage pour révision plusieurs fois et l&#39;auteur peut accéder à toutes les révisions dans le panneau de révision de l&#39;éditeur.
* En tant qu&#39;initiateur, il est possible de transmettre une version ultérieure du contenu pour les réviseurs. Les réviseurs reçoivent une notification lorsqu&#39;un nouveau contenu est publié pour révision.
* En tant qu&#39;auteur, l&#39;utilisateur peut voir les commentaires de révision pour toutes les versions de son contenu dans le panneau de révision de l&#39;éditeur. Les auteurs pourront filtrer les commentaires par numéro de version.
* En tant qu&#39;utilisateur d&#39;auteur, vous pouvez afficher et importer des commentaires sur une ancienne version du contenu dans l&#39;éditeur qui était en cours de révision.

***Divers***

* Créez un dossier, une rubrique ou une carte dans la vue Référentiel.
* Afficher dans l&#39;interface utilisateur des ressources : ajoutez une option de menu pour les dossiers et les rubriques - « Afficher dans l&#39;interface utilisateur des ressources ». Cette option ouvre l&#39;interface utilisateur Ressources dans laquelle l&#39;utilisateur peut voir l&#39;arborescence de contenu à gauche et tous les fichiers en mode Liste à droite, avec tous les menus de ressources en haut.
* Un tableau de bord Révision est désormais disponible sous forme de mosaïque sur le projet DITA qui effectue le suivi de la révision au niveau d&#39;un réviseur et d&#39;un niveau de tâche de révision.
* Ajout de la capacité de convertir IDML en DITA.
* Fournissez une API pour appliquer une étiquette donnée sur toutes les versions spécifiées dans une ligne de base.
* Activez un événement après la fin de la conversion XHTML/DOCX vers DITA. Vous pouvez utiliser cet événement pour ajouter des attributs spécialisés au contenu converti ou pour toute autre logique personnalisée que vous devez implémenter.
* Améliorations de l&#39;onglet Performances de ligne de base. L&#39;utilisateur doit d&#39;abord exécuter un script sur tous les bases existantes.
* Des améliorations ont été apportées au conversion XHTML vers DITA.
* Déchargement DITA-OT pour l&#39;optimisation de publication.
* Correction du tri dans la colonne Type en mode Liste.
* Possibilité de gérer désormais les styles en cascade dans Word vers la conversion DITA.

### Communauté

**[Série webinaire de Cloud Manager Manager Builder](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

Vous souhaitez savoir comment les processus devops peuvent simplifier les activités quotidiennes de la gestion d&#39;Adobe Experience Manager dans le cloud ? Cloud Manager fournit la première fonctionnalité de la fonctionnalité cloud-native pour Adobe Experience Manager qui active la souplesse du cloud, que votre organisation commence sa transformation devops ou recherche des stratégies pour étendre les processus devops existants.

[Cette série](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)mensuelle vous explique comment démarrer et utiliser les fonctionnalités de Cloud Manager pour simplifier la gestion d&#39;Adobe Experience Manager dans le cloud.

Vous découvrirez les éléments suivants :
* Initiation à Cloud Manager et configuration du canal CI/CD
* Fonctionnement de la mise à l&#39;échelle automatique et de la diffusion transparente des services et possibilité de simplifier la gestion de l&#39;environnement d&#39;Adobe Experience Manager dans le cloud
* Utilisation de l&#39;API Cloud Manager et intégration des processus devops existants

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

### Version du printemps 19.1 de Campaign Classic

| Fonction | Description |
| ------------- | ----------- |
| Panneau de contrôle | Pour accroître l&#39;efficacité de votre travail en tant qu&#39;utilisateur administrateur, gérez les paramètres de vos serveurs SFTP en contrôlant le stockage, les adresses IP en liste blanche et l&#39;installation des clés SSH pour chaque instance. Notez que le Panneau de configuration n&#39;est disponible que pour les clients hébergés sur AWS à partir d&#39;aujourd&#39;hui. [Connectez-vous via Experience Cloud](https://experiencecloud.adobe.com/campaign/controlpanel/). <br> Pour plus d&#39;informations, consultez la documentation [détaillée](https://helpx.adobe.com/campaign/kb/control-panel.html) [et la vidéo](https://helpx.adobe.com/campaign/kt/acc/using/acc-control-panel-video-use.html). |
| Journal d&#39;audit | En tant qu&#39;administrateur, augmentez la productivité en surveillant et en gérant les modifications apportées à l&#39;instance Adobe Campaign Classic. Le journal d&#39;audit consigne les actions effectuées sur le schéma source, le processus et l&#39;option. Vous pouvez déterminer rapidement si un élément a été créé, modifié ou supprimé.<br>Pour plus d&#39;informations, consultez la documentation [détaillée](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) [et la vidéo](https://helpx.adobe.com/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html). |
| Sécurisation, robustesse et évolutivité | Une série d&#39;améliorations a été ajoutée à Campaign Classic. Les améliorations de sécurité, de robustesse et d&#39;évolutivité sont répertoriées dans [les Notes de mise à jour de Campaign Classic](https://docs.campaign.adobe.com/doc/AC/en/RN.html). |
| Messagerie SMS sécurisée (TLS) | SMS sécurisé est désormais pris en charge via le connecteur SMPP générique étendu. Cela permet une connexion chiffrée au fournisseur. <br>Pour plus d’informations, consultez la [documentation détaillée](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |
| Mise à jour de la matrice de compatibilité | Avec cette nouvelle version, Adobe Campaign prend désormais en charge les systèmes de base de données suivants. Reportez-vous à [la Matrice de compatibilité](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) <ul><li>Oracle 18 c</li><li>MySQL 5.7 (FDA)</li><li>SQL Server 2017</li><li>Teradata 16 (FDA)</li><li>Postgresql 11</li></ul> |

Voir les [Notes de mise à jour d’Adobe Campaign Classic](http://docs.campaign.adobe.com/doc/AC/en/RN.html) pour les correctifs et améliorations.

### Version de printemps 19.2 de Campaign Standard

| Fonction | Description |
| ------------- | ----------- |
| Panneau de contrôle | Pour accroître l&#39;efficacité de votre travail en tant qu&#39;utilisateur administrateur, vous pouvez facilement surveiller la capacité et gérer les paramètres de vos instances (à partir de la gestion des serveurs SFTP). <br> Pour plus d&#39;informations, consultez la documentation [détaillée](https://helpx.adobe.com/campaign/kb/control-panel.html) [et la vidéo](https://helpx.adobe.com/campaign/kt/acs/using/acs-control-panel-video-use.html). |
| Notifications locales | La messagerie locale vous permet d&#39;informer vos utilisateurs lorsque de nouvelles données sont disponibles dans leurs applications mobiles, même sans avoir accès à Internet ou à l&#39;application mobile s&#39;exécutant en premier plan. Les notifications locales sont déclenchées par une application mobile sur une heure donnée et selon un événement.<br>Pour plus d’informations, consultez la [documentation détaillée](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type). |
| Amélioration du flux de travail : ajout d&#39;une charge utile à l&#39;activité des signaux externes | Démarrez un processus avec une charge utile lorsque des conditions définies sont satisfaites à partir d&#39;un autre flux de travail ou d&#39;un appel d&#39;API REST à intégrer à vos systèmes externes. Cela inclut également une nouvelle activité de test dans laquelle vous pouvez exécuter des tests sur cette fonctionnalité. <br>Pour plus d&#39;informations, consultez la documentation [détaillée](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) [et la vidéo](https://helpx.adobe.com/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html). |
| Amélioration des pages d&#39;entrée - Google recaptcha | Tirez parti de Google recaptcha pour empêcher les messages indésirables sur vos pages d&#39;entrée sans nécessiter d&#39;intervention de vos clients. <br>Pour plus d’informations, consultez la [documentation détaillée](https://helpx.adobe.com/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha). |

Pour consulter la documentation du produit, voir :

* Adobe Campaign Standard : [Documentation](https://helpx.adobe.com/support/campaign/standard.html) – [Notes de mise à jour](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) – [Vidéos de présentation](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic : [Documentation](https://helpx.adobe.com/support/campaign/classic.html) – [Notes de mise à jour](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Vidéos de présentation](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* TLS 1.0 a été désactivé sur tous les serveurs Adobe. Pour que les périphériques Android 4. x se connectent aux services Adobe via SSL, le SDK force désormais TLS 1.1/TLS 1.2 lors de la création d&#39;une liaison.

## Advertising Cloud {#adcloud}

Mise à jour : 5 juin 2019 pour la version du 8 juin

| Produit | Fonction | Description |
| -----------| ---------- | ----------  |
| Rechercher des campagnes, des classifications d&#39;étiquettes et des contraintes | Raccourcis clavier | Vous pouvez maintenant utiliser <b>les touches Maj + clic</b> pour sélectionner plusieurs rangées consécutives et <b>Ctrl + clic</b> pour sélectionner plusieurs lignes non consécutives. |
|  | Sélectionner tout vs. Sélectionner tout sur la page | Dans les tableaux de données, lorsque vous cochez la case supérieure pour sélectionner toutes les lignes, la nouvelle valeur par défaut consiste à sélectionner toutes les lignes de la page (selon que vous visualisez 25 rangées, 50 rangées, 100 rangées, 200 lignes ou défilement continu). Vous avez toujours la possibilité de sélectionner toutes les lignes disponibles. |
| Vues par défaut, vues personnalisées et paramètres de personnalisation des colonnes autonomes | Réorganisation des colonnes | Les nouveaux boutons Haut et Bas permettent de réorganiser les colonnes. Vous pouvez toujours faire glisser des colonnes pour les réorganiser, comme vous le pouviez auparavant. |

## Target Standard/Premium 19.6.1 (25 juin 2019) {#target}

Reportez-vous aux Notes de mise à jour d’Adobe Target pour connaître les informations les plus récentes :

[Notes de mise à jour de Target (préliminaires)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Notes de mise à jour de Target (actualisées)](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

Magento est une plateforme de commerce électronique qui fournit aux marchands en ligne un système de panier souple et un contrôle sur l’aspect, le contenu et les fonctionnalités de leur boutique en ligne. Magento est disponible dans une version open source et dans une version commerce intégrale.

Magento Commerce fait partie d’Adobe Commerce Cloud et offre une solution d’e-commerce avec une puissance d’entreprise, une évolutivité illimitée et une flexibilité open source pour les expériences B2C et B2B.

Vous trouverez les notes de mise à jour des éditions Open Source et Commerce [sur](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) la page Informations sur la version.

## Primetime {#primetime}

Adobe Primetime est une plateforme télévisée multi-écran grâce à laquelle les entreprises multimédias peuvent créer et rentabiliser des contenus personnalisés et attrayants.

[Notes de mise à jour de Primetime](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Accueil de l’aide de Primetime](http://help.adobe.com/en_US/primetime/)

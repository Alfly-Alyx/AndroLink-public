# AndroLink

<p align="center">
  <img src="assets/AndroLink-Workstation.png" alt="Un téléphone relié à un ordinateur avec AndroLink" width="420">
</p>

**Retrouvez votre téléphone sur votre ordinateur, avec des habitudes que vous connaissez déjà.**

AndroLink vous permet de parcourir les fichiers de votre téléphone, retrouver vos photos, gérer vos contacts et vos SMS, créer des sauvegardes et préparer un changement de téléphone, depuis une seule application.

C’est un projet personnel et indépendant, édité par **Alfly-Alyx**, conçu pour être accessible sans être spécialiste en informatique.

[**Télécharger la dernière version**](https://github.com/Alfly-Alyx/AndroLink-public/releases/latest) · [Toutes les versions](https://github.com/Alfly-Alyx/AndroLink-public/releases) · [English](#english)

## Un explorateur familier pour votre téléphone

L’explorateur intégré reprend les repères de l’Explorateur Windows : dossiers, barre d’adresse, retour au dossier précédent, affichage en liste ou en icônes, menus au clic droit, sélection multiple et raccourcis clavier.

Vous parcourez les dossiers accessibles **du téléphone connecté**. Vous pouvez y ranger vos fichiers et choisir ceux que vous souhaitez copier vers l’ordinateur. Pour envoyer des fichiers dans l’autre sens, vous les sélectionnez sur le PC ou utilisez le glisser-déposer.

## Votre téléphone et votre PC communiquent directement

Les échanges avec le téléphone passent par un câble USB ou, lorsque le téléphone le permet et que vous l’avez autorisé, par votre réseau local. Vos fichiers, photos, contacts et SMS ne passent pas par un serveur de stockage ou de transfert AndroLink.

**Aucun compte AndroLink à créer. Aucun espace cloud AndroLink à utiliser.** La gestion du téléphone et la recherche photo locale n’exigent pas de connexion Internet une fois les composants nécessaires installés.

### Quand Internet est-il utilisé ?

AndroLink peut utiliser Internet pour vérifier ou télécharger une mise à jour, trouver une illustration du modèle de votre téléphone, consulter les informations sur les systèmes alternatifs ou récupérer un composant nécessaire qui manque dans l’installation.

Les retours et les rapports de diagnostic utilisent également un service en ligne. Un rapport d’erreur vous est présenté avant envoi, sauf si vous avez activé l’envoi automatique, désactivé par défaut. Lorsqu’une installation Linux mobile doit récupérer des composants manquants, leurs noms peuvent être signalés automatiquement au service de retour. Cela ne transfère pas vos photos, contacts ou SMS.

### Que reste-t-il sur l’ordinateur ?

- **Vos sauvegardes :** les données personnelles sauvegardées et le catalogue des sauvegardes sont chiffrés. Sous Windows, leur protection est liée à votre compte utilisateur.
- **Les fichiers que vous choisissez de copier ou d’exporter :** ils sont enregistrés dans le dossier que vous indiquez. Ces copies ordinaires ne sont pas automatiquement chiffrées par AndroLink. Les fichiers d’installation d’applications conservés dans les sauvegardes restent eux aussi des fichiers ordinaires.
- **Les données de fonctionnement :** vos réglages, des illustrations de modèles de téléphone, les mises à jour téléchargées et les rapports de diagnostic conservés localement.
- **Certaines copies temporaires :** le glisser-déposer vers Windows et certains aperçus peuvent déposer des fichiers en clair sur le PC. Leur nettoyage est prévu, mais AndroLink ne promet pas une absence totale de traces.

Si vous choisissez un dossier synchronisé par OneDrive, Dropbox ou un autre logiciel, ce logiciel peut envoyer les copies dans son propre cloud. Cette synchronisation est indépendante d’AndroLink.

### Et la recherche photo ?

L’analyse des photos s’effectue sur le PC avec un moteur isolé qui n’a pas accès à Internet. Elle n’envoie pas les photos à une intelligence artificielle en ligne.

Les informations qui permettent de retrouver les photos sont conservées dans un **index chiffré**, sur le téléphone lorsque son compagnon le permet. Sinon, AndroLink conserve cet index chiffré sur le PC. Cet index n’est pas une copie de la photothèque. Le compagnon peut aussi conserver les réglages et les informations nécessaires à ses autres fonctions : son stockage ne se limite donc pas à l’index photo.

### Vous gardez la main sur les accès

Le téléphone vous demande les autorisations nécessaires. Dans le compagnon Android, **Révoquer les accès** vous conduit aux réglages du téléphone pour retirer les autorisations de contacts, SMS ou notifications. Pour retirer l’accès du PC au téléphone, utilisez aussi les réglages de connexion du téléphone ; si le Wi-Fi est autorisé, débrancher le câble ne suffit pas nécessairement.

La recherche photo peut être désactivée dans AndroLink. **AndroLink Remote** contrôle le téléphone depuis le PC connecté : ce n’est pas un service de prise en main à travers Internet. Ces protections ne rendent cependant pas un ordinateur ou un téléphone compromis invulnérable.

## Ce que vous pouvez faire avec AndroLink

Les fonctions disponibles dépendent du téléphone, de son système et des autorisations accordées. AndroLink indique ce qui est accessible sur l’appareil connecté.

### Fichiers, photos et vidéos

- Parcourir les dossiers, trier leur contenu et rechercher des fichiers par nom, y compris dans les sous-dossiers.
- Créer des dossiers, renommer, copier, déplacer ou supprimer les éléments sélectionnés.
- Copier des fichiers entre le PC et le téléphone, avec glisser-déposer, raccourcis clavier et sélection multiple.
- Suivre les copies, les mettre en file d’attente, les annuler et choisir quoi faire lorsqu’un fichier existe déjà.
- Voir les miniatures et les aperçus des photos ; classer les photos et vidéos par nom, date ou type.
- Retrouver des photos par leur contenu avec des mots-clés courants en **français et en anglais**. L’allemand et l’espagnol sont en préparation pour la version 0.8.17.
- Identifier l’espace occupé et nettoyer les caches accessibles, les fichiers temporaires, les corbeilles et les anciens fichiers d’installation, selon ce que le téléphone autorise.

### Contacts

- Consulter, créer, modifier et supprimer des contacts, avec plusieurs numéros, adresses, e-mails, photos et autres informations.
- Modifier plusieurs fiches à la fois et repérer puis fusionner les doublons après confirmation.
- Importer ou exporter des contacts au format vCard.
- Importer un tableau Excel ou CSV, choisir les colonnes et vérifier les fiches avant leur ajout.
- Exporter un tableau Excel personnalisé, avec les colonnes, photos et options de présentation choisies.
- Sauvegarder et restaurer le carnet d’adresses.

### SMS et notifications

- Lire les SMS en conversations ou en liste, rechercher un message et rédiger un SMS depuis le PC.
- Exporter les messages en texte, sauvegarder une sélection ou des conversations entières, puis les restaurer.
- Supprimer des SMS après confirmation et avec les autorisations demandées par Android.
- Consulter les notifications compatibles et utiliser les actions proposées par le téléphone, y compris répondre lorsque cette action est disponible.

Les MMS et les conversations RCS ne sont pas pris en charge. L’envoi d’un SMS utilise la carte SIM du téléphone et reste soumis à votre forfait mobile.

### Applications

- Retrouver les applications installées, leur version, leur origine et leur taille lorsqu’elles sont disponibles.
- Installer des applications, les activer, les désactiver ou les désinstaller selon les possibilités du système.
- Sauvegarder les fichiers d’installation Android, puis réinstaller les applications choisies.
- Sur les téléphones Linux compatibles, consulter les applications et utiliser les méthodes d’installation proposées pour le système détecté.

La sauvegarde d’une application Android ne comprend pas ses données privées : une progression de jeu ou une connexion à un compte ne sont pas automatiquement restaurées.

### Sauvegardes et changement de téléphone

- Créer et retrouver des sauvegardes locales de contacts, SMS, applications et données accessibles.
- Vérifier leur intégrité, consulter leur contenu et choisir les éléments à restaurer.
- Préparer un transfert de téléphone avec les fichiers personnels, photos, vidéos et autres catégories compatibles.
- Estimer le volume et la durée du transfert, puis consulter ce qui a réussi ou demande une intervention.
- Être guidé pour reconnecter les comptes sur le nouveau téléphone, sans récupérer leurs mots de passe.

Le transfert dépend des possibilités des deux téléphones. AndroLink ne promet pas une copie intégrale de toutes les données vers n’importe quel appareil.

### Écran, sons et navigation

- Afficher et contrôler l’écran Android à la souris et au clavier avec **AndroLink Remote**, y compris les appuis longs.
- Copier ou coller volontairement entre le téléphone et le PC, sans synchronisation automatique du presse-papiers.
- Régler les volumes du multimédia, des sonneries, notifications et alarmes lorsque le téléphone le permet.
- Choisir des onglets Chrome ouverts sur Android et les ouvrir dans le navigateur du PC. Cette fonction est expérimentale ; les onglets privés ne sont pas lus.

AndroLink Remote ne transmet pas le son du téléphone.

### Informations, réglages et accompagnement

- Consulter les informations réellement communiquées par le téléphone : modèle, système, version, stockage, mémoire et processeur.
- Voir les informations disponibles sur la batterie et les indicateurs de sécurité du système.
- Être guidé pour la connexion USB ou Wi-Fi et résoudre les difficultés de reconnaissance du téléphone.
- Choisir les comportements de connexion et les réglages compatibles proposés par le téléphone.
- Consulter les comptes visibles et ouvrir les réglages du téléphone pour les gérer, sans lire les mots de passe.
- Accéder aux réglages officiels de contrôle parental, sans contourner les protections du téléphone.
- Découvrir les systèmes mobiles alternatifs et rechercher les possibilités officiellement proposées pour son appareil.
- Accéder, sur les téléphones Linux compatibles, aux outils avancés de terminal et de diagnostic.
- Choisir l’apparence disponible, la fréquence de recherche des mises à jour et retrouver une version précédente compatible.
- Envoyer une suggestion, demander de l’aide ou signaler un problème depuis le formulaire proposé dans l’application.

## Télécharger et commencer

Les versions proposées ici sont destinées à **Windows 10 et Windows 11, en 64 bits**. Chaque publication fournit un installateur qui choisit l’interface adaptée à votre Windows, ainsi que deux archives portables distinctes.

Les compagnons et les composants prévus pour les téléphones compatibles sont inclus dans la distribution. Vous n’avez pas à les rechercher séparément.

**Android 5.0 ou plus récent** est pris en charge. Des fonctions sont également proposées pour les téléphones Linux mobile compatibles, dont le Librem 5, ainsi que pour les Lumia/Windows Phone et le Nokia N9. Leur prise en charge reste partielle ou expérimentale : tous n’offrent pas les mêmes fonctions qu’Android. Les éditions PC pour macOS et Linux ne sont pas encore distribuées ici. Les iPhone et iPad ne sont pas pris en charge actuellement.

1. Téléchargez l’installateur ou l’archive portable correspondant à votre Windows.
2. Installez l’application, ou décompressez entièrement l’archive portable avant de lancer AndroLink.
3. Branchez votre téléphone avec un câble permettant le transfert de données, déverrouillez-le et suivez l’aide affichée. Sur Android, la première connexion demande d’activer le débogage USB et d’autoriser votre PC sur le téléphone.

Les exécutables ne disposent pas actuellement d’un certificat commercial de signature. Windows peut donc afficher un avertissement SmartScreen : utilisez les fichiers disponibles sur [la page officielle des versions](https://github.com/Alfly-Alyx/AndroLink-public/releases).

Ce dépôt public rassemble la présentation du logiciel et ses téléchargements. Les mentions des composants tiers sont fournies avec l’application.

---

## English

### Your phone, managed from your PC

AndroLink brings your phone’s everyday tools together on your Windows PC: files, photos, contacts, text messages, applications, backups and more. It is an independent personal project published by **Alfly-Alyx**.

Its file manager uses familiar Windows File Explorer controls to browse the storage accessible on your phone. An address bar, navigation history, search, selection, context menus and drag-and-drop help you find and organise your files using habits you already know.

Available features depend on the phone, its operating system and the permissions you grant. AndroLink uses the capabilities it actually detects.

### Direct connection and control over your data

Your phone’s files, photos, contacts and text messages travel directly between your phone and PC over USB or an authorised local network. **No AndroLink account or AndroLink cloud storage is required.** Once the necessary components are installed, managing the connected phone and using local photo search do not require an Internet connection.

AndroLink Remote lets you view and control a connected Android phone from your PC. It is intended for a direct local connection and does not provide an Internet remote-access service.

You control the permissions granted on your phone. The Android companion’s **Revoke access** button opens the phone’s settings to remove contacts, SMS or notification permissions. Removing the PC’s connection authorisation is a separate step in the phone’s connection settings. Unplugging USB may not disconnect a phone that also has an authorised Wi-Fi connection. Photo search can be disabled in AndroLink.

Some features **do use the Internet**: checking and downloading updates, obtaining missing components, downloading phone-model illustrations, consulting official operating-system resources, and sending feedback or diagnostics. Reports use an online support service. Error reports are presented before sending unless you have enabled automatic reporting, which is disabled by default. When a mobile Linux installation needs to download missing components, their names may also be reported automatically. This does not send your photos, contacts or SMS messages.

### What is stored locally

AndroLink keeps settings, cached phone-model illustrations, downloaded updates and local diagnostic reports on the PC. Files you choose to copy or export are also saved in the destination you select.

Personal-data backups and the backup catalogue are encrypted, with protection tied to your Windows user account. Ordinary exports and backed-up Android application installation files are not automatically encrypted by AndroLink.

Photo search analyses images locally on your PC with an isolated engine that has no Internet access. The photo index is encrypted on the phone when a compatible companion supports it; otherwise an encrypted index is kept on the PC. This index is not a copy of your photo library. The companion also keeps preferences and information needed by its other features.

Some previews and drag-and-drop operations can create temporary unencrypted copies on the PC. Cleanup is provided, but AndroLink cannot guarantee that no traces remain. If you save files in a folder synchronised by OneDrive, Dropbox or another application, that application may upload them to its own cloud independently of AndroLink.

Encryption and local connections do not make a compromised PC or phone invulnerable.

### What you can do

- **Browse and organise files:** search by name, including subfolders; create folders; copy, move, rename and delete items; use drag-and-drop and familiar shortcuts; inspect properties; queue transfers, follow progress, handle existing files and cancel operations.
- **Find photos and videos:** browse thumbnails and photo previews, sort by name, date or type, and search photo content with common French and English keywords. German and Spanish are being prepared for version 0.8.17.
- **Manage storage:** inspect available space and clean accessible caches, temporary files, trash and old installation files, according to the phone’s permissions.
- **Manage contacts:** create and edit contact details and photos, change several contacts at once, detect and merge duplicates after confirmation, import and export vCard, preview Excel and CSV imports, customise Excel exports, and back up or restore contacts.
- **Handle SMS and notifications:** read conversations or chronological lists, search and send standard SMS messages, export messages as text, back up and restore selected messages or conversations, and delete messages after confirmation. View supported notifications and use the actions offered by the phone. MMS and RCS are not supported; sending SMS uses the phone’s SIM and remains subject to your mobile plan.
- **Manage applications:** view installed applications, their versions, origins and available sizes; install, enable, disable or uninstall applications where permitted; back up Android installation files and reinstall selected applications. These backups do not include an application’s private data, such as game progress or signed-in accounts. Compatible Linux phones offer application management appropriate to their system.
- **Back up, restore and change phones:** create encrypted personal-data backups, check their integrity, preview their contents and choose what to restore. Prepare transfers of supported contacts, SMS, files, photos, videos and applications, estimate their size and duration, and see what succeeded. Account reconnection is guided without retrieving passwords. Coverage depends on both phones; this is not a complete backup of every application or every device.
- **Use the connected phone from your PC:** view and control Android with the mouse and keyboard, including long presses; copy and paste deliberately without automatic clipboard synchronisation; adjust supported sound volumes. AndroLink Remote does not stream audio. Experimental Chrome tab continuation opens selected Android tabs in your PC browser and excludes private browsing.
- **Understand and configure your phone:** see detected device, system, storage, memory, processor, battery and security information. Get USB and Wi-Fi help, adjust supported connection settings, view available accounts without reading passwords, and open official parental-control settings. Discover alternative mobile operating systems and official options for your phone. Advanced users can access supported Linux terminal and diagnostic tools.
- **Adjust AndroLink and get help:** choose available appearance options and update-check frequency, access compatible previous versions, and submit a suggestion, help request or problem report through the application’s feedback form.

### Download and compatibility

[**Download the latest stable release**](https://github.com/Alfly-Alyx/AndroLink-public/releases/latest)

Each Windows release includes:

- one **Windows 10/11 x64 installer** that selects the appropriate interface;
- one **Windows 10 portable archive**;
- one **Windows 11 portable archive**.

Companions and the components supplied for supported phones are bundled with AndroLink. You do not need to find them separately.

Android support starts at **Android 5.0**. Compatible mobile Linux phones, including Librem 5, as well as Lumia/Windows Phone and Nokia N9 devices also have partial or experimental support. They do not all offer the same features as Android. Desktop editions for macOS and Linux are not currently distributed here. iPhone and iPad are not currently supported.

Download the installer or fully extract the portable archive before starting AndroLink. Connect and unlock your phone, then follow the connection guide. Android’s first connection requires enabling USB debugging and authorising your PC on the phone.

Windows builds currently have no commercial code-signing certificate, so SmartScreen may display a warning. Use the downloads from [this official release page](https://github.com/Alfly-Alyx/AndroLink-public/releases).

This public repository provides the product presentation and downloads. Third-party notices are included with the application.

---

Une idée ou un souci ? Utilisez le formulaire proposé dans AndroLink, ou ouvrez un [ticket public](https://github.com/Alfly-Alyx/AndroLink-public/issues). N’y joignez pas de données personnelles.

Have a suggestion or a problem? Use AndroLink’s feedback form or open a [public issue](https://github.com/Alfly-Alyx/AndroLink-public/issues). Do not include personal data in public reports.

<sub>Android est une marque de Google LLC. Le robot Android est reproduit ou adapté à partir d’un travail créé et partagé par Google, selon la licence Creative Commons Attribution 3.0. AndroLink est un projet indépendant, sans affiliation ni approbation de Google LLC.

Android is a trademark of Google LLC. The Android robot is reproduced or adapted from work created and shared by Google under the Creative Commons Attribution 3.0 License. AndroLink is an independent project and is not affiliated with or endorsed by Google LLC.</sub>

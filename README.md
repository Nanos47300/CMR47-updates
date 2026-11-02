# CMR47 · Télécharger et mettre à jour l'application Android

**Téléchargement public : aucun compte GitHub nécessaire.**

### 📲 [Télécharger la dernière APK officielle CMR47](https://github.com/Nanos47300/CMR47-updates/releases/latest)

Ce lien est permanent et pointe vers la dernière version officiellement publiée. Les compilations debug et candidates non publiées n'y apparaissent pas.

## Première installation Android
1. Ouvrir le lien ci-dessus depuis le téléphone ou la tablette **Android**.
2. Dans **Assets**, télécharger l'unique fichier APK nommé `CMR47-v....apk`.
3. Ouvrir le fichier téléchargé et accepter les confirmations d'installation Android.
4. Démarrer CMR47.

## Mettre à jour une installation existante
1. **Ne jamais désinstaller l'ancienne application pour faire une mise à jour.** Certaines données restent uniquement sur le téléphone.
2. Dans l'application CMR47 officielle, aller dans **Infos CMR47 → Rechercher une mise à jour**.
3. Confirmer le téléchargement et l'installation lorsque la nouvelle version officielle est proposée.
4. Si l'installation est interrompue, utiliser **Reprendre l'installation** dans Infos lorsque cette option apparaît.
5. En cas d'échec, télécharger la dernière APK via le lien public ci-dessus et l'installer **par-dessus** l'application existante.

Le téléchargement et la mise à jour sont volontairement manuels : rien ne s'installe sans confirmation. Le processus officiel vérifie l'identifiant Android et la signature historique avant publication. Si Android indique une incompatibilité de signature, **ne pas désinstaller** : contacter le responsable CMR47.

## Questions fréquentes

**Un compte GitHub est-il nécessaire ?** Non, les versions officielles sont publiques. Seuls le code source et les tests privés nécessitent des accès spécifiques.

**Est-ce que le lien propose la version en développement ?** Non. Il propose la dernière APK **signée et publiée** ; les compilations Lapinou ne sont pas mises en ligne automatiquement.

**Qu'en est-il d'un iPhone ou d'un ordinateur ?** L'APK ne fonctionne que sur Android. Le portail Web CMR47 est distinct et n'est pas encore opérationnel pour le travail partagé.

**Les données sont-elles conservées ?** Une mise à jour compatible conserve normalement les données locales, mais pas une désinstallation. Les données non synchronisées peuvent être perdues en cas de changement de téléphone.

**Attention pendant les tests :** l'authentification individuelle et la synchronisation sécurisée restent en développement. Ne pas utiliser de données professionnelles confidentielles réelles dans le mode de test.

## Contrôles techniques

Le fichier `version.json` annonce uniquement la version officielle publique, son numéro de build, l'URL HTTPS et le SHA-256 de l'APK. L'application vérifie ces informations ; Android contrôle la signature à l'installation. La publication s'effectue après tests et vérifications de la signature précédente, puis actualise le manifeste **en dernier**.

Consultez le [guide court à partager aux salariés](GUIDE_INSTALLATION.md).

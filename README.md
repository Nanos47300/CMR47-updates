# CMR47 — Téléchargements publics

Ce dépôt contient uniquement les fichiers nécessaires aux mises à jour de l'application Android CMR47.

Le code source et la clé de signature restent dans le dépôt privé.

## Publication

Une version doit être signée avec la clé Android permanente. Publier son APK via une **GitHub Release publique**, calculer son empreinte SHA-256, puis actualiser `version.json` avec les informations exactes.

Ne jamais publier le fichier de signature `.jks`, des mots de passe, des photos de chantiers ou des données de salariés.

Les mises à jour sont **désactivées** tant que le manifeste ne fournit pas un APK valide. Android peut demander à l'utilisateur de confirmer l'installation.

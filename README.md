# fichier-de-d-ploiement
fichier de déploiement global pour les besoins de déploiement sur netlify afin d'éviter de le créer à chaque projet

## Utilisation 
1. Configurer les variables d'environment de netlify
2. Ajoute une variable comme suit :
   ```bash
   NETLIFY_TOML_REPO=https://github.com/mloum1/fichier-de-d-ploiement
   ```
> ⚠️ **Warning**: Il faut penser à faire le build de votre projet avant le déploiement pour obtenir le dossier **dist/browser**

AGRITECH SERVICES — APPLICATION DE FICHES D'INTERVENTION

CONTENU
- index.html : application web mobile
- manifest.webmanifest : configuration installable
- sw.js : cache hors connexion

FONCTIONS DISPONIBLES
- Fiche client et machine
- Diagnostic, travaux, essais, recommandations
- Lignes de pièces et fournitures
- Calcul main-d'oeuvre, trajet, kilomètres, frais, remise, TVA et total
- Signature tactile
- Enregistrement local dans le navigateur
- Historique, export et import de sauvegarde JSON
- Impression / enregistrement PDF depuis le navigateur

IMPORTANT — STOCKAGE
La version fournie enregistre les fiches localement sur l'appareil. Exporter régulièrement la sauvegarde JSON et la conserver dans un espace cloud (Google Drive par exemple) permet une copie externe, mais ce n'est pas une synchronisation automatique multi-appareils.
La zone Supabase est une préparation de configuration uniquement : aucune synchronisation cloud automatique n'est activée dans cette version. Pour l'activer, il faut créer un projet cloud, une authentification privée et une table sécurisée, puis intégrer le mécanisme de synchronisation.

MISE EN LIGNE
L'application doit être publiée sur une adresse HTTPS pour être installable comme PWA. GitHub Pages peut héberger gratuitement ces fichiers dans un dépôt public. Attention : ne jamais stocker de données clients sensibles dans un dépôt GitHub. Les données des fiches restent dans le navigateur ; le dépôt ne contient que le code de l'application.

INSTALLATION
1. Publier index.html, manifest.webmanifest et sw.js à la racine du dépôt GitHub.
2. Activer GitHub Pages (Settings > Pages > Deploy from a branch > main > /(root)).
3. Ouvrir l'adresse HTTPS sur Android / Chrome.
4. Menu Chrome (⋮) > Installer l'application ou Ajouter à l'écran d'accueil.

PDF
Utiliser le bouton « Générer le PDF », puis choisir « Enregistrer au format PDF » dans la fenêtre d'impression du navigateur.

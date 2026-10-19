MON SUIVI CALORIES — application web mobile

CONTENU
- index.html : application complète
- manifest.json et icônes : installation sur écran d'accueil
- sw.js : cache hors ligne après la première ouverture via HTTPS

MISE EN LIGNE POUR L'INSTALLER COMME UNE APPLICATION
Cette application doit être publiée sur une adresse HTTPS pour que le navigateur propose l'installation PWA et que le service worker fonctionne. Le fichier HTML seul ouvert depuis un fichier local ne permet pas une installation complète.

Option simple (GitHub Pages)
1. Connecte-toi/crée un compte GitHub.
2. Crée un dépôt public, par exemple mon-suivi-calories.
3. Téléverse tous les fichiers de ce dossier à la racine du dépôt.
4. Dans Settings > Pages, choisis Deploy from a branch, branche main, dossier /(root), puis Save.
5. Attends la publication et ouvre l'URL HTTPS indiquée par GitHub Pages.

Android (Chrome)
1. Ouvre l'URL HTTPS dans Chrome.
2. Menu ⋮ > « Installer l'application » ou « Ajouter à l'écran d'accueil ».
3. Confirme. L'icône Calories apparaît sur l'écran d'accueil.

iPhone (Safari)
1. Ouvre l'URL HTTPS dans Safari.
2. Appuie sur Partager.
3. Choisis « Sur l'écran d'accueil », puis Ajouter.

SAUVEGARDE
Les repas et le poids sont enregistrés localement dans le navigateur de cet appareil. Utilise « Exporter une sauvegarde » dans Objectifs & données régulièrement. Pour transférer sur un autre téléphone, importe le JSON sur l'autre appareil. Les données ne sont pas synchronisées automatiquement.

SANTÉ
Les calories et macros sont des estimations. Vu fatigue et perte de cheveux, demander un avis médical avant un régime restrictif. Ne pas prendre de fer sans avis médical.

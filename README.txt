EduCard — Cartes scolaires & identifiants
==========================================

CONTENU DU DOSSIER
-------------------
- index.html            -> l'application (fonctionne seule si tu l'ouvres en double-clic)
- manifest.json          -> fiche d'identité de l'app (nom, icône, couleurs) pour l'installation
- service-worker.js      -> permet le fonctionnement hors-ligne une fois l'app installée
- icon-192.png / icon-512.png / icon-512-maskable.png -> icônes de l'application

OUVRIR SANS INSTALLATION
-------------------------
Double-clique sur index.html : l'application fonctionne directement dans ton navigateur,
avec sauvegarde automatique de tes écoles et élèves sur cet appareil.

INSTALLER COMME VRAIE APPLICATION (PWA) — icône sur l'écran d'accueil, mode hors-ligne
-----------------------------------------------------------------------------------------
Les navigateurs n'autorisent l'installation et le mode hors-ligne QUE si les fichiers
sont servis via une adresse http(s) — pas en double-clic direct. Il faut donc héberger
ce dossier quelque part. Options simples et gratuites :

1. GitHub Pages : crée un dépôt, dépose ces fichiers, active "Pages" dans les
   paramètres du dépôt. Tu obtiens une adresse https://tonnom.github.io/... à ouvrir
   sur ton téléphone ou ordinateur, avec un bouton "Installer" / "Ajouter à l'écran
   d'accueil".
2. Netlify / Vercel (glisser-déposer le dossier sur leur site) : pareil, adresse
   https fournie automatiquement.
3. Sur ton propre serveur/hébergement web : dépose simplement ces fichiers dans un
   dossier accessible en https.

Une fois hébergé et ouvert une première fois, le navigateur proposera "Installer
l'application" ou "Ajouter à l'écran d'accueil" — l'app s'ouvrira alors comme une
app native, avec son icône EduCard.

Dis-moi si tu veux de l'aide pour héberger le dossier : je peux te guider pas à pas.

Belvédère du Domaine — Favicon Pack
=====================================

Dépose TOUT le contenu de ce dossier à la racine du site (même niveau que index.html).

Fichiers inclus :
- favicon.ico
- favicon-16.png
- favicon-32.png
- apple-touch-icon.png (180x180)
- android-chrome-192x192.png
- android-chrome-512x512.png
- mstile-150x150.png
- site.webmanifest
- browserconfig.xml
- og-belvedere-1200x630.jpg (image Open Graph pour les partages)

Le <head> de ton site doit contenir les lignes suivantes :

<link rel="icon" href="favicon.ico" sizes="any">
<link rel="icon" type="image/png" href="favicon-32.png" sizes="32x32">
<link rel="icon" type="image/png" href="favicon-16.png" sizes="16x16">
<link rel="apple-touch-icon" href="apple-touch-icon.png">
<link rel="manifest" href="site.webmanifest">
<link rel="mask-icon" href="safari-pinned-tab.svg" color="#DDB23F"> <!-- optionnel si tu ajoutes un SVG -->
<meta name="msapplication-TileColor" content="#DDB23F">
<meta name="theme-color" content="#DDB23F">

Safari pinned tab : pour une qualité parfaite, fournis un logo vectoriel (SVG/AI/PDF) et je te génèrerai un 'safari-pinned-tab.svg' monochrome.

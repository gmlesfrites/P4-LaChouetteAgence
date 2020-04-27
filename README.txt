Explications chronologiques du travail effectué

Initialisation du travail
- Récupération du dossier 'starting website' et renommage en P4_03_codeSource
- initialisation du dépôt
- création de la branche master.

Création de la branche develop
- Modifications concernant le référencement (mots-clés, meta, liens, contenus textuels et images, ...)
- Modifications concernant l'accessibilité (aria-label, taille de police, contraste, :hover:focus, ...)

Création de la branche minify
- Minification de tous les fichiers (html, css, js)
- Suppression du fichier fontawesome.css au profit du lien CDN dans l'index.html

Après première version, évolutions sur le contenu et le style
--> retour à la branche develop puis création de la branche Temp
- MAJ alternatives textuelles
- travail du logo avec l'image dans le style.css
- Utilisation Modularscale pour mise en page du texte
- Travail plus poussé des descriptions
- vérification du responsive (pas de mot coupé, pas d'élément hors écran)

Création branche Delivery :
- Photos en SVG trop lourdes, repassent en png
- Tous les scripts en bas de page avant </body>
- Gros ménage dans le fichier style.css et un peu dans le bootstrap.css (pas trop car version trop ancienne)
- ajout de lazyload (préconisation dareboost + lighthouse)
- repasse à nouveau tout en minification

Création gh-pages pour afficher le tout sur Git Pages sans écraser le master.


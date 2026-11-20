# KABORE ÉNERGIE — site web

Site vitrine responsive en HTML, CSS et JavaScript, bilingue français/anglais.

## Aperçu local
1. Décompresser l'archive.
2. Ouvrir `index.html` dans un navigateur.
3. Pour un aperçu proche d'un hébergement réel, lancer un serveur local, par exemple avec Python :
   `python -m http.server 8000`
   puis ouvrir `http://localhost:8000`.

## Déploiement
Téléverser le contenu du dossier (`index.html`, `styles.css`, `script.js`, `robots.txt`, `sitemap.xml` et `assets/`) dans le répertoire public de l'hébergeur, généralement `public_html`.
Le site peut être hébergé sur un hébergement statique ou un hébergement web classique.

## À faire avant publication
- Vérifier la disponibilité et acheter `kaboreenergie.com` ou un domaine de remplacement.
- Configurer DNS, HTTPS/SSL et redirection vers la version canonique du domaine.
- Remplacer les images d'illustration par des photos réelles autorisées de chantiers KABORE ÉNERGIE.
- Vérifier le logo officiel, les coordonnées, l'e-mail et les liens WhatsApp.
- Le formulaire prépare une demande et ouvre WhatsApp. Il n'enregistre pas les demandes sur un serveur et n'envoie pas automatiquement d'e-mail. Pour une réception fiable, intégrer un backend ou un service de formulaire, puis tester sur téléphone et ordinateur.
- Créer une adresse e-mail sur le domaine, par exemple `contact@kaboreenergie.com`, chez le fournisseur mail choisi et configurer SPF, DKIM et DMARC. Conserver l'adresse Gmail existante en parallèle pendant la transition.
- Ajouter une politique de confidentialité si des données personnelles sont collectées.
- Vérifier le contenu français et anglais, les titres SEO, les images, les performances et l'accessibilité.
- Créer et vérifier les propriétés Google Search Console, soumettre le sitemap et créer/mettre à jour la fiche d'établissement Google si applicable.
- Les certifications, références, chiffres clés, témoignages et promesses de service doivent être confirmés par l'entreprise avant affichage.

## Structure
- `index.html` : pages/sections et contenu
- `styles.css` : identité visuelle responsive
- `script.js` : changement de langue, menu mobile et demande WhatsApp
- `robots.txt` et `sitemap.xml` : base SEO (mettre à jour le domaine si nécessaire)
- `assets/images/favicon.svg` : favicon simple

Les photos distantes utilisées sur la maquette sont des illustrations temporaires provenant d'Unsplash. Elles ne doivent pas être présentées comme des réalisations de l'entreprise.

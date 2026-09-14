# Bureautique Pro — Landing page

Page de vente (landing page haute conversion) pour la formation **Bureautique Pro**
(Word, Excel & PowerPoint — maîtrise du Pack Office en 31 jours).

## Contenu

- **`index.html`** — page unique, autonome : HTML5, CSS et JavaScript inline, sans framework
  ni dépendance lourde (uniquement Google Fonts). Responsive (mobile / tablette / desktop),
  SEO (Open Graph, Twitter Card, JSON-LD), accessibilité et animations au scroll.

## Déploiement rapide

### Vercel
1. Importer ce dépôt sur [vercel.com](https://vercel.com) → **Add New Project**.
2. Vercel détecte automatiquement `index.html` et publie le site en quelques secondes.
3. Après déploiement, remplacer l'URL `canonical` et `og:url` dans le `<head>`
   par le vrai domaine.

### Autres options
Le site étant un simple fichier statique, il fonctionne aussi sur **Netlify**,
**GitHub Pages** ou tout hébergement statique.

## Personnalisation

- **Prix / offre** : rechercher `FCFA` dans `index.html`.
- **Lien de paiement** : rechercher l'URL de checkout Chariow.
- **Durée du compte à rebours** : constante `DURATION` dans le `<script>`.
- **Notifications d'achat** : tableau `buyers` dans le `<script>` (données d'exemple).

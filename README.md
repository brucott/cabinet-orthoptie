
# Cabinet d'Orthoptie - Site Web Professionnel

Ce dépôt contient le code source du site web du cabinet d'orthoptie (3 praticiennes). 
Le site est conçu pour être léger, accessible et facile à maintenir.

## 🛠 Caractéristiques Techniques
- **Langages :** HTML5 / CSS3 (Pur, sans framework).
- **Architecture :** Statique, structurée par composants (Header, Hero, Cards, Footer).
- **Accessibilité :** Optimisé pour les patients malvoyants (contrastes élevés, balises alt descriptives).
- **Responsive :** Compatible Mobile / Tablette / Desktop.

## 📁 Structure du Projet
- `index.html` : Page d'accueil et présentation.
- `articles.html` : Blog et conseils visuels (Nouveau).
- `pathologies.html` : Informations sur les troubles traités.
- `css/styles.css` : Feuille de style unique utilisant des variables CSS.
- `images/` : Ressources graphiques (Format WebP privilégié).

## 🎨 Charte Graphique (Variables CSS)
- **Bleu Primaire :** `#2c5f8d` (Sérieux & Confiance)
- **Bleu Secondaire :** `#4a9fd8`
- **Accent Vert :** `#7bc5ae` (Douceur & Santé)

## 🚀 Déploiement
Le site est destiné à être hébergé sur [Ton hébergeur actuel ou GitHub Pages].
Toute modification doit être testée localement avant d'être "pushée" sur la branche `main`.

## 🔧 Maintenance : Ajouter un article
Pour ajouter un nouvel article dans `articles.html` :
1. **Copier** le bloc `<article>` et sa `<div class="lightbox">` associée.
2. **Inverser la classe** : Si l'article précédent a la classe `article-card`, le nouveau doit avoir `article-card reverse` (et inversement).
3. **ID Unique (Crucial)** : Changer l'ID de la lightbox (ex: `lightbox-3`) dans le lien `href` de l'image ET dans l'ID de la div correspondante.
4. **Images** : Utiliser de préférence le format `.webp` pour la performance.

---
*Dernière mise à jour : 19 Mars 2026*

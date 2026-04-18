# Cabinet d'Orthoptie - Site Web Professionnel

Ce dépôt contient le code source du site web du cabinet d'orthoptie (3 praticiennes). 
Le site est conçu pour être léger, accessible et facile à maintenir.

## 🛠 Caractéristiques Techniques
- **Langages :** HTML5 / CSS3 (Pur, sans framework).
- **Architecture :** Statique, structurée par composants (Header, Hero, Cards, Footer).
- **Accessibilité :** Optimisé pour les patients malvoyants (contrastes élevés, balises alt descriptives).
- **Responsive :** Compatible Mobile / Tablette / Desktop.
- **Fonctionnalité :** Distribution de fiches conseils via téléchargement direct.

## 📁 Structure du Projet
- `index.html` : Page d'accueil et présentation.
- `ConseilsPrevention.html` : Articles et fiches de prévention.
- `pathologies.html` : Informations sur les troubles traités.
- `css/styles.css` : Feuille de style unique utilisant des variables CSS.
- `images/` : Ressources graphiques et fiches téléchargeables (Format WebP privilégié).
- `pdf/` : Tous les flyers et documents téléchargeables.  <-- AJOUTÉ

## 🎨 Charte Graphique (Variables CSS)
- **Bleu Primaire :** `#2c5f8d` (Sérieux & Confiance)
- **Bleu Secondaire :** `#4a9fd8`
- **Accent Vert :** `#7bc5ae` (Douceur & Santé)

## 🔧 Maintenance : Ajouter un article de prévention
Le système de Lightbox (agrandissement) a été remplacé par un système de **téléchargement direct** pour faciliter la diffusion des conseils aux patients.

Pour ajouter un nouvel article :
1. **Copier** le bloc `<article class="article-card">`.
2. **Alternance visuelle** : Si l'article précédent est standard, ajoutez la classe `reverse` au nouveau : `<article class="article-card reverse">`.
3. **Lien de téléchargement** :
   - Utilisez l'attribut `download` dans la balise `<a>` entourant l'image.
   - Exemple : `<a href="images/votre_fiche.webp" download="Nom_Fiche_Patient.webp">`.
4. **Format** : Privilégiez le format `.webp` pour les images du site, mais vous pouvez lier des fichiers `.pdf` dans l'attribut `href` pour une impression de meilleure qualité par les patients.

---
*Dernière mise à jour : 18 Avril 2026*
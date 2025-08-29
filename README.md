# 🌱 IvoryTech Engineering - Site Web

Un site web moderne et minimaliste pour présenter IvoryTech Engineering, une startup innovante focalisée sur la transformation de l'agriculture ivoirienne.

## 🎯 Objectif

Ce site présente IvoryTech comme une startup sérieuse et innovante, mettant en avant notre premier projet et inspirant confiance aux partenaires potentiels. Il s'agit d'une vitrine professionnelle simple mais crédible, conçue pour évoluer au fil du temps.

## ✨ Fonctionnalités

### Design & UX
- **Design moderne et minimaliste** avec une palette de couleurs professionnelles
- **Responsive design** optimisé pour tous les appareils
- **Animations fluides** et interactions utilisateur intuitives
- **Navigation fixe** avec effet de transparence au scroll

### Sections du site
1. **Accueil** - Header visuel avec phrase d'accroche et CTA
2. **Vision & Mission** - Présentation claire de notre objectif
3. **Nos Projets** - Showcase du projet en cours (structure modulable)
4. **Pourquoi IvoryTech ?** - 4 points clés pour inspirer confiance
5. **Contact** - Formulaire simple et informations de contact

### Technologies utilisées
- **HTML5** sémantique et accessible
- **CSS3** avec variables CSS et Flexbox/Grid
- **JavaScript vanilla** pour l'interactivité
- **Google Fonts** (Poppins + Inter)
- **Font Awesome** pour les icônes

## 🎨 Palette de couleurs

- **Vert foncé** (#1B4332) - Agriculture, durabilité
- **Beige/ivoire clair** (#F5F5DC) - Identité ivoirienne, sobriété  
- **Gris anthracite** (#2D2D2D) - Modernité
- **Blanc** (#FFFFFF) - Pureté, espace
- **Gris clair** (#F8F9FA) - Séparations subtiles

## 🚀 Installation et utilisation

### Prérequis
- Un navigateur web moderne
- Serveur web local (optionnel pour le développement)

### Démarrage rapide
1. Clonez ou téléchargez les fichiers du projet
2. Ouvrez `index.html` dans votre navigateur
3. Le site est prêt à l'emploi !

### Développement local
Pour un serveur de développement local :

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (si http-server est installé)
npx http-server

# Avec PHP
php -S localhost:8000
```

Puis ouvrez `http://localhost:8000` dans votre navigateur.

## 📱 Responsive Design

Le site s'adapte automatiquement à tous les écrans :
- **Desktop** : Layout en grille avec navigation horizontale
- **Tablet** : Adaptation des colonnes et espacement
- **Mobile** : Menu hamburger, layout en colonne unique

## 🔧 Personnalisation

### Modifier le contenu
- **Textes** : Éditez directement dans `index.html`
- **Couleurs** : Modifiez les variables CSS dans `:root` (fichier `styles.css`)
- **Images** : Remplacez les placeholders par vos vraies images

### Ajouter de nouveaux projets
La structure est modulable. Pour ajouter un projet :

```html
<div class="project-card">
    <div class="project-image">
        <!-- Votre image ici -->
        <div class="project-badge">Nouveau</div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Titre du projet</h3>
        <p class="project-description">Description...</p>
        <div class="project-details">
            <span class="project-category">Catégorie</span>
            <span class="project-location">Localisation</span>
        </div>
    </div>
</div>
```

### Modifier les fonctionnalités
- **JavaScript** : Éditez `script.js` pour ajouter des interactions
- **Styles** : Personnalisez `styles.css` pour modifier l'apparence
- **Formulaires** : Intégrez votre backend pour le formulaire de contact

## 📧 Formulaire de contact

Le formulaire de contact est actuellement en mode simulation. Pour l'activer :

1. **Backend simple** : Intégrez un service comme Formspree ou Netlify Forms
2. **Backend personnalisé** : Modifiez la fonction de soumission dans `script.js`
3. **Email direct** : Remplacez par un lien `mailto:` vers votre adresse

## 🌐 Déploiement

### Options de déploiement
- **Netlify** : Drag & drop des fichiers
- **Vercel** : Déploiement automatique depuis Git
- **GitHub Pages** : Hébergement gratuit pour projets open source
- **Serveur traditionnel** : Upload via FTP/SFTP

### Configuration recommandée
- Activez la compression GZIP
- Configurez le cache navigateur
- Optimisez les images (WebP, compression)
- Activez HTTPS

## 🔮 Évolutions futures

Le site est conçu pour évoluer facilement :

- **Blog/Actualités** : Section pour partager des insights du secteur
- **Portfolio de projets** : Showcase de projets terminés
- **Page "À propos"** : Histoire de l'entreprise et équipe
- **Section investisseurs** : Informations pour les partenaires financiers
- **Intégration CRM** : Gestion avancée des contacts et leads

## 📝 Structure des fichiers

```
siteweb/
├── index.html          # Page principale
├── styles.css          # Styles et design
├── script.js           # Interactivité et animations
└── README.md           # Documentation
```

## 🤝 Contribution

Ce site est conçu pour IvoryTech Engineering. Pour contribuer :

1. Respectez la charte graphique établie
2. Testez sur différents appareils
3. Maintenez l'accessibilité et la performance
4. Documentez les modifications importantes

## 📞 Support

Pour toute question ou suggestion concernant le site :
- **Email** : ivorytechengineering@gmail.com
- **LinkedIn** : [IvoryTech Engineering](https://www.linkedin.com/company/ivorytech-engineering/)
- **Facebook** : [IvoryTech Engineering](https://www.facebook.com/share/1B5UHCh9fb/?mibextid=wwXIfr)

---

**IvoryTech Engineering** - Innover pour transformer l'agriculture ivoirienne 🌱🇨🇮

---
*Site créé en 2025*

# Meet Landing Page

Une page d'accueil moderne et responsive pour l'application Meet, construite avec HTML, SCSS et JavaScript.

## 🚀 Déploiement sur GitHub Pages

Ce projet est configuré pour être déployé automatiquement sur GitHub Pages. Le site est accessible à l'adresse :
**https://mikeg404.github.io/meet-landing-page/**

### Configuration GitHub Pages

1. Allez dans les **Settings** de votre repository GitHub
2. Dans la section **Pages** (dans le menu de gauche)
3. Sélectionnez **Deploy from a branch**
4. Choisissez la branche **gh-pages** et le dossier **/(root)**
5. Cliquez sur **Save**

## 🛠️ Développement local

### Prérequis
- Node.js (version 18 ou supérieure)
- npm

### Installation
```bash
npm install
```

### Scripts disponibles

```bash
# Compiler le SCSS en CSS
npm run build

# Surveiller les changements SCSS (recompilation automatique)
npm run watch

# Démarrer un serveur de développement local
npm run dev
```

## 📁 Structure du projet

```
meet-landing-page/
├── docs/                    # Dossier de déploiement GitHub Pages
│   ├── index.html          # Page principale
│   ├── style.scss          # Styles SCSS
│   ├── style.css           # CSS compilé
│   └── assets/             # Images et ressources
├── .github/workflows/      # Configuration GitHub Actions
├── package.json            # Dépendances et scripts
└── README.md              # Documentation
```

## 🎨 Fonctionnalités

- ✅ Design responsive (mobile, tablet, desktop)
- ✅ Animations et transitions fluides
- ✅ Optimisation des images
- ✅ Accessibilité (ARIA labels, navigation clavier)
- ✅ Performance optimisée

## 🔧 Technologies utilisées

- HTML5
- SCSS/CSS3
- JavaScript (ES6+)
- GitHub Actions (déploiement automatique)

## 📱 Responsive Design

Le site s'adapte parfaitement à tous les écrans :
- **Mobile** : < 768px
- **Tablet** : 768px - 1439px  
- **Desktop** : ≥ 1440px

## 🚀 Déploiement

Le déploiement est automatique via GitHub Actions. À chaque push sur la branche `main`, le site est automatiquement mis à jour sur GitHub Pages.

---

**Challenge Frontend Mentor** - Meet Landing Page

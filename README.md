# Mon Blog - Site Statique HTML

Un blog moderne et responsive créé avec HTML5 et CSS3 pur.

## 🚀 Fonctionnalités

- **Design moderne** - Interface élégante avec dégradés et animations
- **Responsive** - S'adapte parfaitement à tous les écrans (mobile, tablette, desktop)
- **Performance** - Site statique ultra-rapide, pas de JavaScript nécessaire
- **Facile à personnaliser** - Code HTML/CSS simple et bien organisé

## 📁 Structure du projet

```
.
├── index.html              # Page d'accueil avec la liste des articles
├── about.html              # Page À propos
├── css/
│   └── style.css          # Tous les styles du site
└── posts/
    ├── premier-article.html
    ├── introduction-web.html
    └── design-moderne.html
```

## 🌐 Utilisation

### Option 1 : Ouvrir directement dans le navigateur
Double-cliquez sur `index.html` pour ouvrir le site dans votre navigateur.

### Option 2 : Serveur local
Pour un meilleur rendu (chemins relatifs), utilisez un serveur local :

```bash
# Python 3
python3 -m http.server 8080

# Python 2
python -m SimpleHTTPServer 8080

# Node.js (avec http-server)
npx http-server -p 8080
```

Puis ouvrez http://localhost:8080 dans votre navigateur.

## ✏️ Personnalisation

### Modifier les couleurs
Éditez `css/style.css` et changez les couleurs principales :
- `#2563eb` - Couleur primaire (bleu)
- `#667eea` et `#764ba2` - Dégradés

### Ajouter un nouvel article
1. Créez un nouveau fichier HTML dans le dossier `posts/`
2. Copiez la structure d'un article existant
3. Ajoutez une carte pour votre article dans `index.html`

### Modifier le contenu
Tous les textes sont en HTML pur, modifiez-les directement dans les fichiers `.html`.

## 📱 Compatibilité

- ✅ Chrome/Edge (versions récentes)
- ✅ Firefox (versions récentes)
- ✅ Safari (versions récentes)
- ✅ Appareils mobiles (iOS/Android)

## 📝 License

Libre d'utilisation pour vos projets personnels et commerciaux.

# Portfolio - Étudiant en Ingénierie Aéronautique et Astronautique

Portfolio professionnel bilingue (Français/Anglais) pour un étudiant en ingénierie aéronautique et astronautique à l'Université Tsinghua.

## 🚀 Caractéristiques

- **Design Moderne et Professionnel** : Interface élégante avec des couleurs inspirées de l'aérospatiale
- **Bilingue** : Basculement facile entre français et anglais
- **Responsive** : Optimisé pour tous les appareils (mobile, tablette, desktop)
- **Animations Fluides** : Transitions et effets visuels professionnels
- **Sections Complètes** :
  - Accueil avec présentation
  - À Propos
  - Formation Académique (Timeline)
  - Compétences Techniques
  - Expérience
  - Projets Académiques
  - Langues
  - Centres d'Intérêt
  - Contact

## 📁 Structure des Fichiers

```
portfolio/
│
├── index_complete.html    # Fichier HTML principal (UTILISEZ CELUI-CI)
├── styles.css            # Styles CSS
├── script.js             # JavaScript pour interactivité
└── README.md             # Ce fichier
```

## 🎨 Palette de Couleurs

- **Bleu Primaire** : #0A2463 (Bleu profond aérospatial)
- **Bleu Secondaire** : #3E92CC (Bleu ciel)
- **Bleu Accent** : #1E88E5 (Bleu vif)
- **Bleu Foncé** : #001233 (Bleu nuit)
- **Bleu Clair** : #D8E9F0 (Bleu pastel)
- **Doré** : #FFD700 (Pour les accents)

## 🚀 Comment Utiliser

### Option 1 : Ouvrir Directement dans un Navigateur

1. Naviguez vers le dossier `portfolio`
2. Double-cliquez sur `index_complete.html`
3. Le portfolio s'ouvrira dans votre navigateur par défaut

### Option 2 : Utiliser un Serveur Local

```bash
# Avec Python 3
cd portfolio
python -m http.server 8000

# Puis ouvrez http://localhost:8000/index_complete.html dans votre navigateur
```

### Option 3 : Utiliser Live Server (VS Code)

1. Installez l'extension "Live Server" dans VS Code
2. Cliquez droit sur `index_complete.html`
3. Sélectionnez "Open with Live Server"

## ✏️ Personnalisation

### Modifier les Informations Personnelles

1. **Informations de Contact** (Section Contact) :
   - Ouvrez `index_complete.html`
   - Cherchez la section `<!-- Contact Section -->`
   - Modifiez :
     - Email : `votre.email@example.com`
     - Téléphone : `+86 XXX XXXX XXXX`
     - LinkedIn : `linkedin.com/in/votre-profil`

2. **Ajouter une Photo de Profil** :
   - Remplacez l'icône de fusée dans la section Hero
   - Ligne ~60 : Remplacez `<i class="fas fa-rocket"></i>` par `<img src="votre-photo.jpg" alt="Photo">`

3. **Modifier les Compétences** :
   - Section Skills : Ajustez les pourcentages dans `style="width: XX%"`
   - Ajoutez ou supprimez des compétences selon vos besoins

4. **Ajouter des Projets** :
   - Dupliquez un bloc `.project-card` dans la section Projects
   - Modifiez le titre, la description et les tags

### Modifier les Couleurs

Dans `styles.css`, modifiez les variables CSS (lignes 2-18) :

```css
:root {
    --primary-color: #0A2463;      /* Couleur principale */
    --secondary-color: #3E92CC;    /* Couleur secondaire */
    --accent-color: #1E88E5;       /* Couleur d'accent */
    /* ... */
}
```

## 🌐 Fonctionnalités JavaScript

- **Changement de Langue** : Bouton en haut à droite
- **Menu Mobile** : Menu hamburger responsive
- **Scroll Smooth** : Navigation fluide entre sections
- **Animations au Scroll** : Éléments qui apparaissent progressivement
- **Barres de Compétences Animées** : Animation lors du scroll
- **Bouton Retour en Haut** : Apparaît après avoir scrollé

## 📱 Responsive Design

Le portfolio est optimisé pour :
- **Desktop** : > 1024px
- **Tablette** : 768px - 1024px
- **Mobile** : < 768px

## 🔧 Technologies Utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Styles modernes avec Flexbox et Grid
- **JavaScript (Vanilla)** : Interactivité sans framework
- **Font Awesome 6.4.0** : Icônes professionnelles

## 📝 Sections à Personnaliser

### Priorité Haute
- [ ] Email de contact
- [ ] Numéro de téléphone
- [ ] Profil LinkedIn
- [ ] Photo de profil (optionnel)

### Priorité Moyenne
- [ ] Ajouter vos vrais projets
- [ ] Ajuster les pourcentages de compétences
- [ ] Ajouter des expériences spécifiques

### Priorité Basse
- [ ] Modifier les couleurs selon vos préférences
- [ ] Ajouter des certifications
- [ ] Intégrer un blog (optionnel)

## 🌟 Conseils d'Utilisation

1. **Pour un CV** : Imprimez la page ou exportez en PDF depuis le navigateur
2. **Pour Postuler** : Hébergez sur GitHub Pages, Netlify ou Vercel
3. **Pour LinkedIn** : Ajoutez le lien dans votre profil
4. **Pour Réseautage** : Partagez le lien lors d'événements professionnels

## 🚀 Hébergement Gratuit

### GitHub Pages
```bash
# Créez un repo GitHub
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/votre-username/portfolio.git
git push -u origin main

# Activez GitHub Pages dans les paramètres du repo
# Votre site sera disponible à : https://votre-username.github.io/portfolio/
```

### Netlify
1. Glissez-déposez le dossier `portfolio` sur netlify.com
2. Votre site sera en ligne en quelques secondes

### Vercel
```bash
npm i -g vercel
cd portfolio
vercel
```

## 📧 Support

Pour toute question ou suggestion d'amélioration, n'hésitez pas à :
- Ouvrir une issue sur GitHub
- Me contacter via le formulaire de contact du portfolio

## 📄 Licence

Ce portfolio est libre d'utilisation pour un usage personnel et éducatif.

---

**Créé avec ❤️ pour les futurs ingénieurs aérospatiaux**

🚀 Bon vol vers votre carrière ! 🌟

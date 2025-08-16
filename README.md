# README.md

# 🚀 Portfolio - Hatim Lamarti

Portfolio personnel moderne et responsive présentant mes compétences en développement Full Stack et Data Science.

## 🌟 Aperçu

- **Site live :** [https://hatim3310.github.io/portfolio](https://hatim3310.github.io/portfolio)
- **Technologies :** HTML5, CSS3, JavaScript, EmailJS
- **Hébergement :** GitHub Pages

## ✨ Fonctionnalités

- ✅ Design moderne et responsive
- ✅ Animations fluides et interactives
- ✅ Section projets avec liens GitHub
- ✅ Formulaire de contact fonctionnel (EmailJS)
- ✅ Téléchargement CV intégré
- ✅ Blog personnel
- ✅ Optimisé pour mobile

## 🛠️ Installation locale

1. **Cloner le repository**
```bash
git clone https://github.com/hatim3310/portfolio.git
cd portfolio
```

2. **Lancer un serveur local**
```bash
# Avec Python
python -m http.server 8000

# Avec Node.js
npx http-server

# Avec VS Code Live Server extension
```

3. **Accéder au site**
Ouvrir `http://localhost:8000` dans votre navigateur

## 📧 Configuration du formulaire de contact

Le formulaire utilise EmailJS pour l'envoi d'emails. Pour le configurer :

1. **Créer un compte EmailJS**
   - Aller sur [EmailJS.com](https://emailjs.com)
   - Créer un compte gratuit

2. **Configurer le service email**
   - Ajouter un service email (Gmail, Outlook, etc.)
   - Noter le `Service ID`

3. **Créer un template d'email**
   - Créer un nouveau template
   - Noter le `Template ID`
   - Utiliser ces variables : `{{from_name}}`, `{{from_email}}`, `{{subject}}`, `{{message}}`

4. **Mettre à jour le code**
   Dans `index.html`, remplacer :
   ```javascript
   emailjs.init("YOUR_EMAILJS_USER_ID"); // Votre User ID
   
   await emailjs.send(
       'YOUR_SERVICE_ID',    // Votre Service ID
       'YOUR_TEMPLATE_ID',   // Votre Template ID
       templateParams
   );
   ```

## 📁 Structure du projet

```
portfolio/
├── index.html              # Page principale
├── blog.html               # Page blog
├── css/
│   └── style.css           # Styles principaux
├── js/
│   └── form.js            # Scripts formulaire (optionnel)
├── images/
│   ├── logo.png           # Logo personnel
│   ├── profile.jpg        # Photo de profil
│   ├── projects/          # Images des projets
│   ├── certifications/    # Images des certifications
│   └── logos/             # Logos des entreprises
├── assets/
│   └── CV_Hatim_Lamarti.pdf  # CV téléchargeable
├── projects/              # Pages détails projets
└── README.md             # Documentation
```

## 🚀 Déploiement GitHub Pages

1. **Pousser le code sur GitHub**
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. **Activer GitHub Pages**
   - Aller dans Settings du repository
   - Section "Pages"
   - Source : "Deploy from a branch"
   - Branch : "main" / "(root)"
   - Sauvegarder

3. **Accéder au site**
   Le site sera disponible à : `https://[username].github.io/portfolio`

## 🎨 Personnalisation

### Couleurs
Modifier les variables CSS dans `css/style.css` :
```css
:root {
    --accent-blue: #0066ff;
    --accent-purple: #6c5ce7;
    --accent-green: #00d4aa;
    /* ... autres couleurs */
}
```

### Contenu
- **À propos :** Modifier la section `#about` dans `index.html`
- **Projets :** Ajouter/modifier dans la section `#projects`
- **Compétences :** Mettre à jour la section `#skills`

### Images
- Ajouter vos images dans le dossier `images/`
- Respecter les dimensions recommandées :
  - Logo : 45x45px
  - Profile : 300x300px
  - Projets : 400x200px

## 📱 Responsive Design

Le site est optimisé pour tous les appareils :
- 📱 Mobile : 320px - 767px
- 📱 Tablette : 768px - 1023px
- 💻 Desktop : 1024px+

## 🔧 Technologies utilisées

- **Frontend :** HTML5, CSS3, JavaScript ES6+
- **Styles :** CSS Grid, Flexbox, Custom Properties
- **Animations :** CSS Animations, Transitions
- **Icons :** Font Awesome 6.4.0
- **Fonts :** Google Fonts (Inter, Poppins)
- **Email :** EmailJS
- **Hébergement :** GitHub Pages

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 📞 Contact

- **Email :** contact@hatimlamarti.dev
- **LinkedIn :** [linkedin.com/in/lamartihatim](https://linkedin.com/in/lamartihatim)
- **GitHub :** [github.com/hatim3310](https://github.com/hatim3310)

---

⭐ **Si ce projet vous plaît, n'hésitez pas à lui donner une étoile !**

---

## 🔄 Mises à jour

- **v1.0.0** - Version initiale avec toutes les sections
- **v1.1.0** - Ajout du blog et optimisations mobile
- **v1.2.0** - Intégration EmailJS et déploiement GitHub Pages

---

**Fait avec ❤️ par Hatim Lamarti**
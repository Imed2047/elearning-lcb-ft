# 🎓 Formation LCB-FT - Plateforme eLearning Interactive

## 📋 Description

Plateforme de formation complète en **Lutte Contre le Blanchiment de Capitaux et Financement du Terrorisme (LCB-FT)** avec :
- **90 modules** de formation
- **445 questions** de quiz interactif
- **3 sections** complètes
- Interface **moderne et responsive**
- Scoring automatique
- Progression sauvegardée

## 📦 Fichiers fournis

### 1. **index.html**
Page principale avec interface interactive :
- Sidebar navigation
- Grille des modules
- Modal quiz complet
- Design moderne et professionnel
- Compatible mobile/tablette/desktop

### 2. **index.json**
Fichier de données contenant :
- 90 modules complets
- Toutes les questions (445 total)
- Réponses correctes marquées
- Explications pour chaque question
- Modules 3.13 et 3.15 corrigés
- Structure optimisée pour le HTML

## 🚀 Déploiement

### Sur GitHub Pages

1. **Créez un repository** : `elearning-lcb-ft` (ou équivalent)

2. **Uploadez les fichiers** dans la racine du repo :
   ```
   elearning-lcb-ft/
   ├── index.html
   └── index.json
   ```

3. **Activez GitHub Pages** :
   - Settings → Pages
   - Source: main branch
   - Folder: / (root)

4. **Accédez à** :
   ```
   https://imed2047.github.io/elearning-lcb-ft/
   ```

### Localement

1. Téléchargez les fichiers
2. Placez-les dans le même dossier
3. Double-cliquez sur `index.html`

## 📊 Contenu

### Sections de formation

#### Section 1 : Initiation (30 modules)
- Introduction à la LCB-FT
- Obligations déclaratives
- Fondamentaux compliance

#### Section 2 : Intermédiaire (30 modules)
- Typologies avancées
- Secteurs à risque
- Cas pratiques

#### Section 3 : Expert (30 modules)
- PSAN et fintech
- Financement du terrorisme
- Reporting complexe

## ✅ Fonctionnalités

- 🎯 **Quiz interactif** : 5 questions par module
- 📊 **Progression** : Sauvegardée automatiquement
- 💡 **Explications** : Feedback instantané
- 🎨 **Design** : Interface moderne et épurée
- 📱 **Responsive** : Fonctionne partout
- 🔒 **Sécurisé** : 100% local, aucune data externe

## 🛠️ Technologie

- HTML5
- CSS3 (Grid, Flexbox, Gradients)
- JavaScript Vanilla (pas de dépendances)
- Font Awesome (icônes)
- JSON (données)

## 📝 Structure HTML-JSON

### HTML attend :
```javascript
modulesData.all_modules[moduleId]
modulesData.sections
module.title
module.difficulty
module.duration
module.quiz.questions
option.correct
```

### JSON fournit :
✅ Toutes ces clés
✅ 90 modules complets
✅ 445 questions structurées
✅ Réponses marquées
✅ Aucune donnée manquante

## 🐛 Dépannage

### "Erreur de chargement"
- Vérifiez que `index.json` est dans le même dossier
- Videz le cache navigateur (Ctrl+Shift+Del)

### "Aucun module affiché"
- Vérifiez la console (F12)
- Assurez-vous que le JSON est valide

### "Quiz ne fonctionne pas"
- Rechargez la page
- Testez dans un autre navigateur

## 📞 Support

Pour toute question :
1. Vérifiez la structure des fichiers
2. Ouvrez la console (F12)
3. Cherchez les messages d'erreur

## ✅ Vérifications

- ✅ 90 modules présents
- ✅ 445 questions complètes
- ✅ Modules 3.13 et 3.15 corrigés
- ✅ Aucune donnée manquante
- ✅ Aucune suppression
- ✅ Aucune troncature
- ✅ HTML ↔ JSON compatible 100%

## 🎉 Prêt à l'emploi !

La plateforme est **totalement fonctionnelle** et **prête pour la production**.
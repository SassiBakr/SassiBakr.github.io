# 📝 Guide de Personnalisation des Certificats

## ✅ Ce qui a été fait automatiquement

1. ✅ **Photo de profil ajoutée** dans la section Hero avec animations
2. ✅ **7 certificats intégrés** avec effet flip 3D interactif
3. ✅ **Lien CV fonctionnel** vers `Bakr_Sassi_CV.pdf`
4. ✅ **Design responsive** pour mobile, tablette et desktop

## 🎯 Ce que vous devez personnaliser

### Pour CHAQUE Certification (7 au total)

Ouvrez `index.html` et cherchez les sections avec `[Nom de l'émetteur]` et `[Année]`.

#### Exemple de personnalisation :

**AVANT :**
```html
<h4 class="cert-title">Certification Professionnelle 1</h4>
<p class="cert-issuer">
    <i class="fas fa-building"></i> [Nom de l'émetteur]
    <span class="cert-year">[Année]</span>
</p>
<p class="cert-description">Description de cette certification professionnelle</p>
```

**APRÈS (exemple Power BI) :**
```html
<h4 class="cert-title">Microsoft Power BI Data Analyst</h4>
<p class="cert-issuer">
    <i class="fas fa-building"></i> Microsoft
    <span class="cert-year">2024</span>
</p>
<p class="cert-description">Visualisation de données avancée et business intelligence</p>
```

### 🔍 Comment Trouver les Sections à Modifier

Dans `index.html`, cherchez (Ctrl+F) :
- `Certification Professionnelle 1` → Ligne ~620
- `Certification Professionnelle 2` → Ligne ~660
- `Certification Professionnelle 3` → Ligne ~700
- `Certification Professionnelle 4` → Ligne ~740
- `Certification Professionnelle 5` → Ligne ~780
- `Certification Professionnelle 6` → Ligne ~820
- `Certification Professionnelle 7` → Ligne ~860

### 📋 Modèle à Suivre pour Chaque Certificat

Pour chaque certificat, remplissez :

1. **Titre** : Le nom complet de la certification
2. **Émetteur** : Nom de l'organisation (Microsoft, Coursera, LinkedIn Learning, etc.)
3. **Année** : Année d'obtention
4. **Description** : Courte phrase décrivant ce que couvre la certification
5. **Icône** (optionnel) : Changer l'icône si nécessaire

### 🎨 Changer les Icônes (Optionnel)

Remplacez `<i class="fas fa-certificate"></i>` par :

**Exemples d'icônes disponibles :**
- Power BI / Data : `<i class="fas fa-chart-line"></i>`
- SQL / Bases de données : `<i class="fas fa-database"></i>`
- Python : `<i class="fab fa-python"></i>`
- JavaScript : `<i class="fab fa-js"></i>`
- Excel : `<i class="fas fa-file-excel"></i>`
- Cloud : `<i class="fas fa-cloud"></i>`
- Sécurité : `<i class="fas fa-shield-alt"></i>`
- Business : `<i class="fas fa-briefcase"></i>`
- Marketing : `<i class="fas fa-bullhorn"></i>`
- Design : `<i class="fas fa-palette"></i>`

Trouvez plus d'icônes sur : https://fontawesome.com/icons

### 📸 Ordre des Certificats

Vos certificats sont dans l'ordre :
- **cert-1.png** → Certification Professionnelle 1
- **cert-2.png** → Certification Professionnelle 2
- **cert-3.png** → Certification Professionnelle 3
- **cert-4.png** → Certification Professionnelle 4
- **cert-5.png** → Certification Professionnelle 5
- **cert-6.png** → Certification Professionnelle 6
- **cert-7.png** → Certification Professionnelle 7

Si vous voulez réorganiser, renommez simplement les fichiers PNG dans le dossier `images/certifications/`

### 💡 Exemple Complet de Personnalisation

```html
<!-- Certification 1: Power BI -->
<div class="cert-card" data-cert="cert1">
    <div class="cert-card-inner">
        <div class="cert-card-front">
            <div class="cert-icon-badge">
                <i class="fas fa-chart-line"></i> <!-- Icône changée -->
            </div>
            <h4 class="cert-title">Microsoft Power BI Data Analyst</h4>
            <p class="cert-issuer">
                <i class="fas fa-building"></i> Microsoft
                <span class="cert-year">2024</span>
            </p>
            <p class="cert-description">Maîtrise de la visualisation de données et de la business intelligence</p>
            <div class="cert-hover-hint">
                <i class="fas fa-eye"></i>
                <span>Voir le certificat</span>
            </div>
        </div>
        <!-- Ne pas toucher à la partie "cert-card-back" -->
```

### 🎯 Ordre de Priorité

Personnalisez dans cet ordre :
1. ✅ Les **titres** de chaque certification
2. ✅ Les **émetteurs** (noms des organisations)
3. ✅ Les **années** d'obtention
4. ✅ Les **descriptions** courtes
5. 🎨 Les **icônes** (optionnel, si vous voulez les personnaliser)

### ⚠️ Ce qu'il NE FAUT PAS Modifier

**NE touchez PAS à :**
- Les chemins d'images : `src="images/certifications/cert-X.png"`
- Les classes CSS : `class="cert-card"`, `class="cert-card-inner"`, etc.
- La structure HTML (les `<div>`, `</div>`)
- La section `cert-card-back` (partie arrière avec l'image)

### ✅ Checklist de Vérification

Après personnalisation, vérifiez :
- [ ] Les 7 titres sont personnalisés
- [ ] Les 7 émetteurs sont remplis
- [ ] Les 7 années sont remplies
- [ ] Les 7 descriptions sont personnalisées
- [ ] Les icônes sont appropriées (si changées)
- [ ] Aucune erreur de syntaxe HTML
- [ ] Testez en ouvrant `index.html` dans le navigateur
- [ ] Survolez chaque carte pour vérifier l'effet flip

### 🚀 Résultat Final

Une fois personnalisé, vous aurez :
- ✨ Votre photo de profil animée dans le Hero
- 🎓 7 cartes de certification interactives
- 🔄 Effet flip 3D au survol
- 📱 Design responsive sur tous les appareils
- ✅ Badge "Certificat vérifié" sur chaque carte
- 🔍 Bouton "Voir en plein écran" pour chaque certificat

### 📞 Support

Si vous avez des questions ou besoin d'aide supplémentaire, référez-vous aux autres guides :
- `GUIDE_CERTIFICATIONS.md` - Guide détaillé complet
- `CERTIFICATIONS_README.md` - Résumé des fonctionnalités
- `CUSTOMIZATION_CHECKLIST.md` - Checklist générale

---

**Bon courage pour la personnalisation ! 🎉**

# 🏕️ Sécurité Structures Itinérantes CTS & ERP Type L

## 🌐 Accès Direct
**Application en ligne** : [Sécurité Structures Itinérantes CTS & ERP Type L](https://fi-regie.github.io/securite-structures-itinerantes-cts-erp/)

## 📖 Présentation Générale

Application web professionnelle complète pour la sécurité des structures itinérantes (CTS) et établissements de type L. Cet outil regroupe l'ensemble des réglementations, simulateurs et outils pratiques nécessaires aux exploitants, régisseurs et organismes de contrôle.

## 🎯 Fonctionnalités Principales

### **8 Modules Complets**

#### **1. 📊 Tableau de Bord**
- Vue d'ensemble des obligations réglementaires
- Graphique de répartition des points de contrôle CTS
- Alertes critiques (vent, registre, ancrage)
- Cadre général ERP Type L vs CTS

#### **2. 🧮 Simulateurs**
- Calculateur interactif de catégorie ERP
- Simulateur de dégagements (Unités de Passage)
- Analyse matériaux (classements M0-M4)
- Organisation du personnel sécurité

#### **3. 🌬️ CTS & Météo**
- Simulateur de décision météo pour chapiteaux
- Échelle de Beaufort interactive
- Checklist points de contrôle obligatoires
- Statut exploitation en temps réel

#### **4. 🐾 Faune Sauvage**
- Timeline législative Loi 2021-1539
- Échéances critiques (2023-2028)
- Points clés juridiques animaux sauvages
- Guide de transition pour cirques

#### **5. ⚖️ Législation**
- Bibliothèque de liens officiels Légifrance
- Moteur de recherche par thème/mot-clé
- 9 catégories réglementaires complètes
- Accès direct aux textes consolidés

#### **6. 🔄 Procédures**
- Chronologie interactive (conception → contrôle)
- Tableau synthétique des contrôles
- Détails réglementaires étape par étape
- Références articles CTS

#### **7. 🏗️ Focus Technique**
- Ancrage au sol (tests d'arrachement, DICT)
- Charpente & levage (goupilles, câbles)
- Toiles & réaction au feu (M1/M2)
- Électricité & chauffage (BAES, distances)

#### **8. ✅ Outils Pratiques**
- Checklist "Jour J" sauvegardable
- Glossaire technique complet
- Termes métier définis précisément
- Outils de vérification terrain

## ✨ Caractéristiques Techniques

### **Calculateurs Interactifs**
- **Calculateur de catégorie ERP** : Basé sur effectif total
- **Simulateur de dégagements** : Calcul UP et largeurs minimales
- **Analyse vent CTS** : Algorithme décisionnel météo
- **Matériaux** : Visualisation proportions M0-M4

### **Visualisations Professionnelles**
- **7 graphiques Chart.js** interactifs
- **Diagrammes de répartition** (doughnut, bar, line)
- **Timeline législative** animée
- **Indicateurs visuels** temps réel

### **Système de Persistance**
- **Sauvegarde locale** des checklists
- **Mémorisation** des préférences utilisateur
- **Statuts conservation** entre sessions
- **Données utilisateur** sécurisées

## 🎨 Design & Interface

### **Palette "Architectural Safety"**
```css
stone: { 50: '#fafaf9', 900: '#1c1917' }   /* Neutre professionnel */
orange: { 600: '#ea580c' }                 /* Alertes sécurité */
emerald: { 600: '#059669' }                /* Conformité/validation */
slate: { 700: '#334155' }                  /* Cadre réglementaire */
```

### **Navigation Professionnelle**
- **8 onglets thématiques** organisés
- **Navigation horizontale** responsive
- **Indicateur visuel** onglet actif
- **Transitions fluides** entre sections

### **Responsive Design**
- **Mobile-first** optimisation
- **Adaptation tablette/desktop**
- **Interface tactile** optimisée
- **Performances** cross-device

## 🔧 Technologies Utilisées

### **Stack Frontend**
```html
<!-- Tailwind CSS v3.3+ -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Chart.js v4.4+ -->
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<!-- Font Awesome v6.4+ -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

### **Architecture JavaScript**
```javascript
// Structure modulaire organisée
const modules = {
    navigation: switchTab,
    charts: initCharts,
    calculs: {
        erp: calculateERP,
        evacuation: updateEvacuation,
        vent: updateWeatherStatus
    },
    data: {
        legislation: renderLinksTable,
        procedures: updateProcedure,
        technique: showTechDetail
    },
    outils: {
        checklist: { init: initChecklist, reset: resetChecklist },
        recherche: setupSearch
    }
};
```

## 📚 Sources Réglementaires

### **Textes Officiels Intégrés**
- 📜 **Arrêté du 23 janvier 1985** : Règlement CTS
- 📜 **Code de la Construction** : Articles R. 123-43 à R. 123-45
- 📜 **Arrêté du 25 juin 1980** : Dispositions générales ERP
- 📜 **Loi n° 2021-1539** : Animaux sauvages cirques itinérants
- 📜 **Code du travail** : Santé et sécurité au travail
- 📜 **Code santé publique** : Réglementation bruit

### **Articles Clés CTS**
- **CTS 1-4** : Généralités & Classification
- **CTS 5-9** : Structure & Ossature
- **CTS 10-12** : Enveloppe & Réaction au feu
- **CTS 13-28** : Installations électriques
- **CTS 31-37** : Contrôles & Vérifications
- **CTS 52** : Attestation bon montage

## 🚀 Installation & Déploiement

### **Utilisation en Ligne**
1. Accédez à : https://fi-regie.github.io/securite-structures-itinerantes-cts-erp/
2. Naviguez entre les 8 onglets thématiques
3. Utilisez les simulateurs interactifs
4. Consultez la bibliothèque légale

### **Utilisation Locale**
```bash
# Clone du dépôt
git clone https://github.com/fi-regie/securite-structures-itinerantes-cts-erp.git

# Structure minimale
securite-structures-itinerantes-cts-erp/
├── index.html      # Application complète (single file)
├── README.md       # Documentation
└── (évolutions)    # Futures versions
```

### **Dépendances**
- **Aucune installation** requise
- **CDN externes** : Tailwind, Chart.js, Font Awesome
- **Navigateur moderne** : Chrome, Firefox, Safari, Edge
- **Connexion internet** pour CDN (optionnel hors ligne)

## 📱 Compatibilité

### **Navigateurs Supportés**
- ✅ Chrome 90+ (optimisé)
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 91+
- ✅ Mobile (iOS 14+, Android 10+)

### **Performances**
- **Temps chargement** : < 2 secondes
- **Taille totale** : ~180KB (sans CDN)
- **Mémoire** : < 50MB
- **CPU** : Optimisé pour anciens devices

## 🔗 Écosystème Applications

### **Suite d'Outils Open Source**
- 🎯 **Simulateur Sécurité ERP** : https://fi-regie.github.io/Simulateur-Reglement-Securite-ERP/
- 🎪 **Réglementation Spectacle Itinérant** : https://fi-regie.github.io/Reglementation-Spectacle-Itinerant/
- 🏕️ **Réglementation CTS** : https://fi-regie.github.io/reglementation-CTS-/
- 🎓 **Formation Sécurité ERP** : https://fi-regie.github.io/Formation-Securite-ERP/
- ❓ **Quiz du Régisseur** : https://fi-regie.github.io/Quiz-CTS/

### **Ressources Externes**
- 📚 **Légifrance** : Textes officiels
- 🏛️ **Service Public** : Obligations légales
- 🎓 **Organismes formation** : SSIAP, régisseur
- 📋 **Commissions sécurité** : Guides pratiques

## 👥 Public Cible

### **Professionnels Terrain**
- 🎪 Exploitants chapiteaux/cirques
- 🏗️ Directeurs techniques CTS
- 🔧 Régisseurs généraux/travelling
- 🎭 Organisateurs spectacles itinérants

### **Contrôle & Vérification**
- 📋 Organismes agréés (BVCTS)
- ⚖️ Commissions de sécurité
- 🏢 Services préfectoraux/mairies
- 📊 Bureaux d'études techniques

### **Formation & Conseil**
- 🎓 Centres formation sécurité
- 📚 Écoles spectacle/événementiel
- 🏫 Formateurs indépendants
- 💼 Consultants réglementaires

## 📊 Données et Contenu

### **Base de Connaissances**
- **8 modules** : 50+ sections détaillées
- **9 textes réglementaires** complets
- **20+ calculateurs/simulateurs**
- **15+ études cas techniques**
- **Glossaire** : 6 termes techniques définis

### **Métriques d'Utilisation**
- **Temps parcours complet** : 1-2 heures
- **Simulations rapides** : 30 secondes
- **Recherche textes** : résultats instantanés
- **Sauvegarde données** : persistance locale

## 🛠️ Personnalisation

### **Configuration Technique**
```javascript
// Exemple configuration utilisateur
const userConfig = {
    typeStructure: 'CTS', // CTS, ERP-L, ERP-L1
    region: 'France', // Adaptations régionales
    niveauExpertise: 'professionnel', // débutant/avancé/expert
    notifications: {
        vent: true,
        legal: true,
        contrôles: true
    }
};
```

### **Extensions Possibles**
- 🌍 **Internationalisation** : Traductions
- 📱 **PWA** : Installation application mobile
- 📊 **Analytics** : Statistiques utilisation
- 🔄 **Sync cloud** : Sauvegarde multi-device

## ⚠️ Limitations et Avertissements

### **Usage Professionnel**
> ⚠️ **Outil d'aide à la décision** - Ne remplace pas :
> - L'expertise d'un organisme agréé
> - La visite d'une commission de sécurité
> - La consultation des textes officiels actualisés
> - L'avis d'un professionnel certifié

### **Couverture Réglementaire**
- 📅 **Actualisation** : Vérifier dates textes Légifrance
- 🏛️ **Territoire** : Droit français métropolitain
- 🎭 **Spécificités** : Cas particuliers locaux
- 🔄 **Évolution** : Réglementation en constante mutation

## 🌟 Roadmap Évolutive

### **Plan Développement 2025**
- [ ] **Mode hors ligne** complet
- [ ] **Export PDF** des checklists
- [ ] **Base Q/R** élargie
- [ ] **Notifications** personnalisables
- [ ] **API météo** intégration directe

### **Améliorations Techniques**
- [ ] **PWA** : Installation application
- [ ] **Service Worker** : Cache optimisé
- [ ] **IndexedDB** : Stockage avancé
- [ ] **Web Components** : Modularisation

## 📞 Support et Contact

### **Support Technique**
- 🐛 **Issues GitHub** : https://github.com/fi-regie/securite-structures-itinerantes-cts-erp/issues
- 📚 **Documentation** : Ce README et commentaires code
- 👥 **Communauté** : Professionnels du spectacle

### **Contact Direct**
- 📧 **Email** : philippe.potier-regie@proton.me
- 📋 **Sujet** : [Sécurité CTS] - Votre demande

### **Contributions**
- 🌟 **Forks** : Adaptations encouragées
- 🔧 **PR** : Améliorations bienvenues
- 💡 **Suggestions** : Retours terrain appréciés
- 🐛 **Bugs** : Signalements utiles

## 📄 Licence et Conditions

### **Licence d'Utilisation**
- ✅ **Usage gratuit** professionnel
- ✅ **Modification autorisée** avec attribution
- ✅ **Distribution** dans la profession
- ✅ **Open Source** : Code disponible

### **Attribution Requise**
```
Sécurité Structures Itinérantes CTS & ERP Type L © 2025
Développé par Philippe Potier pour la profession
Source : https://github.com/fi-regie/securite-structures-itinerantes-cts-erp
```

## 🙏 Remerciements

### **Contributeurs**
- **Philippe Potier** : Conception, développement, contenu
- **Professionnels terrain** : Retours, validation, cas pratiques
- **Communauté open source** : Bibliothèques, inspiration

### **Technologies**
- **Tailwind CSS** : Framework CSS utilitaire
- **Chart.js** : Visualisations données
- **Font Awesome** : Système icônes
- **GitHub Pages** : Hébergement gratuit

---

**Version** : 1.0.0 (Décembre 2025)  
**Mise à jour** : 20 décembre 2025  
**Contact** : philippe.potier-regie@proton.me  
**Licence** : Open Source - Usage professionnel  

*« La sécurité itinérante : une responsabilité mobile, des exigences fixes. »* 🏕️🌬️🔧

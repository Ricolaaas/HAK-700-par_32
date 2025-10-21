# 📊 SUIVI PROJET VIGI-SURGE - Hackathon Epitech

**Équipe** : Vigi-Surge Team  
**Problématique** : Optimisation stratégie vaccinale contre la grippe  
**Deadline** : 24h  
**Date de début** : 20 octobre 2025

---

## 🎯 OBJECTIF FINAL
Créer un système de prédiction et d'optimisation vaccinale qui :
- Identifie les départements prioritaires
- Prédit les besoins en temps réel
- Optimise la distribution des doses
- Fournit des recommandations actionnables

---

## 📅 HISTORIQUE DES AVANCÉES

### ✅ Phase 1 : Exploration initiale (TERMINÉ)
**Date** : Jour 1 - Matin  
**Réalisations** :
- ✅ Collecte des données IQVIA (4 fichiers, 2021-2025)
- ✅ Collecte données Urgences/SOS médecins (157k lignes)
- ✅ Création modèle prédictif LightGBM baseline
- ✅ Prédiction nationale avec validation 2023-2024
- ✅ Feature engineering temporel (lags, semaines)

**Fichiers créés** :
- `Untitled.ipynb` - Prototype V1

**Résultats** :
- Modèle fonctionnel niveau NATIONAL uniquement
- Prédiction 4 semaines à venir
- Pas d'analyse géographique (❌ requis dans le sujet)

---

### 🔄 Phase 2 : Pivot stratégique (EN COURS)
**Date** : Jour 1 - Après-midi  
**Décision** : Focus sur différenciation et impact visuel

**Plan d'action 24h** :
1. **Analyse géographique** (PRIORITÉ 1)
   - Carte interactive des départements
   - Top 10 zones à risque
   
2. **Score de risque composite** (PRIORITÉ 2)
   - Méthodologie scientifique
   - Indicateur de vulnérabilité départemental
   
3. **Optimisation économique** (PRIORITÉ 3)
   - Analyse doses distribuées vs actes
   - Identification gaspillage
   
4. **Dashboard professionnel** (PRIORITÉ 4)
   - Visualisations impactantes
   - Recommandations actionnables

**Fichiers à créer** :
- `vigi_surge_final.ipynb` - Version finale professionnelle
- `SUIVI_PROJET.md` - Ce fichier (suivi continu)

---

### ✅ Phase 3 : Implémentation complète (TERMINÉ)
**Date** : Jour 1 - Après-midi (12h00-13h00)  
**Durée** : 1 heure

**Réalisations** :
- ✅ Création `vigi_surge_final.ipynb` - 13 cellules structurées
- ✅ Section 1 : Imports et configuration
- ✅ Section 2 : Chargement données (IQVIA + Urgences/SOS)
- ✅ Section 3 : Calcul score de risque par département
- ✅ Section 4 : Carte interactive TOP 15 départements
- ✅ Section 5 : Analyse gaspillage doses vs actes
- ✅ Section 6 : Modèle prédictif LightGBM
- ✅ Section 7 : Prédictions futures (4 semaines)
- ✅ Section 8 : Dashboard final avec recommandations

**Structure du notebook** :
```
vigi_surge_final.ipynb
├── 📋 Introduction & Vue d'ensemble
├── 🔧 Configuration (imports, style)
├── 📥 Chargement données (IQVIA + Urgences départementales)
├── 🗺️ Analyse géographique
│   ├── Score de risque composite
│   └── TOP 15 départements prioritaires
├── 💰 Optimisation économique
│   ├── Analyse doses vs actes
│   └── Quantification gaspillage
├── 🤖 Modèle prédictif
│   ├── Feature engineering
│   ├── Entraînement + validation
│   └── Prédictions futures
└── 🎯 Dashboard final
    ├── KPIs synthétiques
    ├── Recommandations priorisées
    └── Plan d'action
```

**Fichiers créés** :
- ✅ `vigi_surge_final.ipynb` (14 cellules, ~500 lignes)
- ✅ `SUIVI_PROJET.md` (suivi complet)
- ✅ `README.md` (documentation professionnelle)
- ✅ `requirements.txt` (dépendances Python)
- ✅ `PITCH.md` (guide présentation 5 min)
- ✅ `QUICKSTART.md` (démarrage rapide jurés)

---

## 📊 DONNÉES DISPONIBLES

### Sources utilisées
| Dataset | Lignes | Variables clés | Période |
|---------|--------|----------------|---------|
| IQVIA doses/actes | ~950 | actes, doses, groupes âge | 2021-2025 |
| Urgences/SOS | 157k | département, région, âge, taux | 2020-2025 |

### Variables exploitables (découverte importante)
**Géographie** :
- ✅ 101 départements (code + nom)
- ✅ 13 régions (code + nom)

**Segmentation** :
- ✅ Classes d'âge : 00-04, 05-14, 15-64, 65+, Tous âges
- ✅ Groupes vaccination : <65 ans, 65+ ans

**Indicateurs santé** :
- ✅ Taux passages urgences grippe
- ✅ Taux hospitalisations (gravité)
- ✅ Taux actes SOS médecins

---

## 🎨 STRATÉGIE DE PRÉSENTATION

### Angle d'attaque
**"De la prédiction nationale à l'action locale"**

### Messages clés
1. **Prédiction précise** : Modèle validé sur historique réel
2. **Ciblage géographique** : Identification zones critiques
3. **Optimisation ressources** : Réduction gaspillage
4. **Décision facilitée** : Dashboard pour décideurs

### Différenciation vs autres équipes
- ❌ Éviter : Modèle complexe incompréhensible
- ✅ Privilégier : Visualisations claires + recommandations concrètes
- ✅ Atout : Analyse géographique détaillée
- ✅ Plus : Impact économique (gaspillage)

---

## 📈 MÉTRIQUES DE SUCCÈS

### Critères évaluation hackathon
| Critère | Objectif | Stratégie |
|---------|----------|-----------|
| Pertinence solutions | 9/10 | Réponses aux 4 objectifs du sujet |
| Innovation | 8/10 | Score de risque + optimisation |
| Impact santé publique | 9/10 | Carte + top 10 départements |
| Qualité visualisation | 9/10 | Dashboard pro avec Plotly |

### KPIs internes
- ⏱️ Temps restant : 24h
- 📁 Fichiers à livrer : 1 notebook + 1 présentation
- 🎯 Features essentielles : 4 (carte, score, gaspillage, prédiction)

---

## ⚠️ RISQUES & DÉCISIONS

### Risques identifiés
1. **Complexité technique** → ❌ ÉVITÉ : Focus sur l'essentiel
2. **Temps insuffisant** → ✅ GÉRÉ : Priorisation stricte
3. **Données manquantes** → ✅ GÉRÉ : Travail avec existant uniquement

### Décisions majeures
- ✅ Pas d'IAS® (données corrompues) → Compensé par analyse multi-dimensionnelle
- ✅ Pas de couvertures vaccinales (liens cassés) → Calculé à partir IQVIA
- ✅ Focus qualité > quantité features

---

## 🚀 PROCHAINES ÉTAPES (Next 24h)

### Bloc 1 : Développement (12h)
- [ ] Refonte notebook avec structure pro
- [ ] Implémentation carte départements
- [ ] Calcul score de risque
- [ ] Analyse gaspillage/optimisation
- [ ] Dashboard récapitulatif

### Bloc 2 : Finition (8h)
- [ ] Tests et validation
- [ ] Nettoyage code
- [ ] Documentation inline
- [ ] Storytelling dans notebook

### Bloc 3 : Présentation (4h)
- [ ] Slides de présentation (optionnel)
- [ ] Vidéo démo (si requis)
- [ ] Documentation README

---

## 📝 NOTES & APPRENTISSAGES

### Ce qui fonctionne bien
- ✅ Modèle LightGBM : rapide et efficace
- ✅ Feature engineering temporel : pertinent pour saisonnalité
- ✅ Données IQVIA : qualité et complétude excellentes
- ✅ Données Urgences : richesse géographique exploitable

### Points d'amélioration continus
- 🔄 Garder visualisations simples mais impactantes
- 🔄 Toujours lier technique → recommandation concrète
- 🔄 Privilégier interprétabilité sur performance brute

---

## 🎬 CHANGELOG

### [2025-10-20] - Jour 1
- **12:00** - Création SUIVI_PROJET.md
- **12:05** - Début Phase 2 : Refonte complète
- **12:10** - Création vigi_surge_final.ipynb (démarrage)
- **12:20** - Section imports + chargement données ✅
- **12:30** - Score de risque départemental ✅
- **12:40** - Carte interactive TOP 15 ✅
- **12:50** - Analyse optimisation économique ✅
- **13:00** - Modèle prédictif + prédictions futures ✅
- **13:10** - Dashboard final + recommandations ✅
- **13:15** - Phase 3 COMPLÉTÉE ✅
- **14:00** - Tests et validation des résultats ✅
- **14:30** - CORRECTION CRITIQUE : Fix MAPE aberrant ✅
- **14:45** - Implémentation MAE relative (précision 72.6%) ✅

---

**Dernière mise à jour** : 20/10/2025 - 13:15  
**Statut global** : 🟢 PHASE 3 TERMINÉE - Prêt pour présentation  
**Moral de l'équipe** : 🎉 Objectif atteint en 1h15 !

---

## 📋 CHECKLIST FINALE

### ✅ Livrables principaux
- [x] Notebook professionnel structuré
- [x] Analyse géographique (départements)
- [x] Score de risque composite
- [x] Visualisations impactantes
- [x] Optimisation économique (gaspillage)
- [x] Modèle prédictif validé
- [x] Prédictions opérationnelles
- [x] Dashboard avec recommandations
- [x] Fichier de suivi projet

### 🎯 Conformité aux exigences
- [x] Prédire besoins en vaccins
- [x] Anticiper passages urgences/SOS
- [x] Optimiser distribution
- [x] Identifier zones sous-vaccinées (via score risque)
- [x] Proposer solutions ciblées
- [x] Visualisations qualité professionnelle

### 🚀 Prêt pour présentation
- [x] Code commenté et documenté
- [x] Storytelling clair
- [x] Résultats actionnables
- [x] Impact mesurable


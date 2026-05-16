# 📐 Projet de Recherche Opérationnelle 2026

**Université de Nouakchott (FST)**  
Faculté des Sciences — Licence  
Module : Recherche Opérationnelle  
Responsable : Dr. EL BENANY Med Mahmoud  
Année universitaire : 2025–2026

---

## 👤 Informations sur l'étudiant

| Champ | Détail |
|-------|--------|
| **Nom complet** | Malick Mohamed Tounkara |
| **Filière** | Licence en Informatique / Mathématiques |
| **Année** | 2ème année |
| **Email** | *[malicktounkara37@gmail.com]* |

---

## 📋 Description du projet

Ce dépôt contient les travaux pratiques et projets réalisés dans le cadre du module de **Recherche Opérationnelle** (2025–2026). Chaque sujet comprend une formulation mathématique rigoureuse, une résolution manuelle et une implémentation Python.

> ⚠️ Chaque sujet appartient à une catégorie différente, conformément aux consignes du module. La catégorie **Problèmes réels en Mauritanie** est incluse obligatoirement.

---

## 📂 Structure du dépôt

```
projet-RO-2026/
│
├── sujet_1_4_simplexe/
│   ├── rapport.pdf            # Rapport complet (formulation + résolution manuelle)
│   └── simplexe.py            # Code Python avec PuLP
│
├── sujet_2_4_files_attente/
│   ├── rapport.pdf            # Théorie M/M/1 + calculs analytiques
│   └── simulation_mm1.py      # Simulation Monte-Carlo M/M/1
│
├── sujet_6_2_hopital/
│   ├── rapport.pdf            # Application réelle : urgences en Mauritanie
│   └── modele_mmc.py          # Modèle M/M/c + optimisation du nombre de serveurs
│
└── README.md                  # Ce fichier
```

---

## 📚 Sujets traités

### ✅ Sujet 1.4 — Méthode du Simplexe
**Catégorie :** Sujets classiques et fondamentaux

- Formulation d'un problème de programmation linéaire (PL)
- Mise en forme standard avec variables d'écart
- Résolution manuelle par la méthode du simplexe (2 itérations)
- Interprétation de la solution optimale et analyse de la dualité (prix fantômes)
- Implémentation Python avec la bibliothèque **PuLP**

**Problème traité :**
$$\max z = 3x + 4y \quad \text{s.c.} \quad x + 2y \leq 8, \quad 3x + y \leq 9, \quad x,y \geq 0$$

**Solution optimale :** $x^* = 2$, $y^* = 3$, $z^* = 18$

---

### ✅ Sujet 2.4 — Optimisation des files d'attente (M/M/1)
**Catégorie :** Logistique et supply chain

- Modélisation d'un système de file d'attente M/M/1
- Calcul analytique des indicateurs de performance : $\rho$, $L_q$, $W_q$
- Simulation Monte-Carlo sur 10 000 arrivées avec Python
- Comparaison entre résultats théoriques et empiriques

**Paramètres :** $\lambda = 5$ clients/h, $\mu = 8$ clients/h

---

### ✅ Sujet 6.2 — Files d'attente en centre hospitalier *(Obligatoire — Problème réel RIM)*
**Catégorie :** Problèmes réels en Mauritanie

- Extension vers le modèle **M/M/c** (plusieurs serveurs)
- Application aux urgences d'un centre hospitalier en Mauritanie
- Détermination du nombre optimal de médecins/guichets
- Analyse de l'impact sur le temps d'attente des patients

---

## 🛠️ Outils et technologies

| Outil | Usage |
|-------|-------|
| **Python 3.x** | Langage principal |
| **PuLP** | Résolution de programmes linéaires |
| **NumPy / Random** | Simulation Monte-Carlo |
| **Matplotlib** | Visualisation des résultats |

---

## ▶️ Comment exécuter le code

1. Cloner le dépôt :
```bash
git clone https://github.com/malicktounkara112-ui/projet-RO-2026.git
cd projet-RO-2026
```

2. Installer les dépendances :
```bash
pip install pulp numpy matplotlib
```

3. Exécuter un script :
```bash
python sujet_1_4_simplexe/simplexe.py
python sujet_2_4_files_attente/simulation_mm1.py
python sujet_6_2_hopital/modele_mmc.py
```

---

## 📊 Critères d'évaluation

| Critère | Description |
|---------|-------------|
| Formulation du modèle | Rigueur mathématique de la mise en forme |
| Justesse mathématique | Exactitude des calculs et des résultats |
| Expérimentation | Qualité du code et des simulations |
| Interprétation | Analyse critique des résultats obtenus |
| Rapport & présentation | Clarté, structure et qualité rédactionnelle |

---

## 📬 Contact

Pour toute question relative au module :  
📧 **Dr. EL BENANY Med Mahmoud** — medmhdbennannu@gmail.com

# 🏙️ Student Housing Investment Analyzer  
### 🎓 Analyse des Villes Étudiantes — Projet Data Science

Ce projet, réalisé par **Quentin Heitz**, **Arthur Brosseau** et **Loan Perrard**, propose un **outil d’aide à la décision pour investir dans l’immobilier étudiant**, basé sur des données socio-démographiques, immobilières et urbaines.

---

## 🎯 Persona : Investisseur Immobilier Étudiant

Notre utilisateur cible est un investisseur souhaitant identifier les meilleures villes pour investir dans un logement étudiant.

Il cherche à évaluer :

- 📈 **Rentabilité foncière**
- 🎓 **Proportion d’étudiants** dans la ville  
- 📉 **Évolution du nombre d’étudiants**  
- 🏢 **Tension locative** (offre vs demande de logements)
- 🚇 **Qualité de l’accès aux transports**
- 🔌 **Qualité du réseau électrique**
- 🔐 **Niveau d’insécurité**
- ⚖️ **Comparaison multi-critères entre villes**

L’objectif :  
→ **investir sereinement et maximiser son rendement.**

---

## 📊 Objectif du Projet

Construire un système interactif permettant de :

1. **Comparer différentes villes françaises** selon 9 critères étudiés  
2. Calculer un **score final pondéré** selon les préférences de l’utilisateur  
3. Visualiser **en temps réel** l’impact des critères grâce à un dashboard interactif  
4. Générer un **classement dynamique** des meilleures villes étudiantes

---

## 🧱 Structure du Projet

### 📘 1. Notebook principal : `python_scipy.ipynb`

Ce notebook contient :

- 📥 Importation et nettoyage des datasets
- 🔗 Fusion des données (ville / critères étudiants / critères urbains)
- ⚙️ Fonction de calcul du score :
  ```python
  calculate_score()

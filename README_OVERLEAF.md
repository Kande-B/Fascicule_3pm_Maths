# 📖 Guide d'Utilisation Overleaf — Fascicule 3PM Mathématiques

Ce dossier contient l'ensemble du projet LaTeX prêt à être compilé ou importé directement sur **Overleaf**.

---

## 🚀 Comment importer ce projet sur Overleaf en 3 étapes :

1. **Télécharger l'archive ZIP** :
   - Utilisez le fichier `dist/fascicule_3pm_maths_overleaf.zip` généré par le script.
2. **Importer sur Overleaf** :
   - Rendez-vous sur [Overleaf.com](https://www.overleaf.com/).
   - Cliquez sur le bouton vert **« New Project »** $\rightarrow$ **« Upload Project »**.
   - Déposez le fichier `.zip`.
3. **Compiler** :
   - Ouvrez le projet et assurez-vous que le fichier principal sélectionné est `main_3pm_maths.tex`.
   - Cliquez sur **« Recompile »** (moteur par défaut : **pdfLaTeX**).
   - Le fascicule PDF complet est généré instantanément !

---

## 📁 Architecture des fichiers du projet :

- `main_3pm_maths.tex` : Fichier maître (Couverture TikZ, Sommaire, Quatrième de couverture).
- `fascicule_style.sty` : Thème graphique, encadrés `tcolorbox`, marges, en-têtes et pieds de page.
- `macros.sty` : Raccourcis mathématiques et badges de compétences.
- `chapitres/` :
  - `00_progression_annuelle.tex` : Tableau annuel et référentiel officiel.
  - `01_calcul_litteral.tex` : Activités, Cours, Automatismes, TD 10 exos, TP Tableur, Sujets DNB Pro.
  - `02_equations.tex` : Résolution algébrique, équations produits, problèmes métiers.
  - `03_fonctions_affines.tex` : Fonctions linéaires et affines, lecture graphique.
  - `04_pythagore_trigonometrie.tex` : Théorème de Pythagore et trigonométrie (CAH-SOH-TOA).
  - `05_statistiques_probabilites.tex` : Moyenne, médiane, étendue, équiprobabilité.
  - `06_aires_volumes_conversions.tex` : Formulaire officiel, volumes usuels et conversions.

---

## ⚙️ Compatibilité & Paramètres recommandés :
- **Moteur TeX** : pdfLaTeX (ou XeLaTeX / LuaLaTeX)
- **Format de page** : A4
- **Polices** : Latin Modern (incluses par défaut sur Overleaf)

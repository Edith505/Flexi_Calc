
# 🔢 FlexiCalc

**FlexiCalc** est une application web polyvalente regroupant plusieurs outils de calcul et de conversion dans une seule interface moderne et responsive.

---

## 🧭 Fonctionnalités

### 🧮 Calculatrice
- **Standard** : opérations de base (addition, soustraction, etc.)
- **Scientifique** : fonctions trigonométriques, logarithmes, puissances, etc.
- **Programmeur** : conversions binaires / hexadécimales et opérations logiques
- **Graphique** : saisie de fonctions et affichage de courbes dynamiques

### 🔁 Convertisseur
- **Devises** *(à venir)* : conversion de monnaies avec taux actualisés (via API)
- **Température** : Celsius, Fahrenheit, Kelvin
- **Longueur** : mètre, kilomètre, mile, etc.
- **Poids** : gramme, kilogramme, livre, etc.

---

## 🛠️ Technologies utilisées

- **Frontend** :
  - HTML5 / CSS3 / Bootstrap 5
  - JavaScript (vanilla)
  - Bibliothèques : `Plotly.js`, `math.js`

- **(À venir)** Backend/API :
  - Conversion des devises via une API REST (ex: ExchangeRate API)
  - Flask (optionnel pour version future)

---

## 🗂️ Structure du projet

```
FlexiCalc/
├── index.html
├── style.css
├── script.js
├── /modules/
│   ├── standard.js
│   ├── scientifique.js
│   ├── programmeur.js
│   ├── graphique.js
│   ├── temperature.js
│   ├── longueur.js
│   └── poids.js
└── /libs/
    └── plotly.min.js
```

---

## 🚀 Lancer l'application

Aucune installation requise. Clone ce dépôt et ouvre `index.html` dans ton navigateur :

```bash
git clone https://github.com/Edith505/Flexi_Calc.git
cd Flexi_Calc
start index.html
```

---

## 📌 À faire

- [ ] Finaliser le module Graphique
- [ ] Intégrer l’API de conversion de devises
- [ ] Ajouter un thème clair/sombre
- [ ] Ajouter un système d'historique local

---

## 🤝 Contribuer

Les contributions sont les bienvenues ! Forkez le repo, créez une branche, et proposez un pull request.

---

## 🧑‍💻 Auteur

Développé par **[TonNom]**, passionné de programmation orientée objet, web frontend et interfaces intelligentes.

---

## 📄 Licence

Ce projet est sous licence MIT. Vous êtes libre de l’utiliser, le modifier et le distribuer.

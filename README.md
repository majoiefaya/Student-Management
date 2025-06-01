# 🎓 Student Bulletin – Application de gestion des étudiants (Tkinter)

> Une application bureautique développée en **Python** avec **Tkinter** permettant de gérer les étudiants, leurs notes et de générer des bulletins scolaires. Interface simple, intuitive et locale.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Tkinter-GUI-blue?style=flat-square" alt="Tkinter"/>
  <img src="https://img.shields.io/badge/Type-Bureautique-orange?style=flat-square" alt="Desktop"/>
  <img src="https://img.shields.io/badge/Status-Terminé-brightgreen?style=flat-square" alt="Status"/>
</p>

---

## 🎯 Fonctionnalités principales

- 🧑‍🎓 Enregistrement des étudiants avec informations personnelles
- 📝 Ajout des notes par matière
- 📊 Calcul automatique des moyennes
- 🗃️ Gestion des matières, classes et bulletins
- 📄 Génération d’un bulletin au format lisible et imprimable

---

## 🛠️ Technologies utilisées

| Élément         | Détail                         |
|-----------------|---------------------------------|
| Langage         | Python 3                        |
| Interface       | Tkinter                         |
| Base de données | MySQL (via mysql-connector)     |
| Export          | tkinter + gestion locale        |
| Déploiement     | PyInstaller (exécutable .exe)   |

---

## 🧪 Lancer le projet localement

```bash
# 1. Cloner le dépôt
git clone https://github.com/majoiefaya/Student-Bulletin.git
cd Student-Bulletin

# 2. Installer les dépendances
pip install -r requirements.txt

# 3. Lancer l’application
python main.py
```

---

## 📸 Capture d’écran

<p align="center">
  <img src="https://github.com/majoiefaya/Student-Bulletin/blob/main/app_presentation.png?raw=true" width="600" alt="Aperçu application"/>
</p>

---

## 📦 Générer un exécutable (.exe)

> Pour créer une version distribuable sans installer Python :

```bash
pip install pyinstaller
pyinstaller --onefile --windowed main.py
```

Le fichier `.exe` final est disponible dans le dossier `dist/`.

---

## 📄 Licence

Application personnelle développée par **Faya Lidao Majoie**.  
Utilisation libre à des fins éducatives ou personnelles.

---

## ☕ Me soutenir

<p align="center">
  <a href="https://buymeacoffee.com/majoiefaya" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=flat-square&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee"/>
  </a>
</p>

# Student Bulletin – Application de gestion des étudiants (Tkinter)

> Une application bureautique développée en **Python** avec **Tkinter** permettant de gérer les étudiants, leurs notes et de générer des bulletins scolaires. Interface simple, intuitive et locale.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Tkinter-GUI-blue?style=flat-square" alt="Tkinter"/>
  <img src="https://img.shields.io/badge/Type-Bureautique-orange?style=flat-square" alt="Desktop"/>
  <img src="https://img.shields.io/badge/Status-Terminé-brightgreen?style=flat-square" alt="Status"/>
</p>

<h3 align="center">• • •</h3>

## Fonctionnalités principales

- Enregistrement des étudiants avec informations personnelles
- Ajout des notes par matière
- Calcul automatique des moyennes
- Gestion des matières, classes et bulletins
- Génération d’un bulletin au format lisible et imprimable

<h3 align="center">• • •</h3>

## Technologies utilisées

| Élément         | Détail                         |
|-----------------|---------------------------------|
| Langage         | Python 3                        |
| Interface       | Tkinter                         |
| Base de données | MySQL (via mysql-connector)     |
| Export          | tkinter + gestion locale        |
| Déploiement     | PyInstaller (exécutable .exe)   |

<h3 align="center">• • •</h3>

## Lancer le projet localement

```bash
# 1. Cloner le dépôt
git clone https://github.com/majoiefaya/Student-Bulletin.git
cd Student-Bulletin

# 2. Installer les dépendances
pip install -r requirements.txt

# 3. Lancer l’application
python main.py
```

<h3 align="center">• • •</h3>

## Capture d’écran

<p align="center">
  <table>
    <tr>
      <td align="center">Accueil du bulletin<br/>
        <img src="https://github.com/majoiefaya/Student-Management/blob/main/ASSETS/images/bulletin_accueil.png?raw=true" width="300"/>
      </td>
      <td align="center">Infos élèves<br/>
        <img src="https://github.com/majoiefaya/Student-Management/blob/main/ASSETS/images/info_seleves.png?raw=true" width="300"/>
      </td>
      <td align="center">Bulletin par matière<br/>
        <img src="https://github.com/majoiefaya/Student-Management/blob/main/ASSETS/images/bulletin_matieres.png?raw=true" width="300"/>
      </td>
      <td align="center">Interrogation<br/>
        <img src="https://github.com/majoiefaya/Student-Management/blob/main/ASSETS/images/Interrogation.png?raw=true" width="300"/>
      </td>
    </tr>
  </table>
</p>

<h3 align="center">• • •</h3>

## 📦 Générer un exécutable (.exe)

> Pour créer une version distribuable sans installer Python :

```bash
pip install pyinstaller
pyinstaller --onefile --windowed main.py
```

Le fichier `.exe` final est disponible dans le dossier `dist/`.

<h3 align="center">• • •</h3>

## 📄 Licence

Application personnelle développée par **Faya Lidao Majoie**.  
Utilisation libre à des fins éducatives ou personnelles.

<h3 align="center">• • •</h3>

## ☕ Me soutenir

<p align="center">
  <a href="https://buymeacoffee.com/majoiefaya" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=flat-square&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee"/>
  </a>
</p>

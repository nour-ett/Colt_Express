# 🎲 Colt Express – Projet de Programmation Orientée et Génie Logiciel en Java


## 📝 Description

Ce projet est une adaptation numérique du jeu **Colt Express**, développée en Java dans le cadre d’un projet universitaire. Il met en œuvre des concepts de **programmation orientée objet**, de **conception MVC (Modèle-Vue-Contrôleur)** et de **programmation d'interfaces graphiques** avec **Swing**.

L’application simule les deux phases du jeu (planification des actions et exécution) avec des animations, de l’audio, et une interface utilisateur complète.

---

## 📁 Contenu du dépôt

- `ColtExpress.jar` : Fichier exécutable du jeu.
- `Rapport_POGL.pdf` : Rapport décrivant l’architecture et le déroulement du projet.
- `Diagramme_Classe.pdf` : Diagramme de classes UML du projet.

---

## 🛠️ Fonctionnalités principales

- Interface graphique divisée en trois vues : commandes, train, informations bandits.
- Affichage dynamique des éléments : bandits, marshall, wagons, butins.
- Intégration de sons : musique de fond, tirs, bouton muet.
- Affichage de l’état du jeu dans la fenêtre principale.
- Deux phases de jeu : planification puis exécution.
- Fenêtre de démarrage avec bouton **Start Game** et option de rejouer.

---

## 🧠 Architecture logicielle

Le projet repose sur le modèle **MVC** :

- **Modèle** : gestion de l’état du jeu et des entités (joueurs, wagons, butins).
- **Vue** : interface graphique composée de sous-vues (JPanels personnalisés).
- **Contrôleur** : gestion des interactions utilisateur via des `ActionListener`.

Le tout est synchronisé grâce au **pattern Observer** entre le modèle et la vue.

---

## 🚀 Lancement

1. Télécharger le fichier `ColtExpress.jar`.
2. Double-cliquer sur le fichier (Java doit être installé).
3. Cliquer sur **Start Game** pour démarrer une partie.

---


## 👥 Membres du projet
- **ETTAYEB Nour**
- **FABREGA Isabel**  
Licence 2 Informatique

---

# 🎲 Colt Express – Java GUI Programming Project


## 📝 Description

This project is a digital adaptation of the board game **Colt Express**, developed in Java as part of a university project. It applies concepts such as **object-oriented programming**, the **MVC (Model-View-Controller)** design pattern, and **GUI development** using **Swing**.

The application simulates the two main phases of the game (action planning and execution) with animations, sound, and a full graphical user interface.

---

## 📁 Repository Contents

- `ColtExpress.jar` – Executable game file.
- `Rapport_POGL.pdf` – Report explaining the project architecture and implementation.
- `Diagramme_Classe.pdf` – UML class diagram representing the system structure.

---

## 🛠️ Key Features

- GUI divided into three views: command panel, train display, and bandit info.
- Dynamic rendering of elements: bandits, marshal, wagons, loot.
- Integrated audio: background music, gunfire sounds, and mute button.
- Game state shown in the main window (not the console).
- Two game phases: planning and action.
- Startup screen with **Start Game** button and replay option.

---

## 🧠 Software Architecture

The project follows the **MVC** architecture:

- **Model**: Handles game state and entities (players, wagons, loot).
- **View**: GUI organized in custom JPanel sub-views.
- **Controller**: Manages user actions via `ActionListener` logic.

An **Observer pattern** is used to keep the view synchronized with the model.

---

## 🚀 Launch Instructions

1. Download the `ColtExpress.jar` file.
2. Double-click the file (Java must be installed).
3. Click **Start Game** to begin the game.

---
## 👥 Project Members
- **ETTAYEB Nour**
- **FABREGA Isabel**  
2nd Year Computer Science – University Project

---



Readme · MD
# Inscryption-like Game (SAE)
 
---
 
## 🇫🇷 Français
 
### À propos du projet
 
Application en Java simulant une version simplifiée du jeu de cartes tactique *Inscryption*. Le projet intègre la gestion d'un plateau de jeu à deux lignes, de mécaniques de pioche, de sacrifices de cartes (sang et os), ainsi que l'implémentation de différents pouvoirs spéciaux pour les cartes animaux. Projet académique de groupe réalisé dans le cadre de la SAE (IUT Robert Schuman - Université de Strasbourg).
 
### Fonctionnalités et Contributions principales
 
- **Moteur de jeu & Plateau :** Gestion des tours, des emplacements de cartes (lignes joueur et adversaire) et du système de score (balance).
- **Système de cartes & Pouvoirs :** Implémentation des cartes animaux, des obstacles et des capacités spéciales (*Nombreuses vies*, *Croissance*, *Puant*, *Coureur*, *Contact mortel*, *Piques pointues*, etc.).
- **Tests unitaires :** Couverture de test rigoureuse via JUnit pour valider les règles du jeu, les attaques et les mécaniques de combat.
- **Intégration de l'infrastructure globale :** Assemblage des composants du projet de groupe (modèles, vues, moteur et structure MVC).
### Technologies et Outils
 
- **Langage :** Java
- **Tests :** JUnit 4.13.2, Hamcrest 1.3
- **Modélisation :** PlantUML (`uml/`)
- **Contrôle de version :** Git / GitHub
---
 
## 🇬🇧 English
 
### About the project
 
A Java application simulating a simplified version of the tactical card game *Inscryption*. The project implements a two-row game board, deck management, card sacrifice mechanics (blood and bones), and various special animal card powers. Academic group project built as part of a SAE (IUT Robert Schuman - University of Strasbourg).
 
### Main Features & Contributions
 
- **Game Engine & Board:** Turn management, card slots (player and opponent rows), and score tracking (scale mechanics).
- **Card System & Powers:** Implementation of animal cards, obstacles, and special abilities (*Many Lives*, *Growth*, *Stinky*, *Mover*, *Deadly Touch*, *Sharp Spikes*, etc.).
- **Unit Testing:** Rigorous test coverage using JUnit to validate game rules, attacks, and combat mechanics.
- **Group Project Integration:** Assembly and refinement of core components across the team (models, views, engine, and MVC structure).
### Technologies & Tools
 
- **Language:** Java
- **Testing:** JUnit 4.13.2, Hamcrest 1.3
- **Modeling:** PlantUML (`uml/`)
- **Version Control:** Git / GitHub
---
 
## 📦 Installation & Utilisation / Installation & Usage
 
### 🇫🇷 Français
 
#### Option 1 : Téléchargement direct (Recommandé - Windows)
 
Aucune installation de Java n'est nécessaire.
 
1. Rends-toi dans l'onglet [**Releases**](https://github.com/AndreasColino/project-inscription/releases) de ce dépôt.
2. Télécharge l'archive `InscriptionLike_v1.0.0_win-x64.zip`.
3. Extrais l'intégralité de l'archive dans un dossier.
4. Double-clique sur `InscriptionLike.exe` pour lancer la partie directement dans le terminal.
#### Option 2 : Exécution depuis les sources (IDE)
 
1. **Cloner le dépôt :**
```bash
   git clone https://github.com/AndreasColino/project-inscription.git
```
 
2. **Ouvrir le projet :**
   Ouvre le dossier dans ton IDE Java (IntelliJ IDEA, Eclipse, VS Code).
3. **Dépendances :**
   Les bibliothèques de test (`junit-4.13.2.jar` et `hamcrest-core-1.3.jar`) sont incluses dans le dossier `deps/`. Ajoute-les au Build Path / classpath du projet si nécessaire.
4. **Lancer :**
   Exécute la classe principale `src/Main.java`.
### 🇬🇧 English
 
#### Option 1: Standalone Download (Recommended - Windows)
 
No Java installation required.
 
1. Go to the [**Releases**](https://github.com/AndreasColino/project-inscription/releases) section of this repository.
2. Download `InscriptionLike_v1.0.0_win-x64.zip`.
3. Extract the entire ZIP archive to a folder.
4. Double-click `InscriptionLike.exe` to run the game directly in the console.
#### Option 2: Run from Source (IDE)
 
1. **Clone the repository:**
```bash
   git clone https://github.com/AndreasColino/project-inscription.git
```
 
2. **Open the project:**
   Open the project directory in your Java IDE (IntelliJ IDEA, Eclipse, VS Code).
3. **Dependencies:**
   Test libraries (`junit-4.13.2.jar` and `hamcrest-core-1.3.jar`) are located in the `deps/` folder. Add them to your project's build path / classpath if needed.
4. **Run:**
   Execute the main class located at `src/Main.java` to start the game in the console.
 

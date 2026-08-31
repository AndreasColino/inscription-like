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

1. **Cloner le dépôt :**

   ```bash
   git clone https://github.com/AndreasColino/project-inscription.git
   ```

2. **Ouvrir le projet :**
   Ouvre le dossier dans ton IDE Java (IntelliJ IDEA, Eclipse, VS Code).

3. **Dépendances :**
   Les bibliothèques de test (`junit-4.13.2.jar` et `hamcrest-core-1.3.jar`) sont incluses dans le dossier `deps/`. Assure-toi de les ajouter au Build Path / classpath du projet si nécessaire.

4. **Compiler et exécuter :**
   Lance la classe principale située dans `src/Main.java` pour démarrer la partie dans la console.

### 🇬🇧 English

1. **Clone the repository:**

   ```bash
   git clone https://github.com/AndreasColino/project-inscription.git
   ```

2. **Open the project:**
   Open the project directory in your Java IDE (IntelliJ IDEA, Eclipse, VS Code).

3. **Dependencies:**
   Test libraries (`junit-4.13.2.jar` and `hamcrest-core-1.3.jar`) are located in the `deps/` folder. Make sure to add them to your project's build path / classpath if needed.

4. **Compile and run:**
   Run the main class located in `src/Main.java` to start the game directly in the console.

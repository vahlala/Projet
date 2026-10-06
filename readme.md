# Opération Insecticide

> Titre provisoire

**Créateur :** Arthur Durand Nuekumo Simo
**Cours :** 420-0SW – Programmation jeux et multimédias, Cégep de Shawinigan
**Moteur :** Godot 4

## Concept

Des insectes géants envahissent la Terre, et tu es le dernier soldat capable de les arrêter. *Opération Insecticide* est un jeu de tir à défilement horizontal (*run and gun*) inspiré de *Metal Slug* : tu avances dans chaque mission, tu élimines des vagues d'insectes avec tes armes et tes grenades, tu libères les humains prisonniers de cocons, puis tu affrontes la Reine, le boss de fin.

## Objectifs du jeu

- Traverser la mission jusqu'à la fin sans perdre toutes ses vies. Une seule attaque suffit à faire perdre une vie.
- Éliminer les insectes pour faire le meilleur score possible.
- Libérer les otages pour gagner des armes, des grenades et des points bonus.
- Vaincre le boss de fin de mission.

## Contrôles

| Action | Clavier | Manette / borne |
|---|---|---|
| Se déplacer | ← → | Joystick |
| Viser en haut | ↑ | Joystick haut |
| S'accroupir / viser en bas (en saut) | ↓ | Joystick bas |
| Sauter | *à définir* | *à définir* |
| Tirer / couteau (au corps à corps) | *à définir* | *à définir* |
| Lancer une grenade | *à définir* | *à définir* |
| Pause | P | *à définir* |
| Couper le son | Ctrl + M | — |
| Informations de débogage | F12 | — |

## Ennemis prévus

| Insecte | Comportement |
|---|---|
| Fourmi soldat | Infanterie de base, attaque en groupe |
| Termite | Surgit du sol par surprise |
| Guêpe | Vole et attaque en piqué |
| Araignée | Descend du plafond, sa toile ralentit le joueur |
| Scarabée blindé | Résiste aux balles, vulnérable aux explosifs |
| Criquets | Essaim rapide et fragile |
| Mante religieuse | Mini-boss, combat au corps à corps |
| La Reine | Boss final, plusieurs phases, pond des larves |

## Armes

- **Pistolet** : munitions infinies.
- **Mitrailleuse, roquettes, lance-insecticide, fusil à pompe** : armes spéciales à munitions limitées, trouvées dans des caisses ou données par les otages libérés.
- **Grenades** : en nombre limité.

## Concepts et algorithmes

*Cette section sera complétée au fil du développement.*

- **Machines à états finis** : comportement du joueur et des insectes
- **Boids** : déplacement en essaim des guêpes et des criquets (algorithme fait sans bibliothèque)
- **A\*** : recherche de chemin des termites sous terre (algorithme fait sans bibliothèque)

## Structure du dépôt

```
.
├── readme.md   Ce document
└── src/        Projet Godot
```

## Lancer le projet

1. Installer [Godot 4](https://godotengine.org/download).
2. Dans Godot, ouvrir le fichier `src/project.godot`.
3. Appuyer sur **F5** pour lancer le jeu.

## Sources et crédits

*À compléter : sources consultées, assets utilisés et leurs licences.*

- Inspiration : *Metal Slug* (SNK, 1996). Aucun élément graphique ni sonore du jeu original n'est utilisé.
- Notes du cours 420-0SW : https://nbourre.github.io/0sw_notes_cours/

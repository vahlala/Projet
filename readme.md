# Call of insects

**Créateur :** Arthur Durand Nuekumo Simo
**Cours :** 420-0SW – Programmation jeux et multimédias
**Moteur :** Godot 4.7.2

## Description

Des insectes géants envahissent la Terre, et tu es le dernier soldat capable de les arrêter. Call of insects est un jeu de tir à défilement horizontal (*run and gun*) inspiré de *Metal Slug* : tu avances dans chaque mission, tu élimines des vagues d'insectes avec tes armes et tes grenades, tu libères les humains prisonniers de cocons, puis tu affrontes la Reine, le boss de fin.

## Objectifs du jeu

- Traverser la mission jusqu'à la fin sans perdre toutes ses vies. Une seule attaque suffit à faire perdre une vie.
- Éliminer les insectes pour faire le meilleur score possible.
- Libérer les otages pour gagner des armes, des grenades et des points bonus.
- Vaincre le boss de fin de mission.

## Contrôles

| Action | Clavier | Manette / borne |
|---|---|---|
| Se déplacer | ← → / A D | Joystick |
| Viser en haut | ↑ / W| Joystick haut |
| S'accroupir / viser en bas (en saut) | ↓ / S | Joystick bas |
| Sauter | F | *à définir* |
| Tirer / couteau (au corps à corps) | T | *à définir* |
| Lancer une grenade | G | *à définir* |
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

## Concepts et algorithmes

*Cette section sera complétée au fil du développement.*

- **Machines à états finis** : comportement du joueur et des insectes
- **Boids** : déplacement en essaim des guêpes et des criquets (algorithme fait sans bibliothèque)
- **A\*** : recherche de chemin des termites sous terre (algorithme fait sans bibliothèque)



## Sources et crédits

*À compléter : sources consultées, assets utilisés et leurs licences.*

- Inspiration : *Metal Slug* (SNK, 1996). Aucun élément graphique ni sonore du jeu original n'est utilisé.
- Notes du cours 420-0SW : https://nbourre.github.io/0sw_notes_cours/

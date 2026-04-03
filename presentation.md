# Présentation — Dark Quest 2D

**Trophées NSI 2025-2026 — Dossier n°2110**  
Lycée Français Alioune Blondin Beye — Luanda, Angola

\---

## 1\. Résumé

Python Adventure est un jeu éducatif de plateformes en 3D conçu pour initier les débutants à la programmation fonctionnelle. Le joueur progresse dans un niveau unique divisé en deux plateformes et doit placer correctement des blocs de code dans les murs pour avancer. Le jeu enseigne les bases de la logique, des conditions, des boucles et de la programmation fonctionnelle de manière interactive et ludique. Il est développé avec Blender pour la modélisation et l’animation et Unreal Engine avec Blueprint pour toute la logique du jeu. L’accent est mis sur l’apprentissage progressif : chaque plateforme introduit de nouveaux concepts de code et prépare à des notions plus avancées (POO, récursivité) prévues pour la suite.\---

## 2\. Description détaillée

Python Adventure est réalisé entièrement avec Blender et Unreal Engine. Aucun langage Python n’a été utilisé pour la logique du jeu : tout le code fonctionne via Blueprint, le système de scripts visuels d’Unreal Engine. Blender a été utilisé pour la création des modèles 3D, des textures, et des animations des personnages et objets.

Le jeu est pensé pour les apprentis programmeurs : chaque plateforme introduit progressivement des blocs de code à placer pour résoudre des défis. Les plateformes combinent des éléments de réflexion et de mouvement, offrant un apprentissage pratique de la programmation fonctionnelle.

Remarque : le jeu n’est pas encore terminé. Une suite était prévue pour intégrer des niveaux plus complexes avec programmation orientée objet, récursivité et mécanismes avancés, mais le temps a limité la réalisation.
### Structure des fichiers

|Fichier|Rôle|
|-|-|
Fourmi.blend|Modélisation et animation de la Fourmi 3D
Python.blend|Modélisation et animation du personnage Python en 3D
python_adventure.uproject|Projet complet du jeu vidéo sur Unreal Engine
Terrain_design.fbx|Ensemble des plateforms en 3d utilisées sur la maps dans Unreal Engine
vie_python.png|Design des vies situées en haut à droite de l'écran dans le jeu, généré par l'IA
Fond_d'ecran_python_adventure.png|Image de fond montrée au Menu du jeu, généré par l'IA


### Mécanique de jeu

 •	Niveau unique avec deux plateformes : chaque plateforme introduit progressivement de nouveaux concepts de programmation fonctionnelle.
 •  Blocs de code à placer : le joueur doit positionner correctement les blocs de code dans les murs pour progresser. Placer un bloc incorrect fait perdre une vie.
 •  Système de vies : le personnage possède trois vies. Perdre les trois vies entraîne la fin du jeu.
 •  Interactions avec les ennemis : certaines séquences comportent un ennemis, comme la fourmi.Se faire attaquer par cet ennemi peut faire perdre des vies. Si le joueur perd ses trois vies lors d’un combat ou d’une erreur de code, la partie s’arrête.
 •  Progression pédagogique : apprentissage étape par étape, avec retour immédiat en cas d’erreur, pour encourager la réflexion et la correction.
 •  Personnages et objets interactifs : animés avec Blender et intégrés via Blueprint.
 •  Système de score et HUD : suivi des réussites, échec et vies pour guider l’apprentissage.


\---

## 3\. Nature du code et répartition du travail

Le projet est une création originale, entièrement développé en Blueprint, un système de programmation visuelle basé sur des nœuds. Contrairement à Python, qui repose sur du code écrit, Blueprint permet une approche plus intuitive et accessible à tous, notamment aux débutants. Ce choix répond strictement à la consigne interdisant l’usage du C++, sans utiliser de langage externe.

### Freddy TCHONMO

 •	Modélisation des personnages 3D et décors (Fourmi.blend, Python.blend)
 
 •  Création des squelettes et animations 
 
 •  Textures, matériaux, et effets visuels des plateformes

### Gianni Diemmi-Melley

•	Mise en place des mécaniques de jeu (attraper, déplacer et poser des objets)

•	Création d’une interface claire et intuitive permettant au joueur de comprendre et interagir facilement avec le jeu.

•	Réalisation de séquences animées avec gestion des caméras et du timing pour renforcer l’immersion.

•	Compilation et optimisation du jeu pour le rendre jouable de manière autonome sur une plateforme cible.

•   Création de la maps virtuelle du jeu (plateforms, mur, programme, blocs etc...)





\---

## 4\. Utilisation de l'Intelligence Artificielle

Conformément aux règles du concours, l’équipe déclare de manière transparente les usages de l’intelligence artificielle dans ce projet.

L’intelligence artificielle a été utilisée principalement pour la création du logo, des icônes et de certains éléments visuels de l’interface (écran d’accueil, boutons, identité graphique). Ces éléments ont ensuite été adaptés et intégrés manuellement dans le jeu.
Par ailleurs, certains éléments visuels du jeu, notamment une partie des plateformes, ont été téléchargés depuis la plateforme Sketchfab. Ces ressources ont ensuite été intégrées et adaptées dans l’environnement Unreal Engine pour correspondre au projet.
L’équipe garantit que l’usage de l’intelligence artificielle et de ressources externes est resté limité, encadré et transparent.



### Bilan global

Élément	|Équipe	|IA Externe
|-|-|-|

Code et logique du jeu (Blueprint)	|100 % original	|0 %
Modélisation et animation 3D (Blender)	|100 % original	|0 %
Plateformes et certains assets 3D	|Intégration et adaptation	|Assets téléchargés (Sketchfab)
Scénario et game design	|100 % original	|0 %
Contenu pédagogique (apprentissage code)	|100 % original	|0 %
Logo et icônes	|Intégration et adaptation	|Génération assistée par IA

L'équipe certifie que le code, le scénario et le contenu pédagogique constituent une production originale, et que tous les usages de l'IA ont été limités, réfléchis et transparents.


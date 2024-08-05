**Consignes**

- Créer un milestone pour la release SI besoin (priorité à ceux qui ont l'habitude de Github)
- Créer une issue pour la traduction d'un fichier / correction à apporter / doc à modifier ou ajouter SI besoin (priorité à ceux qui ont l'habitude de Github)
- Créer une branche pour l'issue en assignant un reviewer et un assignee, mettre les labels corrects et le bon milestone
- Traduire en privilégiant les termes spécifiques choisis par l'équipe (voir glossaire) et en mettant en avant l'idée d'une phrase si nécessaire au contexte
- Interdit de push la branche sans avoir reçu l'approbation du reviewer

Dans l'ordre normal des choses, un traducteur arrive et il existe une issue pour chaque fichier à traduire dans le milestone en cours avec ses consignes (si fichier très long, décomposer en plusieurs issues, chaque issue allant max à 1000 lignes et si fichier trop court (-50 lignes, issue commune à un autre fichier).

**Utilisation de git et comment traduire les fichiers .rpy**

Le traducteur créer alors une branche pour l'issue après s'être assigner dessus, puis clone le repo en local (gh repo clone Rosstail/JPDE2-french) avant de se placer sur la branche, "git branch" pour vérifier la branche actuelle (en vert) et "git switch NomDeLaBranche" pour se déplacer.

Ce dernier ouvre le fichier avec n'importe quel logiciel (un IDE n'est pas forcément nécessaire mais ça aide pas mal). La traduction est expliquée plus bas. Une fois celle-ci finie, le traducteur procède à un "git status", vérifie que le fichier de traduction soit "modified", puis réalise un "git add nomDuFichier.rpy", suivi d'un "git commit -m "Message du commit, changements apportés"", et finalement d'un "git push".

![image_2024-07-23_011147357](https://github.com/user-attachments/assets/111240ed-3036-46cd-a13a-aa594e291072)

Un fichier de traduction par ce format. 
La première ligne (#) est un commentaire utile pour les dév et correcteurs/testeurs.
La seconde ligne est la ligne dans la langue par défaut. La troisième est la ligne qui va la remplacer.
Tous 'code' doit être copié collé dans la même ponctuation (espacement). L'écrire soi-même peut mener à des fautes et une légère perte de temps.

**Pour les seniors du Github (milestone/issues)**

Un milestone doit avoir une due date, pour se fixer des limites et s'encourager à travailler. Un milestone = une release.
Une issue doit se nommer "Rx - Nom des fichiers" où x est le numéro de la release.
"R2 - Credits"
Dans la description, doivent être indiqués le chemin du/des fichier.s (/chemin de son dossier/ + url de son dossier) et sa longueur en lignes.

Lors d'un nouvel épisode, une branche doit être créée pour merge les nouveaux fichiers avec les anciens, il est interdit de merge la branche avant d'avoir eu une review, comme toutes les autres.
Pour les conflits, il faut les résoudre. Si c'est le cas, c'est que du texte a été ajouté, il faut donc le notifier par une issue.

**Glossaire**

_Termes du monde de RWBY_
- Huntsmen/Huntresses -> Chasseurs/Chasseuses
- Aura -> (une) Aura
- Semblance -> (une) Semblance
- Team (RWBY/JPDE/JNPR) -> Équipe (RWBY/JPDE/JNPR)
- Dust -> (le) Dust
- Faunus -> un Faunus, des Fauni (une femme Faunus -> une Faunus)
- Noms propres en EN (Pays, villes, personnages, armes, entreprises etc) -> Restent les mêmes en FR
- Grimm -> un Grimm, des Grimms (les créatures de Grimm) Les types comme "Beowolves" garderont les noms EN au masculin
- God of Light/God of Darkness -> Dieu de la Lumière/Dieu des Ténèbres
- Relics -> Reliques
- Silver-Eyed Warrior.s -> Guerrier.s aux yeux argentés
- Summer Maiden (et Winter/Fall/Spring Maidens) -> Dame.s de l'Été (et de l'Hiver/de l'Automne/du Printemps)
- Plus à venir 

_Termes techniques_
- Self-voicing -> Narration
- Clipboard voicing -> Narration du presse-papier
- Viewport -> Fenêtre
- Accessibility Menu -> Menu Accessibilité
- High contrast text -> Texte à haut contraste
- Font Override -> Remplacer police
- Default -> Par défaut
- DejaVu Sans/Opendyslexic -> Noms de polices, ne pas changer
- Text-to-speech/Debug/Transition/Tearing/Framerate/Preload/Ren'Py Sync server/Sync ID/Updater/Joystick/Gamepad/BBCode/Markdown/Parsing -> Garder comme tels
- Tag -> Balise
- Statement -> Déclaration
- Attributes -> Attributs
- Transform -> Transformation
- Channel -> Canal
- Skip Mode -> Mode Passage Rapide
- Skip -> Passer
- Display -> Affichage
- Auto-forward -> Lecture automatique
- Rollback -> Retour en arrière
- Powersave -> Économie d'énergie
- Renderer -> Moteur de rendu
- Slideshow -> Diaporama

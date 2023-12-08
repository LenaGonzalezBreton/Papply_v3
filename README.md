
# Papply

A software developped by FloppyDisks for teachers.
You can easily manage practical works you gave to your students.

## Features

- CRUD Practical Works
- Students Managements
- Validation tasks
- DashBoard with stats


# Papply

Papply will be a software usable by our Teacher to check our practical work and see our progress


![Logo](https://github.com/LenaGonzalezBreton/Papply/blob/master/Assets/Papply_logo.png)

## Features

- CRUD Practical Work
- DashBoard
- Stats
- Students Management
- Tasks Validation





## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Accent color | ![#FF3D00](https://via.placeholder.com/10/FF3D00?text=+) #FF3D00 |
| Background Color | ![#D9D9D9](https://via.placeholder.com/10/D9D9D9?text=+) #D9D9D9 |
| Navbar Color | ![#9190CD](https://via.placeholder.com/10/9190CD?text=+) #9190CD |
| Button Color | ![#41448A](https://via.placeholder.com/10/41448A?text=+) #41448A |
| Text Color | ![#191C58](https://via.placeholder.com/10/191C58?text=+) #191C58 |
| Text2 Color | ![#FFFFFF](https://via.placeholder.com/10/FFFFFF?text=+) #FFFFFF |



## Comment taffer à plusieurs
Après le pull de ce travail (depuis un cmd à l'emplacement voulu : 'git clone https://github.com/LenaGonzalezBreton/Papply_v3.git') il est indispensable de travailler sur une branche à repérable.

Vous pouver la créer depuis votre terminal sur votre IDE : 'git branch nomdelabranche'

_Gardez la même nomenclature_ : nom-fonctionnalité-précision

Exemple: lena-dashboard-récapitulatif

Vérifiez que vous êtes sur cette branche avec la commande : git branch (vous devriez voir une étoile à coté du nom de la branche sur laquelle vous travaillez). Si vous n'êtes pas sur la bonne branche entrez la commande : git switch nomdelabranche.
### Une fois que vous considérez avoir terminé votre tâche
#### Si votre gitignore fonctionne pour le bin :
Entrez ces commandes :

'git add .' (ajoutera toutes les modification dans un fichier temporaire)

'git commit -m "Commentaires et précision sur votre travail"' (préparera le fichier à envoyer en lui donnant une description)

'git push origin nomdelabranche' (envoi de vos modification depuis la source (origin) à la destination (nomdelabranche))

#### Si votre gitignore ne fonctionne pas pour le bin :

Fermez votre IDE et rendez vous manuellement dans les fichiers de votre projet et supprimez le dossier bin

Entrez ces commandes :

'git add .' (ajoutera toutes les modification dans un fichier temporaire)

'git commit -m "Commentaires et précision sur votre travail"' (préparera le fichier à envoyer en lui donnant une description)

'git push origin nomdelabranche' (envoi de vos modification depuis la source (origin) à la destination (nomdelabranche))

Pour ce qui est des merges des différentes branches, je gère.

## Interdiction de push sur master

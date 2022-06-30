*Ce projet est réalisé dans le cadre du module Communication Sans Fil en Licence 1 à l’Université Nice Sophia Antipolis*

# Le Projet
Ce projet à but uniquement visuel à été créé dans un but décoratif essentiellement, pouvoir faire un panneau led d'1m/30cm (taille réduite dans le cadre du projet) qui pourrait troner au milieu d'un salon ou d'une piece de vie commune par exemple. L'idée c'est de pouvoir afficher le spectre audio des musiques écoutées dans la pièce.
## Musicwall V1 (*obsolète*)
Dans cette première version nous comptions utiliser une carte Uno et utiliser bluetooth grâce à un recepteur audio pour faire la liaison entre l'appareil mettant la musique et la carte malheuresement il nous fallait plus de connaissances sur le sujet, cette version a donc été abandonnée après avoir eu les yeux plus gros que le ventre (on a aussi songé à utiliser un ESP32 mais il etait inutilisable hélas)
### 1) Materiel:
-Carte Uno

-Matrice de Led MAX7219 en 8x32

-recpeteur audio

-cables

### 2) Schéma
![Schéma](https://user-images.githubusercontent.com/102424510/176749572-479688df-4e5b-43de-a6d1-5847cdcb3d19.png)
## Musicwall V2 (*obsolète*)
Dans cette version on a décidé de supprimer l'idée du bluetooth et de directement lier l'appareil mettant la musique et la carte au moyen d'une prise jack pour envoyer l'audio sur un des ports de la carte on a aussi réduit la taille de la matrice car l'autre modèle etait introuvable, malgrès un peu de soudure et d'essais on a du stoper l'idée car de toute évidence quelque chose clochait (c'etait la matrice mais on l'ignorait sur l'instant)
### 1) Materiel:
-Carte Uno

-Matrice de Led MAX7219 en 8x8

-jack stereo 3,5mm à souder

-cables
### 2) Montage
![IMG_2042](https://user-images.githubusercontent.com/102424510/176756634-6addc4ec-6a9f-48b3-86f1-3c6ea51745b3.jpg)

## Musicwall VFinale
Pour cette dernière version on a troqué le jack contre un module micro connectéé à la carte permettant de capter le son qui passse
### 1) Matériel:
-Carte Uno

-Matrice Led MAX7219 en 8x8

-Module micro pour arduino

-cables

### 2) Montage
![IMG_2044](https://user-images.githubusercontent.com/102424510/176756737-53ee8671-eeb0-4814-9696-0ea2ef2f7091.jpg)



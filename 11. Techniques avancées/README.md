Section 11 : Techniques avancées
===

## Information
- Title: `Techniques avancées`
- Authors:  `Etienne KOA`


## Récapitulatif des attributs pour la vidéo et l'audio
Les vidéos et les pistes musicales ont exactement les mêmes attributs.

1. `controls`  : pour afficher les boutons de lecture, pause, la gestion du volume (et faire aller votre vidéo)
2. `width`  : largeur
3. `height`  : hauteur
4. `loop`  : lecture en boucle
5. `autoplay`  : jouer automatiquement au chargement
6. `preload`  : charger ou non les données en avance
    a. `auto`  : par défaut, le navigateur choisit
    b. `metadata`  : charge les métadonnées (durée...)
    c. `none`  : non

## Récapitulatif des balises pour les medias queries

Pour les types de `media` , vous avez le choix entre :

1. `screen`: écran d'ordinateur
2. `handheld`: périphérique mobile
3. `print`: tout ce qui est imprimante et impression
4. `tv`: télévision
5. `projection`: projecteur
6. `all`: tous les types d'écran


Vous pouvez aussi choisir plusieurs paramètres :

1. `color`: gestion de la couleur (bits/pixel)
2. `height`: hauteur de la fenêtre
3. `width`: largeur de la fenêtre
4. `device-height`: hauteur du périphérique
5. `device-width`: largeur du périphérique
6. `orientation`: orientation du périphérique (portrait / paysage)


|Navigateur| Largeur du `viewport` par défaut|
|----------|---------------------------------|
|Windows| Phone 1024 pixels|
|iPhone| Safari 980 pixels|
|Android| 800 pixels|
|Opera Mobile| 850 pixels|

## Quizz

**Question 1 :**

Il est possible de mettre plusieurs types de vidéos pour être sûr qu'il y en aura au moins une de compatible avec le navigateur ?

```
                Vrai
```

**Question 2 :**

Quel code est valide pour ajouter une vidéo sur son site internet ?

```
<video controls>
    <source src="movie.mp4" type="video/mp4">
    <source src="movie.ogg" type="video/ogg">
Votre navigateur ne détecte aucune vidéo compatible.
</video>
```

**Question 3 :**

Mettre une musique, c'est globalement le même procédé que pour mettre une vidéo.

```
                Vrai
```

**Question 4 :**

Quel attribut n'existe `pas` ?

```
                loop
                command (*)
                preload
                autoplay
```


**Question 5 :**

Pour définir le titre d'un tableau, nous devonsutiliser la balise :

```
                th
```

**Question 6 :**

Pour fusionner deux cellules de tableau horizontalement j'utilise :

```
                colspan
```


## Directory Hierarchy

```
|—— design
|    |—— default.css
|—— firstproject.html
|—— index.html
|—— pictures
|    |—— bensound.mp3
|    |—— Etixi_logo.png
|    |—— favicon.png
|    |—— illustration_1.png
|    |—— illustration_2.jpg
|    |—— illustration_3.jpg
|    |—— illustration_4.jpg
|    |—— illustration_5.jpg
|    |—— illustration_6.jpg
|    |—— logo.png
|    |—— presentation.png
|—— src
|    |—— theblacklist.ttf
```

Section 12 : Les varables et root
===

## Information
- Title:  `Les varables et :root`
- Authors:  `Etienne KOA`


## Récapitulatif sur les variables

+ Nous venons de voir l'utilisation de `:root` et des variables.



**Pour créer une variable**

![Variables](https://img-c.udemycdn.com/redactor/raw/2019-01-09_12-49-24-b40de62f1a0a0a4ed9a85635431fc14d.jpg)

**Pour utiliser une variable**

![Variables](https://img-c.udemycdn.com/redactor/raw/2019-01-09_12-51-54-e19013c2249dd108c14de5ae2b592e26.jpg)


**Où placer mes variables ?**

Pour placer vos variables, deux choix possibles :

+ Dans l'élément qui doit l'utiliser

Par exemple, si mon titre doit avoir une couleur rose et que je souhaite placer la valeur de la couleur dans une variable, je peux directement déclarer ma variable dans l'élément de mon titre.

Exemple :

```
h1 {
  --couleurPrimaire: pink;
  color: var(--couleurPrimaire);
}
```


Ainsi, ma variable est également réutilisable partout dans ma feuille de style.

+ Dans le sélecteur `:root` (recommandé)

Le fait de mettre mes variables dans le sélecteur :root permet de tout mettre au même endroit et de tout réutiliser où je le désire.

Exemple :

```
:root {
  --couleurPrimaire: pink;
}
 
h1 {
  color: var(--couleurPrimaire);
}
```

## Quizz

**Question 1 :**

Généralement, nous utilisons le sélecteur `:root` pour :

```
          Passer des variables
```

**Question 2 :**
Quel nom de variable est correctement orthographié ?

```
          couleurPrimaire
```

**Question 3 :**
Quel code est valide ?



```
:root {
  --maVariable : blue ;
  }

  p {
    color : var(--maVariable);
  }

```


## Directory Hierarchy
```
|—— root_exercice
|    |—— design.css
|    |—— selecteur.html
|—— variable_exercice
|    |—— background.jpg
|    |—— design.css
|    |—— index.html
```


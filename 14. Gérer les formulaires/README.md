Section 15 : Gérer les formulaires
===

## Information
- Title:  `Gérer les formulaires`
- Authors:  `Etienne KOA`


## Récapitulatif sur les formulaires

**Structure de base d'un formulaire**

```
<form action="page_de_destination.php" method="post">
   <p>Remplissez notre formulaire</p>
</form>
```

**Zone de texte monoligne**

```
<input type="text" name="prenom" /> 
```


**Zone de texte multiligne**

```
<textarea name="description"></textarea> 
```


**Balise des textes**

```
<label>Prénom</label> 
```


**Les attributs des inputs**

`type`  : le type de l'input (text / password / email / url / tel / number / range / color / date / search)

`placeholder`  : texte d'exemple à afficher

`name`  : nom de l'input (sert à classer les informations qui sont envoyées)

`size`  : permet d'agrandir le champ (nombre de caractères)

`maxlength`  : nombre de caractère maximum

`value`  : pour remplir le champ par défaut avec un texte

**Les éléments d'option**

```
<input type="checkbox" name="plat" />  : boite à cocher / checked : sélectionné par défaut

<input type="radio" name="plat" />  : bouton radio à cocher / checked: sélectionné par défaut
```


**Envoyer un formulaire**

```
<input type="submit" value="Je me connecte" />  : envoyer un formulaire
```


**Liste déroulante**

```
<select name="plat">
    <option value="saumon">Saumon</option>
</select>
```



## Quizz

**Question 1 :**

Quelle méthode d'envoi de données permet d'avoir des urls ayant les variables en visuel ? Exemple : comme google.

```
                  La méthode GET
```

**Question 2 :**
Je veux définir un nombre de caractères à ne pas dépasser sur mes inputs, quel attribut utiliser ?

```
                  MaxLength
```


**Question 3 :**
Laquelle de ces réponses concerne un type de bouton dont l'utilisateur ne peut sélectionner qu'un seul élément ?

```
                 <input type="radio" name="plat" />
```


## Directory Hierarchy
```
|—— formulaire.html
```

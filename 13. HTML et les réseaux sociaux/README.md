Section 13 : HTML et les réseaux sociaux
===

## Information
- Title:  `HTML et les réseaux sociaux`
- Authors:  `Etienne KOA`


## Twitter Card récapitulatif
+ Les `Twitter Cards` sont des outils que vous devez utiliser si vous souhaitez vous donner toutes les chances pour que votre site internet soit partagé le plus possible sur les réseaux sociaux.



## Récapitulatif

+ Voici un récapitulatif des propriétés à utiliser pour créer une `Twitter Card` pour votre site internet.

```
<meta name="twitter:card" content="summary">
<meta name="twitter:url" content="https://believemy.com">
<meta name="twitter:title" content="Believemy">
<meta name="twitter:description" content="L'objectif que nous recherchons est celui du bonheur, pour ça et pour tant d'autres raisons, celui-ci vient avec le développement de ses compétences. Notre objectif est d'amener ces personnes à réaliser leurs projets.">
<meta name="twitter:image" content="https://believemy.com/uploads/ff289bcbca98c1e1357d711c3bf24630_4e2f59fa63cc6e36dfd282f168b3a170.jpeg">

```


+ Voici en détail l'utilité de ces propriétés :

`twitter:card` : Le type de carte à créer (summary, photo ou vidéo)

`twitter:url` : L'url à partager

`twitter:title` : Le titre à montrer

`twitter:description` : Maximum 200 caractères de description

`twitter:image` : L'image à afficher



**Pour le type photo**

+ Le type de carte "photo" possède ses propres propriétés dans le but de personnaliser au maximum l'affichage de celle-ci sur les fils d'actualités.

```
<meta name="twitter:image:width" content="600">
<meta name="twitter:image:height" content="600">
```

`twitter:image:width` : largeur de l'image

`twitter:image:height` : hauteur de l'image



**Pour le type video (player)**

+ Tout comme le type photo, le type player possède quelques propriétés que vous devez fournir pour que votre vidéo soit publiée lorsque l'on partage l'url de votre site internet. On retrouve ce type de carte lorsque l'on partage des vidéos YouTube par exemple.

```
<meta name="twitter:player" content="https://believemy.com/videos/mavideo">
<meta name="twitter:player:width" content="1920">
<meta name="twitter:player:height" content="1080">
```

`twitter:player` : L'url HTTPS de l'iFrame de votre vidéo. L'iFrame, c'est tout simplement le lien vers votre lecteur de vidéo. Oui, il faut pour partager une vidéo que vous utilisiez un iFrame. C'est un concept très compliqué qui requiert beaucoup d'autres compétences, mais je souhaite quand même vous montrer comment faire si un jour l'idée vous vient de créer le votre.

`twitter:player:width` : Largeur de la vidéo à afficher

`twitter:player:height`: Hauteur de la vidéo à afficher



**Avantage d'utiliser les Twitter Cards**

Mais l'avantage des Twitter Cards se trouve être de pouvoir préciser le compte Twitter du site et de l'auteur.

```
<meta name="twitter:site" content="@believemyFR">
<meta name="twitter:creator" content="@nicolasleuillet">
```

`twitter:site` : Le compte Twitter du site

`twitter:creator` : Celui de l'auteur (ou du créateur si ce n'est pas un blog)



**Une dernière astuce**

Enfin, pour terminer je souhaite vous donner une dernière astuce. De base, voici un exemple de carte créée avec le type de carte "summary".

![twitter](https://img-c.udemycdn.com/redactor/raw/2019-01-10_09-02-13-56e69c6e2e4dd2664aad4c1643504fdb.png)

**Carte Summary**

Il est possible d'afficher l'image en très grand en précisant le type `summary_large_image` à la place de `summary`.

![twitter](https://img-c.udemycdn.com/redactor/raw/2019-01-10_09-03-23-144fef92c603461c15d2fc4dedc1dccc.png)


## Facebook Card (Open Graph Card) récapitulatif
Tout comme avec les Twitter Cards, Facebook propose aux administrateurs / développeurs de sites, de préciser quelques propriétés pour que leur contenu soit parfaitement diffusé sur le réseau social.



**Facebook Card ou Open Graph Card ?**

Facebook utilise les balises `Open Graph`, qui sont tout simplement des balises standards pour préciser le contenu d'une page. Un peu comme les balises h1 précisent le titre principal d'une page.

+ Voici comment utiliser les balises Open Graph pour Facebook.

```
<meta property="og:url"                content="http://www.nytimes.com/2015/02/19/arts/international/when-great-minds-dont-think-alike.html" />
<meta property="og:type"               content="article" />
<meta property="og:title"              content="When Great Minds Don’t Think Alike" />
<meta property="og:description"        content="How much does culture influence creative thinking?" />
<meta property="og:image"              content="http://static01.nyt.com/images/2015/02/19/arts/international/19iht-btnumbers19A/19iht-btnumbers19A-facebookJumbo-v2.jpg" />
```


Ce qui donne ce résultat (exemple venant de la documentation de Facebook) :


![Facebook](https://img-c.udemycdn.com/redactor/raw/2019-01-10_09-26-09-b6beaa2559daafd4f03d8773f3c9d080.png)



**Précisions sur les balises Open Graph**
Voici comment les balises Open Graph fonctionnent.

`og:url` : L'url de votre site (ou article de blog)

`og:type` : Le type de contenu que vous souhaitez partager.

`og:title` : Le titre du contenu

`og:description` : La description du contenu

`og:image` : L'image à afficher lorsqu'on partage votre lien



**Quelques derniers mots sur les types disponibles**

Facebook propose une dizaine de types possibles pour votre carte. Je vous conseille vivement d'aller sur cette [page](https://developers.facebook.com/docs/sharing/webmasters?locale=fr_FR) de la documentation Facebook pour tous les retrouver si vous avez besoin d'une carte spécifique.

Sachez ceci étant dit, que généralement, nous utilisons le type article. Qui est un type largement utilisé par la plupart des développeurs. Toutefois, si votre site propose par exemple la vente d'un livre, le type book est également possible et permet à Facebook de comprendre ce que vous souhaitez partager.



**La dernière astuce**
Si vous souhaitez voir à quoi correspond votre carte sans partager votre site sur Facebook, vous pouvez utiliser [le débogueur Facebook](https://developers.facebook.com/tools/debug/). Il vous suffira de coller le lien de votre site internet pour voir à quoi ressemble votre carte.

![Facebook](https://img-c.udemycdn.com/redactor/raw/2019-01-10_09-36-25-7dce501504e6bdd6c552b0d0ce846d03.png)


## Directory Hierarchy
```
|—— network.html
```



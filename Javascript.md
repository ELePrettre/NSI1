**Découvrir le Javascript **


Le langage Javascript n’est pas au “programme” de la spécialité NSI, de manière plus générale en spé NSI on apprend à coder plus que des langages. 


1. **Introduction à JavaScript**



    1.1. **Qu'est-ce que JavaScript et à quoi sert-il ?**

JavaScript est un langage de programmation de scripts côté client. Il est utilisé pour créer des pages web **interactives** et **dynamiques** en ajoutant des fonctionnalités telles que les **animations**, les **formulaires interactifs**, les **scripts de validation**, les **galeries d'images,** etc. sans avoir besoin de charger une nouvelle page du serveur.

JavaScript peut être utilisé conjointement avec HTML et CSS pour créer des pages web complètes et riches en fonctionnalités. Il fonctionne dans les navigateurs web modernes sur les ordinateurs de bureau et les appareils mobiles, ce qui en fait un outil de développement web très puissant et largement utilisé.



    1.2. **Comment utiliser JavaScript avec HTML et CSS ?**

Pour utiliser JavaScript avec HTML et CSS, vous devez inclure le code JavaScript dans une page HTML. Il existe plusieurs façons de faire cela, mais les deux méthodes les plus courantes sont les suivantes :



* En intégrant le code JavaScript directement dans la page HTML, à l'intérieur de la balise "script".


```
<!DOCTYPE html>
<html>
  <head>
    <style>
      /* Votre feuille de style CSS */
    </style>
  </head>
  <body>
    <!-- Votre contenu HTML -->
    <script>
      // Votre code JavaScript
    </script>
  </body>
</html>

```



* En incluant un fichier JavaScript externe dans la page HTML, à l'aide de la balise "script".


```
<!DOCTYPE html>
<html>
  <head>
    <style>
      /* Votre feuille de style CSS */
    </style>
    <script src="nom_du_fichier.js"></script>
  </head>
  <body>
    <!-- Votre contenu HTML -->
  </body>
</html>
```


Vous pouvez utiliser JavaScript pour interagir avec le contenu HTML et CSS de votre page, en utilisant des techniques telles que la modification du contenu et du style des éléments HTML, la manipulation du Document Object Model (DOM), la gestion des événements, etc. Cela permet de créer des pages web plus interactives et plus riches en fonctionnalités pour les utilisateurs.



    1.3. **Variables et types de données de base en JavaScript**

En JavaScript, les variables sont des emplacements mémoire où vous pouvez stocker des valeurs, telles que des nombres, des chaînes de caractères, des booléens, etc. Les variables sont déclarées à l'aide de la mot-clé "**var**", "**let**" ou "**const**" et peuvent être affectées à une valeur en utilisant le signe d'affectation "=".

Voici quelques exemples de déclaration de variables en JavaScript :


```
var age = 25;
let name = "John Doe";
const pi = 3.14;
```


En JavaScript, les types de données de base sont les suivants :



1. Number : pour les nombres (entiers ou décimaux)
2. String : pour les chaînes de caractères
3. Boolean : pour les valeurs booléennes (vrai ou faux)
4. Undefined : pour les variables qui n'ont pas encore été initialisées ou qui ont été déclarées sans valeur
5. Null : pour les variables qui ont été explicitement définies sur une valeur nulle

Il est important de comprendre ces types de données de base en JavaScript, car ils sont utilisés pour effectuer des opérations et prendre des décisions dans votre code. Par exemple, vous pouvez utiliser des opérateurs arithmétiques pour effectuer des opérations mathématiques sur les nombres, ou des opérateurs de comparaison pour comparer les valeurs.



    1.4. **Opérateurs arithmétiques et logiques**

En JavaScript, les opérateurs arithmétiques permettent d'effectuer des opérations mathématiques simples telles que l'addition, la soustraction, la multiplication et la division sur des nombres. Les principaux opérateurs arithmétiques sont les suivants :



1. Addition (+)
2. Soustraction (-)
3. Multiplication (*)
4. Division (/)
5. Modulo (%)

Voici quelques exemples d'utilisation des opérateurs arithmétiques :


```
var x = 10;
var y = 20;
var sum = x + y;    // sum = 30
var difference = x - y;    // difference = -10
var product = x * y;    // product = 200
var quotient = x / y;    // quotient = 0.5
var remainder = x % y;    // remainder = 10
```


Les opérateurs logiques en JavaScript permettent de faire des comparaisons entre des valeurs et de déterminer si elles sont vraies ou fausses. Les principaux opérateurs logiques sont les suivants :



1. Égalité (==)
2. Inégalité (!=)
3. Supériorité strictement (>)
4. Infériorité strictement (&lt;)
5. Supériorité ou égalité (>=)
6. Infériorité ou égalité (&lt;=)

Voici quelques exemples d'utilisation des opérateurs logiques :


```
var x = 10;
var y = 20;
var isEqual = x == y;    // isEqual = false
var isNotEqual = x != y;    // isNotEqual = true
var isGreater = x > y;    // isGreater = false
var isLess = x < y;    // isLess = true
var isGreaterOrEqual = x >= y;    // isGreaterOrEqual = false
var isLessOrEqual = x <= y;    // isLessOrEqual = true
```


Il est important de comprendre comment utiliser les opérateurs arithmétiques et logiques en JavaScript, car ils sont largement utilisés pour prendre des décisions et effectuer des opérations dans votre code.



2. **Les instructions et les structures de contrôle **
    2.1. **Les instructions simples et les blocs d'instructions**

En JavaScript, les instructions simples sont des lignes de code qui effectuent une tâche unique. Par exemple, une déclaration de variable est une instruction simple qui déclare une variable et lui assigne une valeur.

Voici un exemple d'instruction simple en JavaScript :


```
var x = 10;
```


Les blocs d'instructions, d'autre part, sont des ensembles d'instructions qui peuvent être exécutées ensemble. Les blocs d'instructions sont généralement entourés de accolades ({ et }).

Voici un exemple de bloc d'instructions en JavaScript :


```
if (x > 0) {
  console.log("x est positif");
  x = x + 1;
}
```


Dans l'exemple ci-dessus, le bloc d'instructions **if (x > 0)** est exécuté seulement si la condition **x > 0** est vraie. Les instructions à l'intérieur des accolades sont alors exécutées **ensemble**.

Les blocs d'instructions sont souvent utilisés dans des structures de contrôle telles que **if**, **for**, **while**, **do...while**, etc., pour déterminer si certaines instructions doivent être exécutées ou non en fonction de certaines conditions. Il est important de comprendre comment utiliser les blocs d'instructions en JavaScript pour écrire des programmes plus complexes.



    2.2. **Les structures conditionnelles (if/else)**

Les structures conditionnelles en JavaScript permettent d'exécuter un bloc d'instructions spécifique en fonction d'une condition déterminée. La structure la plus courante est la structure **if/else**.

La structure **if/else** a la forme suivante :


```
if (condition) {
  // instructions exécutées si la condition est vraie
} else {
  // instructions exécutées si la condition est fausse
}
```


Dans cette structure, la condition est évaluée. Si elle est vraie, le premier bloc d'instructions est exécuté, sinon le deuxième bloc d'instructions **est** **exécuté**.

Voici un exemple d'utilisation de la structure **if/else** en JavaScript :


```
var x = 10;

if (x > 0) {
  console.log("x est positif");
} else {
  console.log("x est négatif ou nul");
}
```


Dans cet exemple, la condition **x > 0** est évaluée. Si elle est vraie, la première instruction est exécutée et affiche "x est positif" dans la console. Si elle est fausse, la deuxième instruction est exécutée et affiche "x est négatif ou nul" dans la console.

Il est important de comprendre comment utiliser les structures conditionnelles en JavaScript, car elles permettent de prendre des décisions dans votre code en fonction de conditions déterminées.



    2.3. **Boucles (for, while)**

Les boucles en JavaScript permettent d'exécuter un bloc d'instructions plusieurs fois. Les boucles les plus courantes sont la boucle **for** et la boucle **while**.

La boucle **for** a la forme suivante :


```
for (initialisation; condition; incrémentation) {
  // instructions exécutées dans la boucle
}
```


Dans cette structure, la **initialisation** est exécutée une seule fois au début de la boucle. La **condition** est évaluée à chaque tour de boucle. Si elle est vraie, le bloc d'instructions est exécuté et l'**incrémentation** est effectuée. La boucle continue ainsi jusqu'à ce que la condition soit fausse.

Voici un exemple d'utilisation de la boucle **for** en JavaScript :


```
for (var i = 0; i < 10; i++) {
  console.log(i);
}
```


Dans cet exemple, la boucle **for** s'exécute 10 fois et affiche les nombres de 0 à 9 dans la console.

La boucle **while** a la forme suivante :


```
while (condition) {
  // instructions exécutées dans la boucle
}
```


Dans cette structure, la condition est évaluée à chaque tour de boucle. Si elle est vraie, le bloc d'instructions est exécuté. La boucle continue ainsi jusqu'à ce que la condition soit fausse.

Voici un exemple d'utilisation de la boucle **while** en JavaScript :


```
var i = 0;

while (i < 10) {
  console.log(i);
  i++;
}
```


Dans cet exemple, la boucle **while** s'exécute 10 fois et affiche les nombres de 0 à 9 dans la console.

Il est important de comprendre comment utiliser les boucles en JavaScript, car elles permettent de répéter des instructions plusieurs fois, ce qui peut être très utile dans de nombreux scénarios.



    2.4. **Fonctions en JavaScript **

Les fonctions en JavaScript permettent de regrouper des instructions en un bloc que l'on peut appeler plusieurs fois. Elles sont définies à l'aide de la syntaxe suivante :


```
function nomDeLaFonction(paramètres) {
  // instructions de la fonction
  return valeurDeRetour;
}
```


Dans cette syntaxe, **nomDeLaFonction** est le nom de la fonction, **paramètres** est une liste facultative de paramètres que la fonction peut recevoir, et **valeurDeRetour** est la valeur retournée par la fonction.

Voici un exemple d'utilisation de fonctions en JavaScript :


```
function addition(a, b) {
  return a + b;
}

var resultat = addition(5, 3);
console.log(resultat); // affiche 8
```


Dans cet exemple, nous définissons une fonction **addition** qui prend deux paramètres **a** et **b** et les additionne. Nous appelons ensuite cette fonction en lui passant les valeurs **5** et **3**. La fonction retourne la somme de ces valeurs, que nous stockons dans la variable **resultat**.

Les fonctions en JavaScript sont très utiles pour encapsuler du code réutilisable et améliorer la lisibilité et la maintenabilité du code.



3. **Les tableaux et les objets :**
    3.1. **Tableaux en JavaScript**

Les tableaux en JavaScript permettent de stocker plusieurs valeurs sous une même variable. Les tableaux sont définis à l'aide de crochets **[]** et peuvent contenir n'importe quel type de données, y compris d'autres tableaux.

Voici un exemple de création et d'utilisation d'un tableau en JavaScript :


```
var tableau = [1, 2, 3, 4, 5];

console.log(tableau[0]); // affiche 1
console.log(tableau[2]); // affiche 3

tableau[2] = 100;
console.log(tableau[2]); // affiche 100
```


Dans cet exemple, nous créons un tableau **tableau** contenant les valeurs **1**, **2**, **3**, **4** et **5**. Nous pouvons accéder à ses éléments en utilisant les crochets **[]** et en spécifiant l'index de l'élément souhaité, en commençant à **0**. Nous pouvons également modifier les valeurs des éléments du tableau en les réassignant.

Les tableaux en JavaScript sont très utiles pour stocker et manipuler des collections de données. Ils peuvent être parcourus à l'aide de boucles et de fonctions spéciales telles que **forEach**, **map**, **filter** et **reduce**.



    3.2. **Parcours des tableaux**

Il existe plusieurs façons de parcourir les tableaux en JavaScript. La méthode la plus courante est d'utiliser une boucle **for** ou une boucle **for...of**.

Voici un exemple d'utilisation de la boucle **for** pour parcourir un tableau :


```
var tableau = [1, 2, 3, 4, 5];

for (var i = 0; i < tableau.length; i++) {
  console.log(tableau[i]);
}
```


Dans cet exemple, nous utilisons une boucle **for** pour itérer sur les éléments du tableau **tableau**. La variable **i** sert d'index pour accéder à chaque élément du tableau. La boucle s'exécute tant que **i** est strictement inférieur à la longueur du tableau, qui est stockée dans la propriété **length**.

Voici un exemple d'utilisation de la boucle **for...of** pour parcourir un tableau :


```
var tableau = [1, 2, 3, 4, 5];

for (var valeur of tableau) {
  console.log(valeur);
}
```


Dans cet exemple, nous utilisons une boucle **for...of** pour itérer sur les éléments du tableau **tableau**. La variable **valeur** prend la valeur de chaque élément du tableau à chaque itération de la boucle.

Il existe également d'autres méthodes pour parcourir les tableaux, telles que les fonctions **forEach**, **map**, **filter** et **reduce**. Chacune de ces fonctions permet de parcourir le tableau de manière différente et de traiter les éléments de différentes manières.



    3.3. **Objets en JavaScript**

Les objets en JavaScript sont des structures de données permettant de stocker des propriétés et des méthodes associées à un objet. Les objets sont définis à l'aide de accolades **{}** et les propriétés sont définies en utilisant la syntaxe **nomDePropriete: valeur**.

Voici un exemple de création et d'utilisation d'un objet en JavaScript :


```
var objet = {
  nom: "monNom",
  type: "Modèle de langage",
  répondre: function(question) {
    return "Je peux répondre à des questions sur divers sujets.";
  }
};

console.log(objet.nom); // affiche "monNom"
console.log(objet.type); // affiche "Modèle de langage"
console.log(objet.répondre("Qu'est-ce que tu fais?")); // affiche "Je peux répondre à des questions sur divers sujets."
```


Dans cet exemple, nous créons un objet **objet** avec les propriétés **nom**, **type** et **répondre**. Nous pouvons accéder à ses propriétés en utilisant la notation point **.** et le nom de la propriété. Nous pouvons également appeler la méthode **répondre** en utilisant la même notation.

Les objets en JavaScript sont très utiles pour modéliser des objets complexes dans votre application. Ils peuvent être imbriqués les uns dans les autres pour former des structures de données plus complexes encore. Les objets peuvent également être définis en utilisant des constructeurs et des prototypes pour permettre la création d'objets similaires à partir d'un même modèle.



    3.4. **Propriétés et méthodes des objets**

Les propriétés d'un objet sont des variables associées à un objet qui peuvent stocker des données. Elles peuvent être accédées et modifiées en utilisant la notation point **.** suivie du nom de la propriété.

Les méthodes sont des fonctions associées à un objet qui peuvent être appelées pour effectuer une action spécifique. Elles peuvent également accéder et modifier les propriétés de l'objet.

Voici un exemple d'objet avec des propriétés et des méthodes :


```
var voiture = {
  marque: "Tesla",
  modèle: "Model S",
  vitesseMax: 250,
  accélérer: function(augmentationVitesse) {
    this.vitesseMax += augmentationVitesse;
  }
};

console.log(voiture.marque); // affiche "Tesla"
console.log(voiture.vitesseMax); // affiche 250
voiture.accélérer(50);
console.log(voiture.vitesseMax); // affiche 300
```


Dans cet exemple, nous avons un objet **voiture** avec les propriétés **marque**, **modèle** et **vitesseMax**. Nous avons également une méthode **accélérer** qui prend en entrée une augmentation de vitesse et l'ajoute à la vitesse maximale en utilisant la propriété **vitesseMax**. La notation **this** est utilisée pour faire référence à l'objet actuel dans la méthode.



4. **Manipulation du Document Object Model (DOM) :**
    4.1. **Qu'est-ce que le DOM ?**

Le DOM (Document Object Model) est une représentation en arbre des éléments et des contenus d'une page web. Il permet aux développeurs de manipuler les éléments HTML d'une page web à l'aide de JavaScript.

Chaque élément HTML sur une page est représenté par un objet dans le DOM, avec des propriétés et des méthodes associées. Les développeurs peuvent accéder à ces objets et les manipuler en utilisant du JavaScript pour ajouter, supprimer ou modifier du contenu, changer les styles CSS, etc.

Le DOM est un standard qui définit comment les pages web peuvent être programmées. Il est supporté par tous les navigateurs modernes et est utilisé pour développer des applications web interactives.



    4.2. **Comment manipuler les éléments HTML avec JavaScript ?**

Il y a plusieurs manières de manipuler les éléments HTML avec JavaScript, mais voici quelques méthodes courantes :



* Sélection des éléments par ID : pour sélectionner un élément HTML en utilisant son ID, nous pouvons utiliser la méthode **document.getElementById()**.


```
var titre = document.getElementById("titre");
titre.style.color = "blue";

```



* Sélection des éléments par nom de classe : pour sélectionner plusieurs éléments HTML qui ont la même classe, nous pouvons utiliser la méthode **document.getElementsByClassName()**.


```
var paragraphes = document.getElementsByClassName("paragraphe");
for (var i = 0; i < paragraphes.length; i++) {
  paragraphes[i].style.backgroundColor = "yellow";
}

```



* Sélection des éléments par nom de tag : pour sélectionner plusieurs éléments HTML qui ont le même nom de tag, nous pouvons utiliser la méthode **document.getElementsByTagName()**.


```
var listeElements = document.getElementsByTagName("li");
for (var i = 0; i < listeElements.length; i++) {
  listeElements[i].innerHTML = "Element " + (i + 1);
}

```



* Sélection des éléments avec querySelector et querySelectorAll : pour sélectionner des éléments HTML en utilisant une sélection CSS, nous pouvons utiliser les méthodes **document.querySelector()** et **document.querySelectorAll()**.


```
var premierParagraphe = document.querySelector(".paragraphe");
premierParagraphe.style.fontWeight = "bold";

var tousLesParagraphes = document.querySelectorAll(".paragraphe");
for (var i = 0; i < tousLesParagraphes.length; i++) {
  tousLesParagraphes[i].style.textAlign = "center";
}
```


Une fois que nous avons sélectionné un ou plusieurs éléments HTML, nous pouvons les manipuler en utilisant leurs propriétés et méthodes. Par exemple, nous pouvons changer leur contenu en utilisant la propriété **innerHTML**, changer leurs styles en utilisant la propriété **style**, etc.

Voici quelques exemples de modification de contenu en utilisant la propriété **innerHTML** :



* Modification du contenu d'un élément :


```
var titre = document.getElementById("titre");
titre.innerHTML = "Nouveau titre";

```



* Ajout de contenu à la fin d'un élément :


```
var paragraphe = document.getElementById("paragraphe");
paragraphe.innerHTML += "<br>Nouveau contenu";

```



* Modification du contenu de plusieurs éléments avec une boucle :


```
var listeElements = document.getElementsByTagName("li");
for (var i = 0; i < listeElements.length; i++) {
  listeElements[i].innerHTML = "Element " + (i + 1);
}

```



* Modification du contenu en HTML en utilisant des balises HTML :


```
var paragraphe = document.getElementById("paragraphe");
paragraphe.innerHTML = "Contenu <b>en gras</b> et <i>italique</i>";
```


Voici quelques exemples de modification de style en utilisant la propriété **style** :



* Modification de la couleur de fond d'un élément :


```
var element = document.getElementById("element");
element.style.backgroundColor = "yellow";

```



* Modification de la couleur de police d'un élément :


```
var element = document.getElementById("element");
element.style.color = "blue";

```



* Modification de la largeur d'un élément :


```
var element = document.getElementById("element");
element.style.width = "200px";

```



* Modification de plusieurs styles en même temps :


```
var element = document.getElementById("element");
element.style.backgroundColor = "yellow";
element.style.color = "blue";
element.style.width = "200px";

```



* Modification de styles en utilisant une boucle :


```
var listeElements = document.getElementsByTagName("li");
for (var i = 0; i < listeElements.length; i++) {
  listeElements[i].style.backgroundColor = "yellow";
  listeElements[i].style.color = "blue";
}
```


Voici quelques autres exemples de manipulation d'éléments HTML :



* Ajout ou suppression de classes CSS :


```
var element = document.getElementById("element");
element.classList.add("classe");
element.classList.remove("classe");

```



* Modification de l'attribut src d'une image pour changer son URL :


```
var image = document.getElementById("image");
image.src = "nouvelle_image.jpg";

```



* Modification de l'attribut href d'un lien pour changer son URL :


```
var lien = document.getElementById("lien");
lien.href = "https://nouveau_lien.com";

```



* Ajout d'un événement (par exemple, un clic) à un élément :


```
var bouton = document.getElementById("bouton");
bouton.addEventListener("click", function() {
  alert("Bouton cliqué");
});

```



* Modification de la visibilité d'un élément en utilisant la propriété display :


```
var element = document.getElementById("element");
element.style.display = "none";
element.style.display = "block";

```



* Modification de la position d'un élément en utilisant les propriétés left, right, top, et bottom :


```
var element = document.getElementById("element");
element.style.position = "absolute";
element.style.left = "100px";
element.style.top = "100px";

```



    4.3. **Événements et gestion des événements**

Les événements en JavaScript sont des actions qui se produisent sur des éléments HTML, telles que le clic sur un bouton, le chargement de la page, le survol de la souris, etc. Pour gérer ces événements, nous pouvons utiliser la méthode **addEventListener** sur un élément HTML sélectionné :


```
var bouton = document.getElementById("bouton");
bouton.addEventListener("click", function() {
  alert("Bouton cliqué");
});
```


Il existe de nombreux types d'événements différents que nous pouvons gérer en JavaScript, tels que :



* **click** : déclenché lorsque l'utilisateur clique sur un élément.
* **load** : déclenché lorsque la page a fini de se charger.
* **mouseover** : déclenché lorsque la souris passe sur un élément.
* **submit** : déclenché lorsque le formulaire est soumis.
* **keydown** : déclenché lorsque l'utilisateur appuie sur une touche du clavier.

Et bien d'autres encore! Il est important de comprendre comment gérer les événements en JavaScript car cela nous permet de réagir aux actions de l'utilisateur et de rendre notre application plus interactive.

Voici quelques exemples de types d'événements en JavaScript :



* Clique sur un bouton : "click"
* Chargement de la page : "load"
* Focus sur un champ de formulaire : "focus"
* Soumission d'un formulaire : "submit"
* Changement de valeur d'un champ de formulaire : "change"
* Mouse Over : "mouseover"
* Mouse Out : "mouseout"
* Mouse Down : "mousedown"
* Mouse Up : "mouseup"
* Keyboard : "keydown", "keypress", "keyup"
* Touch events : "touchstart", "touchmove", "touchend"
* Resize de la fenêtre : "resize"
* Scroll de la fenêtre : "scroll"

Ces sont quelques exemples de types d'événements en JavaScript, il en existe beaucoup d'autres selon les besoins. Il est important de noter que les événements peuvent être déclenchés par des actions de l'utilisateur ou par des actions du script lui-même.

Voici quelques exemples de gestion d'événements en JavaScript :



* Afficher une alerte lorsque l'utilisateur clique sur un bouton :


```
var bouton = document.getElementById("bouton");
bouton.addEventListener("click", function() {
  alert("Bouton cliqué");
});

```



* Changer la couleur de fond d'un élément lorsque la souris passe dessus :


```
var div = document.getElementById("maDiv");
div.addEventListener("mouseover", function() {
  div.style.backgroundColor = "red";
});

```



* Exécuter une fonction lorsque le formulaire est soumis :

var formulaire = document.getElementById("monFormulaire");

formulaire.addEventListener("submit", function(event) {

  event.preventDefault();

  // Traitement du formulaire ici

});



* Afficher le code d'une touche pressée lorsque l'utilisateur tape sur le clavier :


```
document.addEventListener("keydown", function(event) {
  console.log("Touche pressée : " + event.keyCode);
});

```



    4.4. **Modification du style et de la taille des éléments HTML avec JavaScript**

Pour modifier le style et la taille des éléments HTML avec JavaScript, vous pouvez utiliser la propriété "style" des éléments sélectionnés. Par exemple, pour changer la couleur d'arrière-plan d'un élément, vous pouvez utiliser la propriété "style.backgroundColor". Pour changer la largeur d'un élément, vous pouvez utiliser la propriété "style.width".

Voici un exemple de code pour changer la couleur d'arrière-plan et la largeur d'un élément HTML :


```
<!DOCTYPE html>
<html>
  <head>
    <script>
      function changeStyle() {
        document.getElementById("element").style.backgroundColor = "blue";
        document.getElementById("element").style.width = "500px";
      }
    </script>
  </head>
  <body>
    <div id="element" style="background-color: yellow; width: 200px; height: 200px;"></div>
    <button onclick="changeStyle()">Changer le style</button>
  </body>
</html>
```


Ce code crée une div avec un style initial et un bouton qui, lorsqu'il est cliqué, appelle la fonction "changeStyle" qui modifie la couleur d'arrière-plan et la largeur de la div.



5. **Utilisation de bibliothèques et frameworks JavaScript :**
    5.1. **Introduction aux bibliothèques JavaScript (jQuery)**

jQuery est une bibliothèque JavaScript populaire qui facilite la manipulation du Document Object Model (DOM) et l'ajout d'interactivité à des pages web. Il fournit une interface simple et concise pour sélectionner, manipuler et animer des éléments HTML, ainsi que pour effectuer des requêtes AJAX pour charger des données à partir d'un serveur sans recharger la page.

Voici un exemple de code pour sélectionner un élément HTML et changer sa couleur d'arrière-plan en utilisant jQuery :


```
<!DOCTYPE html>
<html>
  <head>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>
      $(document).ready(function() {
        $("#element").click(function() {
          $(this).css("background-color", "blue");
        });
      });
    </script>
  </head>
  <body>
    <div id="element" style="background-color: yellow; width: 200px; height: 200px;"></div>
  </body>
</html>
```


Ce code utilise la méthode "ready" de jQuery pour spécifier que la fonction associée sera appelée une fois que la page sera complètement chargée. Il utilise la méthode "click" pour ajouter un gestionnaire d'événements "click" à l'élément sélectionné. Lorsque l'élément est cliqué, la fonction associée est appelée et utilise la méthode "css" pour changer la couleur d'arrière-plan de l'élément.

Voici d’autres exemples d'utilisation de la bibliothèque jQuery :



* Sélection et manipulation des éléments HTML : vous pouvez facilement sélectionner des éléments HTML en utilisant des sélecteurs CSS et les manipuler en utilisant les méthodes de jQuery telles que "css", "html", "text", "attr", etc.


```
<!DOCTYPE html>
<html>
  <head>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>
      $(document).ready(function() {
        $("#btn").click(function() {
          $("#element").css("background-color", "blue");
          $("#element").html("<b>Hello World!</b>");
        });
      });
    </script>
  </head>
  <body>
    <button id="btn">Click me</button>
    <div id="element" style="background-color: yellow; width: 200px; height: 200px;"></div>
  </body>
</html>

```



* Animation : vous pouvez facilement ajouter des animations à des éléments HTML en utilisant les méthodes d'animation de jQuery telles que "show", "hide", "fadeIn", "fadeOut", "slideUp", "slideDown", etc.


```
<!DOCTYPE html>
<html>
  <head>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>
      $(document).ready(function() {
        $("#btn").click(function() {
          $("#element").fadeOut();
        });
      });
    </script>
  </head>
  <body>
    <button id="btn">Click me</button>
    <div id="element" style="background-color: yellow; width: 200px; height: 200px;"></div>
  </body>
</html>

```



* Requêtes AJAX : vous pouvez facilement effectuer des requêtes AJAX en utilisant la méthode "ajax" de jQuery pour charger des données à partir d'un serveur sans recharger la page.


```
<!DOCTYPE html>
<html>
  <head>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>
      $(document).ready(function() {
        $("#btn").click(function() {
          $.ajax({
            url: "data.json",
            success: function(data) {
              $("#element").html(data);
            }
          });
        });
      });
    </script>
  </head>
  <body>
    <button id="btn">Click me</button>
    <div id="element" style="background-color: yellow; width: 200px; height: 200px;"></div>

```



    5.2. **Introduction aux frameworks JavaScript (React, Angular, Vue.js)**

Les frameworks JavaScript sont des bibliothèques logicielles qui fournissent une structure de développement pour les applications web. Les trois frameworks les plus populaires sont React, Angular et Vue.js.



* React est un framework de développement d'applications web développé par Facebook. Il est utilisé pour développer des applications à interface utilisateur complexes avec une grande quantité de données changeantes.
* Angular est un framework de développement d'applications web développé par Google. Il est utilisé pour développer des applications web à grande échelle avec une structure de code claire et modulaire.
* Vue.js est un framework de développement d'applications web léger et progressif développé par une équipe indépendante. Il est utilisé pour développer des applications web simples et légères avec une syntaxe facile à apprendre.

Chacun de ces frameworks offre des fonctionnalités différentes pour développer des applications web, il est donc important de choisir celui qui convient le mieux à vos besoins en fonction de la complexité et des exigences de votre projet.

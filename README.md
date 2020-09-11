# amendjeli.github.io
Asseel Mendjeli																																																4ICS

# TD 2 : Site web statique (CSS)

## Exercice 0

https://amendjeli.github.io/tp2.html

## Exercice 1

Significations des symboles :

- div p{}
  - ce sélecteur s'applique sur tous les paragraphes dans une balise div
- div ~ p {};
  - ce sélecteur s'applique sur les pararaphes qui sont utilisés après une div. 
- h2#byName, span.byClass{};
  - ce sélecteur s'applique à tous les h2 qui ont un id byName et tous les spans qui ont une class byClass.
- div#byName > Img:nth-child(2n) {};
  - ce sélecteur s'applique aux images paires (2n) filles directes d'une div avec un id byName 
- p#byName > b:hover {};
  - ce sélecteur s'applique aux éléments en gras fils directes des paragraphes dont l'id est byName lorsque l'utilisateurs passe sa souris dessus.
- div#byName > p:nth-child(2n+1) span[class*=re] {};
  - ce sélecteur s'applique aux paragraphes impairs et aux spans dont la classe contient "re" à un endroit. Ils doivent aussi être descendants directs d'une div dont l'id est "byName"
- article p+p.description:nth-child(2n+1) {};
  - ce sélecteur s'applique aux paragraphe de la classe description, impairs (2n+1) qui sont juste après un paragraphe ou un article (<p> ou <article>)

## Exercice 2

https://amendjeli.github.io/ma-boite.html

## Exercice 3

https://amendjeli.github.io/index.html

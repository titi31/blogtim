---
layout: main.html
tags: posts
title: python
---
## le langage python
Le python est le langage des hackers car c'est un langage simple est du coup on peut faire des scripts de pirate assez simplement.
Pour commencer en python :
pour un hello world :

  > print('hello world')
  
va afficher un hello world dans la console.

il y a les variables ce sont des étiquette qui stocke une valeur.

 > nombre=2
 
 > nombre_deuxieme=3
 
 > total=nombre+nombre_deuxieme
 
 > print(total)
  
affichera 5.

les types de données:

il peut y avoir plusieurs type de donnée integer(int) c'est un entier négatif ou positif 

float les nombres flottant ils ont une virgule

string ce sont des chaine de caracteres ex: 'salut les gas'

boolean les booléens sont les valeurs True ou False.

il y a les conditions c'est de verifier si c'est vrai ou faux.

exemple:
- 5>3 =True
- 3>12 = False
- 5>3 (True) or 4<2 (False) = True
- 5>3(True) and 4<2 (False) = False
- 5<12 (True) and 4>2(True) = True
- 5==12 (False) and 3>11(False) = True
les signes:
 - ==(égal à), >=(superieur ou égale), <=(inferieur ou égale), not True(n'est pas vrai donc false),not False (True),>(superieur à),<(inferieur à)

oui donc ne pas confondre ==(qui est un comparatif) et = (qui est une affection de valeur)

bon donc je veux faire un programme qui verifie si la personne est majeur:
 > age=34
 
 > if age >= 18 :
 
 >  print('vous etes majeur')
 
 on crée une variable age qui est égale à 34 si la variable age est supérieur ou égale à 18 le programme affiche 'vous etes majeur' et c'est notre cas(34 est 
 
 supérieur à 18)
 
 sinon il n'affiche rien pas très pratique de ne rien faire
 
 c'est pour on a les else pour dire sinon le cas ou notre conditions est fausse
 
 > age =12
 
 > if age >=18:
 >    print('vous etes majeur')
 >else:
 >  print('vous etes mineurs donc interdit d'acceder au sites')
 
 voila la variable age est egale à 12 donc le else va etre executer
 
 mais si vous avait besoin de faire plusieurs verifications vous avez les elif pour si sinon.
 
 > age=18
 
 >if age == 18 :
 
 >  print('vous etes majeur depuis peu')
 
 >elif age > 18 and age < 50 :
 
 >  print('vous etes junior')
 
 >elif age > 50 and < 90 :
 
 >  print('vous etes senior')
 
 >elif age > 90 :
 
 >  print('bonne fin de vie')
 
 >else:
 
 >  print('vous etes mineur')
 
 dans notre cas sa affichera 'vous etes majeur depuis peu'.
 
 

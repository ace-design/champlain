---

layout: support

title: Quiz pour population vieillissante
authors: mbf
institution: UCA
composante: IUT Nice Côte d'Azur, département d'informatique
date: 09/2019

level: 1
user: 2
gl: 3
link: https://lms.univ-cotedazur.fr/course/view.php?id=19082
tags: [lp]

enseignement: LP20
tags: [lp,projet]
type: projet
num: 4

---



## En savoir plus sur cette étude de cas et la forme du TD

Projet basé sur les travaux du projet CHAMPLAIN entre l’Université Nice - Sophia Antipolis (UNS) et l’Université du Québec à Montréal (UQAM), en visant plus particulièrement le développement d’applications logicielles en support à la population vieillissante.
Ce sujet est inspiré d'un TD préparé par AM. Pinna-Dery (Polytech) et S. Mosser (UQAM)


Ce TD reprend la forme du TD sur [The Landing Gear System Case Study](https://mi-git.univ-tlse2.fr/ECb/LGS/blob/master/README.adoc)



## I. Description de l'étude de cas

Le texte suivant contient la description initiale de l'étude de cas mais où chaque ligne a un numéro pour plus de traçabilité.


> https://git-iutinfo.unice.fr/blay/quizzfordisabledpeople/blob/master/description.txt#L2 


### I.a Description générale

[Description.txt](description.txt)

### I.b Comportements du système
[Comportement.txt](Comportement.txt)

### I.c Exigences sur la réalisation du projet
[ProjetExigences.txt](ProjetExgigences.txt)



## II. Description du Projet

L'objectif pédagogique de ce projet est de couvrir le cycle du développement d'un logiciel de son analyse à son prototypage, en suivant des principes agiles et en utilisant les outils adaptés.


### II.1 Formation des équipes
Vous travaillerez par équipes de quatre et au maximum par groupe de 4 étudiants.

### II.2 Variantes du projet
Chaque équipe doit choisir une variante du projet, en ne travaillant que sur un seul type de handicap

### II.3 Choix technologiques : Obligations
Toutes les interactions dans le projet passent par [Slack DEP-INFO-IUT-NICE-19-20](https://join.slack.com/t/depinfoiutnic-voq7258/shared_invite/enQtODYwOTU3ODUwNjQwLTUyMzliODFlNmFiNjA3MzQyOWY1YjVkMjJjY2IxMjlhYjkwZjZiZWY4Y2VhZmRiNzI0Mjg3NzAwNDg4NWJmM2U) 
sur le canal #lp-gl sur lequel tous les étudiants doivent s'inscrire.

**Le dépôt dans gitlab est obligatoire.**
Les technologies utilisées doivent absolument autoriser des **tests automatiques** que vous saurez déclecher dans l'**intégration continue**.
Des exemples d'utilisation de Java et Junit vous seront donnés en TD.
Si vous faîtes le choix d'autres technologies, il vous appartient de réussir à les utiliser en tests ET en intégration continue. C# est déconseillé.


**C-1** des tests automatiques liés au respect du handicap sont exigés. Il pourra s'agir de **vérifier automatiquement**
*  les normes du W3C sur des fichiers html
*  certaines propriétés telles que
     * "A toute question mémorisée est associée un niveau", 
     * "ne contient pas de mots "compliqués"" (à vous de décider comment vous gérez cette notion) 
     * etc.

* De tels projets doivent absolument être testés avec de vrais utilisateurs. Nous bénéficions de quelques retours que nous utilisons ici. 
MAIS, si les étudiants ont les moyens de faire tester leur application par des personnes en situation de handicap 
alors évidemment qu'ils doivent le faire, même s'ils ne peuvent pas mette à jour leur logiciel, il sera intéressant qu'ils nous fassent part de ces retours. 
Cependant L’utilisateur ne peut pas être trop sollicité (car cela génère du stress et peut entrainer des refus), il convient donc d'avoir une démarche centrée utilisateur avec les Aidants qui peuvent déjà éliminer un grand nombre de pièges.


### II.4 Grandes étapes du projet

Le projet décomposé en 3 grande phases
1. Sprint 0 : Analyse du projet : *du 16/12/19 au 20/1/20*
    - [ TD Modélisation UML](TD/modelisation.md)
    - [ TD Exigences]](TD/exigences.md)
2. Sprint 1 : Livraison d'une version V0 d'un produit minimal viable  du *20/1/20 au 9/2/20*
2. Sprint 2 : Livraison d'une version V1 d'un produit mettant en exergue l'utilisation des techniques du GL pour assurer l'accessibilité du quizz aux personnes en situation du handicap choisi du *9/2/20 au 1/3/20*

### II.5 Livraisons
Les rendus du projet sont décrits dans le [MOODLE](https://lms.univ-cotedazur.fr/mod/assign/index.php?id=19082)
Chaque équipe devra
1.  [ ]  S'inscrire sur Slack [Slack DEP-INFO-IUT-NICE-19-20](https://join.slack.com/t/depinfoiutnic-voq7258/shared_invite/enQtODYwOTU3ODUwNjQwLTUyMzliODFlNmFiNjA3MzQyOWY1YjVkMjJjY2IxMjlhYjkwZjZiZWY4Y2VhZmRiNzI0Mjg3NzAwNDg4NWJmM2U) 
2.  [ ]  Remplir le document partagé suivant en précisant les membres de l'équipe, la variante du sujet choisi et le nom de l'équipe.
1.  [ ]  Proposer un premier document d'analyse de l'application en utilisant les diagrammes UML (voir [ TD Modélisation UML](TD/modelisation.md))




## III. Règles GIT

### III.1 Créer des templates
   * Un template pour les Histoires Utilisateurs
   * Un template pour les tâches Liées à la prise en compte du handicap
  

# Autres Références

* https://www.w3.org/2019/12/pressrelease-intro-web-accessibility-course.html.fr
* https://camo.githubusercontent.com/c59ffa40ba8d00a552f74fb05742f6b950bf4a64/68747470733a2f2f692e696d6775722e636f6d2f463170373568422e706e67
* https://dev.to/madalynrose/5-things-you-need-to-know-about-manual-accessibility-testing-with-the-keyboard-and-screen-readers-3512

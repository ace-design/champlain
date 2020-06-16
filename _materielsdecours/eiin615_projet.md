---

layout: materiel

title: "PolyQuiz : Quiz pour population vieillissante"
date: 01/2020

authors: amd
institution: UCA
composante: Polytech 

level: 2
ihm: 4
user: 4
techno: 5
gl: 2

enseignement: EIIN615
tags: [si3,projet]
num: 1
type: projet

---


## Sujet
Ce sujet est élaboré dans le cadre d'une collaboration UCA  UQAM, projet Champlain concernant la formation des informaticiens aux spécificités de la population vieillissante. L'institut partenaire principal est l'accueil de jour thérapeutique de Biot pour personne Alzheimer https://www.accueilalzheimer.fr/.

Le sujet en une phrase : réaliser un site web  en Angular qui permette de configurer un quiz adapté à des personnes vieillissantes ayant des difficultés pour utiliser un outil informatique

## Problématique
Nous nous intéressons dans le cadre de ce projet à une caractéristique particulière de la population vieillissante : l'évolution et  le cumul d'handicaps associés à la nécessité de rester autonome le plus longtemps possible (retarder la dépendance).

Le handicap peut entraîner la limitation d'activités ou la restriction de participation à la vie en sociét?? par l'altération d'une ou plusieurs fonctions physiques, sensorielles, mentales, cognitives ou psychiques.

Nous allons nous intéresser plus particulièrement aux :

-       problèmes de vision (DMLA maladie évolutive qui impacte la vue)

-       problèmes de mémoire qui peuvent être évolutifs (cas de la maladie d'Alzheimer)

-       problèmes moteurs : tremblements & précisions (cas de la maladie de Parkinson)

## Persona et scénarios d'usage dans le cas de perte de mémoire

P1. Coralie, 35 ans, travaille au centre d'accueil de jour d'Alzheimer, elle est aide médico psy. Elle aimerait que les accueillis puissent s'occuper en faisant des quiz à l'heure des pauses pour solliciter leur mémoire et surtout leur faire plaisir sans aucun stress ni anxiété. Chacun a ses préférences et ses capacités cognitives ce serait bien de pouvoir personnaliser la thématique et les questions.

P2. Pierre 75 ans atteint d'Alzheimer a toujours été intéressé par les nouvelles technologies. Il perd la mémoire immédiate et est très anxieux. Il ne souhaite pas que les autres se rendent compte de ses incapacités et il peut se mettre en colère ou sombrer dans un état dépressif  si quelqu'un lui fait remarquer.

Scénario d'usage

Aujourd'hui Pierre est particulièrement agité. Il adore le sport automobile. Coralie sélectionner= le thème Sport automobile avec des images. Il ne faut pas plus de 4 réponses et surtout ne pas mettre Pierre en difficulté. S'il commet une erreur il faut juste reposer la même question en éliminant la dernière réponse fausse qu'il a faite.

Pierre est sur la page Quiz avec le thème choisi par Coralie. Il fait le quiz. Une fois terminé, il souhaite recommencer. Le même quiz lui est proposé en changeant l'ordre des questions.

Coralie va sur la page des résultats pour consulter les réponses fournies par Pierre. Cela lui permet de se rendre compte qu'il faudrait créer un nouveau quiz plus adapté à Pierre avec de nouvelles images.

Points importants

Dans le cas de la perte de mémoire (Alzheimer & persona Coralie, Pierre et Madeleine)

-       il est important de mettre l'accueilli en confiance et de ne pas le confronter à l'échec

-       Il est important de permettre la répétition

-       Supprimer des réponses automatiquement peut faciliter la réalisation du Quiz

-       Faciliter la personnalisation et la création des quiz par les animatrices.



## Persona et scénarios d'usage dans le cas de problèmes visuels

P3. Geneviève, 60 ans, utilise beaucoup son ordinateur pour ses activités professionnelles et personnelles. Elle aime apprendre et vérifier ses connaissances. Faire des quiz de personnalité l'intéresse également. En ce moment elle se rend compte qu'elle est obligée de retirer ses lunettes, d'approcher son ordinateur ou de zoomer pour bien lire. Elle voudrait pouvoir configurer les quiz pour choisir et adapter la taille de la fonte et les contrastes de couleurs en fonction de son état de fatigue.

Scénario d'usage

J'ai envie de me détendre : Je vais sur la page configuration de PolyQuiz, je télécharge le thème Principauté de Monaco. Je choisis la fonte Courrier de taille 17 avec un contraste noir sur blanc.

Je vais sur la page quiz, je choisis le thème Principauté de Monaco.Je lance le quiz et répond aux questions. Je me rends compte que je n'ai pas choisi le bon contraste il me faudrait plut™t un fond sombre. J'abandonne le quiz et retourne à la configuration pour changer le contraste avant de recommencer mon quiz.

Je vais sur la page des résultats et je vois les résultats de mes derniers tests avec les configurations que j'ai choisies. Je supprime certaines thématiques, en ajoute de nouvelles et j'augmente le niveau de complexité sur la thématique Principauté de Monaco. J'en profite pour me créer 2 configurations préférées : la configuration active et la configuration fatiguée qui change le contraste.

Points importants

Dans le cas de difficultés visuelles (presbytie, DLMA..), il est important de

-       pouvoir choisir une fonte adaptée

-       pouvoir faire varier la taille de la fonte

-       pouvoir changer les contrastes

-       pouvoir revenir sur le choix en cours de quiz

-       pouvoir créer des configurations préférées

-       Pouvoir connaitre la difficulté d'un quiz

## Le cas du Quiz
Proposer des quiz dans le but de tester des connaissances, d'informer de façon ludique, d'entraîner, de passer le temps, de se remémorer des bons souvenirs.

PolyQuiz doit être un site permettant de

1.     configurer un quiz

2.     voir les résultats

3.     réaliser le quiz

En ce qui concerne la création des quiz les attentes sont assez similaires dans tous les cas.

Il est important de permettre de

-       Créer des quiz

-       Pourvoir créer de nouveaux thèmes

-       Pouvoir associer un quiz à un thème

-       Pouvoir ajouter des informations sur un quiz

-       Sélectionner des quiz

-       Pouvoir sauvegarder et charger de nouveaux quiz

En ce qui concerne la réalisation d'un quiz les attentes diffèrent selon les pathologie (cf. sections handicap).

La visualisation des résultats est à définir selon les pathologies également. A minima elle correspond au nombre de réponses justes sur le total des questions.

## Votre projet est votre projet !
A vous de définir le périmètre de votre projet.

Que couvrez vous comme fonctionnalités ?  à quel niveau : Configuration, exécution, résultats. 

Quel handicap traitezvous et comment ?.

Vous devez créer vos persona et scénarios (inspirez vous de ceux donnés en exemple dans les sections handicap).

Vous devez prioriser les fonctionnalités de sorte à avoir toujours un Quiz jouable (MVP évolutif)

## Quelques indications
Attention de ne pas faire des quiz trop infantilisant

Pour la collaboration avec la fondation GSF et les EHPAD, privilégiez les thèmes autour des activités de la vie quotidienne et des passions.

## Références 
Au 1er janvier 2020, plus d'une personne sur cinq en France a 65 ans ou plus : https://www.insee.fr/fr/statistiques/4281618#titrebloc21


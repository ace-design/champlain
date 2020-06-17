Ce site présente le projet Formation en Génie Logiciel pour le développement d’applications en support à la population vieillissante, financé par le programme Samuel de Champlain. 



# Comment administrer le site ?

### Les news 

Chaque news correspond à un fichier .md du dossier _posts/ 
La cartouche d'une news doit à minima contenir :
* layout : post
* title 
* author : qui correspond à l'id d'un des authors spécifiés dans le fichier _data/authors.yml
* tags : par exemple [News, Site web]
* excerpt_separator : <!--more--> 

La news est décrite dans le fichier markdown. Au bout de quelques lignes, il faut ajouter le signe <!--more-->. Lorsque la news est affichée sur la page d'accueil, seul le texte avant le <!--more--> est affiché. Lorsque l'on consulte la liste des news, tout le texte est affiché. 



### L'équipe 

Tous les membres de l'équipe sont décrits dans le fichier _data/authors.yml
Il y a, pour le moment, trois types de membres de l'équipe : 
* les chercheurs principaux de l'équipe, dont la position est "equipe"
* les institutions impliquées dans le projet, dont la position est "institution"
* les intervenants, dont la position est "intervenant" 

#### Les chercheurs principaux 

On doit renseigner :
* name 
* avatar : cet avatar doit forcément être carré 
* url : un lien externe vers le profil (github, linkedin, site web perso...)
* institution 
* short : une courte description 

#### Les institutions  

On doit renseigner :
* name 
* logo 
* url : un lien externe vers le site de l'institution 

#### Les intervenants 

On doit renseigner :
* name 
* institution : d'où vient cet intervenant 
* date : la date de l'intervention 
* contribution : qu'est-ce qu'il a fait pour ce projet ? 



### Les compétences 

Toutes les compétences sont décrites dans le fichier _data/competences.yml
Chacune d'entre elles est composée de trois éléments : 
* name 
* short : une courte description 
* image

Elles sont affichées dans la page de l'équipe. 



### Les enseignements 

Chaque enseignement correspond à un fichier .md du dossier _enseignements/ 
La cartouche d'un enseignement doit à minima contenir :
* layout : enseignement
* sigle 
* title
* date : l'année de début de l'enseignement (2019 si l'enseignement s'est déroulé pendant l'année 2019-2020)
* authors : séparés par une virgule s'il y en a plusieurs, et correspondant aux id des authors spécifiés dans le fichier _data/authors.yml

On peut y rajouter les cartouches suivantes : 
* level : soit 1, soit 2, soit 3 qui correspond au cycle d'étude
* institution : qui correspond à l'id d'une instution dans le fichier _data/authors.yml, UCA ou UQAM 
* composante : une chaîne de caractère (Polytech par exemple)
* link : le lien externe pour accéder à l'enseignement 
* ihm : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intéractions Homme-Machine dans cet enseignement
* user : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Prise en compte de l'utilisateur dans cet enseignement
* ia : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intelligence Artificielle dans cet enseignement
* io : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Internet des Objets dans cet enseignement
* gl : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Génie Logiciel dans cet enseignement
* techno : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Technologies dans cet enseignement
* tags : par exemple [bac +5, sigle]
    
Il est possible de décrire l'enseignement dans le fichier markdown en utilisant, si voulu, du html. 



### Les matériels de cours  

Chaque matériels de cours correspond à un fichier .md du dossier materielsdecours/ 
La cartouche d'un matériel de cours doit à minima contenir :
* layout : materiel
* title
* date 
* authors : séparés par une virgule s'il y en a plusieurs, et correspondant aux id des authors spécifiés dans le fichier _data/authors.yml
* enseignement : le sigle de l'enseignement dans lequel ce support a été utilisé
* type : projet, eval ou support 
* num : le numéro du matériel dans le cours

On peut y rajouter les cartouches suivantes : 
* level : soit 1, soit 2, soit 3 qui correspond au cycle d'étude
* institution : qui correspond à l'id d'une instution dans le fichier _data/authors.yml, UCA ou UQAM 
* composante : une chaîne de caractère (Polytech par exemple)
* link : le lien externe pour accéder au matériel de cours  
* ihm : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intéractions Homme-Machine dans ce matériel de cours
* user : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Prise en compte de l'utilisateur dans ce matériel de cours
* ia : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intelligence Artificielle dans ce matériel de cours
* io : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Internet des Objets dans ce matériel de cours
* gl : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Génie Logiciel dans ce matériel de cours
* techno : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Technologies dans ce matériel de cours
* tags : par exemple [bac +5, sigle]

Il est possible de décrire le matériel de cours dans le fichier markdown en utilisant, si voulu, du html. 



### Les travaux étudiants  

Chaque travail étudiant correspond à un fichier .md du dossier _travauxetudiants/ 
La cartouche d'un travail étudiant doit à minima contenir :
* layout : travail
* title
* date 
* etudiants : séparés par une virgule s'il y en a plusieurs
* sujet : le nom du sujet de projet

On peut y rajouter les cartouches suivantes : 
* level : soit 1, soit 2, soit 3 qui correspond au cycle d'étude
* institution : qui correspond à l'id d'une instution dans le fichier _data/authors.yml, UCA ou UQAM 
* composante : une chaîne de caractère (Polytech par exemple)
* link : le lien externe pour accéder au travail étudiant  
* ihm : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intéractions Homme-Machine dans ce travail étudiant
* user : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Prise en compte de l'utilisateur dans ce travail étudiant
* ia : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intelligence Artificielle dans ce travail étudiant
* io : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Internet des Objets dans ce travail étudiant
* gl : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Génie Logiciel dans ce travail étudiant
* techno : un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Technologies dans ce travail étudiant
* tags : par exemple [bac +5, sigle]

Il est possible de décrire le travail dans le fichier markdown en utilisant, si voulu, du html. 


### Ajouter des documents en local 

Rajoutez vos documents dans le dossier /assets/documents. Eventuellement les ranger dans des dossiers (par exemple, tous les matériels de cours d'un même enseignement dans un dossier).
Le lien vers ce fichier est : "{{ site.url }}/assets/documents/nomdudocument" 



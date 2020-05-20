Ce site présente le projet Formation en Génie Logiciel pour le développement d’applications en support à la population vieillissante, financé par le programme Samuel de Champlain. 



## Comment administrer le site ?

### Les news 

//TODO 


### L'équipe 

Tous les membres de l'équipe sont décrits dans le fichier _data/authors.yml
Il y a, pour le moment, trois types de membres de l'équipe : 
* les membres principaux de l'équipe, dont la position est "equipe". Pour ces membres, on doit y renseigner le nom (name), l'avatar (avatar), une url externe si voulu (url), l'institution (institution) et une courte description (short). 
* les institutions impliquées dans le projet, dont la position est "institution". On doit ajouter le nom de l'institution (name), le logo (logo) et une url externe si voulu (url).
* les intervenants, dont tla position est "intervenant". Pour eux, il faut entrer le nom (name), d'où vient cet intervenant (institution), la date de l'intervention (date), et sa contribution (contribution). 
    
Les paramètres de la page de l'équipe peuvent être modifiés dans le fichier pages/aequipe.html. On peut notamment y modifier le titre de la page et l'image du header. 
Le contenu de la page peut être modifié dans le fichier _includes/equipe.html
Enfin, le style de la page peut être modifié dans le fichier _sass/includes/_equipe.scss. 


### Les compétences 

Toutes les compétences sont décrites dans le fichier _data/competences.yml
Chacune d'entre elles est composée de trois éléments : un nom (name), une courte description (short) et une image représentative (image). 

Elles sont affichées dans la page d'accueil, home. Cet affichage peut être modifié dans _layouts/home.html 


### Les enseignements 

Chaque enseignement correspond à un fichier .md du dossier _enseignements/ 
La cartouche d'un enseignement doit à minima contenir :
* layout : enseignement
* sigle 
* title
* date (l'année de début de l'enseignement, 2019 si l'enseignement s'est déroulé pendant l'année 2019-2020)
* authors (séparés par une virgule s'il y en a plusieurs, et correspondant aux id des authors spécifiés dans le fichier _data/authors.yml)

On peut y rajouter les cartouches suivantes : 
* level (soit 1, soit 2, qui correspond au cycle d'étude)
* institution (qui correspond à l'id d'une instution dans le fichier _data/authors.yml, uca ou uqam)
* composante 
* link (qui correpond au lien externe de l'enseignement)
* ipm (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intéraction Personne-Machine dans cet enseignement)
* user (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Prise en compte de l'utilisateur dans cet enseignement)
* ia (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intelligence Artificielle dans cet enseignement)
* io (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Internet des Objets dans cet enseignement)
* gl (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Génie Logiciel dans cet enseignement)
* techno (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Technologies dans cet enseignement)
    
Il est possible de décrire l'enseignement dans le fichier markdown en utilisant, si voulu, du html. 


### Les matériels de cours  

Chaque matériels de cours correspond à un fichier .md du dossier _supportscours/ 
La cartouche d'un matériel de cours doit à minima contenir :
* layout : support
* title
* date 
* authors (séparés par une virgule s'il y en a plusieurs, et correspondant aux id des authors spécifiés dans le fichier _data/authors.yml)
* enseignement (l'enseignement dans lequel ce support a été utilisé)
* type (sujet de projet, evaluation ou support de cours)

On peut y rajouter les cartouches suivantes : 
* level (soit 1, soit 2, qui correspond au cycle d'étude)
* institution (qui correspond à l'id d'une instution dans le fichier _data/authors.yml, uca ou uqam)
* link (qui correpond au lien externe du support de cours)
* ipm (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intéraction Personne-Machine dans ce support de cours)
* user (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Prise en compte de l'utilisateur dans ce support de cours)
* ia (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intelligence Artificielle dans ce support de cours)
* io (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Internet des Objets dans ce support de cours)
* gl (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Génie Logiciel dans ce support de cours)
* techno (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Technologies dans ce support de cours)
    
Il est possible de décrire le matériel de cours dans le fichier markdown en utilisant, si voulu, du html. 


### Les travaux étudiants  

Chaque travail étudiant correspond à un fichier .md du dossier _travauxetudiants/ 
La cartouche d'un travail étudiant doit à minima contenir :
* layout : travail
* title
* date 
* etudiants (séparés par une virgule s'il y en a plusieurs)
* sujetdeprojet (le sujet de projet du travail)

On peut y rajouter les cartouches suivantes : 
* level (soit 1, soit 2, qui correspond au cycle d'étude)
* institution (qui correspond à l'id d'une instution dans le fichier _data/authors.yml, uca ou uqam)
* link (qui correpond au lien externe du travail étudiant)
* ipm (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intéraction Personne-Machine dans ce travail étudiant)
* user (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Prise en compte de l'utilisateur dans ce travail étudiant)
* ia (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intelligence Artificielle dans ce travail étudiant)
* io (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Internet des Objets dans ce travail étudiant)
* gl (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Génie Logiciel dans ce travail étudiant)
* techno (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Technologies dans ce travail étudiant)
    
Il est possible de décrire le travail dans le fichier markdown en utilisant, si voulu, du html. 









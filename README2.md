# Numérique et Sciences Informatiques Terminale

## [Introduction et rappels](./_ressources/0.0.INTRO.md)

<details>
  <summary><h2>1️⃣ Structures de données</h2></summary>


<details>
    <summary><i>Bulletin Officiel : contenu, capacités attendues</i></summary>

>L’écriture sur des exemples simples de plusieurs implémentations d’une même structure de données permet de faire émerger les notions d’**interface** et d’**implémentation**, ou encore de structure de données abstraite.  
>Le paradigme de la **programmation objet** peut être utilisé pour réaliser des implémentations effectives des structures de données, même si ce n’est pas la seule façon de procéder.  
>| Contenu | Capacités attendues |
>| :-- | :-- |
>| Structures de données, interface et implémentation <br><br><br><br>Dictionnaires, index et clé | - Spécifier une structure de données par son interface <br>- Distinguer interface et implémentation <br>- Écrire plusieurs implémentations d’une même structure de données <br><br>- Distinguer la recherche d’une valeur dans une liste et dans un dictionnaire|
>| Vocabulaire de la Programmation Orientée Objet : classes, attributs, méthodes, objets | - Écrire la définition d’une classe <br>- Accéder aux attributs et méthodes d’une classe | 
>| Listes, piles, files : structures linéaires | - Distinguer des structures par le jeu des méthodes qui les caractérisent <br>- Choisir une structure de données adaptée à la situation à modéliser | 
>| Arbres : structures hiérarchiques <br><br>Arbres binaires : nœuds, racines, feuilles, sous-arbres gauches, sous-arbres droits | - Identifier des situations nécessitant une structure de données arborescente <br>- Évaluer quelques mesures des arbres binaires (taille, encadrement de la hauteur, etc.) | 
>| Graphes : structures relationnelles <br>Sommets, arcs, arêtes, graphes orientés ou non orientés | - Modéliser des situations sous forme de graphes <br>- Écrire les implémentations correspondantes d’un graphe : matrice d’adjacence, liste de successeurs/de prédécesseurs <br>- Passer d’une représentation à une autre | 
</details>
  
- ### [Structures de données, interface et implémentation](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/1.1_struct.ipynb) 
- ### [Vocabulaire de la Programmation Orientée Objet](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/1.2_poo.ipynb)  +  Exercice type BAC : 
- ### [Listes, Piles, Files : Structures linéaires](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/1.3_struc_lin.ipynb)  +  Exercice type BAC : [Spé NSI 2021 - Am. du Nord 1 - Ex. 5](https://raw.githubusercontent.com/abrugiere/tnsi/main/1.3_21-NSIJ1AN1-ex5.pdf)
- ### [Arbres : Structures hiérarchiques](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/1.4_arbres.ipynb)  +  Exercice type BAC : [Spé NSI 2021 - Am. du Nord 1 - Ex. 4](https://raw.githubusercontent.com/abrugiere/tnsi/main/1.4_21-NSIJ1AN1-ex4.pdf)
- ### [Graphes : Structures relationnelles](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/1.5_graphes.ipynb)  +  Exercice type BAC : 
</details>


<details>
  <summary><h2>2️⃣ Bases de données</h2></summary>

<details>
    <summary><i>Bulletin Officiel : contenu, capacités attendues</i></summary> 

>Le développement des traitements informatiques nécessite la manipulation de données de plus en plus nombreuses. Leur organisation et leur stockage constituent un enjeu essentiel de performance.  
>Le recours aux **bases de données relationnelles** est aujourd’hui une solution très répandue. Ces bases de données permettent d’organiser, de stocker, de mettre à jour et d’interroger des données structurées volumineuses utilisées simultanément par différents programmes ou différents utilisateurs. Cela est impossible avec les représentations tabulaires étudiées en classe de première.  
>Des **S**ystèmes de **G**estion de **B**ases de **D**onnées (SGBD) de très grande taille (de l’ordre du pétaoctet) sont au centre de nombreux dispositifs de collecte, de stockage et de production d’informations.  
>L’accès aux données d’une base de données relationnelle s’effectue grâce à des requêtes d’interrogation et de mise à jour qui peuvent par exemple être rédigées dans le **langage SQL** (_Structured Query Language_). Les traitements peuvent conjuguer le recours au langage SQL et à un langage de programmation.  
>| Contenu | Capacités attendues |
>| :-- | :-- |
>| Système de gestion de bases de données relationnelles | - Identifier les services rendus par un système de gestion de bases de données relationnelles : persistance des données, gestion des accès concurrents, efficacité de traitement des requêtes, sécurisation des accès | 
>| Modèle relationnel : relation, attribut, domaine, clef primaire, clef étrangère, schéma relationnel | - Identifier les concepts définissant le modèle relationnel | 
>| Base de données relationnelle | - Savoir distinguer la structure d’une base de données de son contenu. <br> - Repérer des anomalies dans le schéma d’une base de données | 
>| Langage SQL : requêtes d’interrogation et de mise à jour d’une base de données | - Identifier les composants d’une requête <br>- Construire des requêtes d’interrogation à l’aide des clauses du langage SQL : SELECT, FROM, WHERE, JOIN <br>- Construire des requêtes d’insertion et de mise à jour à l’aide de : UPDATE, INSERT, DELETE | 
</details>

- ### [Système de Gestion de Bases de Données - Modèle relationnel - Base de données relationnelle](https://notebook.basthon.fr/?kernel=sql&from=https://raw.githubusercontent.com/abrugiere/tnsi/main/2.1_sgbd_relationnel.ipynb) 
- ### [Langage SQL](https://notebook.basthon.fr/?kernel=sql&from=https://raw.githubusercontent.com/abrugiere/tnsi/main/2.2_sql.ipynb) + TP [Requêtes SQL](https://notebook.basthon.fr/?kernel=sql&from=https://raw.githubusercontent.com/abrugiere/tnsi/main/2.6_tp_sql.ipynb&module=https://raw.githubusercontent.com/abrugiere/tnsi/main/2.6_soccer.db) ([2.6_soccer.db](https://raw.githubusercontent.com/abrugiere/tnsi/main/2.6_soccer.db)) + Exercice type BAC :  [Spé NSI 2023 - Métropole j1 - Ex. 1](https://raw.githubusercontent.com/abrugiere/tnsi/main/2.5_23-NSIJ1ME1-ex1.pdf)
</details>

<details>
  <summary><h2>3️⃣ Architectures matérielles, systèmes d’exploitation et réseaux</h2></summary>

<details>
    <summary><i>Bulletin Officiel : contenu, capacités attendues</i></summary>

>La réduction de taille des éléments des circuits électroniques a conduit à l’avènement de systèmes sur puce (**SoCs** pour *Systems On Chips* en anglais) qui regroupent dans un seul circuit nombre de fonctions autrefois effectuées par des circuits séparés assemblés sur une carte électronique. Un tel système sur puce est conçu et mis au point de façon logicielle, ses briques électroniques sont accessibles par des API, comme pour les bibliothèques logicielles.  
>Toute machine est dotée d’un **système d’exploitation** qui a pour fonction de charger les programmes depuis la mémoire de masse et de lancer leur exécution en leur créant des **processus**, de gérer l’ensemble des ressources, de traiter les interruptions ainsi que les entrées-sorties et enfin d’assurer la sécurité globale du système.  
>Dans un réseau, les **routeurs** jouent un rôle essentiel dans la transmission des paquets sur Internet : les paquets sont routés individuellement par des algorithmes. Les pertes logiques peuvent être compensées par des protocoles reposant sur des accusés de réception ou des demandes de renvoi, comme **TCP**.  
>La protection des données sensibles échangées est au cœur d’Internet. Les notions de **chiffrement** et de **déchiffrement** de paquets pour les communications sécurisées sont explicitées.  
>| Contenu | Capacités attendues |
>| :-- | :-- |
>| Composants intégrés d’un système sur puce | - Identifier les principaux composants sur un schéma de circuit et les avantages de leur intégration en termes de vitesse et de consommation |
>| Gestion des processus et des ressources par un système d’exploitation | - Décrire la création d’un processus, l’ordonnancement de plusieurs processus par le système <br>- Mettre en évidence le risque de l’interblocage (*deadlock*) |
>| Protocoles de routage | - Identifier, suivant le protocole de routage utilisé, la route empruntée par un paquet |
>| Sécurisation des communications | - Décrire les principes de chiffrement symétrique (clef partagée) et asymétrique (avec clef privée/clef publique) <br>- Décrire l’échange d’une clef symétrique en utilisant un protocole asymétrique pour sécuriser une communication |
</details>

- ### [Composants intégrés d’un système sur puce]()
- ### [Gestion des processus et des ressources par un système d’exploitation]()
- ### [Protocoles de routage]()
- ### [Sécurisation des communications]()
</details>

<details>
  <summary><h2>4️⃣ Langages et programmation</h2></summary>

<details>
    <summary><i>Bulletin Officiel : contenu, capacités attendues</i></summary>

>Le travail entrepris en classe de première sur les méthodes de programmation est prolongé. L’accent est mis sur une programmation assurant une meilleure **sûreté**, c’est-à-dire minimisant le nombre d’erreurs. Parallèlement, on montre l’universalité et les limites de la notion de **calculabilité**. La **récursivité** est une méthode fondamentale de programmation. Son introduction permet également de diversifier les algorithmes étudiés. En classe terminale, les élèves s’initient à différents **paradigmes de programmation** pour ne pas se limiter à une démarche impérative.  
>| Contenu | Capacités attendues |
>| :-- | :-- |
>| Notion de programme en tant que donnée <br> Calculabilité, décidabilité | - Comprendre que tout programme est aussi une donnée <br>- Comprendre que la calculabilité ne dépend pas du langage de programmation utilisé<br>- Montrer, sans formalisme théorique, que le problème de l’arrêt est indécidable | 
>| Récursivité | - Écrire un programme récursif<br>-  Analyser le fonctionnement d’un programme récursif |
>| Modularité | - Utiliser des API ou des bibliothèques <br>- Exploiter leur documentation <br>- Créer des modules simples et les documenter |
>| Mise au point des programmes <br>Gestion des bugs | - Dans la pratique de la programmation, savoir répondre aux causes typiques de bugs : problèmes liés au typage, effets de bord non désirés, débordements dans les tableaux, instruction conditionnelle non exhaustive, choix des inégalités, comparaisons et calculs entre flottants, mauvais nommage des variables, etc. |
>|Paradigmes de programmation | - Distinguer sur des exemples les paradigmes impératif, fonctionnel et objet <br>- Choisir le paradigme de programmation selon le champ d’application d’un programme |
</details>

- ### [Notion de programme en tant que donnée - Calculabilité, décidabilité](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/4.1_C_calculabilite.ipynb) 
- ### [Récursivité](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/4.2_recur.ipynb) + Exercice type BAC : 
- ### [Modularité - Mise au point des programmes - Gestion des bugs](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/4.3_C_modul_mise_au_pt.ipynb) 
- ### [Paradigmes de programmation](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/4.4_C_paradigmes.ipynb) 
</details>

<details>
  <summary><h2>5️⃣ Algorithmique</h2></summary>

<details>
    <summary><i>Bulletin Officiel : contenu, capacités attendues</i></summary>

>Le travail de compréhension et de conception d’algorithmes se poursuit en terminale notamment via l’introduction des structures d’arbres et de graphes montrant tout l’intérêt d’une approche **récursive** dans la résolution algorithmique de problèmes.  
>On continue l’étude de la notion de **coût d’exécution**, en temps ou en mémoire et on montre l’intérêt du passage d’un coût quadratique en $n^2$ à $nlog_{2}n$  ou de $n$ à $nlog_{2}n$. Le logarithme en base 2 est ici manipulé comme simple outil de comptage (taille en bits d’un nombre entier).  
>| Contenu | Capacités attendues |
>| :-- | :-- |
>| Algorithmes sur les arbres binaires et sur les arbres binaires de recherche | - Calculer la taille et la hauteur d’un arbre <br>- Parcourir un arbre de différentes façons (ordres infixe, préfixe ou suffixe ; ordre en largeur d’abord) <br>- Rechercher une clé dans un arbre de recherche, insérer une clé | 
>| Algorithmes sur les graphes | - Parcourir un graphe en profondeur d’abord, en largeur d’abord <br>- Repérer la présence d’un cycle dans un graphe <br>- Chercher un chemin dans un graphe | 
>| Méthode « diviser pour régner » | - Écrire un algorithme utilisant la méthode « diviser pour régner » | 
>| Programmation dynamique | - Utiliser la programmation dynamique pour écrire un algorithme | 
>| Recherche textuelle | - Étudier l’algorithme de _Boyer-Moore_ pour la recherche d’un motif dans un texte | 

</details>

- ### [Algorithmes sur les arbres binaires et sur les Arbres Binaires de Recherche](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/5.1_algo_arbres.ipynb) 
- ### [Algorithmes sur les graphes](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/5.2_algo_graphes.ipynb) 
- ### [Méthode « diviser pour régner »](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/5.3_diviser.ipynb) + Exercice type BAC : 
- ### [Programmation dynamique](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/5.4_prog_dyn.ipynb) + Exercice type BAC : 
- ### [Recherche textuelle](https://notebook.basthon.fr/?from=https://raw.githubusercontent.com/abrugiere/tnsi/main/5.5_rech_text.ipynb)
</details>



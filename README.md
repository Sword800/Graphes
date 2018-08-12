# Application de manipulation de graphes orientés et sous graphes partiels

## 1.Principe de l'application

Les graphes sont actuellement considérés comme un outil très puissant de modélisation de problèmes plus ou moins
complexes qui trouvent leurs applications dans plusieurs domaines, tels que l’informatique, le traitement d’images, la
recherche opérationnelle, la biologie, la chimie, l’écologie et autres.De ce fait ,un environnement informatique dédié
aux graphes peut s’avérer d’une très grande utilité pour les chercheurs ou autre personne désirant travailler sur des
graphes.

Le projet “Manipulation de graphes orientés et sous graphes partiels” nous a été attribué dans le cadre
du module « Projet Informatique » du semestre 6 de la licence informatique de l’UVSQ.

Ce projet a donc pour but de fournir aux utilisateurs une application qui permettra d’une part de visualiser et
de manipuler des graphes orientés ainsi que leurs données, et d’autre part d’exécuter des algorithmes de graphes afin
d’aider les utilisateurs à résoudre différents problèmes.

Certaines contrainte ont été imposées dès le début du projet.Nous nous sommes forcer à bien les respecter durant
la phase de développement :

> • L’application doit fournir une interface graphique en permettant à l’utilisateur de visualiser des graphes orientés
et de les manipuler simplement.

> • L’application doit fournir un package de manipulation de graphes orientés divisé en plusieurs modules indé-
pendants les uns des autres.

> • L’application devra fournir des mécanismes de sélections des sommets pour pouvoir traiter des sous graphes
partiels.

> • L’application devra gérer un nombre de graphe quelconque.
> • Les sommets du graphes doivent porter au moins un numéro et deux coordonnées dans le plan.
> • Certains sommets du graphe peuvent être sélectionnées pour définir un graphe partiel restreint à la sélection
	de l’utilisateur.
	
## 2.Installation et Lancement de l’application

###  Pour Windows

> Pour compiler et exécuter le programme sur Windows,Il faudra être en possession de certains fichiers et suivre les
instructions suivantes :
	
				1. Récupérer le programme ( " git clone https://bitbucket.org/projet_s6/projet_universitaire-application-de-manipulation-de-graphes/src ")

				2. Télécharger Qt sur le site officiel en Open Source avec la dernière version 5.10.1 et cocher seulement la case
				mingw53_32 (Compilateur windows)

				3. Une fois Qt installé,rendez vous dans le dossier où vous l’avez stocké,puis dans le dossier du compilateur (en
				général : C :/Qt/5.10.1/mingw53_32)

				4. Copier les fichiers du projet dans C :/Qt/5.10.1/mingw53_32

				5. Lancer le terminal mingw53_32 depuis Menu(Démarrer)

				6. Via le Terminal,déplacez vous dans le dossier projet avec “cd projet”

				7. Exécutez la commande suivante : qmake -config release (configuration)

				8. Exécutez la commande suivante : mingw32-make (compilation du programme)

				9. Un dossier “release" sera créer à la fin de la compilation, double-cliquez dessus pour accédez au projet.exe

				10. Inclure les fichiers .dll suivants(qui se trouvent dans le dossier C :/Qt/5.10.1/mingw53_32/bin) dans le
				dossier release :

					— libgcc_s_dw2-1.dll
					— libstdc++-6.dll
					— libwinpthread-1.dll
					— Qt5Core.dll
					— Qt5Gui.dll
					— Qt5Widgetsd.dll

				11. Double-cliquez sur le projet.exe pour ouvrir le programme et commencer à travailler.
	
### Pour Linux

> Pour compiler et exécuter le programme sur Linux,Il faudra être en possession de certains paquets et suivre les
  instructions suivantes :
	
				1. Dans l’idéal,avoir Qt installé sur sa machine en le téléchargeant sur le site officiel

				2. Récupérez l’archive projet.zip et extraire dans le dossier de votre choix

				3. Assurez vous de posséder qmake en exécutant cette commande dans le terminal : sudo apt-get install
				qt4-qmake

				4. Assurez vous de posséder la librairie de développement en exécutant cette commande dans le terminal : sudo
				apt-get install libqt4-dev

				5. Placez vous dans le dossier "projet" et ouvrez un Terminal

				6. Exécutez la commande suivante : qmake

				7. Exécutez la commande suivante : make (compilation du programme)

				8. Un fichier exécutable projet est créé à la fin de la compilation,exécuter la commande ./projet dans le terminal
				afin d’exécuter le programme et commencer à travailler.

				Remarque :Selon la version de Qt que vous possédez,télécharger les paquets correspondants,dans notre cas la
				version de Linux était Qt4.
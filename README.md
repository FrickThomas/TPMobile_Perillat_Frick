# TPMobile_Perillat_Frick

Aurélien Perillat-Bottonet & Thomas Frick
Projet Programmation Mobile 2015
INF4042

Notre application est composée de deux pages.
page d'accueille : 
	- view -> activity_main.xml -> include : content_main.xml
	- controller -> mainactivity.java 
page 2 :
	- view -> activity_second.xml -> include : content_second.xml
	- controller -> secondactivity.java
Service -> GetBiersServices.java

Contenu de la page d'accueille :
	Bouton CLIQUE permettant d'afficher un toast. 
	Bouton ALERT qui ouvre un alert dialog (popup).
	Bouton NOTIFICATION qui envoi une notification au smartphone.
	Un TextView contenant la date ou l'on peut la modifier à l'aide d'un 	datepickerdialog.
	Un ReciclerView qui va nous permettre de recevoir et d'afficher le contenu 	de ficher biers.json télécharger par notre service GetBiersServices.
	Bouton PAGE 2 qui crée un intent vers la seconde page et lance son activité.
	Ajout d'une action toast me dans la barre de menu. 
	
Le contenu de la page a été laissé vide car elle nous sert juste à tester le bon fonctionnement du bouton page 2, nous n'avons pas eu de besoin supplémentaire pour le reste du développement du projet.

Nous avons traduit l'application en français-anglais à l'aide des ressources strings. 

Pour le développement du service ainsi que le pour le développement de l'ensemble de l'application nous avons suivis point par point le support de TP "INF4042-build-awesome-app.pdf
Pour une raison qui nous est inconnu à la première installation de l’apk en version debug le téléchargement des bières ne s’effectue pas. Il faut relancer l’application  pour qu’il soit effectif. 

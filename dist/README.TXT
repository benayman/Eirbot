Chatbot Project - BENLAHCEN Ayman_CHEIKH Aymane - ENSEIRB-MATMECA 2018/2019

INTRODUCTION
------------

Ce projet permet � l'utilisateur de discuter avec des chatbots en ligne de commande. Il propose notamment une panoplie de chatbots qui vont permettre � l�utilisateur
de r�cup�rer diverses informations � travers des APIs directement depuis son terminal � travers une session de chat.

CONTENTS
--------

Le fichier zip contient principalement :

    /readme.txt - ce fichier
    /build - les fichiers n�cessaires pour la compilation
    /dist - contenant le fichier .jar pour lancer l'application
    /src - contenant deux packages :
		- chatbot : le main de l'application
		- bots : ce fichier contient les diff�rents bots impl�ment�s


DOCUMENTATION & SUPPORT
-----------------------

La documentation des diff�rentes APIs impl�ment�s se trouve dans les liens suivants :
	- http://www.icndb.com/
	- https://opentdb.com/api_config.php
	- https://api.ipify.org?format=json
	- https://api.adviceslip.com/advice
	- https://www.boredapi.com
	- https://breaking-bad-quotes.herokuapp.com/v1/quotes
	

ARCHITECTURE DU PROJET
-------------------
Le projet est principalemnt divis� en deux packages. Le package Chatbot contenant le main du projet, une classe UserInterface qui g�re l'interface utilisateur et une
autre classe qui s'occupe des requ�tes HTTP. Le deuxi�me package est le package bots lequel contient une classe consacr� � chaque bot impl�ment� ainsi qu'une classe
Gestionnaire qui permet de g�rer tous ces bots � l'aide d'un HashMap. Le HashMap rend facile l'ajout et la suppression des bots. 

REMARQUES
--------------------- 
Un bot "@help" donne une description de tous les bots impl�ment�s. Il est � noter que pour icndb et quiz, Il faut taper "@icndb " au lieu de "@icndb" et "@quiz " 
au lieu de "@quiz" au cas o� ces deux bots ne prennent pas d'arguments. Lorsque ces deux bots ne prennent pas des arguments, tout se passe normalement.
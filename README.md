# E-Bus-Travel-Agency-
once you start the application , you will first have to identify as a client or as an admin , for the record each one has its own functions and purposes . 


1 - Client  : 
 - **saisir un voyage** : 
 this calls the function named `ajout-voyage()` that takes different inputs from user to fill out the details of the trip such as destination , date , hotel... 
 - **chercher un voyage** :
 
 There are two ways to look for a trip :
- the first calls a function named `rechercher()` that allows you to narrow your research by entering two dates , it then displays the trips in between those dates .
- the second calls a function named `rechercher1()` that displays the trips available on a specific date entered by the user . 
 
 ⛔The trips are stocked in a file named  `basededonnee`  that has all of the available trips in the format **(departure/destination/date)** . 
- **Afficher le panier :**

- **Afficher la drescription :**
  this calls a function named `panier()` that displays the trips that were booked with all of their details. 
 
 
 - **Supprimer un voyage :** 
   this fisrt displays the booked trips by calling `panier()` then calls a function named  `supprimer()` that take the ID of a trip as a parameter and deletes it  .
  - modifier un voyage : 
   this fisrt displays the booked trips by calling `panier()` then calls a function named  `modif()` that take the ID of a trip as a parameter and allows the user to change certain informations about a trip . 
  

2- Admin : 

- **saisir un voyage** : 
this calls a function named `saisir()` that allows the admin to add any number of new trips to the file **basededonnee** .  


- **afficher toutes les voyages** : 
this calls a function named `afficher()` that takes the date base's name ( which is a file ) as a parameter and displays all of its content . 


------------------------------------------------------------------------------------------------------
PROCESSUS DE RESTAURATION GITHUB
------------------------------------------------------------------------------------------------------
Suite à une modification de code dans GitHub, votre solution ne fonctionne plus. Vous devez donc restaurer votre code mais comment faire.  

**Exercice :** Ecrire dans ce Readme une procédure pour expliquer étape par étape le processus de restauration d'un code issue de votre historique (vos commits). C'est dire, décivrez comment faire un Checkout depuis l'interfaçe GitHub. Vous trouverez ci-dessous le début de la séquence de restauration.  

-------------------------------------------------------------------------------------------------------
Début de procédure : Historique des commits
-------------------------------------------------------------------------------------------------------
L'historique de vos commits vous donne accès à vos différentes versions de votre code.  
A chaque commit, un point de sauvegarde est créé dans GitHub.  

Cliquez sur Commits pour accèder à votre historique de commits  
  
![Screenshot Historique](Historique.jpg)   

Sélectionnez le sauvegarde que vous souhaitez restaurer.  

![Screenshot Browse](Browse.jpg)   

A présent vous n'êtes plus dans votre branche main (branche principale) mais vous naviguez dans un point de restauration (votre code du passé).  

![Screenshot Browse](Browse1.jpg)   

Votre objectif à présent est de faire de ce point de sauvegarde une nouvelle branche pour que vous puissiez ensuite la fusionner avec votre branche principale. C'est à dire faire de cette branche de restauration votre branche main.

**C'est vous de créer la suite de cette procedure de restauration**

------------------------------------------------------------------------------------------------------
Création d'une branche de restauration
-----------------------------------------------------------------------------------------------------

   - Sur la page du commit, cliquez sur le bouton "Browse files".
   - En haut de la page, cliquez sur le menu "main" .
   - Sélectionnez "Create branch from here".
   - Nommez votre nouvelle branche.


------------------------------------------------------------------------------------------------------
Fusionner la branche de restauration avec `main`
------------------------------------------------------------------------------------------------------
**Créer une Pull Request**

   - Allez sur l'onglet "Pull Requests".
   - Cliquez sur "New pull request".
   - Sélectionnez `restauration-commit` comme source et `main` comme destination.
   - Vérifiez les modifications et cliquez sur "Create pull request".






 

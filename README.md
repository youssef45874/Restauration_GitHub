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
------------------------------------------------------------------------------------------------------

Voici les étapes à suivre après avoir sélectionné le commit que vous voulez restaurer :

1. **Créer une nouvelle branche depuis le commit sélectionné**

   - Sur la page du commit, cliquez sur le bouton **"Browse files"**.
   - En haut de la page, cliquez sur le menu **"main"** .
   - Sélectionnez **"Create branch from here"**.
   - Nommez votre nouvelle branche.

2. **Vérifier que votre nouvelle branche est bien crée**

   - Allez dans l'onglet **"Branches"** du dépôt GitHub.
   - Vous devriez voir votre nouvelle branche dans la liste.

---
------------------------------------------------------------------------------------------------------
Fusionner la branche de restauration avec `main`
------------------------------------------------------------------------------------------------------

Une fois que vous avez créé votre branche de restauration vous devez la fusionner avec la branche principale (`main`).

1. **Créer une Pull Request (PR)**

   - Allez sur l'onglet **"Pull Requests"**.
   - Cliquez sur **"New pull request"**.
   - Sélectionnez `restauration-commit` comme source et `main` comme destination.
   - Vérifiez les modifications et cliquez sur **"Create pull request"**.

2. **Fusionner la Pull Request**

   - Une fois la PR créée, cliquez sur **"Merge pull request"**.
   - Confirmez la fusion en cliquant sur **"Confirm merge"**.

---
------------------------------------------------------------------------------------------------------
Vérification et suppression de la branche
------------------------------------------------------------------------------------------------------


1. **Tester votre code**
   - Vérifiez que votre application fonctionne correctement après la restauration.
2. **Supprimer la branche de restauration (optionnel)**
   - Si tout est en ordre, vous pouvez supprimer la branche temporaire `restauration-commit`.

Avec cette procédure, vous pouvez facilement restaurer un commit et l'intégrer à  votre branche principale via l'interface GitHub.




 

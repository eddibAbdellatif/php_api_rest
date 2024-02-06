# php_api_rest

### git remote set-url origin https://github.com/eddibAbdellatif/php_api_rest.git


##Récupérez les modifications depuis la branche distante (origin/master) :

bash
Copy code
git fetch origin master
Fusionnez les modifications distantes dans votre branche locale (master) :

bash
Copy code
git merge origin/master
Si vous préférez réécrire l'historique de votre branche locale (ce qui peut être plus propre si vous êtes le seul à travailler sur cette branche), vous pouvez utiliser le rebase au lieu de la fusion :

bash
Copy code
git pull --rebase origin master
Choisissez la méthode qui convient le mieux à votre flux de travail.

Essayez de pousser à nouveau :

bash
Copy code
git push origin master

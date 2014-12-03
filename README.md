GT Vaches :
===========

!!! on travaille directement dans la branche gh-pages, pas dans master !!!
==========================================================================

0. faire une copie locale :
   1. configurer tout selon https://help.github.com/articles/set-up-git/
   2. puis au choix :

      ``` 
      $ git clone git@github.com:randriam/gt-vaches.git
      ```

      ou

      ``` 
      $ git clone https://github.com/randriam/gt-vaches
      ```
   3. aller dans le dossier gt-vaches

      ``` 
      $ cd gt-vaches
      ```
   4. choisir la branche gh-pages :

      ``` 
      $ git checkout gh-pages
      ```

ensuite on travaille dans `gt-vaches` et ses sous-dossiers

1. recuperer les derniers changements

   ```
   $ git pull
   ```

2. editer les fichiers

3. si besoin ajouter ou enlever un fichier
 
   ```
   $ git add fichier
   ```

   et

   ```
   $ git rm fichier
   ```

4. commiter les modifs

   ```
   $ git commit -a
   ```

5. les renvoyer vers github
   ```
   $ git push origin gh-pages
   ```

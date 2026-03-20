# 19-front-controller

## Premier Site avec contrôleur frontal

- création du dossier `public`, c'est le seul accès qu'on laissera aux utilisateurs du site (**Sécurité!**)
- Pour cet exercice on va créer un fichier nommé `index.php` à la racine de `19-front-controller` avec une redirection vers le dossier `public`, car l'exercice est accessible par une une autre URL. Il contient une redirection relative `header("Location: public");`

```php
<?php
# Formateur/19-front-controller/index.php

// fichier de redirection vers public
// inutile si on a bien fait pointer
// un hôte virtuel ou un nom de domaine 
// vers public
header("Location: public");
// sécurité pour être certain d'arrêter
// le serveur PHP, bonne pratique
exit;
```




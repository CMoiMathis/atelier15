# Exercice initiation Visual Studio

### Partie 1 : Cloner le projet

1. Clonez la repo de github classroom.
2. Ouvrir le projet dans visual studio 2022 en double cliquant sur le fichier atelier15.sln.
3. Exécutez le projet à l’aide du triangle vert en haut de l’ide (voir ci-dessous). 
    
    ![Untitled](Exercice%20initiation%20Visual%20Studio%203f9bb712de5a46f28e4f76da113b031d/Untitled.png)
    
4. Si vous voyez cette ligne se faire afficher dans la console, vous avez réussit la première partie ! (vous pouvez fermer la fenêtre de console)
    
    ![Untitled](Exercice%20initiation%20Visual%20Studio%203f9bb712de5a46f28e4f76da113b031d/Untitled%201.png)
    

### Partie 2 : Comprendre le projet

1. Que fait l’opérateur += ? Pour le découvrir, dupliquez la ligne ci-dessous (click sur la ligne à dupliquer et ctrl + d) et exécutez de nouveau le programme.

```csharp
sortie += nomUtilisateurEntreeUsager;
```

1. Que se passe t’il si vous dupliquez la ligne 2 ? 
Pour voir les erreurs du projet, cliquez sur le *x* rouge en bas à gauche de l’ide.
    
    ![Untitled](Exercice%20initiation%20Visual%20Studio%203f9bb712de5a46f28e4f76da113b031d/Untitled%202.png)
    

Annulez vos dernières modifications avec ctrl + z avant de continuer.

### Partie 3 : Améliorer le projet

1. Renommez la variable *nomUtilisateurEntreeUsager* en un nom plus simple (comme nomUtilisateur) à l’aide de la fonctionnalité de renommage : click sur l’élément à renommer suivi de ctrl + r, ctrl + r.

Remarquez vous un avantage d’utiliser la fonctionnalité de renommage versus renommer la variable manuellement? 

Si ce n’est pas le cas, dupliquez la ligne (ctrl + d) qui ajoute le nom d’utilisateur  à la sortie plusieurs fois et renommez la variable une seconde fois.

2. Nous voulons maintenant ajouter au programme la fonctionnalité de demander le nom de famille à l’utilisateur et de l’afficher en majuscules à la fin du message.

Pour ce faire, inspirez-vous (fortement) du code présent pour demander à l’utilisateur d’entrer son nom de famille et mettez le dans une variable.

Ensuite, affichez le nom en majuscules. Il existe une méthode qui permet d’afficher un string en majuscule qui s’appelle : maVariableQuiContientLeString.ToUp...(). Pour découvrir le reste du nom de la méthode, utilisez le raccourci clavier ctrl + espace pour faire apparaître des suggestions. Finalement, naviguez ces suggestions avec les flèches haut/bas et faites tab pour l’insérer.
3. Pusher vos modifications sur github classroom. Pour ce faire, ouvrez le menu de commit de visual studio.
    
![Untitled](Exercice%20initiation%20Visual%20Studio%203f9bb712de5a46f28e4f76da113b031d/Untitled%203.png)
    

Ensuite, entrez un message de commit et sélectionnez du menu déroulant l’option commit all and push.

![Untitled](Exercice%20initiation%20Visual%20Studio%203f9bb712de5a46f28e4f76da113b031d/Untitled%204.png)

### Bonus : Afficher les initiales

À la place d’afficher le nom complet de l’utilisateur, faites afficher uniquement ses initiales. Donc, à la place d’afficher *Hello Joe DOE* , faite afficher *Hello JD*.

<details>
<summary>Indice</summary>
Pour accéder au à un caractère spécifique d’un string, voici la syntaxe : monString[index] (remplacer monString par votre nom de variable et index par 0, 1, 2 ... selon la position du caractère voulu)
</details>

Si le bonus est complété, créez un nouveau commit et pusher vous modification de nouveau (même procédure que l’étape précédente).
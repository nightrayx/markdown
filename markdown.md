# tuto-markdown

le mardown est un langage de balisage (comme le htlm) sa structure est tres legere

## le titres

avec #vous pouvez indiquer des titres de differents niveau (comme h1,h2 etc en html)

    # titre de niveau 1
    ## titre de niveau 2
    etc

## Les listes

on peut faire des listes de plusieur niveaux :

### liste de course:

    - tomates
        - 3 normales
        - une barquette de tomates cerise
    - mozzarella
    - huile d'olive

## les liens

pour crée un lien on utilise les crochets [] pour y mettre notre texte et les parentheses pour indiquer le lien vers lequel il redirige:

[lien vers github](https://github.com)

## les images

on peut rajouter des images

![alt text](https://images "photo- de johannes plennio")

## les tableaux

| En-tête de colonne 1| En-tête de colonnne 2|
|---------------------|----------------------|
|element-colonne 1 ligne 1| element colonne 2 ligne 1| <=== syntaxe

    | En-tête de colonne 1| En-tête de colonnne 2|
    |---------------------|----------------------|
    |element-colonne 1 ligne 1| element colonne 2 ligne 1| <=== considere que c est du code

## les éléments de texte

on peut mettre des elements en *italique*

    on peut mettre des elements de texte en *italique*

Ou en **gras**

    Ou en **gras**

Il est possible d'inserer des lignes de code entre 3 backticks ('') ou avec des tabulations

    html

    <div class="jumbotron"> </div>

le markdown n interprete pas le retour a la ligne comme les autres langages:
On peut faire 
des
retours
à la ligne
avec 2 epaces
git config --global user.email "mon adresse email"
git flow init
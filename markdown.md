# Cours Markdown

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Cours Markdown](#cours-markdown)
  - [Formatage de texte](#formatage-de-texte)
    - [Mise en forme](#mise-en-forme)
    - [Les puces](#les-puces)
      - [Liste ordonnée](#liste-ordonnée)
      - [Listes non ordonnées](#listes-non-ordonnées)
  - [Les liens](#les-liens)
  - [Les images](#les-images)
  - [Gestion du code](#gestion-du-code)
  - [Les tableaux](#les-tableaux)

<!-- /code_chunk_output -->


## Formatage de texte 
### Mise en forme 
Texte au kilomètre.
Mise **en gras**, *en italique* ou ~~barré~~
Pas de souligné natif, mais <span style="color:red;text-decoration:underline;"> on peut le faire en HTML.</span>
Deuxième contenu.
> Ceci est une citation
> Deuxieme contenu
>
> Avec saut de ligne

### Les puces

#### Liste ordonnée
1. Créer un répertoire
   1. Sous élément
   2. Encore un
2. Rentrer dedans
3. ...

#### Listes non ordonnées

- Item 1
- Item 2
  - Sous item
  - ...
  
## Les liens

- [Github](https://github.com)
- [Mise en forme](#mise-en-forme)
- [Fichier 2](cours2.md)

## Les images
![Gandalf](./image/wallpaperflare.com_wallpaper%20(7).jpg)
![Texte alt](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQWEo3RnXStZ1lcxxCZ6c76FnTrZTdakcx-8w&usqp=CAU)

## Gestion du code

```
<html>
    <head>
    </head>
    <body>
        <h1>Coucou</h1>
    </body>
</html>
``` 

La commande `git init` permet d'initialiser un depot Git.

## Les tableaux 

<!-- altgr 6 | -->
<!-- qlt gr 7 ` -->

| Commande   | Description             |
| ---------- | ----------------------- |
| `git init` | Initialise un depot git |
| `git add`  | Ajoute des fichiers     |


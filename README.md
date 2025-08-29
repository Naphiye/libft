# Libft

Libft est un projet dont l’objectif est de recréer une **bibliothèque standard C** personnalisée.  
Ce projet permet de se familiariser avec le **langage C**, la gestion de la mémoire et l’écriture de fonctions robustes et réutilisables.

## Objectifs

- Réimplémenter des fonctions de la **libc** comme :  
  - Gestion des chaînes (`strlen`, `strcpy`, `strdup`, …)  
  - Gestion des caractères (`isalpha`, `isdigit`, …)  
  - Gestion de la mémoire (`calloc`, `memmov`, `memset`, …)  
- Créer des fonctions supplémentaires utiles pour les projets futurs.  
- Compiler la bibliothèque en **fichier `.a`** pour pouvoir la lier à d’autres projets.

## Structure du projet

-  headers (`libft.h`)  
- `Makefile` : compilation de la bibliothèque  

## Compilation

```bash
make

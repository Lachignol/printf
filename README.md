# ft_printf

## Description
Le projet **ft_printf** consiste à recréer la fonction `printf()` de la bibliothèque standard C. Ce projet, réalisé dans le cadre du cursus de l'école 42, permet de comprendre les mécanismes des fonctions variadiques et de développer une solution robuste et conforme aux normes de codage.

## Fonctionnalités
La fonction `ft_printf` prend en charge les spécificateurs suivants :
- **%c** : Affiche un caractère.
- **%s** : Affiche une chaîne de caractères.
- **%p** : Affiche l'adresse d'un pointeur en hexadécimal.
- **%d / %i** : Affiche un entier signé en base 10.
- **%u** : Affiche un entier non signé en base 10.
- **%x / %X** : Affiche un entier en hexadécimal (minuscule/majuscule).
- **%%** : Affiche un pourcentage.

## Prototype
`int ft_printf(const char *format, …);`

La fonction retourne le nombre total de caractères imprimés ou une valeur négative en cas d'erreur.

## Installation et Compilation
Clonez le projet depuis GitHub et compilez-le avec `make` :

git clone <URL_du_projet>

 cd ft_printf
 
 make

## Utilisation
Incluez le fichier d'en-tête dans votre projet :

#include “ft_printf.h”

Exemple d'utilisation :
```
int main(void) 
{
  ft_printf(“Hello %s!\n”, “World”);
   return 0;
 }
```


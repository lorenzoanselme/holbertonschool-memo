# 💻 Hello World en C

## 🎯 Objectif
Découvrir la compilation, l’affichage et la structure d’un programme C.

## 🧱 Structure minimale
```c
#include <stdio.h>

int main(void)
{
    printf("Hello, Holberton!\n");
    return 0;
}
```

## ⚙️ Compilation
```bash
gcc -Wall -Werror -Wextra -pedantic main.c -o hello
./hello
```

## 🧩 Fonctions d’affichage
| Fonction | Description |
|-----------|-------------|
| `printf` | Formatage complet |
| `puts` | Chaîne + saut de ligne |
| `putchar` | Caractère unique |

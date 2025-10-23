# 🧩 Fonctions & Boucles imbriquées

## 🎯 Objectif
Structurer le code avec des fonctions et gérer les boucles dans les boucles.

## 📄 Exemple
```c
#include "main.h"

void print_square(int n)
{
    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j < n; j++)
            _putchar('#');
        _putchar('\n');
    }
}
```

## 🧠 Bonnes pratiques
- Prototypes dans `main.h`
- Une fonction = une responsabilité
- Toujours un `return` dans les fonctions non `void`

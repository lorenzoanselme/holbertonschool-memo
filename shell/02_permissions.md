# 🔒 Permissions Unix

## 🎯 Objectif
Contrôler qui peut lire, écrire et exécuter un fichier.

## 🧱 Structure
Chaque fichier a 3 groupes de droits :
- **User (u)** : propriétaire
- **Group (g)** : groupe
- **Others (o)** : reste du monde

### Ex :
```
-rwxr-xr--
```
> user = rwx (7), group = r-x (5), others = r-- (4)

## ⚙️ Commandes

| Action | Commande | Exemple |
|--------|-----------|---------|
| Voir les droits | `ls -l` | `ls -l fichier.sh` |
| Modifier les droits | `chmod` | `chmod 755 fichier.sh` |
| Changer le propriétaire | `chown` | `chown user:group fichier` |

## 🧮 Valeurs numériques
| Droit | Valeur |
|--------|---------|
| r | 4 |
| w | 2 |
| x | 1 |

> `chmod 754 fichier` → user=7 (rwx), group=5 (r-x), others=4 (r--)

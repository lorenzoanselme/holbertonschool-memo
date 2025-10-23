# ⚙️ Variables & Expansions

## 🎯 Objectif
Gérer les variables, expansions et initialisations du shell.

## 🧩 Variables
```bash
NOM="Lorenzo"
echo "Bonjour $NOM"
export PATH=$PATH:/mon/chemin
```

## 🧠 Expansions utiles
| Type | Syntaxe | Exemple |
|-------|----------|----------|
| Valeur par défaut | `${VAR:-defaut}` | `${USER:-inconnu}` |
| Longueur | `${#VAR}` | `${#USER}` |
| Substitution de commande | `$(cmd)` | `DATE=$(date +%F)` |
| Expansion de liste | `{a,b,c}` | `touch file_{1,2,3}.txt` |

## 🧾 Fichiers d'init
- `~/.bashrc`, `~/.bash_profile`, `~/.profile`
- Contiennent alias, exports et fonctions.

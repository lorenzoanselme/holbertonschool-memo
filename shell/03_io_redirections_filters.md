# 🔁 Redirections & Filtres

## 🎯 Objectif
Manipuler les flux d'entrée/sortie et traiter des données en ligne de commande.

## 📤 Redirections

| Type | Opérateur | Exemple |
|------|------------|----------|
| Sortie standard | `>` | `echo "Hi" > file.txt` |
| Ajouter à un fichier | `>>` | `echo "Hi" >> log.txt` |
| Entrée standard | `<` | `cat < fichier.txt` |
| Erreurs | `2>` | `ls x 2> erreurs.txt` |

## 🔗 Pipes
Relier plusieurs commandes :
```bash
cat data.txt | grep "error" | sort | uniq -c
```

## 🔍 Filtres utiles

| Outil | Description | Exemple |
|--------|-------------|----------|
| `grep` | Recherche | `grep -i "mot" fichier` |
| `cut` | Découpe colonnes | `cut -d, -f2 data.csv` |
| `sort` | Trie | `sort noms.txt` |
| `uniq` | Supprime doublons | `uniq liste.txt` |
| `wc` | Compte | `wc -l fichier` |
| `tr` | Substitue caractères | `tr a-z A-Z` |

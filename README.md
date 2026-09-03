# Documentation du GitHub avec Git

## Initialisation du repo

## Rediger un commit 

```
Titre du commit

Description du commit avec des informations sur l'evolution du projet
```

## Envoyer un commit sur le depot distant(bonne pratique)

```bash
git add .
git commit -m "titre du commentaire"
git push -u origin main
```

## Creation d'une branche

```bash
git checkout -b nom_branche
```

 Pour les bonnes pratiques, on va integrer la notion de revue de code . Pour cela on va creer une branche, faire des modifications, les envoyer sur le depot distant, puis creer une pull request (PR) pour demander une revue de code.
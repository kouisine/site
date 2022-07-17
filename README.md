# Kouisine Website

[https://kouisine.netlify.app](https://kouisine.netlify.app)

Kouisine est un site de recette communautaire simple qui ne vous espionne pas.

Kouisine est compilé avec [Hugo](https://gohugo.io) avec le thème [lugo](https://github.com/lukesmithxyz/lugo).
This site is compiled and organized with Hugo, using [this very simple theme](https://github.com/lukesmithxyz/lugo).

## Comment puis-je contribuer à Kouisine ? 
- En ajoutant une recette
- En ajoutant des photos au recettes qui n'en n'ont pas encore. Les images devrait être en format `.webp` et préférablement de taille inférieure à 100k.
- En signalant les fautes d'orthographe, de grammaire via une issue.

## Directives concernant les contributions
- Voici un modèle de recette: [example.md](example.md). Mettez la recette dans `content/`.
- Les recette doivent commencer avec un titre h1 (préfixé par `#`) ***sur la première ligne***. 
  Supprimer les lignes vides avant le titre et à la fin de la recette.
- Le nom de fichiers ne doivent pas comporter d'accents, de majuscules et les espaces doivent être remplacés par des tirets (`-`). 
- N'incluez pas le sel et le poivre dans la liste des ingrédients, sauf si c'est vraiment indispensable. (Un saussisson au poivre sans poivre, c'est drôlement moins intéressant.)

**SUIVEZ CES CONSIGNES ATTENTIVEMENT SVP: ça évite au mainteneurs de devoir fixer eux même les PR. Si vous ne les suivez pas votre PR sera fermée ou il vous demandé de fixer votre PR**

Facultatif: vous pouvez insérer un fichier json (voir l'[example](`data/authors/luke-smith.json`)) avec le lien de votre site (`website`) et de vos addresses `btc`, `xmr`, `eth`. Si vous avez une instance fosspay, un compte patreon ou equivalent, vous pouvez utiliser le champ `donate`.

### Mots-clefs

N'oubliez pas d'ajouter des tags à vos recettes, mais essayer de vous restraindre à ceux déjà utilisés par d'autres recettes.

### Images

- Les images doivent être insérées dans `/static/pix/`. 
- Les "images stock" ne sont pas acceptées.
- Si une image sur une recette est vraiment moche, vous pouvez cuisiner le plat, prendre une photo et la soumettre.
- Les images doivent être en format `.webp`. *([ImageMagick](https://imagemagick.org/index.php) peut convertir des images en `.webp`)*.
- Si votre recette porte le nom `crepes-picardes.md`, veuillez nommer vos images `pix/crepes-picardes.webp`.
  - Si vous avez plusieurs images, nommez les `pix/crepes-picardes-01.webp`. NB: utilisez bien deux chiffres.

## License

Ce site web et tout son contenu sont dans le domaine public.
En soumettant quoi que ce soit à ce dépôt, vous renoncez à toute prétention de propriété sur ce "quoi que ce soit",
bien que vous soyez invité à vous attribuer le crédit au bas d'une page soumise pour l'avoir ajouté (y compris les liens personnels ou de donation).

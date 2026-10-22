RENDU
'''markdown
# Rendu : MaelineP

- Dépôt : 
- Site GitHub Pages : https://github.com/MaelineP/exercice_git.git

## Ex2
git log --oneline :
5ce89f4 (HEAD -> main, origin/main) ex2 : corrige une faute
c04a5b8 ex2 : ajoute trois lignes
d8f5b30 ex2 : crée les notes
2905e65 first commit
87d0f19 ex1 : initialise le dépôt

## Ex3
- config.local est-il encore dans l'historique ? Pourquoi ? Oui il est toujours disponible dans l'historique mais il a été retiré du suivi. Il existe toujours car le commit est toujours présent dans le terminal et que le fichier est toujours dans le dossier. 

## Ex4
- git status après avoir retiré brouillon.txt du staging : (il y a eu un problème a un moment et les modifications n'ont pas été enregistrer donc j'ai peut être copié la mauvaise chose...)

On branch main
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   brouillon.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store
	.env
	config.local
	debut.log
	node_modules/

no changes added to commit (use "git add" and/or "git commit -a")

- Différence entre annuler une modification et retirer du staging ? je crois que git restore annule les modifications tandis que git restore --straged retire les modifications sans supprimer les changements. 

## Ex6
- À quoi servent <<<<<<<, ======= et >>>>>>> ? ils servent à montrer de manière visuel qu'il y a un conflit lors de la fusion des deux branches. 

exercice 7 : git stash push -m "ligne en cours"
stash@{0}: On main: ligne en cours

## Ex8
- git pull = git fetch + quoi ? git merge 

exercice 9 : adresse du site : https://maelinep.github.io/exercice_git/

## Ex10
git log --oneline --graph --all :
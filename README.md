# Création Repository en lignes de commandes (ubuntu)

## Etape 1 : Se positionner dans son répertoire de travail suivant le domaine étudié

`~/sites/lab/git/ ou ~/sites/lab/js etc..`

## Etape 2 : Création du repo github

```
> gh repo create
? What would you like to do? Create a new repository on GitHub from scratch
? Repository name <project_name>
*** On accepte les paramètres pas défaut
? Description [enter]
? Visibility Public [enter]
? Would you like to add a .gitignore? No [enter]
? Would you like to add a license? No [enter]
? This will create <project_name> as a public repository on GitHub. Continue? Yes [enter]
✓ Created repository Gaston59400/<project_name> on GitHub
? Clone the new repository locally? Yes [enter]
Initialized empty Git repository in /home/gaston59/sites/lab/express/cheatsheet-express/.git/
```

## Etape 3 : Se positionner dans le répertoire créée

`cd <project_name>`

## Etape 4 : Lancement VS Code

`code .'

## Etape 5 : Création d'un premier fichier

*** Comme le dossier est vide, on crée un premier fichier
    Après le lancement de VS Code, on ajoute un fichier nommé 'README.md'
    Et on lui donne un titre présentant le projet

    `# Ceci est mon projet <project_name> pour ...`

*** Après sauvegarde du fichier sous VS Code :

## Etape 6 : Insertion dans GitHub

```
git status
git add README.md
git commit -m "First commit"
git pull
git push --set-upstream origin main
```






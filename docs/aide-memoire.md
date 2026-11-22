# Aide-mémoire du terminal Linux

## Se déplacer

| Commande       | Ce qu'elle fait                     | Exemple        |
| -------------- | ----------------------------------- | -------------- |
| `pwd`          | Affiche le dossier où je suis       | `pwd`          |
| `cd`           | Change de dossier                   | `cd ~/dev`     |
| `ls`           |   Affiche le contenu du dossier     | `ls`           |
| `ls -l`        | Le contenu en détail                | `ls -l`        |
| `ls -a`        |   les fichiers cachés               | `ls -a`        |
| `clear`        | Efface l’écran                      | `clear`        |
| `whoami`       | Affiche votre nom d’utilisateur     | `whoami`       |
| `echo`         |   Affiche un texte                  | `echo bonjour` |
| `ls --help`    |   Affiche l’aide de la commande  ls | `ls --help`    |
|  `# Mon titre` |   Un grand titre                    | `#Titre1`      |

## Fichiers et dossiers

| Commande                     | Ce qu'elle fait                                  | Exemple                         |
| ---------------------------- | ------------------------------------------------ | ------------------------------- |
| `cp`                         | Copie un fichier                                 | `cp a.txt b.txt`                |
| `mkdir`                      | Crée un dossier                                  | `mkdir photo`                   |
| `mkdir -p`                   |  Crée plusieurs niveaux de dossiers              | `mkdir -p projet/assets/images` |
| `touch vide.txt`             |  Crée un fichier vide                            | `touch vide.txt`                |
| `echo "Bonjour" > notes.txt` |  Crée un fichier qui contient une ligne de texte | `echo "Bonjour" > notes.txt`    |
| `cp -r projet sauvegarde `   | Copie un dossier et tout son contenu             | `cp -r projet sauvegarde`       |
| `mv notes.txt archives/`     | Déplace un fichier dans un dossier               | `mv notes.txt archives/`        |
| `mv notes.txt idees.txt `    | Renomme un fichier                               | `mv notes.txt idees.txt`        |
| `Rm notes.txt `              | Supprime un fichier                              | `Rm notes.txt `                 |
| `rm -i notes.txt `           | Supprime, mais demande d’abord confirmation      | `rm -i notes.txt `              |

## Lire et chercher

…

## Les commandes des branches

| Commande                          | Ce qu’elle fait                                                     |
| --------------------------------- | ------------------------------------------------------------------- |
|  git branch                       | Liste les branches. Une étoile  \*  montre celle où vous êtes       |
|  git switch -c ajout-section      |   Crée la branche  ajout-section  et va dessus ( -c  : create)      |
|  git switch main                  | Va sur la branche  main                                             |
|  git merge ajout-section          | Fusionne la branche  ajout-section  dans la branche ou vous êtes    |
|  git branch -d ajout-section      | Supprime la branche  ajout-section , une fois qu'elle est fusionnée |
|  git log --oneline --graph --all  | Dessine l’historique avec toutes les branches                       |

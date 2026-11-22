# env-dev-warith (B1 DEV, IFRAN)

Environnement de développement de Diarra Check – B1 DEV, IFRAN.

## Mon ordinateur

| Élément    | Valeur                                         |
| ---------- | ---------------------------------------------- |
| Système    | Windows 11 Famille                             |
| Processeur | 13th Gen Intel(R) Core(TM) i5-1340P (1.90 GHz) |
| Mémoire    | 16 Go                                          |
| Éditeur    | VS Code                                        |

## Mon Ubuntu

| Élément     | Valeur             |
| ----------- | ------------------ |
| Version     | Ubuntu 26.04.1 LTS |
| Lancé avec  | WSL                |
| Processeurs | 16                 |
| Mémoire     | 7,6 Go             |
| Utilisateur | warith             |

## Logiciels installés dans Ubuntu

| Logiciel | Version | Commande d'installation  
|
| -------- | -------- | --------------------------------------------------- |
| Git | 2.53.0 | déjà présent dans Ubuntu |
| tree | 2.3.1 | `sudo apt install -y tree` |
| htop | 3.4.1 | `sudo apt install -y htop` |
| nano | 8.7.1 | `sudo apt install -y nano` |
| Node.js | 26.13.1 | dépôt NodeSource, puis `sudo apt install -y nodejs` |
| npm | 11.20.0 | installé avec Node.js |

## Installation

### 1. Installer Ubuntu et VS Code

- **Windows :** dans le Terminal (administrateur), taper `wsl --install`,
  redémarrer, puis choisir un nom d'utilisateur et un mot de passe Ubuntu. - **Mac :** installer Homebrew depuis [brew.sh](https://brew.sh), puis taper
  `brew install colima docker`, `colima start` et `colima ssh`. - Installer VS Code depuis [code.visualstudio.com](https://code.visualstudio.com).

### 2. Installer les outils dans Ubuntu

1. Ouvrir Ubuntu et aller dans le dossier du projet : `cd ~/dev/env-dev-warith`
2. Lancer le script d'installation : `./scripts/installer.sh`

## Vérification

Lancer `./scripts/verifier.sh` dans Ubuntu.
Résultat attendu : une version pour Ubuntu, Git, Node.js, npm et tree.

## Contenu du dossier

| Fichier ou dossier     | Rôle                    |
| ---------------------- | ----------------------- |
| `README.md`            | Cette documentation     |
| `JOURNAL.md`           | Le journal de mes choix |
| `docs/aide-memoire.md` | …                       |
| `scripts/installer.sh` | …                       |
| `scripts/verifier.sh`  | …                       |

## Historique

Ce dossier est suivi avec Git depuis le sous-module 2.

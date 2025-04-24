<div align="center">

# OpenClassrooms - JSE-Avocats
</div>

<p align="center">
    <img src="https://img.shields.io/badge/MariaDB-v11.7.2-blue">
    <img src="https://img.shields.io/badge/Wordpress-v6-blue">
    <img src="https://img.shields.io/badge/docker--build-passing-brightgreen">
  <br><br><br>
</p>

# Prérequis
Pour démarrer cet applicatif web vous devez avoir les outils suivants:
- Docker

# Installation et démarrage
Clonez le projet pour le récupérer
``` 
git clone https://github.com/OpenClassrooms-Student-Center/JSE-Avocats-V2.git
cd JSE-Avocats-V2
```
Enfin pour le démarrer
```
docker compose up -d

```

# Important
Cet applicatif est fait avec wordpress.
Il ce peut que le démarrage final prenne quelques secondes après le démarrage des conteneurs

## Pour éteindre le projet
Assurez vous d'être dans le dossier du projet
(là où se trouve le fichier docker-compose.yml)

```
docker compose down
```

## Fin de travail
Si vous ne revenez pas sur le projet, vous avez la possibilité de supprimer les fichiers et images Docker afin de récupérer la place

```
docker system prune -a

=> tapez Y puis Entrée
```

Cela supprime tout le projet

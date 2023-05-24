# Projet server web
## Context
Projet d'infrastructure et réseau réalisé par deux bachelors informatiques en première année, étudiants de l'école Ynov.
## Objectifs
* Monter un server web sur lequel 2 applications web doivent s'exécuter
* Devoir accéder aux applications via des sous-domaines
* Mise en place d'un loadbalancer
* Sécuriser les échanges entre le loadbalancer et les applications à l'aide de certificats ssl auto-signés
## Application
* Application 1 : Youtube Downloader qui télecharge des musique en mp3 fait avec golang.
* Application 2 : Weather App est une simple application de météo fait avec flask.
## Technologies et outils utilisées
### Première application:
#### Youtube Converter
- front :
    - Node
    - React
    - Next.Js
    - Tailwind
- back :
    - Golang
    - [Youtube-dl](https://github.com/ytdl-org/youtube-dl)
- Docker
### Deuxième application:
#### Weather app
- front :
    - Html
    - Css
- back :
    - Python
    - Flask

## LoadBalancer / ReverseProxy :
- [Kemp](https://freeloadbalancer.com)

## Virtualisation:
- Virtual Box
- Ubuntu
## Caractéristiques techniques :


## Documentation :
[Document pour ajouter une application et gestion de certificat](https://github.com/TomJegou/Projet-infra-SI/wiki/)

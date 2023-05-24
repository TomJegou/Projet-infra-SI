# Projet server web
## Context
Projet d'infrastructure et réseau réalisé par deux bachelors informatiques en première année, étudiants de l'école Ynov.
## Objectifs
* Monter un server web sur lequel 2 applications web doivent s'exécuter
* Devoir accéder aux applications via des sous-domaines
* Mise en place d'un loadbalancer
* Sécuriser les échanges entre le loadbalancer et les applications à l'aide de certificats ssl auto-signés
## Applications
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
- Une machine virtuelle sur laquelle tourne au moins deux applications dans des langages différents.
- Une machine virtuelle avec un Loadbalancer/reverse proxy, qui redirige les requettes vers la bonne application et gérer la gestion de certificats et la gestion de sous-domaines.
- Le loadbalancer n'a qu'une vip (virtual ip address) avec qu'un seul port d'ouvert qui sert de porte pour les applications.
- Pour accéder à une application: `https://nom-de-application.ynov.tomyjthebest`
- Un certificat SSL auto-signé est utilisé pour le protocole `https`
## Tutoriels :
Si vous voulez savoir comment mettre en place un system semblable à la maquette, cliquez [ici](https://github.com/TomJegou/Projet-infra-SI/wiki/)

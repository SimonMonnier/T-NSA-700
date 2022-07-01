# T-NSA

## Aide

Avoir l'ip d'un conteneur-> docker inspect containerID ou docker exec -it containerID ip a

Windows :
Changer dans docker-compose.yml et config.toml giltab.example.com par l'adresse ip du conteneur gitlab

Linux :
Ajouter/modifier dans /etc/hosts:
ContainerIP gitlab.example.com

Aide Deprecié:

- (Pour register ton gitlab-runner s'il n'y a pas de config.toml
docker exec -it containerID gitlab-runner register )
Maintenant le volume avec config.toml est directement dans le repo

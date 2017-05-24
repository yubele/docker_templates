# docker_templates

## wordpress

```
$ cd wordpress
$ cp env.conf.example .env.conf
$ vim .env.conf # Edit environments of nginx
$ cp env.example .env
$ vim .env # Edit environments of docker container
```

Run docker
```
$ source .env && sudo docker-compose up
```

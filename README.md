# OpenStack client in a docker container

## HowTo

1. Copy and edit `.env.sample` file to `.env`

```sh
cp .env.sample .env
editor .env
```

2. Run docker using docker compose


```bash
docker compose run --rm -it --build openstack openstack
```

# OpenStack client docker container

* copy and edit `.env.sample` file to `.env`

```sh
cp .env.sample .env
editor .env
```

* Run docker using docker compose

docker run --rm -it --env-file .env  --build openstack

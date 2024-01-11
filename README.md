## How to run

The easiest way to run **Loggaroo** is via the `compose.yml` in this repo.

To start the `compose.yml` you will need docker in case you do not have docker installed yet please follow [this tutorial](https://docs.docker.com/engine/install/).

Once you have docker installed simply run the command

```bash
docker compose up
```

this will start up all services including node-backend, rust-backend, frontend and a database.

Once this is done head to [localhost:8080](http://localhost:8080) and use **Loggaroo**
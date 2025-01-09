# To start

Start backend services rabbitmq ES mongodb

```bash
cd .
docker compose up -d
```

start gui

```bash
cd .
uv run poe gui start
```

start workers. Restart this to update plugin.

```bash
cd .
uv run poe start
```

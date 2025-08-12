# impulse
I'm not sure how I determined that learning about uncertainty is part of my motivation. I just did.

## 1. How to run
### 1-1. Set up the environment
Change to [`./infra-local/`](./infra-local/) directory:
```bash
cd ./infra-local/
```

Start the containers:
```bash
docker compose up --build --remove-orphans -d
```

### 1-2. Run the AI learning
Get inside the container:
```bash
docker compose exec impulse-ai bash
```

And check [`./impulse-ai/README.md`](./impulse-ai/README.md) for more details.

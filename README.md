# oh-my-stacks

Oh, run my environment on anywhere.


## Usage

### Docker-Compose

```bash
docker-compose -f oh-my-stacks/local/docker-compose.yml up -d
```

### Docker-Swarm

```bash
docker stack deploy -c oh-my-stacks/infra/docker-compose.yml infra

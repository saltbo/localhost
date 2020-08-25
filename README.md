# oh-my-stacks

Oh, run my environment on anywhere.


## Usage

### Docker-Compose

```bash
docker-compose -f oh-my-env/stack/dev.yml up -d
```

### Docker-Swarm

```bash
docker stack deploy -c oh-my-env/stack/prod.yml oh-my-stack 

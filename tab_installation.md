---

title: Installation
displaytext: Installation
layout: null
order: 3
tab: true
tags: dependency-track dtrack

---

## Installation

Dependency-Track is distributed as Docker containers.

### Docker Compose

```bash
curl -LO https://dependencytrack.org/docker-compose.yml
docker-compose up -d
```

### Docker Swarm

```bash
curl -LO https://dependencytrack.org/docker-compose.yml
docker swarm init
docker stack deploy -c docker-compose.yml dtrack
```

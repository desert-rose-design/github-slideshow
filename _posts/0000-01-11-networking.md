---
layout: slide
title: "Docker Networking"
---

### Network Types

| Type | Use Case |
|------|----------|
| **bridge** | Default, isolated network for containers |
| **host** | Share host's network stack |
| **none** | No network access |
| **overlay** | Multi-host networking (Swarm) |

```bash
# Create a network
docker network create mynetwork

# Connect container to network
docker run --network mynetwork myapp
```

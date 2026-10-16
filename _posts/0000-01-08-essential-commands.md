---
layout: slide
title: "Essential Docker Commands"
---

### Building & Running

```bash
# Build an image
docker build -t myapp .

# Run a container
docker run -d -p 8080:3000 myapp

# List running containers
docker ps

# Stop a container
docker stop <container_id>

# View logs
docker logs <container_id>
```

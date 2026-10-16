---
layout: slide
title: "Best Practices"
---

### Building Better Images

1. **Use official base images** - Security & reliability
2. **Minimize layers** - Combine RUN commands
3. **Use .dockerignore** - Exclude unnecessary files
4. **Don't run as root** - Add USER instruction
5. **Use multi-stage builds** - Smaller final images
6. **Tag images properly** - Avoid using `latest`
7. **Scan for vulnerabilities** - Use `docker scout`

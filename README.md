# OWASP Juice Shop Live Demo

This repository documents our live demonstration of vulnerabilities
using OWASP Juice Shop running in a Docker container.

## How the demo was run
```bash
docker pull bkimminich/juice-shop
docker run -d -p 3000:3000 bkimminich/juice-shop

Accessed via: http://localhost:3000

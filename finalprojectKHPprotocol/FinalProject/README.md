# KHP Protocol Exploit

This repository contains the necessary scripts and instructions to exploit the `khp_server` challenge and retrieve the flag.

## Files
- **Dockerfile**: Defines the containerized environment for testing `khp_server`.
- **build-docker.sh**: Automates the process of building and running the Docker container.
- **exploit.py**: Python script to exploit the buffer overflow vulnerability in `khp_server`.

## Steps to Use

### 1. Build and Run the Docker Container
```bash
chmod +x build-docker.sh
./build-docker.sh

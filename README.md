# Rocky Linux 8 (Molecule)

[![Container Release (Rocky Linux 8)](https://github.com/leberkaslabs/molecule-rockylinux-8/actions/workflows/build-push-action.yml/badge.svg)](https://github.com/leberkaslabs/molecule-rockylinux-8/actions/workflows/build-push-action.yml)

This repository is used to build Rocky Linux 8 Docker images for Ansible [Molecule](https://ansible.readthedocs.io/projects/molecule/).

```bash
docker pull dudecalledbro/molecule-rockylinux-8:latest
```

## Build

This image build is scheduled with GitHub Actions and will be pushed to DockerHub. The image will also be rebuilt, if the `main` branch is updated. If you need to build the image locally, ensure [Docker](https://docs.docker.com/engine/installation/) is installed and execute the following:

```bash
docker build -t molecule-rockylinux-8:latest .
```

## License

Copyright © 2025 Niclas Spreng

Licensed under the [MIT license](LICENSE).

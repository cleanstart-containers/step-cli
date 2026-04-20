# CleanStart Container for Step CLI

Official Step CLI container image optimized for enterprise environments. Includes the complete Step CLI toolkit for zero-trust network identity and certificate management. Features security-hardened base image, minimal attack surface, and FIPS-compliant cryptographic modules. Supports both production deployments and development workflows with separate tagged versions. Includes Step CLI, Step CA, and essential PKI tools for certificate management.

## Key Features

- Complete Step CLI environment with PKI capabilities
- Optimized for cloud-native and microservices architectures

## Common Use Cases

- Certificate management and PKI operations
- Zero-trust network identity

## Pull Commands

Download the runtime container images
```bash
docker pull ghcr.io/cleanstart-containers/step-cli:latest
docker pull ghcr.io/cleanstart-containers/step-cli:latest-dev
```

## Interactive Development

Start interactive session for development
```bash
docker run --rm -it --entrypoint /bin/sh ghcr.io/cleanstart-containers/step-cli:latest-dev
```

## Container Start

Start the container
```bash
docker run --rm -it --name step-cli-dev ghcr.io/cleanstart-containers/step-cli:latest
```

## Best Practices

- Use specific image tags for production (avoid latest)
- Configure resource limits: memory and CPU constraints
- Enable read-only root filesystem when possible

## Architecture Support

### Multi-Platform Images
```bash
docker pull --platform linux/amd64 ghcr.io/cleanstart-containers/step-cli:latest
docker pull --platform linux/arm64 ghcr.io/cleanstart-containers/step-cli:latest
```

---

## Documentation Resources
Essential links and resources for further information
 
**CleanStart Images**: https://images.cleanstart.com/
 
**Community Images**:
**Docker Hub**: https://hub.docker.com/u/cleanstart<br>
**GitHub**: https://github.com/cleanstart-containers<br>
**AWS ECR Public Gallery**: https://gallery.ecr.aws/cleanstart/
 
**Presence on Social Media**:
**Community**: https://www.linkedin.com/groups/18324021/<br>
**YouTube**: https://www.youtube.com/@CleanStartOfficial<br>
 
**Contribute to Container Use Cases**: https://github.com/cleanstart-dev/cleanstart-use-cases/

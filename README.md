# portfolio

## Requirements:
- Traefik (helm) with CRDS
- Cert-manager (helm or manifests)
- Public DNS pointing to the traefik's LB IP; like mine: https://gbt55.myddns.me/

1 - Build (Portfolio)[https://github.com/soumyajit4419/Portfolio] on a Docker Image & upload to hub.docker.com
```bash

```
2 - Create a deployment for the Portfolio in my kubernetes cluster

3 - Create a cert specifying the secret-name, which is the private key cert, and the ClusterIssuer, which was previously created by me

4 - create ingress route specifying it
# DockerHub Mirror
DockerHub Mirror on Github powered by Github Actions and [Crane](https://github.com/google/go-containerregistry/tree/main/cmd/crane)  
[![GitHub Workflow Status (branch)][github-actions-badge]][github-actions-link] 

GitHub Actions scheduled to run daily at Midnight UTC to mirror some images to [GHCR.io](https://ghcr.io), bypassing rate limits

Mirrored Images:
* [`alpine`](https://ghcr.io/rblaine95/alpine)
* [`busybox`](https://ghcr.io/rblaine95/busybox)
* [`debian`](https://ghcr.io/rblaine95/debian)
* [`kubectl`](https://ghcr.io/rblaine95/kubectl)
* [`golang`](https://ghcr.io/rblaine95/golang)
* [`node`](https://ghcr.io/rblaine95/node)
* [`mysql`](https://ghcr.io/rblaine95/mysql)
* [`openjdk`](https://ghcr.io/rblaine95/openjdk)
* [`postgres`](https://ghcr.io/rblaine95/postgres)
* [`python`](https://ghcr.io/rblaine95/python)
* [`rust`](https://ghcr.io/rblaine95/rust)

[github-actions-badge]: https://img.shields.io/github/workflow/status/rblaine95/dockerhub-mirror/Mirror%20Dockerhub/master "Github Workflow Status (master)"
[github-actions-link]: https://github.com/rblaine95/dockerhub-mirror/actions?query=workflow%3AMirror%20Dockerhub

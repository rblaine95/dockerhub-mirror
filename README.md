# DockerHub Mirror

DockerHub Mirror on [GHCR.io](https://ghcr.io) powered by Github Actions and [Crane](https://github.com/google/go-containerregistry/tree/main/cmd/crane)

[![GitHub Workflow Status (branch)][github-actions-badge]][github-actions-link]

GitHub Actions scheduled to run daily at Midnight UTC to mirror some images to [GHCR.io](https://ghcr.io), bypassing rate limits

Mirrored Images:

* [`alpine`](https://ghcr.io/rblaine95/alpine)
* [`busybox`](https://ghcr.io/rblaine95/busybox)
* [`debian`](https://ghcr.io/rblaine95/debian)
* [`eclipse-temurin`](https://ghcr.io/rblaine95/eclipse-temurin)
* [`golang`](https://ghcr.io/rblaine95/golang)
* [`mysql`](https://ghcr.io/rblaine95/mysql)
* [`node`](https://ghcr.io/rblaine95/node)
* [`openjdk`](https://ghcr.io/rblaine95/openjdk) **DEPRECATED** - docker-library/openjdk#505
* [`postgres`](https://ghcr.io/rblaine95/postgres)
* [`python`](https://ghcr.io/rblaine95/python)
* [`rust`](https://ghcr.io/rblaine95/rust)

[github-actions-badge]: https://img.shields.io/github/actions/workflow/status/rblaine95/dockerhub-mirror/mirror.yml?branch=master "Github Workflow Status (master)"
[github-actions-link]: https://github.com/rblaine95/dockerhub-mirror/actions?query=workflow%3AMirror%20Dockerhub

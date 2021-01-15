# DockerHub Mirror
DockerHub Mirror on Github powered by Github Actions  
[![GitHub Workflow Status (branch)][github-actions-badge]][github-actions-link] 

GitHub Actions scheduled to run daily at Midnight UTC to mirror some images to [GHCR.io](https://ghcr.io), bypassing rate limits

Mirrored Images:
* [`alpine`](https://ghcr.io/rblaine95/alpine)
* [`busybox`](https://ghcr.io/rblaine95/busybox)
* [`debian`](https://ghcr.io/rblaine95/debian)
* [`golang`](https://ghcr.io/rblaine95/golang)

[github-actions-badge]: https://img.shields.io/github/workflow/status/rblaine95/dockerhub-mirror/Mirror%20Dockerhub/master "Github Workflow Status (master)"
[github-actions-link]: https://github.com/rblaine95/dockerhub-mirror/actions?query=workflow%3AMirror%20Dockerhub

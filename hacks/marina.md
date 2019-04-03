---
hackname: Marina
quicksummary: A simple container scheduler with some batteries included.
resource: true
categories: [hack]
---

Marina
========

Marina is a simple container scheduler that runs a few applications on a single node, e.g. AWS EC2, DigitalOcean Droplet.

It should have the following features:

- HTTP API to schedule workload (run and remove containers)
- HTTP API to trigger deployments of existing applications (CI/CD integration)
- HTTP Reverse Proxy that listens on port 80 (HTTP) and 443 (HTTPS) to forward traffic to the different applications
- Automatically HTTPS certificate management using [Let's Encrypt](https://letsencrypt.org/)

Why Do It?
----------
Kubernetes and similiar orchestration systems are built to distribute workload across multiple nodes in a cluster. They are great products but sometimes running and managing a Kubernetes cluster requires to much effort to run only 2-4 applications. Thus, having a simple container scheduler that is able to run a few appliations that are exposed via automatically issued HTTPS endpoints whould be great.

Requirements
------------

- [Containerd](https://containerd.io/), an industry-standard container runtime
- Basic knowledge of Docker, Kubernetes, or similiar
- Developers interested in learning more about how container orchestration systems work
- Preferred programming language is Golang, but open for discussion

Could use help with...
----------------------

- API Design and implementaton
- HTTP/HTTPS traffic forwarding
- Automated Let's Encrypt certifcated management
- Ensure developer happiness :)

Links
-----

- [Containerd](https://containerd.io/)
- [Let's Encrypt](https://letsencrypt.org/)
- [Docker](https://docker.com)
- [Kubernetes](https://kubernetes.io)


Who's Participating?
--------------------

* [Fabian Mettler](/tamedia-hackdays/whoami/fabianmettler)
* Further help welcome...


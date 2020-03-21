# Container Scanning without setting up Clair server

### What
This repository contains a working example of local container scanning using arminc's prefilled CVE database and Clair.
Using this, you won't need to have to setup a whole Clair server, or fill and maintain a CVE database.
The bash code is pretty universally applicable, the example is written for gitlabCI and does not require Gitlab Ultimate subscription.

### Scan subject
Subject of the scan is a kube-toolbox container I use for K8S work mainly on AWS.

### Requirements
Requirements are:
- Docker

Requirements using the GitlabCI setup:
- docker-executor --privileged

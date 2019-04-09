---
description: Security Projects from BBVA-Labs Team
---

# BBVA-Labs Security

## BBVA-Lab Security Team

Our DevSecOps tools

### DeepTracy - The Security Dependency Analyzers Orchestrator

![DeepTracy Logo](.gitbook/assets/deeptracy-logo-small.png)

DeepTracy is an open security dependency orchestrator service that runs as a service. Featured features:

* Manage multiple Security Dependencies analysers
* Web Interface to manage different builds
* DevSecOps oriented. Build having in mind the integration with C.I. systems.
* Proactive alert: It can alert to the project manager when new vulneabilities appears in the project dependencies
* Featured GraphQL API thanks to Hashura

**Github Repo:** [**https://github.com/BBVA/deeptracy**](https://github.com/BBVA/deeptracy)\*\*\*\*

#### Documentation: [https://github.com/BBVA/deeptracy/tree/master/docs](https://github.com/BBVA/deeptracy/tree/master/docs)

### Patton - The clever vulnerability dependency finder

![Patton Logo](.gitbook/assets/patton-logo.png)

Patton Server can resolve any library name to their CPE. Then returns the associated CVEs for this CPE. Features:

* Get [CPE](https://nvd.nist.gov/products/cpe) Identifier from service banner 
* Get CPE Identifier from operating system dependency name \(Debian, Alpine, Redhat, Python, Golang...\)
* **Resolve CVE** vulnerabilities **from CPE identifiers.**

#### Github Repo: [https://patton-server.readthedocs.org/](https://github.com/BBVA/patton-server)

#### Documentation: [https://patton-server.readthedocs.org/](https://patton-server.readthedocs.org/)


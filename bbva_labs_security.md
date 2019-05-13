---
description: Security Projects from BBVA Labs Security Team
---

# BBVA Labs - Security

## Who we are

We are security practitioners controlling our paranoia \(sometimes\) and focusing our knowledge and experience to build new security solutions and practices for new \(and old\) IT systems and processes.

## What we do

We research new **security tendencies, techniques and solutions** in Cyber-security issues, especially focused in **SecDevOps** processes with near-future impact in the security of BBVA Group and hopefully in the rest of the world.

## Our projects

We like Open Source and we believe in the **"Don't reinvent the wheel"** mantra.

We create projects that **try to close the gaps** not covered by any other Open Source projects nor commercial solutions yet.

Here you can check our projects. We invite you to use them, test them and ... collaborate. **We welcome contributions!**

### APICheck - The DevSecOps toolset for REST APIs

API-Check is a complete **toolset** designed and created for **testing the REST API**.

API-Check focus not only in the security testing and hacking use cases. The goal of the project is to be a complete toolset for DevSecOPs cycles and for different user profiles:

* Developers
* Systems SysAdmins
* Security & penteters

<table>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src=".gitbook/assets/apicheck-logo.png" />
        </p>
      </td>
      <td style="text-align:left">
        <p>
            <b>Github Repo</b>: <a href="https://github.com/BBVA/apicheck">https://github.com/BBVA/apicheck</a>
            <br/>
            <b>Documentation</b>: <a href="https://apicheck.readthedocs.io">https://apicheck.readthedocs.io</a>
        </p>
      </td>
    </tr>
  </tbody>
</table>


### DeepTracy - The Security Dependency Analyzers Orchestrator

DeepTracy is an open security dependency orchestrator service that runs as a service. Featured features:

* Manage multiple security dependency analysers.
* Web interface to manage different builds.
* DevSecOps oriented. Build having in mind the integration with C.I. systems.
* GraphQL API thanks to Hashura.

<table>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src=".gitbook/assets/deeptracy-logo-small.png" />
        </p>
      </td>
      <td style="text-align:left">
        <p>
            <b>Github Repo</b>: <a href="https://github.com/BBVA/deeptracy">https://github.com/BBVA/deeptracy</a>
            <br/>
            <b>Documentation</b>: <a href="https://deeptracy.readthedocs.io/en/latest/">https://deeptracy.readthedocs.io/en/latest/</a>
        </p>
      </td>
    </tr>
  </tbody>
</table>

### Patton - The clever vulnerability dependency finder

Patton Server can resolve any library name to their CPEs and return the associated CVEs. Features:

* Get [CPE](https://nvd.nist.gov/products/cpe) Identifier from service banner.
* Get CPE identifier from operating system dependency name \(Debian, Alpine, Redhat, Python, Golang...\).
* **Resolve CVE** vulnerabilities **from CPE identifiers**.

<table>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src=".gitbook/assets/patton-logo.png" />
        </p>
      </td>
      <td style="text-align:left">
        <p>
            <b>Github Repo</b>: <a href="https://github.com/BBVA/patton">https://github.com/BBVA/patton</a>
            <br/>
            <b>Documentation</b>: <a href="https://patton.readthedocs.io">https://patton.readthedocs.io</a>
        </p>
      </td>
    </tr>
  </tbody>
</table>

### Kapow - CLI as Microservice

Kapow! is the most powerful way to expose command line tools as REST APIs.

**Usage example**

Creating a port scanning REST API backed by the well-known tool [Nmap](https://nmap.org) only needs a few Kapow! lines: [http://site.com/tools/nmap/scan/{IP}](http://site.com/tools/nmap/scan/{IP})

<table>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src=".gitbook/assets/kapow.png" />
        </p>
      </td>
      <td style="text-align:left">
        <p>
            <b>Github Repo</b>: <a href="https://github.com/BBVA/kapow">https://github.com/BBVA/kapow</a>
            <br/>
            <b>Documentation</b>: <a href="https://github.com/BBVA/kapow">https://github.com/BBVA/kapow</a>
        </p>
      </td>
    </tr>
  </tbody>
</table>

### Masquerade - Real-Time data obfuscation

Masquerade is a high-performance, real-time, multi-location data obfuscation tool.

Masquerade allows getting data from many different locations or sources, obfuscate it, and export it to other location. i.e:

**You can get data from CSV in an AWS S3 bucket, and store the results in a HDFS filesystem... in real time!**

Masquerade currently supports these locations:

* AWS S3
* HDFS
* Google Cloud Storage \(GCS\)
* RabbitMQ
* Local files

<table>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src=".gitbook/assets/masquerade-logo-small.png" />
        </p>
      </td>
      <td style="text-align:left">
        <p>
            <b>Github Repo</b>: <a href="https://github.com/BBVA/masquerade">https://github.com/BBVA/masquerade</a>
            <br/>
            <b>Documentation</b>: <a href="https://masquerade-data.readthedocs.io">https://masquerade-data.readthedocs.io</a>
        </p>
      </td>
    </tr>
  </tbody>
</table>

### Q.E.D. - Scalable, auditable and high-performance tamper-evident log

QED is an open-source software that allows you to establish trust relations with others. It can be used in multiple scenarios: secure
tamper evident data transfers, tamper-evident (system/application/business) logging, etc.

QED guarantees that the system itself, event when deployed into a non-trusted server, cannot be modified without being noticed.
It also provides verifiable cryptographic proofs in logarithmic relation (time and size) to the number of entries.

QED aims to be scalable, resilient and ops friendly:

* Designed to manage billions of events per shard
* Over 2000 operations per second per shard under sustained load
* Consistent replication through RAFT
* Operable and instrumented with dozens of metrics
* Zero config files, fully documented single binary

<table>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p>
          <img src=".gitbook/assets/qed_logo.png" />
        </p>
      </td>
      <td style="text-align:left">
        <p>
            <b>Github Repo</b>: <a href="https://github.com/BBVA/qed">https://github.com/BBVA/qed</a>
            <br/>
            <b>Documentation</b>: <a href="https://github.com/BBVA/qed/blob/master/README.md">https://github.com/BBVA/qed/blob/master/README.md</a>
        </p>
      </td>
    </tr>
  </tbody>
</table>


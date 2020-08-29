---

layout: col-sidebar
title: OWASP Kubernetes Security Testing Guide
tags: kstg
level: 1
type:
pitch: A comprehensive guide to Kubernetes Security Testing

---

[![Creative Commons License](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/ "CC BY-SA 4.0")

## Our Vision

### "Create a comprehensive manual for Kubernetes Cluster Security Assessment"

We are creating a comprehensive testing guide for Kubernetes cluster security assessment that covers a top down approach to assess the security of a cluster. The guide include methodology, tools, techniques and procedures (TTP) to execute an assessment that enables a penetration tester to deliver consistent and complete results.

## Deliverables

### Kubernetes Security Testing Guide (KSTG)

The KSTG is (aims to be) a comprehensive manual for Kubernetes security analysts and red teamers. It aims to help DevSecOps Teams understand attacker TTPs and design effective countermeasures. KSTG *propose* to have the following high-level structure:

1. Introduction to Kubernetes Architecture and its Components
2. Kubernetes Cluster Threat Model
3. Container Security Assessment
4. Cluster Discovery and Recon
5. Cluster Security Assessment
6. Auditing against CIS Benchmarks

### Kubernetes Security Testing Checklist

A checklist will be created based on the KSTG. This checklist is meant to be used as a reference by security testers during engagements.

### Kubernetes Security Testing Tools

* Infrastructure Security
.. CloudSploit, https://github.com/cloudsploit/scans

* Docker Security
.. Clair, https://github.com/quay/clair 
.. Anchore, https://github.com/anchore/anchore-engine
.. OpenSCAP, https://github.com/OpenSCAP/openscap

* Kubernetes Security
.. kube-bench, https://github.com/aquasecurity/kube-bench
.. kubeaudit, https://github.com/Shopify/kubeaudit
.. kube-scan, https://github.com/octarinesec/kube-scan 
.. kubesec, https://github.com/controlplaneio/kubesec
.. kube-hunter, https://github.com/aquasecurity/kube-hunter
.. kubei, https://github.com/Portshift/kubei

* General Purpose
.. Metasploit
.. Panther, Cloud-Native SIEM, https://github.com/panther-labs/panther
.. Sysdig Falco


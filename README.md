<div align="center">
  <img src="logo.svg" alt="Skyhold Logo" width="120" />
</div>

# Welcome to Skyhold

![Status](https://img.shields.io/badge/status-Active-brightgreen.svg)
![Cloud Providers](https://img.shields.io/badge/providers-Scaleway%20%7C%20Hetzner-blueviolet.svg)
![Kubernetes](https://img.shields.io/badge/kubernetes-326CE5.svg?logo=kubernetes&logoColor=white)

Skyhold is a centralized cloud provider aggregator and control plane. Our mission is to radically simplify the development and operational workflow for engineers managing multi-cloud resources and Kubernetes clusters.

## What We Do

Managing infrastructure across different cloud providers typically introduces immense operational overhead, fragmented tools, and steep learning curves. 

Skyhold solves this complexity by providing a developer-friendly, unified platform. Instead of forcing developers to master multiple provider APIs or complex networking setups, Skyhold abstracts these difficulties away, handling robust state synchronization and asynchronous provisioning automatically.

## Open Source Tooling

We believe in empowering developers with the right tools. While our core control plane is proprietary, we maintain official, open-source tools to interact with the Skyhold ecosystem seamlessly:

*   **[Skyhold CLI](https://github.com/SkyholdDev/skyhold-cli):** The official Command Line Interface. Manage your multi-cloud infrastructure and Kubernetes clusters directly from your terminal. (Apache 2.0)
*   **[Skyhold Node.js SDK](https://github.com/SkyholdDev/skyhold-sdk):** The official TypeScript/Node.js SDK. Programmatically integrate multi-cloud provisioning into your own applications, internal tooling, or CI/CD pipelines. (Apache 2.0)

## The Core Platform

Our proprietary infrastructure powers the Skyhold experience:

*   **Skyhold Web:** A full-fledged cloud console—comparable to the AWS Management Console or Scaleway Console—designed for engineers to deeply manage, provision, and observe resources across multiple providers.
*   **Skyhold API:** The robust backend orchestration engine handling declarative infrastructure deployment, state drift synchronization, and multi-tenant security via RESTful endpoints.

## Supported Technologies

*   **Kubernetes:** Native support for provisioning and managing K8s clusters seamlessly across different clouds.
*   **Hetzner Cloud:** Optimized for cost-effective, high-performance compute resources.
*   **Scaleway:** Integrated for broader ecosystem capabilities including managed services and object storage.

## Connect With Us

Ready to simplify your multi-cloud workflow? Explore our [official documentation](https://skyhold.dev/docs) or try out our CLI and SDK to get started.

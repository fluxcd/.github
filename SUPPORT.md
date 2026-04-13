# Flux Support Policy

The Flux project provides support to users on a best-effort basis.
We strive to provide timely and helpful responses to all support requests,
but we cannot guarantee a specific response time.

For professional support with strict SLAs and dedicated support engineers,
see the [Commercial Support](#commercial-support) section below.

## General Questions

If you have a general question, need help with configuration, or want to discuss best practices,
please do not open an issue. Instead, use one of the following channels:

- [GitHub Discussions](https://github.com/fluxcd/flux2/discussions/categories/q-a) - for general questions, discussions, and sharing knowledge with the community.
- [Slack](https://slack.cncf.io/) - join the CNCF Slack workspace and use the `#flux` channel for real-time discussions with maintainers, contributors and users.

Note that by joining the Flux CD community, you agree to abide by the [CNCF Code of Conduct](https://github.com/cncf/foundation/blob/main/code-of-conduct.md).

## Bug Reports

If you have found a bug in Flux, please open a GitHub issue in the relevant repository with a clear description of the problem,
the version of Flux you are using, the steps to reproduce it, and any logs or error messages.

Main repositories of the Flux project where you can report issues:

- [fluxcd/flux2](https://github.com/fluxcd/flux2/issues) - for issues related to the Flux distribution and the CLI.
- [fluxcd/pkg](https://github.com/fluxcd/pkg/issues) - for issues related to the GitOps Toolkit Go SDK for building Flux controllers and CLI plugins.
- [fluxcd/source-controller](https://github.com/fluxcd/source-controller/issues) - for issues related to managing sources (Git, OCI and Helm repositories, S3-compatible Buckets).
- [fluxcd/source-watcher](https://github.com/fluxcd/source-watcher/issues) - for issues related to advanced source composition and decomposition patterns.
- [fluxcd/kustomize-controller](https://github.com/fluxcd/kustomize-controller/issues) - for issues related to building GitOps pipelines with Kustomize.
- [fluxcd/helm-controller](https://github.com/fluxcd/helm-controller/issues) - for issues related to lifecycle management of Helm releases.
- [fluxcd/notification-controller](https://github.com/fluxcd/notification-controller/issues) - for issues related to handling inbound and outbound events (alerts and webhook receivers).
- [fluxcd/image-reflector-controller](https://github.com/fluxcd/image-reflector-controller/issues) - for issues related to scanning container registries for new image tags and digests.
- [fluxcd/image-automation-controller](https://github.com/fluxcd/image-automation-controller/issues) - for issues related to patching container image tags and digests in Git repositories.
- [fluxcd/flagger](https://github.com/fluxcd/flagger/issues) - for issues related to progressive delivery (canary, A/B testing, blue/green deployments).

Please note that end-of-life versions of Flux are not subject to support, and issues related to them may be closed without response.
For more information on supported versions, please see the [release policy](https://fluxcd.io/flux/releases/).

## Feature Requests

If you have an idea for a new feature or an improvement to an existing one, please open a GitHub discussion
under the [proposals category](https://github.com/fluxcd/flux2/discussions/categories/proposals)
to discuss it with the community and maintainers before opening a GitHub issue.

Some proposals may be **substantial**, and for these we ask for a design process to be followed
so that all stakeholders can be confident about the direction Flux is evolving in.
The "RFC" (request for comments) process is intended to provide a consistent and
controlled path for substantial changes to enter Flux. For more information,
please see the [RFC process documentation](https://github.com/fluxcd/flux2/blob/main/rfcs/README.md).

## Security Vulnerabilities

If you discover a security vulnerability within the Flux components, please **DO NOT** publish
it publicly or open an issue. Please refer to our [Security Policy](https://fluxcd.io/security/) for
instructions on how to securely disclose the issue to our security team.

Note that **CVEs found by scanners** in Flux container images related to the base image or other
dependencies should not be reported to the Flux security team.
If your organization has concerns about vulnerabilities in the container images, consider purchasing
a commercial support subscription from a vendor that provides hardening and vulnerability
management for Flux, such as [ControlPlane Enterprise for Flux CD](https://control-plane.io/enterprise-for-flux-cd/).

## Commercial Support

If your company requires 24/7 support, SLAs, hardened images, or private consulting, please consider
purchasing a commercial support subscription and consulting services from a vendor that employs maintainers
to work full-time on the Flux project, such as [ControlPlane](https://control-plane.io/enterprise-for-flux-cd/).
By doing so, you not only get enterprise-grade reliability, but directly invest in the long-term health
and sustainability of the project.

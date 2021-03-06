# Argo

An end-user centered [Kubernetes](https://kubernetes.io/) dashboard to run apps in the cloud.
One click to create a new community (organization, domain) and another click to deploy an app for the new community.

## Planned features

* Allow users to create their own communities, and deploy a suite of apps for the community.
* Apps are described as [Helm](https://helm.sh/) [Charts](https://helm.sh/docs/topics/charts/).
* Deployment to an underlying Kubernetes cluster is hidden from the user, but can still inspect it if the user interested/knowledgable.
* Support for easy upgrade to new versions of apps: allowing users to enable auto-upgrade or to trigger upgrades manually.
* Out-of-the-box best practices for managing a secure cluster and running apps.
* Stable reactivity-enabled API, which is used by Argo's frontend as well.
* Automatic domain (including custom domains) and SSL management.
* Automatic backup of data and easy recovery.
* Easy view into usage.
* Everything is logged and auditable.
* Internationalization and localization.

## Related projects

* [G Suite](https://en.wikipedia.org/wiki/G_Suite) – an inspiration for this project with great ease of use for an end-user, but not open source and thus not reusable, moreover,
  this project generalizes apps available to domains (which we call communities) to be customizable and resuable using Helm Charts, we hope for a similar user experience and ease
  of creating new domains and how suite of apps is then available to users, while all the technical details of running those apps on the cloud are hidden from the user
* [Rancher](https://rancher.com/) – too technical and not suitable for end-users to manage their apps
* [Flux CD](https://fluxcd.io/) – easy to automatically deploy apps to the cluster, but targeting devops and not end-users
* [cPanel](https://cpanel.net/) – provides some similar ideas of easy to deploy web apps, but does not user modern containerization
* [Sandstorm](https://sandstorm.io/) – platform for self-hosting of apps with heavy focus on security, requires a custom way of bundling apps, but this project uses Docker
  and builds upon Kubernetes to do the heavy lifting
* [Helm](https://helm.sh/) – package manager for Kubernetes allowing one to easily deploy apps, this project uses it internally and could be seen as a web dashboard for Helm
* [Taisun](https://www.taisun.io/) – Dockar based app manager for single servers
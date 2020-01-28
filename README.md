# Argo

An end-user centered Kubernetes dashboard to run apps in the cloud. One click to create a new community (organization, domain) and another click to deploy an app for the new community.

## Planned features

* Allow users to create their own communities, create user groups, and manage users (leveraging [Charon](https://gitlab.com/charon/charon/)) accross a suite of apps,
  with SSO accross all apps and communities.
* Each community can have a suite of apps deployed.
* Apps are described as [Helm](https://helm.sh/) [Charts](https://helm.sh/docs/topics/charts/).
* Deployment to an underlying Kubernetes cluster is hidden from the user, but can still inspect it if the user interested/knowledgable.
* Support for easy upgrade to new versions of apps.
* Out-of-the-box security best practices for managing a cluter and running apps.
* Automatic domain (including custom domains) and SSL management.

## Related projects

* [G Suite](https://en.wikipedia.org/wiki/G_Suite) – an inspiration for this project with great ease of use for an end-user, but not open source and thus not reusable, moreover,
  this project generalizes apps available to domains (which we call communities) to be customizable and resuable using Helm Charts
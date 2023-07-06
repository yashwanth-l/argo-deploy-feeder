# ArgoCD Deploy Feeder

This repository contains the manifests for the ArgoCD Deploy Feeder, a component designed to feed deployment events to ArgoCD via [argocd-bootstrap](https://github.com/yashwanth-l/argocd-bootstrap) Repo

## Directory Structure

The directory structure of this repository is as follows:

- **`deploy-kustomize-appset-list`**: This directory holds the configuration _bases_ and _kustomization_ for various tools that can be deployed to the cluster via _kustomize_ using ArgoCD.

- **`deploy-kustomize-appset-matrix`**: This directory holds the configuration _bases_ and _kustomization_ for various tools that can be deployed to the cluster via _kustomize_ using ArgoCD.

- **`deploy-kustomize`**: This directory holds the configuration _bases_ and _kustomization_ for various tools that can be deployed to the cluster via _kustomize_ using ArgoCD.

- **`deploy-helm`**: This directory holds the configuration for various tools that can be deployed to the cluster via helm charts using ArgoCD(_COMING SOON!_).

## Prerequisites

Before using the ArgoCD Deploy Feeder, ensure that you have the following prerequisites in place:

- [argocd-bootstrap](https://github.com/yashwanth-l/argocd-bootstrap) has this repo defined as a  `kind: Application` or `kind: ApplicationSet` defined connecting to this repo using `List` or `Matrix` Generators, offered by ArgoCD CRD's.

## Support

If you have any questions or need assistance, please open an [issue](https://github.com/yashwanth-l/argocd-deploy-feeder/issues).

# multicluster-pipeline
Multicluster GitOps pipeline approach


This source is an example of good practices to use Red Hat OpenShift GitOps. The directories are composed as follows:

.apps --> applications directory definition to use as base for CI Pipelines

.config/cicd --> namespace definition to build and push container image to common namespace named cicd

.config/argocd --> definition for ArgoCD projects and environment deployment

.gitops-kustomize --> base and overlays definition to use for CD Pipelines.

rhacm-root --> directory for argocd multicluster deployment definition

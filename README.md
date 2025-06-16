# Codefresh GitOps Certification examples

This repository contains examples for the ArgoCD/GitOps
certification workshops.

Take the certification yourself at https://codefresh.io/courses/get-gitops-certified/


https://github.com/harrylog/gitops-certification-examples



argocd app create demo \
--project default \
--repo https://github.com/harrylog/gitops-certification-examples/ \
--path "./helm-apps/simple-chart" \
--sync-policy auto \
--dest-namespace default \
--dest-server https://kubernetes.default.svc
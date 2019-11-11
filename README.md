# kubectl-erbly

given `k8s/namespace.yml` with:

    ---
    apiVersion: v1
    kind: Namespace
    metadata:
      name: <%= namespace %>

run

    kubectl erbly namespace=test k8s/*

enjoy

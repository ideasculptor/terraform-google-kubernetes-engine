# Stub Domains Cluster

This example illustrates how to create a cluster that adds custom stub domains to kube-dns.

It will:
- Create a cluster
- Remove the default kube-dns configmap
- Add a new kube-dns configmap with custom stub domains

[^]: (autogen_docs_start)

[^]: (autogen_docs_end)

To provision this example, run the following from within this directory:
- `terraform init` to get the plugins
- `terraform plan` to see the infrastructure plan
- `terraform apply` to apply the infrastructure build
- `terraform destroy` to destroy the built infrastructure
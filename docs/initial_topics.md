# List of initial topics for discussion

1. How many juyterhubs should UBC run?

* do we need low, medium and high performance configurations?

* what about binderhubs and voila dashboards?

1. How do we associate multiple course containers with each hub?

1. How do we set disk quotas/resource limits on spawned containers?

1. How do we backup and restore student volumes?

1. How do we automate container builds?

* Use github actions to build, deploy and test as with [pangeo docker stacks]https://github.com/pangeo-data/pangeo-stacks)?

* Should we use a common base image?

* Use [conda-lock](https://github.com/brl0/conda-lock) for exact pinning?

1. Should we maintain a repository of current helm/ansible/docker-compose/terraform config files?

1. Does UBC need to maintain a container registry?

1. Should we keep a database of per-capita costs for current hubs?

1. How do we load test new deployments to set pod specs for resource intensive courses?

1. How do we cost-recover for upper year courses with extra resource requirements?








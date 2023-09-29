# pactbroker
Pact broker for consumer driven contract testing

This will deploy a pactbroker for consumer driven contract testing on a Kubernetes cluster using
a helm chart [sonam-helm-chart](https://github.com/sonamsamdupkhangsar/sonam-helm-chart)


` helm install pactbroker sonam/mychart -f values.yaml -n backend --version 0.1.12`
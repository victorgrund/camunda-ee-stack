# full-camunda-ee-docker
Camunda EE, Optimize and Elasticsearch, all in one simple docker compose file 

Edit the .env file to select desired images.
Review supported combinations for [**Camunda Platform**](https://docs.camunda.org/manual/latest/introduction/supported-environments/) and [**Optimize**](https://docs.camunda.org/optimize/latest/technical-guide/supported-environments/) when making these selections.

You must have access to Camunda's private registry at registry.camunda.cloud in order to access Camunda EE and Optimize. Trial licenses can be obtained [**here**](https://camunda.com/download/enterprise/).  Use the credentials created in this trial license process to access the registry. 

Containers failing with Exit code 137 are usually indicative of insufficient memory available to the container.

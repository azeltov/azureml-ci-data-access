# Accessing Data from an AzureML Compute Instance

The [notebook in this repo](./access_data_on_ci_template.ipynb) provides a template for accessing data that resides on an Azure cloud datastore (e.g. Blob, 
ADLS, SQL) within an [AzureML Compute Instance](https://docs.microsoft.com/en-gb/azure/machine-learning/service/concept-compute-instance).

We make the assumption that the user:

(a) wants to access data quickly without having to understand too many AzureML abstractions.

(b) is not ready to commit the data to being a registered artefact in an AzureML workspace i.e. you just want access data in order to do some EDA, testing.

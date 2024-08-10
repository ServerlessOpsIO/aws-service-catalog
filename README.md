# aws-service-catalog

Service Catalog products

This repository provides AWS Service Catalog products for the organization. These are configuration and services used in accounts on a case-by-case basis and not things that can be target deployed via CloudFormation StackSets because their usage does not conform with thje organization OU structure.

## Distribution
The method of distribution for these Service Catalog products uses Cloudformation StackSets to replicate products. This is used over the built-in Service Catalog product replication because it obviates the need for a product to be imported from the shared portfolio and into a local account portfolio before it can ber launched.
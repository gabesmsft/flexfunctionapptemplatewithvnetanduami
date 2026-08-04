# Flex Consumption Function App with VNET connection and User-Assigned Managed Identity to Storage account

This ARM template deploys a Flex Consumption Function App that connects to its Storage account dependency via VNET integration and a user-assigned managed identity. Public network access is disabled on the Storage account, and the template includes private endpoints for the Storage account blob and queue endpoints. The private endpoint dependencies and VNET are deployed by default as part of the template.

This template is provided as-is for testing and reference purposes only. It is not production-ready by default and carries no warranty of security, reliability, or fitness for any specific use.

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgabesmsft%2Fflexfunctionapptemplatewithvnetanduami%2Fmaster%2Fdeploy%2Fazuredeploy.json)
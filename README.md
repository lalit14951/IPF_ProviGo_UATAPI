# ProviGo API Automation

Collection of GET request APIs used in ProviGo mobile app. Functionally these APIs are executed at the backend of the mobile app.

## FEATURES

1. Code repository currently supports 12 GET request APIs.
2. Supports Continuous Integration connected to Azure Devops.
3. Once the user and the device token values are committed, it triggers the .yml file to execute the linked Azure pipeline.
4. The results are published in an HTML report which gives a detailed assessment of the test execution.
5. The pipeline Analytics section gives out graphs and metrics on the runs such as Pass rate, Failure rate, Trends etc.

### The following APIs are configured: ###
- admin/messageCategories
- admin/messageTemplates
- devices/status
- productProperties
- products/insurance/products
- referenceData
- products
- workforce/messageTemplates
- loanOffers
- profiles
- marketingContent
- messages
- agreements/{agreementId}
- agreements/{agreementId}/debtCases
- agreements/{agreementId}/events
- agreements/{agreementId}/features/insurance
- agreements/{agreementId}/features/paymentHoliday
- agreements/{agreementId}/payments/expected
- profiles/consents
- profiles/notifications/eventGroups/disabled

The pipeline can be seen [in here](https://dev.azure.com/IPF-International-Limited/CusApp/_build?definitionId=1197). (requires access)

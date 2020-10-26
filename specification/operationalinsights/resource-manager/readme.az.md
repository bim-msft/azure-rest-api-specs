## AZ

These settings apply only when `--az` is specified on the command line.

``` yaml $(az)
az:
  extensions: sentinel
  namespace: azure.mgmt.operationalinsights
  package-name: azure-mgmt-operationalinsights
az-output-folder: $(azure-cli-extension-folder)/src/operationalinsights
python-sdk-output-folder: "$(az-output-folder)/azext_operationalinsights/vendored_sdks/operationalinsights"
  
#cli:
#    cli-directive:
#      directive on operationGroup
#       - select: 'operationGroup'
#         where:
#             operationGroup: 'operations'
#         hidden: true
#       - where:
#             parameter: location
#         required: true

```

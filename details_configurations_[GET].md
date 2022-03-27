# [GET] /api/v2/configurations/{name}

Gets the value for one of these configurations:
- EM_OperatingMode
- NVM_PfcFixedCosPhi
- NVM_PfcIsFixedCosPhiActive
- NVM_PfcIsFixedCosPhiLagging
- EM_ToU_Schedule

## Parameters
| Name | Description |
| :------------: | :------------: |
| name (string) | EM_OperatingMode, NVM_PfcFixedCosPhi, NVM_PfcIsFixedCosPhiActive, NVM_PfcIsFixedCosPhiLagging, EM_ToU_Schedule |

## Responses
| Code | Sample-Output |
| ------------ | :------------: |
| 200 | ``` { "EM_OperatingMode": “2” } ``` |
| 401 | ``` 401 Unauthorized ``` |

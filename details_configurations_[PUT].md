# [PUT] /api/v2/configurations/

Sets the value of these configurations:
- EM_OperatingMode
- NVM_PfcFixedCosPhi
- NVM_PfcIsFixedCosPhiActive
- NVM_PfcIsFixedCosPhiLagging
- EM_ToU_Schedule

The operating mode (**EM_OperatingMode**) can not be changed if VPP is active

Example:
- curl -X PUT -d NVM_PfcFixedCosPhi=1 --header 'Auth-Token: TOKEN' http://SYSTEM-IP/api/v2/configurations
- curl -X PUT -d NVM_PfcFixedCosPhi=1 -d NVM_PfcIsFixedCosPhiActive=0 --header 'Auth-Token: TOKEN' http://SYSTEM-IP/api/v2/configurations

## Responses
| Code | Sample-Output |
| ------------ | :------------: |
| 200 | ``` true ``` |
| 401 | ``` 401 Unauthorized ``` |

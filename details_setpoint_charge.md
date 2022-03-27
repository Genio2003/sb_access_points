# setpoint/charge/{watt}

The charging power of a storage system can be controlled by setting a setpoint in watts. The corresponding value of the setpoint is kept until the battery receives a new charging or discharging value.
If VPP is active, the request will be rejected.

## Parameters
| Name | Description |
| :------------: | :------------: |
| watt (integer) | For example: 2000 |

## Responses
| Code | Sample-Output |
| ------------ | :------------: |
| 200 | ``` true ``` |
| 401 | ``` 401 Unauthorized ``` |

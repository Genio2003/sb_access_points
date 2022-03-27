# Sample-Output

Gets latest data for this sonnenBatterie.

``` json
{
  "Consumption_W": 0,
  "FullChargeCapacity": 0,
  "GridFeedIn_W": 0,
  "Pac_total_W": 0,
  "Production_W": 0,
  "RSOC": 0,
  "SetPoint_W": 0,
  "Timestamp": "2019-09-19 15:07:19",
  "USOC": 0,
  "UTC_Offet": 2,
  "ic_status": {
    "DC Shutdown Reason": {
      "Critical BMS Alarm": false,
      "Error condition in BMS initialization": false,
      "HW_Shutdown": false,
      "HardWire Over Voltage": false,
      "HardWired Dry Signal A": false,
      "HardWired Under Voltage": false,
      "Initialization Timeout": false,
      "Initialization of AC contactor failed": false,
      "Initialization of BMS hardware failed": false,
      "Initialization of DC contactor failed": false,
      "Initialization of Inverter failed": false,
      "Invalid or no SystemType was set": false,
      "Inverter Over Temperature": false,
      "Inverter Under Voltage": false,
      "Manual shutdown by user": false,
      "Minimum rSOC of System reached": false,
      "No Setpoint received by HC": false,
      "Shutdown Timer started": false,
      "System Validation failed": false,
      "Voltage Monitor Changed": false
    },
    "Eclipse Led": {
      "Pulsing Green": false,
      "Pulsing Orange": true,
      "Pulsing White": false,
      "Solid Red": false
    },
    "Flat Status": {
      "Auto Mode": false,
      "Error": false,
      "Full Charge Power": false,
      "Full Discharge Power": false,
      "Not Connected": false,
      "Spare 1": false,
      "Spare 2": false,
      "Spare 3": false,
      "Timeout": false
    },
    "MISC Status Bits": {
      "Discharge not allowed": false,
      "Min System SOC": false,
      "Min User SOC": false
    },
    "Microgrid Status": {
      "Continious Power Violation": false,
      "Discharge Current Limit Violation": false,
      "Low Temperature": false,
      "Max System SOC": false,
      "Max User SOC": false,
      "Microgrid Enabled": false,
      "Min System SOC": false,
      "Min User SOC": false,
      "Over Charge Current": false,
      "Over Discharge Current": false,
      "Peak Power Violation": false,
      "Protect is activated": false,
      "Transition to Ongrid Pending": false
    },
    "Setpoint Priority": {
      "BMS": false,
      "Energy Manager": false,
      "Flat": false,
      "Full Charge Request": false,
      "Inverter": false,
      "Min User SOC": false,
      "Trickle Charge": false
    },
    "System Validation": {
      "Country Code Set status flag 1": false,
      "Country Code Set status flag 2": false,
      "Self test Error DC Wiring": false,
      "Self test Postponed": false,
      "Self test Precondition not met": false,
      "Self test Running": false,
      "Self test successful finished": false
    },
    "nrbatterymodules": 0,
    "secondssincefullcharge": 0,
    "statebms": "not ready",
    "statecorecontrolmodule": "config",
    "stateinverter": "not ready",
    "timestamp": "Thu Jan 1 01:00:00 1970"
  }
}
```
# Explanation of output-content

| Attribute | Unit | Details |
| --------- |:-------:|
| ... | ... | ... |

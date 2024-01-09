# Itho-daalderop-hru-400
ESPHOME config for HRU 400

To connect to the WTW unit you will need a modbus connection to a ESP device of choiche. 

## Automation
For the automation to work you will need to create 2 helpers in home assistant:

- `input_boolean.wtw_time_30`
- `input_boolean.wtw_time_60`

Icons: 
- `mdi:fast-forward-30`
- `mdi:fast-forward-60`


## Secrets:
you will need the following secrets, either create them in the `HRU-400.yaml` or place then in your secrets yaml:
- !secret lot_wifi_ssid
- !secret lot_wifi_password
- !secret wtw-fbw
- !secret wtw-api
- !secret wtw-ota

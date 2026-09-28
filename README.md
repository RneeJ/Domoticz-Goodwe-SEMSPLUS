# Domoticz-Goodwe-SEMSPLUS
Domoticz dzVents script for reading Goodwe inverter data en presenting them in Domoticz

This is a work in progress.

It is use-able but you need some knowledge of dzVents scripting and Domoticz.

Note on using this script :
- in case of using the same device (idx) numbers as the python plugin it is advised you set the python plugin only run once every day.
  You have to make a manual adaption in plugin.py  : around line 64 Mode2 : ``` <option label="24h" value="8640"/> ```
- Alternative : you can create new dummy devices.
- if you use other idx numbers your history data will break.

NO WARRANTY !!

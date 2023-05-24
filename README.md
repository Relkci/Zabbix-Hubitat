# Zabbix Hubitat Template
Zabbix Template for Hubitat Smart Home Hub
* https://hubitat.com/

# Pre-Requisite 
Requires use of Hubitat Marer API
* https://docs2.hubitat.com/en/apps/maker-api
- Add Maker API module to Hubitat
- Select devices you wish to monitor in Zabbix
- Copy the Access Token and Hubitat Maker API App ID.  These are found in the URL exampels provided by Maker API.


# Installation
- Import Zabbix-Hubitat Template into Zabbix (Zabbix Template)
- Create Zabbix host
- Set Hubitat host Agent IP Address = IP of Zabbix agent
- Link new Zabbix Template "Hubitat"
- Set Macros {$HUBITAT_ACCESS_TOKEN} and {$HUBITAT_APP_ID} respectively

| ![image](https://github.com/Relkci/Zabbix-Hubitat/assets/29710634/d29b5de0-6f38-4c64-9fab-0fd3dcef167a) |
|------------|

- The Macro values can be found in the Hubitat Maker API interface. 

| ![image](https://github.com/Relkci/Zabbix-Hubitat/assets/29710634/bb0ca81f-8558-4483-afa8-76dbc7348085) |
|-------------|

# Supported Devices
- The Hub itself
- The discovery API pulls in attributes for thermostats and standard switches.  More attributes will be added as I monitor more device types.

# Items
- Hub Status and Alerts
- Devices via LLD

# Alerts
- Hub Load - Elevated / High / Severe 
- Zwave Offline / Crashed
- Zigbee Offline
- Low Memory
- Platform Update Available

| ![image](https://github.com/Relkci/Zabbix-Hubitat/assets/29710634/b671fd6d-5585-4379-9047-f2f298a210ca) | 
|----------------| 

# Screenshots

Thermostat Graph

Tempearture Hubmidity (Thermostat Device)
| ![image](https://github.com/Relkci/Zabbix-Hubitat/assets/29710634/1995c981-9a6c-4a7c-9906-741d419c11c7) |
|-------------|

Thermostat with Set Points
| ![image](https://github.com/Relkci/Zabbix-Hubitat/assets/29710634/f4a44f45-11ef-4230-99d7-aa555284aa51) |
|-------------|

Battery Graph
| ![image](https://github.com/Relkci/Zabbix-Hubitat/assets/29710634/0734007c-f0af-426e-9f7e-0881fc374fab) |
|--------------|

Hubitat Alerts 
| ![image](https://github.com/Relkci/Zabbix-Hubitat/assets/29710634/47560895-e9b6-49d7-b1c4-8a716a7ddb1d) |
|--------------|



# Contact
Twitter: @KRelkci
GitHub: @Relkci


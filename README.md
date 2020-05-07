Nalfam Cisco Network Manager is an app that imitates real life scenario in which you would have an admin that would control all the devices connected to network, we were trying to do something similar. Network is mimicking devices that are connected to network, and server is storing data and making sure all the devices are unique.
Server is mainly storying Download/Upload speed and time, we wanted to start with that as it was nice amount of data to show on the front end. 


You need nalfam01 nalfam02 nalfam03 to run app.

NETWORK

# Activate venv
```
$ pipenv shell
```
# Install dependencies
```
pipenv install

python initdb.py

python app.py
```

SERVER

# Activate venv
```
$ pipenv shell
```
# Install dependencies
```
pipenv install

python initdb.py

python app.py
```
NETWORKING PANEL
```
npm install
npm start
```

To deactivate shell type 
```
deactivate
```
Then we have to populate network through Postman to mimic real life scenario.
```
{
"host_name": "RT1",
"device_type": "Router",
"operating_system": "Cisco IOS",
"mac_address": "00:1B:44:11:3A:B7",
"ip_address": "172.16.101.1",
"upload_speed": 80,
"download_speed": 100,
"active_connection": true
},
{
"host_name": "SW1",
"device_type": "Switch",
"operating_system": "Cisco IOS",
"mac_address": "00:1B:44:11:5R:B8",
"ip_address": "172.16.101.2",
"upload_speed": 80,
"download_speed": 100,
"active_connection": true
},
{
"host_name": "WorkStation_01",
"device_type": "Desktop PC",
"operating_system": "Ubuntu",
"mac_address": "00:1B:54:18:3A:A2",
"ip_address": "192.168.100.23",
"upload_speed": 20,
"download_speed": 80,
"active_connection": true
},
{
"host_name": "WorkStation_02",
"device_type": "Desktop PC",
"operating_system": "Ubuntu",
"mac_address": "20:5B:74:19:5A:C7",
"ip_address": "192.168.100.24",
"upload_speed": 15,
"download_speed": 75,
"active_connection": true
},
{
"host_name": "WorkStation_03",
"device_type": "Desktop PC",
"operating_system": "OSx",
"mac_address": "31:6B:84:18:GA:A2",
"ip_address": "192.168.100.25",
"upload_speed": 21,
"download_speed": 80,
"active_connection": true
},
{
"host_name": "WorkStation_04",
"device_type": "Desktop PC",
"operating_system": "OSx",
"mac_address": "20:CB:21:10:BA:C7",
"ip_address": "192.168.100.26",
"upload_speed": 15,
"download_speed": 80,
"active_connection": true
},
{
"host_name": "WorkStation_05",
"device_type": "Laptop",
"operating_system": "OSx",
"mac_address": "41:7B:04:78:9A:A2",
"ip_address": "192.168.100.27",
"upload_speed": 20,
"download_speed": 80,
"active_connection": true
},
{
"host_name": "WorkStation_06",
"device_type": "Laptop",
"operating_system": "OSx",
"mac_address": "00:0B:04:19:6D:C7",
"ip_address": "192.168.100.28",
"upload_speed": 15,
"download_speed": 75,
"active_connection": true
},
{
"host_name": "WorkStation_07",
"device_type": "Laptop",
"operating_system": "OSx",
"mac_address": "31:7B:84:19:GA:B2",
"ip_address": "192.168.100.29",
"upload_speed": 21,
"download_speed": 80,
"active_connection": true
},
{
"host_name": "WorkStation_08",
"device_type": "Laptop",
"operating_system": "OSx",
"mac_address": "52:C6:45:B0:BA:C8",
"ip_address": "192.168.100.30",
"upload_speed": 15,
"download_speed": 80,
"active_connection": true
},
{
"host_name": "Alan's Phone",
"device_type": "Mobile Phone",
"operating_system": "Android",
"mac_address": "22:4B:54:39:GB:B3",
"ip_address": "192.168.200.1",
"upload_speed": 10,
"download_speed": 50,
"active_connection": true
},
{
"host_name": "Nick's Phone",
"device_type": "Desk Phone",
"operating_system": "Android",
"mac_address": "52:56:41:C6:BA:C9",
"ip_address": "192.168.200.2",
"upload_speed": 10,
"download_speed": 50,
"active_connection": true
}
```

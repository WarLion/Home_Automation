# Home Automation using Domoticz, motionEye and ESP8266

## Main Features:
  - Smart electrical heating management using existing basic heaters
  - Detailed energy monitoring. House thermal characteristics computation
  - Legacy wired alarm appliance go to Internet
  - Cameras and motion detection with motionEye. End to end communication between motionEye and Domoticz 
  - Ligthing management reusing existing latching relays and wall pushbuttons
  - Robust implementation with two Domoticz synchronized servers (failover cluster) and alerting on sensors/actuators failure 

## Architecture:
  - Domoticz High Availability Cluster : Synology Dz V3.5877 (Main) - Raspberry Dz V4.97 (Backup) - Node.js scripts
  - Alarm server : Raspberry - motionEye - iot_ALARM-SVR Node.js script
  - Sensors/Actuators : ESP8266 (Electrodragon IoT ESP8266 Relay Board and standalone ESP-12E) - Arduino sketches
  - Communication protocol : MQTT

## Forum topics about:
  - http://www.domoticz.com/forum/viewtopic.php?f=38&t=17032

  - http://www.domoticz.com/forum/viewtopic.php?f=38&t=21608

  - http://www.domoticz.com/forum/viewtopic.php?f=38&t=22436

  - http://www.domoticz.com/forum/viewtopic.php?f=38&t=23914

  - https://easydomoticz.com/forum/viewtopic.php?f=21&t=4798

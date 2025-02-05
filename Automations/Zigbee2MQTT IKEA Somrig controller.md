##  🔵 Zigbee2MQTT IKEA Somrig controller
It only works with: [Z2M](https://github.com/zigbee2mqtt/hassio-zigbee2mqtt#installation)

[Requires addons to be installed]([MQTT](https://www.home-assistant.io/integrations/mqtt)
    + [Z2M addon](https://www.zigbee2mqtt.io/guide/installation/03_ha_addon.html)).

## ⚠️The following actions can be triggered using this blueprint:
    - Press the **one dot** or **two dots** buttons

    - Double press the **one dot** or **two dost** buttons.

    - Press and hold the **one dot** or **two dots** buttons. 
   
    - **Helper - Hold delay**, Delay between the execution of the Hold action(s). 
  
    - **Helper - Max number of loops** Maximum number of loops when holding down a button. 


[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://gist.github.com/Bearstorm/eb7565573c76c082bdc4729e6cc3c0c8)

## :bulb: It is necessary to enter the name of the controlled device from MQTT into Blueprint
## MQTT
![MQTT name 1](https://github.com/user-attachments/assets/84141df1-2252-4487-8b94-128c0cd2154e)


## BLUEPRINT
![MQTT name ](https://github.com/user-attachments/assets/9fe87485-5192-4d8b-a1fd-74cf743bfb3e)



💡Adapted from https://gist.github.com/damru/b2c1c780ffb0ddc084952eb89db9573a

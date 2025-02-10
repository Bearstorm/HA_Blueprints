##  🔵 Zigbee2MQTT IKEA Somrig controller
Works with: [Z2M](https://www.zigbee2mqtt.io) and [ZHA](https://www.home-assistant.io/integrations/zha)

[Requires addons to be installed]([MQTT](https://www.home-assistant.io/integrations/mqtt)
    + [Z2M addon](https://www.zigbee2mqtt.io/guide/installation/03_ha_addon.html)) or [ZHA](https://www.home-assistant.io/integrations/zha).

## ⚠️The following actions can be triggered using this blueprint:
    - Press the **one dot** or **two dots** buttons

    - Double press the **one dot** or **two dost** buttons.

    - Press and hold the **one dot** or **two dots** buttons. 
   
    - **Helper - Hold delay**, Delay between the execution of the Hold action(s). 
  
    - **Helper - Max number of loops** Maximum number of loops when holding down a button. 


[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://gist.github.com/Bearstorm/0cb9d90b68e6f8df6f5313cdf13aacef#file-z2m-zha-ikea_somrig-controller-_v1-2-yaml)

## :bulb: It is necessary to enter the name of the controlled device from MQTT into Blueprint

## The schedule has a device controller search box that only shows IKEA SOMRIG E2213 devices.

![Automat SOMRIG](https://github.com/user-attachments/assets/8c9e0822-45c4-4362-bff9-630ae746ec30)


## - Press the **one dot** or **two dots** buttons

## - Double press the **one dot** or **two dost** buttons.

## - Press and hold the **one dot** or **two dots** buttons.

![dots](https://github.com/user-attachments/assets/399c6dbc-ee8d-4375-a471-e29fe79ac7b5)

## Helper

![helper](https://github.com/user-attachments/assets/8a23d865-1238-4fd9-95e0-a54f47aab5da)

✔ ❌ Older version v1.0 without automatic search for all IKEA SOMRIG devices  [here](https://gist.github.com/Bearstorm/eb7565573c76c082bdc4729e6cc3c0c8).

✔ ❌ Older version v1.1 with automatic search for all IKEA SOMRIG devices. [here](https://gist.github.com/Bearstorm/0cb9d90b68e6f8df6f5313cdf13aacef).

💡Adapted from https://gist.github.com/damru/b2c1c780ffb0ddc084952eb89db9573a
